# ECS on VPC Terraform Setup

This repository contains Terraform code to deploy an AWS infrastructure with:

- A VPC having 2 public and 2 private subnets across two availability zones.
- An ECS cluster running a containerized application on Fargate.
- ECS tasks deployed only in the private subnets.
- An Application Load Balancer (ALB) in public subnets exposing the service.

---

## requirement 

- [Terraform](https://www.terraform.io/downloads) installed on your local machine. 

- An AWS account with permissions to create VPCs, ECS clusters, IAM roles, and related resources.
- AWS CLI configured locally with credentials (`aws configure`).

---

## How to Use

### 1. Clone the repository

```bash
git clone https://github.com/<your-github-username>/<repo-name>.git
cd <repo-name>
 There have some files
Initialize Terraform using
#terraform init For
Review what Terraform will create
#terraform plan
#terraform apply
To Delete infrastructure use
#terraform destroy

