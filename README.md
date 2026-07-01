# NIST CSF 2.0 Risk Assessment & Governance Policy Framework
## Client: BlackSea E-Com Fulfillment (BEF)

## 📌 Project Overview
This repository contains a comprehensive, end-to-end manual Governance, Risk, and Compliance (GRC) audit conducted for **BlackSea E-Com Fulfillment (BEF)**, a hybrid-infrastructure logistics and supply chain company based in Burgas, Bulgaria. 

The primary objective of this project was to analyze BEF's current technical environment, operational workflows, and employee security habits against the standard guidelines of the **NIST Cybersecurity Framework (CSF) 2.0**. Using a manual audit methodology, I identified critical security gaps, evaluated their risk postures, provided actionable remediation strategies, and drafted formal governance policies to align the business with modern cybersecurity standards.

---

## 🛠️ Methodology & Risk Scoring System

To evaluate the overall threat landscape of the organization, a structured **Inherent Risk Scoring Matrix** was used. Each identified security gap was assessed qualitatively based on **Likelihood** and **Impact** using a localized **1 to 3 scaling system**:

*   **Likelihood:** 1 (Low/Unlikely), 2 (Medium/Possible), 3 (High/Almost Certain)
*   **Impact:** 1 (Low/Minor Disruption), 2 (Medium/Moderate Loss), 3 (High/Critical System or Data Breach)

$$\text{Total Inherent Risk Score} = \text{Likelihood} \times \text{Impact}$$

### Risk Categorization:
*   🔴 **High Risk (Scores 6–9):** Immediate remediation required within 30 days. Critical threats to business operations or sensitive data.
*   🟡 **Medium Risk (Scores 3–4):** Remediation required within 90 days. Operational gaps that weaken the defensive posture.
*   🟢 **Low Risk (Scores 1–2):** General security hygiene enhancements to be monitored continuously.

---

## 📁 Repository Structure

The artifacts generated during this comprehensive manual audit are organized as follows:

```text
├── README.md               # Project overview and executive summary (This file)
├── /Assessment            # Excel Risk Register tracking and analyzing all identified gaps
│   └── BEF_NIST_CSF_Risk_Register.xlsx
├── /Reports               # Formal 3-page Executive Gap Analysis Report (PDF)
│   └── BEF_Executive_Gap_Analysis_Report.pdf
└── /Policies              # Formal enterprise security policies written for remediation
    └── BEF_Access_Control_and_Incident_Response_Policy.pdf
