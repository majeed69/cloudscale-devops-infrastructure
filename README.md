# CloudScale DevOps Infrastructure on AWS

Production-style DevOps infrastructure project built using AWS, Docker, Nginx, GitHub Actions, and Application Load Balancer (ALB).

---

## 🚀 Project Overview

CloudScale is a cloud-native DevOps infrastructure project demonstrating modern deployment practices, CI/CD automation, reverse proxy architecture, Docker containerization, and AWS load balancing.

The project simulates a production-ready multi-service architecture using AWS EC2, Docker containers, Nginx reverse proxy, and GitHub Actions for automated deployments.

---

## 🏗️ Architecture

Users
↓
AWS Application Load Balancer (ALB)
↓
Nginx Reverse Proxy
↓
Docker Containers
├── Portfolio Service
└── Monitoring Service

---

## ⚡ Features

- AWS EC2 Deployment
- Docker Containerization
- Nginx Reverse Proxy
- Path-Based Routing
- GitHub Actions CI/CD
- Application Load Balancer (ALB)
- Health Checks & Target Groups
- Automated Deployment Pipeline
- Multi-Service Architecture
- Linux Server Administration

---

## 🛠️ Technologies Used

### Cloud
- AWS EC2
- AWS Application Load Balancer
- AWS Target Groups
- AWS Security Groups

### DevOps
- Git
- GitHub
- GitHub Actions
- CI/CD Pipelines

### Containers
- Docker
- Docker Images
- Docker Containers

### Web & Networking
- Nginx
- Reverse Proxy
- Path-Based Routing
- HTTP Networking

### Operating System
- Ubuntu Linux

---

## 🚀 Deployment Workflow

1. Developer pushes code to GitHub
2. GitHub Actions triggers CI/CD pipeline
3. Workflow connects to AWS EC2 using SSH
4. Updated code is deployed automatically
5. Docker containers serve applications
6. Nginx routes traffic to services
7. AWS ALB distributes incoming traffic

---

## 🌐 Services

- /portfolio → Portfolio Service
- /monitoring → Monitoring Service

---

## 🎯 Learning Outcomes

This project helped strengthen practical knowledge of:

- AWS Cloud Infrastructure
- Linux Administration
- Docker Containerization
- Reverse Proxy Architecture
- CI/CD Automation
- GitHub Actions
- Load Balancing
- Cloud Networking
- DevOps Best Practices

---
