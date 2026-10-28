# Lambda

## Deploying Aplication on AWS
- deploy EC2 so you have some compute power to run code
- grab AMI to configure
- connect with ssh
- secure with firewall
- copy code over to machine
- install dependencies
- set up config to scale

## Lambda makes it much easier
- just upload code and aws manages the server (serverless)
- will automatically pull instances from reserve instance pool when needed and put them back when not

## Use cases
- need to resize images in s3
- lambda can pull and resize and put them back in the bucket

## To run
- needs a function (just code)
- needs a trigger; something within aws that causes it to run (upload file s3, request to api gateway, dynamodb update)
- trigger is passed into the event argument of the function

## Benefits
- don't need to manage servers
- faster development
- only pay when function runs

## Downsides
- function can run for 15 minutes at most
- no local state
- cold start

## Pricing
- charged per function ran