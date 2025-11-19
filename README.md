# 🛡️ Security Integration Lab Documentation

This repository contains my personal 30-day project to build a complete cybersecurity environment using SIEM, SOAR, EDR, XDR, PAM, and Firewall solutions.  
The goal is to learn **Security Solutions Integration** by deploying real tools, collecting logs, detecting attacks, and documenting the process.

---

## 📌 1. Architecture Diagram




![Uploading Capture d'écran 2025-11-19 195113.png…]()





---

## 🖥️ 2. Virtual Machine Specifications

### **Ubuntu SIEM VM**
- **OS:** Ubuntu Server 22.04 LTS  
- **RAM:** 4 GB  
- **CPU:** 2 vCPUs  
- **Disk:** 40 GB  
- **Network:**
  - NAT (Internet access)
  - Host-only (Internal lab)
- **Roles:**
  - SIEM (ELK Stack)
  - Log processing (Filebeat/Logstash)
  - Future SOAR/EDR integrations

---

### **Windows 10 Endpoint VM**
- **OS:** Windows 10 Pro 22H2  
- **RAM:** 4 GB  
- **CPU:** 2 vCPUs  
- **Disk:** 50 GB
- **Network:**
  - NAT
  - Host-only
- **Roles:**
  - Sysmon telemetry
  - Winlogbeat/Filebeat agent
  - Attack simulation using TryHackMe labs

---

## 🧩 3. OS & Software Versions

- **Ubuntu Server:** 22.04.4 LTS  
- **Windows 10 Pro:** Version 22H2  
- **VirtualBox:** 7.x  

---

## 🎯 4. Goal of the Lab

The purpose of this lab is to build a complete cybersecurity monitoring environment that covers:

- SIEM integration (Elastic, Security Onion)
- Endpoint telemetry (Sysmon, Beats)
- EDR/XDR deployment
- SOAR orchestration
- Firewall setup and log forwarding
- Incident detection & attack simulation
- Documentation for professional Security Engineering/Integration roles

The ultimate goal is to understand **how security solutions integrate together** and produce a real portfolio for cybersecurity job applications.

---
