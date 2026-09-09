# 🚀 EC2 Linux Web Server Deployment using Apache HTTPD

![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Linux](https://img.shields.io/badge/Linux-Amazon%20Linux-black)
![Apache](https://img.shields.io/badge/Apache-HTTPD-red)
![HTML](https://img.shields.io/badge/HTML5-orange)
![CSS](https://img.shields.io/badge/CSS3-blue)
![Git](https://img.shields.io/badge/Git-Version%20Control-orange)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black)
![DevOps](https://img.shields.io/badge/DevOps-Project-green)

---

# 📌 EC2 Linux Web Server Deployment using Apache HTTPD

## 👨‍💻 Project By

### Mohit Gadilohar

**Cloud & DevOps Engineer**

---

# 📖 Table of Contents

- 📌 Project Overview
- 🎯 Project Objective
- 🏗️ Project Architecture
- ☁️ Step 1: Create EC2 Instance
- 🛡️ Step 2: Configure Security Group
- 💻 Step 3: Connect to Linux Server
- 👑 Step 4: Switch to Root User
- 🔄 Step 5: Update Linux Packages
- 📦 Step 6: Install Apache HTTPD
- 📁 Step 7: Move to Website Directory
- 📄 Step 8: Create HTML File
- ✍️ Step 9: Edit HTML File
- ▶️ Step 10: Start Apache
- 🔁 Step 11: Enable Apache
- 🔍 Step 12: Verify Apache
- 🌍 Step 13: Access Website
- ✅ Step 14: Expected Output
- 🧾 Complete Command Summary
- 🛠️ Technologies Used
- 📚 Skills Learned
- 🔧 Troubleshooting
- 📸 Project Screenshots
- 📁 Project Structure
- 🔄 Project Workflow
- 🎯 Project Outcome
- 🏆 Conclusion
- 👨‍💻 Author

---

# 📌 Project Overview

This project demonstrates how to create an **AWS EC2 Linux instance**
and deploy a simple website using the **Apache HTTPD web server**.

The complete project covers:

☁️ AWS EC2 Instance Creation

🐧 Linux Server Configuration

🛡️ Security Group Configuration

🔐 SSH Connection

📦 Apache HTTPD Installation

📁 Apache Website Directory

📄 HTML Website Creation

▶️ Apache Service Management

🌍 Website Deployment

✅ Website Verification

This project provides practical experience in **AWS Cloud,
Linux Administration, Apache Web Server, Networking,
and Web Deployment**.

---

# 🎯 Project Objective

The main objective of this project is to understand the complete
process of deploying a website on an AWS EC2 Linux server.

### Objectives

✅ Launch an EC2 Linux instance

✅ Configure Security Group rules

✅ Connect to EC2 using SSH

✅ Configure Linux server

✅ Install Apache HTTPD

✅ Create an HTML webpage

✅ Deploy webpage to Apache

✅ Start Apache Web Server

✅ Enable Apache after reboot

✅ Access website using Public IP

---

# 🏗️ Project Architecture

```text
                         🌐 INTERNET
                              |
                              |
                              ▼
                    ┌──────────────────┐
                    │    AWS EC2       │
                    │   Linux Server   │
                    └────────┬─────────┘
                             |
                             |
                             ▼
                    ┌──────────────────┐
                    │  Apache HTTPD    │
                    │    Web Server    │
                    └────────┬─────────┘
                             |
                             |
                             ▼
                    ┌──────────────────┐
                    │ /var/www/html    │
                    │                  │
                    │   index.html     │
                    └────────┬─────────┘
                             |
                             |
                             ▼
                    ┌──────────────────┐
                    │   Web Browser    │
                    │       💻         │
                    └──────────────────┘
