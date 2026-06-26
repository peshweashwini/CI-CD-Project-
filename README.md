# CI-CD-Project-
Enterprise CI/CD Pipeline using Azure DevOps, Docker &amp; AKS
# Enterprise Azure DevOps CI/CD Pipeline POC

## Overview

This project demonstrates an enterprise-grade CI/CD pipeline using Azure DevOps for building, testing, securing, containerizing, and deploying a Spring Boot application to Azure Kubernetes Service (AKS).

## Tech Stack

- Azure Repos
- Azure Pipelines
- Maven
- SonarQube
- Docker
- Trivy
- Azure Container Registry (ACR)
- Azure Kubernetes Service (AKS)
- Helm
- Azure Key Vault
- Azure Monitor
- Prometheus
- Grafana

## Pipeline Flow

Developer
↓
Azure Repos
↓
Pull Request
↓
CI Pipeline
↓
Build
↓
Unit Test
↓
SonarQube
↓
Docker Build
↓
Trivy Scan
↓
Push to ACR
↓
CD Pipeline
↓
Deploy to AKS
↓
Smoke Test
↓
Production

## Project Goals

- Enterprise CI Pipeline
- Enterprise CD Pipeline
- Secure Secret Management
- Infrastructure as Code
- Automated Deployments
- Monitoring
- Rollback Strategy

Branching :
main
develop
feature/ci-pipeline
feature/docker
feature/helm
feature/aks
feature/acr
feature/keyvault
feature/monitoring
feature/rollback

## Status
this is how our 
azure-devops-aks-cicd-poc/
│
├── app/
├── azure-pipelines/
│   ├── ci-pipeline.yml
│   ├── cd-pipeline.yml
│   └── templates/
├── kubernetes/
├── helm/
├── scripts/
├── docs/
└── README.md
🚧 Work in Progress
