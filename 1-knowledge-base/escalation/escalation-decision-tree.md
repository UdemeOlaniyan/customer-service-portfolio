# 🔄 Escalation Decision Tree & Handoff Template

**Purpose:** Help agents decide when to escalate and how to hand off cases cleanly so nothing gets lost.

---

## When To Escalate — Decision Tree

```
Customer contacts support
         │
         ▼
Can you resolve this within your scope and tools?
         │
    ┌────┴────┐
   YES        NO
    │          │
    ▼          ▼
Resolve     Is it a known outage or system-wide issue?
& document       │
            ┌────┴────┐
           YES        NO
            │          │
            ▼          ▼
       Log ticket   Have you attempted all
       under known  troubleshooting steps?
       incident          │
                    ┌────┴────┐
                   YES        NO
                    │          │
                    ▼          ▼
              Escalate to   Continue
              Tier 2        troubleshooting
                    │
                    ▼
         Is it sensitive (security, billing, legal)?
                    │
               ┌────┴────┐
              YES        NO
               │          │
               ▼          ▼
         Escalate to  Escalate to
         Tier 2 +     standard
         flag urgency  Tier 2
```

---

## Escalation Triggers — Quick Reference

Escalate **immediately** (no further troubleshooting needed):

- ❗ Suspected security breach or unauthorized account access
- ❗ Customer reports identity theft
- ❗ Billing dispute over $100 or involving fraud
- ❗ Customer is abusive or threatening — escalate to supervisor
- ❗ Legal or compliance-related request (data deletion, GDPR, subpoena)

Escalate **after troubleshooting**:

- 🔁 Issue not resolved after all documented steps attempted
- 🔁 Same issue recurring for a customer 3+ times
- 🔁 Technical error you cannot replicate or explain
- 🔁 Account-level change requiring admin access beyond your permissions

---

## Escalation Handoff Template

Use this template in Salesforce when escalating a ticket. Copy, fill in, and paste into the internal notes field.

---

```
ESCALATION HANDOFF NOTE
========================
Date/Time: [DATE] [TIME]
Agent Name: [YOUR NAME]
Ticket ID: [SALESFORCE TICKET ID]
Escalating To: [TIER 2 / SUPERVISOR / BILLING TEAM / etc.]
Priority Level: [LOW / MEDIUM / HIGH / URGENT]

CUSTOMER INFORMATION
---------------------
Name: [CUSTOMER FULL NAME]
Account/Email: [ACCOUNT IDENTIFIER]
Contact Method: [PHONE / EMAIL / CHAT]
Identity Verified: [YES / NO — method used]

ISSUE SUMMARY
--------------
[2–3 sentence plain-language description of what the customer is experiencing]

STEPS ALREADY TAKEN
--------------------
1. [Step 1 — what you did and what happened]
2. [Step 2 — what you did and what happened]
3. [Step 3 — what you did and what happened]

ERROR MESSAGES / SCREENSHOTS
------------------------------
[Paste exact error message or describe what was observed]

REASON FOR ESCALATION
-----------------------
[Why this is being escalated — be specific. "Issue unresolved after all Tier 1 steps" or "Requires admin-level access" etc.]

CUSTOMER EXPECTATION SET
-------------------------
[What did you tell the customer to expect? "Tier 2 will follow up within 24 hours via email"]

URGENCY NOTE
-------------
[Any time sensitivity — "Customer has a presentation in 2 hours and needs access restored urgently"]
```

---

## After Escalating — What To Tell The Customer

> "I've escalated your case to our specialist team who have full visibility into what we've already tried. You won't need to repeat yourself. [They'll reach out within X hours / I'll follow up with you directly] — is [email/phone] still the best way to reach you?"

---

## Agent Notes

- Never escalate without completing the handoff note — an escalation without context wastes everyone's time
- Always tell the customer what happens next before ending the interaction
- If you're unsure whether to escalate, err on the side of escalating — it's better than leaving a customer stuck

---

*Last updated: 2025 | Author: Udeme Olaniyan*
