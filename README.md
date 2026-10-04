# Mediro-General-Hospital-Week-4-Cyber-Security-Assessment
Week 4 cybersecurity assessment covering penetration testing, evidence collection, security findings, and remediation recommendations.

# Mediroza Hospital – Week 4 Cybersecurity Assessment

**Participant:** Abdulmudallif Ibrahim  
**Program:** Cybersecurity Internship / Workflow Program  
**Week:** 4  
**Focus:** Penetration Testing, Evidence Collection & Security Assessment

---

## Overview

This repository contains the documentation and evidence produced during the Week 4 cybersecurity assessment.

The assessment focused on practical penetration-testing activities, evidence collection, vulnerability identification, database exposure analysis, risk assessment, and professional security reporting.

All testing was performed within the authorized assessment environment provided for the internship.

---

## Assessment Scope

**Target:**

`https://medirozahospital.com`

The assessment covered the provided Mediroza Hospital web application and the associated resources exposed within the authorized training environment.

---

## Milestones

### Milestone 1 – Web Application Assessment

Activities included:

- Reviewing exposed web resources
- Analyzing `robots.txt`
- Identifying accessible application paths
- Username enumeration testing
- SQL injection testing
- Authentication bypass validation
- Reviewing accessible patient reports

**Status:** Completed

---

### Milestone 2 – PDF Security Assessment

Activities included:

- Reviewing accessible PDF reports
- Testing PDF password protection
- Password recovery/cracking using the provided assessment methodology
- Decrypting recovered PDF files
- Validating access to protected documents

**Status:** Completed

---

### Milestone 3 – Metadata & Database Exposure

Activities included:

- Metadata analysis using `exiftool`
- Identifying sensitive document metadata
- Investigating the exposed `/old/` directory
- Identifying the exposed database backup
- Reviewing staff and shareholder records
- Correlating metadata with database information

**Status:** Completed

---

### Milestone 4 – Findings & Risk Assessment

The assessment identified the following security findings:

| # | Finding | Risk |
|---|---|---|
| 1 | Username Enumeration | Medium |
| 2 | SQL Injection Authentication Bypass | Critical |
| 3 | Unauthorized Access to Encrypted PDF Reports | High |
| 4 | Weak PDF Passwords | High |
| 5 | Sensitive PDF Metadata Exposure | Medium |
| 6 | Exposed Backup Directory | Critical |
| 7 | Confidential Database Information Exposure | Critical |

**Status:** Completed

---

## Key Security Observations

The assessment demonstrated several security weaknesses, including:

- Authentication weaknesses
- SQL injection
- Insufficient access control
- Weak document passwords
- Sensitive metadata exposure
- Publicly accessible backup resources
- Exposure of confidential staff and shareholder information

---

## Evidence

Evidence has been organized according to each milestone:

```text
screenshots/
├── milestone-1/
├── milestone-2/
├── milestone-3/
└── milestone-4/

