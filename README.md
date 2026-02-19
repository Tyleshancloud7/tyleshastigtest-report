nano README.md

# 🥷🏽💎 STIG Lab Vulnerability Hunt  
## “Notepad Tried to Become a Hacker”

> Target: `tyleshastigtest`  
> Scanner: Tenable / Nessus  
> Scan Type: Credentialed  
> Mood: Calm. Patchy. Slightly offended at Notepad.

---

# 📊 Executive Summary (The Tea ☕)

| Severity | Count |
|----------|--------|
| 🔴 Critical | 0 |
| 🟠 High | 5 |
| 🟡 Medium | 2 |
| 🔵 Low | 2 |
| ℹ️ Info | 124 |
| **Total** | **133** |

## 📸 Executive Summary Evidence
![Executive Summary](screenshots/Screenshot 2026-02-17 at 1.20.00 PM.png)

---

# 🚨 High Severity Findings (a.k.a. “Fix Me Immediately”)

- Outlook Missing Security Updates  
- Notepad < 11.2510 – Command Injection 😭  
- Microsoft Teams – Remote Code Execution  
- Windows Defender Signature Issues  
- WinVerifyTrust Signature Validation (CVE-2013-3900 Mitigation)

### Translation:
Even the built-in apps said:  
> “Let’s be exploitable today.”

## 📸 High Severity Screenshot
![High Findings](screenshots/Screenshot 2026-02-17 at 5.31.23 PM.png)

---

# 🟡 Medium / Low Severity (Suspicious Behavior)

- SSL Self-Signed Certificate  
- SSL Certificate Cannot Be Trusted  
- ICMP Timestamp Disclosure  
- Microsoft Teams Elevation of Privilege  

> Because in cybersecurity, we clean everything.

## 📸 Medium / Low Screenshot
![Medium / Low Findings](screenshots/Screenshot 2026-02-17 at 6.14.19 PM.png)

---

# ℹ️ Informational Findings (124)

Examples: SMB shares, installed software, patch report, OS info, network interfaces  

## 📸 Informational Findings Screenshot
![Informational Findings](screenshots/Screenshot 2026-02-17 at 6.19.32 PM.png)

---

# 🛠️ Remediation Plan

- Patch Outlook, Teams, and Notepad  
- Update Defender signatures  
- Enable CertPaddingCheck mitigation  
- Replace self-signed SSL certificate  
- Re-scan and validate

---

# 🧠 Final Thoughts

No Critical vulnerabilities detected.  
Notepad attempting command injection? That was personal.  

Security is not hype.  
It’s consistency.

