
## SOC Investigations | Detection Engineering Labs

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

I focus on Security Operations, incident investigation, and detection validation through independent cybersecurity labs and documented technical projects.

My work includes SIEM investigations, endpoint and network telemetry analysis, detection development, and evidence-based incident documentation using Splunk, Microsoft Sentinel, Wazuh, Sysmon, and related security tools.

I document what I investigated, the evidence examined, the decisions made, and the limitations of each finding.

My primary career target is SOC Analyst Tier 1, with continued development toward Tier 2 investigations and Detection Engineering.

These are independent lab projects and simulations, not claims of professional SOC employment.

**Certification:** ISC2 Certified in Cybersecurity (CC)  
**Current studies:** CompTIA Security+

---

## Upstream Contributions

Two detection gaps reported to SigmaHQ, validated against real telemetry from my own lab.

| Issue | Technique | Finding |
|--------|-----------|---------|
| [SigmaHQ #6056](https://github.com/SigmaHQ/sigma/issues/6056) | T1071.001 | False positive - Sysmon EID 3 firing on legitimate Azure traffic |
| [SigmaHQ #6057](https://github.com/SigmaHQ/sigma/issues/6057) | T1136.001 | Coverage gap - ADSI/WinNT local user creation, Windows 4104 |

Both reported by me. The remediation PR was opened by a community contributor.

---

## Featured Projects

The detection, triage, and incident response work most representative of day-to-day SOC and detection engineering operations.

<table>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/DETECTIONLABS-333333?style=flat-square)![](https://img.shields.io/badge/DETECTION_ENG-8CE196?style=flat-square)

**[Detection Engineering Labs](https://github.com/WiLL75G/detection-engineering-labs)**

Host + network detection with custom Wazuh, Suricata & PowerShell rules

`T1110` `T1046` `T1059.001`

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/SENTINELLAB-333333?style=flat-square)![](https://img.shields.io/badge/CLOUD_SIEM-7EE8E8?style=flat-square)

**[Microsoft Sentinel SOC Lab](https://github.com/WiLL75G/sentinel-soc-lab-setup)**

Cloud SIEM with KQL analytics rules & threat hunting

`T1110` `T1059.001`

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/AIERALAB-333333?style=flat-square)![](https://img.shields.io/badge/AI_THREATS-E5B93C?style=flat-square)

**[AI Era Detection Lab](https://github.com/WiLL75G/soc-ai-era-detection-lab)**

NHI abuse, prompt injection & MCP attack chain detection

`Multi-technique`

</td>
</tr>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/SSHBRUTE-333333?style=flat-square)![](https://img.shields.io/badge/SPLUNK-EF4444?style=flat-square)

**[SSH Brute Force Detection](https://github.com/WiLL75G/soc-day01-ssh-brute-force-detection)**

Splunk SIEM detection & log analysis for credential attacks

`T1110`

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/SIGMALAB-333333?style=flat-square)![](https://img.shields.io/badge/DETECTION_AS_CODE-8CE196?style=flat-square)

**[Sigma Detection Lab](https://github.com/WiLL75G/sigma-detection-lab)**

Detection-as-code & portable Sigma rule authoring

`Multi-technique`

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/PHISHTRIAGE-333333?style=flat-square)![](https://img.shields.io/badge/EMAIL_TRIAGE-7EE8E8?style=flat-square)

**[Phishing Email Analysis](https://github.com/WiLL75G/soc-day02-phishing-email-analysis)**

Email triage & IOC extraction workflow

`T1566`

</td>
</tr>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/SPLALERTS-333333?style=flat-square)![](https://img.shields.io/badge/DASHBOARD-E5B93C?style=flat-square)

**[Splunk SIEM Alerts & Dashboard](https://github.com/WiLL75G/soc-day08-splunk-siem-alerts-dashboard)**

Alert engineering & real-time SOC dashboards

`T1548.003` `T1053.003`

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/IRPLAYBOOK-333333?style=flat-square)![](https://img.shields.io/badge/INCIDENT_RESPONSE-EF4444?style=flat-square)

**[Incident Response Playbooks](https://github.com/WiLL75G/soc-day09-incident-response-playbook)**

IR workflow & containment procedures

`T1110` `T1566` `T1204`

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/PCAPLAB-333333?style=flat-square)![](https://img.shields.io/badge/WIRESHARK-7EE8E8?style=flat-square)

**[Network Traffic Analysis](https://github.com/WiLL75G/soc-day18-network-traffic-analysis-wireshark-lab)**

Packet inspection & C2 detection with Wireshark

`T1219` `T1071.001`

</td>
</tr>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/SHIFTSIM-333333?style=flat-square)![](https://img.shields.io/badge/CAPSTONE-8CE196?style=flat-square)

**[SOC Shift Simulation Capstone](https://github.com/WiLL75G/soc-day15-soc-shift-simulation)**

End-to-end shift with campaign correlation

`Full chain`

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/ATTACKMAP-333333?style=flat-square)![](https://img.shields.io/badge/MITRE_MAPPING-E5B93C?style=flat-square)

**[MITRE ATT&CK Detection Coverage](https://github.com/WiLL75G/soc-day10-mitre-attack-mapping)**

Detection mapping & coverage gap analysis

`Coverage`

</td>
<td width="33%" valign="top"></td>
</tr>
</table>

---

## Additional Projects

<table>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/PORTSCAN-333333?style=flat-square)![](https://img.shields.io/badge/RECON_DETECT-7EE8E8?style=flat-square)

**[Network Port Scan Detection](https://github.com/WiLL75G/soc-day03-port-scan-detection-wireshark)**

Recon detection with Wireshark

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/WINEVENTS-333333?style=flat-square)![](https://img.shields.io/badge/LOG_TRIAGE-8CE196?style=flat-square)

**[Windows Event Log Analysis](https://github.com/WiLL75G/soc-day04-windows-event-log-analysis)**

Endpoint log triage

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/LINUXFIM-333333?style=flat-square)![](https://img.shields.io/badge/INTEGRITY-E5B93C?style=flat-square)

**[Linux Log Analysis & File Integrity](https://github.com/WiLL75G/soc-day05-linux-log-analysis-file-integrity)**

Host integrity monitoring

</td>
</tr>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/PWSPRAY-333333?style=flat-square)![](https://img.shields.io/badge/IDENTITY-EF4444?style=flat-square)

**[Password Spray Detection](https://github.com/WiLL75G/soc-day06-password-spray-detection)**

Identity attack detection

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/MALHUNT-333333?style=flat-square)![](https://img.shields.io/badge/THREAT_HUNT-7EE8E8?style=flat-square)

**[Malware Analysis & Threat Hunting](https://github.com/WiLL75G/soc-day07-malware-analysis-threat-hunting)**

Threat hunting

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/VULNSCAN-333333?style=flat-square)![](https://img.shields.io/badge/VULN_MGMT-E5B93C?style=flat-square)

**[Vulnerability Scanning & Remediation](https://github.com/WiLL75G/soc-day11-vulnerability-scanning-remediation)**

Vuln management

</td>
</tr>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/FWHARDEN-333333?style=flat-square)![](https://img.shields.io/badge/NET_DEFENSE-8CE196?style=flat-square)

**[Firewall Hardening](https://github.com/WiLL75G/soc-day12-firewall-hardening)**

Network defense

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/PSTOOLKIT-333333?style=flat-square)![](https://img.shields.io/badge/AUTOMATION-7EE8E8?style=flat-square)

**[PowerShell SOC Toolkit](https://github.com/WiLL75G/soc-day13-powershell-soc-toolkit)**

Automation & scripting

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/THREATINTEL-333333?style=flat-square)![](https://img.shields.io/badge/OSINT-E5B93C?style=flat-square)

**[Threat Intelligence & OSINT](https://github.com/WiLL75G/soc-day14-threat-intelligence-osint)**

Threat intel

</td>
</tr>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/AWSCLOUD-333333?style=flat-square)![](https://img.shields.io/badge/CLOUDTRAIL-EF4444?style=flat-square)

**[AWS Cloud Security Investigation](https://github.com/WiLL75G/aws-detection-engineering)**

Cloud detection with CloudTrail

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/SOCTOOLKIT-333333?style=flat-square)![](https://img.shields.io/badge/55_TOOLS-8CE196?style=flat-square)

**[SOC Analyst Toolkit](https://github.com/WiLL75G/soc-analyst-toolkit)**

55 curated tools across 13 sections

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/TRIAGEKIT-333333?style=flat-square)![](https://img.shields.io/badge/DFIR_BASH-7EE8E8?style=flat-square)

**[Linux Triage Toolkit](https://github.com/WiLL75G/linux-triage-toolkit)**

DFIR Bash modules

</td>
</tr>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/CORPOPS-333333?style=flat-square)![](https://img.shields.io/badge/SHELL_SUITE-E5B93C?style=flat-square)

**[CorpOps Shell Suite](https://github.com/WiLL75G/CorpOps-Shell-Suite)**

Bash automation, Nmap detection & Python OSINT

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/IOCTRACK-333333?style=flat-square)![](https://img.shields.io/badge/36_IOCS-EF4444?style=flat-square)

**[SOC IOC Tracker](https://github.com/WiLL75G/soc-ioc-tracker)**

36 IOCs across 14 labs

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/REGEXKIT-333333?style=flat-square)![](https://img.shields.io/badge/LOG_PARSING-8CE196?style=flat-square)

**[Regex Log Parsing Toolkit](https://github.com/WiLL75G/soc-day21-regex-log-parsing-toolkit)**

Log parsing & SPL

</td>
</tr>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/WAZUHEDR-333333?style=flat-square)![](https://img.shields.io/badge/EDR-7EE8E8?style=flat-square)

**[Wazuh EDR Lab](https://github.com/WiLL75G/soc-day22-edr-wazuh-endpoint-detection-lab)**

EDR & endpoint detection

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/FORENSICS-333333?style=flat-square)![](https://img.shields.io/badge/DFIR-E5B93C?style=flat-square)

**[Digital Forensics Investigation](https://github.com/WiLL75G/soc-24-digital-forensics-investigation-lab)**

Digital forensics & incident response

</td>
<td width="33%" valign="top">

![](https://img.shields.io/badge/SOCMETRICS-333333?style=flat-square)![](https://img.shields.io/badge/REPORTING-8CE196?style=flat-square)

**[SOC Metrics Dashboard](https://github.com/WiLL75G/soc-26-soc-metrics-dashboard)**

SOC reporting

</td>
</tr>
<tr>
<td width="33%" valign="top">

![](https://img.shields.io/badge/ADVSPLUNK-333333?style=flat-square)![](https://img.shields.io/badge/ADVANCED_SIEM-EF4444?style=flat-square)

**[Advanced Splunk Intelligence Platform](https://github.com/WiLL75G/soc-28-advanced-splunk-intelligence-platform)**

Advanced SIEM

</td>
<td width="33%" valign="top"></td>
<td width="33%" valign="top"></td>
</tr>
</table>

---

## Career Goal

Apply my documented independent SOC investigation and detection development work to an entry-level Security Operations role, while continuing to build deeper investigation and detection engineering capabilities.

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-WilliamInCyber-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/WilliamInCyber)
[![X](https://img.shields.io/badge/X-@WilliamInCyber-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/WilliamInCyber)
[![Medium](https://img.shields.io/badge/Medium-WilliamInCyber-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@WilliamInCyber)

> Open to networking and collaboration in cybersecurity and Blue Team learning.

