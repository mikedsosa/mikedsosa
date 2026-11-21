# Hi, I'm Mike

I've been building things since I was 12 - first houses, now security teams and the systems they protect. Nearly seven years in the Army, and today as a cyber officer: I've led teams across cyber defense, threat intelligence, and security engineering, and I teach other professionals how adversaries think. On my own time I ship AWS and Azure/Entra labs, IR runbooks, and adversarial ML work, and I write it up so others can reuse it.

More of the story: [mikedsosa.com/about](https://mikedsosa.com/about)

## Focus areas

- **AWS security as code:** an offline organization-level Security Specialty lab (guardrails, logging, detection, network and compute controls) and a single-account audit baseline. Nothing in either lab has been applied.
- **Entra as code:** Conditional Access, PIM, and identity hardening in Terraform, report-only first
- **IR runbooks and detection testing:** order-of-operations playbooks for compromised Entra accounts (KQL, tabletops), plus an offline harness that replays synthetic Entra and Microsoft 365 telemetry against KQL and Sigma rules
- **Adversarial ML labs:** phishing detectors I build, then attack, plus a prompt-injection lab for AI agents

## Certifications

| Certification | Issuer | Status |
| --- | --- | --- |
| CISSP | ISC2 | Held |
| PMP | PMI | Held |
| [AWS Certified Solutions Architect - Professional](https://www.credly.com/badges/541fa9a0-6c18-43d2-93fd-51b28b98c167) | AWS | Earned |
| [AWS Certified Security - Specialty](https://www.credly.com/badges/e824c028-889a-4458-be99-b82c908444d6) | AWS | Earned |
| [Microsoft Certified: Cybersecurity Architect Expert](https://learn.microsoft.com/en-us/users/mikesosa-5273/transcript/vpz2t1m2lzm3yj7) | Microsoft | Earned |
| [Microsoft Certified: Cloud and AI Security Engineer Associate](https://learn.microsoft.com/en-us/users/mikesosa-5273/transcript/vpz2t1m2lzm3yj7) | Microsoft | Earned |
| CCSP: Certified Cloud Security Professional | ISC2 | In progress |

## Featured projects

### [AWS Security Specialty lab](https://github.com/mikedsosa/aws-security-specialty-lab)
**Offline SCS-C03 lab.** Organization guardrails, an organization trail, KMS, GuardDuty and Security Hub, permission boundaries, EventBridge-to-Lambda remediation, a study VPC with Session Manager and IMDSv2, fifteen exercises, and an IR runbook. Never applied.

### [AWS audit baseline](https://github.com/mikedsosa/aws-audit-baseline)
**Single-account audit baseline in Terraform.** CloudTrail, KMS, S3, and an auditor role, plus a Python plan-evidence checker. Offline-validated, never applied.

### [Azure Entra ID Identity Hardening](https://github.com/mikedsosa/azure-entra-identity-hardening)
**SC-500 lab in Terraform.** Report-only Conditional Access baseline, break-glass design, PIM, least-privilege RBAC, and sign-in log export with KQL checks. Write-up: [Report-Only First](https://mikedsosa.com/blog/report-only-first/).

### [Entra Account Compromise IR](https://github.com/mikedsosa/entra-account-compromise-ir)
**Incident response runbook.** Containment order for a compromised Entra ID account, Fabrikam tabletop, and KQL detections. Write-up: [Order of Operations](https://mikedsosa.com/blog/order-of-operations/).

### [Detection Test Harness](https://github.com/mikedsosa/detection-test-harness)
**Offline detection testing.** Replays synthetic Entra ID and Microsoft 365 telemetry against KQL and Sigma rules and reports a pass/fail table per rule. Synthetic data only; a PASS is not a live-tenant validation.

### [Prompt Injection Lab](https://github.com/mikedsosa/prompt-injection-lab)
**Local open-weight LLM01 lab.** OWASP / MITRE ATLAS tagged cases, canary scoring, and layered defenses on Ollama.

## Contact

- Site: [mikedsosa.com](https://mikedsosa.com)
- LinkedIn: [linkedin.com/in/mikedsosa](https://www.linkedin.com/in/mikedsosa)
