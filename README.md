# 🚀 Automated CI/CD Pipeline for Web Server Deployment

![CI/CD](https://img.shields.io/badge/CI%2FCD-Automated-success)
![Jenkins](https://img.shields.io/badge/Jenkins-Pipeline-red)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![GitHub](https://img.shields.io/badge/GitHub-Webhooks-black)
![Status](https://img.shields.io/badge/Build-Success-brightgreen)

## 📖 Introduction

In modern software development, manual deployment processes are time-consuming, error-prone, and difficult to scale. DevOps practices aim to solve these challenges by automating the build, test, and deployment lifecycle using Continuous Integration and Continuous Deployment (CI/CD).

This project focuses on implementing a real-world CI/CD pipeline using Jenkins, Docker, and AWS EC2. The goal is to automate application deployment such that any change pushed to the GitHub repository is automatically built and deployed without manual intervention.





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
```

## 📸 Project Screenshots

### 🔹 AWS EC2 Instance Setup
![EC2 Machine](screenshots/ec2-machine.png)

### 🔹 Jenkins Installation and Homepage
![Jenkins Installation Success](screenshots/jenkins-homepage.png)

### 🔹 Jenkins Pipeline Execution
![Pipeline Success](screenshots/jenkins-build.png)

### 🔹 CI/CD Website Before Automation
![Website Before Automation](screenshots/before-automation.png)

### 🔹 GitHub Webhook Configuration
![Webhook Configuration](screenshots/webhook-config.png)

### 🔹 Live Website Deployment
![Live Website](screenshots/after-final-automation.png)

```




