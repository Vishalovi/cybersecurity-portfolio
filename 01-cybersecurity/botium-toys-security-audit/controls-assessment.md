# Botium Toys – Security Controls Assessment

## 1. Assessment Objective

The objective of this assessment is to evaluate the security controls identified in the fictional Botium Toys case study, determine their implementation status, identify control gaps, and recommend improvements to strengthen the organisation's security posture.

This is an educational assessment based on the case study information and is not a formal independent audit.

## 2. Control Assessment Summary

The following table summarises the 14 security controls evaluated.

| ID | Security Control | Assessment Status | Audit Observation |
|---|---|---|---|
| C01 | Least Privilege | Not Implemented | All employees have access to internally stored data, without adequate restrictions based on job responsibilities. |
| C02 | Disaster Recovery Plan | Not Implemented | A documented disaster recovery plan is not currently in place. |
| C03 | Password Policy | Not Implemented | Password requirements are nominal and do not provide adequate protection. |
| C04 | Separation of Duties | Not Implemented | Responsibilities are not adequately separated, increasing the risk of unauthorised or conflicting activities. |
| C05 | Firewall | Implemented | Firewall rules are appropriately defined to filter network traffic. |
| C06 | Intrusion Detection System | Not Implemented | An intrusion detection system is not currently deployed. |
| C07 | Data Backups | Not Implemented | A regular backup arrangement is not currently in place. |
| C08 | Antivirus | Implemented | Antivirus software is installed and monitored. |
| C09 | Legacy System Maintenance | Partially Implemented | Legacy systems receive monitoring and maintenance, but activities are irregular and lack clearly documented procedures. |
| C10 | Data Encryption | Not Implemented | Customer payment card information is not encrypted. |
| C11 | Centralised Password Management | Not Implemented | A centralised password management system is not currently in place. |
| C12 | Physical Locks | Implemented | Physical locks are available to protect the premises. |
| C13 | CCTV Monitoring | Implemented | CCTV monitoring is available and up to date. |
| C14 | Fire Detection and Prevention | Implemented | Fire detection and prevention arrangements are available. |

## 3. Control Assessment Results

The assessment identifies the following implementation status:

| Status | Number of Controls |
|---|---:|
| Fully Implemented | 5 |
| Partially Implemented | 1 |
| Not Implemented | 8 |
| **Total** | **14** |

### Course Checklist Result

The original course checklist uses a binary Yes/No assessment.

| Checklist Response | Number of Controls |
|---|---:|
| Yes | 6 |
| No | 8 |
| **Total** | **14** |

The legacy system maintenance control is counted as Yes in the course checklist because monitoring and maintenance activities exist. However, this assessment classifies it as partially implemented because the activities are irregular and lack documented procedures.

This distinction separates the existence of a control from the quality and effectiveness of its implementation.

## 4. Control Classification

### Administrative and Managerial Controls

- Least Privilege
- Password Policy
- Separation of Duties
- Account Management
- Disaster Recovery Planning

### Technical Controls

- Firewall
- Intrusion Detection System
- Antivirus
- Data Encryption
- Centralised Password Management
- Data Backup Arrangements

### Physical and Operational Controls

- Physical Locks
- CCTV Monitoring
- Fire Detection and Prevention
- Legacy System Maintenance

## 5. Control Type Classification

| Control Type | Purpose | Example |
|---|---|---|
| Preventive | Prevents or reduces the likelihood of a security incident. | Firewall, access restrictions and encryption |
| Detective | Identifies suspicious activity or security incidents. | Intrusion Detection System and CCTV monitoring |
| Corrective | Helps restore systems or recover from incidents. | Data backups and disaster recovery arrangements |
| Deterrent | Discourages unauthorised or inappropriate behaviour. | Warning signage and visible physical security measures |

A security control may support more than one control objective depending on its design and implementation.

## 6. Key Audit Findings

### Finding 1 – Excessive User Access

**Risk:** Unauthorised access to confidential information.

**Observation:** Access to internally stored data is not adequately restricted according to employees' business responsibilities.

**Recommendation:** Implement role-based access control, the principle of least privilege, and periodic user access reviews.

### Finding 2 – Inadequate Payment Data Protection

**Risk:** Exposure or unauthorised disclosure of sensitive payment card information.

**Observation:** Payment card information is not encrypted, and access is not adequately restricted.

**Recommendation:** Implement appropriate encryption, secure key management, and access restrictions for payment card data.

### Finding 3 – Inadequate Backup and Recovery

**Risk:** Loss of critical business information and extended business downtime.

**Observation:** Regular backup arrangements and a documented disaster recovery plan are absent.

**Recommendation:** Establish scheduled backups, perform restoration testing, and implement a documented disaster recovery plan.

### Finding 4 – Weak Authentication Controls

**Risk:** Account compromise and unauthorised system access.

**Observation:** Password policy requirements are inadequate, and a centralised password management system is absent.

**Recommendation:** Establish stronger password policies and introduce centralised credential management.

### Finding 5 – Insufficient Security Detection

**Risk:** Delayed identification of security incidents and potential malicious activity.

**Observation:** An intrusion detection system is not deployed.

**Recommendation:** Introduce suitable intrusion detection capabilities, centralised logging, and security alert monitoring.

### Finding 6 – Inadequate Legacy System Maintenance

**Risk:** Increased exposure to vulnerabilities, system failures, and operational disruptions.

**Observation:** Legacy systems are monitored and maintained, but maintenance activities are irregular and documented procedures are unclear.

**Recommendation:** Establish a formal maintenance schedule, document procedures, and periodically review legacy system security.

## 7. Overall Assessment

The assessment identifies significant weaknesses in Botium Toys' security control environment.

Although certain physical and technical controls are in place, important gaps remain in access management, authentication, encryption, backup and recovery, and security monitoring.

The organisation should prioritise remediation of the following areas:

1. Least Privilege and Separation of Duties.
2. Password policies and centralised password management.
3. Encryption of sensitive payment card information.
4. Regular backup arrangements and disaster recovery planning.
5. Deployment of an Intrusion Detection System.
6. Formalised legacy system maintenance procedures.

Addressing these gaps will improve the confidentiality, integrity, and availability of organisational information assets.

## 8. Audit Methodology and Limitations

This assessment is based on information provided in a fictional educational case study.

No independent evidence inspection, sample testing, control walkthrough, or operating effectiveness testing was performed.

The assessment status classifications represent preliminary observations based
