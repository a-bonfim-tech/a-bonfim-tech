# SOC portfolio index

Primary target: first SOC Analyst / Junior Cybersecurity role. No production SOC experience claimed. Public portfolio evidence is separated from synthetic, guided and specification-only work.

## Current public evidence order

| Priority / category | Project | What it proves | What it does not prove | Evidence / reproduction | Interview support |
|---|---|---|---|---|---|
| **1 — SOC Core** | [soc-analyst-lab](https://github.com/a-bonfim-tech/soc-analyst-lab) | Evidence-bounded controlled-lab SOC investigations with Microsoft Defender for Endpoint/XDR, Microsoft Sentinel KQL runtime, real Windows endpoint telemetry, phishing/email and controlled network evidence, severity/disposition decisions and Sigma validation | No production SOC employment, customer incident handling, production Microsoft Sentinel/Defender administration, enterprise-scale operations or real adversary incident | [README](https://github.com/a-bonfim-tech/soc-analyst-lab) / [SOC-2026-006 investigation](https://github.com/a-bonfim-tech/soc-analyst-lab/blob/main/03-investigations/SOC-2026-006/investigation.md) / [Sentinel KQL runtime](https://github.com/a-bonfim-tech/soc-analyst-lab/blob/main/04-detection-rules/kql/SOC-2026-006/README.md) / [SOC-2026-003 Windows endpoint](https://github.com/a-bonfim-tech/soc-analyst-lab/blob/main/03-investigations/SOC-2026-003/CASE_OVERVIEW.md) | Walk through SOC-2026-006 from Defender for Endpoint alert to XDR incident, Sentinel KQL, severity reassessment and closure; contrast with SOC-2026-007 phishing escalation and explicit laboratory boundaries |
| 2 | [cybersecurity-private-cloud-homelab](https://github.com/a-bonfim-tech/cybersecurity-private-cloud-homelab) | Retained native PF records and synthetic Suricata/Wazuh test outputs | No production SIEM, real adversary incident or unified packet path | [docs/evidence/executions/wazuh/WAZUH-EXEC-001-result.txt](https://github.com/a-bonfim-tech/cybersecurity-private-cloud-homelab/blob/main/docs/evidence/executions/wazuh/WAZUH-EXEC-001-result.txt) / [REPRODUCE.md](https://github.com/a-bonfim-tech/cybersecurity-private-cloud-homelab/blob/main/REPRODUCE.md) | Explain rule 100010; distinguish alert from prevention; explain negative controls; separate two clocks; justify escalation |
| 3 | [kali-devsecops-baseline](https://github.com/a-bonfim-tech/kali-devsecops-baseline) | Dated Linux state collection and reporting | No complete alert-led incident or production Linux responsibility | [evidence/2026-01-15/01_system.txt](https://github.com/a-bonfim-tech/kali-devsecops-baseline/blob/main/evidence/2026-01-15/01_system.txt) / [REPRODUCE.md](https://github.com/a-bonfim-tech/kali-devsecops-baseline/blob/main/REPRODUCE.md) | What auth data exists; what command failed; how preserve timestamps; what proves firewall state; what missing evidence blocks closure |
| 4 | [tshark-teamwork-soc-case-study](https://github.com/a-bonfim-tech/tshark-teamwork-soc-case-study) | Guided training narrative and bounded methodology | No retained PCAP/command output or independently verified incident | [README.md](https://github.com/a-bonfim-tech/tshark-teamwork-soc-case-study/blob/main/README.md) / [REPRODUCE.md](https://github.com/a-bonfim-tech/tshark-teamwork-soc-case-study/blob/main/REPRODUCE.md) | What did platform supply; does POST prove theft; which packet supports IOC; how timezone is known; why reputation is not proof |
| 5 | [security-plus-crypto-lab](https://github.com/a-bonfim-tech/security-plus-crypto-lab) | Retained local TLS handshake and certificate observations | No production PKI ownership, compliance or incident response | [evidence/02_tls13_handshake.txt](https://github.com/a-bonfim-tech/security-plus-crypto-lab/blob/main/evidence/02_tls13_handshake.txt) / [REPRODUCE.md](https://github.com/a-bonfim-tech/security-plus-crypto-lab/blob/main/REPRODUCE.md) | Which protocol negotiated; what proves certificate trust; what cipher proves; what is missing; how reproduce safely |

## Categories and gaps

- **SOC Core:** the dedicated [soc-analyst-lab](https://github.com/a-bonfim-tech/soc-analyst-lab) is public and is the primary SOC review path; the homelab remains supporting network/detection evidence.
- **Detection Engineering / SIEM:** public evidence includes homelab Suricata/Wazuh validation, Sigma rules, retained Azure Data Explorer/Kusto KQL-runtime results and controlled-lab Microsoft Sentinel KQL runtime in `soc-analyst-lab`; no continuously operating production SOC pipeline, production Microsoft Sentinel administration or production Sigma deployment is claimed.
- **DFIR / Windows:** public `soc-analyst-lab` evidence includes sanitized derived artifacts from real Windows endpoint EventRecord XML, including Windows Security, Sysmon and PowerShell telemetry used for multi-source investigation and timeline reconstruction. This is controlled-lab endpoint evidence, not a production forensic acquisition.
- **Network Security:** homelab detection/PF, guided TShark, local TLS. Packet analysis, detection and enforcement are separate.

## Recruiter-facing scope

The public portfolio is intentionally concentrated on SOC investigation, network detection, Linux evidence collection, packet analysis and TLS interpretation.

Advanced AI, governance and software-engineering projects are maintained separately and are not part of the primary SOC Analyst / Tier 1 recruiter path.


[Publication gate](PRIVATE_REPOSITORY_PUBLICATION_GATE.md) · [CV evidence map](SOC_PORTFOLIO_TO_CV_MAP.md)
