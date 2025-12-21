# 🚀 CI/CD Pipeline to Cloud Run on Google Cloud

This project demonstrates a complete CI/CD pipeline on Google Cloud Platform.
A containerized web application is automatically built and deployed to **Cloud Run**
using **Cloud Build** after each push to the GitHub repository.

---

## 📌 Project Overview

The goal of this project is to show how to:
- containerize an application using Docker
- automatically build and push container images
- deploy applications to Cloud Run using CI/CD
- manage permissions using IAM and service accounts

The entire deployment process is fully automated and does not require manual steps.

---

## 🧱 Architecture

```text
GitHub Repository
        │
        ▼
Cloud Build (CI/CD)
        │
        ▼
Artifact Registry
        │
        ▼
Cloud Run (Serverless)
