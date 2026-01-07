# ansible-ec2-deployment
Automated AWS EC2 infrastructure provisioning and application deployment using Ansible with roles, vault, and dynamic inventory.

## Features
- EC2 instance creation using Ansible
- Secure AWS credentials using Ansible Vault
- Public IP assignment and tagging
- Region-specific AMI handling
- Modular role-based structure

## Prerequisites
- Ansible
- Python 3
- boto3 & botocore
- AWS account
- IAM user with EC2 permissions

## Setup

1. Configure AWS credentials using Ansible Vault:
```bash
ansible-vault create vault.yml

step 2
Install required Python libraries:

**pip install boto3 botocore **

step 3
Run the playbook:
ansible-playbook -i inventory/inventory.ini ec2_create.yaml --vault-password-file vault.pass

Technologies Used

Ansible

AWS EC2

IAM

Python

Ansible Vault
