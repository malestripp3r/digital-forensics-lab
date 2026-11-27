# digital-forensics-lab
Digital forensics investigations involving network traffic analysis, disk image examination, artifact identification and incident reconstruction.

# Digital Forensics Lab

This repository documents my ongoing practical work in digital forensics as part of my cybersecurity studies.

The project focuses on investigating security incidents through the analysis of network traffic, disk images, memory captures, and Windows event logs.

The investigations are based on a simulated security incident involving **Dino-Secure**, an organization experiencing suspicious activity within its infrastructure.

## Objectives

The main objectives of this project are to:

- Analyze different types of digital evidence.
- Identify suspicious activities and potential indicators of compromise (IOCs).
- Investigate possible attack vectors and persistence mechanisms.
- Examine potential data exfiltration and lateral movement.
- Correlate evidence to reconstruct security incidents.
- Document investigation techniques, observations, and findings.

## Investigations

The project covers four complementary areas of digital forensics, with investigations being documented progressively.

### 01 — Network Forensics

Analysis of a network capture (`merged.pcap`) to identify suspicious network activity and investigate communications between internal and external systems.

**Tools:** Wireshark, TShark, Kali Linux

**Focus areas:**
- Network traffic and protocol analysis
- DNS, HTTP, TLS, and SSH communications
- Suspicious connections and traffic patterns
- Potential data exfiltration

### 02 — Disk Forensics

Examination of a Linux disk image (`webserver_disk.raw`) to investigate filesystem artifacts, system activity, and potential signs of compromise.

**Tools:** Autopsy, Linux CLI

**Focus areas:**
- Filesystem and artifact analysis
- User and system activity
- Suspicious files and configurations
- Persistence and privilege escalation indicators

### 03 — Memory Forensics

Analysis of a Linux memory capture (`debian13-memory.lime`) to investigate processes and identify potentially suspicious activity in system memory.

**Tools:** Volatility 3, Linux CLI

**Focus areas:**
- Process enumeration and analysis
- Suspicious command-line activity
- Process relationships
- Memory artifacts and evidence correlation

### 04 — Windows Event Log Forensics

Analysis of Windows event logs collected from the organization's Active Directory server to investigate potential lateral movement and determine whether the attacker expanded their access within the infrastructure.

**Tools:** Hayabusa, Kali Linux

**Focus areas:**
- Windows event log analysis
- Authentication and account activity
- Suspicious logon events
- Potential lateral movement
- Correlation with previous forensic findings

*Status: Planned — Investigation not yet started.*

## Methodology

The investigations follow a structured forensic approach:

1. **Evidence Verification** — Verify the integrity of the provided evidence.
2. **Initial Examination** — Identify relevant systems, artifacts, and activities.
3. **Technical Analysis** — Examine suspicious findings using forensic tools.
4. **Evidence Correlation** — Connect observations across available evidence sources.
5. **Incident Reconstruction** — Establish timelines and investigate potential attack scenarios.
6. **Documentation** — Record procedures, findings, and supporting evidence.

## Tools and Technologies

- **Wireshark / TShark** — Network traffic analysis
- **Autopsy** — Disk and filesystem analysis
- **Volatility 3** — Memory analysis
- **Hayabusa** — Windows event log analysis
- **Kali Linux** — Investigation environment
- **Linux CLI** — Evidence examination and processing

## Documentation

Each investigation will be progressively documented with relevant commands, observations, screenshots, and technical findings.

The documentation aims to distinguish confirmed evidence from hypotheses and provide clear explanations of the investigation process.

## Project Status

**Ongoing — Investigations and documentation in progress.**

Additional findings and investigation reports will be added as the project develops.
