# AWS Bastion Host Setup using Terraform

This Terraform script sets up a **Bastion Host** to securely access a **Private Server** in AWS.

## Prerequisites
Before running this script, ensure you have:

- **Terraform** installed → [Download Terraform](https://developer.hashicorp.com/terraform/downloads)
- **AWS CLI** configured (`aws configure`)
- **SSH key pair** generated for Bastion & Private Server:

  ```bash
  ssh-keygen -t rsa -b 4096 -f bastion-key
  ssh-keygen -t rsa -b 4096 -f private-key
