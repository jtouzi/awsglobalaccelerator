# AWS Global Accelerator
This repository contains instructions and blueprints for AWS Global Accelerator Workshop


## Overview

In this workshop you will learn how to host an application in multiple AWS regions using [AWS Global Accelerator]( https://aws.amazon.com/global-accelerator/).

The workshop demonstrates the usage of the following AWS services:
* **Amazon EC2**: Host your example application in multiple regions. 
* **Amazon ALB**: Loadbalance your application cross multiple AZ's within the region
* **Amazon DynamoDB Global Tables**: the dynamic data will be stored in a DynamoDB global table, span acorss regions 
* **Amazon Global Accelerator**: Improve global application availability and performance using the AWS global network
* **AWS Lambda**: the dynamic content generation and content customization will be driven by Lambda functions


## Lab 0 - Launch the Stack

To start the workshop, launch the CloudFormation stack to bootstrap the resources in the US West (Oregon) Region.

Click the launch stack button below to kick it off, accept all default values and wait for CloudFormation to complete the creation of the stack.

If you need more detailed instructions please have a look at the screenshots in following link.

[Lab 0 - Launch the stack with (steps screenshots)](./Lab0_LaunchTheStack/Readme.md)

The CloudFormation stack will create several AWS resources for this workshop, including EC2 instances, LaunchConfig, Security Groups for both instances and ALBs, ALB in the region you would like your applications running. 

You can see all resources created by the CloudFormation stack in [AWS CloudFormation Console](https://console.aws.amazon.com/cloudformation/home?region=us-west-2).


## Lab 1 - Creating Global Accelrator 

[Lab1 - Create GA](Step by Step screenshots)(./Lab1_CreatingGA/Readme.md)



## Lab 2 - Application with Multi-Player Game with UDP 
## Lab 3 - Application with DNS Hosting 


This library is licensed under the Apache 2.0 License. 
