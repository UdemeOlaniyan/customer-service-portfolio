# 🗺️ CRM Workflow Diagram — Customer Complaint (Billing)

```
INBOUND CONTACT (Phone / Email / Chat)
              │
              ▼
┌─────────────────────────────────┐
│  GREET & LISTEN                 │
│  • Warm, professional greeting  │
│  • Let customer explain fully   │
│  • Begin CRM search in parallel │
└────────────────┬────────────────┘
                 │
                 ▼
┌─────────────────────────────────┐
│  VERIFY IDENTITY                │
│  • Name                         │
│  • Email on file                │
│  • Account ID / DOB             │
│  ⚠️ Never skip this step        │
└────────────────┬────────────────┘
                 │
                 ▼
┌─────────────────────────────────┐
│  INVESTIGATE ISSUE              │
│  • Pull account/billing history │
│  • Check for known system issues│
│  • Confirm problem exists       │
│  • Tell customer: "You're right"│
└────────────────┬────────────────┘
                 │
        ┌────────┴────────┐
        │                 │
        ▼                 ▼
  WITHIN MY          OUTSIDE MY
  AUTHORITY          AUTHORITY
        │                 │
        ▼                 ▼
┌──────────────┐  ┌──────────────────────┐
│ RESOLVE      │  │ ESCALATE             │
│ DIRECTLY     │  │ • Complete handoff   │
│              │  │   note in CRM        │
│ • Take action│  │ • Tell customer what │
│ • Give ref # │  │   happens next       │
│ • Confirm    │  │ • Set expectations   │
│   resolution │  └──────────┬───────────┘
└──────┬───────┘             │
       │                     │
       └──────────┬──────────┘
                  │
                  ▼
┌─────────────────────────────────┐
│  CLOSE INTERACTION              │
│  • Confirm customer is satisfied│
│  • Ask if anything else needed  │
│  • Professional closing         │
│  • Set follow-up if needed      │
└────────────────┬────────────────┘
                 │
                 ▼
┌─────────────────────────────────┐
│  DOCUMENT IN CRM                │
│  • Contact type & timestamp     │
│  • Issue category               │
│  • Every step taken             │
│  • Resolution outcome           │
│  • Follow-up flag if needed     │
│  ✅ 100% of tickets documented  │
└─────────────────────────────────┘
```

---

## Key Decision Points

| Decision | Criteria | Action |
|----------|----------|--------|
| Escalate or resolve? | Is the issue within my tool access and authority? | Resolve if yes; escalate if no |
| Follow-up needed? | Will something happen after the call that needs checking? | Flag with date if yes |
| Urgent escalation? | Security issue, fraud, or legal concern? | Immediate escalation + supervisor flag |
| Known issue? | Is this in the system-wide incident log? | Log under known incident; don't open duplicate |

---

*Last updated: 2025 | Author: Udeme Olaniyan*
