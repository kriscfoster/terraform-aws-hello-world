# terraform-aws-hello-world

Creates an AWS EC2 Instance with nginx.

## Prerequisites
- AWS Account.
- EC2 key pair created through AWS console.

## Flow
- `terraform init`
- `terraform plan -out module.tfplan`
- `terraform apply module.tfplan`
- `terraform destroy`
