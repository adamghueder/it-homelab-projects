# IT Homelab Projects
IT Support/Help Desk Technician labs: Spiceworks ticketing system + Windows file server permissions

**Role Simulated:** Help Desk Technician / Junior System Administrator  
**Environment:** Windows 11 Enterprise Lab  
**Focus:** RBAC, NTFS Permissions, Help Desk Workflow

# 1. Windows File Server RBAC Lab

## Overview
Simulated a corporate shared drive environment using a Windows 11 virtual machine.

## Skills Demonstrated
- User and Group Management
- NTFS Permissions
- Role-Based Access Control (RBAC)
- Shared Folder Configuration (\\localhost)
- Access Testing & Troubleshooting

## What I Built
Created departmental folders:
- HR
- Finance
- Marketing
- Operations
- Accounting
- Customer Support

Configured permissions so users could only access their assigned department.

## Testing Performed
- Verified HR could create files in HR folder
- Verified Finance access was denied for HR users
- Tested permissions via network share path

## Tools Used
Windows 11 VM (UTM)
Computer Management
NTFS Security Permissions


# 2. Spiceworks Help Desk Simulation

## Overview
Built a simulated help desk environment using Spiceworks Cloud Help Desk.

## Skills Demonstrated
- Ticket Lifecycle Management
- Incident Categorization
- Troubleshooting Documentation
- Help Desk Workflow Simulation

## Tickets Created
- Password Reset
- Printer Offline
- Slow Computer Performance
- VPN Connectivity Issue
- Email Sync Issue

## Tools Used
Spiceworks Cloud Help Desk
Windows 11 Virtual Machine

## Lessons Learned
- Importance of disabling inheritance for department isolation
- Difference between NTFS and Share permissions
- Real-world troubleshooting using access denied scenarios
