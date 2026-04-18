# Cybersecurity Writeups

Concept-focused writeups and methodology notes from structured training plus independent local lab practice.

---

## Learning Scope

- Linux fundamentals and secure system operation
- HTTP and web application behavior analysis
- Reconnaissance and enumeration workflows
- Injection risk concepts (SQLi, XSS) in controlled environments
- Security documentation discipline and repeatable learning structure

---

## Core Track Summaries

### Linux Foundations

**What this covers:** shell operations, permissions, environment handling, process control, and scripting basics.

**Writeups:**
- [File Permissions](linux-luminarium/file-permissions.md)
- [Environment Variables](linux-luminarium/environment-variables.md)
- [Shell Scripting](linux-luminarium/shell-scripting.md)
- [Process Control](linux-luminarium/process-control.md)
- [Piping](linux-luminarium/piping.md)
- [PATH Manipulation](linux-luminarium/path-manipulation.md)
- [Data Dealings](playing-with-programs/data-dealings.md)

### Web Security & Reconnaissance

**What this covers:** request/response analysis, endpoint discovery, and input-driven vulnerability awareness.

**Writeups:**
- [Web Fundamentals](tryhackme/web-fundamentals-networking-http-security.md)
- [Web Enumeration & Reconnaissance](tryhackme/web-enumeration-and-reconnaissance.md)
- [Gobuster Enumeration Methodology](tryhackme/gobuster-enumeration-methodology.md)
- [XSS Fundamentals](tryhackme/xss-cross-site-scripting-fundamentals.md)
- [SQL Injection Fundamentals](tryhackme/sql-injection-authentication-bypass.md)
- [File Upload Security Risks](tryhackme/file-upload-and-web-shells.md)

### Security Fundamentals

**What this covers:** security principles, cryptography basics, system architecture, and defensive context.

**Writeups:**
- [Offensive & Defensive Security Intro](tryhackme/offensive-defensive-security-intro.md)
- [Computer Fundamentals & OS Security](tryhackme/computer-fundamentals-virtualization-os-security.md)
- [Security Fundamentals, Crypto & Recon](tryhackme/security-fundamentals-crypto-recon-programming.md)
- [Practical Attack Lifecycle Summary](tryhackme/practical-attack-lifecycle-summary.md)
- [NTLM Credential Exposure & Moniker Link Risk](tryhackme/ntlm-credential-exposure-and-moniker-link-risk.md)

---

## Independent Lab Work (VulnVault)

This repository also includes documentation from self-directed local lab work where the vulnerable app environment was deployed and analyzed in an authorized, controlled setup.

### Practical Outcomes

- Built and ran a local web security lab end-to-end
- Practiced intercepting and inspecting HTTP traffic
- Studied how unsafe input handling can impact authentication and browser behavior
- Connected recon, enumeration, and validation into one repeatable workflow

---

## Tools Practiced

- Linux terminal and Bash
- Python and pip for local app execution
- Git for lab/tool and documentation management
- Burp Suite Community for request inspection
- Gobuster for directory/resource discovery
- Nmap for service exposure visibility
- Wireshark and browser DevTools for protocol/application observation

---

## Current Level and Direction

**Current stage:** Beginner → Early Practical Pentesting

**Next focus:**
- Deeper XSS and SQLi understanding from a secure coding perspective
- Stronger Burp Suite request analysis workflows
- Advanced enumeration interpretation and reporting quality
- Continued concept-first documentation growth

---

*This repository shares concepts, skills, writeups, and notes only. No direct platform solutions or sensitive exploitation instructions are included.*
