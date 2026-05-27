# Active Directory SOC Lab

## 📌 Overview

This project documents the creation of a Windows Active Directory home lab designed for SOC analyst training, log analysis, and threat detection practice.

The environment simulates a small enterprise network with:

- Active Directory Domain Services
- Windows domain-joined endpoints
- Enterprise user accounts
- Authentication logging
- Future SIEM integration with Splunk and Microsoft Sentinel

## 🎯 Objectives

- Learn Active Directory administration
- Generate realistic Windows security logs
- Practice authentication monitoring
- Simulate enterprise attack scenarios
- Build hands-on SOC analyst skills

## 🛠️ Technologies Used

- Windows Server 2022
- Active Directory Domain Services (AD DS)
- Windows 10
- VMware Workstation
- Kali Linux
- Splunk (planned)
- Sysmon (planned)

## 🧱 Lab Architecture

```text
[ DC01 ] ---- Domain Controller
     |
[ CLIENT01 ] ---- Domain Joined Workstation
     |
[ Kali Linux ] ---- Attack Simulation
```

## ✅ Completed Tasks

- Installed Windows Server 2022
- Configured DC01 as Domain Controller
- Created corp.local domain
- Created Organizational Units (OUs)
- Created enterprise user accounts
- Created privileged admin account
- Joined CLIENT01 to domain

## 🚧 In Progress

- Splunk installation
- Sysmon deployment
- Log ingestion
- Detection engineering
- Threat hunting scenarios

## 🧠 Skills Learned

- Active Directory administration
- Windows domain management
- Enterprise authentication workflows
- User and group management
- SOC lab architecture

## 🚀 Future Improvements

- Splunk SIEM integration
- Microsoft Sentinel integration
- Sysmon logging
- Brute force detection
- PowerShell threat detection
- Incident response playbooks