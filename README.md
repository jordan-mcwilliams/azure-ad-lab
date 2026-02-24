# Active Directory Domain Services Lab (Azure)

## Overview
This lab demonstrates deploying and configuring a Windows Server 2022 virtual machine in Azure, 
installing Active Directory Domain Services (AD DS), promoting the server to a domain controller, 
creating a basic Organizational Unit (OU) structure, and managing users and groups. Authentication 
is tested using both GUI and PowerShell.

## Environment
- **Azure VM**: Windows Server 2022
- **Size**: B1s (low-cost tier)
- **Region**: East US
- **Domain Name**: lab.local
- **Client OS**: Windows 10

## Repository Structure
```text
azure-ad-lab
│
├── README.md # Project documentation (this file)
├── screenshots/ # Screenshots of lab steps
├── powershell/ # PowerShell scripts used for AD configuration
└── notes/ # Troubleshooting notes and reflections
```
## Planned Sections
- **Core Concepts** – Key AD concepts like Kerberos, LDAP, forest vs domain, and DNS
- **Security Considerations** – Least privilege, group-based access control, and authentication security
- **Lessons Learned** – Troubleshooting, lab insights, and reflection
- **Potential Improvements** – Next steps for scaling the lab environment
- **Screenshots of lab steps** – Visual documentation of lab steps
- **PowerShell scripts** – Scripts used to create users, groups, and configure AD
- **Troubleshooting notes** – Problems encountered and how they were resolved

## Example Domain Structure
```text
lab.local
│
├── Users
│ ├── jdoe
│ └── asmith
├── Computers
│ ├── PC01
│ └── WS2022
└── Groups
├── HR-SharedFolder
└── IT-Admins
```
*Note: All usernames and domain objects are fictitious and for lab purposes only*
