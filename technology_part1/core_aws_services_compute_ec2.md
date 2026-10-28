# Compute

## Deploying an Application
- Find datacenter
- Purchase server
- Physically rack the server
- Install operating system
- Handle hardware failures

## Deploying an Application with AWS
- Just make EC2 servers

## EC2
- secure, resizable compute capacity in the cloud
- ec2 allows you to provision a server on AWS in minutes
- multiple ec2 instances can be deployed on a singler server using virtual machines
- VPCs are used to logically isolate each customer's infrastructure
- can specify the operating system

## Amazon Machine Image (AMI)
- the image that provides the information required to launch an ec2 instance
- info on OS and packages
- can use to deploy identical EC2 instances
- like an installer disk

## Instance Types
- ec2 provides a wide selection of instance types
- have varying combinations of cpu, memory, storage, and networking capacity
- different server models
- general purpose: balance and diverse
- compute optimized: compute-heavy applications
- memory optimized
- storage optimized
- accelerated computing

## EC2 pricing options
- on-demand pricing: pay by the hour
- spot pricing: aws offers spare compute capacity at discounted rates
- reserved pricing: a long term agreement that gives a discount if commited too