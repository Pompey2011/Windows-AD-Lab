# Active Directory Home Lab (Windows Server 2022 + Windows 10)

## Overview
This project is a fully deployed Microsoft Active Directory environment built in VirtualBox. It demonstrates domain controller deployment, user management, OU structure, Group Policy configuration, and client domain joining—simulating a real enterprise network.

## Lab Architecture
- Windows Server 2022 Domain Controller
  - AD DS + DNS
  - Domain: lab.local
  - IP: 10.0.0.10
- Windows 10 Enterprise Client
  - Joined to domain
  - IP: 10.0.0.20

## Features Implemented
- Active Directory Domain Services
- DNS configuration
- OU structure (_Departments, _Computers, _Admins)
- Domain user accounts for IT, HR, Sales
- Password policy enforcement GPO
- Control Panel restriction GPO
- Mapped network drive GPO (H: drive)
- Successful domain client join and policy application

## Skills Demonstrated
- Windows Server administration
- AD/DNS configuration
- GPO creation and troubleshooting
- Network configuration (IP, DNS)
- Identity and access management
- Virtualization architecture

## What I Learned
- Designing enterprise OU structures
- Deploying and promoting a domain controller
- Creating and linking GPOs
- Managing domain users and authentication
- Troubleshooting DNS/domain join issues
