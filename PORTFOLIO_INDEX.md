# Cybersecurity Portfolio Index

This index maps portfolio repositories to recruiter-facing security signals,
technical evidence, and the roles each project best supports.

## Objective

Provide a fast, audit-friendly route through the public GitHub portfolio for
recruiters, mentors, reviewers, and cybersecurity hiring teams.

## Priority Projects

| Repository | Primary signal | Evidence type | Best fit |
| --- | --- | --- | --- |
| [thm-guided-pentest-web](https://github.com/a-bonfim-tech/thm-guided-pentest-web) | Authorized web application penetration testing | Scope, methodology, evidence structure, vulnerability chain analysis | Web security, penetration testing, vulnerability assessment |
| [ai-devsecops-baseline](https://github.com/a-bonfim-tech/ai-devsecops-baseline) | Automated DevSecOps security gates | GitHub Actions, SBOM, vulnerability scanning, secrets detection, OPA policy-as-code | DevSecOps, security automation, cloud security engineering |
| [gcp-security-study-cases](https://github.com/a-bonfim-tech/gcp-security-study-cases) | Google Cloud security study cases | Cloud Armor, NGFW, BeyondCorp, KMS, logging and monitoring notes | Cloud security, GCP, security architecture |
| [tshark-teamwork-soc-case-study](https://github.com/a-bonfim-tech/tshark-teamwork-soc-case-study) | Network forensics and SOC analysis | TShark investigation, IOC extraction, HTTP analysis, threat correlation | SOC, blue team, incident analysis |
| [cloud-risk-decision-framework](https://github.com/a-bonfim-tech/cloud-risk-decision-framework) | Risk-based cloud security decisions | Decision options, trade-off analysis, audit-ready reasoning | GRC, cloud risk, architecture review |
| [human-siem-cybersecurity](https://github.com/a-bonfim-tech/human-siem-cybersecurity) | Governance-driven security operations model | SIEM/SOC governance, validation and leadership review framing | SOC governance, GRC, security leadership |

## Role Mapping

| Role direction | Repositories to inspect first | Why |
| --- | --- | --- |
| Cloud Security | `gcp-security-study-cases`, `cloud-risk-decision-framework`, `ai-devsecops-baseline` | Shows cloud controls, decision quality, and security automation. |
| SOC / Blue Team | `tshark-teamwork-soc-case-study`, `human-siem-cybersecurity` | Shows investigation workflow, evidence handling, and operational reasoning. |
| DevSecOps | `ai-devsecops-baseline`, `kali-devsecops-baseline` | Shows automated security gates and repeatable tooling. |
| GRC / Governance | `cloud-risk-decision-framework`, `human-siem-cybersecurity`, `bonfim-security-constitution` | Shows decision records, auditability, and compliance-safe documentation. |
| Web Security | `thm-guided-pentest-web` | Shows authorized lab scope, OWASP/PTES-inspired methodology, and vulnerability chaining. |
| Responsible AI Governance | `ai-governance-inference-privacy-case-study` | Shows privacy, inference behavior, and risk communication framing. |

## Evidence Standard

Portfolio projects should prefer:

- Clear authorization and scope.
- Sanitized evidence.
- Repeatable methodology.
- Explicit risk reasoning.
- Framework alignment where useful.
- No active credentials, flags, tokens, or live third-party targets.

## Current Improvement Priorities

1. Keep the six priority projects pinned on the GitHub profile.
2. Add or maintain explicit licenses and security policies in anchor repositories.
3. Add validation notes and diagrams to cloud/security architecture projects.
4. Keep workflow badges only where the underlying workflow is stable.
5. Separate original work from forks, references, and third-party learning material.
