# CI/CD Pipeline using Jenkins and Docker

## 📌 Overview
This project demonstrates a complete CI/CD pipeline where code changes pushed to GitHub automatically trigger a Jenkins pipeline to build and deploy a Dockerized application on AWS EC2.

## 🛠️ Tools & Technologies
- Git & GitHub
- Jenkins
- Docker
- Linux
- AWS EC2

## 🚀 CI/CD Workflow
1. Code pushed to GitHub
2. GitHub webhook triggers Jenkins
3. Jenkins builds Docker image
4. Old container is stopped and removed
5. New container is deployed automatically

## 📂 Project Structure
- Jenkinsfile – Defines the CI/CD pipeline
- Dockerfile – Builds the application image
- index.html – Sample application

## 🔍 Key Learnings
- Jenkins pipeline automation using SCM
- Docker image creation and container deployment
- Handling real-world issues like permission errors and port conflicts
- Webhook-based build automation

## 🌐 Deployment
The application is deployed on AWS EC2 and runs inside a Docker container.

## 👤 Author
Yogesh Parihar  
DevOps Fresher

