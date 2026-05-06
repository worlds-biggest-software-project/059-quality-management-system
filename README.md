# Quality Management System (QMS)

> Part of the [worlds-biggest-software-project](https://github.com/worlds-biggest-software-project) initiative.
>
> An AI-native open-source QMS for ISO compliance, non-conformance tracking, and CAPA management.

This project is a quality management system designed for regulated manufacturers, medical device companies, and life sciences organisations that need controlled documents, CAPA workflows, audit readiness, and training records. It targets the gap between expensive commercial eQMS platforms (Veeva Vault, MasterControl, ETQ Reliance) and the limited open-source alternatives (qmsWrapper, ProcessMaker, Senaite) that lack a modern UX, complete regulatory data model, and AI capabilities.

---

## Why Quality Management System (QMS)?

- **No open-source QMS combines a modern UX, a proper regulatory data model, 21 CFR Part 11 compliance, and an AI layer.** ProcessMaker provides workflow mechanics with no QMS data model; qmsWrapper has the model but no AI and a small community; Senaite is a LIMS rather than a full QMS.
- **The commercial entry point is $22K–$25K/yr** (Greenlight Guru, Qualio), which prices out medical device and pharma startups that nonetheless need a QMS for regulatory submission and investor due diligence.
- **Enterprise eQMS costs scale to $50K–$200K+/yr** (ETQ Reliance, Intelex, MasterControl) with implementation timelines of 3–6 months and dated UIs.
- **Vendor lock-in is severe in life sciences:** Veeva Vault QMS only delivers full value inside the Veeva ecosystem (Vault RIM, CTMS, EDC), leaving non-pharma adopters paying for unused integration.
- **AI capabilities in incumbent tools are nascent.** MasterControl's predictive and generative AI features are limited; Octave Reliance's AI is newer than its core QMS; open-source options have none. ISO 9001:2026 (expected September 2026) is anticipated to address AI integration — an AI-native OSS QMS built now would be positioned ahead of the standard update.

---

## Key Features

### Controlled Document Management

- Create, collaboratively author, multi-level review/approve, eSign, publish, distribute, and obsolete documents with full audit trail and version history
- Mandatory read/acknowledge for impacted personnel on document revisions
- Electronic signature meeting 21 CFR Part 11 and EU Annex 11 requirements
- Role-based access control configurable per document type, workflow step, and module

### CAPA, Non-Conformance & Deviation Workflow

- CAPA lifecycle: initiation, investigation, root cause analysis, action planning, implementation tracking, effectiveness check, and closure
- Non-conformance / deviation recording with disposition (accept, reject, rework, scrap) and CAPA linkage
- Configurable investigation forms with root cause tools (5 Why, Fishbone)
- KPI dashboards for open CAPAs, cycle time, and overdue actions

### Audit & Training Management

- Audit planning, scheduling, checklist execution, finding recording, and Corrective Action Plan (CAP) tracking
- Training task assignment triggered on document release, completion tracking, and training records linked to document revisions
- Pre-configured templates for ISO 9001, ISO 13485, and IATF 16949

### AI-Assisted Quality Operations

- AI-assisted root cause analysis: correlate new NCRs with recent process changes, supplier lots, equipment events, and similar historical incidents, proposing probable root causes with evidence links
- Natural language audit evidence package generator: query QMS records in plain language (e.g. "all CAPA records closed in the last 12 months with supporting evidence for ISO 9001 Clause 10.2") and compile structured evidence packages
- Predictive CAPA (backlog): ML model on historical production and supplier data predicting defect likelihood before non-conformances occur
- Change control intelligence (backlog): AI identifies documents containing a changed specification and proposes redlines

### Supplier Quality & Vertical Extensions

- Supplier quality portal: issue supplier CAPAs, track supplier corrective action responses, and manage approved supplier list with requalification triggers
- Trend analysis dashboard: defect rate, CAPA cycle time, audit findings by category, and cost of poor quality metrics with configurable alert thresholds
- Design controls module (backlog) with ISO 14971 risk management and bidirectional traceability matrix for medical device manufacturers
- SPC (Statistical Process Control) integration (backlog): ingest production measurement data and trigger NCRs on process capability violations
- Post-market surveillance (backlog): complaint intake, MDR/PSUR workflow, and signal detection for regulated medical device and pharmaceutical organisations

---

## AI-Native Advantage

Current QMS tools are reactive — they manage CAPAs after a non-conformance occurs. An AI layer trained on historical production data, supplier records, equipment maintenance, and environmental factors enables a shift to proactive risk elimination: predicting defect likelihood, automatically proposing root causes with cited evidence, and compressing CAPA cycle time from weeks to hours. AI also addresses two notoriously manual pain points in regulated environments: assembling audit evidence packages across hundreds of records, and identifying every document impacted by a specification change for redline and re-approval. These capabilities are largely absent from incumbent open-source QMS tools and only emerging in the most expensive commercial platforms.

---

## Tech Stack & Deployment

The project targets self-hosted and cloud deployment, with validation evidence sufficient for 21 CFR Part 11 and EU Annex 11 regulated use. Industry standards in scope include ISO 9001:2015, ISO 13485:2016, ISO 14971:2019, IATF 16949:2016, AS9100 Rev D, FDA 21 CFR Part 11, FDA 21 CFR Part 820 (QSR), EU MDR (2017/745), GMP (FDA, EMA, WHO), and VDA 6.3. Integration is expected via REST API, SSO via SAML 2.0, and connectors to ERP (SAP, Oracle, Microsoft Dynamics) and LIMS systems — matching the integration footprint of incumbent platforms. A from-scratch implementation under a permissive licence avoids the GPLv3 (qmsWrapper) and AGPLv3 (ProcessMaker) copyleft entanglement that would otherwise affect a derivative product.

---

## Market Context

The global quality management software market is valued at approximately $12.26B–$15.9B in 2026, with a CAGR of 11.5% projected through 2033 to reach $28.82B (Grand View Research, 2026; Polaris Market Research, 2026). The CAPA segment alone accounted for over 20% of global market share in 2022. Primary buyers are Quality Directors, Regulatory Affairs Managers, Operations Managers in manufacturing, CTOs evaluating system validation, and CEOs of medical device and pharma companies managing regulatory and recall risk. Pricing ranges from $3K–$12K/yr at the SMB tier (QT9 QMS, SimplerQMS), $10K–$40K/yr mid-market (Qualio, Greenlight Guru, isoTracker), and $25K–$200K+/yr enterprise (Veeva Vault QMS, MasterControl, ETQ Reliance, Intelex).

---

## Project Status

> This project is in the **research and specification phase**.  
> Contributions, feedback, and domain expertise are welcome.

---

## Contributing

We welcome contributions from developers, domain experts, and potential users.
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Important:** All contributions must be your own original work or clearly attributed
open-source material with a compatible licence. Copyright infringement and licence
violations will not be tolerated and will result in immediate removal of the offending
contribution. If you are unsure whether a piece of code, text, or other material is
safe to contribute, open an issue and ask before submitting.

---

## Licence

Licence to be determined. Source files note that an AI-native OSS QMS built from scratch under MIT or Apache 2.0 would avoid the GPLv3 / AGPLv3 copyleft entanglement of existing open-source QMS code. See [discussion](#) for context.
