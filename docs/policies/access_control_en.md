1. Access Control Policy
Version: 1.0

Status: Draft for Fintech Project

Purpose
To establish the necessary controls to ensure that access to Fintech information assets is limited to authorized users, based on the principle of least privilege.

Key Guidelines
Unique Identification: Every user must have an individual and non-transferable account. Shared accounts are strictly prohibited.

Multi-Factor Authentication (MFA): MFA is mandatory for accessing the AWS console, PCI databases, and VPN networks.

Role-Based Access Control (RBAC): Permissions will be assigned according to the job profile (e.g., Developer, Auditor, Administrator).

Access Reviews: The GRC team will perform privilege reviews every 90 days to decommission unnecessary access.

Control Mapping: ISO 27001:2022 (A.5.15, A.8.5) | SOC 2 (CC6.1)

2. Vulnerability Management Policy
Version: 1.0

Status: Draft for Fintech Project

Purpose
To define the process for identifying, assessing, and remediating technical weaknesses in infrastructure and applications to prevent security incidents.

Key Guidelines
Asset Scanning: Monthly vulnerability scans will be performed on servers and databases, and quarterly on web applications.

Severity Classification: The CVSS (Common Vulnerability Scoring System) will be used to prioritize findings.

Remediation Timelines:

Critical (9.0-10.0): Maximum 48 hours.

High (7.0-8.9): Maximum 15 days.

Medium (4.0-6.9): Maximum 30 days.

Patch Management: Systems must be updated following the change management process to avoid service disruptions.

Control Mapping: ISO 27001:2022 (A.8.8) | NIST CSF (ID.RA-1)
