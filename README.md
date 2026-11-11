# Awesome-Cloud-Native-Data-Resiliency-Platform

# Top Cloud-Native Data Resiliency Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cyber Resilience, Immutable Backup & Multi-Cloud Data Protection*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud-Native Data Resiliency**. These platforms provide the control plane for protecting data across SaaS applications, cloud workloads, and on-premises infrastructure—covering immutable backups, ransomware detection, orchestrated recovery, and compliance reporting from a single cloud-native console.

**Examples** include Druva Cloud Platform, Veeam Data Platform, Commvault Cloud, Cohesity Cloud Services, Rubrik Security Cloud, Acronis Cyber Cloud, Datto Cloud, HYCU R-Cloud, Clumio, and Rewind (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted backup engines, cloud DR orchestration, and Kubernetes data protection—ideal for SREs, platform engineers, and organizations seeking transparent, vendor-neutral resilience without per-TB cloud billing surprises.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Druva Cloud Platform](https://www.druva.com/)** | Cloud-native data resiliency platform with agentless backup, global deduplication, and automated cyber recovery. Covers endpoints, SaaS apps, and cloud workloads. Developer Sandbox available for integration testing . | ~$8.00/month starting (per third-party listing); enterprise quote-based on deduplicated TB . | **Developer Sandbox**: free for 1 year, limited storage, strictly for testing integrations . No general free tier; trial via sales. |
| **[Veeam Data Platform](https://www.veeam.com/)** | Enterprise data protection with backup, replication, and recovery across virtual, physical, and cloud workloads. Foundation tier covers core backup; Advanced adds immutability and malware detection. | ~$155–$227.50 per workload/year (VUL licensing, depending on edition) . | **Community Edition**: free forever, full backup/replication for up to 10 workloads, no time limit, no technical support . |
| **[Commvault Cloud](https://www.commvault.com/)** | Unified data protection with immutable backups, air-gapped copies, and cleanroom recovery. Command Center provides centralized policy and license management. | Quote-only (enterprise contract). | **30-day free trial**: protect multiple environments simultaneously, no credit card required, no strings attached . |
| **[Cohesity Cloud Services](https://www.cohesity.com/)** | Fully managed multicloud Backup-as-a-Service (BaaS) hosted in AWS, Azure, and GCP. Eliminates CapEx with subscription pricing; includes unlimited restores and no egress spikes. | Quote-only (no published prices; subscription terms of 1, 3, or 5 years via sales) . | **Free Trial**: 5 FE TiB (front-end capacity) for evaluation; no self-serve signup . |
| **[Rubrik Security Cloud](https://www.rubrik.com/)** | Cyber resilience platform with immutable backups, anomaly detection, and orchestrated recovery. Editions: Foundation (basic), Business (threat detection), Enterprise (full suite), Rubrik Go (3-year evergreen) . | Quote-only (enterprise contract; no public price list) . | **No free plan available**; trial via sales . |
| **[Acronis Cyber Cloud](https://www.acronis.com/)** | Cyber protection platform combining backup, disaster recovery, and AI-based ransomware detection. Service providers choose per-workload or per-GB pricing. | Per-workload or per-GB (quote-only via service providers). | **Promotional free periods** available through some regional distributors (e.g., 4-month free campaign for eligible new customers in Japan) . No permanent free tier. |
| **[Datto Cloud](https://www.datto.com/)** | Business continuity and disaster recovery for MSPs, including SIRIS appliances with local and cloud virtualization, screenshot verification, and ransomware detection. | SIRIS 5 starts at **~$995** (appliance; quote via partner) . | **No free tier**; quote-only pricing via MSP partners . |
| **[HYCU R-Cloud](https://www.hycu.com/)** | Multi-cloud data protection platform protecting 100+ workloads across AWS, Azure, GCP, and SaaS apps. Agentless, WORM-backed, with ransomware readiness architecture. | ~$1.20/year starting (per third-party listing) . | Free trial available (per third-party listing); no permanent free tier . |
| **[Clumio](https://www.clumio.com/)** | Fully managed, air-gapped cloud backup for AWS and Google Cloud. API-first architecture with Terraform provider; restore of 100M S3 objects in ~3 hours. | ~$0.025/GB (usage-based) starting per third-party analysis . | **Free trial** available upon request; no permanent free tier . |
| **[Rewind](https://rewind.com/)** | SaaS data backup for cloud applications (Jira, GitHub, Shopify, QuickBooks, etc.) with encrypted storage, granular restore, and compliance features. | Standard: **$4.00/user/month**; Advanced: **$5.20/user/month** . | **Free trial** on every plan; run first backup and test restore before paying . |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Restic](https://github.com/restic/restic)** | [![Stars](https://img.shields.io/github/stars/restic/restic?style=social&color=white)](https://github.com/restic/restic/stargazers) | Fast, secure, deduplicated backup tool with encryption. Supports S3, GCS, Azure Blob, SFTP, and local storage. CLI-first, widely used as a self-hosted BaaS foundation. |
| **[BorgBackup](https://github.com/borgbackup/borg)** | [![Stars](https://img.shields.io/github/stars/borgbackup/borg?style=social&color=white)](https://github.com/borgbackup/borg/stargazers) | Deduplicating, compressing, authenticated backup tool with encryption. Mature and battle-tested; supports local, SSH, and cloud storage backends. |
| **[Velero](https://github.com/vmware-tanzu/velero)** | [![Stars](https://img.shields.io/github/stars/vmware-tanzu/velero?style=social&color=white)](https://github.com/vmware-tanzu/velero/stargazers) | Kubernetes backup and restore tool for cluster resources and persistent volumes. Supports AWS, Azure, GCP, and on-premises storage; includes schedules and pre/post hooks. |
| **[cloud-dr-orchestrator](https://github.com/Kobeep/cloud-dr-orchestrator)** | [![Stars](https://img.shields.io/github/stars/Kobeep/cloud-dr-orchestrator?style=social&color=white)](https://github.com/Kobeep/cloud-dr-orchestrator/stargazers) | Multi-cloud disaster recovery orchestrator with automated backup scheduling, encryption, and restore workflows targeting Oracle Cloud Free Tier. Includes systemd/cron automation and Grafana monitoring hooks . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[ReaR (Relax-and-Recover)](https://github.com/rear/rear)** | [![Stars](https://img.shields.io/github/stars/rear/rear?style=social&color=white)](https://github.com/rear/rear/stargazers) | Linux disaster recovery framework producing bootable rescue images; supports Bacula, Borg, Duplicity, rsync, and many enterprise backup backends. |
| **[Kopia](https://github.com/kopia/kopia)** | [![Stars](https://img.shields.io/github/stars/kopia/kopia?style=social&color=white)](https://github.com/kopia/kopia/stargazers) | Fast, secure backup/restore tool with deduplication, encryption, and support for S3, Azure, GCS, and local storage. Includes server mode and web UI. |
| **[Duplicati](https://github.com/duplicati/duplicati)** | [![Stars](https://img.shields.io/github/stars/duplicati/duplicati?style=social&color=white)](https://github.com/duplicati/duplicati/stargazers) | Open-source backup software with web-based management, encryption, and support for S3, SFTP, WebDAV, and cloud storage destinations. |

**Frameworks for building custom systems**: Combine **Restic** or **BorgBackup** for encrypted, deduplicated backup storage, **Velero** for Kubernetes workload protection, **cloud-dr-orchestrator** for multi-cloud DR automation, and **Kopia** for cross-platform backup with a web UI—creating a fully self-hosted data resiliency stack on commodity infrastructure or cloud object storage.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data resiliency platforms handle sensitive production data; enforce encryption at rest and in transit, least-privilege access, and regular restore testing.
- Self-hosted open-source solutions require capacity planning, off-site replication, and immutable storage strategies to protect against ransomware; always validate RTO/RPO against business requirements. Enterprise pricing (Cohesity, Rubrik, Commvault) is universally quote-only and varies significantly by volume—engage sales for accurate budgeting.

---

**Made for SREs, platform engineers, backup administrators, and organizations building cyber-resilient infrastructure.**  
Let's make cloud-native data resiliency more open, automated, and provable.
