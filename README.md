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
| Folder | Contents |
|--------|----------|
| /findings | Documented vulnerabilities with evidence |
| /dashboard | Security assessment reporting dashboard |
| /scripts | Automated endpoint testing scripts |
| /report | Final assessment report and PPT |

---

## Solution: SecureScope Dashboard
An interactive security assessment dashboard that visualizes 
all findings with severity ratings, proof-of-concept evidence, 
and remediation recommendations.

---

## Current Progress (Sept 19, 2026)
- ✅ Target application mapped — 214 API endpoints analyzed
- ✅ 6 vulnerabilities identified (3 Critical, 2 High, 1 Medium)
- ✅ CVSS scores: 9.1, 9.1, 8.6, 7.5, 7.5, 5.3
- ✅ Proof-of-concept documented with live evidence
- ✅ SecureScope dashboard built — /dashboard/index.html
- 🔄 Demo video in progress
- 🔄 Final PDF submission in progress
