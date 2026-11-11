# Botium Toys – Audit Recommendations and Remediation Plan

## 1. Purpose

This document defines recommended corrective actions for the security control gaps identified during the educational assessment of Botium Toys.

The objective is to reduce security risks, strengthen governance, and improve the organisation's overall control environment.

## 2. Remediation Action Plan

| ID | Finding | Recommended Remediation | Priority | Proposed Owner |
|---|---|---|---|---|
| F01 | Excessive user access | Implement role-based access control and least privilege | Critical | IT Security / IAM |
| F02 | Lack of segregation of duties | Identify conflicting responsibilities and introduce independent approvals | High | IT Governance |
| F03 | Unencrypted payment card data | Implement appropriate encryption and key management | Critical | Information Security |
| F04 | Weak password policy | Establish stronger authentication and password requirements | High | IT Security |
| F05 | No centralised password management | Implement centralised credential management | High | IAM Team |
| F06 | No intrusion detection | Deploy suitable IDS/IPS and security monitoring | High | Security Operations |
| F07 | No regular data backups | Establish scheduled backups and restoration testing | Critical | IT Operations |
| F08 | No disaster recovery plan | Document and test disaster recovery procedures | High | Business Continuity / IT Operations |
| F09 | Irregular legacy system maintenance | Establish scheduled patching and vulnerability assessments | High | Infrastructure Team |

## 3. Implementation Roadmap

### Phase 1 – Immediate Risk Reduction (0–30 Days)

- Review access to sensitive customer and payment information.
- Remove unnecessary access privileges.
- Identify critical data and backup requirements.
- Review password policy weaknesses.
- Assign accountable owners to all critical findings.

### Phase 2 – Control Improvement (31–60 Days)

- Implement role-based access control.
- Establish segregation of duties.
- Introduce centralised password management.
- Establish regular backup schedules.
- Document disaster recovery requirements.
- Define legacy system maintenance procedures.

### Phase 3 – Monitoring and Validation (61–90 Days)

- Deploy or improve intrusion detection and security monitoring.
- Perform backup restoration tests.
- Conduct user access reviews.
- Validate remediation evidence.
- Perform follow-up control testing.
- Report outstanding risks to management.

## 4. Audit Follow-up and Evidence Requirements

| Control Area | Example Evidence to Request |
|---|---|
| User access management | User access listing, role matrix, approval records |
| Segregation of duties | SoD matrix, conflict review, approval evidence |
| Encryption | Configuration evidence, encryption standards, key management records |
| Password security | Approved password policy and configuration settings |
| Password management | Credential management configuration and access records |
| Intrusion detection | IDS/IPS configuration, alert logs, incident records |
| Backups | Backup schedules, job logs, restoration test results |
| Disaster recovery | Approved DR plan and test reports |
| Legacy systems | Patch records, maintenance logs, vulnerability reports |

## 5. Remediation Tracking

The following fields should be maintained in a formal audit issue tracker:

- Finding ID
- Risk description
- Root cause
- Agreed management action
- Control owner
- Target completion date
- Current status
- Supporting evidence
- Auditor validation result
- Closure approval

## 6. Validation Approach

After management completes remediation, the auditor should:

1. Obtain evidence that the corrective action was implemented.
2. Verify that the revised control is appropriately designed.
3. Inspect relevant configurations, records, and approvals.
4. Perform sample-based testing where applicable.
5. Confirm that the control operated effectively over the required period.
6. Document the results and any remaining exceptions.

## 7. Conclusion

Effective remediation requires management accountability, clear deadlines, appropriate evidence, and independent validation.

The recommended 90-day roadmap provides a proposed sequence for addressing the identified weaknesses. Actual timelines should be agreed with management based on risk, resources, and business priorities.

## 8. Disclaimer

This is an independent educational remediation plan for a fictional organisation. Proposed owners and timelines are illustrative and have not been agreed by any real management team.
