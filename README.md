# Computing Fundamentals – Capstone Project (Module 13)

This repository contains the capstone project for **Computing Fundamentals – Module 13: Put up an Environment**.

The goal of this project is to configure a complete Linux-based environment using virtualization and automation tools.

---

## 👤 Student Information

- **Name:** Usman Muhammad  
- **R-number:** r0916150  
- **Course:** Computing Fundamentals  
- **Module:** Module 13 – Put up an Environment  

---

## 🖥️ Project Overview

In this project, two Linux virtual machines were created and configured using **Oracle VirtualBox**:

- A **Jump Server** used as the Ansible control node
- A **Web Server** used to host an Apache website

All configuration and software installation is automated using **Ansible**.

---

## 🧱 Virtual Machines

### Jump Server
- Hostname: `jumpserver1`
- Purpose:
  - Ansible control node
  - SSH key generation
  - VNC access for remote desktop

### Web Server
- Hostname: `webserver1`
- Purpose:
  - Apache web server
  - Hosting a website deployed from GitHub using Ansible

---

## 🔐 Authentication

- SSH key-based authentication is used
- The SSH key pair is generated on the jump server
- Passwordless SSH access is configured for both machines

---

## ⚙️ Technologies Used

- Ubuntu Linux
- Oracle VirtualBox
- Ansible
- Apache Web Server
- SSH
- VNC
- Git & GitHub

---

## 📂 Repository Structure

