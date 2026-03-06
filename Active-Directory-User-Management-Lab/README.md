# Active Directory User Management Lab

## Overview

This lab demonstrates the deployment and administration of **Active Directory Domain Services (AD DS)** in a virtualized Windows Server environment.

The project simulates common **IT Help Desk and Junior System Administrator tasks**, including:

* Domain Controller deployment
* Organizational Unit (OU) design
* User provisioning
* Password reset
* Account unlock
* Security group management
* Role-Based Access Control (RBAC)

All steps were performed in a **Windows Server 2022 lab environment** and documented with screenshots.

---

# Environment

| Component   | Technology          |
| ----------- | ------------------- |
| Host OS     | Windows 11          |
| Hypervisor  | Oracle VirtualBox   |
| Server OS   | Windows Server 2022 |
| Domain      | homelab.local       |
| Server Name | DC01                |

---

# Infrastructure Setup

CPU virtualization was enabled on the host system and a Windows Server virtual machine was created using VirtualBox.

### Virtualization Enabled

![Virtualization Enabled](screenshots/01-virtualization-enabled.png)

### Windows Features Configuration

![Windows Features](screenshots/02-windows-features.png)

### Virtual Machine Hardware Configuration

![VM Hardware Settings](screenshots/06-vm-hardware-settings.png)

---

# Windows Server Deployment

A Windows Server 2022 virtual machine was deployed and configured as the foundation for the domain environment.

### Windows Server Installation

![Windows Server Install](screenshots/09-windows-server-install-start.png)

### Windows Server Desktop

![Windows Server Desktop](screenshots/10-windows-server-desktop.png)

### Local Server Configuration

![Local Server Settings](screenshots/11-local-server-settings.png)

---

# Active Directory Deployment

The **Active Directory Domain Services (AD DS)** role was installed and the server was promoted to a **Domain Controller**.

### Add Roles and Features Wizard

![Add Roles Wizard](screenshots/12-add-roles-wizard.png)

### Active Directory Role Selected

![AD DS Role Selected](screenshots/13-active-directory-role-selected.png)

### Domain Controller Promotion

![New Forest Domain](screenshots/16-new-forest-domain.png)

### Domain Controller Successfully Installed

![Domain Controller Ready](screenshots/22-domain-controller-ready.png)

---

# Active Directory Administration Console

The **Active Directory Users and Computers** management console was used to administer the domain.

![Active Directory Console](screenshots/23-active-directory-console.png)

---

# Organizational Unit Structure

Organizational Units (OUs) were created to simulate a corporate departmental structure.

Departments created:

* IT
* HR
* Finance
* Marketing
* Sales

![Department OUs](screenshots/24-department-ous.png)

---

# User Provisioning

User accounts were created within their respective departmental Organizational Units.

Example users created:

| Name         | Department | Username |
| ------------ | ---------- | -------- |
| John Admin   | IT         | jadmin   |
| Sarah Parker | HR         | sparker  |
| Mike Chen    | Finance    | mchen    |
| Emily Davis  | Marketing  | edavis   |
| David Lopez  | Sales      | dlopez   |

![Users Created](screenshots/25-department-users-created.png)

---

# Help Desk Ticket Simulations

To simulate real IT support scenarios, several common help desk tasks were performed.

---

## Password Reset

A simulated support ticket was created where **Sarah Parker (HR)** forgot her password.

The password was reset and the user was required to change it at next login.

![Password Reset](screenshots/26-password-reset-ticket.png)

---

## Account Unlock

Another support scenario simulated an account lockout for **Mike Chen (Finance)**.

The account was unlocked through Active Directory.

![Account Unlock](screenshots/28-account-unlock.png)

---

# Security Group Management

A security group was created to demonstrate **Role-Based Access Control (RBAC)**.

### Security Group Created

```
IT_Admins
```

User **John Admin** was added to the group to simulate administrative access assignment.

![Security Group Membership](screenshots/29-security-group-membership.png)

---

# Skills Demonstrated

This lab demonstrates the following IT administration skills:

* Windows Server Deployment
* Active Directory Domain Services (AD DS)
* Domain Controller Configuration
* DNS Integration
* Organizational Unit Design
* User Account Provisioning
* Password Reset Procedures
* Account Lockout Resolution
* Security Group Management
* Role-Based Access Control (RBAC)
* Windows Server Administration

---

# Role Simulated

**IT Help Desk Technician / Junior System Administrator**

---

# Project Documentation

The full deployment process was documented with **29 screenshots**, covering:

* Infrastructure setup
* Windows Server installation
* Active Directory deployment
* Organizational Unit configuration
* User management
* Help desk task simulations
* Security group administration

This project demonstrates hands-on experience with **enterprise identity management systems used in corporate IT environments**.

Full deployment documented with **29 screenshots** covering environment setup, Active Directory installation, and administrative tasks.
