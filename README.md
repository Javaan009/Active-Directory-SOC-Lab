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

## ✅ Purpose

This lab provides a practical environment for learning how attackers move through Active Directory and how SOC analysts detect, investigate, and respond to suspicious activity in enterprise Windows environments.