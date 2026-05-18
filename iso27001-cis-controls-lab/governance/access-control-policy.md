# Access Control Policy
**Document Type:** Governance Policy  
**Version:** 1.0  
**Owner:** Information Security / ISMS Lead  
**Last Updated:** 2026-05-18  
**Classification:** Internal

---

## 1. Purpose

This Access Control Policy defines requirements for managing logical and physical access to organizational systems and data.  

The objective is to ensure that only authorized users have appropriate access based on business need, while protecting confidentiality, integrity, and availability of information assets in accordance with **ISO/IEC 27001**.

---

## 2. Scope

This policy applies to:
- Employees
- Contractors
- Third-party vendors
- Temporary and privileged users

It covers:
- Applications and systems (EHR, billing, HR, etc.)
- Cloud infrastructure
- Networks and endpoints
- Databases and backups

---

## 3. Access Control Principles

Access must follow:

- **Least Privilege:** Users receive minimum access required for their role
- **Need-to-Know:** Access granted only for legitimate business purposes
- **Role-Based Access Control (RBAC):** Access based on defined roles
- **Segregation of Duties (SoD):** Critical tasks must not be assigned to a single user

---

## 4. User Access Management

- All access requests must be formally approved
- Unique user IDs must be assigned to each individual
- Shared accounts are strictly prohibited
- Access must be reviewed periodically (at least quarterly for high-risk systems)
- Access must be revoked immediately upon termination or role change

---

## 5. Privileged Access Management

Privileged accounts (admin/root/system-level access):
- Must be strictly limited
- Require Multi-Factor Authentication (MFA)
- Must be logged and monitored continuously
- Must not be used for daily non-administrative tasks

---

## 6. Authentication Requirements

- MFA is mandatory for critical systems
- Passwords must comply with organizational password policy
- Default credentials must be changed immediately upon deployment
- Authentication logs must be retained for audit purposes

---

## 7. Remote Access

- Remote access must be secured via approved VPN or Zero Trust solutions
- Unsecured public networks must not be used without protection
- Device compliance checks may be enforced before access is granted

---

## 8. Monitoring & Review

Access activity is subject to:
- Continuous logging
- Security monitoring (SIEM)
- Regular access reviews and audits

---

## 9. Compliance Mapping

**ISO/IEC 27001 Controls:**
- A.5.15 Access control
- A.5.16 Identity management
- A.8.2 Privileged access rights
- A.8.5 Secure authentication

**CIS Controls v8:**
- CIS 5 Account Management
- CIS 6 Access Control Management
- CIS 8 Audit Log Management

---

## 10. Enforcement

Non-compliance may result in:
- Access revocation
- Disciplinary action
- Contract termination
- Legal action where applicable
