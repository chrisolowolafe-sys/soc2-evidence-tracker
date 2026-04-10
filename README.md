# SOC 2 Evidence Tracker

**Live Demo:** [soc2-evidence-tracker.pages.dev](https://soc2-evidence-tracker.pages.dev)  
**Built by:** [Chris Olowo, PMP®](https://chris-olowo-grc-portfolio.pages.dev) — GRC Analyst & Risk Practitioner

---

## Overview

A fully interactive, browser-based SOC 2 Type II evidence collection tracker that maps all 37 Trust Service Criteria (TSC) controls to evidence requirements, tracks collection status, assigns owners, monitors due dates, and generates audit-ready reports.

---

## Features

- **37 TSC controls** across 12 categories — load all as placeholders in one click
- **Evidence types** — Policy, Procedure/SOP, Screenshot, System Log, Configuration Export, Audit Report, Contract, Training Record, Risk Assessment, Test Result
- **Status workflow** — Not Started → In Progress → Collected / Overdue / N/A
- **Automatic overdue detection** based on due date
- **Live Audit Readiness Score** — percentage with colour-coded indicator
- **Category Summary** — per-TSC-category progress bars with ISO 27001 mapping table
- **Audit Report** — gaps section, full evidence register, print to PDF / export CSV

---

## SOC 2 TSC Coverage

| Category | Controls |
|---|---|
| CC1 | CC1.1–CC1.5 — Control Environment |
| CC2 | CC2.1–CC2.3 — Communication & Information |
| CC3 | CC3.1–CC3.4 — Risk Assessment |
| CC4 | CC4.1–CC4.2 — Monitoring |
| CC5 | CC5.1–CC5.3 — Control Activities |
| CC6 | CC6.1–CC6.8 — Logical & Physical Access |
| CC7 | CC7.1–CC7.5 — System Operations |
| CC8 | CC8.1 — Change Management |
| CC9 | CC9.1–CC9.2 — Risk Mitigation |
| A1 | A1.1–A1.3 — Availability |
| C1 | C1.1–C1.2 — Confidentiality |
| PI1 | PI1.1–PI1.2 — Processing Integrity |

**Total: 37 TSC controls with ISO 27001:2022 mappings**

---

## Security Architecture

All security headers enforced server-side via Cloudflare `_headers`. Additional: HTTPS enforcement, GitHub Pages redirect, Chart.js SRI, safety stub, XSS prevention, localStorage try/catch, prefers-reduced-motion, no tracking.

---

## Repository Structure

```
soc2-evidence-tracker/
├── index.html    ← Full application
├── _headers      ← Cloudflare security headers
└── README.md     ← This file
```

---

## Complete GRC Portfolio

| Project | Live URL |
|---|---|
| 🏠 ShomriTech GRC Platform | [chris-olowo-grc-portfolio.pages.dev](https://chris-olowo-grc-portfolio.pages.dev) |
| 1️⃣ Vendor Risk Assessment Tool | [vendor-risk-assessment-tool.pages.dev](https://vendor-risk-assessment-tool.pages.dev) |
| 2️⃣ User Access Review Tracker | [user-access-review-tracker.pages.dev](https://user-access-review-tracker.pages.dev) |
| 3️⃣ **SOC 2 Evidence Tracker** *(this repo)* | [soc2-evidence-tracker.pages.dev](https://soc2-evidence-tracker.pages.dev) |
| 4️⃣ NIST AI RMF Gap Assessment | [nist-ai-rmf-assessment.pages.dev](https://nist-ai-rmf-assessment.pages.dev) |
| 5️⃣ Security Questionnaire Library | [security-questionnaire-library.pages.dev](https://security-questionnaire-library.pages.dev) |

---

## Author

**Chris Olowo, PMP®**  
GRC Analyst & Risk Practitioner · Calgary, Canada  
ISO 27001 Lead Auditor · NIST CSF 2.0 · ISO 42001 · GRC · PrivacyOps · PMP®

*Pro bono ISO 42001 AI governance consulting provided to non-profit organizations in Calgary.*

[Portfolio](https://chris-olowo-grc-portfolio.pages.dev) · [LinkedIn](https://www.linkedin.com/in/chris-o-742316135) · [GitHub](https://github.com/chrisolowolafe-sys)

---

*For demonstration and educational purposes only. Not a certified compliance platform or legal service.*
