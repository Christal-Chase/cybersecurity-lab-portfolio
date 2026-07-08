# L02 - Password + MFA Audit

## Objective

The objective of this lab was to review five important accounts, assess password and multi-factor authentication status, identify authentication risks, and recommend improvements.

This lab helped me practice foundational cybersecurity concepts related to authentication, MFA, account protection, and risk reduction.

---

## Scenario

A user wants to improve the security of important personal and professional accounts. To reduce the risk of account compromise, I reviewed five account categories, checked password and MFA status, identified risks, and documented recommended improvements.

No passwords, recovery codes, backup codes, usernames, phone numbers, or sensitive personal details were stored in this lab.

---

## Tools Used

- Account security settings
- Password manager
- Spreadsheet 
- GitHub
- MFA settings

---

## Accounts Reviewed

The following account categories were reviewed:

- Primary email account
- GitHub account
- Cloud storage account
- Financial account
- Shopping account

---

## Password + MFA Audit Table

| Account Category | Data / Access Protected | Password Status | MFA Status | Main Risk | Recommended Improvement | Action Taken | Final Risk |
|---|---|---|---|---|---|---|---|
| Primary Email Account | Email, password resets, connected accounts | Strong / Unique | Enabled - Authenticator App | If compromised, attacker could reset other account passwords | Keep MFA enabled, review recovery options, monitor sign-ins | Reviewed settings and confirmed MFA | Low |
| GitHub Account | Portfolio, repositories, account profile | Strong / Unique | Enabled - Authenticator App or Passkey | Unauthorized access could alter or delete portfolio work | Enable MFA, use unique password, review active sessions | MFA confirmed or enabled | Low |
| Cloud Storage Account | Documents, photos, backups, shared files | Moderate / Unique | Enabled - SMS or App | Misuse could expose personal documents or shared files | Upgrade MFA to authenticator app, review sharing permissions | Reviewed MFA and sharing settings | Medium |
| Financial Account | Banking/payment information | Strong / Unique | Enabled - SMS or App | Account takeover could lead to financial fraud | Use strongest MFA available, enable alerts, review devices | Confirmed MFA and alerts | Low |
| Shopping / Payment Account | Saved cards, address, purchase history | Moderate / Reused or Unknown | Not Enabled or SMS | Saved payment methods could be abused | Change to unique password and enable MFA | Updated password and enabled MFA | Medium |

---

## Key Findings

The audit showed that accounts with access to password resets, financial information, cloud files, and professional work require stronger protection.

The primary email account is one of the most important accounts to secure because it can often be used to reset passwords for other accounts.

MFA significantly reduces account takeover risk, especially when paired with a strong and unique password.

---

## Risk or Gap Identified

The main risks identified were:

- Some accounts may rely on weak or reused passwords
- Some accounts may not have MFA enabled
- SMS-based MFA is better than no MFA, but stronger options may be available
- Recovery options need to stay updated
- Saved payment methods and cloud files increase the impact of account compromise

---

## Recommendations

Based on the audit, the following improvements are recommended:

1. Use a unique password for every important account
2. Enable MFA on all critical accounts
3. Use an authenticator app, passkey, or security key when available
4. Review account recovery options regularly
5. Remove old devices or sessions that are no longer used
6. Enable login alerts where available
7. Store backup codes securely outside of GitHub

---

## Screenshots / Evidence

Password and MFA audit table:

![Password MFA Audit Table](screenshots/password-mfa-audit-table.png)

---

## Reflection

This lab helped me understand that account security is one of the most practical areas of cybersecurity. Strong passwords are important, but passwords alone are not enough.

The biggest takeaway is that MFA adds an additional layer of protection and helps reduce the risk of account takeover. I also learned that documenting security improvements requires care because evidence should prove the work was completed without exposing sensitive information.
