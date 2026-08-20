# Cybersecurity Portfolio Index

A recruiter-facing map of the public portfolio, organized by demonstrated evidence, technical depth and complementary hiring signals rather than by repository age or course completion.

## Professional Positioning

**Cybersecurity — Secure AI, Cloud Security, IAM, Security Automation, Security Governance and SOC-related analysis**

The portfolio is intentionally structured around six evidence dimensions:

1. **Security infrastructure and detection** — segmentation, firewall policy, IDS/SIEM rules, testing and retained evidence.
2. **Secure AI and authorization architecture** — bounded agency, human accountability, identity, scope and execution controls.
3. **Security engineering and automation** — governed SDKs, deterministic validation, testing, packaging and supply-chain controls.
4. **Governance, risk and compliance** — control mapping, evidence, risk scoring, remediation and audit-oriented outputs.
5. **AI-assisted security analysis** — synthetic event correlation, analyst validation and calibrated conclusions.
6. **Security operations** — traffic analysis, IOC extraction, phishing investigation and incident reasoning.

## Recruiter Fast Path — Six Flagship Repositories

For a 15–20 minute review, inspect these projects in this order:

| Priority | Repository | What to verify |
| ---: | --- | --- |
| **1** | **[Cybersecurity Private Cloud Homelab](https://github.com/a-bonfim-tech/cybersecurity-private-cloud-homelab)** | Native FreeBSD PF segmentation evidence, Suricata and Wazuh tests, IaC, threat modeling, integrity manifests and explicit unproven boundaries. |
| **2** | **[Officer-Bound Digital Investigation Agent](https://github.com/a-bonfim-tech/officer-bound-digital-investigation-agent)** | Human-bound authorization, default-DENY execution, officer/case/scope/time/connector binding, threat modeling, Go implementation, AC01–AC20, security scanning, SBOM and CI. |
| **3** | **[Bonfim SDK](https://github.com/a-bonfim-tech/bonfim-sdk)** | Governed Python Skills/Agents/Automations, 3.11–3.14 compatibility, test/coverage evidence, strict typing, SAST, secret scanning, CycloneDX SBOM, packaging and provenance. |
| **4** | **[AI SaaS Security & Compliance Fit-Gap](https://github.com/a-bonfim-tech/ai-saas-security-compliance-fit-gap-public)** | TypeScript evidence engine mapping security/compliance requirements to controls, evidence, gaps, risk and remediation across six framework domains. |
| **5** | **[Gemini Security Engineering Study Lab](https://github.com/a-bonfim-tech/gemini-security-engineering-study-lab)** | Tested synthetic event correlation, AI-risk controls, human validation and explicit separation of learned, demonstrated and unproven claims. |
| **6** | **[TShark SOC Case Study](https://github.com/a-bonfim-tech/tshark-teamwork-soc-case-study)** | Authorized phishing-analysis study with HTTP inspection, IOC extraction, defanging and threat-intelligence correlation. |

## Why This Order

The six repositories are intentionally complementary:

```text
Security Infrastructure & Detection
        ↓
Secure AI Architecture
        ↓
Security Engineering & Automation
        ↓
GRC / AI Governance
        ↓
AI-Assisted Security Analysis
        ↓
SOC Hands-On Investigation
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

1. `cybersecurity-private-cloud-homelab`
2. `officer-bound-digital-investigation-agent`
3. `ai-saas-security-compliance-fit-gap-public`

Signals: cloud-control knowledge, identity-first security, Zero Trust, network exposure review, logging, encryption and defensible risk decisions.

### Security Governance / GRC / AI Governance

1. `ai-saas-security-compliance-fit-gap-public`
2. `officer-bound-digital-investigation-agent`
3. `human-siem-cybersecurity`

Signals: control assessment, evidence management, risk communication, auditability, GDPR/ISO/NIST-oriented reasoning, AI governance and explicit limitations.

### SOC / Blue Team

1. `cybersecurity-private-cloud-homelab`
2. `tshark-teamwork-soc-case-study`
3. `gemini-security-engineering-study-lab`

Signals: packet analysis, IOC development, investigation structure, cloud observability, escalation reasoning and operational documentation.

## Supporting Public Portfolio

These repositories remain useful supporting evidence but are intentionally secondary to the six flagships:

- [AI DevSecOps Baseline](https://github.com/a-bonfim-tech/ai-devsecops-baseline) — automated security gates, SBOM, vulnerability and secrets controls.
- [Guided Web Pentest](https://github.com/a-bonfim-tech/thm-guided-pentest-web) — authorized web application assessment, IDOR, authentication weaknesses, RCE and attack-chain analysis.
- [Cloud Risk Decision Framework](https://github.com/a-bonfim-tech/cloud-risk-decision-framework) — documentation-first cloud-risk decisions and audit traceability.
- [Cyber-Portfolio](https://github.com/a-bonfim-tech/Cyber-Portfolio) — governance and audit-oriented security documentation.
- [Kali DevSecOps Baseline](https://github.com/a-bonfim-tech/kali-devsecops-baseline) — repeatable workstation security baseline and evidence collection.
- [AWS EBS Snapshot Audit](https://github.com/a-bonfim-tech/aws-ec2-ebs-snapshot-check-bash) — read-only AWS snapshot-security audit automation.
- [GCP Security Study Cases](https://github.com/a-bonfim-tech/gcp-security-study-cases) — cloud-security study notes; current public evidence is incomplete and should not be treated as execution proof.
- [Human SIEM Cybersecurity](https://github.com/a-bonfim-tech/human-siem-cybersecurity) — security decision and governance model; primarily conceptual documentation rather than executable proof.
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

1. **Private Cloud Homelab** — close validated security findings and expand only through bounded integration evidence.
2. **OBDIA** — preserve `v0.1.x` as the bounded reference baseline; develop productionization separately without weakening the original security boundary.
3. **Bonfim SDK** — continue release hardening, followed by isolated-execution research.
4. **AI SaaS Security & Compliance Fit-Gap** — raise public assurance and evidence maturity as the primary GRC / AI-governance anchor.
5. **Gemini Security Engineering Study Lab** — retain its educational boundary and add personal authorized-lab evidence only when available.
6. **TShark SOC Case Study** — add reproducible command output, detection logic, incident timeline and mapped response decisions.
