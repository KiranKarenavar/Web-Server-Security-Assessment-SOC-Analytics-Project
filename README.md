# Web Server Security Assessment & SOC Analytics Project

## Author
Kiran Karenavar

---

## Project Overview
This project demonstrates a complete **end-to-end cybersecurity workflow**, starting from web server lab setup and penetration testing to **SOC-focused log analysis and incident response**.

All activities were conducted in a **controlled lab environment** to simulate real-world attacks and analyze them from a **Security Operations Center (SOC)** perspective.

---

## Objectives
- Understand common web server attack techniques
- Simulate real-world attacks in a safe lab environment
- Analyze system and service logs
- Detect malicious activities
- Perform SOC-style incident analysis and response
- Map attacks to the **MITRE ATT&CK framework**
- Create professional cybersecurity documentation

---

## Lab Environment
- **Target System:** Ubuntu Server (LAMP Stack)
- **Attacker System:** Kali Linux
- **Environment Type:** Controlled Lab
- **Services Tested:**
  - SSH
  - FTP
  - MySQL
  - SMTP

---

## Lab Setup
The lab environment was configured using the LAMP stack to host multiple network services for security testing. This setup provided a realistic web server environment for simulating attacks and analyzing defensive responses.

Technologies used:
- Linux (Ubuntu)
- Apache Web Server
- MySQL Database
- PHP
- phpMyAdmin

---

## Penetration Testing Activities
Penetration testing was performed to simulate attacker behavior and identify security weaknesses in commonly used services.

### Services Tested
- **FTP:** Anonymous login testing, brute-force attacks, and service enumeration  
- **SSH:** Brute-force attacks, authentication abuse, and key-based access testing  
- **MySQL:** Credential abuse, remote access testing, and database enumeration  
- **SMTP:** Mail service abuse and misconfiguration testing  

These activities were conducted strictly for educational purposes to understand attacker techniques and improve defensive detection capabilities.

---

## SOC Log Analysis and Detection
Following the attack simulations, system and application logs were analyzed from a **SOC analyst perspective**.

Key activities included:
- Reviewing authentication and service logs
- Identifying Indicators of Compromise (IOCs)
- Detecting brute-force and unauthorized access attempts
- Assigning severity levels based on impact
- Documenting detection logic for each service

Logs analyzed:
- SSH authentication logs
- FTP service logs
- MySQL database logs
- SMTP mail logs

---

## Incident Response Analysis
A formal **SOC Incident Response Report** was created to document the security incident lifecycle.

The report includes:
- Incident identification and analysis
- Indicators of Compromise (IOCs)
- Attack timeline
- Containment actions
- Eradication and recovery steps
- Lessons learned from a blue-team perspective

This demonstrates practical understanding of SOC workflows and incident handling procedures.

---

## MITRE ATT&CK Mapping

| Service | Tactic | Technique |
|------|------|------|
| SSH | Credential Access | T1110 – Brute Force |
| FTP | Initial Access | T1078 – Valid Accounts |
| MySQL | Credential Access | T1110 – Brute Force |
| SMTP | Command and Control | T1071 – Application Layer Protocol |

---

## Skills Demonstrated
- Linux system administration
- Network and service enumeration
- Penetration testing fundamentals
- Log analysis and threat detection
- SOC incident response workflow
- MITRE ATT&CK framework
- Security reporting and documentation

---

## Target Roles
This project is relevant for:
- SOC Analyst (Level 1)
- Cybersecurity Analyst
- Blue Team Intern / Fresher

---

## Disclaimer
⚠️ **Disclaimer:**  
All testing activities were conducted in a **controlled lab environment** for educational purposes only.  
No real-world systems, networks, or organizations were targeted.

---

## Contact
Email: kirankarenavar15@gmail.com
LinkedIn: https://linkedin.com/in/yourprofile  
GitHub: [https://github.com/](https://github.com/KiranKarenavar)
