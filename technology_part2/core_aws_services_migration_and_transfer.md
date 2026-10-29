# Migration and Transfer

## AWS Migration Hub
- allows you to centralize and see all migration you have in place via AWS services

## What methods are used to migrate
- Rehosting (lift-and-shift): just copy up to the cloud
- Replatforming (lift, tinker and shift): very minor changes like just changing the OS
- Refactoring (or Rearchitecting): change the application to be architectected with AWS services
- Repurchasing: just buy a license on AWS for the same software
- Retaining (do nothing): just keep the server in your tradional data center until you don't need it anymore
- Retiring: it just goes away

## What if you needed to move data to the AWS offline?

## The Snow Family
- snowball edge storage optimized: a suitcase that you plug into your network
- snowball edge compute optimized: portable VM
- snowmobile: a literal truck that pulls up and downloads all your data up to 100PB
- snowcone: small portable computer, stil very powerful

## Transfer online?

## The Transfer Family
- FTP: secure transfer to s3 or EFS
- AS2: send a recieve messages using s3 as backend using a2a protocol

## Other
- AWS DataSync: online service that automates and accelerates moving data between on premises and AWS Storage services

## What if you need to move Applications, Databases and whole racks of Servers to AWS?
- Application Discovery Service: tells you about the applications that you're migrating
- Application Migration Service: migrates the application
- Database Migration Service: Continually replicate database to AWS if you want
- Elastic Disaster Recovery: copies disks, tracks all the changes, and puts them in small ec2 instances. When you go live, it upsizes the instances
- Mainframe Modernization: get off legacy mainframe and run in modern AWS