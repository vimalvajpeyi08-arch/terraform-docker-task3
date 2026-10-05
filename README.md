# Task 3: Infrastructure as Code (IaC) with Terraform & Docker

This project demonstrates how to provision and manage a local Docker container using Terraform.

## Tools Used
- **Terraform** (v1.16+)
- **Docker Desktop**

## Steps Followed
1. `terraform init` - Initializes the working directory and downloads the Docker provider.
2. `terraform plan` - Previews the execution plan.
3. `terraform apply` - Provisions the Nginx Docker container locally on port `8081`.
4. `terraform state list` - Inspects the current state of managed resources.
5. `terraform destroy` - Cleans up and removes the infrastructure.
