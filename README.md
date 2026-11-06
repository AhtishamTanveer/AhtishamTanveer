<h1 align="center">Ahtisham Tanveer</h1>

<p align="center">
  <b>Cybersecurity graduate | SOC · DFIR · Digital Forensics</b><br/>
  Islamabad, Pakistan
</p>

<p align="center">
  <a href="mailto:bcy222002@myu.edu.pk"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/ahtisham-tanveer-0b36b0316/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

---

### About

I am a BS Computer Science (Cybersecurity) graduate who likes working out what happened in an incident and building tools that make that faster. I trained in digital forensics and cybercrime investigation at ICDFA (Nigeria), interned at NCCIA, and run home labs where I simulate attacks and tune detections with Wazuh and Splunk.

My latest project asks how far a small, fully local LLM can go in SOC triage when its answers are checked by code.

---

### Featured project: [SentinelFlow](https://github.com/AhtishamTanveer/sentinelflow-wazuh-soar)

A lightweight SOAR pipeline that runs on an 8 GB laptop. Wazuh alerts are grouped, enriched (AbuseIPDB, VirusTotal, a MISP-format feed, asset and identity context), triaged by a local LLM (Ollama), checked by a validation layer, and sent to DFIR-IRIS, with automatic Velociraptor evidence collection for serious alerts.

- With the validation layer on, none of the 8 real attacks in a 24-alert synthetic test set was dismissed (one was without it).
- The small model obeyed a prompt injection hidden in a user name, so I added detection and a structural safeguard; in a worst-case test, 0 of 10 simulated attacks were closed.
- 23 automated tests, a demo video, and an honest list of limitations in the README.

`Wazuh` · `Python / FastAPI` · `Ollama` · `DFIR-IRIS` · `Velociraptor` · `VirusTotal` · `AbuseIPDB` · `MITRE ATT&CK`

---

### Skills

| Area | Tools and topics |
|---|---|
| Digital forensics | Autopsy, FTK Imager, Volatility, EnCase, evidence handling, chain of custody, forensic reporting |
| SOC and DFIR | Wazuh, Splunk, DFIR-IRIS, Velociraptor, alert triage, IOC identification, threat hunting, incident response |
| Security tools | Wireshark, Nmap, Burp Suite, Metasploit |
| Systems and networking | Windows Server (Active Directory), Linux, pfSense, TCP/IP, DNS, DHCP, VirtualBox |
| Languages | Python, Bash, PowerShell |

---

### Experience

**Cybercrime Investigation Intern, National Cyber Crime Investigation Agency (NCCIA)**, Aug 2024 to Oct 2024
- Supported investigators on cybercrime cases, with evidence documentation and forensic imaging.
- Gained exposure to national cybercrime investigation workflows, legal frameworks and chain-of-custody standards.

**Threat Hunting Intelligence & Research Intern (Remote), Thincs-Corp, Dubai**, 2024 (8 weeks)
- Ran threat hunting exercises to look for suspicious network behaviour using intelligence-driven methods.
- Analyzed threat intelligence feeds and produced IOC reports; researched attacker techniques and TTPs.

**Cybersecurity Intern, Security Experts Pvt. Ltd.**, Aug 2024 to Sep 2024

---

### Training

**Cybercrime Investigation Training, ICDFA, Nigeria**, Aug 2025 to Feb 2026 (Certified Cybersecurity Specialist, Mastery with Distinction)
- Six months of advanced training: digital evidence acquisition, chain of custody, memory forensics, malware analysis, and court-admissible forensic reporting.
- Produced 8 forensic investigation reports covering memory, browser, malware, mobile, network and financial cybercrime: [Advance_Cybercrime_Investigations_Projects](https://github.com/AhtishamTanveer/Advance_Cybercrime_Investigations_Projects)

---

### More projects

- **Home lab: SOC and forensics environment** (VirtualBox, Kali Linux, Windows, Wazuh, Splunk). Simulated attacks from Kali, watched the alerts they produced, and tuned detection rules.
- **Home lab: office IT and network environment** (Windows Server with Active Directory, Linux endpoints, pfSense). DNS/DHCP, firewall rules, centralized logging with Wazuh and Splunk, and documented fixes for simulated problems.

---

### Education

**B.S. Computer Science (Cybersecurity)**, Muslim Youth University, Islamabad, 2022 to Aug 2026

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

---

### Goals

- Work in a SOC or DFIR team and grow into threat intelligence and incident response.
- Keep building open, well-documented security tooling and measure how well it works.

---

### Disclaimer

Everything here is for educational and demonstration purposes. Attacks are run only in my own lab, and no confidential or real investigation data is shared.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00264D,100:0078D4&height=100&section=footer"/>
</p>
