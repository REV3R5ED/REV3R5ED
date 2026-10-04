# 👋 Hi, I'm Pouya Shini Karim

### Cybersecurity • IT Infrastructure • Python Automation

📍 North Vancouver, British Columbia, Canada

[![LogLens CI](https://img.shields.io/github/actions/workflow/status/REV3R5ED/LogLens/ci.yml?branch=main&label=LogLens)](https://github.com/REV3R5ED/LogLens/actions) [![NetScope CI](https://img.shields.io/github/actions/workflow/status/REV3R5ED/NetScope/ci.yml?branch=main&label=NetScope)](https://github.com/REV3R5ED/NetScope/actions) [![AutoOPS CI](https://img.shields.io/github/actions/workflow/status/REV3R5ED/AutoOPS/ci.yml?branch=main&label=AutoOPS)](https://github.com/REV3R5ED/AutoOPS/actions) [![SentinelKit CI](https://img.shields.io/github/actions/workflow/status/REV3R5ED/SentinelKit/ci.yml?branch=main&label=SentinelKit)](https://github.com/REV3R5ED/SentinelKit/actions) [![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org) [![License: MIT](https://img.shields.io/badge/license-MIT-green)](https://github.com/REV3R5ED/LogLens/blob/main/LICENSE)

I build practical defensive-security and IT-automation tools with an emphasis on **clear documentation, explainable results, safe defaults, and automated testing**.

My background spans IT infrastructure, systems administration, network defense, cybersecurity analysis, cloud fundamentals, and technical training. My current portfolio turns that experience into reproducible Python tools for Blue Team, SOC, networking, and IT operations workflows.

---

## 🔎 Start here

If you are reviewing this portfolio for a security, infrastructure, or Python role, start with [**LogLens**](https://github.com/REV3R5ED/LogLens): a deterministic defensive log-analysis CLI with structured parsing, explainable anomaly detection, reproducible JSON/CSV reporting, tests, CI, security documentation, and an end-to-end portfolio demo.

The ten projects below form a complementary defensive toolkit rather than unrelated demos: **LogLens** analyzes logs, **SentinelKit** supports IOC and authentication triage, **NetScope** provides bounded network diagnostics, **AutoOPS** handles safe operational checks and automation, **MetaTrace** traces image metadata and forensic characteristics, **HuntForge** hunts endpoints and reconstructs attacks, **PhishScope** traces messages and exposes email evidence, and **AegisForge** is the commercial DFIR platform unifying them into cases, timelines, and reports. Sitting above the engines, **AegisBoard** is the unified web workbench — every engine behind one professional browser UI, no CLI required — and **BlackEcho** is the end-to-end investigation lab that stages a synthetic breach across all eight tools with ground-truth scoring.

## 🚀 Featured projects

| Project | Focus | Highlights |
|---|---|---|
| [**AegisForge**](https://github.com/REV3R5ED/AegisForge) | DFIR platform (commercial, 1-week free trial) | Modular incident-response platform: network discovery, forensics, log analysis, PCAP, threat intel, correlation, case management |
| [**LogLens**](https://github.com/REV3R5ED/LogLens) | Defensive log analysis | JSON, text, RFC 5424 and OpenTelemetry parsing; explainable anomaly rules; JSON/CSV reporting |
| [**NetScope**](https://github.com/REV3R5ED/NetScope) | Network visibility and diagnostics | IPv4/IPv6 inspection, DNS, bounded TCP and route diagnostics, automation-friendly health gates |
| [**AutoOPS**](https://github.com/REV3R5ED/AutoOPS) | Safe IT operations automation | Cross-platform health checks, artifact validation, dry-run safety, workflows and structured audit logging |
| [**SentinelKit**](https://github.com/REV3R5ED/SentinelKit) | Blue Team and SOC utilities | IOC extraction, IP inspection, file hashing and authentication-log triage |
| [**HuntForge**](https://github.com/REV3R5ED/HuntForge) | Endpoint threat hunting & Windows forensics | EVTX/Sysmon/PowerShell parsing, prefetch & registry forensics, unified timeline, process lineage, explainable detection rules |
| [**PhishScope**](https://github.com/REV3R5ED/PhishScope) | Email & phishing forensics | Safe .eml parsing, Received-chain analysis, SPF/DKIM/DMARC authentication, URL/domain analysis — fully offline, observation-first |
| [**MetaTrace**](https://github.com/REV3R5ED/MetaTrace) | Image forensics and metadata analysis | EXIF/XMP/IPTC extraction, GPS normalization, tamper analysis, batch processing, timeline reports, evidence-first workflow |
| [**AegisBoard**](https://github.com/REV3R5ED/AegisBoard) | Unified web workbench for the 8 engines | Point-and-click browser UI over every engine: 16 live actions, run history, dark SOC design — a technician picks a tool and runs it, no CLI required |
| [**BlackEcho**](https://github.com/REV3R5ED/BlackEcho) | End-to-end DFIR investigation lab | Stages a full synthetic breach (phishing → endpoint → network → case) across all eight tools with ground-truth scoring — stage the breach, prove the defense |

Each project is designed around authorized defensive use and includes automated tests, CI workflows, structured output, documentation, and reproducible examples. AegisForge is commercial software with a 1-week free trial; the eight engines are open source under MIT.

## 🧭 Portfolio map

- **Image forensics:** [MetaTrace](https://github.com/REV3R5ED/MetaTrace) extracts and normalizes EXIF/metadata, hashes evidence, and keeps observation separate from interpretation.
- **DFIR platform:** [AegisForge](https://github.com/REV3R5ED/AegisForge) unifies network, forensic, log, and threat-intel evidence into cases, timelines, and reports (commercial, 1-week free trial).
- **SOC / incident triage:** start with [LogLens](https://github.com/REV3R5ED/LogLens), then use [SentinelKit](https://github.com/REV3R5ED/SentinelKit) for IOC and authentication-log inspection.
- **Network troubleshooting:** use [NetScope](https://github.com/REV3R5ED/NetScope) for local visibility, DNS, bounded TCP checks, and route diagnostics.
- **IT operations / automation:** use [AutoOPS](https://github.com/REV3R5ED/AutoOPS) for read-only health checks, artifact validation, dry-run-safe workflows, and audit-friendly output.
- **Technical review:** each core repository includes tests, CI, defensive scope documentation, and reviewer-oriented or reproducible examples so behavior can be verified rather than taken on trust.
- **Endpoint forensics:** [HuntForge](https://github.com/REV3R5ED/HuntForge) parses Windows event logs, prefetch, registry, and scheduled tasks into a unified timeline with process lineage and explainable detections — observations stay separate from verdicts.
- **Email forensics:** [PhishScope](https://github.com/REV3R5ED/PhishScope) traces messages safely: header and Received-chain analysis, SPF/DKIM/DMARC authentication, URL/domain inventory — fully offline, nothing fetched, nothing resolved.
- **Unified web access:** [AegisBoard](https://github.com/REV3R5ED/AegisBoard) puts all eight engines behind one professional browser UI — 16 live actions with run history. If you'd rather click than type, start here.
- **Investigation lab:** [BlackEcho](https://github.com/REV3R5ED/BlackEcho) stages a complete synthetic intrusion (phishing → Office/PowerShell execution → persistence → network activity) and runs it across all eight tools with ground-truth scoring: 100% indicator coverage, 6/6 cross-tool relationships reconstructed.

## 🛡️ Security and infrastructure focus

- Defensive security, SOC workflows, incident-response support and threat analysis
- Log parsing, IOC handling, anomaly detection and audit-friendly reporting
- Network diagnostics, IPv4/IPv6, DNS and bounded connectivity testing
- Linux and Windows systems administration
- Python CLI development, Git/GitHub and CI/CD automation
- Safe automation patterns, input validation, dry-run controls and deterministic output
- Cloud, containers, Kubernetes and DevOps fundamentals

## 🎓 Verified credentials

My digital credentials are publicly verifiable through my [**Credly profile**](https://www.credly.com/users/sheini).

### Headline certifications

- [**Junior Cybersecurity Analyst Career Path**](https://www.credly.com/users/sheini) — Cisco · issued May 13, 2022
- [**Cybersecurity Analyst Professional Certificate**](https://www.credly.com/users/sheini) — IBM · issued Jan 26, 2023
- [**MCSA: Windows Server 2012**](https://www.credly.com/users/sheini) — Microsoft · issued Dec 2014
- [**Microsoft Certified Trainer**](https://www.credly.com/users/sheini) — Microsoft · 2021–2022 and 2022–2023

### Cisco supporting badges

[Network Defense](https://www.credly.com/users/sheini) · [Endpoint Security](https://www.credly.com/users/sheini) · [Cyber Threat Management](https://www.credly.com/users/sheini) · [Networking Essentials](https://www.credly.com/users/sheini) · [Introduction to Cybersecurity](https://www.credly.com/users/sheini) — all issued Apr–May 2022.

### IBM supporting specializations

[Security Analyst Fundamentals Specialization](https://www.credly.com/users/sheini) · [Cybersecurity IT Fundamentals Specialization](https://www.credly.com/users/sheini) — issued Oct 2021.

## 🛠️ Core technologies

`Python` · `Linux` · `Windows Server` · `Networking` · `Git` · `GitHub Actions` · `CI/CD` · `Docker` · `Kubernetes` · `JSON` · `CSV` · `CLI Tooling`

## 🤝 Open to collaboration

I'm interested in collaborating on:

- Defensive security and Blue Team tools
- Security automation and log-analysis projects
- Open-source IT operations tooling
- Network diagnostics and observability
- AI-assisted cybersecurity projects

## 📫 Connect

- GitHub: [@REV3R5ED](https://github.com/REV3R5ED)
- Verified credentials: [Credly — Pouya Shini Karim](https://www.credly.com/users/sheini)

---

> Build tools that solve real problems. Make the results explainable. Test everything.
