# Terraform Docker NGINX Project 🚀

This project demonstrates how to use **Terraform** to provision a **Docker container** running **NGINX** on a local/EC2 machine.

## 📦 Tech Stack
- Terraform
- Docker
- NGINX
- EC2 (Ubuntu)

## 🛠️ What It Does
- Pulls the latest NGINX image from Docker Hub
- Creates and runs a container using Terraform
- Destroys resources using `terraform destroy`
- Tracks state and configuration through `main.tf`

## 📂 Files Included
- `main.tf` – Terraform configuration
- `.terraform.lock.hcl` – Lockfile for provider dependencies
- `README.md` – Project description

## 🔧 Commands Used

```bash
terraform init         # Initialize Terraform
terraform plan         # See what will be created
terraform apply        # Create the container
terraform destroy      # Clean everything up
![Screenshot 2025-04-13 223057](https://github.com/user-attachments/assets/48fcd074-c3f2-4e7e-81ba-fef1807435c8)
![Screenshot 2025-04-13 223002](https://github.com/user-attachments/assets/e6a3a9bf-becc-483c-a2c5-7b2d60b0b3b4)
