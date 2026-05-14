# Christopher Hejduk — DevOps Engineer

![DevOps](https://img.shields.io/badge/Role-DevOps%20Engineer-0A66C2)
![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?logo=amazonaws)
![Terraform](https://img.shields.io/badge/IaC-Terraform-7B42BC?logo=terraform)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-EKS-326CE5?logo=kubernetes)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?logo=githubactions)
![Status](https://img.shields.io/badge/Portfolio-Active-success)

> Cloud infrastructure engineer focused on AWS, Terraform, Docker,
> Kubernetes, and security-first design.

---

## Skills

`Terraform` `AWS` `EC2` `VPC` `IAM` `Security Groups` `Docker` `CI/CD`
`GitHub Actions` `Kubernetes` `EKS` `ECR` `eksctl` `kubectl`
`Python` `Flask` `Linux` `Git` `PowerShell` `SSH`

---

## Projects

---

### 01 — [Terraform AWS EC2 Infrastructure](https://github.com/PowershellWarrior/terraform-aws-ec2-infra)

![Terraform](https://img.shields.io/badge/Terraform-1.x-7B42BC?logo=terraform)
![AWS](https://img.shields.io/badge/AWS-Free%20Tier-FF9900?logo=amazonaws)

Provisions a complete AWS environment — VPC, subnet, Internet Gateway,
security group, and EC2 instance — using Terraform as Infrastructure as Code.

**Highlights:**
- SSH restricted to single IP via `/32` CIDR — not open to `0.0.0.0/0`
- Custom VPC — never the insecure AWS default
- Dynamic AMI lookup — no hardcoded image IDs
- Fully parameterized — `main.tf` never edited directly

---

### 02 — [Flask Docker CI/CD Pipeline](https://github.com/PowershellWarrior/flask-docker-cicd)

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?logo=githubactions)

Containerizes a Python Flask application using Docker and automates the
build and push process to Docker Hub via a GitHub Actions CI/CD pipeline
on every commit to main — zero manual steps.

**Highlights:**
- GitHub Actions pipeline triggers automatically on every push to main
- Docker image tagged with both `latest` and unique SHA per commit
- Credentials managed via GitHub Secrets — never hardcoded in pipeline
- `python:3.12-slim` base image — minimal attack surface and image size

---

### 03 — [Flask EKS Kubernetes Deployment](https://github.com/PowershellWarrior/flask-eks-project)

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python)
![Kubernetes](https://img.shields.io/badge/Kubernetes-EKS-326CE5?logo=kubernetes)
![AWS](https://img.shields.io/badge/AWS-ECR%20%7C%20EKS-FF9900?logo=amazonaws)

Deploys a containerized Flask application to a managed Kubernetes cluster
on AWS EKS — image stored privately in Amazon ECR and exposed publicly
via an AWS Elastic Load Balancer with zero manual console configuration.

**Highlights:**
- EKS cluster provisioned with eksctl — VPC, subnets, and IAM roles
  created automatically
- Docker image stored in private Amazon ECR — IAM authenticated,
  never public
- Kubernetes deployment runs 2 replicas — automatic pod restart
  on failure
- AWS Load Balancer provisioned automatically via Kubernetes
  Service manifest

---

## How These Projects ConnectProject 01 — Terraform    ← Provision the infrastructure
Project 02 — Docker CI/CD ← Containerize and automate deployments
Project 03 — EKS          ← Orchestrate containers at scale on AWS

> Together these three projects demonstrate a complete DevOps stack —
> from infrastructure provisioning to container orchestration —
> covering the most in demand skills in the DevOps market today.

---

## Connect

| | |
|---|---|
| GitHub | [github.com/PowershellWarrior](https://github.com/PowershellWarrior) |
| LinkedIn | [linkedin.com/in/chejduk](https://www.linkedin.com/in/chejduk/) |
| Email | chejduk12.email@gmail.com |

---

*Actively maintained — new projects added regularly.*
