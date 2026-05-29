# Amazon EKS Infrastructure Automation using Terraform and GitHub Actions

## Project Overview

This project demonstrates automated provisioning of an Amazon EKS cluster using Terraform and GitHub Actions.

The goal is to automate infrastructure deployment using Infrastructure as Code and CI/CD best practices.

---

## Technologies Used

* AWS
* Terraform
* Amazon EKS
* GitHub Actions
* IAM
* VPC
* EC2
* Kubernetes

---

## Infrastructure Components

The Terraform code provisions:

### Networking

* VPC
* Public Subnets
* Private Subnets
* Internet Gateway
* NAT Gateway
* Route Tables

### Security

* IAM Roles
* Security Groups

### Kubernetes

* Amazon EKS Cluster
* Managed Node Groups

---

## CI/CD Workflow

GitHub Actions is configured to:

1. Validate Terraform Code
2. Initialize Terraform
3. Generate Terraform Plan
4. Apply Infrastructure Changes
5. Destroy Infrastructure When Required

---

## Project Structure

terraform/

├── backend.tf

├── providers.tf

├── variables.tf

├── vpc.tf

├── eks.tf

├── outputs.tf

├── versions.tf

---

## Deployment Flow

GitHub Push

↓

GitHub Actions

↓

Terraform Init

↓

Terraform Validate

↓

Terraform Plan

↓

Terraform Apply

↓

Amazon EKS Cluster Creation

---

## Key Features

* Infrastructure as Code
* Automated EKS Deployment
* Automated Terraform Validation
* Automated Terraform Planning
* Repeatable Infrastructure Builds
* Cloud Resource Management

---

## Learning Outcomes

* Terraform Fundamentals
* AWS Networking
* Amazon EKS Deployment
* GitHub Actions Workflows
* Infrastructure Automation
* Cloud Resource Provisioning

---

## Challenges Solved

* Terraform Backend Configuration
* AWS Authentication Configuration
* State Management
* EKS Node Group Deployment
* VPC Configuration
* GitHub Actions Workflow Troubleshooting

---

## Screenshots

Screenshots of Terraform execution, GitHub Actions workflows, and AWS resources are available in the screenshots folder.

---

## Author

Rohith Darnasi

Cloud | DevOps | Terraform | AWS | Kubernetes
