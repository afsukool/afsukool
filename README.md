# Afsar Kuttiyassan

**Cybersecurity Engineer** · SOC Analysis · Detection Engineering · Active Directory Security

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Afsar%20Kuttiyassan-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/afsar-kuttiyassan)
[![GitHub](https://img.shields.io/badge/GitHub-afsukool-181717?style=flat&logo=github)](https://github.com/afsukool)
![Focus](https://img.shields.io/badge/Focus-Blue%20Team%20%7C%20Red%20Team-darkblue)

---

I build enterprise-grade security labs and document attack simulations end-to-end — from exploitation through SIEM detection, root cause analysis, and hardening recommendations.

My background in Windows infrastructure and Active Directory environments gives me a practical edge in understanding how real enterprise attacks work and how to detect them.

---

## 🔬 What I've Built

### [Enterprise AD Security Lab](https://github.com/afsukool/security-homelab)
Full multi-machine lab: Windows Server 2019 DC, domain-joined Windows 10 client, Splunk Enterprise SIEM, and Kali Linux attacker — all on an isolated `CORP.LOCAL` domain.

**Completed attack simulations with live detection validation:**

| Attack | MITRE | Splunk Detection |
|--------|-------|-----------------|
| Password Spraying | T1110.003 | EventCode=4625, multi-user spike from single src_ip |
| Kerberoasting | T1558.003 | EventCode=4769, Ticket_Encryption_Type=0x17 |
| AD Path Enumeration | T1069, T1482 | BloodHound + LDAP query correlation |
| Encoded PowerShell | T1059.001 | Sysmon ID 1, `-enc` / `IEX` in cmdline |

> 📄 [Full SOC Incident Report](https://github.com/afsukool/security-homelab/blob/main/docs/Afsar_Kuttiyassan_SOC_Incident_Report.pdf) — professional-grade writeup with evidence screenshots, MITRE mapping, and remediation recommendations.

---

### [Windows Hardening Project](https://github.com/afsukool/windows-hardening-project)
Security baseline implementation against a live Windows environment — Defender tuning, PowerShell Constrained Language Mode, ASR rules, GPO hardening, RDP lockdown, and local security policy review.

### [Pentesting Writeups](https://github.com/afsukool/pentest-writeups)
Documented HTB / VulnHub labs covering enumeration → exploitation → privilege escalation, with methodology notes and lessons learned.

### [Security Automation Scripts](https://github.com/afsukool/security-automation-scripts)
Python, PowerShell, and Bash scripts for log parsing, Windows auditing, IOC checks, and vulnerability scanning automation.

---

## 🛠️ Technical Stack

```
SIEM & Detection    Splunk Enterprise · Sysmon · Windows Event Logging · PowerShell Script Block Logging
AD & Identity       Active Directory · BloodHound · Impacket · Kerberos attack chains
Offensive           Kali Linux · Nmap · Burp Suite · CrackMapExec · Impacket suite
Defensive           Windows Hardening · GPO · ASR Rules · gMSA · Tiered Admin Model
Languages           Python · PowerShell · Bash
Networking          Wireshark · TCP/IP · DNS · LDAP · Kerberos · SMB
Vulnerability       Nessus · CVE analysis
```

---

## 📜 Certifications & Training

- **CPENT** — Training completed, exam scheduled
- **CCNA** — Networking fundamentals, routing & switching
- Windows enterprise environment experience (AD, endpoint support, infrastructure)

---

## 📊 GitHub Stats

![Afsar's GitHub Stats](https://github-readme-stats.vercel.app/api?username=afsukool&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=afsukool&layout=compact&theme=dark&hide_border=true)

---

*Focused on building real skills through real lab work — not certifications alone.*
