# Enterprise Attack & Defense Simulation

## Overview
This project demonstrates a real-world cybersecurity attack and defense simulation using Kali Linux (attacker) and Metasploitable2 (vulnerable target).

The project focuses on identifying, exploiting, detecting, and mitigating common web application vulnerabilities such as SQL Injection (SQLi) and Cross-Site Scripting (XSS).

## Objectives
- Simulate real-world cyber attacks in a controlled lab environment  
- Identify and exploit vulnerabilities (SQLi, XSS)  
- Perform reconnaissance using Nmap  
- Gain system access and analyze impact  
- Implement security measures and system hardening  

## Tools & Technologies
- Kali Linux  
- Metasploit Framework  
- Nmap  
- Metasploitable2  
- PHP & MySQL  

## Methodology

### 1. Vulnerability Testing
- Identified SQL Injection and XSS in a custom login system  
- Performed authentication bypass using SQLi  
- Executed malicious scripts using XSS  

### 2. Reconnaissance
- Scanned target using Nmap (`-sV`)  
- Identified running services and versions  

### 3. Exploitation
- Used Metasploit to exploit vulnerabilities  
- Established Meterpreter session  

### 4. Privilege Escalation
- Gained root-level access  
- Executed system-level commands  

### 5. Data Access
- Accessed sensitive files:
  - `/etc/passwd`
  - `/etc/shadow`  

### 6. Detection
- Analyzed logs:
  - `/var/log/auth.log`
  - Apache access & error logs  
- Identified suspicious activity  

### 7. Response
- Blocked attacker IP using firewall (UFW)  
- Updated system passwords  
- Restarted services  
- Applied system updates  

### 8. Hardening
- Implemented prepared statements (SQLi fix)  
- Input validation and sanitization  
- Output encoding (XSS protection)  
- Enabled firewall and security configurations  

## Results
- SQL Injection successfully bypassed authentication  
- XSS enabled script execution  
- System fully compromised in lab environment  

## Key Learnings
- Practical understanding of attack lifecycle  
- Importance of secure coding practices  
- Real-world penetration testing workflow  

## Disclaimer
This project was conducted in a controlled lab environment for educational purposes only. No real-world systems were targeted.
