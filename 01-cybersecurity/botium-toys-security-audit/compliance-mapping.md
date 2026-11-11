# Botium Toys – Compliance Mapping Assessment

## 1. Assessment Objective

The objective of this assessment is to evaluate the fictional Botium Toys case study against selected security and compliance best practices associated with:

- Payment Card Industry Data Security Standard (PCI DSS)
- General Data Protection Regulation (GDPR)
- System and Organization Controls (SOC) considerations

The assessment identifies potential compliance gaps and recommends improvements to strengthen information security and data protection practices.

This is an educational compliance mapping exercise, not a formal compliance audit or certification assessment.

## 2. Payment Card Industry Data Security Standard (PCI DSS)

PCI DSS establishes security requirements for organisations that store, process, or transmit payment card information.

### Assessment Checklist

| ID | Best Practice / Assessment Question | Yes | No | Explanation |
|---|---|:---:|:---:|---|
| PCI-01 | Only authorised users have access to customers' credit card information. | No | Yes | All employees currently have access to the company's internal data, including customer credit card information. |
| PCI-02 | Credit card information is accepted, processed, transmitted, and stored internally in a secure environment. | No | Yes | Credit card information is not encrypted, and access to internal data is not adequately restricted. |
| PCI-03 | Data encryption procedures are implemented to secure credit card transaction touchpoints and data. | No | Yes | The company does not currently use encryption to protect the confidentiality of customers' financial information. |
| PCI-04 | Secure password management policies are adopted. | No | Yes | Password policies are nominal, and a password management system is not currently in place. |

### PCI DSS Assessment Result

| Result | Count |
|---|---:|
| Yes | 0 |
| No | 4 |

**Key gaps identified:**

- Excessive access to payment card information.
- Lack of encryption for sensitive financial information.
- Inadequate password policies.
- Absence of a centralised password management system.

**Recommendations:**

- Restrict payment card information access to authorised personnel.
- Implement appropriate encryption and key management.
- Strengthen authentication and password management.
- Review access permissions periodically.

## 3. General Data Protection Regulation (GDPR)

GDPR establishes requirements for protecting personal data and ensuring appropriate data privacy and security practices.

### Assessment Checklist

| ID | Best Practice / Assessment Question | Yes | No | Explanation |
|---|---|:---:|:---:|---|
| GDPR-01 | E.U. customers' data is kept private and secured. | No | Yes | Encryption is not currently used to adequately protect the confidentiality of customers' financial information. |
| GDPR-02 | A plan exists to notify E.U. customers within 72 hours in the event of a data breach. | Yes | No | The case study indicates that a plan exists to notify E.U. customers within 72 hours of a data breach. |
| GDPR-03 | Data is properly classified and inventoried. | No | Yes | Company assets have been inventoried or listed, but they have not been properly classified. |
| GDPR-04 | Privacy policies, procedures, and processes are enforced to document and maintain data appropriately. | Yes | No | Privacy policies, procedures, and processes have been developed and enforced among IT team members and other employees, as needed. |

### GDPR Assessment Result

| Result | Count |
|---|---:|
| Yes | 2 |
| No | 2 |

**Key gaps identified:**

- Inadequate protection of sensitive customer information.
- Lack of formal data classification.
- Need for stronger data protection and access management controls.

**Recommendations:**

- Establish a formal data classification framework.
- Identify and classify personal and sensitive information.
- Implement appropriate encryption and access controls.
- Review privacy policies and data handling procedures periodically.
- Maintain and test a documented data breach response process.

**Regulatory clarification:** GDPR Article 33 generally requires notification of a personal data breach to the competent supervisory authority within 72 hours of becoming aware of it, where applicable. Article 34 separately addresses communication to affected individuals when the breach is likely to result in a high risk to their rights and freedoms.

The course checklist's 72-hour customer notification statement is reproduced as a case study assessment point and should not be interpreted as a complete statement of the GDPR legal requirement.

## 4. System and Organization Controls (SOC) Considerations

SOC reporting provides independent assurance over controls within a service organisation.

SOC 1 focuses on controls relevant to user entities' internal control over financial reporting.

SOC 2 evaluates controls against applicable Trust Services Criteria, including security, availability, processing integrity, confidentiality, and privacy.

### Assessment Checklist

| ID | Best Practice / Assessment Question | Yes | No | Explanation |
|---|---|:---:|:---:|---|
| SOC-01 | User access policies are established. | No | Yes | Least Privilege and Separation of Duties controls are not currently in place. All employees have access to internally stored data. |
| SOC-02 | Sensitive data, including PII and SPII, is confidential and private. | No | Yes | Encryption is not currently used to adequately protect the confidentiality of PII and SPII. |
| SOC-03 | Data integrity ensures information is consistent, complete, accurate, and validated. | Yes | No | The case study indicates that data integrity is in place. |
| SOC-04 | Data is available only to individuals authorised to access it. | No | Yes | Data is available to all employees, whereas access should be restricted to individuals who require it to perform their job responsibilities. |

### SOC Assessment Result

| Result | Count |
|---|---:|
| Yes | 1 |
| No | 3 |

**Key gaps identified:**

- Inadequate user access governance.
- Lack of confidentiality controls for sensitive information.
- Excessive access to internally stored data.
- Need for stronger access authorisation and monitoring.

**Recommendations:**

- Implement role-based access control and least privilege.
- Establish formal user access policies.
- Introduce periodic access reviews and approval procedures.
- Implement encryption for sensitive information.
- Strengthen logging and monitoring of access to critical systems and data.

## 5. Consolidated Compliance Assessment

| Framework | Yes | No | Total |
|---|---:|---:|---:|
| PCI DSS | 0 | 4 | 4 |
| GDPR | 2 | 2 | 4 |
| SOC Considerations | 1 | 3 | 4 |
| **Total** | **3** | **9** | **12** |

The results indicate that Botium Toys has significant gaps across payment data protection, access management, data classification, encryption, and authentication.

## 6. Overall Recommendations

The following actions should be prioritised:

1. Implement least privilege and separation of duties.
2. Restrict access to payment card information and sensitive customer data.
3. Introduce appropriate encryption mechanisms.
4. Strengthen password policies and centralised password management.
5. Establish formal data classification and inventory procedures.
6. Review privacy policies and data protection procedures.
7. Implement periodic user access reviews.
8. Improve security monitoring and logging.

## 7. Assessment Limitations

This assessment is based exclusively on information available in the fictional Botium Toys educational case study.

No independent audit testing, legal review, technical validation, or formal compliance assessment was conducted.

The checklist results represent educational observations and do not establish that Botium Toys is legally compliant or non-compliant with PCI DSS, GDPR, SOC 1, or SOC 2 requirements.
