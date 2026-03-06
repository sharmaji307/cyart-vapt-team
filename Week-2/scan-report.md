# Vulnerability Scanning Lab

Target: Metasploitable2

Tool Used: Nmap

Command Used

nmap -sV 192.168.56.101

---

## Scan Results

| Scan ID | Vulnerability   | CVSS Score | Priority | Host           |
| ------- | --------------- | ---------- | -------- | -------------- |
| 001     | Open FTP Port   | 6.5        | Medium   | 192.168.56.101 |
| 002     | Outdated Apache | 8.2        | High     | 192.168.56.101 |
| 003     | SMB Service     | 7.5        | High     | 192.168.56.101 |

---

## Risk Analysis

Open services may allow attackers to exploit vulnerabilities in outdated software.

Regular patching and service hardening is recommended.
