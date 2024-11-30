# NahamStore-Report
Detailed penetration testing report for NahamStore, covering vulnerabilities such as SQL Injection, XSS, and RCE with exploitation steps and mitigation strategies

# NahamStore Penetration Testing Report

## Overview
This repository contains a comprehensive penetration testing report for NahamStore, documenting discovered vulnerabilities and exploitation techniques.

## Table of Contents
1. **Methodology**: Steps for reconnaissance, enumeration, and exploitation.
2. **Findings**:
   - SQL Injection (SQLi)
   - Cross-Site Scripting (XSS)
   - Remote Code Execution (RCE)
   - Local File Inclusion (LFI)
   - Server-Side Request Forgery (SSRF)
   - Insecure Direct Object References (IDOR)
3. **Exploitation Details**:
   - Using tools like Nmap, Gobuster, and manual payloads.
4. **Recommendations**: Mitigation strategies for identified vulnerabilities.

## Key Findings
- **SQL Injection**: Login form allowed bypass authentication.
- **XSS**: Multiple parameters were vulnerable to stored and reflected XSS.
- **RCE**: Achieved remote code execution through file upload vulnerability.
- **LFI**: Exploited directory traversal to access sensitive files.
- **SSRF**: Accessed internal resources using SSRF vulnerability.

## Tools Used
- **Nmap**: For network scanning.
- **Gobuster**: For directory enumeration.
- **Burp Suite**: For interception and injection testing.
- **Custom Scripts**: For payload delivery and exploitation.

by AbdElRhman Mohamed Salah Khalil
لاغ
