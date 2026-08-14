<h1 align="center">Hi, I'm Shaho Ahmed 👋</h1>
<p align="center"><b>SOC Analyst &amp; Detection Engineer</b> · Threat Hunting · Detection Engineering · Cloud Security</p>

<p align="center">
<a href="https://www.linkedin.com/in/shaho-ahmed"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:shahoaumed@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
Cybersecurity Engineering graduate with a non-traditional path into the field. I build hands-on detection labs that simulate real adversary behavior, engineer the detections to catch it, and document the whole thing like a working SOC. I bring an entrepreneur's discipline and a detection engineer's precision to everything I do.
</p>

---

## 🧭 About me

My road to cybersecurity hasn't been a straight line, and that's my edge. I immigrated to the U.S. from Iraq and restarted my education from where I left off, an early lesson in resilience. To put myself through college I built an online health and fitness coaching business that grew to nearly 200K followers across TikTok and Instagram, then founded a private transportation company in the DC area now running contracts with law firms, NGOs, and political offices behind a team of 8 full-time drivers.

Running those businesses taught me how to think under pressure, manage people, and allocate time and resources when it actually matters. Cybersecurity is where my heart has always been, and I'm bringing that same drive and problem-solving mindset into **threat detection, threat hunting, and cloud security.**

- 🔭 Currently building an **APT29 (SolarWinds actor) adversary-emulation and detection-engineering capstone** in Splunk
- 🌱 Focused on **blue team** security: **SOC Analyst / Detection Engineer** roles
- 💬 Always happy to connect with other people who love this work — reach out on [LinkedIn](https://www.linkedin.com/in/shaho-ahmed)

---

## 🛠️ Skills &amp; Tools

**SIEM &amp; Detection**
<p>
<img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" />
<img src="https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Elastic%20Stack-005571?style=for-the-badge&logo=elastic&logoColor=white" />
<img src="https://img.shields.io/badge/KQL-3776AB?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/SPL-65A637?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Sigma-1E90FF?style=for-the-badge&logoColor=white" />
</p>

**EDR, Endpoint &amp; Threat Detection**
<p>
<img src="https://img.shields.io/badge/LimaCharlie-2E2E2E?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Sysmon-0078D4?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/MITRE%20ATT%26CK-C0392B?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/VirusTotal-394EFF?style=for-the-badge&logo=virustotal&logoColor=white" />
</p>

**Adversary Emulation &amp; Offensive**
<p>
<img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" />
<img src="https://img.shields.io/badge/Atomic%20Red%20Team-D22128?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Impacket-4B275F?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Sliver%20C2-1E1E1E?style=for-the-badge&logoColor=white" />
</p>

**Cloud &amp; DevSecOps**
<p>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=trivy&logoColor=white" />
</p>

**Programming &amp; Scripting**
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
</p>

**Frameworks &amp; Compliance**
<p>
<img src="https://img.shields.io/badge/NIST%20800--171-005EA2?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/DFARS-1B1B1B?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/MITRE%20ATT%26CK-C0392B?style=for-the-badge&logoColor=white" />
</p>

---

## 🚀 Projects

### 🛰️ Threat Hunting Report — Microsoft Sentinel
Proactive, hypothesis-driven threat hunting in Microsoft Sentinel. Three hunts mapped to MITRE ATT&CK, two Sigma rules, and a live analytics rule that fires a real incident. The centerpiece is a cloud identity account-takeover hunt modeled on the technique behind the 2023 MGM and Caesars breaches.
`Sentinel` `KQL` `Sigma` `MITRE ATT&CK` `Detection-as-Code`
🔗 [**View repository →**](https://github.com/shahoahmed/threat-hunting-report)

### 🧠 AD Identity Attack Detection Lab
AI-augmented detection lab across the full identity kill chain: simulate the attack, ingest telemetry, write the detection, score the alert with machine learning, and triage it with a local LLM. Detects Kerberoasting, DCSync, Pass-the-Hash, and LSASS dumping.
`Elastic` `Sysmon` `Atomic Red Team` `Isolation Forest` `Llama 3.2`
🔗 [**View repository →**](https://github.com/shahoahmed/ad-identity-attack-detection-lab)

### 🛡️ SOC Detection &amp; Response Lab
End-to-end SOC detection and incident response against a live credential-theft attack. Disable defenses, run a Sliver C2 implant, dump LSASS, then detect and triage it entirely through EDR telemetry.
`LimaCharlie EDR` `Sliver C2` `Incident Response` `VirusTotal`
🔗 [**View repository →**](https://github.com/shahoahmed/soc-detection-lab)

### 📦 Container Security Pipeline
CI/CD pipeline that scans container images with Trivy, automatically maps every finding to the NIST 800-171 control it violates, and blocks the build over a risk threshold. A base-image fix cut build-blocking findings by 72%.
`Docker` `GitHub Actions` `Trivy` `Terraform` `NIST 800-171`
🔗 [**View repository →**](https://github.com/shahoahmed/container-security-pipeline)

### 🌐 Pi-hole Network DNS Lab
Self-hosted network-wide DNS filtering on DietPi and VirtualBox, plus the insight that the query log is a passive DNS threat-hunting source you can cross-reference against IOC feeds.
`Pi-hole` `DNS` `DietPi` `Threat Hunting`
🔗 [**View repository →**](https://github.com/shahoahmed/pihole-network-dns-lab)

### 🚧 APT29 Detection Engineering Capstone *(in progress)*
Emulating APT29 (the SolarWinds actor) end to end in Splunk, then engineering and CI-testing the detections to catch it, with automated response, threat-intel enrichment, and a full incident response report.
`Splunk` `SPL` `Adversary Emulation` `SOAR` `Detection-as-Code`
🔗 *Repository coming soon*

---

## 🎓 Education

**B.S. in Cybersecurity Engineering** — George Mason University · December 2024

---

## 📜 Certifications

<p>
<img src="https://img.shields.io/badge/CompTIA%20Security%2B-E4002B?style=for-the-badge&logo=comptia&logoColor=white" />
<img src="https://img.shields.io/badge/CompTIA%20Network%2B-E4002B?style=for-the-badge&logo=comptia&logoColor=white" />
</p>
<p>
<img src="https://img.shields.io/badge/Oracle%20Cloud%20Infrastructure%20Multicloud%20Architect-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/Oracle%20Generative%20AI%20Professional-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/Oracle%20Autonomous%20Database%20Cloud%20Professional-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
</p>

---

## 🌍 Languages

- 🇺🇸 **English** — Fluent
- 🟩 **Kurdish** — Fluent
- 🟢 **Arabic** — Fluent

<!-- Optional GitHub stats (uncomment to use):
<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=shahoahmed&show_icons=true&theme=tokyonight" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shahoahmed&layout=compact&theme=tokyonight" height="165" />
</p>
-->
