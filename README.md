Terraform Task 3 – Infrastructure as Code (IaC) with Docker

Objective
Provision a local Docker container using Terraform to demonstrate Infrastructure as Code (IaC) principles.

Tools Used
- Terraform v1.12.2
- Docker Desktop

Steps Performed
1. Created a `main.tf` file using the Docker provider.
2. Defined resources for pulling the `nginx:latest` image and running a Docker container on port 8080.
3. Ran `terraform init` to initialize the project.
4. Used `terraform plan` to preview the changes.
5. Applied the infrastructure with `terraform apply`.
6. Verified that nginx was running on [http://localhost:8080](http://localhost:8080)
7. 7. Cleaned up resources using `terraform destroy`.
8. Checked Terraform-managed resources using `terraform state list`.

Outcome
This task helped me understand the concept of Infrastructure as Code and how to automate local Docker container provisioning using Terraform.
