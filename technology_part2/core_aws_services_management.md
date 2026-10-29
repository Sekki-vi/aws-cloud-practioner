# Management

# How do we create AWS services
- Cloudformation: creates services automatically by telling it what you need
- give cloudformation a file of what services you need

# How to install software on them?
- AWS OpsWorks: installs software into systems (vms or containers)

# How do I install all of these servers and all these services?
- Systems Manager: configures services created by cloudformation and OpsWorks

# How do I manage all of my AWS accounts as if they are one account?
- AWS Organizations is used to centrally govern and manage multiple accounts

# How do I offer my AWS services to my employees like AWS was a vending machine?
- AWS Service Catalog: allows employees to request services

# How do I manage multiple accounts using Organizations in a best practice way?
- Control Tower: a service that helps you set up AWS organizations in a secure best practice, with auditing, logging, and compliance rules in place

# How do I manage and audit my accounts for malicious activity and track changes?
- AWS Config: is used to record and evaluate all configuration changes in your AWS services
- Cloudtrail: tracks and records all user and API activity in your AWS account