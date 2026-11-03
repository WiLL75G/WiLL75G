
# SOC Investigations | Detection Engineering Labs

**Security Operations | Incident Investigation | Detection Validation**

Independent cybersecurity labs focused on investigating suspicious activity, analyzing security telemetry, developing detections, and documenting evidence-based findings.

---

## About Me

I focus on Security Operations, incident investigation, and detection validation through independent cybersecurity labs and documented technical projects.

My work includes SIEM investigations, endpoint and network telemetry analysis, detection development, and technical incident documentation.

I have worked with Splunk, Microsoft Sentinel, Wazuh, Windows Security Logs, Sysmon, PowerShell, Suricata, and Wireshark across controlled security investigation scenarios.

My investigation approach focuses on understanding the baseline, examining relevant events, correlating activity, identifying evidence gaps, and reaching defensible conclusions.

I distinguish between detection logic that has been written, tested, and validated against observed telemetry.

My portfolio documents the investigations performed, evidence examined, findings reached, and limitations identified.

**Career Focus:** SOC Analyst Tier 1, with continued development toward Tier 2 investigations and Detection Engineering.

**Experience Context:** Independent cybersecurity home labs and simulated security operations, not production SOC employment.

**Certification:** ISC2 Certified in Cybersecurity (CC)

**Current Studies:** CompTIA Security+

---

## Core Technical Areas

| Area | Tools and Technologies |
|---|---|
| SIEM & Log Analysis | Splunk, SPL, Microsoft Sentinel, KQL, Wazuh |
| Endpoint & Identity | Windows Security Logs, Sysmon, PowerShell, Active Directory |
| Network Security | Wireshark, Suricata, Zeek, TCP/IP, DNS |
| Detection Development | Sigma, SIEM Detection Rules, MITRE ATT&CK |
| Incident Investigation | Alert Triage, Event Correlation, Technical Documentation |
| Scripting | PowerShell, Python, Bash |

---

## Upstream Detection Contributions

Reported two detection findings to the SigmaHQ community, based on observations from my independent lab telemetry.

