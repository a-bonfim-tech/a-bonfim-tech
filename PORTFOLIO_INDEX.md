# Cybersecurity Portfolio Index

A recruiter-facing map of the public portfolio, organized by demonstrated evidence, technical depth and complementary hiring signals rather than by repository age or course completion.

## Professional Positioning

**Cybersecurity — Secure AI, Cloud Security, IAM, Security Automation, Security Governance and SOC-related analysis**

The portfolio is intentionally structured around six evidence dimensions:

1. **Secure AI and authorization architecture** — bounded agency, human accountability, identity, scope and execution controls.
2. **Security engineering and automation** — governed SDKs, deterministic validation, testing, packaging and supply-chain controls.
3. **Governance, risk and compliance** — control mapping, evidence, risk scoring, remediation and audit-oriented outputs.
4. **Cloud security** — IAM, network controls, encryption, logging, Zero Trust and cloud-security evidence.
5. **Security operations** — traffic analysis, IOC extraction, phishing investigation and incident reasoning.
6. **Security decision engineering** — detection strategy, governance, auditability and human-reviewed security decisions.

## Recruiter Fast Path — Six Flagship Repositories

For a 15–20 minute review, inspect these projects in this order:

| Priority | Repository | What to verify |
| ---: | --- | --- |
| **1** | **[Officer-Bound Digital Investigation Agent](https://github.com/a-bonfim-tech/officer-bound-digital-investigation-agent)** | Human-bound authorization, default-DENY execution, officer/case/scope/time/connector binding, threat modeling, Go implementation, AC01–AC20, fuzzing, security scanning, SBOM, CI and evidence governance. |
| **2** | **[Bonfim SDK](https://github.com/a-bonfim-tech/bonfim-sdk)** | Governed Python Skills/Agents/Automations, 3.11–3.14 compatibility, strong test/coverage evidence, strict typing, SAST, full-history secret scanning, CycloneDX SBOM, packaging and provenance. |
| **3** | **[AI SaaS Security & Compliance Fit-Gap](https://github.com/a-bonfim-tech/ai-saas-security-compliance-fit-gap-public)** | TypeScript evidence engine mapping security/compliance requirements to controls, evidence, gaps, risk and remediation across NIST CSF, ISO 27001, SOC 2, GDPR, EU AI Act and OWASP-oriented domains. |
| **4** | **[GCP Security Study Cases](https://github.com/a-bonfim-tech/gcp-security-study-cases)** | Cloud Armor, Cloud NGFW, BeyondCorp, CMEK/KMS, logging, monitoring, VPC Flow Logs and evidence-backed cloud-security reasoning. |
| **5** | **[TShark SOC Case Study](https://github.com/a-bonfim-tech/tshark-teamwork-soc-case-study)** | PCAP investigation, phishing identification, HTTP analysis, IOC extraction, defanging and threat-intelligence correlation. |
| **6** | **[Human SIEM Cybersecurity](https://github.com/a-bonfim-tech/human-siem-cybersecurity)** | Security-decision operating model, detection strategy, SOC reasoning, governance constraints, synthetic evidence and audit-oriented decision documentation. |

## Why This Order

The six repositories are intentionally complementary:

```text
Secure AI Architecture
        ↓
Security Engineering & Automation
        ↓
GRC / AI Governance
        ↓
Cloud Security
        ↓
SOC Hands-On Investigation
        ↓
Security Decision Engineering
```

The objective is to demonstrate breadth without presenting a collection of disconnected labs.

## Role-Based Reading Paths

### Secure AI / AI Security / Security Architecture

1. `officer-bound-digital-investigation-agent`
2. `bonfim-sdk`
3. `ai-saas-security-compliance-fit-gap-public`

Signals: human accountability, authority boundaries, fail-closed execution, secure agent design, threat modeling, governance and evidence engineering.

### Security Automation / DevSecOps

1. `bonfim-sdk`
2. `officer-bound-digital-investigation-agent`
3. `ai-saas-security-compliance-fit-gap-public`

Signals: Python/Go/TypeScript engineering, deterministic validation, tests, CI, SAST, SBOM, provenance, secret scanning and secure release practices.

### Cloud Security and IAM

1. `gcp-security-study-cases`
2. `officer-bound-digital-investigation-agent`
3. `ai-saas-security-compliance-fit-gap-public`

Signals: cloud-control knowledge, identity-first security, Zero Trust, network exposure review, logging, encryption and defensible risk decisions.

### Security Governance / GRC / AI Governance

1. `ai-saas-security-compliance-fit-gap-public`
2. `officer-bound-digital-investigation-agent`
3. `human-siem-cybersecurity`

Signals: control assessment, evidence management, risk communication, auditability, GDPR/ISO/NIST-oriented reasoning, AI governance and explicit limitations.

### SOC / Blue Team

1. `tshark-teamwork-soc-case-study`
2. `human-siem-cybersecurity`
3. `gcp-security-study-cases`

Signals: packet analysis, IOC development, investigation structure, cloud observability, escalation reasoning and operational documentation.

## Supporting Public Portfolio

These repositories remain useful supporting evidence but are intentionally secondary to the six flagships:

- [AI DevSecOps Baseline](https://github.com/a-bonfim-tech/ai-devsecops-baseline) — automated security gates, SBOM, vulnerability and secrets controls.
- [Guided Web Pentest](https://github.com/a-bonfim-tech/thm-guided-pentest-web) — authorized web application assessment, IDOR, authentication weaknesses, RCE and attack-chain analysis.
- [Cloud Risk Decision Framework](https://github.com/a-bonfim-tech/cloud-risk-decision-framework) — documentation-first cloud-risk decisions and audit traceability.
- [Cyber-Portfolio](https://github.com/a-bonfim-tech/Cyber-Portfolio) — governance and audit-oriented security documentation.
- [Kali DevSecOps Baseline](https://github.com/a-bonfim-tech/kali-devsecops-baseline) — repeatable workstation security baseline and evidence collection.
- [AWS EBS Snapshot Audit](https://github.com/a-bonfim-tech/aws-ec2-ebs-snapshot-check-bash) — read-only AWS snapshot-security audit automation.
- [Gemini Security Engineering Study Lab](https://github.com/a-bonfim-tech/gemini-security-engineering-study-lab) — evidence-first AI-assisted security analysis using synthetic data.
- [Security+ Crypto Lab](https://github.com/a-bonfim-tech/security-plus-crypto-lab) — TLS 1.3 and cryptographic evidence exercises.

Training-oriented and conceptual repositories remain available for depth but do not receive recruiter priority over independently engineered flagship artifacts.

## Evidence Standard

A project qualifies for recruiter priority only when it clearly states:

- problem and authorized scope;
- individual contribution;
- methodology, tools and assumptions;
- reproducible execution or validation steps;
- sanitized technical evidence;
- findings and risk interpretation;
- remediation, decision or conclusion;
- limitations and unresolved work;
- security/privacy safeguards;
- separation between original work and third-party material;
- human authority boundaries where AI or automation is involved.

## Publication Rules

- No credentials, tokens, private keys, customer data, employer-owned evidence or production secrets.
- No unsupported claims of compliance, certification, seniority or production readiness.
- Synthetic and training environments must be identified explicitly.
- Private canonical projects require an explicit publication/sanitization decision before public use.
- Forks do not receive recruiter priority unless the individual contribution is substantial and documented.

## Current Elevation Queue

1. **OBDIA** — preserve `v0.1.x` as the bounded reference baseline; develop `v0.2.x` productionization architecture without weakening the original security boundary.
2. **Bonfim SDK** — public/release hardening for `v0.2.x`, followed by `v0.3.x` isolated execution architecture.
3. **AI SaaS Security & Compliance Fit-Gap** — raise public assurance, evidence and release maturity as the primary GRC / AI-governance anchor.
4. **GCP Security Study Cases** — deepen IAM and cloud-control reproducibility.
5. **TShark SOC Case Study** — add detection engineering, incident timeline and mapped response decisions.
6. **Human SIEM** — strengthen executable validation/evidence while preserving its decision-engineering role.
