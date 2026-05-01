# Quality Management System — Feature & Functionality Survey

> Candidate #59 · Researched: 2026-05-01

## Solutions Analysed

| Tool | Type | Licence / Model | URL |
|------|------|-----------------|-----|
| MasterControl | Commercial SaaS | Proprietary; ~$30K–$60K/yr (10 users) | https://www.mastercontrol.com |
| Veeva Vault QMS | Commercial SaaS | Proprietary; from $25K/yr | https://www.veeva.com/products/vault-qms |
| ETQ Reliance (now Octave Reliance) | Commercial SaaS | Proprietary; ~$50K–$200K+/yr | https://www.octave.com |
| Greenlight Guru | Commercial SaaS | Proprietary; ~$22K–$40K/yr | https://www.greenlight.guru |
| Qualio | Commercial SaaS | Proprietary; ~$25K/yr entry | https://www.qualio.com |
| Dot Compliance | Commercial SaaS | Proprietary; mid-market pricing | https://www.dotcompliance.com |
| isoTracker (Ideagen) | Commercial SaaS | Proprietary; from ~$900/mo | https://www.isotracker.com |
| Intelex (EHSQ) | Commercial SaaS | Proprietary; enterprise custom | https://www.intelex.com |
| qmsWrapper | Open Source / Commercial | GPLv3 (Community); proprietary (Commercial) | https://www.qmswrapper.com |
| ProcessMaker | Open Source / Commercial | AGPLv3 (Community); proprietary (Enterprise) | https://www.processmaker.com |

## Feature Analysis by Solution

### MasterControl

**Core features**
- Enterprise eQMS covering document control, training management, CAPA (Corrective and Preventive Action), audit management, supplier quality, and production quality records
- Document control with controlled review and approval workflows, electronic signature capture, version management, and mandatory read/acknowledge for impacted personnel
- Training management LMS with module delivery, competency tracking, training records linked to document revisions, and training effectiveness testing
- CAPA workflow with root cause analysis tools (5 Why, Fishbone), effectiveness check scheduling, and KPI dashboards
- 21 CFR Part 11 validated out-of-box with audit trail, electronic signatures, and access controls meeting FDA requirements

**Differentiating features**
- The most comprehensive training management integration in any QMS: training requirements automatically generated when a document is revised, assigned to affected roles, and tracked to completion before the new revision is considered effective
- Supplier Quality module with approved supplier list management, supplier audit scheduling, supplier CAPA issuance, and requalification triggers
- MasterControl Manufacturing Excellence suite adds production batch record management, deviation tracking, and in-process quality data capture
- Broad life sciences pedigree: pharmaceutical, medical device, biotech, and contract manufacturing verticals

**UX patterns**
- Feature-rich but dated interface; users report high capability at the cost of UX complexity
- Structured workflow forms with configurable fields per CAPA, deviation, or document type
- Dashboard KPIs for open CAPAs, overdue training, and approaching audit dates

**Integration points**
- ERP connectors (SAP, Oracle); LIMS integration; API for custom integration; SSO via SAML 2.0

**Known gaps**
- Expensive for SMBs ($30K–$60K/yr for 10 users); cost scales significantly with user count
- UI is dated; implementation timelines of 3–6 months are common
- AI capabilities are limited; limited predictive or generative AI features compared to newer platforms
- Not suitable for non-life-sciences industries; terminology and templates are heavily pharma/device-oriented

**Licence / IP notes**
- Fully proprietary; private company with ~$400M+ estimated revenue

---

### Veeva Vault QMS

**Core features**
- Cloud QMS built on the Veeva Vault platform, tightly integrated with Vault RIM (regulatory information management), Vault CTMS (clinical trial management), and Vault EDC for a unified life sciences data model
- Quality documents: controlled document creation, collaborative authoring, review, approval, eSignature, and distribution with audit trail
- Quality events: deviation management, CAPA, change control, complaints, and audit management with cross-linking between related events
- Post-market surveillance: complaint tracking, MDR (Medical Device Reporting) submission workflow, and signal detection for pharma vigilance
- Training management integrated with document control; training tasks auto-assigned on document approval

