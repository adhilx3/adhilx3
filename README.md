<div align="center">

# 🛡️ Adhil Parokkot
### **Information Security | Defensive Tool Developer | CEH Candidate**

[![Live Portfolio](https://img.shields.io/badge/Portfolio-adhilparokkot.vercel.app-E11D2E?style=for-the-badge&logo=vercel&logoColor=white)](https://adhilparokkot.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Adhil_Parokkot-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adhil-parokkot-86b688380/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-adhil.parokkot-A20000?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/adhil.parokkot)
[![Email](https://img.shields.io/badge/Email-adhilsaju3551%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adhilsaju3551@gmail.com)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=adhilx3&color=E11D2E&style=flat-square&label=PROFILE+VIEWS" alt="Profile Views" />
</p>

---

</div>

## 📌 Executive Summary

I am an **Information Security** student and **Security Tool Developer** pursuing an Advanced Diploma in Information Security and preparing for the **Certified Ethical Hacker (CEH)** credential. 

I focus on **defensive automation**, **protocol reconnaissance**, and **threat triage tooling**. Rather than relying solely on off-the-shelf tools, I build software that audits protocols against RFC standards, detects anomalies in high-velocity telemetry, and automates triage workflows.

- 🎓 **Education:** Advanced Diploma in Information Security (Network Defense, OS Internals, Web Application Security)
- 📜 **Certifications:** Certified Ethical Hacker (CEH) — *In Active Preparation*
- 🎯 **Hands-On Labs:** [TryHackMe Active Practitioner](https://tryhackme.com/p/adhil.parokkot) (Privilege Escalation, Network Enumeration, Web Exploits)
- 📍 **Location:** Kerala, India
- 💼 **Career Focus:** Open to **Security Engineering Internships**, **Junior SOC Analyst**, **AppSec**, and **Junior Security Operations** roles at global enterprises.

---

## 🔬 Featured Engineering & Security Projects

### 1. [dns-recon — DNS Hygiene, Email Spoofing & OSINT Suite](https://github.com/adhilx3/Portfolio)
> **Defensive reconnaissance scanner verifying RFC compliance, email spoofing resistance, and infrastructure attack surfaces.**
- **Live Deployment:** [dns-recon.vercel.app](https://dns-recon.vercel.app)
- **Email Security Auditing:** Validates **SPF** (RFC 7208 10-lookup limit, syntax, duplicate detection), **DMARC** (RFC 7489 enforcement policies `p=reject`/`quarantine`, aggregate `rua` reporting), and cryptographic **DKIM** key size validation (<2048-bit flagged).
- **Advanced Protocols:** Audits **BIMI** (Brand Indicators with VMC checks) and **MTA-STS & TLS-RPT** (RFC 8461/8460) to protect against SMTP STARTTLS stripping.
- **OSINT & Subdomain Takeovers:** Scans 15+ cloud provider fingerprints (AWS S3, CloudFront, Azure, GitHub Pages) for dangling CNAMEs, integrates Certificate Transparency logs (`crt.sh`), and maps IP/reverse PTR records.
- **Reliability:** Built with Python, comprehensive test suite with **70+ automated tests**, and interactive web dashboard.

---

### 2. [V-Scan — Privacy-First Malware Triage Engine](https://github.com/adhilx3/V-Scan-by-dazai)
> **Windows desktop malware triage application querying VirusTotal's 70+ threat intelligence engines.**
- **Privacy-First Hash Triage:** Computes local **SHA-256** digests client-side first, querying VirusTotal v3 by hash to ensure confidential or sensitive files are never uploaded without explicit operator consent.
- **Multi-Engine Breakdown:** Aggregates real-time threat intelligence into clear triage states: *Clean*, *Suspicious (1–4 flags)*, and *Dangerous (5+ flags)* with per-engine breakdowns.
- **Architecture:** Multi-threaded CustomTkinter architecture keeping the UI non-blocking during network queries, complete with automated standalone executable builds (`build.py`).

---

### 3. [Six7-X-Security — Discord Defensive Operations & Anti-Raid](https://github.com/adhilx3/Six7-X-Security)
> **High-concurrency anti-nuke, anti-raid, and server defense bot with an embedded FastAPI management dashboard.**
- **Anti-Nuke Defense Engine:** Sliding-window rate-limiting monitors administrative audit logs in real-time. Immediately strips dangerous permissions (`administrator`, `ban_members`, `manage_roles`) upon detecting rogue actions.
- **Smart Lockdown & Clean State Persistence:** Automatically locks channels during mass-join raids while caching original channel permission states, cleanly restoring original permissions upon unlock.
- **Intelligent Auto-Mod:** Regex word boundaries (`\b`) preventing false positives, homoglyph/leetspeak obfuscation normalization, and malicious attachment/link blocking.
- **Embedded Control Center:** Real-time web dashboard powered by **FastAPI** and **Tailwind CSS** supporting dual-mode authentication (Discord OAuth2 + Master Key).

---

### 4. [Phishing-Detector — Heuristic URL Analysis Engine](https://github.com/adhilx3/Phishing-Detector)
> **Lexical and structural heuristic analyzer evaluating suspicious links across 12 threat indicators.**
- **Heuristic Rule Matrix:** Detects raw IP masquerading, `@` delimiter destination masking, missing TLS/HTTPS, suspicious TLDs, typosquatting patterns, and Punycode/IDN homograph attacks.
- **Explainable Triage:** Generates deterministic risk tiers (*LOW*, *MEDIUM*, *HIGH*) with detailed explanation breakdowns for security analysts.
- **Delivery:** Standalone compiled CLI binary supporting batch file evaluation (`--file urls.txt`).

---

## 🛠️ Technical Competency Matrix

| Domain | Technologies & Tooling |
| :--- | :--- |
| **Core Languages** | Python, TypeScript, JavaScript, C++, SQL (SQLite / aiosqlite), Bash |
| **Security & Penetration Testing** | Kali Linux, Nmap, Burp Suite, VirusTotal API v3, Wireshark, Metasploit, Gobuster |
| **Defensive & Protocol Engineering** | DNS & Email Spoofing Defense (SPF, DMARC, DKIM, MTA-STS, BIMI), Threat Intelligence Triage, Heuristic Analysis, Anti-Abuse Rate Limiting |
| **Web & Application Engineering** | React 19, Vite, Tailwind CSS, FastAPI, GSAP (Motion & UI), REST APIs, PyInstaller |
| **Software Quality & DevOps** | Vitest, Pytest, Git & GitHub Actions, Vercel Edge Network, Linux Host Hardening |

---

## 📊 Live GitHub Telemetry

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=adhilx3&theme=tokyonight" alt="Adhil's GitHub Stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=adhilx3&theme=tokyonight" alt="Top Languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=adhilx3&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

## ⚖️ Code of Ethics & Disclosure Statement

> *"The only way to learn security is to practice it, legally and ethically."*

All security utilities, reconnaissance scripts, and proof-of-concept tools developed and maintained in my repositories are designed strictly for **educational research**, **defensive engineering**, and **authorized security assessments** within environments owned or formally contracted with explicit permission. I strictly adhere to standard responsible disclosure guidelines and promote defensive cybersecurity practices.

---

## 📬 Connect with Me

- 🌐 **Interactive Portfolio:** [adhilparokkot.vercel.app](https://adhilparokkot.vercel.app)
- 💼 **LinkedIn:** [linkedin.com/in/adhil-parokkot-86b688380](https://www.linkedin.com/in/adhil-parokkot-86b688380/)
- 🎯 **TryHackMe:** [tryhackme.com/p/adhil.parokkot](https://tryhackme.com/p/adhil.parokkot)
- ✉️ **Email:** [adhilsaju3551@gmail.com](mailto:adhilsaju3551@gmail.com)

<div align="center">
  <sub>Engineered by <strong>Adhil Parokkot</strong> • Built with rigor for enterprise cybersecurity standards.</sub>
</div>
