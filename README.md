# 🔐 Network Scanning & Vulnerability Analysis using Nmap

## 📌 Overview
This project demonstrates network reconnaissance and basic vulnerability analysis using Nmap. The objective was to identify active devices, open ports, running services, and potential security risks within a local network.

---

## 🎯 Objectives
- Discover active hosts in a local network  
- Identify open ports and services  
- Perform OS and service version detection  
- Analyze potential security risks  
- Conduct basic vulnerability scanning  

---

## 🛠️ Tools & Technologies
- 🐉 Kali Linux  
- 📦 VirtualBox  
- 🔍 Nmap  

---

## 🌐 Environment Setup
- **Attacker Machine:** Kali Linux (Virtual Machine)  
- **Network Range:** 192.168.29.0/24  
- **Scanning Type:** Local network (safe & ethical)  

---

## 🔍 Scanning Techniques Used

### 🔹 Basic Scan
```bash
nmap <target-ip>
```

### 🔹 Network Scan
```bash
nmap 192.168.29.0/24
```

### 🔹 Service & OS Detection
```bash
nmap -sS -sV -O <target-ip>
```

### 🔹 Aggressive Scan
```bash
nmap -A <target-ip>
```

### 🔹 Vulnerability Scan
```bash
nmap --script vuln <target-ip>
```

---