**Differentiating features**
- The dominant QMS in mid-to-large pharma and biotech: the Veeva ecosystem (Vault RIM, CTMS, EDC) creates a unified data layer across clinical, regulatory, and quality that no other vendor matches
- Cross-object linking: a deviation automatically links to the related batch, product, site, and regulatory submission record within Vault
- Post-market surveillance depth for Class II/III medical devices and pharmaceutical pharmacovigilance; FDA MDR and EMA PSUR workflow support
- Veeva AI (2025/2026): summarisation of quality event records, draft CAPA generation, and regulatory intelligence integration

**UX patterns**
- Modern Vault platform UI consistent across all Veeva products; role-based dashboards for quality managers, regulatory affairs, and operations
- Cross-object relationship views; a deviation record shows its related CAPA, change control, and product record in a single pane

**Integration points**
- Deep Vault ecosystem integration; Veeva Network (supplier data); Salesforce CRM; REST API for external system integration; Veeva Link for external data enrichment

**Known gaps**
- Deeply tied to the Veeva ecosystem; customers outside pharma/biotech find limited value in the platform investments
- Overkill and overpriced for organizations that do not need the full Vault ecosystem
- Medical device manufacturing operations quality (process control, SPC) is weaker than life sciences document and CAPA management
- Post-Hyland era (Veeva competes in content management): integration complexity is growing

**Licence / IP notes**
- Fully proprietary; Veeva Systems NYSE: VEEV; $28B+ market cap

---

### Octave Reliance (formerly ETQ Reliance)

**Core features**
- Cloud-native enterprise QMS with 40+ configurable applications covering document control, CAPA, audits, risk management, training, non-conformance, supplier quality, and customer complaints
- Highly configurable no-code workflow builder: any QMS process can be modelled without professional services
- Risk management module with configurable risk assessment workbook and FMEA templates
- Industry-specific templates for ISO 9001, IATF 16949, AS9100, ISO 14001, and ISO 45001
- Advanced analytics and AI-driven insights (post-Hexagon integration) for quality trend analysis and cost of poor quality tracking

**Differentiating features**
- Highest configurability in the mid-enterprise QMS market: every form, workflow, notification, and report is configurable without code
- Best-in-class audit management module: audit planning, scheduling, on-site checklist execution (mobile), finding management, and CAP (Corrective Action Plan) tracking
- Strong manufacturing and automotive vertical coverage: APQP (Advanced Product Quality Planning), PPAP (Production Part Approval Process), and SPC (Statistical Process Control) templates
- Hexagon integration roadmap adds metrology and measurement data integration for manufacturing quality

**UX patterns**
- Configurable dashboards per role; management QMS health dashboard aggregating open CAPAs, overdue audits, and non-conformance trends
- Mobile audit application for conducting on-site audits on tablet with offline capability and automatic sync

**Integration points**
- ERP connectors (SAP, Oracle, Microsoft Dynamics); LIMS integration; REST API; SSO via SAML 2.0; Hexagon manufacturing software integration

**Known gaps**
- Significant configuration effort required for initial deployment; professional services cost adds to total cost of ownership
- Acquisition by Hexagon creates uncertainty about product direction and roadmap priorities
- AI capabilities are newer and less proven than the core QMS functionality
- Expensive ($50K–$200K+/yr) for smaller manufacturers

**Licence / IP notes**
- Fully proprietary; acquired by Hexagon (2022)

---

### Greenlight Guru

**Core features**
- QMS purpose-built for medical device manufacturers; covers design controls, risk management (ISO 14971), quality events, document control, and supplier management
- Design controls module integrating design history file (DHF) management with risk-linked requirements traceability matrix
- Risk management: ISO 14971-compliant risk analysis, FMEA, hazard analysis, and risk-benefit analysis with full traceability to design outputs
- Quality events: non-conformance, CAPA, deviation, and complaint management with MDR reporting workflow
- Regulatory submissions workflow for 510(k), PMA, and CE Mark documentation package assembly

