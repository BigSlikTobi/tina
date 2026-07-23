# Agentic MVP: The first Tax Advisor platform shot

- Artifact ID: ADV-MORNING-001-MVP-A001
- Artifact type: agentic-mvp
- Version: 1.3
- Artifact completeness: complete
- Job ID: ADV-MORNING-001
- Canonical lifecycle stage: discovery
- Capability mode: mixed
- Requested transition: none. Stay in discovery and narrow the proof contract before build and replay.
- Gate decision: hold
- Decision consequence: narrow
- Owner: Product
- Updated date: 2026-07-23
- Canonical brief: Open. No canonical JTBD dossier exists for this job yet.
- Input artifacts: ADV-MORNING-001-SOTA-A001 v1.2 ([SOTA benchmark](SOTA/sota_benchmark.md)); ADV-MORNING-001-VIS-A001 v0.14 ([Product Vision](product_vision.md)); ADV-MORNING-001-MET-A001 v1.1 ([Metrics and gates](metrics_learning.md)); ADV-MORNING-001-GTM-A001 v1.0 ([GTM scenario](gtm_scenario.md)); ADV-MORNING-001-WAR-A001 v2.1 ([War game](war_game.md)); ADV-MORNING-001-DEC-A001 v1.2 ([Build decision](agentic_mvp_decision.md)); TAX-PLATFORM-CONTEXT-A001 v0.1 ([platform context](../tax-advisor-platform-context.md)); [Agentic Tax Practice Manifesto](../../agentic-tax-practice-manifesto.md); [context architecture](../../../context-architecture.md); internal SE-DIFM strategy corpus (Notion/Drive, fetched 2026-07-21)
- Transcript link: [agentic_mvp_agent_transcript.md](agentic_mvp_agent_transcript.md)
- Thought-process link: [agentic_mvp_thought_process.md](agentic_mvp_thought_process.md)

## The MVP in one sentence

Build the daily home base for a German Tax Advisor.

It covers the full book of work at the control layer. It goes deeply agentic for one bookkeeping period. It stops safely when the evidence, capability, or authority is missing.

## Evidence and decision register

Stable IDs are kept. Superseded entries stay visible.

