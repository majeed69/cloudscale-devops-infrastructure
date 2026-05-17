# CloudScale DevOps Infrastructure on AWS

A full-stack cloud-native DevOps project built on AWS using Docker, Nginx, PostgreSQL, Node.js, GitHub Actions CI/CD, and Application Load Balancer (ALB).

This project demonstrates real-world DevOps concepts including containerization, reverse proxy configuration, CI/CD automation, cloud deployment, load balancing, persistent storage, and full-stack authentication architecture.

---

# 🚀 Features

* Full-stack authentication system
* Frontend login interface
* Backend authentication API using Node.js and Express.js
* PostgreSQL database integration
* Persistent database storage using Docker Volumes
* Dockerized multi-container architecture
* Nginx reverse proxy with path-based routing
* GitHub Actions CI/CD pipeline
* AWS EC2 deployment
* AWS Application Load Balancer (ALB)
* Health checks and traffic routing
* Linux server administration

---

# 🏗️ Architecture

User → AWS ALB → Nginx Reverse Proxy → Frontend → Backend API → PostgreSQL Database

---

# 🛠️ Technologies Used

* AWS EC2
* AWS Application Load Balancer (ALB)
* Docker
* Docker Compose
* Nginx
* PostgreSQL
* Node.js
* Express.js
* GitHub Actions
* Git
* Linux (Ubuntu)
* CI/CD

---

# 🚀 Project Structure

cloudscale-devops-infrastructure/

├── backend/

├── monitoring/

├── portfolio/

├── docker-compose.yml

├── README.md

└── .github/workflows/

---

# 🔐 Authentication

The project includes a fully functional authentication system:

* Frontend Login Page
* Backend API Validation
* PostgreSQL Database Verification
* Success and Invalid Credential Handling

---

# 🚀 CI/CD Workflow

1. Code pushed to GitHub
2. GitHub Actions pipeline triggered
3. Application deployed to AWS EC2
4. Docker containers rebuilt and restarted
5. Updated application served through Nginx and ALB

---

# 📦 Docker Services

* Frontend Container
* Backend API Container
* PostgreSQL Database Container

---

# 💾 Persistent Storage

PostgreSQL database persistence is configured using Docker Volumes to prevent data loss during container restarts.

---

# 🧠 Key DevOps Concepts Demonstrated

* Infrastructure Deployment
* Containerization
* Reverse Proxy Configuration
* CI/CD Automation
* Load Balancing
* Docker Networking
* Persistent Volumes
* Linux Server Administration
* Application Debugging
* Cloud Architecture

---

# 🚀 Future Improvements

* HTTPS with SSL/TLS
* JWT Authentication
* Password Hashing
* Auto Scaling
* Prometheus & Grafana Monitoring
* Kubernetes Deployment
* Custom Domain Integration

---
