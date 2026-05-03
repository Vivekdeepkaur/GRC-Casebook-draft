# 🛡️ NIST Cybersecurity Framework (CSF)  
## Incident Detection & Response Readiness Assessment

---

## 📌 Overview

This project evaluates an organization’s **incident detection and response maturity** using the **NIST Cybersecurity Framework (CSF)**.

The assessment identifies gaps in current security operations and provides structured controls to improve cybersecurity resilience through detection, response, and recovery capabilities.

---

## 🏢 Scenario

The organization operates a **cloud-based application** storing customer and business data.

### Current Security Posture:
- Basic security controls exist
- No centralized incident detection system
- Logs are available but not monitored effectively
- No formal incident response framework or playbook

### Objective:
Improve security maturity by aligning operations with **NIST CSF**, focusing on:
- Detection capabilities
- Incident response readiness
- Security monitoring structure

---

## 🧱 Current State (AS-IS)

- Logs exist across multiple systems but are not centralized  
- No Security Operations Center (SOC) in place  
- Security alerts are not actively monitored  
- No documented Incident Response Plan (IRP)  

---

## ⚠️ Risk Assessment

| Risk ID | Description | Impact | Likelihood |
|--------|-------------|--------|-----------|
| R1 | Delayed detection of cyber incidents | High | High |
| R2 | Lack of incident response coordination | High | Medium |
| R3 | Inability to investigate security events | High | High |
| R4 | Prolonged system downtime during incidents | Medium | Medium |

---

## 🔐 Control Design (GRC Framework)

| Control ID | Control Description |
|------------|-------------------|
| C1 | Centralized log management (SIEM implementation) |
| C2 | Continuous monitoring of security events |
| C3 | Defined Incident Response Plan (IRP) |
| C4 | Role-based incident response team structure |
| C5 | Alert triage and escalation procedures |

---

## 🔗 NIST CSF Mapping

| Function | Category | Controls |
|----------|----------|----------|
| Detect | Anomalies & Events | C1, C2 |
| Detect | Security Monitoring | C1, C2 |
| Respond | Response Planning | C3 |
| Respond | Communications | C4, C5 |
| Recover | Recovery Planning | C3 |

---

## 🧪 Validation Approach

The following validation methods are used to assess effectiveness:

- Review SIEM log ingestion and alert configuration  
- Simulate security events to test detection capabilities  
- Validate incident response workflows and documentation  
- Analyze historical incident handling records (if available)  

### ✅ Expected Outcomes:
- Centralized security logging across all systems  
- Real-time alert monitoring and response  
- Defined and tested incident response procedures  

---

## 🏁 Conclusion

The organization currently demonstrates **low to moderate maturity** in incident detection and response.

By implementing:
- Centralized logging (SIEM)
- Continuous monitoring
- Formal incident response planning

The organization can significantly enhance its cybersecurity resilience and achieve alignment with the **NIST CSF framework**.

---
