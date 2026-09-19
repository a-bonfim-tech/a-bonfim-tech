# Private Repository Publication Gate

This document defines the minimum review required before any private repository is made public or converted into a recruiter-facing portfolio edition.

## Default decision

Do **not** change a canonical private repository to public by default.

For internship, employer, client, product, governance, AI, cloud or security projects, the preferred model is:

1. keep the canonical repository private;
2. create a separate sanitized public portfolio edition;
3. publish only after the checks below pass;
4. preserve provenance and explicitly identify synthetic, redacted or reconstructed evidence.

## Immediate publication blockers

A repository must remain private when it contains or may contain:

- credentials, API keys, tokens, certificates, private keys or connection strings;
- customer, employee, patient, user or other personal data;
- internal company names, tenant IDs, subscription IDs, resource IDs, hostnames or IP addresses;
- screenshots from private consoles, tickets, Slack, Linear, email, dashboards or monitoring tools;
- employer-owned source code, architecture, logs, contracts, security controls or audit evidence;
- vulnerability details affecting an unresolved or reachable system;
- infrastructure state, secrets history, sensitive Git history or deleted files that remain recoverable;
- licensing restrictions, copied course material or third-party assets without publication rights;
- proprietary prompts, datasets, models, product strategy or commercial documentation;
- statements that imply production readiness, certification, compliance or seniority without evidence.

## Security review

Before publication, verify:

- repository history, not only the current working tree;
- branches and tags;
- Git LFS objects;
- issues, pull requests, discussions and Actions logs;
- workflow files and environment references;
- release assets and downloadable artifacts;
- dependency manifests and lockfiles;
- screenshots, diagrams, PDFs and exported reports;
- `.env`, configuration, backup and temporary files;
- commit authorship, email addresses and embedded metadata.

Recommended checks include secret scanning, dependency review, static analysis, license review and a manual evidence inspection.

## Recruiter-value gate

A public edition should not be published merely because it is safe. It should also demonstrate:

1. a clear security problem and authorized scope;
2. the author's individual contribution;
3. tools, methods and assumptions;
4. reproducible execution or validation steps;
5. sanitized technical evidence;
6. findings, risk interpretation and limitations;
7. remediation, decision or conclusion;
8. a professional README and repository structure;
9. clear separation between original work and third-party material;
10. no inflated claims beyond the evidence supplied.

## Public-edition pattern

A sanitized public repository should normally contain:

```text
README.md
SECURITY.md
LICENSE
NOTICE.md                 # when third-party material exists
docs/
  scope.md
  methodology.md
  architecture.md
  findings.md
  limitations.md
  evidence-register.md
evidence/
  synthetic-or-redacted/
src-or-config/            # only when safe and relevant
tests-or-validation/
.github/workflows/         # only stable, non-sensitive workflows
```

## Panos.AI-derived portfolio rule

No Panos.AI repository, document, screenshot, finding or evidence should be published directly unless Panos.AI has explicitly authorized publication.

A safe public case study may demonstrate the competencies developed during the internship using:

- a synthetic cloud environment;
- reconstructed examples;
- neutral resource names;
- redacted or newly generated evidence;
- general control categories such as TLS, HSTS, encryption at rest, IAM, logging, backup and recovery;
- explicit statements that no employer systems, identifiers, configurations or confidential evidence are included.

## Decision outcomes

Each repository review must end with one of four decisions:

- **Keep Private** — publication risk or ownership restrictions remain.
- **Sanitize and Reassess** — valuable project, but blockers must be removed.
- **Create Separate Public Edition** — preferred for canonical private projects.
- **Approved for Public Release** — security, legal, evidence and recruiter-value gates passed.

The approval decision should be documented in a review record before changing visibility.
