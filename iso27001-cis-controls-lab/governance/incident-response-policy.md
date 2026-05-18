# Incident Response Policy
**Document Type:** Governance Policy  
**Version:** 1.0  
**Owner:** Information Security / SOC Lead  
**Last Updated:** 2026-05-18  
**Classification:** Internal

---

## 1. Purpose

This Incident Response Policy defines the structured approach for identifying, managing, responding to, and recovering from security incidents.  

The goal is to minimize impact on confidentiality, integrity, and availability of systems and ensure compliance with **ISO/IEC 27001** and applicable regulatory requirements.

---

## 2. Scope

This policy applies to:
- All employees and contractors
- All information systems and infrastructure
- Cloud environments and third-party services
- Data including personal, financial, and medical records

---

## 3. Incident Definition

An information security incident includes:
- Unauthorized access to systems or data
- Data breaches or leakage
- Malware infections or ransomware
- Service disruption or denial of service
- Suspicious or malicious user activity

---

## 4. Incident Response Lifecycle

### 4.1 Identification
- Detect incidents via monitoring systems, alerts, or user reports
- Classify severity (Low, Medium, High, Critical)

### 4.2 Containment
- Isolate affected systems
- Prevent further damage or spread
- Preserve evidence for investigation

### 4.3 Eradication
- Remove root cause (malware, compromised accounts, vulnerabilities)
- Patch exploited weaknesses

### 4.4 Recovery
- Restore systems from secure backups
- Validate system integrity before returning to production
- Monitor for recurrence

### 4.5 Lessons Learned
- Conduct post-incident review
- Document findings and improvements
- Update controls and policies if needed

---

## 5. Incident Reporting

All personnel must immediately report:
- Suspected data breaches
- Lost or stolen devices
- Phishing attempts
- Unauthorized system access

Reporting channels:
- IT Security Team / SOC
- Incident Response Hotline or Ticketing System

---

## 6. Roles and Responsibilities

- **Employees:** Report incidents immediately
- **IT Team:** Initial containment and technical response
- **SOC:** Monitoring, detection, and escalation
- **ISMS Lead:** Governance and reporting
- **Management:** Business impact decisions and communication

---

## 7. Communication & Escalation

- High and critical incidents must be escalated immediately
- External communication is managed only by authorized personnel
- Regulatory notification (e.g., GDPR/FADP) must be performed when required

---

## 8. Logging & Evidence Handling

- All incident-related logs must be preserved
- Evidence must be protected from modification
- Chain of custody must be maintained for forensic analysis

---

## 9. Compliance Mapping

**ISO/IEC 27001 Controls:**
- A.5.24 Information security incident management planning and preparation
- A.5.25 Assessment and decision on information security events
- A.5.26 Response to information security incidents
- A.5.27 Learning from information security incidents

**CIS Controls v8:**
- CIS 8 Audit Log Management
- CIS 13 Security Monitoring
- CIS 17 Incident Response Management

---

## 10. Review Cycle

This policy is reviewed:
- Annually, or
- After significant security incidents
