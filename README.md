# Week 2 – VAPT Practical Assignment

This repository contains documentation and practical work related to **Vulnerability Assessment and Penetration Testing (VAPT)**.

The objective of this task is to understand the complete **VAPT lifecycle**, including reconnaissance, vulnerability scanning, exploitation, post-exploitation, and reporting.

---

## Tools Used

* Kali Linux
* Nmap
* OpenVAS
* Nikto
* Metasploit Framework
* Burp Suite
* sqlmap
* Shodan
* Maltego

---

## VAPT Workflow

### 1 Reconnaissance

Performed OSINT using tools like **Shodan, Maltego, and Sublist3r** to identify exposed services and subdomains.

### 2 Vulnerability Scanning

Used **Nmap and OpenVAS** to detect open ports, services, and vulnerabilities.

### 3 Exploitation

Used **Metasploit Framework and sqlmap** to exploit discovered vulnerabilities.

### 4 Post Exploitation

Used **Meterpreter** to perform privilege escalation and gather evidence.

### 5 Reporting

Documented vulnerabilities, impact, and remediation recommendations.

---

## Lab Environment

Target Machines

* Metasploitable2
* DVWA (Damn Vulnerable Web Application)

Attacker Machine

* Kali Linux

---

## Outcome

The assessment successfully demonstrated vulnerabilities such as:

* SQL Injection
* Outdated Services
* Exposed Network Ports

Recommendations were provided to improve system security.
