# Detection Engineering and SOC Portfolio

Blue team. Detection engineering. Incident response.

## Core Stack

### SIEM and Detection

![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![SPL](https://img.shields.io/badge/SPL-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005792?style=for-the-badge&logo=wazuh&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=for-the-badge&logoColor=white)
![Sigma](https://img.shields.io/badge/Sigma-008080?style=for-the-badge&logoColor=white)

### Endpoint and Network

![Sysmon](https://img.shields.io/badge/Sysmon-5391FE?style=for-the-badge&logo=microsoft&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=nmap&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### IR and Frameworks

![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=for-the-badge&logo=servicenow&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=for-the-badge&logoColor=white)

---

## About

I'm William, an early career detection engineer focused on defensive security, detection authoring, and incident response.

Everything here is hands on work: rules I wrote, alerts I triaged to a verdict, investigations I closed on evidence, and the negative findings I documented when nothing was there. Labs, not production. Where a project's scope is limited, its README says so.

Certifications: ISC2 Certified in Cybersecurity | CompTIA Security+ in progress

---

## Upstream Contributions

Two detection gaps reported to SigmaHQ, validated against real telemetry from my own lab.

| Issue | Technique | Finding |
|---|---|---|
| [SigmaHQ #6056](https://github.com/SigmaHQ/sigma/issues/6056) | T1071.001 | False positive, Sysmon EID 3 firing on legitimate Azure traffic |
| [SigmaHQ #6057](https://github.com/SigmaHQ/sigma/issues/6057) | T1136.001 | Coverage gap, ADSI and WinNT local user creation missed, Windows 4104 |

Both reported by me. The remediation PR was opened by a community contributor.

---

## Flagship Projects

The work most representative of detection engineering and day to day SOC operations.

| Project | What It Shows | Techniques |
|---|---|---|
| [Detection Engineering Labs](https://github.com/WiLL75G/detection-engineering-labs) | Four lab set. Same SSH brute force caught host side by Wazuh and network side by Suricata. Custom rules written from scratch, both fired on live Kali attacks. Plus ServiceNow incident lifecycle and Windows endpoint forensics | T1110, T1046, T1059.001 |
| [Microsoft Sentinel SOC Lab](https://github.com/WiLL75G/sentinel-soc-lab-setup) | Full cloud SIEM build. Arc to AMA to DCR ingestion, KQL hunts. 88 failed logins and 8 successes traced to one source | T1110, T1059.001 |
| [AI Era Detection Lab](https://github.com/WiLL75G/soc-ai-era-detection-lab) | NHI abuse, prompt injection, and MCP attack chains correlated into one kill chain. 1,877 records exfiltrated via a single IOC | Multi technique |
| [Splunk SIEM Alerts and Dashboard](https://github.com/WiLL75G/soc-day08-splunk-siem-alerts-dashboard) | Four real time alerts and a four panel dashboard on live endpoint telemetry. Includes an honest assessment of why the rules are untuned | T1548.003, T1053.003, T1078.003 |
| [SOC Shift Simulation Capstone](https://github.com/WiLL75G/soc-day15-soc-shift-simulation) | Three alerts eight hours apart, correlated to one campaign on a shared IP and a shared host. Full kill chain, IOC table, IR handoff | Full chain |
| [Network Traffic Analysis](https://github.com/WiLL75G/soc-day18-network-traffic-analysis-wireshark-lab) | NetSupport RAT C2 in 15,512 packets. Beaconing confirmed, infected host identified by hostname and MAC via DHCP | T1219, T1071.001, T1571 |
| [MITRE ATT&CK Coverage Assessment](https://github.com/WiLL75G/soc-day10-mitre-attack-mapping) | Audited my own detections against the matrix. Found coverage sits at the front of the kill chain and nothing watches exfiltration | Gap analysis |
| [Incident Response Playbooks](https://github.com/WiLL75G/soc-day09-incident-response-playbook) | Three NIST 800-61 playbooks with the step analysts skip under pressure named in each | T1110, T1566, T1204 |

---

## Detection and Investigation

| Project | Focus |
|---|---|
| [SSH Brute Force Detection, Splunk](https://github.com/WiLL75G/soc-day01-ssh-brute-force-detection) | SPL field extraction, threshold logic, and the negative finding that closed it |
| [Sigma Detection Lab](https://github.com/WiLL75G/sigma-detection-lab) | Detection as code, Sigma rule authoring |
| [Wazuh EDR Lab](https://github.com/WiLL75G/soc-day22-edr-wazuh-endpoint-detection-lab) | Endpoint detection and response |
| [Password Spray Detection](https://github.com/WiLL75G/soc-day06-ad-password-spray-detection) | Correlating 4625 across accounts, not within one |
| [Windows Event Log Analysis](https://github.com/WiLL75G/soc-day04-windows-event-log-analysis) | Reading the sequence, not the event |
| [Linux Log Analysis and File Integrity](https://github.com/WiLL75G/soc-day05-linux-log-analysis-file-integrity) | auth.log, process state, /etc integrity |
| [Port Scan Detection, Wireshark](https://github.com/WiLL75G/soc-day03-port-scan-detection-wireshark) | TCP flags, open versus closed at packet level |
| [Phishing Email Analysis](https://github.com/WiLL75G/soc-day02-phishing-email-analysis) | Header forensics, IOC extraction |
| [Malware Triage and Threat Hunt](https://github.com/WiLL75G/soc-day07-malware-analysis-threat-hunting) | Static only, host hunted clean and documented |
| [Threat Intelligence and OSINT](https://github.com/WiLL75G/soc-day14-threat-intelligence-osint) | Three IOCs across four platforms, correlated to one campaign |
| [Digital Forensics Investigation](https://github.com/WiLL75G/soc-24-digital-forensics-investigation-lab) | DFIR workflow |
| [AWS Cloud Security Investigation](https://github.com/WiLL75G/aws-detection-engineering) | CloudTrail JSON, service role versus human identity |

---

## Tooling and Automation

| Project | Focus |
|---|---|
| [SOC Analyst Toolkit](https://github.com/WiLL75G/soc-analyst-toolkit) | 55 curated tools across 13 sections |
| [Linux Triage Toolkit](https://github.com/WiLL75G/linux-triage-toolkit) | DFIR Bash modules |
| [PowerShell SOC Toolkit](https://github.com/WiLL75G/soc-day13-powershell-soc-toolkit) | Six module endpoint triage, cross platform |
| [CorpOps Shell Suite](https://github.com/WiLL75G/CorpOps-Shell-Suite) | Seven Bash projects, Nmap detection, Python OSINT |
| [Regex Log Parsing Toolkit](https://github.com/WiLL75G/soc-day21-regex-log-parsing-toolkit) | Log parsing, SPL |
| [SOC IOC Tracker](https://github.com/WiLL75G/soc-ioc-tracker) | 36 IOCs across 14 labs |

---

## Hardening and Reporting

| Project | Focus |
|---|---|
| [Firewall Hardening](https://github.com/WiLL75G/soc-day12-firewall-network-segmentation) | Default deny, and the rule that looked right and did nothing |
| [Vulnerability Scanning and Remediation](https://github.com/WiLL75G/soc-day11-vulnerability-scanning-remediation) | Greenbone scan to prioritised remediation |
| [SOC Metrics Dashboard](https://github.com/WiLL75G/soc-26-soc-metrics-dashboard) | SOC reporting |
| [Advanced Splunk Intelligence Platform](https://github.com/WiLL75G/soc-28-advanced-splunk-intelligence-platform) | Advanced SIEM |
| [28 Day SOC Foundation](https://github.com/WiLL75G/soc-day01-ssh-brute-force-detection) | The first full build. Splunk ingest, SPL, dashboards, Wireshark, Nmap |

---

## Live Portfolio

[will75g.github.io/-portfolio](https://will75g.github.io/-portfolio)

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gokah%20William-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/gokahwilliam)
[![X](https://img.shields.io/badge/X-@WilliamInCyber-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/WilliamInCyber)
