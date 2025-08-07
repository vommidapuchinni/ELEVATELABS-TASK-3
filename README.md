# Task 3: Infrastructure as Code (IaC) with Terraform

## Objective:
Provision a local Docker container running NGINX using Terraform.

## Tools Used:
- Terraform
- Docker

## What I Did:
- Used the Docker provider in Terraform.
- Wrote Terraform configuration (`main.tf`) to:
  - Pull the latest `nginx` image.
  - Create and run a Docker container with port mapping (8080:80).
- Initialized Terraform using `terraform init`.
- Previewed the changes using `terraform plan`.
- Created the infrastructure using `terraform apply`.
- Verified container is running and accessible at `http://localhost:8080`.
- Destroyed the container using `terraform destroy`.

## Output:
NGINX container successfully provisioned and accessed via browser at:  
**http://localhost:8080**

# Documentation is provided in REPO
