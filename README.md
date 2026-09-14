# SIH26163 — Security Assessment of World Monitor Application

**Team:** Aditya Srivastava, Aadarsh Abhay Raj, Saransh, 
Krish Soni, Pratham Barde, Tehzeeb Dalal  
**Institution:** IIIT Bangalore  
**Organization:** National Technical Research Organisation (NTRO)  
**Theme:** Blockchain & Cybersecurity

---

## Problem Statement
Conduct an authorized security assessment of the World Monitor 
application to identify vulnerabilities, assess their impact, 
demonstrate proof-of-concept in a controlled environment, and 
recommend remediation measures.

## Target Application
- Live App: https://www.worldmonitor.app
- Source Code: https://github.com/koala73/worldmonitor

---

## Our Methodology
We followed the OWASP Top 10 framework for web application 
security testing, combined with API security assessment 
using the application's published OpenAPI specification.

**Tools Used:**
- Browser Developer Tools (Network tab analysis)
- OpenAPI specification analysis (214 endpoints reviewed)
- Manual API endpoint testing
- Source code review

---

## Key Findings Summary

| ID | Severity | Title |
|----|----------|-------|
| F1 | 🔴 CRITICAL | Unauthenticated Military Theater Posture Access |
| F2 | 🔴 CRITICAL | Unauthenticated Cyber Threat Intelligence Access |
| F3 | 🔴 CRITICAL | Unauthenticated DDoS Attack Intelligence Access |
| F4 | 🟠 HIGH | Unauthenticated Aviation Safety Data Access |
| F5 | 🟠 HIGH | Systemic API Authentication Design Flaw (152/214 endpoints) |
| F6 | 🟡 MEDIUM | Subscription Paywall Bypass |

---

## Repository Structure
