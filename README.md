# confluent-aws-workshop

This repo includes the Cloudformation templates for [Introduction to Building Data in Motion applications with Confluent on AWS](https://confluent.awsworkshop.io/) workshop. Each template creates all the neceasary AWS resources for the workshop to work in a specific region. This is an updated version of the cfn template included in workshop. 

The following changes were made:

1. Added prefix parameter to be used as a prefix to some of the resources on AWS. This allows multiple deployments in the same AWS region.
2. Added email parameter to be used in resources that support tags.

Like the workshop the templates only works with us-east-1, us-east-2 and us-west-2 AWS regions.
