# Ethical Hacking Practicals — Final Year Computer Science Students

> **Educational use only.** These practicals are for learning ethical hacking techniques in a **controlled, authorized lab environment**. Do **NOT** perform these activities on real-world systems without explicit written permission. Unauthorized testing is illegal and unethical.

---

## 🧠 Overview

This repository contains hands-on practicals for final year Computer Science students focusing on:

- Linux Network Analysis  
- Nmap Scanning  
- Metasploit Framework (Safe Usage)  
- Cross-Site Scripting (XSS)  
- SQL Injection (SQLi)  
- Keylogger (Concepts & Detection)

Each module is designed to teach offensive and defensive techniques **only in a legal, isolated environment** such as test VMs or CTF labs.

---

## 🎯 Learning Objectives

- Understand basic offensive security tools and how they are used.
- Identify and demonstrate common vulnerabilities like XSS and SQLi.
- Use tools like Nmap, Metasploit, and packet analyzers effectively.
- Learn basic detection, prevention, and remediation strategies.
- Operate ethically and legally within defined boundaries.

---

## 🧪 Labs Included

### 1. Linux Network Analysis
- Tools: `tcpdump`, `wireshark`, `netstat`, `iftop`
- Goal: Analyze traffic, detect anomalies, and interpret protocols.

### 2. Nmap — Network Discovery
- Tasks: Port scanning, service detection, version enumeration
- Goal: Identify open ports, running services, and potential entry points.

### 3. Metasploit (Safe Modules)
- Usage: Understand exploit-payload-session cycle (non-destructive)
- Goal: Learn how attackers use Metasploit and how to defend against it.

### 4. Cross-Site Scripting (XSS)
- Types: Reflected, Stored, DOM-based
- Goal: Identify and patch XSS vulnerabilities in sample web apps.

### 5. SQL Injection (SQLi)
- Types: Union-based, Boolean, Error-based
- Goal: Exploit SQLi vulnerabilities and learn how to prevent them using secure coding practices.

### 6. Keylogger (Conceptual)
- Focus: How keyloggers work, detection methods, and system hardening.
- **Note**: No real malicious code is provided — only logs and analysis.

---

## 💻 Prerequisites

- Familiarity with Linux and basic networking.
- Lab setup using VirtualBox, VMware, or cloud VMs.
- Recommended targets:  
  - DVWA (Damn Vulnerable Web App)  
  - Metasploitable 2  
  - OWASP Mutillidae II

> Always use an isolated network or host-only adapter when working with vulnerable machines.

---

## 🚀 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Prathamesh911-Dev/EH.git
   cd EH
