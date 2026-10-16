# Learn-SecByte-CTF-Labs-Collection-Security-Logging-Active-Directory-PrivEsc-Basics
A curated collection of hands-on cybersecurity CTF labs covering Security Logging &amp; SIEM Monitoring, Active Directory Fundamentals, Windows/Linux Privilege Escalation Basics, Secure Network Architecture, OWASP Top 10, and Password Cracking from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a structured, searchable index of hands-on security logging and SIEM monitoring, Active Directory authentication fundamentals, Windows/Linux privilege escalation baselines, secure network architecture, password hash cracking, and introductory vulnerability exploitation labs designed for cybersecurity students, CTF players, SOC analysts, penetration testers, and defensive security engineers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Establishing a defensive baseline and understanding core attack vectors are fundamental requirements for both blue team defenders and offensive security practitioners. Hosted on [Learn SecByte](https://learn.secbyte.org/), this foundational collection of CTF challenge labs provides essential training across core security operations and system fundamentals.

From transforming raw system event noise into actionable security logging, SIEM monitoring, and incident triage, to navigating Active Directory domain logins, escalating privileges on Windows and Linux systems, designing secure network trust boundaries, cracking password hashes, and mastering OWASP Top 10 web security basics, these exercises build complete, well-rounded security proficiency.

---

## Lab Collection & Index

Below is the complete, searchable index of all security logging, Active Directory, privilege escalation, network architecture, and security fundamentals challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Active Directory Fundamentals: From Domain Login to Detection** | Active Directory & System Fundamentals | Domain Controllers, Kerberos/NTLM logins, Active Directory objects, event logging, login anomaly detection | [Access Lab](https://learn.secbyte.org/ctf/active-directory-fundamentals-from-domain-login-to-detection) |
| 2 | **Windows Privilege Escalation Basics** | System Privilege Escalation | Unquoted service paths, weak service permissions, scheduled tasks, UAC bypass vectors, Accesschk usage | [Access Lab](https://learn.secbyte.org/ctf/windows-privilege-escalation-basics) |
| 3 | **Linux Privilege Escalation Basics: From Enumeration to Root** | System Privilege Escalation | SUID/SGID binaries, LinPEAS enumeration, sudo misconfigurations, GTFOBins exploitation, cron job abuse | [Access Lab](https://learn.secbyte.org/ctf/linux-privilege-escalation-basics-from-enumeration-to-root) |
| 4 | **Exploitation Fundamentals: From Surface to Shell** | Web & Vulnerability Assessment | Vulnerability scanning, payload staging, netcat listeners, interactive reverse shell handling, flag capture | [Access Lab](https://learn.secbyte.org/ctf/exploitation-fundamentals-from-surface-to-shell) |
| 5 | **Security Logging and Monitoring: From Noise to Insight** | Security Logging & Network Architecture | Event log collection, SIEM parsing rules, log reduction, identifying operational anomalies, telemetry baselining | [Access Lab](https://learn.secbyte.org/ctf/security-logging-and-monitoring-from-noise-to-insight) |
| 6 | **Secure Network Architecture** | Security Logging & Network Architecture | Network segmentation, DMZ design, firewall rule configuration, zero-trust network principles | [Access Lab](https://learn.secbyte.org/ctf/secure-network-architecture) |
| 7 | **Security Logging and Monitoring: From Noise to Actionable Evidence** | Security Logging & Network Architecture | Forensic log collection, chain of custody, syslog aggregation, correlation rule development, evidentiary triage | [Access Lab](https://learn.secbyte.org/ctf/security-logging-and-monitoring-from-noise-to-actionable-evi) |
| 8 | **Security Logging and Monitoring: From Noise to Incident** | Security Logging & Network Architecture | Automated alert correlation, incident creation, threat hunting, severity classification, SOC workflow automation | [Access Lab](https://learn.secbyte.org/ctf/security-logging-and-monitoring-from-noise-to-incident) |
| 9 | **Secure Network Architecture: Defend the Trust Boundaries** | Security Logging & Network Architecture | Trust boundary mapping, internal perimeter defense, VLAN hopping prevention, network access control (NAC) | [Access Lab](https://learn.secbyte.org/ctf/secure-network-architecture-defend-the-trust-boundaries) |
| 10 | **Password Security and Cracking Concepts** | Web & Vulnerability Assessment | Hashing algorithms (MD5, SHA256, bcrypt), salt mechanics, dictionary attacks, Hashcat/John the Ripper usage | [Access Lab](https://learn.secbyte.org/ctf/password-security-and-cracking-concepts) |
| 11 | **Web Security Basics and OWASP Top 10** | Web & Vulnerability Assessment | Injection flaws, broken authentication, sensitive data exposure, security misconfigurations, XSS basics | [Access Lab](https://learn.secbyte.org/ctf/web-security-basics-and-owasp-top-10) |
| 12 | **Vulnerability Assessment Fundamentals 3** | Web & Vulnerability Assessment | Automated vulnerability scanning, CVE matching, CVSS scoring, report writing, remediation validation | [Access Lab](https://learn.secbyte.org/ctf/vulnerability-assessment-fundamentals-3) |

---

## Categories

### 1. Security Logging, SIEM Monitoring & Network Architecture
Collect, parse, and correlate system event telemetry into actionable evidence, while designing segmented network trust boundaries.
- [Security Logging and Monitoring: From Noise to Insight](https://learn.secbyte.org/ctf/security-logging-and-monitoring-from-noise-to-insight)
- [Security Logging and Monitoring: From Noise to Actionable Evidence](https://learn.secbyte.org/ctf/security-logging-and-monitoring-from-noise-to-actionable-evi)
- [Security Logging and Monitoring: From Noise to Incident](https://learn.secbyte.org/ctf/security-logging-and-monitoring-from-noise-to-incident)
- [Secure Network Architecture](https://learn.secbyte.org/ctf/secure-network-architecture)
- [Secure Network Architecture: Defend the Trust Boundaries](https://learn.secbyte.org/ctf/secure-network-architecture-defend-the-trust-boundaries)

### 2. System Privilege Escalation & Active Directory
Identify host-level privilege escalation pathways on Windows and Linux targets, and analyze Active Directory domain authentication flows.
- [Active Directory Fundamentals: From Domain Login to Detection](https://learn.secbyte.org/ctf/active-directory-fundamentals-from-domain-login-to-detection)
- [Windows Privilege Escalation Basics](https://learn.secbyte.org/ctf/windows-privilege-escalation-basics)
- [Linux Privilege Escalation Basics: From Enumeration to Root](https://learn.secbyte.org/ctf/linux-privilege-escalation-basics-from-enumeration-to-root)

### 3. Web Security, Password Cracking & Vulnerability Assessment
Learn fundamental web application attack vectors, perform automated vulnerability scans, and crack password hashes using dictionary rules.
- [Web Security Basics and OWASP Top 10](https://learn.secbyte.org/ctf/web-security-basics-and-owasp-top-10)
- [Password Security and Cracking Concepts](https://learn.secbyte.org/ctf/password-security-and-cracking-concepts)
- [Vulnerability Assessment Fundamentals 3](https://learn.secbyte.org/ctf/vulnerability-assessment-fundamentals-3)
- [Exploitation Fundamentals: From Surface to Shell](https://learn.secbyte.org/ctf/exploitation-fundamentals-from-surface-to-shell)

---

## Learning Path

Follow this structured progression path to build core proficiency across defensive monitoring, system administration, and introductory security testing:

1. **Phase 1: Web Security, Password Cracking & Scanning** — Master fundamental security concepts, password algorithms, and vulnerability assessment:
   - [Web Security Basics and OWASP Top 10](https://learn.secbyte.org/ctf/web-security-basics-and-owasp-top-10)
   - [Password Security and Cracking Concepts](https://learn.secbyte.org/ctf/password-security-and-cracking-concepts)
   - [Vulnerability Assessment Fundamentals 3](https://learn.secbyte.org/ctf/vulnerability-assessment-fundamentals-3)
   - [Exploitation Fundamentals: From Surface to Shell](https://learn.secbyte.org/ctf/exploitation-fundamentals-from-surface-to-shell)

2. **Phase 2: Operating System Privilege Escalation & Active Directory** — Learn Windows/Linux enumeration and Active Directory domain login mechanics:
   - [Linux Privilege Escalation Basics: From Enumeration to Root](https://learn.secbyte.org/ctf/linux-privilege-escalation-basics-from-enumeration-to-root)
   - [Windows Privilege Escalation Basics](https://learn.secbyte.org/ctf/windows-privilege-escalation-basics)
   - [Active Directory Fundamentals: From Domain Login to Detection](https://learn.secbyte.org/ctf/active-directory-fundamentals-from-domain-login-to-detection)

3. **Phase 3: Secure Network Architecture & Trust Boundaries** — Design resilient network perimeters and enforce segmentation controls:
   - [Secure Network Architecture](https://learn.secbyte.org/ctf/secure-network-architecture)
   - [Secure Network Architecture: Defend the Trust Boundaries](https://learn.secbyte.org/ctf/secure-network-architecture-defend-the-trust-boundaries)

4. **Phase 4: Security Logging, SIEM Telemetry & Incident Triage** — Collect log streams, configure detection rules, and correlate actionable evidence:
   - [Security Logging and Monitoring: From Noise to Insight](https://learn.secbyte.org/ctf/security-logging-and-monitoring-from-noise-to-insight)
   - [Security Logging and Monitoring: From Noise to Actionable Evidence](https://learn.secbyte.org/ctf/security-logging-and-monitoring-from-noise-to-actionable-evi)
   - [Security Logging and Monitoring: From Noise to Incident](https://learn.secbyte.org/ctf/security-logging-and-monitoring-from-noise-to-incident)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario requirements and target environment directives on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy security analysis tools (Splunk, Elastic Stack, Wireshark, Hashcat, John the Ripper, LinPEAS, WinPEAS, Burp Suite) inside an isolated laboratory environment.
4. Enumerate local targets, analyze SIEM log streams, escalate system privileges, crack password hashes, defend trust boundaries, and retrieve target flags.

---

## Disclaimer

This repository and its linked resources are strictly intended for educational, threat research, and authorized technical training purposes. Never execute vulnerability scanners, privilege testing tools, or password cracking scripts against unauthorized systems, production infrastructure, or unapproved networks.
