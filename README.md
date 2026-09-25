# 🚀 DevOps CI/CD Project

A simple web application deployed using a complete DevOps CI/CD pipeline with GitHub, Jenkins, Docker, and AWS EC2.

## 📌 Project Overview

This project demonstrates how a web application can be automatically built and deployed whenever new code is pushed to GitHub.

The CI/CD pipeline is implemented using Jenkins and Docker, and the application is hosted on an AWS EC2 instance.

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript
- Git
- GitHub
- AWS EC2
- Linux
- Docker
- Jenkins
- GitHub Webhook

## 🏗️ Architecture

```text
Developer
    ↓
GitHub
    ↓
GitHub Webhook
    ↓
Jenkins
    ↓
Clone Repository
    ↓
Verify Files
    ↓
Docker Build
    ↓
Docker Container
    ↓
AWS EC2
    ↓
Live Website