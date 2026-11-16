# Third-Party Risk Management (TPRM) - SaaS Vendor Assessment

## 🏢 Assessment Overview
**Organization:** FinTech Global
**Assessed Vendor:** DataFlow CRM (SaaS Provider)
**Framework Utilized:** Cloud Security Alliance (CSA) Consensus Assessments Initiative Questionnaire (CAIQ v4.0.1)

---

## 🎯 Objective
FinTech Global is evaluating "DataFlow CRM" to replace its legacy on-premise customer database. Because this platform will process and store Highly Restricted customer financial data, a rigorous Third-Party Risk Assessment was required prior to contract execution. The objective was to evaluate the vendor's self-attested security controls, identify supply chain risks, and define mandatory contract stipulations.

---

## 🛠️ Methodology & Scope
Rather than assessing all 250+ domains of the CAIQ, this targeted assessment focused on the 15 critical domains most relevant to SaaS data hosting and network integration:
*   **Data Security & Information Lifecycle (DSP):** Cryptography at-rest (AES-256) and in-transit (TLS).
*   **Identity & Access Management (IAM):** SAML 2.0 Single Sign-On (SSO) and Multi-Factor Authentication (MFA).
*   **Incident Response & Logging (SEF/LOG):** Breach notification SLAs and SIEM log availability.
*   **Supply Chain Risk (STA):** Sub-processor auditing and offshore contractor vetting.

---

## 📊 Key Findings & Metrics
A targeted sample of **15 critical controls** was assessed based on the vendor's CAIQ responses.

*   **Assessment Status:**
    *   ✅ Pass: 4 Controls
    *   ⚠️ Requires Clarification (Medium Risk): 3 Controls
    *   ❌ Fail (High Risk): 8 Controls

### 🚨 Critical Vulnerabilities & Contract Blockers:
1.  **Cryptographic Downgrade Risk:** Vendor APIs still accept legacy TLS 1.1 connections, exposing FinTech Global to in-transit interception.
2.  **Blindspots in Visibility:** Tenant-level audit logs are not streamed in real-time, and Critical (CVSS 9.0+) vulnerabilities have an unacceptable 30-day patching SLA.
3.  **Insider Threat / Fourth-Party Risk:** Unvetted offshore contractors have logical database access, and the vendor does not formally audit its own downstream sub-processors.

---

## 📁 Project Deliverables

### 1. Vendor Risk Assessment Report
A C-Suite advisory report detailing the identified vulnerabilities and delivering a "Conditional Approval" verdict, pending the execution of a strict security contract addendum.
*   📄 **[View the TPRM Risk Report PDF](GRCl_DataFlowCRM_TPRM_Report.pdf)**

### 2. CAIQ Technical Assessment Tracker
The master spreadsheet documenting the exact CAIQ control IDs, the vendor's self-attested answers, analyst risk assessments, and the required contract stipulations to mitigate those risks.
*   📊 **[View the CAIQ Assessment Tracker](GRC_CAIQ_Vendor_Assessment.xlsx)**

---

## 👨‍💻 About the Author
**[Harshil Reddy]**
* Network Engineering Background*
Leveraging a deep background in network architecture and SOC visibility to critically evaluate third-party vendor infrastructure, API security, and enterprise integration risks.
