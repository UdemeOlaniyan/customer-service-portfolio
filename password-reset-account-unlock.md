# 📋 SOP — Daily Customer Support Workflow

**Purpose:** Standardize the start-to-finish workflow for handling customer support interactions to ensure consistency, quality, and full documentation.

---

## SOP Overview

| Phase | Action | Time Estimate |
|-------|--------|---------------|
| 1 | Start of shift — system check | 5 min |
| 2 | Receive and triage incoming contact | 1–2 min |
| 3 | Verify customer identity | 1–2 min |
| 4 | Investigate and resolve issue | Varies |
| 5 | Document the interaction | 2–3 min |
| 6 | Close or escalate | 1 min |
| 7 | End of shift — queue check | 5 min |

---

## Phase 1 — Start of Shift System Check

Before taking any contacts:

- [ ] Log into all required systems (CRM, phone/VoIP, email, remote desktop)
- [ ] Check for any active system outages or known incidents
- [ ] Review any handoff notes from the previous shift
- [ ] Confirm your status is set to **Available** in the phone/chat queue
- [ ] Review the top 3 most common issues from the prior day (check team notes or ticket trends)

---

## Phase 2 — Receive and Triage Incoming Contact

When a contact comes in (call, email, or chat):

**For calls:**
- Answer within 3 rings
- Open CRM and begin searching for the customer's account while greeting
- Standard greeting: *"Thank you for calling [Company] support, this is [Your Name]. How can I help you today?"*

**For emails/chat:**
- Acknowledge within [SLA window]
- Read the full message before responding — never reply to the first line only
- Check if a previous ticket exists for this customer before opening a new one

**Triage questions to ask yourself:**
1. Is this urgent (no system access, security concern)?
2. Is this a known issue with an existing resolution?
3. Is this within my scope to resolve, or does it need escalation?

---

## Phase 3 — Verify Customer Identity

Before accessing or changing any account information:

- Confirm full name
- Confirm email address on file
- Confirm account ID or last 4 digits of employee ID (if applicable)
- Use secondary verification if first check fails (date of birth, security question)

> ⚠️ **Do not skip identity verification.** Even if the customer sounds legitimate — anyone can call.

---

## Phase 4 — Investigate and Resolve

- Use the knowledge base first — check if a documented solution exists
- Follow the relevant troubleshooting guide step by step
- Do not skip steps even if you think you know the answer
- Keep the customer informed throughout:
  > *"I'm looking into that now — give me just a moment."*
  > *"I'm going to try something that usually resolves this."*
- If resolution takes longer than 3 minutes, set expectations:
  > *"This will take me about [X] more minutes — I appreciate your patience."*

---

## Phase 5 — Document the Interaction

**Every single interaction must be documented in Salesforce before closing.** No exceptions.

Required fields:

```
Contact Type:       [Call / Email / Chat]
Customer Name:      [Full name]
Account ID:         [Account identifier]
Issue Category:     [Access / Billing / Technical / General]
Issue Description:  [2–3 sentences — what the customer reported]
Steps Taken:        [Numbered list of everything attempted]
Resolution:         [What fixed it, or why it's being escalated]
Follow-Up Needed:   [Yes / No — if yes, specify what and when]
QA Notes:           [Anything unusual or worth flagging]
```

---

## Phase 6 — Close or Escalate

**If resolved:**
- Confirm with the customer before ending:
  > *"Does everything look good on your end now? Is there anything else I can help you with?"*
- Update ticket status to **Resolved** in Salesforce
- Send follow-up confirmation email if the issue was complex

**If escalating:**
- Complete the full escalation handoff note (see `escalation-decision-tree.md`)
- Tell the customer what happens next before ending the call
- Do not leave the customer without a clear next step

---

## Phase 7 — End of Shift Queue Check

Before logging off:

- [ ] Confirm no open tickets are left without a status update
- [ ] Any pending tickets: add a note with current status and expected next action
- [ ] Leave handoff notes for the next shift if anything is mid-resolution
- [ ] Set status to **Unavailable** or **Offline** in all queues
- [ ] Log out of all systems

---

## Quality Standards

| Metric | Target |
|--------|--------|
| Same-day resolution rate | 95%+ |
| QA accuracy score | 96–100% |
| Average resolution time | Under 10 minutes |
| Documentation completion | 100% of tickets |
| Customer follow-up (complex cases) | Within 24 hours |

---

*Last updated: 2025 | Author: Udeme Olaniyan*
