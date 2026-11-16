# ISO 27001:2022 Internal Audit & Gap Assessment (GRC_project1)

## 🏢 Client Overview
**Organization:** FinTech Global (Fictional Mid-Sized Tech Company just for learning purpose).
**Industry:** Financial Technology.
**Audit Scope:** Corporate Network and Cloud Infrastructure.

---

## 🎯 Audit Objective
The objective of this internal audit was to assess the design and operating effectiveness of FinTech Global's network infrastructure against the **ISO/IEC 27001:2022 (Annex A)** standard. The assessment focused on identifying security gaps in access control, endpoint protection, and infrastructure monitoring, providing actionable remediation roadmaps to management.

---

## 🛠️ Methodology & Scope
This audit was conducted using a risk-based approach, simulating real-world GRC consulting engagements.

*   **Core Network Infrastructure:** Reviewed Cisco iOS configurations, VLAN segmentation, and access controls (TACACS+).
*   **Endpoint Security:** Analyzed Microsoft Intune MDM policies, BitLocker encryption status, and local admin rights.
*   **Monitoring & Incident Response:** Evaluated Splunk SIEM log retention, Palo Alto firewall rules, and incident playbooks.
*   **Cloud IAM:** Assessed AWS S3 bucket permissions for infrastructure backups.

---

## 📊 Key Findings & Metrics
A targeted sample of **20 critical controls** was assessed.

*   **Implementation Status:**
    *   ✅ Implemented: 10%
    *   ⚠️ Partially Implemented: 65%
    *   ❌ Not Implemented: 25%

*   **Risk Breakdown:**
    *   🔴 High Risk: 11 Findings
    *   🟡 Medium Risk: 6 Findings
    *   🟢 Low Risk: 3 Findings

### 🚨 Critical Vulnerabilities Identified:
1.  **Identity Access Lifecycle:** Shared admin credentials on core routers and lack of automated HR offboarding (terminated users active for up to 7 days).
2.  **Infrastructure Visibility:** Missing network patching schedule (14 months outdated) and insufficient firewall log retention (7 days local storage only).
3.  **Endpoint Exposure:** Lack of off-network DNS filtering and missing USB Data Loss Prevention (DLP) controls.

---

## 📁 Project Deliverables

### 1. Executive Summary Report
A highly professional 1-page business report designed for C-Suite management, summarizing the audit scope, key findings, and a prioritized remediation roadmap.
*   📄 **[View the Executive Summary PDF](ISO27001_Audit_Executive_Summary(grc_project).pdf)**

### 2. The Audit Tracker Matrix
The master working paper detailing the 20 assessed controls, evidence reviewed, specific gap descriptions, assigned risk owners, and target completion dates.
*   📊 **[View the Excel Audit Tracker](FinTech_Global_ISO27001_Audit_Tracker.xlsx)**

---

## 👨‍💻 About the Author
**Harshil Reddy**
* Network Engineering Background Fresher*
Transitioning from technical network operations into Governance, Risk, and Compliance. This project demonstrates the ability to translate technical infrastructure realities into business risk and compliance frameworks.
