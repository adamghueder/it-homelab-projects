# Active Directory User Management Lab

## Overview

This lab demonstrates deployment and administration of **Active Directory Domain Services (AD DS)** in a virtualized Windows Server environment.
The project simulates common **IT Help Desk and Junior System Administrator tasks**, including user provisioning, password resets, account unlocks, and group-based access control.

## Environment

* Windows Server 2022 (Domain Controller)
* Oracle VirtualBox
* Windows 11 Host Machine
* Active Directory Domain: **homelab.local**

## Infrastructure Setup

Configured a Windows Server 2022 virtual machine and promoted it to a **Domain Controller**.

Key tasks:

* Enabled CPU virtualization
* Installed VirtualBox hypervisor
* Created VM **DC01**
* Installed Windows Server 2022
* Installed **Active Directory Domain Services**
* Promoted server to Domain Controller
* Configured DNS integration

## Active Directory Configuration

Created Organizational Units to simulate corporate departments:

* IT
* HR
* Finance
* Marketing
* Sales

Users were provisioned in each department OU.

Example users:

* John Admin (IT)
* Sarah Parker (HR)
* Mike Chen (Finance)
* Emily Davis (Marketing)
* David Lopez (Sales)

## Help Desk Ticket Simulations

### Password Reset

Simulated user support ticket by resetting the password for **Sarah Parker (HR)**.

### Account Unlock

Simulated account lockout resolution for **Mike Chen (Finance)**.

### Security Group Management

Created security group **IT_Admins** and added **John Admin** as a member to demonstrate **role-based access control (RBAC)**.

## Skills Demonstrated

* Active Directory Administration
* Domain Controller Deployment
* Organizational Unit Design
* User Account Management
* Password Reset Procedures
* Account Lockout Resolution
* Security Group Management
* Role-Based Access Control (RBAC)
* Windows Server Administration

## Role Simulated

**IT Help Desk Technician / Junior System Administrator**

## Documentation

Full deployment documented with **29 screenshots** covering environment setup, Active Directory installation, and administrative tasks.
