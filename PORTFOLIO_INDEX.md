# Cybersecurity Portfolio Index

A recruiter-facing map of the public portfolio, organized by demonstrated evidence rather than by course completion or broad skill claims.

## Professional Positioning

**Junior Cybersecurity Analyst — Cloud Security, IAM, Security Governance and SOC-related analysis**

The portfolio is designed to show four evidence categories:

1. **Cloud controls** — IAM, network security, encryption, logging and policy decisions.
2. **Security operations** — traffic analysis, IOC extraction, investigation and incident reasoning.
3. **Secure engineering** — CI security gates, SBOM, scanning and policy-as-code.
4. **Governance and assurance** — control assessment, technical evidence, risk decisions and audit-ready documentation.

## Recruiter Fast Path

For a ten-minute review, inspect these projects in order:

| Order | Repository | What to verify |
| ---: | --- | --- |
| 1 | [GCP Security Study Cases](https://github.com/a-bonfim-tech/gcp-security-study-cases) | Cloud Armor, Cloud NGFW, BeyondCorp, KMS, logging, monitoring and evidence-based cloud review. |
| 2 | [TShark SOC Case Study](https://github.com/a-bonfim-tech/tshark-teamwork-soc-case-study) | PCAP investigation, phishing identification, HTTP analysis, IOC extraction and threat-intelligence correlation. |
| 3 | [DevSecOps Baseline](https://github.com/a-bonfim-tech/ai-devsecops-baseline) | GitHub Actions, SBOM generation, vulnerability scanning, secrets detection and OPA policy-as-code. |
| 4 | [Guided Web Pentest](https://github.com/a-bonfim-tech/thm-guided-pentest-web) | Authorized scope, reconnaissance, IDOR, weak reset logic, RCE, vulnerability chaining and reporting. |
| 5 | [Human SIEM Cybersecurity](https://github.com/a-bonfim-tech/human-siem-cybersecurity) | Synthetic security-decision documentation, governance controls and audit-oriented reasoning. |
| 6 | [Cloud Risk Decision Framework](https://github.com/a-bonfim-tech/cloud-risk-decision-framework) | Cloud-risk options, trade-offs, decision records and limitation-aware recommendations. |

## Role-Based Reading Paths

### Cloud Security and IAM

1. `gcp-security-study-cases`
2. `ai-devsecops-baseline`
3. `cloud-risk-decision-framework`

Signals: cloud-control knowledge, identity-first security, network exposure review, logging, encryption and defensible risk decisions.

### SOC and Blue Team

1. `tshark-teamwork-soc-case-study`
2. `human-siem-cybersecurity`
3. `ai-devsecops-baseline`

Signals: evidence handling, packet and log analysis, IOC development, investigation structure and operational documentation.

### Security Governance and GRC

1. `cloud-risk-decision-framework`
2. `human-siem-cybersecurity`
3. `gcp-security-study-cases`

Signals: control assessment, risk communication, traceability, audit-ready documentation and explicit limitations.

### DevSecOps and Security Automation

1. `ai-devsecops-baseline`
2. `gcp-security-study-cases`
3. `thm-guided-pentest-web`

Signals: repeatable checks, workflow security, scanning, policy gates and technically grounded remediation.

### Web Security

1. `thm-guided-pentest-web`
2. `tshark-teamwork-soc-case-study`

Signals: authorized testing, vulnerability chaining, traffic evidence and professional reporting.

## Evidence Standard

A project qualifies for recruiter priority only when it clearly states:

- the problem and authorized scope;
- the author's contribution;
- tools, methodology and assumptions;
- reproducible execution or validation steps;
- sanitized evidence;
- findings and risk interpretation;
- remediation, decision or conclusion;
- limitations and unresolved work;
- separation between original work and third-party material.

## Publication Rules

- No credentials, tokens, private keys, internal identifiers or production evidence.
- No employer-owned material without explicit publication authorization.
- No unsupported claims of compliance, certification, seniority or production readiness.
- Private canonical projects require a separate, sanitised public portfolio edition.
- Forks do not receive recruiter priority unless the contribution is substantial and documented.

The full release procedure is defined in [PRIVATE_REPOSITORY_PUBLICATION_GATE.md](PRIVATE_REPOSITORY_PUBLICATION_GATE.md).

## Current Portfolio Roadmap

1. Prepare a sanitized public portfolio edition based on security-control assessment experience.
2. Harden and publish the strongest private security-automation project after security review.
3. Complete the GCP Cloud Security Lab with reproducible, sanitized evidence.
4. Standardize README structure, security policies, licenses, CI and recruiter reading paths across anchor repositories.
5. Replace provisional pins only after the new projects pass publication and evidence gates.
