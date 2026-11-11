# Botium Toys – Security Controls Assessment

## 1. Assessment Objective

The objective is to evaluate the security controls identified in the fictional Botium Toys case study and document their implementation status and potential control gaps.

## 2. Control Assessment Summary

| ID | Security Control | Status | Audit Observation |
|---|---|---|---|
| C01 | Least Privilege | Not Implemented | Employees have excessive access to internally stored data |
| C02 | Disaster Recovery Plan | Not Implemented | No documented disaster recovery plan |
| C03 | Password Policy | Partially Implemented | Policy exists but does not enforce adequate password complexity |
| C04 | Segregation of Duties | Not Implemented | Conflicting responsibilities are not adequately separated |
| C05 | Firewall | Implemented | Firewall filters network traffic using defined rules |
| C06 | Intrusion Detection System | Not Implemented | No IDS is deployed |
| C07 | Data Backups | Not Implemented | Critical data is not regularly backed up |
| C08 | Antivirus | Implemented | Antivirus is installed and regularly monitored |
| C09 | Legacy System Maintenance | Partially Implemented | Monitoring and maintenance exist but are irregular |
| C10 | Data Encryption | Not Implemented | Payment card information is not encrypted |
| C11 | Centralised Password Management | Not Implemented | No centralised password management system |
| C12 | Physical Locks | Implemented | Physical locks protect the premises |
| C13 | CCTV Monitoring | Implemented | CCTV is available and up to date |
| C14 | Fire Detection and Prevention | Implemented | Fire detection and prevention arrangements are available |

## 3. Control Classification

### Administrative and Managerial Controls

- Least privilege
- Password policy
- Segregation of duties
- Account management
- Disaster recovery planning

### Technical Controls

- Firewall
- Intrusion detection
- Antivirus
- Data encryption
- Password management
- Backup arrangements

### Physical and Operational Controls

- Physical locks
- CCTV monitoring
- Fire detection and prevention
- Legacy system maintenance

## 4. Control Type Classification

| Control Type | Purpose | Example |
|---|---|---|
| Preventive | Prevents or reduces the likelihood of an incident | Firewall and access restrictions |
| Detective | Identifies suspicious activity or incidents | IDS and CCTV monitoring |
| Corrective | Helps restore systems or recover from incidents | Backups and disaster recovery |
| Deterrent | Discourages unauthorised or inappropriate behaviour | Warning signage and visible security measures |

A control may support more than one control objective depending on its design and implementation.

## 5. Key Audit Findings

### Finding 1 – Excessive User Access

**Risk:** Unauthorised access to confidential information.

**Observation:** Access is not restricted according to employees' business responsibilities.

**Recommendation:** Implement role-based access control, least privilege, and periodic user access reviews.

### Finding 2 – Inadequate Payment Data Protection

**Risk:** Exposure of sensitive payment card information.

**Observation:** Payment card information is not encrypted.

**Recommendation:** Implement appropriate encryption, secure key management, and access restrictions.

### Finding 3 – Inadequate Backup and Recovery

**Risk:** Loss of critical business information and extended downtime.

**Observation:** Regular backups and a documented disaster recovery plan are absent.

**Recommendation:** Establish scheduled backups, restoration testing, and a documented disaster recovery plan.

### Finding 4 – Weak Authentication Controls

**Risk:** Account compromise and unauthorised system access.

**Observation:** Password policy requirements are inadequate and centralised password management is absent.

**Recommendation:** Strengthen authentication requirements and introduce centralised credential management.

### Finding 5 – Insufficient Security Detection

**Risk:** Delayed identification of security incidents.

**Observation:** An intrusion detection system is not deployed.

**Recommendation:** Introduce suitable IDS/IPS capabilities, centralised logging, and security alert monitoring.

## 6. Overall Assessment

The assessment identifies 14 security controls:

- Implemented: 5
- Partially implemented: 2
- Not implemented: 7

The organisation should prioritise remediation of critical weaknesses involving payment card data protection, access management, and backup and recovery.

## 7. Audit Methodology Note

This assessment is based on the information supplied in an educational case study. No independent evidence inspection, sample testing, control walkthrough, or operating effectiveness testing was performed.

The status classifications represent preliminary observations and should not be interpreted as formal audit conclusions.
