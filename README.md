# SOC-analysis-
# SOC Analyst Cybersecurity Lab Portfolio

## Overview

This repository documents my 15-week SOC Analyst cybersecurity lab roadmap.

The purpose of this portfolio is to build practical hands-on skills in cybersecurity fundamentals, Windows security monitoring, networking, vulnerability assessment, SIEM analysis, incident response, and basic digital forensics.

The lab is built using virtual machines in an isolated VirtualBox environment. Each week contains documentation, screenshots, evidence, notes, and practical lab results.

---

## Lab Environment

### Virtualization Platform

- Oracle VirtualBox

### Operating Systems Used

- Kali Linux
- Windows Server 2022

### Base Network Setup

The initial lab uses an isolated internal network.

| Machine | IP Address | Purpose |
|---|---|---|
| Kali Linux | 192.168.56.10 | Security testing and analysis machine |
| Windows Server 2022 | 192.168.56.20 | Windows server, logs, Event Viewer, and future Active Directory lab |

### Network Name

```text
CyberLabs
```

Both machines are connected to the same VirtualBox Internal Network. This allows the lab systems to communicate with each other while remaining isolated from external networks.

---

## 15-Week SOC Analyst Roadmap

| Week | Topic | Main Focus |
|---|---|---|
| Week 1 | Full Lab Setup | VirtualBox, Kali Linux, Windows Server, static IPs, connectivity testing |
| Week 2 | CIA, AAA, Risk Table, Event Viewer | Security fundamentals and Windows log analysis |
| Week 3 | OpenSSL, Hashing, Keys, Certificates | Cryptography basics |
| Week 4 | pfSense Firewall, VLAN, DMZ | Firewall and network segmentation concepts |
| Week 5 | Nmap, Wireshark, Snort IDS | Scanning, packet analysis, and intrusion detection |
| Week 6 | DNS Analysis and Wireless Security | DNS traffic and wireless security theory |
| Week 7 | Nessus Vulnerability Scan | Vulnerability assessment and reporting |
| Week 8 | Metasploitable and Metasploit | Controlled exploitation lab |
| Week 9 | DVWA, SQLi, XSS, OSINT | Web security and open-source intelligence |
| Week 10 | Active Directory, Users, OUs, GPOs | Windows domain administration |
| Week 11 | Splunk SIEM Dashboard | Log monitoring and SIEM analysis |
| Week 12 | Incident Response and FTK Imager | Forensics and phishing awareness |
| Week 13 | PKI Certificate Authority Lab | Certificate authority and PKI concepts |
| Week 14 | TLS Handshake and Cloud Security | TLS analysis and cloud security basics |
| Week 15 | Governance, Risk Register, Final Portfolio | Final documentation and portfolio presentation |

---

## Tools Covered

This roadmap includes the following cybersecurity tools and technologies:

- Nmap
- Wireshark
- Snort
- Nessus
- Metasploit
- Splunk
- FTK Imager
- OpenSSL
- Windows Event Viewer
- VirtualBox
- Kali Linux
- Windows Server 2022

---

## Repository Structure

```text
SOC-analysis/
│
├── Week-01-Lab-Setup/
│   ├── Screenshots/
│   ├── Evidence/
│   ├── Notes/
│   └── Week-01-Documentation.pdf
│
├── Week-02-CIA-AAA-EventViewer/
│   ├── Screenshots/
│   ├── Evidence/
│   ├── Notes/
│   └── Week-02-Documentation.pdf
│
├── Week-03-OpenSSL-Certificates/
├── Week-04-pfSense-VLAN-DMZ/
├── Week-05-Nmap-Wireshark-Snort/
├── Week-06-DNS-Wireless-Security/
├── Week-07-Nessus-Report/
├── Week-08-Metasploit-Lab/
├── Week-09-DVWA-SQLi-XSS-OSINT/
├── Week-10-Active-Directory-GPO/
├── Week-11-Splunk-SIEM/
├── Week-12-Incident-Response-FTK/
├── Week-13-PKI-CA-Lab/
├── Week-14-TLS-Cloud-Security/
├── Week-15-Governance-Final-Portfolio/
│
└── README.md
```

---

## Week 1 Summary

In Week 1, I configured a basic isolated cybersecurity lab using VirtualBox.

The lab includes Kali Linux and Windows Server 2022 connected through the same internal network. Static IP addresses were assigned, and connectivity was tested using ping from both machines.

### Week 1 Key Tasks

- Installed Kali Linux
- Installed Windows Server 2022
- Configured VirtualBox Internal Network
- Assigned static IP addresses
- Troubleshot network adapter issues
- Fixed mismatched internal network names
- Enabled ICMPv4 Echo Request on Windows Firewall
- Verified connectivity between Kali and Windows Server
- Created screenshots and documentation

### Week 1 Final Result

| Machine | IP Address | Status |
|---|---|---|
| Kali Linux | 192.168.56.10 | Working |
| Windows Server 2022 | 192.168.56.20 | Working |

Successful ping tests confirmed that both machines can communicate inside the isolated lab network.

---

## Week 2 Summary

Week 2 focuses on basic SOC Analyst concepts and Windows security monitoring.

### Main Topics

- CIA Triad
- AAA Model
- Risk Assessment Table
- Windows Event Viewer
- Security Event IDs
- Successful and failed login analysis

### Important Windows Event IDs

| Event ID | Meaning |
|---|---|
| 4624 | Successful logon |
| 4625 | Failed logon |
| 4634 | Logoff |
| 4672 | Special privileges assigned to new logon |

---

## Learning Objectives

The main objectives of this portfolio are to:

- Build a safe virtual cybersecurity lab
- Understand core cybersecurity principles
- Practice Windows log analysis
- Learn network scanning and packet analysis
- Understand vulnerability scanning
- Explore IDS and SIEM monitoring
- Practice incident response basics
- Learn basic digital forensics
- Build a professional cybersecurity portfolio for internships and entry-level SOC roles

---

## Skills Developed

This lab portfolio helps develop practical skills in:

- Virtual machine configuration
- Network troubleshooting
- Windows Server administration
- Windows Event Viewer analysis
- Security log interpretation
- Risk assessment
- Vulnerability scanning
- Packet analysis
- IDS alert monitoring
- SIEM dashboard creation
- Incident response documentation
- Digital evidence handling
- Cybersecurity reporting

---

## Safety and Ethics

All labs in this repository are performed in a private and isolated virtual environment.

The tools and techniques documented here are used strictly for learning, defensive security, and SOC Analyst training.

No testing is performed against public systems, third-party networks, or unauthorized targets.

---

## Author

**Nishchay Bholla**  
Cybersecurity Student | SOC Analyst Learner | IT Support & Security Enthusiast

---

## Portfolio Status

This repository is a work in progress and will be updated weekly as each lab is completed.
