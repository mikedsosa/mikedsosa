# Hi, I'm Mike

Security professional with a background in military and government security work, now focused on cloud security engineering, architecture, and security leadership. I'm interested in building secure systems and helping teams manage risk across Azure and AWS.

Open to security engineering, security architecture, GRC, technical program management, and security leadership roles.

## Focus areas

- **Cloud security architecture:** designing secure Azure and AWS environments
- **Identity and access management:** least privilege, conditional access, privileged access
- **Security operations and posture:** monitoring, detection, and continuous compliance
- **Governance, risk, and compliance:** mapping controls to frameworks and making risk visible
- **Applied cryptography:** digital signatures, key management, data protection

## Certifications in progress

| Certification | Issuer | Status |
| --- | --- | --- |
| SC-100: Cybersecurity Architect Expert | Microsoft | In progress |
| SC-500: Cloud and AI Security Engineer Associate | Microsoft | In progress |
| AWS Certified Solutions Architect – Professional | AWS | Planned |
| AWS Certified Security – Specialty | AWS | Planned |
| CCSP: Certified Cloud Security Professional | ISC2 | Planned |

## Currently building

Hands-on Azure security labs aligned to SC-100 and SC-500, documented so others can reproduce them:

- Identity hardening with Microsoft Entra ID (conditional access, privileged identity management)
- Network security and segmentation for Azure workloads
- Monitoring and threat detection with Microsoft Defender for Cloud and Microsoft Sentinel
- Key and secret management with Azure Key Vault

AWS labs will follow, aligned to AWS Security Specialty and Solutions Architect Professional.

## Featured projects

### [Phishing Detector Adversarial Robustness](https://github.com/mikedsosa/phishing-detector-adversarial-robustness)
**Adversarial ML research in Python.** Gradient-boosting and character-level CNN phishing URL detectors, tested on two public datasets (PhiUSIIL and the time-split PhreshPhish). Cheap, realistic URL edits evade 62–63% of detections on PhiUSIIL and 83–96% on PhreshPhish. Adversarial training cuts that to 18–35%, but edits it never saw and a stronger beam search still get through 35–98% of the time. Includes a threat model, a short paper, a model card and a local single-URL demo.

### [Azure Entra ID Identity Hardening](https://github.com/mikedsosa/azure-entra-identity-hardening)
**SC-500 lab in Terraform.** Report-only Conditional Access baseline, break-glass design, PIM, least-privilege RBAC and sign-in log export, with a STRIDE threat model, runbook and KQL detections.

### [Azure Zero Trust Reference Architecture](https://github.com/mikedsosa/azure-zero-trust-reference-architecture)
**SC-100 work sample.** Zero Trust design for a mid-size org on Azure and Microsoft 365, with architecture decision records, MCRA and MCSB mapping, and a phased rollout roadmap with risks and decision points.

### [CloudCoin](https://github.com/mikedsosa/CloudCoin)
**Digital signatures demo in C#, security-reviewed and fixed.** ECDSA-signed transactions in a hash-linked chain. I reviewed my own old code, fixed the tampering and validation flaws I found, and added tests and CI.

## Contact

- LinkedIn: [linkedin.com/in/mikedsosa](https://www.linkedin.com/in/mikedsosa)
