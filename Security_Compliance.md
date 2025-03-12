# AWS Cloud Practitioner (CLF-C02) - Security & Compliance

Study guide for the Security and Regulatory Standards domain (25%). Updated as of March 12, 2025.

---

## Responsibility Division
- **AWS Scope:** Secures the cloud foundation.
  - Covers physical facilities, hardware, and core systems.
  - Example: Protects EC2 server hardware from physical threats.
- **User Scope:** Secures usage within the cloud.
  - Includes configurations, data protection, and access rules.
  - Example: Configures EC2 security groups to control traffic.

## Essential Security Tools
- **IAM (Identity & Access Management):**
  - Controls access via users, groups, and policy definitions (JSON-based).
  - Supports MFA (Multi-Factor Authentication) for enhanced login protection.
  - Root account: Highest privilege level, requires strict safeguarding with MFA.
- **AWS Shield:** Guards against DDoS attacks (free Standard tier included, paid Advanced option available).
- **AWS KMS (Key Management Service):** Manages cryptographic keys for data encryption across services.
- **CloudTrail:** Records all account activities for auditing, tracking actions and timestamps.
- **Inspector:** Identifies security weaknesses in applications and infrastructure configurations.

## Regulatory Compliance
- Aligns with standards such as GDPR, HIPAA, and PCI DSS.
- **AWS Artifact:** Provides on-demand access to compliance documentation and reports.

## Security Essentials
- Root account: Enforce strong passwords and enable MFA immediately.
- Access keys: Keep confidential, rotate periodically to maintain security.

---
