Access reviews ensure that users only have the permissions necessary to perform their job functions. They support:

-Least Privilege, Separation of Duties (SoD), Compliance with standards like SOC 2, ISO 27001, HIPAA, and NIST

# Types of Access Reviews
- Quarterly User Access Reviews (UARs)
- Privileged Access Reviews (PARs)
- System/Application-Specific Reviews



# Sample Quarterly Access Review

### Company: Couture Customs By Gina, LLC.
### System: Workday  
### Review Period: Q1 2025  
### Reviewer: John Doe, IAM Manager 
### Prepared By: Gina  

| User | Role | Last Login | Status | Action Needed |
|------|------|------------|--------|---------------|
| J. Smith | HR Admin | 12/10/24 | Active | Keep |
| K. Brooks | HR Viewer | 01/03/25 | Active | Remove – employee transferred teams |
| L. Carter | Payroll Admin | 11/29/24 | Active | Keep |
| P. Daniels | HR Admin | 05/2024 | Inactive | No longer an employee |

### To-Do
- 1 role removal needed  
- 1 inactive account (high risk)  
- Evidence retained in `/evidence/` folder

- # Access Review Checklist

✔ Obtain attestation document from manager
✔ Confirm roles match job responsibilities  
✔ Identify dormant/inactive accounts     
✔ Confirm terminated users are removed  
✔ Capture screenshots or reports as evidence  
✔ Submit tickets for access removal via ServiceNow
✔ Sign-off for audit

- # Manager Attestation Process

1. Export user access list from system  
2. Send list to managers with instructions  
3. Managers review and mark:
   - KEEP
   - REMOVE
   - CHANGE ROLE  
4. Collect responses  
5. Apply updates in system  
6. Validate changes  
7. Store evidence for audit (PDF, CSV, screenshots)

