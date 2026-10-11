# Section 4 – Securing Software

## Introduction
Software security focuses on designing, developing, testing, and maintaining applications in ways that reduce vulnerabilities and resist attacks. Since modern applications process sensitive data and connect users across networks, weaknesses in software can become entry points for attackers.

This section explored how software works, how vulnerabilities emerge, and how developers and security professionals reduce risk.

---

## Foundations of Web Applications

### HTML (HyperText Markup Language)
HTML structures content displayed in web applications.

### JavaScript
JavaScript adds interactivity and dynamic behavior to applications.

### Cascading Style Sheets (CSS)
CSS controls presentation and visual design.

Understanding these technologies helps explain how web applications function and where security issues may appear.

---

## User Manipulation and Application Attacks

### Phishing
Phishing targets users through deceptive messages or websites designed to collect sensitive information.

### Code Injection
Code injection occurs when malicious input causes unintended execution within an application.

---

## Cross-Site Scripting (XSS)

XSS occurs when attackers inject malicious scripts into web pages.

Types explored:

### Reflected XSS
Malicious scripts are immediately returned in responses.

### Stored XSS
Malicious content is permanently stored and later delivered to users.

### Character Escaping
Character escaping reduces unintended execution by treating special characters as ordinary text.

---

## Database Security

### SQL (Structured Query Language)
SQL is used to manage and retrieve database information.

### Prepared Statements
Prepared statements separate commands from user input and reduce injection risks.

---

## Command Injection

Command injection occurs when applications unintentionally allow execution of system commands.

### Eval
Functions that execute dynamically generated code can introduce security risks when input handling is unsafe.

---

## Browser and Client-Side Security

### Developer Tools
Browser developer tools allow inspection and debugging of web applications.

### Checkboxes and Client Controls
User interface controls alone should not be trusted for security decisions.

### Client-Side Validation
Input validation performed in the browser improves usability but cannot guarantee security.

### Server-Side Validation
Server-side validation verifies data after submission and provides stronger protection.

---

## Request and Session Security

### Cross-Site Request Forgery (CSRF)
CSRF tricks authenticated users into performing unintended actions.

### GET Requests
Used primarily to retrieve information.

### POST Requests
Commonly used to submit or modify information.

---

## Advanced Software Exploitation

### Remote Code Execution (RCE)
RCE vulnerabilities allow execution of code on remote systems.

### Buffer Overflow
Occurs when excess data overwrites memory boundaries.

### Stack Overflow
A memory-related condition that may cause application instability or unexpected behavior.

---

## Software Investigation and Analysis

### Cracking
Cracking refers to bypassing protections or restrictions in software.

### Reverse Engineering
Reverse engineering studies software behavior and internal logic.

### Malware Analysis
Malware analysis examines malicious programs to understand behavior and improve defense.

---

## Software Distribution and Trust

### Open Source Software
Software with publicly accessible source code.

Advantages:
- Transparency
- Community review

### Closed Source Software
Software with restricted source code access.

### App Stores
Application marketplaces that provide software distribution and security controls.

### Package Managers
Tools used to install, update, and manage software dependencies.

### Operating Systems
Operating systems manage hardware resources and provide environments for applications.

---

## Vulnerability Discovery and Management

### Bug Bounty Programs
Programs that reward security researchers for reporting vulnerabilities.

### Vulnerability Catalogs
Databases that organize known software weaknesses.

### CVE (Common Vulnerabilities and Exposures)
Standardized identifiers for publicly disclosed vulnerabilities.

### CVSS (Common Vulnerability Scoring System)
Measures vulnerability severity.

### EPSS (Exploit Prediction Scoring System)
Estimates the likelihood that vulnerabilities may be exploited.

### KEV (Known Exploited Vulnerabilities)
Catalogs vulnerabilities confirmed to be actively exploited.

---

## Personal Reflection
This section changed my perspective on software development by showing that functionality alone is not enough. Applications must be designed with security in mind because attackers often target user input, application logic, dependencies, and overlooked implementation details.

---

## Key Takeaways
- Secure software begins during development.
- Input validation reduces many common attacks.
- Client-side protections alone are insufficient.
- Vulnerability management is continuous.
- Software trust depends on both code quality and maintenance.
