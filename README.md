# SOC 2 Evidence Tracker

**Live Demo:** [soc2-evidence-tracker.chrisolowolafe.workers.dev](https://soc2-evidence-tracker.chrisolowolafe.workers.dev)  
**Built by:** [Chris Olowo, PMP®](https://chris-olowo-grc-portfolio.pages.dev) — GRC Analyst & Risk Practitioner

---

## Overview

A fully interactive, browser-based SOC 2 Type II evidence collection tracker that maps all 37 Trust Service Criteria (TSC) controls to evidence requirements, tracks collection status, assigns owners, monitors due dates, and generates audit-ready reports.

---

## Features

### Evidence Register
- Add evidence items linked to any of the 37 SOC 2 TSC controls
- Evidence types: Policy, Procedure/SOP, Screenshot, System Log, Configuration Export, Audit Report, Contract, Training Record, Risk Assessment, Test Result, Interview Notes
- Owner assignment and due date tracking
- Status workflow: Not Started → In Progress → Collected / Overdue / N/A
- Automatic overdue detection based on due date
- Search and filter by status and TSC category
- Edit modal with full field updates
- Load all 37 TSC controls as placeholders in one click

### Audit Readiness Score
- Live percentage score based on collected vs total evidence
- Colour-coded readiness indicator (Green ≥80%, Orange ≥50%, Red <50%)
- Per-category progress bars

### Category Summary
- Readiness breakdown across all 9 Common Criteria categories + Availability, Confidentiality, Processing Integrity
- Full TSC reference table with ISO 27001:2022 control mappings

### Audit Report
- Complete evidence collection status report
- Readiness by Trust Service Category
- Evidence gaps section highlighting overdue and not-started items
- Full evidence register table
- Print to PDF / Export CSV

### Sample Data
- 15 realistic pre-configured evidence items across key controls
- Demonstrates collected, in-progress, overdue, and not-started states

---

## SOC 2 TSC Coverage

| Category | Controls | Description |
|---|---|---|
| CC1 | CC1.1–CC1.5 | Control Environment |
| CC2 | CC2.1–CC2.3 | Communication & Information |
| CC3 | CC3.1–CC3.4 | Risk Assessment |
| CC4 | CC4.1–CC4.2 | Monitoring Activities |
| CC5 | CC5.1–CC5.3 | Control Activities |
| CC6 | CC6.1–CC6.8 | Logical & Physical Access Controls |
| CC7 | CC7.1–CC7.5 | System Operations |
| CC8 | CC8.1 | Change Management |
| CC9 | CC9.1–CC9.2 | Risk Mitigation |
| A1 | A1.1–A1.3 | Availability |
| C1 | C1.1–C1.2 | Confidentiality |
| PI1 | PI1.1–PI1.2 | Processing Integrity |

**Total: 37 TSC controls with ISO 27001:2022 mappings**

---

## Security Architecture

All security headers enforced server-side via Cloudflare `_headers`:

| Header | Value |
|---|---|
| `X-Frame-Options` | `DENY` |
| `X-Content-Type-Options` | `nosniff` |
| `Referrer-Policy` | `strict-origin-when-cross-origin` |
| `Strict-Transport-Security` | `max-age=63072000; includeSubDomains; preload` |
| `Content-Security-Policy` | Strict allowlist |
| `Permissions-Policy` | Geolocation, microphone, camera, payment denied |

Additional: HTTPS enforcement, GitHub Pages redirect, Chart.js SRI, safety stub, XSS prevention, localStorage try/catch, prefers-reduced-motion, no tracking.

---

## Repository Structure

```
soc2-evidence-tracker/
├── index.html    ← Full application
├── _headers      ← Cloudflare security headers
└── README.md     ← This file
```

---

## Part of the GRC Portfolio

| Project | Status |
|---|---|
| [ShomriTech GRC Platform](https://chris-olowo-grc-portfolio.pages.dev/grc-platform) | ✅ Live |
| [Vendor Risk Assessment Tool](https://vendor-risk-assessment-tool.chrisolowolafe.workers.dev) | ✅ Live |
| [User Access Review Tracker](https://user-access-review-tracker.chrisolowolafe.workers.dev) | ✅ Live |
| **SOC 2 Evidence Tracker** *(this repo)* | ✅ Live |
| NIST AI RMF Gap Assessment | Coming soon |

---

## Author

**Chris Olowo, PMP®**  
GRC Analyst & Risk Practitioner · Calgary, Canada  
ISO 27001 Lead Auditor · NIST CSF 2.0 · GRC · PrivacyOps · ISO 42001

[Portfolio](https://chris-olowo-grc-portfolio.pages.dev) · [LinkedIn](https://www.linkedin.com/in/chris-o-742316135)

---

*For demonstration and educational purposes only. Not a certified compliance platform or legal service.*
