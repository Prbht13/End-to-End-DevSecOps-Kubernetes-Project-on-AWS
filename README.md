# DevOps Implementation on MERN Stack Application
# 🚀 End-to-End Kubernetes Three Tier DevSecOps Project

## 📌 Project Objective
A fully automated and secure three-tier application deployed on Kubernetes using DevSecOps practices.

## 🧱 Project Architecture

![Architecture Diagram](images/architecture.png)

## 🧰 Tech Stack

- 🐳 Docker
- ☸️ Kubernetes
- 🔧 Jenkins
- 🛡️ SonarQube
- 🧪 Trivy
- 📦 Nexus
- 🔐 Vault
- 🐘 PostgreSQL
- 🌐 Nginx

## 🧵 CI/CD Workflow

```mermaid
graph TD;
    Dev[Developer Push Code] --> Jenkins;
    Jenkins --> SonarQube;
    Jenkins --> Trivy;
    Jenkins --> Nexus;
    Nexus --> Kubernetes;
