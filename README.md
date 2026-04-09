# 🚀 LAMP Stack Deployment on AWS (Manual → Ansible → Cloud)

## 📌 Project Overview

This project demonstrates the complete journey of deploying a LAMP stack (Linux, Apache, MySQL, PHP) from manual setup to automation and finally deploying it on AWS cloud using modern DevOps practices.

---

# 🧭 Project Phases

## 🔹 Phase 1: Manual Setup

* Installed Apache, MySQL, PHP manually on server
* Configured web server and database
* Deployed a basic PHP application
* Tested application locally

📌 **Learning:**
Understanding core fundamentals of LAMP stack and server setup.

---

## 🔹 Phase 2: Automation using Ansible

* Automated LAMP stack setup using Ansible playbooks
* Managed configuration using YAML files
* Reduced manual effort and ensured consistency

📌 **Learning:**
Infrastructure as Code (IaC) and configuration management.

---

## 🔹 Phase 3: AWS Cloud Deployment

* Deployed application on AWS EC2
* Used RDS for managed MySQL database
* Integrated S3 for storing static files
* Configured security groups for secure communication

📌 **Learning:**
Cloud architecture, scalability, and real-world deployment practices.

---

# 🏗️ Architecture

User → EC2 (Apache + PHP) → RDS (MySQL)
→ S3 (Static Storage)

---

# ☁️ AWS Services Used

* EC2 – Web server hosting
* RDS – Managed MySQL database
* S3 – Static file storage
* IAM – Access control
* Security Groups – Network security

---

# ⚙️ Features

* End-to-end LAMP stack deployment
* Manual + Automated + Cloud setup
* Secure database connection using RDS
* Static file storage using S3
* Real-world debugging and issue resolution

---

# 🧠 Challenges Faced

* Fixed MySQL access denied issue using security groups
* Resolved HTTP 500 error due to PHP syntax issue
* Solved S3 403 (Access Denied) error using bucket policy
* Fixed S3 404 (NoSuchKey) error due to missing index file

---

# 📂 Project Structure

```
LAMP-stack-project/
├── phase-1-manual/
├── phase-2-ansible/
├── aws/
├── screenshots/
├── README.md
```

---

# 📸 Screenshots

### 🔹 EC2 Instance

![EC2](screenshots/ec2.png)

### 🔹 RDS Database

![RDS](screenshots/rds.png)

### 🔹 S3 Bucket

![S3](screenshots/s3.png)

### 🔹 Web Application

![WebApp](screenshots/webapp.png)

---

# 🚀 Future Improvements

* Domain mapping using Route 53
* CI/CD pipeline integration

---

# 💡 Author

Priyanshi Kothari
B.Tech CSE (AI & DS) | DevOps Enthusiast
