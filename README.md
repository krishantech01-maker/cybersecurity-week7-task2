# Web Application Penetration Testing with OWASP ZAP (Week 7 - Task 2)

## Overview
This repository contains the deliverables for **Week 7 - Task 2** of the Cyber Security Internship. The project demonstrates an end-to-end web application penetration test performed using **OWASP ZAP (Zed Attack Proxy)** to discover, exploit, and document critical OWASP Top 10 vulnerabilities—including **SQL Injection (SQLi)**, **Cross-Site Scripting (XSS)**, and **Broken Authentication**—along with actionable remediation steps.

## Repository Structure
* `docs/OWASP_ZAP_Pentest_Report.md` - Comprehensive penetration testing report detailing ZAP configuration (Spider, AJAX Spider, Active Scan), risk findings, and security recommendations.
* `docs/PoC_Exploits_and_Vectors.md` - Detailed attack vector analysis and reproducible Proof-of-Concept (PoC) HTTP requests/payloads validated via ZAP Manual Request Editor.

## Tools & Standards Used
* **Primary Tool:** OWASP ZAP (Automated Scanner, Traditional & AJAX Spider, Passive/Active Scan, Fuzzer, Manual Request Editor)
* **Target Lab:** OWASP Juice Shop / DVWA (`http://localhost:3000`)
* **Framework:** OWASP Web Security Testing Guide (WSTG) & OWASP Top 10 (2021)
