# Data Protection Impact Assessment (DPIA)

## 🏢 Client & Product Overview
**Organization:** FinTech Global (Fictional FinTech Enterprise)
**Assessed Product:** "FinVision" (AI-Powered Video KYC & Instant Credit Scoring Module)
**Applicable Frameworks:** EU GDPR (Article 35) & India DPDP Act 2023

---

## 🎯 Assessment Objective
The objective of this DPIA was to evaluate the inherent privacy risks associated with the large-scale processing of **Sensitive Personal Data (Biometrics and Financial Records)** and the use of automated decision-making prior to the launch of the FinVision product. The assessment focused on ensuring strict regulatory compliance regarding user consent, data minimization, algorithmic fairness, and data lifecycle management.

---

## 🛠️ Methodology & Scope
This assessment simulated a rigorous pre-deployment privacy review, mapping the entire data lifecycle from collection to deletion.

*   **Lawful Basis & Consent:** Analyzed biometric capture workflows and age-gating mechanisms for minors.
*   **Automated Decision-Making:** Evaluated the AI credit scoring algorithm for demographic bias and user appeal rights (GDPR Art 22).
*   **Data Lifecycle & Erasure:** Assessed AWS S3 video retention policies and database "soft-deletion" vs. "hard-deletion" routines.
*   **Cross-Border Data Transfers:** Audited secondary database backups against local financial sector data localization mandates (RBI/DPDP).

---

## 📊 Key Findings & Metrics
A targeted sample of **15 critical data processing activities** was evaluated.

*   **Risk Breakdown:**
    *   🔴 High Risk (Regulatory Violation): 11 Findings
    *   🟡 Medium Risk (Control Deficiency): 3 Findings
    *   🟢 Low Risk (Procedural Enhancement): 1 Finding

### 🚨 Critical Vulnerabilities Identified:
1.  **Illegal Consent Capture:** Pre-ticked consent boxes for facial biometrics and lack of verifiable parental consent for users under 18.
2.  **Algorithmic Bias:** The ML model ingests direct PII (Name, Location), creating a high risk of discriminatory lending decisions without human review fallback.
3.  **Data Retention Failures:** Indefinite storage of raw Video KYC files in AWS S3 and failure to cryptographically erase user data upon account deletion requests.
4.  **Localization Violations:** Indian financial data backups are synced to a US-based AWS region, violating data localization guidelines.

---

## 📁 Project Deliverables

### 1. DPO Executive Report
A formal, C-suite ready privacy impact report outlining the critical vulnerabilities and the mandatory "Launch Blocker" remediation roadmap.
*   📄 **[View the DPIA Executive Report PDF](p3_FinTech_Global_FinVision_DPIA_Report.pdf)**

### 2. The DPIA Risk Register
The master working paper detailing the 15 assessed processing activities, the specific GDPR/DPDP Act articles violated, and the required engineering action plans.
*   📊 **[View the Excel Risk Register](p3_FinTech_Global_FinVision_DPIA.xlsx)**

---

## 👨‍💻 About the Author
**Harshil Reddy**
This project demonstrates the ability to map complex data flows, translate global privacy laws (GDPR/DPDP) into actionable engineering requirements, and advocate for data principal rights within corporate product development.
