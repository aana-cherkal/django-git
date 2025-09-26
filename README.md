# Django K8s CI/CD Project

## Description
This project demonstrates a full DevOps workflow for a Django application, including:
- Docker containerization
- Kubernetes deployment
- CI/CD pipelines with GitHub Actions and Jenkins
- Infrastructure as Code (IaC) using Terraform

## Features
- Dockerized Django application
- Kubernetes deployment on EC2 nodes
- Automated CI/CD pipelines
- Terraform provisioning for Docker container

## Project Structure
- `mysite/` – Django project files
- `Dockerfile` – Docker build instructions
- `main.tf` – Terraform configuration for Docker container
- `.github/workflows/` – GitHub Actions CI/CD workflows
- `tasks.md` – Documentation of Git workflow and task steps

## Getting Started
1. Clone the repository
2. Build and run the Docker container
3. Apply Terraform configuration for local Docker deployment
4. Deploy the app on Kubernetes using YAML manifests
5. Verify deployment via browser or curl

## Branches
- `main` – stable production-ready code
- `dev` – development branch for integration
- `feature/*` – feature-specific branches

## Author
Aahana Cherkal
