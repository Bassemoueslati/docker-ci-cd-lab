# 🐳 Docker CI/CD Pipeline Lab

Repository: docker-ci-cd-lab

---

## 🎯 Project Objective

This project demonstrates how to automate a complete Docker CI pipeline using GitHub Actions:

- 🔨 Build Docker image  
- 🧪 Test container automatically  
- 📦 Push image to Docker Hub  

---

## 🏗 Project Structure

docker-ci-cd-lab/
│
├── app/
│   └── app.py
├── requirements.txt
├── Dockerfile
├── .github/
│   └── workflows/
│       └── ci.yml
└── README.md

---

## 🚀 Application Overview

This project contains a simple Flask web application.

When running, it returns:

Docker CI/CD Pipeline Working!

The application runs on:

http://localhost:5000

---

## 🐳 Docker Configuration

### Dockerfile

- Base image: python:3.10-slim
- Sets working directory to /app
- Installs dependencies from requirements.txt
- Copies application files
- Exposes port 5000
- Runs app.py

---

## ▶️ Run Project Locally

### 1️⃣ Build Docker Image

```bash
docker build -t docker-ci-app .