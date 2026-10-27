# AWS Networking

- when AWS was first concieved, an immediate issue arose. If multiple applicartions are deployed to AWS, can these applications interact with each other?
- solved by implementing private clouds or Virtual Private Cloud (VPC)

## VPC
- a secure, isolated network segment hosted within AWS
- VPC isolated computing resources from other computing resources available in the cloud
- gives customer full control of the networking in the cloud
-- subnetting (IP address)
-- routing (route tables)
-- firewalls (NACLs and Security groups)
-- gateways

## Multiple VPCs
- you can create one for different purposes such as development, staging, and production
- can segment clouds in own organization

## VPCs and Regions
- VPC acts as a network boundary
- VPC is specific to a region

## Subnets
- a group of IP adresses in your VPC
- you deploy VMs to specific subnets
- they exist in different availability zones
- can be public or private
- private is not exposed to the internet

## VPN (Virtual Private Network)
- can be used to connect physical data center to your VPC

## VPC
- every VPC has a range of IP addresses assigned to it called the CIDR block
- CIDR block defines the IP adresses that resources in the VPC can use
- the first 4 IP adresses of a subnet are reserved and cannot be used
-- Ex: 192.168.10.0-3
- the last address also cannot be used
-- Ex: 192.168.10.255

## VPC External Connectivity
- subnets when they are first created are private by default

## Internet Gateway
- allows subnets in a VPC to communicate with the Internet either direction

## NAT Gateway
- a connection must be initiated from within the VPC
- connect the internet gateway to the private subnet

## Virtual Private Gateway
- Uses a VPN to connect to services over the internet while remaining encrypted

## Direct Connect
- direct high speed link