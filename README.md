# confluent-aws-workshop

This repo includes a Cloudformation template for [Introduction to Building Data in Motion applications with Confluent on AWS](https://confluent.awsworkshop.io/) workshop. The template creates all the neceasary AWS resources for the workshop to work. This is an updated version of the cfn template included in workshop. 

The following changes were made:

1. Added prefix parameter to be used as a prefix to some of the resources on AWS. This allows multiple deployments in the same AWS region.
2. Added email parameter to be used in resources that support tags.

The template only works for us-east-2. For it to work with us-east-1 and us-west-2, change the DBSnapshotIdentifier value to the correct one for the region.
