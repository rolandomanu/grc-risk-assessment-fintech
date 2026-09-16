# FinTech GRC Risk Assessment & Control Assurance Lab

## Executive Summary
This project demonstrates an enterprise-level Governance, Risk, and Compliance (GRC) evaluation for a simulated financial services environment (FinTech). It focuses on identifying data security risks, mapping controls between international standards (**ISO/IEC 27001**) and federal cyber frameworks (**NIST CSF**), and establishing enforceable access control policies.

---

## 🎯 Project Scope & Objectives
* **Risk Register & Scoring:** Conducted asset-based risk identification, likelihood/impact scoring, and mitigation strategies.
* **Framework Crosswalk:** Mapped physical and logical controls between ISO/IEC 27001 clauses and NIST CSF subcategories to eliminate security coverage gaps.
* **Policy Assurance:** Drafted production-ready security policies in English and Spanish for role-based access control (RBAC) and vulnerability remediation.

---

## 📊 Control Mapping Matrix (ISO/IEC 27001 vs. NIST CSF)

| ISO/IEC 27001:2022 Control | NIST CSF 2.0 Subcategory | Implementation / Technical Control | Assurance Evidence |
| :--- | :--- | :--- | :--- |
| **A.5.15** Access Control | **PR.AA-01** Identity & Access | Enforced Role-Based Access Control (RBAC) & Entra ID Conditional Access. | Entra ID Sign-in Logs & Access Review Reports |
| **A.8.12** Data Leakage Prevention | **PR.DS-01** Data Protection | Implemented Microsoft Purview DLP policies for PII/PCI-DSS data in transit. | Purview DLP Alert Dashboard & Policy Audit Logs |
| **A.8.8** Management of Tech Vulnerabilities | **ID.RA-01** Risk Assessment | Bi-weekly vulnerability scans and mandatory 14-day SLA patching for critical assets. | Qualys/Nessus Executive Scan Reports |
| **A.5.12** Classification of Information | **PR.DS-02** Data Posture | Automated Sensitivity Labels applied to unstructured repositories and emails. | Purview Data Estate Insights |

---

## 📁 Repository Structure

```text
├── policies/
│   ├── Access-Control-Policy-EN.pdf       # English RBAC & Access Governance Policy
│   └── Politica-Control-de-Acceso-ES.pdf  # Spanish Version
├── risk-assessment/
│   └── Fintech-Risk-Register.xlsx          # Detailed Likelihood/Impact Scoring Matrix
└── README.md

## 🛡️ Key Takeaways & Quality Control (QC)

* **Audit Readiness:** All mapped controls include explicit requirements for evidence generation to satisfy internal and external auditor reviews.
* **Data Security Integration:** Demonstrates how data loss vectors are constrained by aligning identity management (RBAC) with endpoint and cloud DLP rules.
