## Detection Engineering & SOC Portfolio

> Blue Team | Detection Engineering | Incident Response

**Core stack:**

### SIEM & Detection
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![SPL](https://img.shields.io/badge/SPL-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005792?style=for-the-badge&logo=wazuh&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=for-the-badge&logoColor=white)
![Sigma](https://img.shields.io/badge/Sigma-008080?style=for-the-badge&logoColor=white)

### Endpoint & Network
![Sysmon](https://img.shields.io/badge/Sysmon-5391FE?style=for-the-badge&logo=microsoft&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=nmap&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### IR & Frameworks
![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=for-the-badge&logo=servicenow&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=for-the-badge&logoColor=white)

---

## About Me

I'm **William**, a detection engineer and SOC analyst (early-career) focused on **defensive security, detection engineering, and incident response**. This repository documents structured, hands-on work across the Blue Team skill stack: alert triage, log analysis, SIEM investigations, detection authoring, and threat hunting.

Every project here is built to mirror the workflows of a working SOC, not tutorial replays. These are lab environments, and where a project's scope is limited, its README says so. The goal is demonstrable competence: detections I've written, incidents I've walked through end-to-end, and tooling I can speak to in an interview.

**Certifications:** ISC2 Certified in Cybersecurity (CC) | CompTIA Security+ (in progress)

---

## Upstream Contributions

Two detection gaps reported to SigmaHQ, validated against real telemetry from my own lab.

| Issue | Technique | Finding |
|--------|-----------|---------|
| [SigmaHQ #6056](https://github.com/SigmaHQ/sigma/issues/6056) | T1071.001 | False positive Sysmon EID 3 firing on legitimate Azure traffic |
| [SigmaHQ #6057](https://github.com/SigmaHQ/sigma/issues/6057) | T1136.001 | Coverage gap ADSI/WinNT local user creation, Windows 4104 |

Both reported by me. The remediation PR was opened by a community contributor.

---

## Core SOC Projects

The detection, triage, and incident response work most representative of day-to-day SOC and detection engineering operations.

| Project | Focus | Technique |
|--------|-------|-----------|
| [Detection Engineering Labs](https://github.com/WiLL75G/detection-engineering-labs) | Host + network detection, custom rules | T1110, T1046, T1059.001 |
| [Microsoft Sentinel SOC Lab (KQL)](https://github.com/WiLL75G/sentinel-soc-lab-setup) | Cloud SIEM, KQL analytics rules, hunting | T1110, T1059.001 |
| [AI Era Detection Lab](https://github.com/WiLL75G/soc-ai-era-detection-lab) | NHI abuse, prompt injection, MCP attack chains | Multi-technique |
| [SSH Brute Force Detection (Splunk)](https://github.com/WiLL75G/soc-day01-ssh-brute-force-detection) | SIEM detection, log analysis | T1110 |
| [Sigma Detection Lab](https://github.com/WiLL75G/sigma-detection-lab) | Detection-as-code, Sigma rule authoring | Multi-technique |
| [Phishing Email Analysis](https://github.com/WiLL75G/soc-day02-phishing-email-analysis) | Email triage, IOC extraction | T1566 |
| [Splunk SIEM Alerts & Dashboard](https://github.com/WiLL75G/soc-day08-splunk-siem-alerts-dashboard) | Alert engineering, dashboards | T1548.003, T1053.003 |
| [Incident Response Playbooks](https://github.com/WiLL75G/soc-day09-incident-response-playbook) | IR workflow, containment | T1110, T1566, T1204 |
| [Network Traffic Analysis (Wireshark)](https://github.com/WiLL75G/soc-day18-network-traffic-analysis-wireshark-lab) | Packet inspection, C2 detection | T1219, T1071.001 |
| [SOC Shift Simulation Capstone](https://github.com/WiLL75G/soc-day15-soc-shift-simulation) | End-to-end shift, campaign correlation | Full chain |
| [MITRE ATT&CK Detection Coverage](https://github.com/WiLL75G/soc-day10-mitre-attack-mapping) | Detection mapping, gap analysis | — |

---

## Additional Projects

| Project | Focus |
|--------|-------|
| [Network Port Scan Detection (Wireshark)](https://github.com/WiLL75G/soc-day03-port-scan-detection-wireshark) | Recon detection |
| [Windows Event Log Analysis](https://github.com/WiLL75G/soc-day04-windows-event-log-analysis) | Endpoint log triage |
| [Linux Log Analysis & File Integrity](https://github.com/WiLL75G/soc-day05-linux-log-analysis-file-integrity) | Host integrity monitoring |
| [Password Spray Detection](https://github.com/WiLL75G/soc-day06-ad-password-spray-detection) | Identity attack detection |
| [Malware Analysis & Threat Hunting](https://github.com/WiLL75G/soc-day07-malware-analysis-threat-hunting) | Threat hunting |
| [Vulnerability Scanning & Remediation](https://github.com/WiLL75G/soc-day11-vulnerability-scanning-remediation) | Vuln management |
| [Firewall Hardening](https://github.com/WiLL75G/soc-day12-firewall-network-segmentation) | Network defense |
| [PowerShell SOC Toolkit](https://github.com/WiLL75G/soc-day13-powershell-soc-toolkit) | Automation/scripting |
| [Threat Intelligence & OSINT](https://github.com/WiLL75G/soc-day14-threat-intelligence-osint) | Threat intel |
| [AWS Cloud Security Investigation](https://github.com/WiLL75G/aws-detection-engineering) | Cloud detection, CloudTrail |
| [SOC Analyst Toolkit](https://github.com/WiLL75G/soc-analyst-toolkit) | 55 curated tools, 13 sections |
| [Linux Triage Toolkit](https://github.com/WiLL75G/linux-triage-toolkit) | DFIR Bash modules |
| [CorpOps Shell Suite](https://github.com/WiLL75G/CorpOps-Shell-Suite) | Bash automation, Nmap detection, Python OSINT |
| [SOC IOC Tracker](https://github.com/WiLL75G/soc-ioc-tracker) | 36 IOCs across 14 labs |
| [Regex Log Parsing Toolkit](https://github.com/WiLL75G/soc-day21-regex-log-parsing-toolkit) | Log parsing, SPL |
| [Wazuh EDR Lab](https://github.com/WiLL75G/soc-day22-edr-wazuh-endpoint-detection-lab) | EDR/endpoint detection |
| [Digital Forensics Investigation](https://github.com/WiLL75G/soc-24-digital-forensics-investigation-lab) | DFIR |
| [SOC Metrics Dashboard](https://github.com/WiLL75G/soc-26-soc-metrics-dashboard) | SOC reporting |
| [Advanced Splunk Intelligence Platform](https://github.com/WiLL75G/soc-28-advanced-splunk-intelligence-platform) | Advanced SIEM |

---

## Live Portfolio

[will75g.github.io/-portfolio](https://will75g.github.io/-portfolio)

---

## Goal

Build a real-world detection engineering and SOC portfolio through hands-on detection, investigation, and documentation, and land an entry-level Blue Team role.

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-WilliamInCyber-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/WilliamInCyber)
[![X](https://img.shields.io/badge/X-@WilliamInCyber-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/WilliamInCyber)

> Open to networking and collaboration in cybersecurity and Blue Team learning.
