# 🚀 AWS Jenkins CI/CD Pipeline

Production-style CI/CD pipeline built using AWS EC2, Jenkins, Maven, Docker, DockerHub, GitHub, and Jenkins Shared Libraries.

---

## 📌 Overview

This project demonstrates an automated CI/CD workflow for a Java Spring Boot application.

### Implemented Stages

- Git Checkout
- Maven Unit Testing
- Integration Testing
- Maven Build & Packaging
- Docker Image Build
- DockerHub Push
- Cleanup & Reporting

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|-------------|
| Cloud | AWS EC2 |
| CI/CD | Jenkins, Jenkins Shared Libraries |
| Build | Maven, JUnit |
| Containerization | Docker, DockerHub |
| Source Control | Git, GitHub |
| Operating System | Ubuntu Linux |

---

## 📐 Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
Jenkins Pipeline
    │
    ├── Git Checkout
    ├── Unit Testing
    ├── Integration Testing
    ├── Maven Build
    ├── Docker Build
    ├── DockerHub Push
    └── Cleanup
```

---

## 📷 Screenshots

### GitHub Repository Overview
![GitHub Repository](screenshots/01_github-repository-overview.jpg)

### Jenkins Pipeline Code
![Jenkinsfile](screenshots/02_jenkinsfile-pipeline-code.jpg)

### AWS EC2 Environment
![AWS](screenshots/03_aws-ec2-environment.jpg)

### Successful Pipeline Execution
![Pipeline Success](screenshots/05_successful-pipeline-run.jpg)

### DockerHub Published Image
![DockerHub](screenshots/07_dockerhub-image-published.jpg)

---

## 📊 Key Outcomes

- Automated CI/CD workflow using Jenkins
- Implemented Jenkins Shared Libraries
- Containerized application using Docker
- Published images to DockerHub
- Hosted pipeline infrastructure on AWS EC2

---

## 📂 Repository Structure

```text
AWS-Jenkins-DevSecOps-Pipeline
│
├── README.md
├── Jenkinsfile
├── Dockerfile
│
├── screenshots
│   ├── 01_github-repository-overview.jpg
│   ├── 02_jenkinsfile-pipeline-code.jpg
│   ├── 03_aws-ec2-environment.jpg
│   ├── 04_jenkins-stage-view.jpg
│   ├── 05_successful-pipeline-run.jpg
│   ├── 06_console-output-success.jpg
│   └── 07_dockerhub-image-published.jpg
│
└── Java_app_3.0
```

---

## 🚀 Future Enhancements

- SonarQube Integration
- Trivy Security Scanning
- Kubernetes Deployment
- Terraform Infrastructure Automation
- GitOps using ArgoCD
- JFrog Artifactory Integration
- Prometheus Monitoring
- Grafana Dashboards

---

## 🔗 Repositories

### CI/CD Pipeline Repository

https://github.com/pvenki8890/AWS-Jenkins-DevSecOps-Pipeline

### Application Repository

https://github.com/pvenki8890/Java_app_3.0

---

## 👨‍💻 Author

**Papisetti Venkatesh**

DevOps Engineer | Platform Engineer | Site Reliability Engineer (SRE) 

GitHub: https://github.com/pvenki8890

LinkedIn: https://www.linkedin.com/in/v-0b3699225/

---

⭐ If you found this project useful, consider giving it a star.
