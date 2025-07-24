Welcome to my DevOps project portfolio. This repo contains two hands-on projects demonstrating my skills in cloud infrastructure, CI/CD automation, and deployment using AWS and GitHub Actions.

---

## 📁 Project 1: Static Website Deployment to S3 via GitHub Actions

### 🔍 Overview
This project automates the deployment of a static HTML website to AWS S3 using GitHub Actions. Every push to the `main` branch triggers a CI/CD pipeline that syncs updated site files to an S3 bucket.

### Tech Stack
- AWS S3
- GitHub Actions
- HTML/CSS
- IAM & Access Keys

### CI/CD Workflow
- On push to `main`, GitHub Actions:
  - Installs AWS CLI
  - Configures credentials from GitHub Secrets
  - Syncs `s3-site/` folder to the S3 bucket
- Bucket is configured for static website hosting

Live Demo
[http://my-first-demo-2.s3-website-<region>.amazonaws.com](http://my-first-demo-2.s3-website-us-east-1.amazonaws.com)
