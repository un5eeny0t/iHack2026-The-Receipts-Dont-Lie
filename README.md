# **The Receipts Don’t Lie: Introduction to Log Analysis**

**Hands-on training materials and lab artifacts for the log analysis workshop at iHack 2026, Universiti Teknologi MARA (UiTM) Shah Alam.**

---
**This workshop introduces practical, hands-on log triage directly from the Linux command line. Participants learn how to parse structured system logs using native utilities (`grep`, `awk`, `sort`, `uniq`, `sed`), uncover suspicious behaviors across authentication, web, and mail services, and reconstruct an end-to-end incident timeline from raw forensic evidence.**

---
## **📁 Repository Structure**

```text
.
├── slides/
│   └── iHack 2026 - The Receipt Don't Lie - Slide.pptx   # Workshop presentation deck
├── docs/
│   └── iHack 2026 - Receipt Don't Lie - Lab Sheet.docx   # Student step-by-step lab guide
├── logs/
│   ├── sample-auth.log                                   # SSH & authentication events
│   ├── sample-access.log                                 # Web server request traffic
│   └── sample-mail.log                                   # Postfix mail server records
└── README.md
