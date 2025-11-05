# 🧠 SOC Analyst Labs by Tsega Abebe
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Splunk](https://img.shields.io/badge/SIEM-Splunk-orange?logo=splunk)
![TryHackMe](https://img.shields.io/badge/TryHackMe-Labs-red?logo=tryhackme)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)

Hands-on projects, Splunk investigations, and blue-team exercises.

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
## 📂 Navigation
- [Day 1](./Day1) – Basic Splunk search and data ingestion  
- [Day 2](./Day2) – VPN log analysis and user correlation  
- [Projects](./Projects) – Personal cybersecurity tools  
- [Splunk Queries](./SplunkQueries) – Detection and response queries
  
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Splunk](https://img.shields.io/badge/SIEM-Splunk-orange?logo=splunk)
![TryHackMe](https://img.shields.io/badge/TryHackMe-Labs-red?logo=tryhackme)


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


## Skills Highlighted
SIEM (Splunk), Incident Response, Threat Detection, Log Analysis, TCP/IP, Python, Linux, Cryptography, IAM, Web Security.
index=vpn_logs sourcetype=_json action="teardown" | stats count by user

## Day 1: Splunk Data Onboarding & Search
- Learned how to ingest log files into Splunk Enterprise
- Performed basic searches: `index=* | stats count by sourcetype`
- Created visual dashboards to track login activity


