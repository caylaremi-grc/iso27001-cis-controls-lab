# Data Classification Matrix – Leman Health Service (Switzerland)

| Classification Level | Description | Examples of Data | Access Rules | Security Controls |
|---------------------|-------------|------------------|--------------|------------------|
| Public | Information approved for public release with no confidentiality risk | Website content, public health information, marketing brochures | Open access | Basic integrity checks, no sensitive controls needed |
| Internal | Non-sensitive operational data used within the organization | Internal policies, staff directories (non-sensitive), internal schedules | Employees only | Access control, basic authentication |
| Confidential | Sensitive business or personal data requiring protection | Patient administrative data (non-medical), invoices, appointment data, internal reports | Restricted to authorized staff / departments | Encryption, role-based access (RBAC), audit logs |
| Highly Confidential (Sensitive Health Data) | Legally protected health and personal data under Swiss FADP / GDPR special category data | Medical records, diagnoses, lab results, mental health data, genetic data, insurance health claims | Strictly limited to healthcare professionals involved in care | Strong encryption (at rest & in transit), MFA, strict RBAC, logging, data minimization |
| Restricted (Critical) | Data with extreme impact if exposed or altered | Credentials, cryptographic keys, system admin access, patient identity linking tables | Very limited (admin/security only) | HSM/secure vaults, zero-trust access, continuous monitoring, incident response controls |

