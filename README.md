# Awesome-Connected-App-Security

## Top Connected App Security Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on OAuth Governance, SaaS Supply Chain Risk & Zero Trust Access*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Connected App Security**. These tools help security teams discover, monitor, and control third-party applications connected to corporate SaaS environments — managing OAuth tokens, restricting risky flows, and enforcing least-privilege access to prevent supply chain attacks.



**Examples** include Salesforce Connected App Management, Cloudflare Zero Trust, Zscaler Private Access, Palo Alto Prisma Access, Netskope, Microsoft Defender for Cloud Apps, AppOmni, Wing Security, Adaptive Shield, and Spin.AI (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom OAuth auditing, and open zero-trust access — ideal for security teams seeking transparent, vendor-independent connected app governance.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Connected App Management](https://help.salesforce.com/)**  

  Native Salesforce controls for OAuth policies, IP allowlisting, refresh token rotation, and JWT-based access tokens. Recommended settings include disabling device flow, removing client credential flow, and enforcing admin-approved user authorization to prevent app sprawl and unauthorized data access .



- **[Cloudflare Zero Trust](https://www.cloudflare.com/zero-trust/)**  

  Identity-aware proxy and secure web gateway providing zero-trust access to internal applications. Features device posture checks, DNS filtering, and browser isolation.



- **[Zscaler Private Access](https://www.zscaler.com/)**  

  Cloud-delivered zero-trust network access (ZTNA) replacing traditional VPNs. Provides per-app access, continuous verification, and inline threat inspection.



- **[Palo Alto Prisma Access](https://www.paloaltonetworks.com/prisma/access)**  

  Cloud-native SASE platform combining ZTNA, CASB, and threat prevention. Provides SaaS application discovery and connected app risk management .



- **[Netskope](https://www.netskope.com/)**  

  CASB and SASE platform with SaaS application discovery, DLP, and threat protection. Tracks sanctioned and unsanctioned app usage including GenAI tools .



- **[Microsoft Defender for Cloud Apps](https://www.microsoft.com/en-us/security/business/cloud-app-security)**  

  CASB providing discovery, control, and threat protection for SaaS applications. Features OAuth app governance and anomaly detection for token abuse.



- **[AppOmni](https://www.appomni.com/)**  

  SaaS security posture management (SSPM) platform. Provides deep visibility into connected apps, OAuth permissions, and misconfigurations across Salesforce, Microsoft 365, and other SaaS platforms.



- **[Wing Security](https://www.wing.security/)**  

  SSPM focused on SaaS-to-SaaS integrations and OAuth app risk. Discovers connected apps, assesses permission scopes, and provides remediation workflows.



- **[Adaptive Shield](https://www.adaptive-shield.com/)**  

  SSPM platform with connected app discovery, OAuth token analysis, and GenAI application governance.



- **[Spin.AI](https://spin.ai/)**  

  SaaS security platform specializing in OAuth app risk assessment, browser extension security, and shadow IT discovery.



## Open-Source GitHub Projects



- **[Pangolin](https://github.com/fosrl/pangolin)**  

  Open-source SASE platform (AGPL-3.0) built on WireGuard providing zero-trust VPN, identity-aware reverse proxy, and privileged access management. Alternative to Cloudflare One, Zscaler, and Prisma Access .



- **[Octelium](https://github.com/octelium/octelium)**  

  Next-generation FOSS zero-trust secure access platform (Apache-2.0). Operates as remote access VPN, ZTNA, API/AI/MCP gateway, and PaaS. Features OpenTelemetry-native auditing, passwordless SSH, and clientless remote sandboxes via Cordium .



- **[ClosedSSPM](https://github.com/PiotrMackowski/ClosedSSPM)**  

  Open-source SaaS Security Posture Management CLI (Go, version v0.4.2). Audits connected app configurations across platforms including Jira. Provides commands for collecting, evaluating, and exposing security findings .



- **[FoxNode ASPM](https://github.com/valinorintelligence/foxnode-aspm)**  

  Open-source Application Security Posture Management platform (license varies). Features 16+ security tool parsers, Jira sync, Slack notifications, RBAC, and CI/CD integration. Includes AI finding triage and compliance mapping to OWASP, SOC 2, and ISO 27001 .



- **[AccuKnox](https://accuknox.com/)**  

  Open-source CNAPP (Apache-2.0 for KubeArmor components). Provides runtime security for cloud, containers, and Kubernetes. Features AI-SPM for GenAI app security, MCP server sandboxing, and ModelArmor for model protection .



- **[ORY](https://github.com/ory)**  

  Open-source identity and authorization services (Apache-2.0). Provides composable IAM solutions including OAuth2 server, Hydra, Kratos, and Oathkeeper for building custom connected app authorization flows .



- **[Falco](https://github.com/falcosecurity/falco)**  

  Cloud-native runtime security tool (Apache-2.0) for detecting anomalous application behavior across hosts, containers, and Kubernetes. CNCF graduated project with 1M+ downloads. Can monitor connected app runtime behavior .



- **[Bitwarden](https://github.com/bitwarden/server)**  

  Open-source password manager (AGPL-3.0) with secrets management capabilities. Provides secure credential storage for connected app secrets and API keys .



### Additional Strong Open-Source Options



- **[OpenCSPM](https://github.com/open-cspm/opencspm)** — Open-source cloud security posture management platform.

- **[Prowler](https://github.com/prowler-cloud/prowler)** — AWS/Azure/GCP security assessment tool with 300+ checks.

- **[Kubescape](https://github.com/kubescape/kubescape)** — Kubernetes security platform from ARMO (Apache-2.0).

- **[Trivy](https://github.com/aquasecurity/trivy)** — Comprehensive security scanner for containers, code, and cloud.

- **[Vault](https://github.com/hashicorp/vault)** — Secrets management platform (BUSL license) for OAuth credentials.

- **[Keycloak](https://github.com/keycloak/keycloak)** — Open-source identity and access management with OAuth2/OIDC support.

- Community **n8n** workflows for OAuth token auditing and Slack alerting.



**Frameworks for building custom systems**: Combine **Pangolin** or **Octelium** for zero-trust access control with **ClosedSSPM** for SaaS posture auditing, **ORY Hydra** for OAuth authorization infrastructure, **Falco** for runtime monitoring, and **Vault** for secrets management — creating a fully self-hosted connected app security stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Connected app security must comply with data protection regulations (GDPR, CCPA, SOC 2, etc.).

- Self-hosted open-source solutions require proper security hardening, OAuth token lifecycle management, and ongoing maintenance.



---



**Made for security engineers, SaaS administrators, identity architects, and developers building transparent connected app governance.**  

Let's make connected app security more open, data-driven, and resilient.
