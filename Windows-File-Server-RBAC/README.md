# Windows File Server RBAC Lab

## Overview
This project simulates a corporate shared drive using a Windows 11 virtual machine.
I configured department-based access control using security groups, NTFS permissions, and shared folders.

The goal was to practice real-world Help Desk and Junior System Administration tasks such as user management, permission troubleshooting, and access validation.

---

## Technologies Used
- Windows 11 Virtual Machine (UTM on Apple Silicon)
- Local Users and Groups
- NTFS Permissions
- SMB Network Share (\\localhost)
- Role-Based Access Control (RBAC)

---

## 👥 User & Group Setup
Created simulated company departments:

- HR
- Finance
- Marketing
- Operations
- Accounting
- Customer Support

Each user was assigned to a security group to enforce least-privilege access.

![Users and Groups](PASTE-USER-SCREENSHOT-LINK)

---

## 📁 Shared Folder Structure
Created a centralized company share:

## 📁 Shared Folder Configuration
C:\CompanyShare
├── HR
├── Finance
├── Marketing
├── Operations
├── Accounting
└── CustomerSupport

![Share]([image-link](https://github.com/adamghueder/it-homelab-projects/blob/main/Windows-File-Server-RBAC/screenshots/Windows-File-Server-RBAC.1.png?raw=true))

## 🚫 Access Denied Validation
![Access Denied]([image-link](https://github.com/adamghueder/it-homelab-projects/blob/main/Windows-File-Server-RBAC/screenshots/Windows-File-Server-RBAC.10.png?raw=true))

