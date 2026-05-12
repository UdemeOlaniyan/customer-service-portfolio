# 🔧 Troubleshooting Guide — Password Reset & Account Unlock

**Category:** Identity & Access  
**Severity:** High (blocks all system access)  
**Avg. Resolution Time:** 2–5 minutes

---

## Symptoms

- Customer cannot log in — password not accepted
- Account shows as locked
- Customer never received password reset email
- Customer forgot security question answers

---

## Step-by-Step Resolution

### Step 1 — Identify the Issue Type
Ask:
> "Are you seeing an error message? Can you read it to me exactly?"

| Message | Issue Type |
|---------|------------|
| "Incorrect password" | Wrong credentials — attempt reset |
| "Account is locked" | Too many failed attempts — unlock required |
| "Account not found" | Wrong username — verify identity |
| No message / spinning | System issue — check service status |

---

### Step 2 — Verify Customer Identity
Before taking any action, confirm identity:

- Full name
- Email address on file
- Last 4 digits of employee/account ID (if applicable)
- Date of birth or security verification question

> ⚠️ **Never reset a password without completing identity verification.**

---

### Step 3a — Password Reset (Wrong Password)

1. Navigate to account management portal
2. Search customer by verified email
3. Select **Reset Password**
4. Choose: **Send reset link to email on file**
5. Confirm with customer:
   > "I've sent a reset link to [email]. Check your inbox — it may take 2–3 minutes. Also check your spam folder."
6. Stay on the line while they complete the reset
7. Confirm successful login before closing ticket

---

### Step 3b — Account Unlock (Locked Account)

1. Navigate to account management portal
2. Search customer by verified email
3. Select **Unlock Account**
4. Once unlocked, advise customer:
   > "Your account is unlocked. Please try logging in now with your current password. If you've forgotten it, I can send a reset link at the same time."
5. Confirm successful login before closing ticket

---

### Step 4 — If Reset Email Not Received

1. Confirm correct email address is on file
2. Ask customer to check spam/junk folder
3. If wrong email on file → escalate to account management team to update
4. If correct email, no email received after 5 minutes → resend reset link
5. If still not received → escalate to Tier 2 (possible mail server issue)

---

### Step 5 — Document and Close

In Salesforce, log:
- Issue type (wrong password / locked account / no reset email)
- Identity verification method used
- Steps taken
- Resolution outcome
- Any follow-up needed

---

## Agent Notes

- Never share a temporary password over chat or email — always use the self-service reset link
- If a customer reports being locked out multiple times in a short period, flag for security review
- Password resets are high-sensitivity actions — document thoroughly

---

*Last updated: 2025 | Author: Udeme Olaniyan*