| Contribution | MITRE ATT&CK | Finding |
|---|---|---|
| [SigmaHQ Issue #6056](https://github.com/SigmaHQ/sigma/issues/6056) | T1071.001 | False positive involving Sysmon Event ID 3 and legitimate Azure network traffic |
| [SigmaHQ Issue #6057](https://github.com/SigmaHQ/sigma/issues/6057) | T1136.001 | Detection coverage gap involving ADSI/WinNT local user creation and PowerShell Event ID 4104 |

These issues document the findings I reported. A community contributor opened the remediation pull request.

---

## Selected SOC & Detection Projects

A selection of independent security investigations, SIEM detection work, and simulated SOC operations from my technical portfolio.

### 01 | SSH Brute Force Detection with Splunk

**Focus:** Security Monitoring & Alert Investigation

Investigated SSH authentication activity in a controlled Linux lab using Splunk.

- Analyzed repeated authentication failures.
- Developed SPL searches to identify source activity.
- Examined subsequent authentication events.
- Distinguished observed password guessing from confirmed successful access.
- Documented investigation findings and evidence limitations.

**Technologies:** Splunk, SPL, Linux Authentication Logs

**MITRE ATT&CK:** T1110

[View Investigation Repository](https://github.com/WiLL75G/soc-day01-ssh-brute-force-detection)

---

### 02 | Advanced Splunk Intelligence Platform

**Focus:** SIEM Analysis & Detection Development

Developed an SPL detection and threat hunting library for investigating suspicious activity across controlled lab scenarios.

- Developed 12 SPL detection queries.
- Created 4 threat hunting playbooks.
- Documented validation of 4 detection scenarios against lab telemetry.
- Investigated authentication, PowerShell, and network activity.
- Identified considerations for detection coverage and false positives.

The remaining detection queries are not presented as fully validated.

**Technologies:** Splunk, SPL, Windows and Linux Telemetry

[View Detection Repository](https://github.com/WiLL75G/soc-28-advanced-splunk-intelligence-platform)

---

### 03 | Microsoft Sentinel SOC Lab

**Focus:** Cloud SIEM & Security Investigation

Built a Microsoft Sentinel lab to practice security monitoring, KQL analysis, and investigation workflows.

- Configured a cloud-based SIEM investigation environment.
- Worked with security telemetry and KQL queries.
- Developed lab analytics and detection logic.
- Investigated simulated SSH and PowerShell security scenarios.
- Documented the lab environment and investigation workflow.

**Technologies:** Microsoft Sentinel, Microsoft Azure, KQL

**MITRE ATT&CK:** T1110, T1059.001

[View Sentinel SOC Lab](https://github.com/WiLL75G/sentinel-soc-lab-setup)

---

### 04 | Detection Engineering Labs

**Focus:** Detection Development & Validation

Developed and tested security detection logic using endpoint and network telemetry in controlled lab environments.

- Developed custom Wazuh detection rules.
- Created Suricata rules for suspicious network activity.
- Investigated PowerShell-related security events.
- Generated controlled activity to examine detection behavior.
- Documented observed alerts, validation results, and detection limitations.

**Technologies:** Wazuh, Suricata, PowerShell, Windows Security Telemetry

**MITRE ATT&CK:** T1110, T1046, T1059.001

[View Detection Engineering Labs](https://github.com/WiLL75G/detection-engineering-labs)

---

### 05 | Phishing Email Analysis

**Focus:** Email Security & Initial Investigation

Practiced phishing email investigation using a documented lab analysis workflow.

- Examined suspicious email characteristics.
- Analyzed available message indicators.
- Investigated potential indicators of compromise.
- Documented findings and supporting evidence.
- Practiced structured phishing triage.

**Focus Areas:** Email Analysis, Indicator Extraction, Security Investigation

**MITRE ATT&CK:** T1566

[View Phishing Investigation](https://github.com/WiLL75G/soc-day02-phishing-email-analysis)

---

### 06 | SOC Shift Simulation Capstone

**Focus:** SOC Operations & Investigation Workflow

Completed a simulated SOC shift exercise designed to practice investigation and incident handling decisions in a controlled environment.

- Practiced security alert triage.
- Reviewed related security activity.
- Worked through incident correlation scenarios.
- Documented investigation findings.
- Practiced incident handling and reporting workflows.

This project represents a lab simulation, not professional SOC shift experience.

**Focus Areas:** Alert Triage, Investigation, Event Correlation, Incident Documentation

[View SOC Shift Simulation](https://github.com/WiLL75G/soc-day15-soc-shift-simulation)

---

## Investigation Approach

My investigations follow an evidence-first process:

**Baseline → Activity → Triage → Investigation → Correlation → Evidence Gaps → Disposition → Documentation**

I focus on answering five questions:

1. What activity was observed?
2. What does the evidence support?
3. What related events provide additional context?
4. What remains unknown or unverified?
5. What conclusion or next investigation action is justified?

I use MITRE ATT&CK mapping where the observed behavior supports the technique.

I treat tool deployment, alert generation, and detection validation as separate activities requiring different levels of evidence.

---

## Career Direction

My primary target is a **SOC Analyst Tier 1** role within an enterprise security team, internal SOC, MDR provider, or MSSP.

I bring documented independent lab practice involving SIEM investigations, endpoint and network telemetry, detection development, and technical reporting.

My continuing development focuses on deeper Tier 2 investigations, operational security monitoring, and Detection Engineering.

The objective is to apply my existing technical foundation in a professional SOC environment while continuing to improve investigation judgment and operational readiness.

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-WilliamInCyber-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/WilliamInCyber)

[![X](https://img.shields.io/badge/X-WilliamInCyber-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/WilliamInCyber)

[![Medium](https://img.shields.io/badge/Medium-WilliamInCyber-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@WilliamInCyber)

**Open to professional networking, technical collaboration, and relevant SOC opportunities.**

