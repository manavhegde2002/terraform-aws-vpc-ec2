# Terraform AWS VPC and EC2 Infrastructure

## Project Overview

This project uses Terraform to provision AWS infrastructure from code.

The infrastructure includes a custom VPC, public subnet, Internet Gateway, route table, route, security group, and an Ubuntu EC2 instance.

## Architecture

Internet
   |
Internet Gateway
   |
Route Table
   |
Public Subnet
   |
Security Group
   |
EC2 Instance

## AWS Resources

- VPC
- Public Subnet
- Internet Gateway
- Route Table
- Route Table Association
- Route
- Security Group
- EC2 Instance
- Ubuntu AMI data source

## Terraform Concepts Practiced

- Terraform providers
- AWS resources
- Terraform data sources
- Resource dependencies
- Resource references
- Terraform state
- terraform init
- terraform validate
- terraform plan
- terraform apply
- terraform destroy
- Git and GitHub

## How to Run

```bash
terraform init
terraform validate
terraform plan
terraform apply
