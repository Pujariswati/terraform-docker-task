# Task 3: Infrastructure as Code (IaC) with Terraform – Docker Provisioning

## 🚀 Objective
Provision a local Docker container running the **NGINX** web server using Terraform.

## 🛠️ Tools & Technologies Used
- Terraform
- Docker
- Windows 10/11 with Docker Desktop

## 📁 Project Structure


## 📜 Description

This project demonstrates how to use Terraform to:
- Use the Docker provider
- Pull the latest NGINX image from Docker Hub
- Launch a container mapped to port `8080` on localhost

## ⚙️ How to Use

### 1️⃣ Prerequisites
- Docker Desktop installed and running
- Terraform installed and added to PATH
- Internet connection to pull Docker image

### 2️⃣ Initialize Terraform

```bash
terraform init
