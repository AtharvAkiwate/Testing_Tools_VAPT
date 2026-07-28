# Testing Tools (VAPT)

## Overview

This project demonstrates the complete Vulnerability Assessment and Penetration Testing (VAPT) lifecycle in a controlled virtual laboratory environment. The assessment was performed against the Metasploitable2 virtual machine using Kali Linux and industry-standard cybersecurity tools.

The project includes vulnerability discovery, controlled exploitation, web traffic interception, and remediation recommendations.

---

## Objectives

- Perform vulnerability assessment on a target machine.
- Identify open ports and running services.
- Detect known vulnerabilities.
- Perform controlled penetration testing.
- Capture and analyze HTTP requests.
- Recommend security improvements.

---

## Tools Used

- Kali Linux
- VMware Workstation
- Metasploitable2
- Nmap
- Nikto
- Metasploit Framework
- Burp Suite Community Edition

---

## Project Workflow

1. Network Connectivity Verification
2. Port Scanning using Nmap
3. Service Enumeration
4. Web Vulnerability Scanning using Nikto
5. Exploitation using Metasploit Framework
6. HTTP Request Interception using Burp Suite
7. Vulnerability Analysis
8. Remediation Recommendations

---

## Folder Structure

```
Testing_Tools_VAPT
│
├── Nmap Results
├── Nikto Results
├── Report
└── Screenshots
```

---

## Key Findings

- Multiple TCP ports were identified.
- VSFTPD 2.3.4 Backdoor Vulnerability detected.
- Outdated Apache Web Server identified.
- Directory indexing enabled.
- Information disclosure issues observed.
- Remote command execution successfully demonstrated in a controlled environment.
- HTTP requests intercepted using Burp Suite.

---

## Learning Outcomes

- Network reconnaissance
- Vulnerability assessment
- Web server security testing
- Controlled penetration testing
- HTTP request analysis
- Security documentation

---

## Disclaimer

This project was performed only inside a controlled virtual laboratory for educational purposes. No unauthorized systems were targeted.

---

## Author

Atharv Akiwate
