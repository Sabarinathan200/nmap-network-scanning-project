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

## 📊 Key Findings
- ✅ Host is active and reachable
- 🔓 Port 22 (SSH) is open
- 🖥️ OS detected: Linux (Kernel 5.x / 6.x)
- 🔧 Service detected: OpenSSH 10.2p1
- ⚠️ No critical vulnerabilities detected (basic scan)

---

## 🔎 Analysis
- Open SSH port may allow remote access
- Weak credentials can lead to unauthorized access
- System appears secure but requires deeper testing

---

## ⚠️ Risk Level

Low to Medium

---

## 🛡️ Recommendations
- Use strong SSH passwords
- Disable root login
- Keep system updated
- Apply firewall restrictions

---

## 📸 Screenshots
🔹 Local IP Address

🔹 Basic Scan

🔹 Network Scan

🔹 Advanced Scan

🔹 Vulnerability Scan

---

## 📚 Learning Outcome
- Learned how to perform network scanning using Nmap
- Understood how to interpret scan results
- Gained knowledge of ports, services, and vulnerabilities
- Improved practical cybersecurity skills

---

## 🚀 Future Improvements
- Perform deeper vulnerability scanning
- Use additional tools like Burp Suite
- Set up a complete penetration testing lab

---

## 👨‍💻 Author

## **Sabarinathan B**
Cybersecurity Enthusiast | Ethical Hacking Learner
