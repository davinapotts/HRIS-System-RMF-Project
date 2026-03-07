# HRIS Risk Register

This risk register summarizes key risks identified for the Human Resources Information System (HRIS).  
Risks were evaluated based on threat sources, system vulnerabilities, potential impact to HR operations, and the effectiveness of implemented security controls.

A detailed working risk register, including full threat modeling and likelihood reasoning, is maintained in the project risk register spreadsheet.

---

## Identified System Risks

| Risk ID | Asset | Risk Description | Risk Level | Risk Treatment | Risk Owner | Residual Risk |
|-------|------|----------------|-----------|--------------|-----------|-------------|
| HRIS-DB-R-01 | HRIS Database | SQL injection attack through application interfaces leading to unauthorized access or modification of employee data | High | Mitigate | HRIS System Owner | Medium |
| HRIS-DB-R-02 | HRIS Database | Insider accessing HR database beyond assigned privilege level due to improper access controls | High | Mitigate | HRIS System Owner | Medium |
| HRIS-DB-R-03 | HRIS Database | Data migration errors during system updates resulting in corruption or loss of HR records | High | Mitigate | HRIS System Owner | Medium |
| HRIS-DB-R-04 | HRIS Database | Exploitation of database software vulnerabilities due to delayed patching | High | Mitigate | HRIS System Owner | Medium |
| HRIS-DB-R-05 | HRIS Database | Environmental or infrastructure disruption impacting database availability | Medium | Transfer | Cloud Service Provider | Medium |
| HRIS-DB-R-06 | HRIS Database | Third-party cloud provider outage affecting HRIS availability | Medium | Transfer | Cloud Service Provider | Medium |
| HRIS-DB-R-07 | HRIS Database | Denial-of-Service attack overwhelming system resources | Medium | Mitigate | HRIS System Owner | Medium |
| HRIS-APP-R-01 | HRIS Web Application | Authenticated user bypassing application authorization controls | High | Mitigate | HRIS Application Owner | Medium |
| HRIS-APP-R-02 | HRIS Web Application | Misconfigured application settings exposing sensitive HR data | High | Mitigate | HRIS Application Owner | Medium |
| HRIS-IDP-R-01 | Identity Provider (SSO with MFA) | Compromised user credentials through phishing or password reuse | High | Mitigate | Identity Management Team | Medium |
| HRIS-INT-R-01 | Integration Layer | Exploitation of insecure API connections between HRIS and external systems | High | Mitigate | HRIS Application Owner | Medium |
| HRIS-LOG-R-01 | Logging and Monitoring | Failure to review security logs resulting in delayed detection of suspicious activity | High | Mitigate | Security Operations Team | Medium |

---

## Risk Evaluation Method

Risks were evaluated using qualitative analysis based on:

• Threat likelihood  
• Potential impact to HR operations and employee data  
• Existing security controls within the HRIS environment  

Risk treatment decisions follow standard response strategies:

Mitigate  
Transfer  
Accept  
Avoid

---

## Relationship to Security Controls

Many identified risks are addressed through security controls implemented within the HRIS environment, including:

AC-2 Account Management  
AC-6 Least Privilege  
IA-2 Identification and Authentication  
AU-6 Audit Review

These controls reduce the likelihood or impact of identified threats and contribute to lowering residual risk levels.
