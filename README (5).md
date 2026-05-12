# 📖 How To Use — Customer Interaction Tracker

---

## Getting Started

1. Download `customer-interaction-tracker.csv`
2. Open in **Microsoft Excel** or upload to **Google Sheets** (File → Import)
3. Each row represents one customer interaction
4. Fill in each field as you complete the interaction — don't wait until end of day

---

## Field Guide

| Field | What To Enter | Example |
|-------|---------------|---------|
| **Ticket ID** | Unique ID — use TKT-001, TKT-002, etc. (or pull from your CRM) | TKT-042 |
| **Date** | Date of interaction (YYYY-MM-DD format) | 2025-03-15 |
| **Time** | Time interaction started | 10:30 AM |
| **Agent Name** | Your full name | Udeme Olaniyan |
| **Contact Method** | Phone / Email / Chat | Phone |
| **Customer Name** | Customer's full name | Jane Smith |
| **Customer Email** | Email on account | jane@email.com |
| **Account ID** | Account reference number from CRM | ACC-10042 |
| **Issue Category** | Pick from the standard list below | Access - Password Reset |
| **Issue Description** | 1–2 sentences — what the customer reported | Customer cannot log in. Password rejected after recent update. |
| **Steps Taken** | Numbered list of everything you did | 1. Verified identity. 2. Sent reset link. 3. Confirmed login. |
| **Resolution Status** | Resolved / Escalated / In Progress / Follow-Up Pending | Resolved |
| **Resolution Time (mins)** | Total minutes from first contact to resolution | 6 |
| **Follow-Up Needed** | Yes / No | No |
| **Follow-Up Date** | If yes — when will you follow up? | 2025-03-18 |
| **Escalated To** | If escalated — who received it? | Tier 2 Network Team |
| **Notes** | Anything extra worth capturing | Customer mentioned issue started after Windows update |

---

## Standard Issue Categories

Use consistent categories to make filtering and trend analysis easier:

- `Access - Password Reset`
- `Access - Account Locked`
- `Access - Email Change`
- `Technical - VPN`
- `Technical - DNS`
- `Technical - App Crash`
- `Technical - Connectivity`
- `Billing - Incorrect Charge`
- `Billing - Cancellation`
- `Billing - Upgrade/Downgrade`
- `General - Feature Question`
- `General - Account Info Update`
- `General - Complaint`

---

## Useful Filters & Analysis (Google Sheets / Excel)

Once you have data, try these:

**Filter by status to find open cases:**
- Column L (Resolution Status) → Filter → "In Progress" or "Follow-Up Pending"

**Calculate average resolution time:**
- In an empty cell: `=AVERAGE(M2:M100)` (adjust range as needed)

**Count tickets by category:**
- Use a pivot table on Column I (Issue Category)

**Find cases needing follow-up today:**
- Column N (Follow-Up Needed) = Yes + Column O (Follow-Up Date) = today's date

---

## Tips for Real-World Use

- **Document during the interaction**, not after — memory fades fast on high-volume days
- **Be specific in "Steps Taken"** — vague notes don't help you or the next agent
- **Use the Notes field generously** — small details often matter on follow-up calls
- **Review your tracker weekly** — patterns in issue categories can highlight training gaps or product issues worth escalating to a manager

---

*Last updated: 2025 | Author: Udeme Olaniyan*
