<h1 align="center">Ahtisham Tanveer</h1>

<p align="center">
  <b>Cybersecurity · IT Support · Networking · Network Security</b><br/>
  SOC · DFIR · Digital Forensics · Windows and Linux support<br/>
  Islamabad, Pakistan
</p>

<p align="center">
  <a href="mailto:bcy222002@myu.edu.pk"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/ahtisham-tanveer-0b36b0316/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

---

### About

I am a BS Computer Science (Cybersecurity) graduate with hands-on experience on two sides of IT: **keeping systems and networks running** (Windows and Linux support, Active Directory, DNS/DHCP, firewalls) and **protecting and investigating them** (SOC monitoring, digital forensics, incident response).

I build and break things in my own labs, trace problems through logs, and write down every fix.

**Open to:** Junior SOC / security analyst, DFIR and forensics roles, IT support / helpdesk / desktop support, junior system administrator, and network support or network security roles (internships included).

---

### Featured project: [SentinelFlow](https://github.com/AhtishamTanveer/sentinelflow-wazuh-soar)

A lightweight SOAR pipeline that runs on an 8 GB laptop. Wazuh alerts are grouped, enriched (AbuseIPDB, VirusTotal, a MISP-format feed, asset and identity context), triaged by a local LLM (Ollama), checked by a validation layer, and sent to DFIR-IRIS, with automatic Velociraptor evidence collection for serious alerts.

- With the validation layer on, none of the 8 real attacks in a 24-alert synthetic test set was dismissed (one was without it).
- The small model obeyed a prompt injection hidden in a user name, so I added detection and a structural safeguard; in a worst-case test, 0 of 10 simulated attacks were closed.
- 23 automated tests, a demo video, and an honest list of limitations in the README.

`Wazuh` · `Python / FastAPI` · `Ollama` · `DFIR-IRIS` · `Velociraptor` · `VirusTotal` · `AbuseIPDB` · `MITRE ATT&CK`

---

### Featured lab: office IT and network environment

An office-style environment built in VirtualBox, used to practise the daily work of IT support and network administration, and to see how it looks from the security side.

- **Systems:** Windows Server with Active Directory (user management, access control, Group Policy), Windows and Linux endpoints, PowerShell and bash scripting, backups and patching.
- **Network:** DNS and DHCP, VLANs, subnetting, routing and switching exercises.
- **Network security:** pfSense firewall rules, tested from a Kali Linux client; Wireshark traffic analysis.
- **Monitoring:** Wazuh and Splunk for centralized logging and alerts. I diagnosed and fixed simulated outages, misconfigured services and access problems, and documented each fix.

`Windows Server` · `Active Directory` · `pfSense` · `Group Policy` · `DNS/DHCP` · `Wireshark` · `Wazuh` · `Splunk`

---

### Skills

| Area | Tools and topics |
|---|---|
| IT support and helpdesk | Windows 10 and 11 troubleshooting and setup, software installation, printer and antivirus support, hardware and peripheral support, user account and password management, remote support (RDP, VPN), Microsoft 365 (Outlook, Teams), technical documentation |
| Systems administration | Windows Server, Active Directory, Group Policy, Linux, VirtualBox, backup and patching, user management and access control |
| Networking | TCP/IP, DNS, DHCP, LAN/WAN, VLANs, subnetting, routing and switching |
| Network security | pfSense firewall, firewall rule testing, Wireshark, Nmap |
| SOC and DFIR | Wazuh, Splunk, DFIR-IRIS, Velociraptor, alert triage, IOC identification, threat hunting, incident response |
| Digital forensics | Autopsy, FTK Imager, Volatility, EnCase, evidence handling, chain of custody, forensic reporting |
| Security testing | Burp Suite, Metasploit, Kali Linux |
| Scripting | Python, PowerShell, Bash |

---

### Experience

**Intern (Cybercrime Investigation and IT Operations), National Cyber Crime Investigation Agency (NCCIA)**, Aug 2024 to Oct 2024
- Supported investigators on cybercrime cases, with evidence documentation and forensic imaging.
- Handled workstation setup, hardware handling and digital record-keeping in a government IT environment.
- Followed chain-of-custody, data-handling and compliance procedures.

**Threat Hunting Intelligence & Research Intern (Remote), Thincs-Corp, Dubai**, 2024 (8 weeks)
- Ran threat hunting exercises to look for suspicious network behaviour using intelligence-driven methods.
- Analyzed threat intelligence feeds and produced IOC reports; researched attacker techniques and TTPs.

**Cybersecurity Intern, Security Experts Pvt. Ltd.**, Aug 2024 to Sep 2024

**Volunteer Management Intern, Al-Khidmat Foundation**, Jul 2026 to Sep 2026
- Managed volunteer registration records and databases with Microsoft Office and prepared reports.

---

### Training

**Cybercrime Investigation Training, ICDFA, Nigeria**, Aug 2025 to Feb 2026 (Certified Cybersecurity Specialist, Mastery with Distinction)
- Six months of advanced training: digital evidence acquisition, chain of custody, memory forensics, malware analysis, and court-admissible forensic reporting.
- Produced 8 forensic investigation reports covering memory, browser, malware, mobile, network and financial cybercrime: [Advance_Cybercrime_Investigations_Projects](https://github.com/AhtishamTanveer/Advance_Cybercrime_Investigations_Projects)

**Cyber Security (CEH) Certificate Course, NAVTTC (PMYSDP Batch III), Grade A**, Feb to May 2026

---

### Education

**B.S. Computer Science (Cybersecurity)**, Muslim Youth University, Islamabad, 2022 to Aug 2026
Relevant coursework: Computer Networks, Operating Systems, Database Systems, Information Security, Digital Forensics, Python, C++

---

### Certifications

| Certification | Issuer |
|---|---|
| Certified Cybersecurity Specialist | ICDFA |
| Certified Ethical Hacker (CEH) | EC-Council |
| SOC Analyst | Let's Defend |
| ISO 27001 Information Security Auditor | Mastermind |
| Google Cybersecurity Professional Certificate | Google / Coursera |
| Security Operations Center (SOC) in Practice | IBM |
| One-Year Computer Diploma | |

---

### Goals

- Start in IT support, networking or a SOC and grow into network security, incident response and threat intelligence.
- Keep building open, well-documented tools and measure how well they work.

---

### Disclaimer

Everything here is for educational and demonstration purposes. Attacks are run only in my own lab, and no confidential or real investigation data is shared.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00264D,100:0078D4&height=100&section=footer"/>
</p>