**Differentiating features**
- The only QMS where design controls and risk management are native first-class features linked bidirectionally to quality events
- Traceability matrix: a single view showing the linkage from user needs to design inputs to design outputs to verification to validation evidence to risk mitigations
- Purpose-built for ISO 13485 and FDA QSR; pre-validated templates reduce validation effort for medical device startups
- Modern UX designed to be adopted by engineers and quality professionals at startups; fastest time-to-compliance in the medical device segment

**UX patterns**
- Clean, modern SaaS interface; onboarding in days rather than months
- Risk file and DHF views provide a structured navigation of complex regulatory documentation requirements
- Activity feed and @mentions for team collaboration on quality events

**Integration points**
- REST API; Slack integration for notifications; Jira integration for linking quality events to product development tickets; DocuSign for eSignature

**Known gaps**
- Narrow vertical focus; manufacturing operations quality (SPC, machine capability, in-process inspection) is not a core capability
- No LMS/training management module; companies must use a separate training system
- Limited for non-medical-device industries; ISO 9001 manufacturing quality use cases are underserved
- Priced out of very early startups; the cost floor ($22K/yr) is meaningful for pre-revenue device companies

**Licence / IP notes**
- Fully proprietary; raised $120M Series C (2022) at ~$1B valuation

---

### Qualio

**Core features**
- Cloud QMS for life sciences SMBs and scale-ups with document control, training management, CAPA, and supplier quality
- Document control with automated review and approval routing, eSignature, version management, and training task generation on document release
- CAPA and event management with configurable investigation forms, root cause fields, and effectiveness check workflows
- Supplier quality module with approved supplier list, supplier questionnaires, and audit scheduling
- Modern UX prioritised for adoption speed; typical go-live in weeks for a 20–100 person company

**Differentiating features**
- Fastest implementation timeline for a life sciences QMS: configurable template library and intuitive interface enable go-live in 2–6 weeks
- Qualio Connect: integration hub connecting Qualio to Jira, Slack, Salesforce, and development tools for software-as-medical-device (SaMD) companies
- Strong for early-stage and scaling pharma/biotech and medical device companies that need to establish a QMS quickly for investor due diligence or regulatory submission
- Transparent pricing and predictable cost structure appealing to VC-backed life sciences companies

**UX patterns**
- Modern, clean interface similar to B2B SaaS productivity tools; low training burden
- Guided onboarding with template library for ISO 13485 and FDA QSR document types

**Integration points**
- Jira, Slack, Salesforce, GitHub, and Zapier via Qualio Connect; REST API; DocuSign for eSignature

**Known gaps**
- Less configurable at enterprise scale than ETQ Reliance or MasterControl
- Audit management module less mature than competitors' dedicated audit features
- Not suitable for complex manufacturing quality operations (IATF 16949, APQP, SPC)
- Limited reporting depth for quality trend analysis without BI tool integration

**Licence / IP notes**
- Fully proprietary; private company; Series B funded

---

### qmsWrapper (Open Source)

**Core features**
- Open-source QMS for medical device and manufacturing with document control, risk assessment (ISO 14971), CAPA management, and traceability logs
- Community edition available for self-hosted deployment; commercial edition adds support and advanced features
- ISO 13485-oriented data model with controlled document types, risk file management, and CAPA linking
- Traceability matrix linking requirements to risk mitigations and verification records

**Differentiating features**
- Only open-source QMS with a native ISO 14971 risk assessment module and ISO 13485 data model
- Provides a genuine starting point for medical device companies needing a QMS without the cost of commercial tools
- Traceability logs support regulatory inspection evidence without requiring manual compilation

**UX patterns**
- Web-based interface; functional but requiring modernisation for contemporary UX standards
- Self-hosted on Linux with PHP/MySQL stack; technical setup required

**Integration points**
- REST API (limited); primarily standalone; CSV import/export

