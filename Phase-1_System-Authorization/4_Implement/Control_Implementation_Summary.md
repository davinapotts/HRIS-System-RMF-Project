# Control Implementation Summary

The following control implementation statements reflect selected controls from the Moderate baseline defined in NIST SP 800-53 Rev. 5 and NIST SP 800-53B tailored for the HRIS system. Control classifications include common, hybrid, and system-specific responsibilities in accordance with the shared responsibility model. The controls included in this repository represent a selected sample of that baseline and are provided for demonstration purposes to illustrate how controls are analyzed, classified, and documented within the system.

---

## AC-1 Access Control Policy and Procedures (Common Control)

### Control Type
Common

### Implementation Description
The Chief Information Security Officer (CISO) is responsible for establishing and maintaing the agency's Access Control Policy. HRIS-specific access control procedures are developed and maintained in alignment with the agency's Access Control Policy to ensure consistenent implementation of enterprise security requirements within the system. The Access Control Policy is reviewed at least annually and updated as necessary, or upon significant organizational, regulatory, or system changes, to ensure continued alignment with enterprise security requirements. The HRIS System Owner is responsible for ensuring that access control requirements are implemented within the system in accordance with agency policy and documented procedures.

### Control Responsibility
Control Provider: Chief Information Security Officer  
System Responsible Party: HRIS System Owner

---

## AC-2 Account Management (Hybrid Control)

### Control Type
Hybrid

### Implementation Description
HRIS user accounts are provisioned upon request by Human Resources administrators and require approval from the HRIS System Owner prior to activation. Access privileges are assigned using role-based access control principles and are limited to the minimum permissions necessart to perform assigned job function. User accounts are promptly disabled upon employee separation or role change to prevent unauthorized access. The HRIS System Owner and designated administrators conduct quarterly reviews of active accounts and associated privileges to validate continued access requirements and ensure alignment with assigned roles.

### Control Responsibility
Enterprise Portion:
- Control Provider: Enterprise Identity Management Team  
- Responsible Party: Identity Services Manager  

HRIS Application Portion:
- Control Provider: HRIS Administrators  
- Responsible Party: HRIS System Owner  

---

## AC-6 Least Privilege (Hybrid Control)

### Control Type
Hybrid

### Implementation Description
Access to HRIS functionality is assigned through predefined role-based access controls aligned to job functions, including HR Administrator, HR Specialist, Manager, Employee Self Service, Payroll Viewer, and Auditor. Each role contains only the permissions necessary to perform assigned duties within the application. Administrative privileges are granted through dedicated administrative roles that are separate from standard user roles to prevent unauthorized elevation of access. Direct database and infrastructure access is restricted to the SaaS vendor, while organizational administrators are limited to approved application-level configuration interfaces. The HRIS System Owner and designated administrators conduct quarterly reviews of all user and privileged role assignments to verify continued adherence to least privilege. User accounts are disabled promptly upon employee separation or role change in accordance with enterprise access control procedures.
### Control Responsibility
Enterprise Portion:
- Control Provider: Enterprise Identity Management Team  
- Responsible Party: Identity Services Manager  

HRIS Application Portion:
- Control Provider: HRIS Administrators  
- Responsible Party: HRIS System Owner  
