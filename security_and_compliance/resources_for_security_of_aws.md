# Prevention

## AWS Web Application Firewall (WAF)
- protect web applications
- listens to incoming http requests and monitor them and make sure they aren't attacks
- define resource to monitor -> create inspection criteria -> action (block, allow)

## AWS Shield
- protects against ddos attacks
- detects and mitigates sophisticated Distributed Denial of Service attacks (DDoS)

## AWS Network Firewall
- VPC used to isolated resources from other resources
- stateful firewall to protecrt traffic entering and leaving VPC

# Detection

## AWS Inspector
- will scan workload for vulnerabilites and undesired network exposure
- automatically discovers EC2 instances, container iamges in ECR, and lambda functions
- produces report when vulnerability is found
- re-runs scans whenever changes that could introduce new vulnerabilites are made: installing a new package, installing patch

## AWS GuardDuty
- detects threats with machine learning and anomaly detection to identify potential threats
- continuous monitoring
- review findings, integrate into event management, or trigger AWS lambda function for automated remediation

## Amazon Detective
- ingests data from VPC flow logs, Cloudtrail logs, and GuardDuty findings
- uses machine learning and statistical analysis to create advanced visualization that shows resource behaviors and interactions over time

## AWS Config
- tracks and audits the configuration of AWS resources over time

## AWS Security Hub
- automates security checks and brings security alerts into a central location
- takes findings from amazon inspector and GuardDuty
- performs validation against AWS/security best practices

## CloudTrail
- cloudtrail tracks user and API activity within an AWS account
- anytime a user performs an actions within AWS, an event is logged in CloudTrail: logging in, modifying security policies

## Security Lake
- collect security logs from multiple different sources
- aggregates in one place
- converts into storage and query-efficient parquet format

## AWS Macie
- uses pattern matching and machine learning to automatically discover sensitive data
- will generate an inventory report of S3 buckets and scan objects for sensitive data
- notify of all findings

# Management 

## Firewall Manager
- central place to manage firewall and security rules/policies
- works across all accounts

## Resource Access Manager
- allows sharing of resources across all accounts

## AWS Cognito
- add login and sign up functionality
- manages user credentials
- implements customer identity and access management for mobile and web applications

## IAM
- manages access to aws resources

## IAM Identity Center
- maanges sign in security in a central place

## Secrets Manager
- applications will need access to various credentials/secretss to perform a variety of tasks
- don't want to hardcode the credentials
- credentials can be stored and managed in AWS Secrets Manager
- dynamically pulls the secrets from the Secrets Manager
- automatic rotation scheduling for secrets

## AWS Certificate Manager (ACM)
- handles creating, storing, and renewing public/private certificates

## AWS Private Certificate Authority
- Easy way rto create a private CA to manage private certificates within an organization

## Key Management Service (KMS)
- create and manage all cryptographic keys

## Cloud Hardware Security Module (HSM)
- all keys are securely stored on the HSM and they never leave the device
