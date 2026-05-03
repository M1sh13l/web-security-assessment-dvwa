# Web Application Security Assessment (DVWA Lab)

## Overview

This project demonstrates a structured security assessment conducted on a deliberately vulnerable web application (DVWA) in a controlled lab environment.

The objective was to identify common web vulnerabilities, understand their impact, and propose secure mitigation strategies.

---

## Objectives

* Identify common web application vulnerabilities
* Perform controlled security testing
* Analyze system weaknesses
* Apply secure coding and defense principles

---

## Scope

All testing was performed in a local, controlled environment using DVWA (Damn Vulnerable Web Application).
No real systems or unauthorized targets were involved.

---

## Vulnerabilities Explored

### 1. SQL Injection (SQLi)

* Tested login forms and input fields
* Demonstrated authentication bypass
* Observed how improper query handling exposes databases

### 2. Cross-Site Scripting (XSS)

* Injected client-side scripts into input fields
* Simulated session-related risks
* Demonstrated impact of improper input sanitization

### 3. Input Validation Weaknesses

* Tested how the application handles unexpected input
* Identified lack of validation and sanitization

---

## Tools Used

* Burp Suite (request interception and analysis)
* sqlmap (automated SQL injection testing)
* Browser Developer Tools

---

## Key Findings

* Lack of input validation allows injection attacks
* Absence of prepared statements exposes database queries
* Client-side inputs are not sanitized properly
* Session handling mechanisms are weak

---

## Security Recommendations

* Use prepared statements and parameterized queries
* Implement input validation and sanitization
* Apply proper session management techniques
* Enforce authentication and authorization checks

---

## Screenshots

See the `/screenshots` folder for demonstration of:

* SQL Injection testing
* Request interception using Burp Suite
* XSS input examples

---

## Disclaimer

This project was conducted strictly for educational purposes in a controlled environment.
No unauthorized systems were targeted.
