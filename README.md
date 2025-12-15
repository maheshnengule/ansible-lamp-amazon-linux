# ansible-lamp-amazon-linux
LAMP stack deployment on Amazon Linux using Ansible

# Ansible LAMP Stack Deployment on Amazon Linux (AWS)

## Project Overview
This project demonstrates automated deployment of a **LAMP stack**
(Linux, Apache, MariaDB, PHP) on **Amazon Linux 2023** using **Ansible**.
The goal is to eliminate manual server configuration by using
**Infrastructure as Code (IaC)** principles.

This project is suitable for **Cloud Engineer, DevOps Engineer,
System Administrator, and AWS Fresher roles**.

---

## Key Skills Demonstrated
- Ansible Automation
- AWS EC2 (Amazon Linux 2023)
- Apache Web Server (httpd)
- MariaDB 10.5
- PHP & php-fpm
- Linux System Administration
- systemd Service Management
- Infrastructure as Code (IaC)

---

## Technology Stack
- OS: Amazon Linux 2023
- Automation Tool: Ansible
- Web Server: Apache (httpd)
- Database: MariaDB 10.5
- Scripting Language: PHP
- Process Manager: systemd

---

## Project Files
- `lamp.yml` – Ansible playbook to install and configure LAMP stack

---

## Automation Workflow
1. Installs Apache web server
2. Installs MariaDB database server
3. Installs PHP and php-fpm
4. Starts and enables all required services
5. Deploys a PHP test application (`index.php`)
6. Verifies application availability via browser

---

## How to Execute
```bash
ansible-playbook lamp.yml

## Project Screenshots

<img width="812" height="434" alt="image" src="https://github.com/user-attachments/assets/c4df8e4e-8633-4c0b-bd90-8a0a9796b6d4" />
