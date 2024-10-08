# Building a CI/CD pipeline for a Microservices-Based Web Application on local system and AWS

### 👋 Welcome to my organization!!!

This is my project that contains repositories collectively support the architecture and implementation of a CI/CD pipeline for deploying and monitoring microservices application.<br>

**About the project**: This CI/CD pipeline automates the development, testing, and deployment of a microservices application across development, staging, and production environments. The process starts with Jenkins triggering a pipeline on code changes, which builds and packages artifacts. In the development environment, Docker Compose is used for deployment, with Trivy scanning Docker images for security. For staging, Kubernetes is set up with `kubeadm`, Terraform, and Ansible on AWS, and Jenkins deploys the application for testing. In production, Jenkins deploys to EKS, using GitHub Actions and Helm to set up Prometheus and Grafana for monitoring.

<br>

<p align="center">
    <img src="../images/cicd-pipeline-architecture.png" alt="CI/CD pipeline architecture"></img>
</p>

## 📥 Repositories

### 1. [class-management](https://github.com/NT114-O21-DACN-DevOps/class-management)
👉 This repository contains the source code for a microservices application, including front-end and back-end services.

### 2. [class-management-terraform-ansible](https://github.com/NT114-O21-DACN-DevOps/class-management-terraform-ansible)
👉 This repository contains Terraform and Ansible configurations for setting up a Kubernetes cluster.

### 3. [class-management-k8s-config](https://github.com/NT114-O21-DACN-DevOps/class-management-k8s-config)
👉 This repository holds Kubernetes configuration files for deploying the application to staging and production environments.

### 4. [class-management-EKS-monitoring](https://github.com/NT114-O21-DACN-DevOps/class-management-EKS-monitoring)
👉 This repository contains files for setting up monitoring on an EKS cluster.

****

💡**For detailed instructions on each repository, please refer to their individual README files.**