| ID | Type | Status | Claim or decision | Source | Date | Owner | Confidence |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-MVP-E001 | fact | active | The first deep job is preparing one bookkeeping period for Advisor review. | [Manifesto](../../agentic-tax-practice-manifesto.md#the-first-state) | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-E002 | fact | limited | Product currently intends German, low-document-volume, VAT-liable freelancers and digital consultants in SE-DIFM as the first cohort. The five-day and case evidence has not yet validated the low-volume or digital-consultant qualifiers. | [Product Vision](product_vision.md#current-user-truth); [GTM H007](gtm_scenario.md#evidence-and-decision-register) | 2026-07-18 | Product | high for intent; medium for fit |
| ADV-MORNING-001-MVP-E003 | fact | active | The first wedge needs an evidence-linked review package. Missing input, conflicts, unknowns, and unsupported work must stay visible. | [SOTA benchmark](SOTA/sota_benchmark.md#first-wedge-before-the-working-machine) | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-E004 | fact | superseded | Earlier scope inherited `csv_reader` and current-build format limits. Those limits do not define this greenfield MVP. | ADV-MORNING-001-MVP-D017 | 2026-07-18 | Product / Engineering | high |
| ADV-MORNING-001-MVP-E005 | fact | active | The Advisor keeps professional judgment, acceptance, the client relationship, and all consequential external actions. | [Platform context](../tax-advisor-platform-context.md#roles-and-authority) | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-E006 | fact | superseded | Earlier source ownership was written around the current build. The greenfield MVP source contract is now controlled by D017–D018. | ADV-MORNING-001-MVP-D017; ADV-MORNING-001-MVP-D018 | 2026-07-18 | Product / Engineering | high |
| ADV-MORNING-001-MVP-E007 | fact | active | The first evaluation uses synthetic data. Real or re-identifiable client data needs fresh named approval. | [Manifesto](../../agentic-tax-practice-manifesto.md#out-of-scope) | 2026-07-18 | Product / Security / Privacy | high |
| ADV-MORNING-001-MVP-E008 | fact | active | Source fidelity, ownership, checks, handovers, visible blockers, durable history, and human review must be preserved. | [SOTA benchmark](SOTA/sota_benchmark.md#parity-and-differentiation-bars) | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-E009 | fact | active | A Desk that only shows information leaves the Advisor as the workflow engine. | [Manifesto](../../agentic-tax-practice-manifesto.md#the-problem) | 2026-07-18 | Product | medium-high |
| ADV-MORNING-001-MVP-E010 | fact | active | Context is the foundation. State, tools, permissions, checks, recovery, and human review complete the work. | [Context architecture](../../../context-architecture.md) | 2026-07-18 | Product / Engineering | high |
| ADV-MORNING-001-MVP-E011 | fact | active | The Vision combines broad work control, one deep bookkeeping job, and human control over consequential decisions. | [Product Vision](product_vision.md) | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-E012 | fact | limited | The manifesto allows drafting client requests, but D019 moves client chat and message drafting out of this MVP. Automatic outreach remains forbidden. | [Manifesto](../../agentic-tax-practice-manifesto.md#the-first-state); ADV-MORNING-001-MVP-D019 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-E013 | fact | active | The Metrics artifact already defines separate Advisor-day and bookkeeping scorecards, product Gates G001 and G002, the acceptance and false-ready rules, the gold-pack structure, mandatory scenarios, KPIs, and hard guardrails. Exact values and evidence are still Open. | [Metrics and gates](metrics_learning.md) | 2026-07-21 | Product | high |
| ADV-MORNING-001-MVP-E014 | fact | active | The GTM artifact already defines the internal-discovery gate, six later rollout gates, and the evidence-based claim ladder. These commercial gates do not replace Metrics G001 or G002. | [GTM commercial gates](gtm_scenario.md#commercial-gates) | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-MVP-E015 | fact | active | The war game ran 32 of 32 design challenges. Its result is `hold` and `narrow`: close the proof and design gaps without removing the workbench or deep bookkeeping job. | [War game](war_game.md) | 2026-07-21 | Product | high |
| ADV-MORNING-001-MVP-E016 | fact | active | Vision, Metrics, and GTM still contain older current-build, PDF-reader, GFR, client-chat, or calendar assumptions. They are historical or stale where they conflict with D017–D020. | [War-game cross-lens findings](war_game.md#cross-lens-contradictions) | 2026-07-21 | Product | high |
| ADV-MORNING-001-MVP-H001 | hypothesis | superseded | Bounded L2 preparation is the thinnest honest agentic slice. | ADV-MORNING-001-MVP-D009 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-H002 | hypothesis | superseded | Synthetic replay should come before controlled live work. | ADV-MORNING-001-MVP-D008 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-H003 | hypothesis | superseded | The first shot should be one deep mission in a thin shell. | ADV-MORNING-001-MVP-D001 | 2026-07-18 | Product / Design | high |
| ADV-MORNING-001-MVP-H004 | hypothesis | superseded | Time to trusted review is a Kano performance accelerator. It is a KPI, not a feature. | ADV-MORNING-001-MVP-D002 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-H005 | hypothesis | superseded | Return Brief should be the delighter. | ADV-MORNING-001-MVP-D003 | 2026-07-18 | Product / Design | high |
| ADV-MORNING-001-MVP-H006 | hypothesis | superseded | Agentic execution depth is the lead accelerator. It is too abstract for the Kano Matrix. | ADV-MORNING-001-MVP-D002 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-H007 | hypothesis | superseded | Opportunity Radar belongs with the performance accelerators. | ADV-MORNING-001-MVP-D003 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-H008 | hypothesis | superseded | Opportunity Radar should run after preparation and show one strong need. | ADV-MORNING-001-MVP-D010 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-H009 | hypothesis | superseded | Client communication is an accelerator. The AI evidence loop is a delighter. | ADV-MORNING-001-MVP-D004; ADV-MORNING-001-MVP-D011 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-H010 | hypothesis | superseded | One Tax Advisor Agent should lead a small visible specialist team. | ADV-MORNING-001-MVP-D012 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-H011 | hypothesis | superseded | `Context is all you need` needs a sharper meaning. | ADV-MORNING-001-MVP-D013 | 2026-07-18 | Product / Engineering | high |
| ADV-MORNING-001-MVP-O001 | open question | superseded | Does the MVP include a controlled manual DATEV handoff? | ADV-MORNING-001-MVP-D007 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O002 | open question | superseded | Should the first evaluation use replay or real data? | ADV-MORNING-001-MVP-D008 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O003 | open question | superseded | Where does agent preparation stop? | ADV-MORNING-001-MVP-D009 | 2026-07-18 | Product / Domain | high |
| ADV-MORNING-001-MVP-O004 | open question | superseded | Metrics D004, D007–D008, and D012–D014 defined the period shape, material-correction rule, acceptance rule, gold-pack structure, owner roles, and scenario rule. The remaining concrete inputs are split into O021–O027. | [Metrics and gates](metrics_learning.md) | 2026-07-18 | Product / Domain | high |
| ADV-MORNING-001-MVP-O005 | open question | superseded | Thin shell, case screen, or daily workbench? | ADV-MORNING-001-MVP-D001 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O006 | open question | superseded | What are the concrete performance accelerators? | ADV-MORNING-001-MVP-D002; ADV-MORNING-001-MVP-D004 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O007 | open question | superseded | What is the exact Opportunity Radar promise? | ADV-MORNING-001-MVP-D010 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O008 | open question | superseded | When does the Radar run? | ADV-MORNING-001-MVP-D010 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O009 | open question | superseded | What is the first Radar signal? | ADV-MORNING-001-MVP-D010 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O010 | open question | superseded | How many opportunities should the first shot show? | ADV-MORNING-001-MVP-D010 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O011 | open question | superseded | Should the MVP have one or two delighters? | ADV-MORNING-001-MVP-D014 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O012 | open question | superseded | Can an AI command count as approval to send a client message? | ADV-MORNING-001-MVP-D006 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O013 | open question | superseded | Where does the client conversation live? | ADV-MORNING-001-MVP-D011 | 2026-07-18 | Product / Design | high |
| ADV-MORNING-001-MVP-O014 | open question | superseded | Which agents are visible in the first shot? | ADV-MORNING-001-MVP-D012 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O015 | open question | superseded | One AI front door or separate agent chats? | ADV-MORNING-001-MVP-D012 | 2026-07-18 | Product / Design | high |
| ADV-MORNING-001-MVP-O016 | open question | superseded | Should the UI lead with the job or the agent name? | ADV-MORNING-001-MVP-D012 | 2026-07-18 | Product / Design | high |
| ADV-MORNING-001-MVP-O017 | open question | superseded | Keep or sharpen the context statement? | ADV-MORNING-001-MVP-D013 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O018 | open question | superseded | Should the agent send client messages? | ADV-MORNING-001-MVP-D006 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-O019 | open question | active | Retention, deletion, provider path, permission versions, security owner, and privacy owner must be named before controlled live use. | ADV-MORNING-001-MVP-E007 | 2026-07-18 | Security / Privacy / Engineering | high |
| ADV-MORNING-001-MVP-O020 | open question | narrowed | Connected-source contract: four-system surface (GFR.ai polled, DATEV reference-copy-only FR-DATEV-08, Taxfix App+Backoffice, FinAPI <15 min), ownership, and freshness are now documented in the SE-DIFM Requirements Spec (WAR-E023–E024). Still open: exact ~60-of-1200 SKR03/04 account list + SKR choice (Julian + Suat), dashboard real-time vs poll freshness (Workshop D-07). | ADV-MORNING-001-MVP-D018; ADV-MORNING-001-WAR-E023–E024 | 2026-07-23 | Product / Domain / Engineering | high |
| ADV-MORNING-001-MVP-O021 | open question | narrowed | First case is frozen: neu-gegründet Einzelunternehmer/Freiberufler, EÜR, Ist-Versteuerung, one bank account, ≤50–80 tx/month, no cash, no employees, no e-commerce, not Kleinunternehmer §19. Readiness rubric documented (WAR-E026): missing Ausgangsrechnung = NOGO; missing Eingangsrechnung = partial; recurring rent = contract. Match target >85%. Still open: exact ~60-of-1200 SKR03/04 account list + SKR choice; accounting-method/VAT-period enum values (OQ-1); prior-bookkeeping takeover policy. | ADV-MORNING-001-MET-O002; ADV-MORNING-001-WAR-E026 | 2026-07-23 | Product / Domain | high |
| ADV-MORNING-001-MVP-O022 | open question | narrowed | Evidence types now documented (WAR-E027): bank (finAPI Transaction object, FR-BANKTX-01 fields, MATCHED/MISSING_DOCUMENT/DUPLICATE), invoices (PDF/JPEG OCR'd, §14 UStG validation, PROCESSED/FAILED/DUPLICATE), ledger (Hauptbuch), debtors/creditors (DATEV CSV/DAT). Still open: structured e-invoice (ZUGFeRD/XRechnung/EN-16931) handling — GFR OCR-only pipeline named nowhere; genuine gap as B2B E-Rechnungspflicht phases in. GFR-OCR trust boundary (quarantine document-derived text). | ADV-MORNING-001-WAR-O004; ADV-MORNING-001-WAR-E027; ADV-MORNING-001-WAR-F032 | 2026-07-23 | Domain / Execution Safety | high |
| ADV-MORNING-001-MVP-O023 | open question | narrowed | Handoff is now documented (WAR-E025): Suat Göydeniz / TaxVentures exports GFR CSV → imports manually to DATEV → submits USt-VA via ELSTER; ELSTER protocol = receipt; Bescheid PDF re-uploaded to Backoffice. Requires Untervollmacht §80 AO + LAPIS Unterberaternummer (A-1 = critical-path blocker). Manual workflow scoped for first 50–100 clients (NFR-09). Still open: A-1 resolution (F024, controlled-live prerequisite); Finanzamt-rejection remediation ("TA handles it" — under-specified). | ADV-MORNING-001-MET-D009–D011; ADV-MORNING-001-WAR-E025; ADV-MORNING-001-WAR-F024 | 2026-07-23 | Product / Domain / Operations | high |
| ADV-MORNING-001-MVP-O024 | open question | narrowed | People are now named (WAR-E033): sponsor COO Markus Berger de León; PM Christine Kiefer; GTM Claire Davidson; venture dev Marcel Koka; Eng Massimo; Ops Carolin Krüger; Dashboard Ozan Kara; StB Suat Göydeniz (TaxVentures); external DPO Carlo Piltz. Still open: Security/CISO owner unnamed; D-04 (contract owner) and D-05 (Suat capacity) still open. | ADV-MORNING-001-MET-O004–O005; ADV-MORNING-001-WAR-E033; ADV-MORNING-001-WAR-F025 | 2026-07-23 | Product / GTM / Research | high |
| ADV-MORNING-001-MVP-O025 | open question | active | What happens when the Expert or Advisor reviewer is absent, overloaded, late, or rubber-stamping? Define hold, expiry, reassignment, reason, escalation, and take-over rules before replay. | ADV-MORNING-001-WAR-O008; ADV-MORNING-001-WAR-F016 | 2026-07-21 | Advisors / Operations | high |
| ADV-MORNING-001-MVP-O026 | open question | active | What numeric thresholds and minimum replay volume apply? Metrics says to set them after the five-day baseline and before results are seen. | ADV-MORNING-001-MET-D003, D014; ADV-MORNING-001-MET-O005 | 2026-07-21 | Product / Domain / Research | high |
| ADV-MORNING-001-MVP-O027 | open question | narrowed | Correction window is now documented (WAR-E030): Einspruchsfrist §347 AO = 1 month from Bescheid; post-export/pre-ELSTER re-file warning; late docs roll to next period (FR-GFR-11); 10yr §147 AO audit; Steuerberater retains full StBerG liability. Still open: TA-Dashboard PRD automated detection only — the remediation workflow for a rejected filing or deviating Bescheid ("TA handles it") remains under-specified. | ADV-MORNING-001-WAR-E030; ADV-MORNING-001-WAR-O009 | 2026-07-23 | Domain / Advisors | high |
| ADV-MORNING-001-MVP-O028 | open question | active | Which allowed service catalog and relevance, usefulness, and evidence threshold let Opportunity Radar show a card to an Advisor? | ADV-MORNING-001-WAR-S012 | 2026-07-21 | Product / Advisors | high |
| ADV-MORNING-001-MVP-O029 | open question | active | What total-effort, parallel-system work, latency, cost, support, and review-load limits show that the workbench removes more work than it creates? | ADV-MORNING-001-WAR-S015, S025, S031 | 2026-07-21 | Product / Operations / Finance | high |
| ADV-MORNING-001-MVP-D001 | decision | superseded | The first shot is a SOTA-complete daily Advisor workbench plus one deep agentic bookkeeping workflow. | ADV-MORNING-001-MVP-D018 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-D002 | decision | active | Taxfix client flow and agentic bookkeeping preparation are performance accelerators. | User confirmation | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-D003 | decision | active | Opportunity Radar is a delighter. | User confirmation | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-D004 | decision | superseded | In-app Advisor-client communication was a performance accelerator in the first scope. | ADV-MORNING-001-MVP-D019 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-D005 | decision | superseded | The AI evidence loop was accepted as a delighter, but Send was not explicit enough. | ADV-MORNING-001-MVP-D006 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-D006 | decision | limited | When the later communication iteration is designed, AI may draft a client message. Only the Advisor can click Send. An AI command never sends. D019 keeps all client-message drafting outside this MVP. | User confirmation; ADV-MORNING-001-MVP-D019 | 2026-07-18 | Product / Execution Safety | high |
| ADV-MORNING-001-MVP-D007 | decision | active | The MVP ends with Advisor accept or return plus a recorded, human-operated downstream handoff. The platform does not write to DATEV. Replay simulates the handoff. Exact action, destination, operator, and receipt remain Open under O023. | Delegated finalization from O001; ADV-MORNING-001-MET-D009–D011 | 2026-07-18 | Product | medium-high |
| ADV-MORNING-001-MVP-D008 | decision | active | The first evaluation mode is synthetic replay. | Delegated finalization from O002 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-D009 | decision | active | The agent owns bounded L2 preparation until review, a blocker, cancellation, or a human stop. | Delegated finalization from O003 | 2026-07-18 | Product / Domain | medium-high |
| ADV-MORNING-001-MVP-D010 | decision | active | Opportunity Radar runs after supported preparation. It shows at most one strong overdue-receivables signal. It never changes readiness. | Delegated finalization from O007 to O010 | 2026-07-18 | Product | medium-high |
| ADV-MORNING-001-MVP-D011 | decision | superseded | The client conversation lived at engagement level and the AI evidence loop was an MVP delighter. | ADV-MORNING-001-MVP-D019 | 2026-07-18 | Product / Design | medium-high |
| ADV-MORNING-001-MVP-D012 | decision | active | One Taxfix AI front door leads the mission. DataJanitor Pro, FristenGuard, and AdvisorLens work behind it. The UI shows the job first and the agent name second. | Delegated finalization from O014 to O016 | 2026-07-18 | Product / Design | medium-high |
| ADV-MORNING-001-MVP-D013 | decision | active | Use: `Context is the foundation. Controlled execution creates the outcome.` | Delegated finalization from O017 | 2026-07-18 | Product / Engineering | medium-high |
| ADV-MORNING-001-MVP-D014 | decision | superseded | The MVP had two delighters: Opportunity Radar and the AI-assisted missing-evidence loop. | ADV-MORNING-001-MVP-D019 | 2026-07-18 | Product | medium-high |
| ADV-MORNING-001-MVP-D015 | decision | active | Hold the product gate and narrow the next work to the exact proof contract. | E015; O020–O024 | 2026-07-18 | Product | high |
| ADV-MORNING-001-MVP-D016 | decision | superseded | The daily Advisor workbench remains an MVP must-have, but the SOTA benchmark does not own MVP scope. | ADV-MORNING-001-MVP-D017; ADV-MORNING-001-MVP-D018 | 2026-07-19 | Product | high |
| ADV-MORNING-001-MVP-D017 | decision | active | This is a greenfield MVP. Current code, features, tests, and limits do not define product scope. Required capabilities come from the confirmed user job. | User correction during war-game review | 2026-07-21 | Product | high |
| ADV-MORNING-001-MVP-D018 | decision | active | The MVP workbench connects to DATEV, task lists, and Taxfix systems at the control layer. Important bookkeeping dates come from DATEV and Taxfix systems. Email and a general calendar integration are outside MVP scope. This does not yet approve DATEV write automation. | User confirmation | 2026-07-21 | Product | high |
| ADV-MORNING-001-MVP-D019 | decision | active | Advisor-client chat and the AI-assisted client-message loop are outside the MVP. They are an early follow-up iteration. The permanent human-Send rule in D006 still applies when that iteration is designed. | User confirmation | 2026-07-21 | Product / Design | high |
| ADV-MORNING-001-MVP-D020 | decision | active | The primary MVP user is an internal Taxfix Advisor. A Tax Expert supports preparation. The first deep job prepares one bookkeeping period for Advisor review. | User confirmation | 2026-07-21 | Product | high |
| ADV-MORNING-001-MVP-D021 | decision | active | Reuse the existing gate systems. Metrics owns product and evaluation Gates G001 and G002. GTM owns recruitment and rollout gates. The MVP and war game reference them and do not create a third gate system. | E013–E015; documentation audit requested by the user | 2026-07-21 | Product | high |
| ADV-MORNING-001-MVP-D022 | decision | active | Open matters are grouped by when they are needed. A later real-data, launch, or scale question does not reopen the confirmed MVP scope and does not block earlier discovery work unless its named gate requires it. | E013–E015; documentation audit requested by the user | 2026-07-21 | Product | high |

## Conversation decisions

- Confirmed process scope: A full daily workbench at the control layer. One deep bookkeeping workflow at the execution layer. The primary user is an internal Taxfix Advisor; a Tax Expert supports preparation.
- Confirmed user promise: The Advisor can run the day in Taxfix and receive a source-linked bookkeeping package instead of rebuilding the case.
- Confirmed agentic boundary: Bounded L2 preparation until review, blocker, cancellation, or human stop.
- Confirmed capability and evaluation modes: Mixed capability mode. Synthetic replay first.
- Confirmed source boundary: The MVP workbench connects to DATEV, task lists, and Taxfix systems. Email, a general calendar connection, and client chat are outside the MVP. Chat is an early follow-up iteration.
- Confirmed effect and authority boundaries: AI can prepare. Humans decide. DATEV write automation is not approved by the control-layer connection decision.
- Confirmed acceptance bar: No false-ready result. Every material claim needs evidence. Every blocker needs an owner and next action.
- Matters delegated to the agent: O001 to O003, O007 to O011, and O013 to O017 were closed with the recommendations in D007 to D014.

## What is already defined and what remains open

### Short answer on tests and gates

Yes. The tests and gates are already substantially defined.

- [Metrics](metrics_learning.md) owns the product proof. G001 decides whether the contract is ready for build. G002 decides whether the built product is ready for synthetic replay.
- [GTM](gtm_scenario.md#commercial-gates) owns recruitment and rollout. It starts with internal discovery and ends with open-market expansion.
- The [war game](war_game.md) attacks those contracts. It does not replace them.

The current `hold` does not mean “we forgot to design the gates.” It means some gate inputs still
need exact values, owners, fixtures, or evidence.

### Already decided

| Area | What is already defined | Source |
| --- | --- | --- |
| Product shape | Full-day Advisor workbench plus one deep bookkeeping-period job | D017–D020 |
| User and support | Internal Taxfix Advisor is primary. Tax Expert supports preparation. | D020 |
| MVP sources | DATEV, task lists, and Taxfix systems are in. Email, general calendar, and client chat are out. | D018–D019 |
| Product package | The active Kano Matrix defines must-haves, accelerators, and Opportunity Radar | D002–D003, D010, D012 |
| Agent boundary | Bounded L2 preparation. Humans keep judgment, acceptance, client contact, and consequential action. | D006, D008–D009 |
| Evaluation start | Synthetic replay comes first | D008 |
| Acceptance meaning | Correct client and month, required input accounted for, supported evidence reconciled, material claims linked, conflicts visible, human accept or return | ADV-MORNING-001-MET-D008 |
| False-ready rule | A ready result fails if a required input, conflict, capability, check, or review is missing | ADV-MORNING-001-MET-D008 |
| Material correction | A change to readiness, reconciliation, missing-evidence need, Advisor decision, or handoff is material | ADV-MORNING-001-MET-D004 |
| Test design | Gold pack, required scenarios, separate scorecards, four early KPIs, and hard guardrails | ADV-MORNING-001-MET-D001, D012, D014–D015 |
| Product gates | G001 discovery to build. G002 build to synthetic replay. | ADV-MORNING-001-MET-G001–G002 |
| Commercial gates | Seven stages from internal discovery to open-market expansion | ADV-MORNING-001-GTM-D003, D005–D006 |
| Price and claims | No customer price yet. Claims widen only after the relevant evidence gate passes. | ADV-MORNING-001-GTM-D003, D006 |

### Open before G001 can approve build

These are missing inputs to the existing gate. They are not a request to redesign the MVP.

| Open ID | What still needs definition | Why it matters |
| --- | --- | --- |
| O020 | Exact DATEV, task-list, and Taxfix-system data, source ownership, freshness, sync, and allowed effects | Prevent a stale or duplicate workbench from saying the day is clear |
| O021 | Exact case schema, low-volume rule, required fields, exclusions, gold matches, unresolved items, and gold readiness result | Make the bookkeeping result testable |
| O022 | Required evidence types and subtypes, validated fields, source links, safe handling, and blocked outcomes | Stop unsafe reading, fake support, and hidden instructions |
| O023 | Exact downstream handoff action, destination, operator, receipt, correction, and unknown-result rule | Make the accepted end state and recovery real |
| O024 | Actual people and access for observation, gold approval, vetoes, and incidents | Run the existing gate with accountable humans. This does not redefine the user. |

The five-day Advisor study supplies evidence for O020, O021, O024, and the workbench kill shot. The
five-day window is already decided. The participating people and observed source map are not.

### Open after the baseline and before replay or visible use

| Open ID | What still needs definition | Due point |
| --- | --- | --- |
| O025 | Reviewer absence, overload, expiry, reassignment, reason, escalation, and take-over rules | Before replay |
| O026 | Numeric thresholds and the minimum precommitted replay volume | After baseline, before results |
| O027 | Post-handoff window for delayed material correction or harm | Before G002 |
| O028 | Allowed-service catalog and Opportunity Radar relevance, usefulness, and evidence threshold | Before Advisor-visible Radar proof |

### Open before real client data

O019 owns the provider and data contract. It must name the provider path, region, subprocessors,
support access, transfer route, retention, deletion, permissions, tenant controls, incident route,
and responsible Security and Privacy people. This is not needed to run synthetic replay.

### Open before wider rollout or scale

O029 owns the strongest unresolved war-game threat. We must measure total human work across
Advisors, Experts, support, handoff, correction, and parallel systems. We must also set limits for
latency, cost, support load, and review load. If the workbench creates more work than it removes
after bounded repair, the combined product shape should be killed.

The GTM artifact already owns later partner and market questions. Before Stage 3 it still needs the
seven named partner firms, their mix, evidence volume, data path, onboarding, support, and partner
thresholds. Pricing stays Open until operating and buyer evidence exists.

### Documentation repairs, not new product questions

- Create the canonical JTBD dossier so one place owns lifecycle status and gate decisions. This is record-keeping. It does not require us to rename the user or redesign the MVP.
- Update Metrics, GTM, Vision, and the context overlay where they still use current-build limits, a separate PDF-reader assumption, GFR-specific wording, or the old client-chat scope.
- Keep SOTA as As-Is and market analysis. Correct its stale source date, but do not use it to choose MVP scope.
- Keep the two proof units separate. A good bookkeeping result cannot prove the workbench runs the day, and a useful workbench cannot prove the bookkeeping result is ready.

## Process evidence handoff

- Process documentation and versions: SOTA v1.2, Product Vision v0.14, Platform Context v0.1, Manifesto proposed v0.
- Evidence status: partial
- Scope: whole daily-work control layer plus one deep bookkeeping-period preparation job
- Trigger, actor, and desired outcome: An internal Taxfix Advisor is the primary user. A Tax Expert supports preparation of an eligible bookkeeping period so the Advisor can review one evidence-linked package.
- Start state: Tenant, client, engagement, workstream, period, permissions, and approved synthetic evidence exist.
- Accepted end state: Advisor accepts or returns the package. A controlled human-operated downstream handoff is then recorded or replayed. O023 must define its exact contract.
- Strengths to preserve: Source fidelity, ownership, checks, visible blockers, durable state, and human review.
- Pain to remove: Evidence hunting, copy-paste, repeated client chasing, weak handovers, and hidden work.
- Authority boundary: The system prepares. The Tax Expert supports preparation. The Advisor owns judgment, the client relationship, any future Send, and acceptance.
- Inherited evidence gaps: O020–O029. O019 applies only before real client data.

| Process step | Current strength or problem | Treatment | Reason |
| --- | --- | --- | --- |
| Set client, mandate, period, and evidence scope | Wrong scope makes all later work unsafe | deterministic | Fail closed on any mismatch |
| Check input and capability support | Unsupported files can look usable | deterministic | Exact allowlist and visible `needs_capability` state |
| Plan the preparation | Today the human carries the plan | agentic | The plan must change when evidence changes |
| Read job-required evidence | Stable parsing should be predictable | deterministic | Required types and checks come from the job, not a current build |
| Reconcile transactions, invoices, and open items | Manual matching is slow | agentic | Continue, ask, or block based on evidence |
| Check completeness and readiness | False-ready is the critical failure | deterministic | Required checks stay explicit |
| Resolve ambiguity or conflict | This needs tax and client judgment | human | Never guess through a material conflict |
| Build the review package and draft questions | The handover must carry proof | agentic | Package and drafts change with the case |
| Accept, return, and hand off | The Advisor owns the decision | human | Record the decision and controlled downstream handoff |
| Surface a client opportunity | Useful, but separate from readiness | agentic | Evidence-backed and Advisor-gated |
| Contact, sell, file, pay, sign, or judge | Outside agent authority | remove | These actions stay human |

## Kano Matrix for the MVP

This matrix controls the first platform shot.

A must-have prevents the product from failing as the Advisor's daily home base.

A performance accelerator gets better as there is more of it.

A delighter creates useful value the Advisor did not expect.

| Kano class | Product feature | First-shot promise | Why it belongs here | MVP proof |
| --- | --- | --- | --- | --- |
| Must-have | Daily Advisor workbench | All important clients, deadlines, tasks, waits, blockers, reviews, owners, sources, and next actions stay visible | Without this, the Advisor still needs another place to run the day | A representative book shows no hidden in-scope work |
| Must-have | Source-system continuity | DATEV, task-list, and Taxfix-system dates and work states stay visible in the workbench | Full work coverage does not mean rebuilding every source system | Source, owner, state, blocker, freshness, and next action are reconciled for every in-scope item |
| Must-have | One deep bookkeeping mission | The platform prepares one supported bookkeeping period from start to review | A broad dashboard without real execution is not enough | Happy and exception paths both complete the full agent loop |
| Must-have | Trust and human control | Sources, checks, limits, history, blockers, pause, cancel, return, and take-over stay visible | Tax work without reviewable proof is not a product | No unsupported or conflicting fixture reaches ready |
| Must-have | Real agents, one front door | The Tax Advisor Agent leads. Specialist work is visible in one Plan and one Trace | Agent names alone are decoration | Every agent has a scope, capability limit, stop rule, result, and human gate |
| Performance accelerator | Taxfix client flow | More eligible Taxfix clients arrive mandate-ready in the Advisor workbench | More workable clients can mean more revenue | Measure activated mandates, onboarding effort, and time to first work |
| Performance accelerator | Agentic bookkeeping preparation | More supported preparation is completed by the platform | More completed preparation increases Advisor capacity | Measure accepted periods, hands-on minutes, corrections, and supported coverage |
| Delighter | Opportunity Radar | The platform spots one real client need and shows the proof | It creates new client value beyond today's requested job | Show one overdue-receivables signal with evidence, impact, confidence, unknowns, and Advisor choice |

### Later accelerators, not MVP scope

| Feature | Why it is later |
| --- | --- |
| Client chat and AI-assisted missing-evidence loop | This is the first planned follow-up. It needs a clear client channel, message state, human Send, reply linking, and recovery. |
| DATEV write automation | DATEV visibility is in the MVP. Writing or posting back needs a separate effect, reconciliation, and recovery decision. |
| OpsMaestro | It needs broader practice data and proven workflow signals. |
| ClientFit Scout | The first cohort is already selected. Scoring and pricing add scope before the first job is proven. |
| Evidence types outside the first job contract | The MVP must support the evidence required by the first job. Other types come later after job-specific validation. |

## Agent team

The Advisor works with one mission lead. The product does not become an inbox full of bots.

| Agent | MVP job | Hard limit |
| --- | --- | --- |
| Tax Advisor Agent | Owns the mission, plan, routing, blocker explanation, and review package | No professional judgment or client contact |
| DataJanitor Pro | Inventories job-required data, normalizes it, reconciles the period, and exposes gaps | No claim beyond validated evidence types |
| FristenGuard | Watches approved DATEV and Taxfix bookkeeping dates, waits, missing input, stale work, and resume conditions | No email, general calendar, or tax-office coverage |
| AdvisorLens | Creates one evidence-backed opportunity card | Never changes readiness. Never contacts or sells to the client. |
| Document Review Agent | Checks completeness for supported evidence | Unsupported input still stops |

The UI shows the job first.

Example: `Bookkeeping preparation | DataJanitor Pro`.

Named agents are greenfield product roles. Their capability must be proven against the job.

## Early-iteration client communication contract

Client chat is not part of the MVP. It is the first planned follow-up iteration.

The private Advisor-AI thread and the client conversation are separate.

The engagement-level client conversation can link to a mission, blocker, evidence request, reply, and upload.

The safe loop is:

1. The Advisor asks what is missing.
2. AI names the blocker and source.
3. AI drafts the exact client request.
4. AI places the draft in the client composer.
5. The Advisor checks recipient and wording.
6. The Advisor clicks Send.
7. The client replies or uploads evidence.
8. The system links the reply as untrusted evidence.
9. The agent checks it.
10. Work resumes or the blocker stays visible.

An AI chat command never sends a message.

When this iteration is built, replay must simulate Send and reply. A future live mode records the human send result. If the result is unknown, the system reconciles it before a retry.

## Opportunity Radar contract

- Trigger: After supported bookkeeping preparation and checks.
- Scope: Same tenant, client, workstream, and period only.
- First signal: Overdue receivables and possible cash-flow pressure.
- Output: At most one strong opportunity.
- Required fields: Observed need, source evidence, client impact, suggested allowed service, confidence, unknowns, and Advisor decision.
- Advisor choices: Save or dismiss with reason. Creating a client draft belongs to the early chat iteration.
- Hard boundary: The opportunity never changes bookkeeping readiness.
- Forbidden action: No automatic outreach, sale, price, promise, or conversion.

## Light Codex UI direction

This is an interaction direction. It is not a final visual design.

| Area | What it must do |
| --- | --- |
| Today | Show what needs attention, why, owner, deadline, and next action |
| Clients | Show the full client book and durable client workspace |
| Mission | Show goal, period, state, owner, blocker, and human next step |
| Plan | Show a short plan, current step, checks, and dependencies |
| Work | Show useful progress and pause, resume, cancel, and take-over controls |
| Trace | Show sources, actions, checks, changes, unknowns, and conflicts |
| Review | Let the Advisor accept or return the package |
| Conversation | Early iteration, not MVP: keep private AI chat separate from the client-visible thread |
| Return Brief | Show what changed since the last visit and where work resumes |

The surface is work-first. Chat supports the work. It does not replace state, Plan, Trace, or Review.

## Alignment with Vision, Manifesto, and context architecture

The direction still holds.

| Finding | Alignment | Condition |
| --- | --- | --- |
| Full daily workbench | Fits the Vision's broad work control | Breadth stays at the control layer. Deep execution stays with bookkeeping. |
| Agentic bookkeeping | Fits the first deep job | Only supported evidence and bounded L2 preparation |
| Client chat | Early follow-up iteration | Outside MVP; AI drafts and the Advisor sends when built |
| Opportunity Radar | Fits the shadow-first opportunity machine | Separate from readiness and controlled by the Advisor |
| Named agents | Fits the target capability portfolio | One shared context, Plan, Trace, and review path |
| DATEV source connection | Required for dates and work state | Exact views, freshness, and reconciliation remain Open under O020 |
| Human-operated downstream handoff | Keeps write effects bounded | Exact contract stays Open under O023. No silent DATEV write automation. |

The old phrase needs one clear boundary:

> Context is the foundation. Controlled execution creates the outcome.

Context helps the system understand the job. It does not grant authority. It does not prove correctness. It does not replace state, checks, recovery, or human judgment.

## Research coverage

- Research mechanisms used: Full review of all 24 Markdown files and the HTML mock under `ADV-MORNING-001`, plus the supplied sources already cited by those artifacts.
- Research limitation: No new external research was needed for this update. Direct Advisor observation and exact job proof are still missing.

| Source ID | Publisher | Link | Access date | Supported claim | Evidence quality | Status |
| --- | --- | --- | --- | --- | --- | --- |
| SOTA-A001 | Taxfix Product | [SOTA benchmark](SOTA/sota_benchmark.md) | 2026-07-18 | Market bar, DATEV boundary, and missing proof | Completed internal synthesis with primary-source register | accepted with limits |
| VIS-A001 | Taxfix Product | [Product Vision](product_vision.md) | 2026-07-18 | Cohort, platform shape, authority, and roadmap direction | Internal decision artifact | accepted as direction |
| MET-A001 | Taxfix Product | [Metrics and gates](metrics_learning.md) | 2026-07-21 | Existing product gates, tests, metrics, guardrails, and open values | Internal decision artifact | accepted; stale build assumptions excluded |
| GTM-A001 | Taxfix Product | [GTM scenario](gtm_scenario.md) | 2026-07-21 | Existing recruitment and rollout gates and claim ladder | Internal decision artifact | accepted; old chat and build assumptions excluded |
| WAR-A001 | Taxfix Product | [War game](war_game.md) | 2026-07-21 | 32 design attacks, cross-lens conflicts, and phased remediation | Completed design simulation | accepted as design challenge, not runtime proof |
| TAX-PLATFORM-CONTEXT-A001 | Taxfix Product | [Platform context](../tax-advisor-platform-context.md) | 2026-07-18 | Capability, data, evaluation, and safety contract | Primary internal contract | accepted |

## Promise and boundaries

- User promise: Run the Advisor's day in one workbench. Prepare one eligible bookkeeping period for review. Stop clearly when the work cannot continue.
- Demo moment: DATEV, task-list, and Taxfix-system work appears in one daily view. A missing receipt changes the plan and creates a visible blocker. New evidence in an approved source is checked and work resumes. The final package reaches Advisor review. One separate opportunity card appears.
- Start state: Scoped synthetic client, engagement, period, allowed evidence, permissions, and active approved capabilities.
- Accepted end state: Advisor accepts or returns the package. The controlled human-operated downstream handoff is recorded or replayed.
- Valid blocked states: `missing_input`, `needs_capability`, `conflicting_evidence`, `failed_check`, `needs_human_review`, `cancelled`, and `unknown_external_outcome`.
- Non-goals: Email integration, general calendar integration, client chat, real client data without approval, automatic selling, filing, payment, signing, professional judgment, DATEV write automation, unsupported evidence claims, PACS, formal Seal, whole-book automation, and a generic chatbot.

## Agentic qualification

- Classification: agentic

| Criterion | Observable proof | Present |
| --- | --- | --- |
| Goal | Prepare one period for review or stop with a named blocker | yes |
| Observe | Read scope, allowed evidence, capability state, prior actions, and human feedback | yes |
| Decide | Choose the next read, match, check, question, retry, handoff, or stop | yes |
| Act | Create plans, claims, blockers, checks, and a review package | yes |
| Check | Run source, coverage, conflict, support, and readiness checks | yes |
| Adapt | Re-plan, ask, retry, block, cancel, resume, hand over, or stop | yes |

- Happy path: Load the in-scope DATEV, task-list, and Taxfix state; scope, plan, prepare, check, package, Expert handover, Advisor decision, and record the bounded downstream handoff.
- Exception path: Missing or conflicting evidence changes the plan. The run blocks. New evidence arrives. The run resumes and checks again.
- Why this is agentic: The path changes when the observed case changes. Stable rules stay deterministic.

## Capability and evaluation context

- Proposed capability mode: mixed
- Project autonomy level: L2 Prepare
- Evaluation mode: synthetic replay
- Canonical lifecycle implication: Stay in discovery until Metrics Gate G001 passes. Do not invent another product gate here.
- Evidence needed before build: O020–O024 plus the existing G001 inputs in Metrics.
- Evidence needed before replay or visible use: O025–O028 plus a passed G001 and the precommitted G002 test set.
- Evidence needed before controlled live: O019 plus fresh real-data approval.

## Agent loop

| Step | Goal | Observe | Decide and act | Check | Adapt or stop | Human gate | Evidence created |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Scope | Bind one eligible period | Client, mandate, period, manifest, permissions | Proceed or block | Exact tenant, client, period, and input match | Ask or stop | Expert if unclear | Scope record |
| Plan | Choose bounded work | Inputs, prior events, blockers, task catalog | Create a short versioned plan | Required work and capability limits covered | Re-plan, ask, or block | Expert can narrow or stop | Plan and reason |
| Prepare | Reconcile supported evidence | Job-required evidence through approved readers and source connections | Match, leave open, flag conflict, or ask | Source coverage and conflict checks | Continue, retry, or block | Expert resolves ambiguity | Claims and blockers |
| Block | Expose missing evidence | Required input, source state, and prior work | Record the exact gap, owner, and next action | Blocker is source-linked and no ready claim exists | Wait, correct, or stop | Tax Expert supports; Advisor can take over | Blocker record |
| Resume | Use new evidence | New approved-source evidence, prior blocker, source version | Link evidence and continue work | Support, scope, and evidence checks | Clear blocker or remain blocked | Tax Expert if ambiguous | New evidence and resume event |
| Package | Create reviewable outcome | Passed checks, unknowns, unresolved work | Build package and handover | Rubric and evidence links | Correct or hand over | Expert hands over | Package and handover |
| Review | Reach a human decision | Package, Trace, evidence, unknowns | Accept or return | Named rubric | Close or reopen | Advisor | Review decision |
| Handoff | Record the approved downstream next step | Accepted package and human result | Record simulated or human handoff | Reconcile receipt or status | Remediate or block | Advisor / Operations | Handoff record |
| Radar | Surface one client need | Prepared evidence and allowed service catalog | Create or suppress one opportunity | Evidence, confidence, and unknowns complete | Save or dismiss | Advisor | Opportunity decision |

## Effect, retry, and recovery contract

| Step | Effect class | Idempotency key | Retry rule | Unknown-outcome check | Recovery | Owner |
| --- | --- | --- | --- | --- | --- | --- |
| Scope and plan | reversible | tenant + workstream + period + plan version | Retry only after confirmed internal failure | Read durable product state first | Cancel or supersede with reason | Engineering |
| Evidence read | read-only | source hash + reader hash + run task | Retry the exact approved read only | Compare action, result, and source hash | Block on change or unsupported input | Engineering |
| Claims and package | reversible | run + result type + evidence version | Versioned upsert only | Read durable result and event history | Supersede, never erase reviewed history | Engineering / Expert |
| Advisor review | reversible before downstream effect | package version + reviewer + command | Never replay blindly | Read current review event | Return or reopen with reason | Advisor |
| Human-operated downstream handoff | potentially irreversible outside Taxfix | package + handoff type + operator | No system retry | Check the destination result and Taxfix record | Named manual correction | Advisor / Operations |

An external action with an unknown result is never retried blindly.

## Permissions, data, and versions

- Tool and capability allowlist: Define it from the exact job and the confirmed DATEV, task-list, Taxfix-system, and evidence contracts. Every capability needs validation and explicit approval.
- Forbidden actions: Client contact in the MVP, automatic outreach, sale, filing, payment, signing, professional judgment, unapproved provider transfer, unvalidated capability use, cross-tenant access, unsupported evidence claims, silent DATEV write, and automatic authority growth.
- System of record: Each source keeps ownership of its records. The exact DATEV, task-list, and Taxfix ownership and sync contract is Open under O020.
- Review: Tax Expert supervises. Advisor accepts or returns.
- Data class: Synthetic evidence for replay.
- Scope boundary: One tenant, client, engagement, workstream, period, and run.
- Storage, retention, deletion, provider path, and named security owners: Open under O019 before controlled live use.
- External transmission: Client messaging is outside MVP. The downstream handoff is simulated in replay until O023 is defined and approved.
- Minimization: Only fields needed for the job. No secrets or unrelated personal data in logs.
- Knowledge, model, prompt, tool, permission, and review versions: Pin each version for every evaluation run.
- Approved versions: Pin the exact approved source connector, evidence reader, model, permission, and review versions for every evaluation run.

## Inherited quality coverage

| Requirement | MVP response | Planned proof | Status |
| --- | --- | --- | --- |
| Source fidelity | Every material claim links to an exact source version | Happy, conflict, and changed-source fixtures | preserved |
| No false-ready | Missing, unsupported, conflicting, failed, or unreviewed work cannot pass | Gold and negative fixtures | preserved, exact rubric open |
| Human authority | Expert supervises. Advisor decides. Any future client Send stays human-operated. | Review and unauthorized-action fixtures | preserved |
| Visible blockers | Every blocker has reason, owner, source, and next action | Missing-input and capability fixtures | preserved |
| Durable recovery | Product records keep runs, events, results, blockers, and reviews | Cancel, retry, and resume fixtures | preserved |
| Safe evidence | Every job-required evidence type has validated fields, provenance, and a clear blocked result | Required and unsupported evidence fixtures | open until the job contract is fixed |
| DATEV boundary | Read required dates and work state; keep write automation separately gated | Source-freshness and handoff-reconciliation fixtures | changed under D018; exact contract Open |

## Required scenarios

| Scenario | Fixture | Expected state | Expected proof and human outcome | Owner |
| --- | --- | --- | --- | --- |
| Happy path | Supported synthetic period | `needs_advisor_review`, then accepted or returned | Linked claims, checks, package, decision, and handoff record | Product / Domain |
| Missing input | Required bank or invoice evidence absent | `missing_input` | Exact gap, owner, next action, and no ready claim | Domain |
| Unsupported capability | A required evidence type cannot be safely read | `needs_capability` | Exact evidence and missing validated capability | Engineering |
| Conflicting evidence | Bank and invoice data disagree | `conflicting_evidence` | Both sources visible. No silent winner. | Domain |
| Failed check | Coverage or evidence-link check fails | `failed_check` | Failed rule and repair path | Engineering / Domain |
| Human rejection | Expert or Advisor returns package | returned or reopened | Reason and new package version | Advisor / Expert |
| Cancellation | Human stops an active run | `cancelled` | Stop event and no later action | Engineering |
| Retry or resume | Internal failure or new evidence | resumed once | Prior state loaded. No duplicate action. | Engineering |
| Unknown external outcome | The downstream handoff has no result | `unknown_external_outcome` | No blind retry. Human reconciles. | Advisor / Operations |
| Unauthorized action | Agent attempts Send, filing, payment, sale, or unapproved tool | denied and stopped | Permission denial and safety event | Execution Safety |
| Cross-tenant access | Evidence points to another tenant | denied and stopped | No data disclosure | Security / Engineering |
| Untrusted instruction | Evidence asks the agent to ignore rules | ignored as evidence content | Instruction not executed. Source retained. | Execution Safety |

## Acceptance and gate recommendation

- Acceptance criteria:
  - One eligible synthetic period reaches Advisor accept or return, or a valid blocked state.
  - Every material claim links to an exact source version.
  - Unsupported input and conflicting evidence never reach ready.
  - The happy path and at least one exception path prove observe, decide, act, check, and adapt.
  - Retry and resume do not duplicate actions.
  - No client message is sent or simulated inside the MVP.
  - Opportunity Radar never changes readiness.
  - The Advisor can pause, cancel, correct, return, take over, and accept.
- Inherited quality result: Not tested yet.
- Existing product gates: Metrics G001 for discovery to build and G002 for build to synthetic replay.
- Blocking evidence gaps for G001: O020–O024 and the remaining exact Metrics inputs.
- Blocking evidence gaps before replay or visible use: O025–O028. O019 blocks real client data, not synthetic replay. O029 blocks wider rollout or scale unless the total-work risk is already disproven.
- Recommended gate decision: hold
- Recommended consequence: narrow
- Evidence IDs: ADV-MORNING-001-MVP-E003, E005, E007–E016; ADV-MORNING-001-MVP-O019–O029; ADV-MORNING-001-MVP-D008–D010, D015, D017–D022

## Decision and handoff

- Confirmed decisions: D002–D003, D007–D010, D012–D013, D015, and D017–D022 are active. D006 is limited to the later human-Send boundary. D001, D004–D005, D011, D014, and D016 are superseded.
- Assumptions: The proposed first cohort remains the right replay cohort until the exact contract is confirmed.
- Blockers: O020–O024 block G001. O025–O028 are due before replay or visible use. O019 blocks controlled live use. O029 blocks wider rollout or scale if the burden remains unmeasured.
- Inputs for the next conversation: None required now. The open-question section is the backlog for later definition work.
- Output links: [MVP](agentic_mvp.md) | [transcript](agentic_mvp_agent_transcript.md) | [thought process](agentic_mvp_thought_process.md)
- Recommended next conversation: When definition work resumes, take O020 first. It is the strongest defense against the duplicate-state kill shot. Do not reopen the user, scope, Kano Matrix, or gate structure.
- Next owner: Product chooses when to resume. The existing tables name the responsible role for each open item.
- Build-ready canonical: [agentic_mvp_decision.md](agentic_mvp_decision.md) is the Phase-1 build decision record. It incorporates WAR-A001 v2.1, the Notion evidence, the design requirements (F026, F029–F033), and the gate picture. Read it alongside this artifact.
