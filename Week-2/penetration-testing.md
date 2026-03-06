# Penetration Testing Techniques

## Introduction

Penetration testing is a simulated cyber attack performed to identify and exploit vulnerabilities in systems.

The goal is to evaluate security defenses.

---

## Phases of Penetration Testing

### 1 Reconnaissance

Gathering information about the target system.

Techniques:

* WHOIS lookup
* Subdomain enumeration
* DNS reconnaissance

Tools

Shodan
Maltego
Google Dorking

---

### 2 Scanning

Identify open ports, services, and vulnerabilities.

Tools

* Nmap
* OpenVAS
* Nessus

---

### 3 Exploitation

Attackers exploit discovered vulnerabilities.

Tools

Metasploit
sqlmap
Burp Suite

Example vulnerability:

SQL Injection

---

### 4 Post Exploitation

After gaining access, attackers attempt:

* Privilege escalation
* Data extraction
* Persistence

Tool

Meterpreter

---

### 5 Reporting

Security findings are documented including:

* vulnerability description
* risk level
* remediation steps
