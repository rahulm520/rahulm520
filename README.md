# Rahul Rao M
### Cybersecurity & SIEM Engineer | Detection Engineering, Cloud Security & Incident Response
**Bengaluru, India** • [LinkedIn](https://www.linkedin.com/in/Rahul-Rao-M/) • [Credly (Security+)](https://www.credly.com/badges/1c34ddab-7556-460c-b3b5-5f943421853b/linked_in_profile) • `rahulraom2002@gmail.com`

---

### 🛡️ About Me
Production-focused **Cybersecurity & SIEM Engineer** with end-to-end ownership of centralized Wazuh and OpenSearch security infrastructure monitoring **550+ active endpoints across a 680-asset enterprise fleet**. I specialize in custom detection engineering, high-volume alert noise suppression, cross-platform endpoint hardening, and auditable cloud log integrity.

- 🔭 **SIEM & Detection Engineering:** Administering centralized Wazuh 4.14.9 / OpenSearch 2.19 clusters on Ubuntu 24.04; writing custom XML decoders and suppression logic that eliminated **50,000+ daily false alerts** and reclaimed **155 GB** of storage.
- ☁️ **Cloud Log Integrity & Multi-Cloud Telemetry:** Ingesting telemetry across 17 AWS accounts (CloudTrail, CloudWatch), Microsoft 365, Active Directory, and perimeter firewalls; built a **3-tier AWS S3 log archiving pipeline** with SHA-256 pre-purge verification (**116/116 passing unit tests**).
- ⚙️ **Endpoint Hardening & Multi-OS Automation:** Enforcing CIS Benchmark Level 1/2 baselines, AppLocker whitelisting, and client enclave isolation via Active Directory GPOs alongside idempotent **Ansible, PowerShell, and Bash** onboarding across Windows, macOS, and Ubuntu.
- 🔍 **Incident Response & Vulnerability Management:** Leading P1/P2 root-cause investigations (infostealer malware triage, Active Directory exposure remediation via AWS Client VPN/WireGuard) and executing OpenVAS vulnerability audits across **10,900+ IP endpoints**.
- 📜 **Compliance & Certifications:** **CompTIA Security+ (ce)** • **EC-Council DFE** • **ISO/IEC 27001:2022** & **ISO/IEC 42001:2023 (AIMS)**.

---

### 🛠️ Technical Tooling & Stack

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **SIEM & Log Management** | Wazuh 4.14.9 (Manager, Indexer, Dashboard), OpenSearch 2.19, Elastic Stack (ELK), Filebeat, Logstash, Syslog |
| **Detection Engineering** | Custom XML Decoders & Rules, Alert Noise Suppression, MITRE ATT&CK Mapping, Windows EventChannels |
| **Cloud & Identity Security** | AWS (CloudTrail, CloudWatch, S3 Lifecycle, Client VPN, IAM), Microsoft Entra ID, M365 Security, Active Directory |
| **Incident Response & Vuln Mgmt** | L1/L2 Alert Triage, Malware Forensics, Root Cause Analysis (RCA), Active Response (`netsh`, `iptables`), OpenVAS |
| **Automation & Hardening** | Python (`pytest`, SQLite, REST APIs), PowerShell, Bash, Ansible, CIS Benchmarks (Level 1/2), AppLocker |
| **Governance & Standards** | ISO/IEC 27001:2022 (Annex A Controls), ISO/IEC 42001:2023 (AIMS), SOC Runbooks & SOPs |

---

### 🚀 Featured Engineering & Research

#### 1. [Enterprise SIEM Detection & Log Archiving Engineering](https://github.com/rahulm520/siem-detection-and-archiving-toolkit) *(Sanitized Production Patterns)*
- **Alert Noise Suppression:** Custom Wazuh XML decoders and Level 0 suppression rules eliminating high-volume Windows Event 4673/4957 loops and physical access controller heartbeats without masking high-severity threats.
- **Cryptographic Log Archiving:** Tiered AWS S3 log lifecycle automation with pre-deletion byte-size and SHA-256 integrity checks backed by automated `pytest` suites.
- **Cross-Platform Onboarding:** Idempotent Linux/macOS/Windows bootstrap patterns for automated endpoint registration and hardening.

#### 2. [Multi-Layer Cloud DDoS Detection & Prevention Framework](https://github.com/rahulm520/ddos-multilayer-security-oncloud)
*Published Technical Research (2024)*  
- Modeled multilayer mitigation frameworks incorporating cloud edge WAF controls, anomaly detection thresholds, and centralized log collection to accelerate cloud incident response.

#### 3. Enterprise SIEM Detection Engineering Lab
- Built a multi-node containerized SIEM lab using Elasticsearch, Logstash, Filebeat, Kibana, and Docker on Linux.
- Authored custom Logstash parsers and MITRE ATT&CK-mapped detection rules for Linux privilege escalation (`sudo`) and anomalous authentication activity.

#### 4. [GraphQL & Web API Security Assessment Framework](https://github.com/rahulm520/web-api-pentest)
- Black-box and gray-box API assessment suite evaluating GraphQL authorization models for Broken Object Level Authorization (BOLA), user enumeration, and verbose error leaks aligned with OWASP API Security Top 10.

---

### 📈 Target Roles
Open to **L2 SOC Analyst**, **SIEM / Detection Engineer**, and **Security Infrastructure Engineer** roles in Bengaluru focused on detection engineering, incident response, cloud security, and automated defense.
