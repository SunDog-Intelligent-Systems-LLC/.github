# SunDog Intelligent Systems, LLC

**Private On-Premises AI Appliances & Deterministic Agentic Infrastructure for Regulated SMBs**

SunDog Intelligent Systems designs, deploys, and manages local-first AI appliances for law firms, CPA practices, specialty healthcare clinics, and engineering organizations across Charleston and the Southeast. Every deployment executes inside customer-controlled hardware boundaries with zero public cloud data egress.

## Core Commercial Appliances

### 1. Private Knowledge Vault (`private-rag-box`)
An air-gapped document intelligence appliance combining lexical search and dense vector retrieval over internal SOPs, contracts, project archives, and clinical or legal policies.
- **Strict Grounding:** Every factual claim requires inline document-chunk citations; unverified queries return deterministic `INSUFFICIENT_CONTEXT` refusals.
- **Zero Egress:** All ingestion, embedding, and generation run locally on dedicated Apple Silicon unified-memory hardware.

### 2. Back-Office Triage & Ledger Gate (`backoffice-workflow`)
A schema-locked intake and reconciliation engine for accounts payable invoices, subcontractor compliance packets, purchase orders, and client onboarding forms.
- **Deterministic Math & Policy Guards:** Line-item totals, tax calculations, SHA-256 duplicate checks, and approval thresholds are verified in Python rather than delegated to probabilistic prompts.
- **Human-in-the-Loop ERP Staging:** High-value payables and flagged anomalies pause in an auditable approval queue; prompt-injection and payment-diversion payloads are quarantined before ledger export.

## Architectural Security Invariants

- **Loopback & Private-VLAN Isolation:** Inference services bind strictly to local interfaces and fail closed (`HTTP 503`) rather than falling back to external cloud APIs.
- **Hardened Runtime Boundaries:** Services run inside rootless containers with read-only root filesystems, dropped Linux capabilities, and encrypted secret stores.
- **Continuous Managed Verification:** Monthly golden evaluation suites verify citation fidelity, refusal accuracy, backup integrity, and retrieval stability under SLA retainers.

## Inquiries & Architecture Reviews

- **Web:** [sundogits.com](https://sundogits.com)
- **Principal Contact:** [mike@sundogits.com](mailto:mike@sundogits.com)
- **Headquarters:** Charleston, South Carolina
