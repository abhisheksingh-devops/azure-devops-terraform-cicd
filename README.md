# Azure DevOps CI/CD Pipeline with Terraform

## 📌 Project Overview

This project demonstrates how Terraform infrastructure deployment can be automated using an **Azure DevOps CI/CD pipeline**.

The pipeline automates the Terraform workflow from initialization and validation to planning and infrastructure deployment on Microsoft Azure.

## 🛠️ Technologies Used

* Microsoft Azure
* Terraform
* Azure DevOps
* Azure Pipelines
* Git
* GitHub
* CI/CD
* Infrastructure as Code (IaC)

## 🔄 CI/CD Workflow

```text
Developer
    ↓
Git Repository
    ↓
Azure DevOps Pipeline
    ↓
Terraform Init
    ↓
Terraform Validate
    ↓
Terraform Plan
    ↓
Terraform Apply
    ↓
Microsoft Azure
```

## 🚀 Pipeline Stages

### Terraform Init

Initializes the Terraform working directory and configures the remote backend.

### Terraform Validate

Checks the Terraform configuration for syntax and configuration errors.

### Terraform Plan

Creates an execution plan showing the infrastructure changes Terraform will make.

### Terraform Apply

Applies the approved Terraform plan and provisions infrastructure in Azure.

## 📂 Project Structure

```text
azure-devops-terraform-cicd/
│
├── README.md
├── azure-pipelines.yml
├── terraform/
│   ├── main.tf
│   ├── provider.tf
│   ├── variables.tf
│   └── outputs.tf
│
└── .gitignore
```

## 🔐 Azure Service Connection

An Azure DevOps service connection is used to authenticate the pipeline with Microsoft Azure.

The service connection keeps authentication details outside the source code.

## 🗄️ Remote Terraform State

Terraform state is stored remotely using an Azure Storage Account backend.

This helps maintain centralized and consistent Terraform state management.

## 🌿 Git Workflow

The project uses Git-based development practices.

Example workflow:

```text
feature branch
      ↓
Pull Request
      ↓
Code Review
      ↓
main branch
      ↓
Azure DevOps Pipeline
      ↓
Terraform Deployment
```

## 🎯 Key Learning

Through this project, I practiced:

* Azure DevOps CI/CD
* YAML pipelines
* Terraform automation
* Terraform Init / Plan / Apply
* Azure service connections
* Remote Terraform state
* Git branching
* Pull Requests
* Automated Azure infrastructure deployment

## 👨‍💻 Author

**Abhishek Singh**

DevOps Engineer | Azure | Terraform | CI/CD | Git | Linux

