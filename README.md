# Walker | SOC Analyst & Digital Forensics Investigator

I hunt threats in Windows environments, investigate suspicious activity, and turn the telemetry behind those investigations into detections a SOC can use. I develop Splunk correlation searches, adapt Sigma rules to the data available, and automate repetitive triage steps so analysts can spend more time validating and responding to findings.

## Core Competencies

| Area | Capabilities |
|---|---|
| **SIEM & log analysis** | Splunk Enterprise Security, SPL query development, correlation searches, Sysmon event analysis, and correlation across endpoint and authentication logs |
| **Detection engineering** | Custom detection logic, Sigma-to-SPL conversion, false-positive analysis, and validation against expected administrative activity |
| **Incident response & forensics** | Windows artifact parsing and timeline reconstruction, investigation of process injection and fileless persistence, Eric Zimmerman’s tools, and FLARE-VM |
| **Scripting & automation** | Python and PowerShell for evidence parsing and enrichment, plus Cortex XSOAR playbooks for triage and response |
| **Threat intelligence & hunting** | IOC enrichment, hypothesis-driven hunts, and MITRE ATT&CK mapping to connect observed behavior with adversary techniques |

## Featured Projects

*Repository placeholders for SPL, Sigma, and DFIR automation work.*

| Project | What it demonstrates |
|---|---|
| **Splunk ES Detection Library** | Custom SPL and correlation searches that combine Sysmon and Windows event data. Each detection documents its telemetry requirements, common benign matches, and the fields analysts need to validate an alert without rebuilding the search. |
| **Sigma Rules for Windows Threat Hunting** | Behavior-based rules for suspicious execution and persistence, with MITRE ATT&CK mappings, SPL translations, and notes on field mappings and false positives. |
| **DFIR Triage & Response Playbooks** | Cortex XSOAR workflows that use Python and PowerShell to enrich indicators, collect triage context, and standardize handoffs. The goal is to reduce mean time to resolution (MTTR) by removing manual lookups and duplicate work. |

## Professional Approach

I start a hunt with a testable hypothesis and identify which data sources can confirm or challenge it. Before promoting a hunt query to a detection, I check how it behaves against routine administrative activity and make sure the alert gives the next analyst enough context to act. In an investigation, I document what the evidence supports, what remains uncertain, and what to check next.

[Security Field Notes](https://walker5555.github.io/Ahmed-Moaz/) · [LinkedIn](https://www.linkedin.com/in/ahmed-moaz11/) · [Medium](https://medium.com/@ahmedmoaz2003)
