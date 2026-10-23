# 🛡️ Threat Hunting Team (THT)

**Cyber Threat Intelligence · Threat Detection Engineering · Threat Hunting**

[![Community](https://img.shields.io/badge/Community-RedTeamRD.org-blue.svg)](https://redteamrd.org)
[![Conference](https://img.shields.io/badge/Event-HackConRD.org-red.svg)](https://hackconrd.org)
[![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-Reference-orange.svg)](https://attack.mitre.org)
[![MITRE D3FEND](https://img.shields.io/badge/MITRE%20D3FEND-Reference-purple)](https://d3fend.mitre.org/resources/)

## About the project

THT is a collaborative initiative by **RedTeamRD.org** to strengthen Cyber Threat Intelligence and Threat Hunting across corporate, government, and community environments. We share an interest in CTFs and in understanding how adversaries combine tactics, techniques, and procedures (TTPs).

Our objective is to share resources, detection ideas, tools, and analysis that help defenders investigate threats and improve detection and response. The research scope is not limited to a specific threat actor.

## Repository contents

The repository currently provides introductory documentation and visual resource collections:

- [Local tools — part 1](Tools%20local%201.png) and [part 2](Tools%20local%202.png)
- [Online tools — part 1](Tools%20oline1.png) and [part 2](Tools%20oline2.png)
- [Other platforms](Other%20Platforms.png)

The intended contribution areas include contextualized IoCs, SentinelOne detection and hunting examples, analysis utilities, forensic use cases, and educational material. These are development directions; availability and validation should be assessed per artifact.

## From intelligence to detection

```text
Threat context → Hunt hypothesis → Required telemetry → Detection logic → Validation → Tuning
```

For each detection or hunt contribution, document:

1. **Objective:** the behavior being investigated and its defensive value.
2. **Data requirements:** telemetry sources, fields, product versions, and assumptions.
3. **ATT&CK mapping:** relevant techniques or sub-techniques, with reasoning.
4. **Validation:** controlled test procedure and expected evidence.
5. **Tuning:** likely false positives, exclusions, and coverage limitations.
6. **Provenance:** public references and relevant observation dates.

SentinelOne queries and other product-specific examples should identify the applicable query language, schema, and tested environment. Treat unvalidated examples as research material.

## How to contribute

- Fork the repository and submit a focused pull request.
- Explain the use case, data requirements, validation, and limitations.
- Share only material you are authorized to publish. Use public, synthetic, or sanitized examples.
- Exclude credentials, client identifiers, personal information, private infrastructure, and confidential telemetry.
- Include context and provenance for IoCs, and distinguish observations from hypotheses.

Corrections, validation results, hunting ideas, and documentation improvements are welcome.

## Reference resources

### Frameworks and tooling

- [MITRE ATT&CK](https://attack.mitre.org)
- [MITRE D3FEND](https://d3fend.mitre.org/resources/)
- [Maltego TRX](https://github.com/MaltegoTech/maltego-trx)
- [ADHD Project](https://adhdproject.github.io/#!index.md)

### Advisories and threat research

- [CISA Alerts](https://www.cisa.gov/stopransomware/alerts) and [Cybersecurity Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories)
- [NIST Cybersecurity News](https://csrc.nist.gov/news)
- [FBI Cyber News](https://www.fbi.gov/investigate/cyber/news)
- [ENISA Threats](https://www.enisa.europa.eu/news?f%5B0%5D=topics%3A526#contentList)
- [INTERPOL Cybercrime Threat Response](https://www.interpol.int/Crimes/Cybercrime/Cybercrime-threat-response)
- [NCSC Threat Reports](https://www.ncsc.gov.uk/section/keep-up-to-date/threat-reports?q=&defaultTypes=report&sort=date%2Bdesc)
- SentinelLabs: [Crimeware](https://www.sentinelone.com/labs/category/crimeware/) and [Security Intelligence](https://www.sentinelone.com/labs/category/security-intelligence/)

## Community

- [RedTeamRD.org](https://redteamrd.org) — cybersecurity community in LATAM.
- [HackConRD.org](https://hackconrd.org) — offensive and defensive security conference.
- [RM-ReactorHunt](https://github.com/RM-ReactorHunt) — maintaining this repository under a research pseudonym.

## Responsible use

Content is intended for authorized defensive security, education, and research. Validate detections and automation in a controlled environment before production use. References to products, frameworks, or organizations do not imply endorsement.

<p align="center">
  <img src="https://raw.githubusercontent.com/RM-ReactorHunt/Threat-Hunting-Team-THT-/main/THT%20Threat%20Hunting%20Team.png" alt="Threat Hunting Community" width="700">
</p>
