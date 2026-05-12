# 🔧 Troubleshooting Guide — VPN Connection Issues

**Category:** Connectivity  
**Severity:** Medium–High (impacts access to all business systems)  
**Avg. Resolution Time:** 4–8 minutes

---

## Symptoms

- Customer cannot connect to VPN
- VPN connects but immediately drops
- VPN shows "Authentication Failed"
- VPN connected but no access to internal systems

---

## Step-by-Step Resolution

### Step 1 — Confirm Basic Internet Connectivity
Ask the customer:
> "Before we look at the VPN, can you open a browser and load any website — like google.com?"

- ✅ Internet works → proceed to Step 2
- ❌ Internet not working → redirect to ISP/router troubleshooting (see `internet-connectivity.md`)

---

### Step 2 — Check VPN Credentials
> "Let's make sure we're using the right login details. Can you re-enter your username and password carefully?"

- Remind customer: username is usually their **work email**, not a personal one
- Confirm CAPS LOCK is off
- If they've recently had a password reset, confirm they're using the **new** password

---

### Step 3 — Restart the VPN Client
> "Let's close the VPN application completely — not just minimize it — and reopen it."

1. Right-click the VPN icon in the system tray
2. Select **Exit** or **Quit** (not just close the window)
3. Reopen from the Start menu or desktop shortcut
4. Attempt connection again

---

### Step 4 — Check for Software Updates
> "Sometimes an outdated VPN client causes connection issues. Let's check if there's an update available."

- Open VPN client → Settings or Help → Check for Updates
- If update available: install, restart, retry

---

### Step 5 — Flush DNS Cache
> "I'm going to walk you through a quick technical step that often fixes this."

**Windows:**
```
1. Press Windows Key + R
2. Type: cmd → press Enter
3. Type: ipconfig /flushdns → press Enter
4. You should see: "Successfully flushed the DNS Resolver Cache"
5. Retry VPN connection
```

**macOS:**
```
1. Open Terminal (search "Terminal" in Spotlight)
2. Type: sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder
3. Enter your Mac password when prompted
4. Retry VPN connection
```

---

### Step 6 — Restart Router/Modem
> "Let's try restarting your router. This clears any network conflicts on your end."

- Unplug the router from power
- Wait 30 seconds
- Plug back in and wait for all lights to stabilize (about 2 minutes)
- Retry VPN

---

### Step 7 — Escalate if Unresolved
If Steps 1–6 do not resolve the issue:

- Document all steps taken in the ticket
- Note exact error message (screenshot if possible)
- Note OS version, VPN client version
- Escalate to Tier 2 with full context (see escalation SOP)

---

## Common Error Messages & What They Mean

| Error Message | Likely Cause | Quick Fix |
|---------------|--------------|-----------|
| Authentication Failed | Wrong credentials or expired password | Password reset |
| Connection Timed Out | Firewall or ISP blocking VPN port | Try alternate network |
| No Network Access | VPN connected but DNS not routing | Flush DNS (Step 5) |
| Certificate Error | Outdated VPN client | Update client (Step 4) |

---

## Notes for Agents

- Always confirm the customer's OS before starting (Windows vs macOS steps differ)
- If the customer is on a public WiFi (hotel, airport), VPN issues are common — recommend a mobile hotspot
- Document every step attempted in Salesforce before closing or escalating

---

*Last updated: 2025 | Author: Udeme Olaniyan*
