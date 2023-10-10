# Simple Terraform code for Amazon AWS VPC,EC2,SG, Public/Private Subnets

This Terraform module creates:

* Amazon AWS VPC
* Public Subent with Internet Gateway
* Private Subnet with NAT Gateway
* EC2 instance in Public Subnet
* Security Group that allow ssh from anywhere
* Public IP output to get the Public IP of EC2 Instance

# Prerequisite 
* Take help to configure your AWS Credentials [here](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html)

```
terraform init
terraform plan
terraform apply --auto-approve=true 
terraform destroy --auto-approve=true 
```
# Attention Please
**terraform.lock.hcl** in your version control ensures that all team members and your deployment systems use the exact same provider versions. 
