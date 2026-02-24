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

## User & Group Setup
Created simulated company departments:

- HR
- Finance
- Marketing
- Operations
- Accounting
- Customer Support

Each user was assigned to a security group to enforce least-privilege access.
## Project Screenshots

### Company Share Structure
![CompanyShare](screenshots/Windows-File-Server-RBAC.1.png)

### HR Permissions
![HR Permissions](screenshots/hr-permissions.png)

### Finance Access Test
![Finance Access](screenshots/finance-test.png)
