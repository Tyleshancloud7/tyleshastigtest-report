# 🥷🏽💎 STIG Lab Vulnerability Hunt – GitHub Hero Edition

> “Notepad Tried to Become a Hacker” 💻💥  

**Target:** Tylesha11STIGTest  
**Scanner:** Tenable / Nessus  
**Scan Type:** Credentialed  

> ⚡ Pro Tip: Always check your built-in apps. They might be plotting.

---

## 📊 Executive Summary

| Severity | Count |
|----------|--------|
| 🔴 Critical | 0 |
| 🟠 High | 5 |
| 🟡 Medium | 2 |
| 🔵 Low | 2 |
| ℹ️ Informational | 124 |
| **Total Findings** | **133** |

---

## 🚨 High Severity Findings (Patch Immediately)

| Issue | Impact |
|-------|--------|
| Missing Security Updates | Potential system compromise |
| Notepad < 11.2510 – Command Injection | Local RCE risk |
| Microsoft Teams – Remote Code Execution | Exploitable vulnerability |
| Windows Defender Signature Issues | Antivirus protection may fail |
| WinVerifyTrust Signature Validation (CVE-2013-3900) | Certificate trust bypass |

---

## 🟡 Medium / 🔵 Low Severity Findings

- SSL Self-Signed Certificate  
- SSL Certificate Cannot Be Trusted  
- ICMP Timestamp Disclosure  
- Microsoft Teams Elevation of Privilege  

---

## ℹ️ Informational Findings (124)

- SMB Shares  
- Installed Software Inventory  
- Patch Reports  
- OS & Network Interfaces  

---

## 🧪 Lab Build – Environment Configuration

### 1️⃣ Windows 11 Lab Setup
- Created Windows 11 VM named **Tylesha11STIGTest**
- Disabled Windows Firewall
- Opened NSG (all inbound allowed)
- Verified connectivity with `ping`

### 2️⃣ Intentional Misconfiguration
- Enabled built-in Administrator account
- Set blank password and disabled expiration
- Added Administrator to Administrators group
- Enabled Guest account
- Added Guest to Administrators group
- No password configured

### 3️⃣ Nessus Scan Configuration

**Template:** Advanced Network Scan  

**Basic Settings**
- Start Remote Registry  
- Enable Admin Shares  
- Start Server Service  

**Discovery**
- Ping Host  
- Fast Network Discovery  
- TCP Port Scan  

**Assessment**
- Perform thorough tests  
- Disabled “Only use credentials”  

**Compliance**
- DISA Windows 11 STIG v2r5  
- Enabled policy and plugin checks  

---

## 🚀 Scan Execution

- Created new scan  
- Entered target IP address  
- Launched scan  
- Monitored results  

---

## 🛠️ Remediation Plan

- Patch Outlook  
- Patch Microsoft Teams  
- Update Notepad  
- Update Defender signatures  
- Enable CertPaddingCheck mitigation  
- Replace self-signed SSL certificate  
- Re-scan to validate remediation  

---

## 🧠 Final Thoughts

- No Critical vulnerabilities detected  
- Security requires consistency and validation  
- Always re-scan after remediation  

---

⭐ If you found this project helpful, consider starring the repository.

---

**Author:** Tylesha A  
Cybersecurity | GRC | STIG Lab Practice