**Known gaps**
- Small community; long-term maintenance sustainability uncertain
- UI requires significant modernisation to compete with commercial tools
- No AI capabilities; no predictive analytics or intelligent root cause assistance
- Limited integrations; primarily standalone system
- Training management absent; audit management is basic

**Licence / IP notes**
- GPLv3 (Community edition); proprietary (Commercial edition). GPLv3 copyleft: derivative works distributed to others must be GPLv3. Internal use of modified software does not trigger disclosure.

---

### ProcessMaker (Open Source BPM)

**Core features**
- Open-source BPM and workflow automation platform widely adapted to build CAPA, deviation, and audit workflows
- Drag-and-drop process designer with BPMN-compatible workflow modelling
- Form designer with conditional fields, calculations, and file attachment support
- Task assignment with delegation, escalation, and deadline tracking
- Process analytics with task completion times and bottleneck identification

**Differentiating features**
- Most flexible workflow foundation for building custom QMS processes without a fixed QMS data model
- Active development with commercial enterprise offering providing long-term maintenance confidence
- REST API enabling integration with ERP, LIMS, and document management systems

**UX patterns**
- Web-based workflow designer accessible to business analysts without programming knowledge
- Task inbox for process participants with guided forms for each workflow step

**Integration points**
- REST API; webhooks; LDAP authentication; database connectors; third-party SaaS integrations

**Known gaps**
- Not a QMS out-of-the-box; requires extensive configuration to model QMS processes; no pre-built ISO 9001 or 21 CFR Part 11 templates
- No QMS-specific data model (no native CAPA record type, no document version control, no training management)
- 21 CFR Part 11 compliance requires additional validation effort; not pre-validated
- No AI capabilities; no predictive quality analytics or root cause assistance

**Licence / IP notes**
- Community Edition: AGPLv3. AGPLv3 requires source code disclosure for modified versions run as network services. Enterprise edition is proprietary.

---

## Cross-Cutting Feature Themes

### Table-Stakes Features
- Controlled document management: create, review, approve, eSign, distribute, and obsolete documents with full audit trail
- CAPA (Corrective and Preventive Action) lifecycle: initiation, investigation, root cause analysis, action planning, implementation, effectiveness check, and closure
- Non-conformance / deviation recording and disposition workflow
- Audit management: audit planning, scheduling, checklist execution, finding recording, and CAP tracking
- Training management: training task assignment, completion tracking, and training record linked to document revisions
- Electronic signature with 21 CFR Part 11 or EU Annex 11 compliance for regulated industries
- Role-based access control with configurable permissions per document type, workflow step, and module

### Differentiating Features
- Predictive CAPA: AI models trained on historical NCR, process, and supplier data predicting defect probability before non-conformances occur
- Automated root cause analysis assistance: AI correlates a new non-conformance with recent process changes, supplier lots, equipment maintenance events, and similar historical incidents
- Natural language audit package generation: "produce all CAPA records closed in the last 12 months with supporting evidence for ISO 9001 Clause 10.2" generates a structured audit evidence package
- Intelligent change control impact analysis: AI identifies all documents impacted by a specification change, drafts redline amendments, and initiates the approval workflow
- Design controls + risk traceability (Greenlight Guru model): bidirectional linkage from user needs through design inputs, outputs, verification, validation, and risk mitigations in a single navigation
- SPC (Statistical Process Control) integration with production data for real-time process capability monitoring

### Underserved Areas / Opportunities
- No open-source QMS combines a modern UX, proper regulatory data model (CAPA, audit, NCR, document control), 21 CFR Part 11 compliance, and an AI layer
- Medical device and pharma startups needing a QMS for regulatory submission have no affordable open-source alternative; the commercial market entry point is $22K–$25K/yr
- Manufacturing quality (IATF 16949, APQP, FMEA, SPC) is served by commercial tools but no OSS solution provides a genuine IATF/APQP workflow
- ISO 9001:2026 is expected to address AI integration guidance; no current QMS (commercial or OSS) has addressed this proactively
- Supplier quality management integrated with external supplier-facing portals (supplier CAPA issuance, requalification tracking) is a commercial-only feature

