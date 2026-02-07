# 🚀 Automated CI/CD Pipeline for Web Server Deployment

![CI/CD](https://img.shields.io/badge/CI%2FCD-Automated-success)
![Jenkins](https://img.shields.io/badge/Jenkins-Pipeline-red)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![GitHub](https://img.shields.io/badge/GitHub-Webhooks-black)
![Status](https://img.shields.io/badge/Build-Success-brightgreen)

## 🏗️ System Architecture

```text
Developer
   |
   |  (git push)
   v
GitHub Repository
   |
   |  (Webhook Trigger)
   v
Jenkins CI/CD Pipeline
   |
   |  (Build Docker Image)
   v
Docker Container
   |
   |  (Deploy)
   v
AWS EC2 Web Server (Live Website)

## 📸 Project Screenshots

### 🔹 AWS EC2 Instance Setup
![EC2 Machine](screenshot/ec2-machine.png)

### 🔹 Jenkins Installation and Homepage
![Jenkins Installation Success](screenshot/jenkins-homepage.png)

### 🔹 Jenkins Pipeline Execution
![Pipeline Success](screenshot/jenkins-build.png)

### 🔹 CI/CD website before Automation
![Website deployed](screenshot/before-automation.png)

### 🔹 GitHub Webhook Configuration
![Webhook Configuration](screenshot/webhook-config.png)

### 🔹 Live Website Deployment
![Live Website](screenshot/after-final-automation.png)
