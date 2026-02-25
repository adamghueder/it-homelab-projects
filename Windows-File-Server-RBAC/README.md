# Windows File Server RBAC Lab

## Overview
This lab demonstrates the implementation of Role-Based Access Control (RBAC) within a Windows file server environment using a Windows 11 virtual machine.

A simulated corporate shared drive was created with department-based access restrictions using security groups, NTFS permissions, and SMB share permissions. The objective was to replicate real-world Help Desk and Junior System Administration responsibilities such as user provisioning, permission management, access troubleshooting, and validation testing.

## Real-World Scenario
This lab simulates how corporate IT departments manage shared file access using least-privilege security principles. 

In real environments, improper NTFS or share permissions can expose sensitive HR or Finance data. This project demonstrates how role-based access control prevents unauthorized access while allowing departments to collaborate securely.
---

## Key Skills Demonstrated
- User and Group Administration
- NTFS Permission Management
- SMB Share Configuration
- Least-Privilege Access Design
- Access Control Validation & Testing
- Help Desk Troubleshooting Methodology

---

## Technologies Used
- Windows 11 Virtual Machine (UTM on Apple Silicon)
- Local Users and Groups
- NTFS Permissions
- SMB Network Share (`\\localhost`)
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

Each user account was placed into a department-based security group to enforce least-privilege access across shared resources.

---

## Project Screenshots

### Company Share Structure
![CompanyShare](screenshots/01-companyshare-root-folder-created)

### Security Group Configuration
![Group Setup](screenshots/03-security-groups-created-local-users-and-groups)

### NTFS Permission Configuration
![NTFS Permissions](screenshots/04-hr-group-membership-assignment)

### Share Permission Configuration
![Share Permissions](screenshots/06-companyshare-share-permissions-configured)

### Access Denied Validation Test
![Access Denied](screenshots/10-rbac-access-denied-hr-user-blocked-from-finance)

### Authorized Access Validation
![Authorized Access](screenshots/11-rbac-hr-user-successful-write-access)
