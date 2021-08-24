# Learn Terraform AWS Instance
Use terraform to provision and deploy EC2 instance to AWS

## Pre-requisite
- AWS account
- AWS CLI

## Steps
```
# Initialize the project which install the provider defined in the configuration - aws
terraform init

# Format your configuration - prettify
terraform fmt

# Validate configuration
terraform validate

# Deploy
terraform apply

# Check state
terraform show

```