# Botium Toys – Compliance Mapping

## 1. Objective

This document maps selected security control observations from the Botium Toys educational case study to relevant compliance and assurance requirements.

The purpose is to understand how security weaknesses may affect compliance obligations and control objectives.

## 2. PCI DSS – Payment Card Industry Data Security Standard

PCI DSS establishes security requirements for organisations that store, process, or transmit payment card data.

| Security Area | Identified Gap | Potential Compliance Concern | Recommended Action |
|---|---|---|---|
| Access restriction | Excessive employee access | Cardholder data may be accessible to unauthorised users | Restrict access based on business need and least privilege |
| Data protection | Payment card information is not encrypted | Inadequate protection of stored cardholder data | Apply appropriate encryption and key management |
| Authentication | Weak password requirements | Weak access security | Enforce strong authentication controls |
| Credential management | No centralised password management | Inconsistent credential protection | Implement secure credential management |

**Assessment observation:** The identified gaps indicate potential weaknesses against PCI DSS security objectives. A formal assessment would require confirmation of the organisation's cardholder data environment, applicable PCI DSS requirements, and supporting evidence.

## 3. GDPR – General Data Protection Regulation

GDPR establishes requirements for the protection and lawful processing of personal data relating to individuals in the European Union.

| GDPR Consideration | Identified Gap or Existing Measure | Potential Concern | Recommended Action |
|---|---|---|---|
| Personal data protection | Excessive employee access | Unauthorised access to personal data | Apply access restrictions and periodic reviews |
| Security of processing | Payment and personal data protection weaknesses | Inadequate technical and organisational safeguards | Apply appropriate security measures |
| Breach notification | A 72-hour notification plan exists | The organisation must ensure applicable notification obligations are met | Maintain documented incident assessment and notification procedures |
| Data governance | Data inventory and classification need strengthening | Inadequate visibility of personal data | Maintain data inventory, classification, and retention controls |
| Privacy governance | Privacy policies and procedures exist | Policies need effective implementation and monitoring | Review and periodically test privacy procedures |

**Assessment observation:** GDPR Article 33 generally requires notification to the competent supervisory authority within 72 hours of becoming aware of a personal data breach, where feasible, unless the breach is unlikely to result in a risk to individuals' rights and freedoms. Article 34 addresses communication to affected individuals where a breach is likely to result in a high risk.

## 4. SOC 1 and SOC 2 – Assurance Considerations

SOC reports are independent assurance reports issued by a service auditor. They are not certifications.

### SOC 1

SOC 1 focuses on controls at a service organisation that are relevant to user entities' internal control over financial reporting.

Relevant areas for consideration in this case study may include:

- Access controls over financial applications and data.
- Authorisation of financial transactions.
- Segregation of duties.
- Change management affecting financial systems.
- Processing accuracy and completeness.

### SOC 2

SOC 2 evaluates controls against applicable Trust Services Criteria.

The relevant categories include:

- Security
- Availability
- Processing Integrity
- Confidentiality
- Privacy

| Control Area | Identified Observation | Relevant SOC Consideration |
|---|---|---|
| User access | Excessive access to sensitive information | Security |
| Data confidentiality | Payment data is not encrypted | Confidentiality |
| Data integrity | Integrity controls are reported to exist | Processing Integrity |
| System availability | Availability controls are reported to exist, but backups are absent | Availability |
| Security monitoring | No intrusion detection system | Security |

**Assessment observation:** The identified weaknesses may affect relevant SOC control objectives. Actual SOC 1 or SOC 2 conclusions depend on the service organisation's scope, control design, evidence, testing, and the applicable report criteria.

## 5. Consolidated Compliance Risk Summary

| Framework | Main Risk Area | Priority |
|---|---|---|
| PCI DSS | Payment card data protection and access restrictions | Critical |
| GDPR | Personal data security and access governance | High |
| SOC 1 | Financial application access and segregation of duties | High |
| SOC 2 | Security monitoring, confidentiality, and availability | High |

## 6. Recommended Remediation Priorities

1. Restrict access to sensitive information using role-based access control.
2. Protect payment card data using appropriate encryption and key management.
3. Strengthen authentication and credential management.
4. Implement backup, recovery, and restoration testing.
5. Improve security monitoring and incident detection.
6. Maintain data inventories and privacy governance procedures.
7. Establish periodic compliance reviews and evidence retention.

## 7. Conclusion

The case study identifies security weaknesses that may affect payment card protection, personal data privacy, and service organisation control objectives.

A structured remediation programme should assign control owners, establish target dates, retain supporting evidence, and monitor progress through periodic compliance reviews.

## 8. Important Disclaimer

This document is an independent educational compliance mapping exercise based on a fictional organisation. It is not a PCI DSS assessment, GDPR legal opinion, SOC audit, certification, or formal assurance report.
