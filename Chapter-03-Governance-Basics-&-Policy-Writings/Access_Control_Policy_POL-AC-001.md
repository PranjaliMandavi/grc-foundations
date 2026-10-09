# POL-AC-001 Access Control Policy

| Field | Value |
|---|---|
| Organization | Mandavi FinTech Pvt. Ltd. (fictional) |
| Version | 0.2 (draft) |
| Owner | Head of Information Security (fictional role) |
| Approver | Chief Information Security Officer (fictional role) |
| Review cycle | Every 12 months, or after a High-rated change request |
| Related frameworks | NIST SP 800-53 Rev 5, ISO/IEC 27001:2022, CIS Controls v8 |

## 1. Purpose
Make sure only authorized people can reach company systems and data, and only to the
extent their job needs.

## 2. Scope
All employees, contractors and service accounts, and all systems that store or process
company or customer data.

## 3. Policy requirements

| ID | Requirement | NIST 800-53 Rev 5 | ISO 27001:2022 | CIS v8 | How to check |
|---|---|---|---|---|---|
| AC-R1 | Access is granted by approved request and based on role and least privilege. | AC-2, AC-3, AC-6 | A.5.15, A.5.18 | 6.1, 6.8 | Sample of access requests with approvals |
| AC-R2 | Every user has a unique ID. Shared accounts are not allowed. | AC-2, IA-2 | A.5.16 | 5.1 | Account list with duplicates check |
| AC-R3 | Multi-factor authentication is required for remote access, administrator access and externally exposed applications. | IA-2(1), IA-2(2), AC-17 | A.8.5 | 6.3, 6.4, 6.5 | Share of in-scope accounts with MFA |
| AC-R4 | Administrators use separate privileged accounts, restricted to those who need them. | AC-6 | A.8.2 | 5.4 | List of privileged accounts vs approved list |
| AC-R5 | Access is removed within 24 hours of exit and updated on role change. | AC-2, PS-4, PS-5 | A.6.5, A.5.18 | 6.2 | Exit list vs account disable dates |
| AC-R6 | Accounts inactive for 45 days are disabled. | AC-2(3) | A.5.18 | 5.3 | Last-login report |
| AC-R7 | Access rights are reviewed every quarter by system owners. | AC-2 | A.5.18 | 6.1 | Signed review records |
| AC-R8 | Access and authentication events are logged and reviewed. | AU-2, AU-6 | A.8.15 | 8.2, 8.11 | Log samples and review records |

## 4. Roles
- **Policy owner:** maintains the policy and tracks change requests.
- **System owner:** approves access and performs quarterly reviews.
- **IT operations:** provisions and removes access.
- **All users:** protect their credentials and report suspected misuse.

## 5. Exceptions
An exception needs a written reason, a named owner, compensating controls and an expiry
date, approved by the CISO and recorded in the change request log.

## 6. Enforcement
Violations are reported to the policy owner and may lead to loss of access and
disciplinary action under company rules.

## 7. Version history

| Version | Date | Change | Author |
|---|---|---|---|
| 0.1 | 2026-10-09 | Initial draft | Pranjali Mandavi |
| 0.2 | 2026-10-09 | Added MFA requirement after CR-001; added dormant account rule after CR-002 | Pranjali Mandavi |
