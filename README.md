# Allocator Bookkeeping Repository for OpenLedger Pathway

## Allocator JSON Link
[OpenLedger Pathway JSON](https://github.com/filecoin-project/Allocator-Registry/tree/main/Allocators/OpenLedger_Pathway.json)

## Client Diligence

OpenLedger Pathway employs a rigorous, transparent client diligence process to ensure trust and prevent abuse:

- **KYC/KYB Verification**:  
  Clients submit identification or business registration documents via Jumio/Veriff. For requests over 500 TiB, video calls are conducted for additional identity confirmation. Cross-checks with public records prevent Sybil attacks. All verification events are anonymized and logged on GitHub for Governance Team audits.
- **Ownership Validation**:  
  Enterprise clients must provide legal documents (e.g., licenses, contracts) to prove data ownership.  
- **Evidence and Auditability**:  
  All client diligence records, including anonymized logs and supporting documentation, are published or summarized on GitHub, ensuring transparency and auditability.

## Description of Data Diligence

To ensure all datasets meet Fil+ and legal requirements, OpenLedger Pathway conducts the following:

- **Legal Compliance**:  
  Datasets are verified for compliance with local/regional laws via legal consultation. Clients provide compliance declarations and legal ownership proofs, which are logged on GitHub.
- **Data Ownership Verification**:  
  Clients submit source documents (e.g., research papers, repository links) or enterprise contracts. Ownership is cross-checked using public records or third-party audits (e.g., Qichacha), and summarized on GitHub.
- **Random Data Sampling**:  
  10% of each dataset is sampled using the CID Checker Bot to verify that the content matches client claims and is publicly retrievable. Sampling results are published on GitHub.
- **Data Quality and Deal Confirmation**:  
  Bi-monthly retrieval tests by CID Checker Bot ensure 95% retrievability across 4–5 replicas in 3–4 regions. Deal data is tracked on DataCapStats.io, with logs available on GitHub for review.

## Short Description of Pathway for Clients

OpenLedger Pathway provides efficient, fair allocation of up to 1 PiB of DataCap for open, public datasets such as research or archives. Our rigorous KYC, regular data sampling, and transparent audit logs on GitHub guarantee high-quality, retrievable storage on Filecoin, tailored to diverse client needs.

## Contact Info

- **Slack:** @U02A9HJ2JBV (Filecoin Slack)  
- **Email:** zhangxin@ruilanit.cn  
- **GitHub:** [OpenLedger Pathway Repository](https://github.com/OpenLedger-Pathway)

## Detailed Allocator Policies, Procedures, and Requirements

- **Policies:**  
  Outlined in `/policies/client_diligence_policy.md` and `/policies/data_diligence_policy.md` on GitHub, covering KYC/KYB, data sampling, rate limits, and compliance.
- **Procedures:**  
  - Clients apply via FIDL Allocator Directory or GitHub issue template.  
  - KYC/KYB via Jumio/Veriff, with video calls for >500 TiB requests.  
  - 10% data sampling and bi-monthly retrieval tests using CID Checker Bot.  
  - Tranche-based allocation: 50 TiB initial, up to 1 PiB after verification.
- **Requirements:**  
  Datasets must be public, retrievable, and stored with 4–5 replicas across 3–4 regions. Clients must submit ownership proof and compliance declarations.

## Risk Mitigation Strategies

- **Operational Security:**  
  Multi-signature wallets with Ledger hardware for DataCap allocation, restricted to verified team members.
- **User Agreements:**  
  Clients sign agreements confirming data ownership and compliance, logged on GitHub.
- **Alerts:**  
  DataCapStats.io monitors for duplicate wallets; automated alerts flag suspicious activity.
- **Throttling:**  
  Cap at 2 PiB/month and 1 PiB/client, with a 30-day cooling-off period between tranches.
- **Blacklisting:**  
  Non-compliant clients (e.g., fraudulent data) are suspended, with records logged on GitHub.

## Dispute Resolutions

- **Internal Disputes:**  
  Resolved within 48 hours via email/Slack, logged on GitHub with hashed client ID.
- **External Disputes:**  
  Resolved within 5 days, documented publicly on GitHub. Non-compliant parties may face DataCap suspension.
- **Process:**  
  Clients submit disputes via GitHub issues. The team reviews using KYC/KYB, data sampling, and DataCapStats.io data. All resolutions are transparent for Governance Team review.

## Compliance Audit Check

- **Client Compliance:**  
  KYC/KYB, ownership, and legal compliance verified via Jumio/Veriff, legal consultations, and document audits; results logged on GitHub.
- **SP Compliance:**  
  Confirm 4–5 replicas across 3–4 regions through DataCapStats.io and CID Checker Bot. Non-compliant SPs are excluded.
- **Audits:**  
  Governance Team receives anonymized KYC/KYB reports, sampling and retrieval test logs, deal verification data, and dispute resolution records via GitHub.
- **Ongoing Monitoring:**  
  Monthly audits of 5% of clients, with results published on FIDL Dashboards and GitHub.
