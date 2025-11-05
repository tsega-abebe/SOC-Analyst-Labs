# 🧠 SOC Analyst Labs

Hands-on Security Operations Center (SOC) projects and TryHackMe exercises showcasing log analysis, SIEM investigation, and threat detection workflows.  
This repository serves as my practical portfolio demonstrating incident response, Splunk queries, and cybersecurity automation.

---

## 🔍 Overview

This collection includes day-by-day SOC labs and small projects that reflect real-world blue-team scenarios.  
Each folder contains exercises designed to strengthen my skills in:

- Threat detection and triage  
- SIEM (Splunk) log analysis  
- Network traffic investigation  
- Incident response documentation  
- Cyber defense automation (Python, Bash)

---

## 📂 Repository Structure

| Folder | Description |
|--------|--------------|
| **Day1/** | Intro to Splunk & basic log ingestion |
| **Day2/** | VPN log analysis, user activity correlation |
| **SplunkQueries/** | Custom detection queries and dashboards |
| **Projects/** | Independent cybersecurity projects |
| **LICENSE** | Repository license |
| **.gitignore** | Ignore unnecessary local files |

---

## 🧪 Projects Included

### 1. Network Scanner
A Python-based tool that scans network subnets, identifies live hosts, and checks open ports.  
> **Skills:** Nmap scripting, socket programming, OSINT reconnaissance  

### 2. Image Cipher Steganography
A simple encryption + image hiding project to demonstrate data confidentiality techniques.  
> **Skills:** Cryptography, Steganography, Python PIL library  

### 3. Web-Based Biometric Authentication
A prototype login system using facial recognition APIs and secure hash verification.  
> **Skills:** Web security, Flask, Biometrics, Secure password hashing  

---

## 🛠️ Tools & Technologies

- **SIEM:** Splunk Enterprise  
- **Languages:** Python, Bash, SQL  
- **Platforms:** TryHackMe, GitHub  
- **Frameworks:** Flask, Scapy, Requests  
- **Security Concepts:** Incident Response, Threat Detection, Log Analysis, Vulnerability Management  

---

## 📊 Sample Splunk Queries

```spl
index=windowslogs | stats count by EventCode, User

# SOC Analyst Labs & Projects

This repository contains my hands-on SOC Analyst practice (TryHackMe/Splunk) and three showcase projects.
It is designed to be recruiter- and ATS-friendly and demonstrates skills in SIEM, threat detection, and secure engineering.

## Structure
- **Day1/** and **Day2/** — lab notes, searches (SPL), and findings.
- **SplunkQueries/** — reusable SPL queries.
- **Projects/** — three portfolio projects (Network Scanner, Image Steganography, Web Biometric Auth).
- ### 🧠 Featured Projects
[![SOC Analyst Labs](https://img.shields.io/badge/SOC%20Analyst-Labs-blue?style=flat&logo=github)](https://github.com/tsega-abebe/SOC-Analyst-Labs)


## How to Reproduce
- Import `SplunkQueries/vpn_logs_queries.spl` into Splunk's Search & Reporting.
- Replace placeholders in project READMEs and run the examples.
- Export tables from Splunk as CSV and place them in the corresponding Day folders if screenshots are unavailable.

## Skills Highlighted
SIEM (Splunk), Incident Response, Threat Detection, Log Analysis, TCP/IP, Python, Linux, Cryptography, IAM, Web Security.
