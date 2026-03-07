# Plan of Action and Milestones (POA&M)

This POA&M documents identified weaknesses and planned remediation actions associated with the HRIS environment. Items listed below originate from risks identified during the risk assessment process and are tracked until remediation is completed.

---

## POA&M Items

| Weakness ID | Control Related | Weakness Description | Risk Level | Planned Remediation | Responsible Party | Target Completion Date | Status |
|-------------|----------------|---------------------|-----------|--------------------|------------------|-----------------------|--------|
| POAM-01 | AC-2 Account Management | Account provisioning and deprovisioning processes may not consistently enforce least privilege across HRIS administrative accounts. | High | Implement automated identity lifecycle management and quarterly access reviews to ensure privileges align with assigned roles. | HRIS System Owner | 2026-09-30 | Open |
| POAM-02 | IA-2 Identification and Authentication | User credential compromise through phishing or password reuse could allow unauthorized access to HRIS resources. | High | Enforce multi-factor authentication (MFA) through the enterprise identity provider and implement user security awareness training. | Identity Management Team | 2026-08-15 | Open |
| POAM-03 | AU-6 Audit Review | Security logs may not be consistently reviewed for suspicious activity, increasing the likelihood of delayed threat detection. | Medium | Establish scheduled log review procedures and integrate automated alerting through the organization's security monitoring tools. | Security Operations Team | 2026-10-01 | Open |

---

## POA&M Tracking Process

POA&M items are reviewed periodically to track remediation progress. Responsible parties provide status updates until the weakness has been mitigated or risk acceptance has been formally approved.

Remediation activities may include:

• Control implementation improvements  
• System configuration changes  
• Policy or procedure updates  
• Additional monitoring controls
