# Botium Toys – Executive Audit Summary

## 1. Executive Overview

This educational security assessment evaluates the cybersecurity controls, information security risks, and selected compliance considerations of the fictional organisation Botium Toys.

The objective is to identify weaknesses in the existing security environment, assess potential risks to organisational assets, and recommend improvements to strengthen the confidentiality, integrity, and availability of information.

The assessment covers 14 security controls and selected compliance considerations associated with PCI DSS, GDPR, and SOC reporting.

## 2. Scope of Assessment

The assessment covers:

- User access management and least privilege.
- Password policies and authentication.
- Separation of duties.
- Firewall and intrusion detection.
- Antivirus protection.
- Data encryption and payment card protection.
- Data backup and disaster recovery.
- Legacy system maintenance.
- Physical security controls.
- PCI DSS, GDPR, and SOC-related security considerations.

## 3. Security Controls Assessment Results

A total of 14 security controls were evaluated.

| Control Status | Number | Percentage |
|---|---:|---:|
| Fully Implemented | 5 | 35.71% |
| Partially Implemented | 1 | 7.14% |
| Not Implemented | 8 | 57.14% |
| **Total** | **14** | **100%** |

### Course Checklist Result

The original course checklist uses binary Yes/No responses.

| Checklist Response | Number |
|---|---:|
| Yes | 6 |
| No | 8 |
| **Total** | **14** |

The partially implemented legacy system maintenance control is counted as Yes in the course checklist because monitoring and maintenance activities exist. However, its implementation is deficient because maintenance is irregular and procedures are unclear.

Therefore, the binary checklist result and the detailed implementation status are two different views of the same assessment.

## 4. Key Security Findings

### Finding 1 – Excessive User Access

Employees have access to internally stored information without adequate restrictions based on their business responsibilities.

**Risk:** Unauthorised access to confidential and sensitive information.

### Finding 2 – Inadequate Payment Data Protection

Customer payment card information is not encrypted, and access restrictions are inadequate.

**Risk:** Exposure or unauthorised disclosure of sensitive financial information.

### Finding 3 – Weak Authentication Controls

Password requirements are nominal, and a centralised password management system is absent.

**Risk:** Increased likelihood of account compromise and unauthorised access.

### Finding 4 – Missing Backup and Disaster Recovery Arrangements

Regular backup arrangements and a documented disaster recovery plan are absent.

**Risk:** Data loss, extended downtime, and disruption to business operations.

### Finding 5 – Insufficient Security Detection

An intrusion detection system is not currently deployed.

**Risk:** Delayed detection of suspicious activities and potential security incidents.

### Finding 6 – Inadequate Legacy System Maintenance

Legacy systems receive monitoring and maintenance, but activities are irregular and procedures are not clearly documented.

**Risk:** Increased exposure to vulnerabilities and operational disruptions.

## 5. Compliance Assessment Summary

The compliance mapping exercise evaluated 12 checklist points across three areas.

| Framework | Yes | No | Total |
|---|---:|---:|---:|
| PCI DSS | 0 | 4 | 4 |
| GDPR | 2 | 2 | 4 |
| SOC Considerations | 1 | 3 | 4 |
| **Total** | **3** | **9** | **12** |

### Major Compliance-Related Gaps

- Payment card information is not encrypted.
- Access to sensitive customer data is not adequately restricted.
- Password management practices are inadequate.
- Data classification procedures are not established.
- User access policies and separation of duties need improvement.
- Sensitive personal information requires stronger confidentiality controls.

These are preliminary case study observations, not formal compliance determinations.

## 6. Recommended Remediation Priorities

### Priority 1 – Access and Authentication

- Implement least privilege.
- Establish separation of duties.
- Strengthen password policies.
- Introduce centralised password management.
- Perform periodic user access reviews.

### Priority 2 – Data Protection

- Implement encryption for sensitive financial and customer information.
- Introduce appropriate data classification.
- Restrict access to payment card information.
- Review data handling and privacy procedures.

### Priority 3 – Business Continuity

- Establish regular backup arrangements.
- Develop a documented disaster recovery plan.
- Conduct periodic backup restoration tests.

### Priority 4 – Security Monitoring

- Implement an Intrusion Detection System.
- Strengthen security logging and monitoring.
- Establish a formal maintenance schedule for legacy systems.

## 7. Conclusion

The assessment identifies significant gaps in Botium Toys' security control environment.

Although certain physical and technical controls are implemented, weaknesses in access management, authentication, encryption, backup and recovery, and security monitoring increase the organisation's exposure to information security risks.

Management should prioritise remediation based on business impact, risk exposure, and regulatory obligations.

Implementing the recommended improvements will help strengthen the organisation's security posture and improve the protection of its information assets.

## 8. Assessment Methodology and Limitations

This assessment is based on a fictional educational case study.

No independent audit evidence collection, control walkthrough, sample testing, technical validation, or operating effectiveness testing was performed.

The findings and recommendations are educational and should not be interpreted as formal audit opinions, legal advice, or independent assurance conclusions.