### AI-Augmentation Candidates
- Predictive CAPA: ML model on historical production, supplier, and environmental data predicting defect probability before incidents occur
- Automated root cause suggestion: correlate a new NCR with recent changes across processes, suppliers, equipment, and similar historical events
- Natural language audit evidence assembly: generate structured audit packages from natural language queries against the QMS database
- Intelligent document impact analysis for change control: AI identifies all documents containing the changed specification and proposes redlines
- CAPA effectiveness prediction: ML model predicts whether a proposed corrective action is likely to be effective based on similar historical CAPAs

---

## Legal & IP Summary

All leading commercial QMS platforms (MasterControl, Veeva, ETQ/Octave, Greenlight Guru, Qualio, Dot Compliance, isoTracker, Intelex) are fully proprietary with no open-source licensing.

Open-source options:
- **qmsWrapper (GPLv3):** GPLv3 copyleft applies to derivative works distributed to third parties. Internal organisational use of modified code does not trigger the copyleft. Building a new product that incorporates qmsWrapper code requires either GPLv3 compliance or a commercial licence agreement.
- **ProcessMaker Community (AGPLv3):** AGPLv3 copyleft applies to modifications run as network services, requiring source disclosure. Using ProcessMaker Community as a foundation for a hosted QMS product requires AGPLv3 compliance.

An AI-native OSS QMS built from scratch under MIT or Apache 2.0 would avoid all copyleft entanglement. Industry standards (ISO 9001, ISO 13485, ISO 14971, IATF 16949, AS9100, 21 CFR Part 11, FDA QSR, EU MDR) are open specifications with no software licensing implications, though software must demonstrate compliance through validation evidence, not just implementation.

ISO 9001:2026 (expected September 2026) is anticipated to address AI integration; an AI-native QMS built now would be positioned ahead of the standard update.

---

## Recommended Feature Scope

**Must-have (MVP)**
- Controlled document management: create, collaborative author, multi-level review/approve, eSign, publish, distribute, and obsolete, with complete audit trail and version history
- CAPA lifecycle management: initiation, investigation (with root cause tools), action planning, implementation tracking, effectiveness check, and closure with configurable workflow
- Non-conformance / deviation recording, disposition (accept, reject, rework, scrap), and CAPA linkage
- Training management: task assignment on document release, completion tracking, and training record audit trail
- Basic audit management: audit scheduling, checklist execution, finding recording, and CAP (Corrective Action Plan) tracking
- Role-based access control with electronic signature meeting 21 CFR Part 11 requirements for regulated industry users

**Should-have (v1.1)**
- AI-assisted root cause analysis: correlate new NCRs with recent process changes, supplier lots, equipment events, and similar historical incidents; propose probable root causes with evidence links
- Natural language audit evidence package generator: query QMS records in plain language and compile structured evidence packages for specific regulatory clauses
- Supplier quality portal: issue supplier CAPAs, track supplier corrective action responses, and manage approved supplier list with requalification triggers
- ISO 9001 / ISO 13485 / IATF 16949 pre-configured templates reducing configuration effort for standard-compliant deployments
- Trend analysis dashboard: defect rate, CAPA cycle time, audit findings by category, and cost of poor quality metrics with configurable alert thresholds

**Nice-to-have (backlog)**
- Predictive CAPA: ML model on historical production and supplier data predicting defect likelihood before non-conformances occur
- Design controls module with ISO 14971 risk management and bidirectional traceability matrix for medical device manufacturers
- SPC (Statistical Process Control) integration: ingest production measurement data and trigger NCRs on process capability violations
- Change control intelligence: AI identifies all documents containing a changed specification and proposes redlines for review
- Post-market surveillance module: complaint intake, MDR/PSUR workflow, and signal detection for regulated medical device and pharmaceutical organizations
