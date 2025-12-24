🚀 AWS EKS CI/CD Pipeline using GitHub Actions
📌 Project Overview

This project demonstrates an end-to-end DevOps CI/CD pipeline using GitHub Actions to automatically build and deploy a Dockerized application on AWS EKS (Elastic Kubernetes Service).
The goal of this project is to show how modern cloud-native applications are deployed using containers and Kubernetes without using Jenkins.

🛠️ Technologies Used

GitHub Actions (CI/CD)

Docker

Kubernetes

AWS EKS

AWS EC2

AWS IAM

Docker Hub

YAML

🔁 Project Workflow

Developer pushes code to GitHub repository

GitHub Actions pipeline triggers automatically

Application is built into a Docker image

Docker image is pushed to Docker Hub

Kubernetes manifests are applied to AWS EKS

Application runs inside Kubernetes Pods

🧩 Architecture Flow
GitHub Repo
     ↓
GitHub Actions (CI)
     ↓
Docker Image Build
     ↓
Docker Hub
     ↓
AWS EKS (Kubernetes)
     ↓
Pods & Services

⚙️ CI/CD Pipeline Details

GitHub Actions workflow is defined using YAML

Pipeline automates:

Code checkout

Docker image build

Image push to Docker Hub

Deployment to Kubernetes cluster

No manual intervention required after code push

☸️ Kubernetes Components Used

Deployment – manages application pods

Service – exposes application

Pods – run the Docker containers

YAML files – define infrastructure and app configuration

🔐 AWS Services Used

EKS – managed Kubernetes cluster

EC2 – worker nodes

IAM – secure access and permissions

VPC – networking (default or custom)

✅ Key Learnings

How to build CI/CD pipelines using GitHub Actions

Docker image creation and management

Deploying applications on AWS EKS

Kubernetes deployment and service management

Real-world DevOps workflow without Jenkins

🎯 Use Case

Real-world DevOps project for resumes

Suitable for 8–14 LPA DevOps roles

Production-style cloud-native deployment

📌 Conclusion

This project follows DevOps best practices and demonstrates how organizations deploy scalable applications using GitHub Actions, Docker, Kubernetes, and AWS EKS. It is ideal for learning and showcasing modern DevOps skills.
