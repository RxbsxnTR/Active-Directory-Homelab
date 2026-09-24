Windows Server & Active Directory Homelab

📌 Project Overview

This repository contains the documentation, configuration details, and scripts for a custom IT infrastructure homelab. The goal of this project is to simulate an enterprise Windows domain environment to practice System Administration, Active Directory management, networking, and automation.

🏗️ Architecture & Technologies

Hypervisor: Oracle VirtualBox

Servers: Windows Server 2022 Standard (DC01)

Clients: Windows 11 Pro (PC1)

Core Services: Active Directory Domain Services (AD DS), DNS, Group Policy (GPO), File Services

Network: Isolated Internal Network (192.168.1.0/24)

🚀 Current Progress (v1.0)

[x] Hypervisor setup and virtual network configuration.
[x] Windows Server 2022 deployment.
[x] Static IP and local DNS configuration.
[x] Promotion to Domain Controller (Domain: robin.local).
[x] Windows 11 Pro deployment and domain joining.
[x] Creation of Organizational Units (OU) structure.
[x] User account management and security testing (Account Lockout Policy).
[x] Group Policy Object (GPO) implementation and verification.
[x] Role-Based Access Control (RBAC) implementation using Security Groups.
[x] File Server configuration with Share and NTFS Security permissions.
[x] Automated network drive mapping via GPO Preferences.
[x] Windows Defender Firewall configuration via GPO for ICMP (Ping) diagnostics.

📸 Setup Gallery

Phase 1: Server & Domain Initialization
Here are some key moments from the initial infrastructure deployment:

1. Network Configuration
2. AD DS Role Installation
3. Domain Promotion
4. Server Manager Dashboard

Phase 2: Client Integration & IT Support Scenarios
Practical helpdesk tasks, client configuration, and domain management:

5. Client Network Configuration (DNS pointing to DC)
6. Welcome to the Domain
7. Active Directory Structure (OU & Users)
8. Account Lockout Policy Test (Security)
9. GPO Configuration (Restricting Desktop Background)
10. GPO Applied successfully on Client

Phase 3: Resource Management & Network Diagnostics
Advanced file sharing, permission management, and remote troubleshooting:

11. Security Group Configuration (RBAC)
12. NTFS and Share Permissions Configuration
13. Automated Network Drive Mapping (GPO)
14. Successful ICMP Ping via Firewall GPO Exception

Created by Robin Laskowski - Aspiring Junior IT Support Specialist.