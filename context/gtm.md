# Evidence-Gated GTM Scenario: Internal SE-DIFM Advisor Workbench and Bookkeeping Preparation

- Artifact ID: ADV-MORNING-001-GTM-A001
- Artifact type: evidence-gated-gtm-scenario
- Version: 1.0
- Artifact completeness: complete
- Job ID: ADV-MORNING-001
- Canonical lifecycle stage: discovery
- Capability mode: mixed
- Requested transition: No product lifecycle or capability transition. Begin internal Taxfix SE-DIFM discovery and design-partner recruitment.
- Gate decision: go
- Decision consequence: continue
- Owner: Product / GTM
- Updated date: 2026-07-21
- Canonical brief: Open — no canonical JTBD dossier exists for this job
- Input artifacts: ADV-MORNING-001-SOTA-A001 v1.2 ([SOTA benchmark](SOTA/sota_benchmark.md)); ADV-MORNING-001-MVP-A001 v1.0 ([Agentic MVP](agentic_mvp.md)); ADV-MORNING-001-VIS-A001 v0.14 ([Product Vision](product_vision.md)); ADV-MORNING-001-MET-A001 v1.1 ([Metrics and gates](metrics_learning.md)); TAX-PLATFORM-CONTEXT-A001 v0.1 ([platform context](../tax-advisor-platform-context.md))
- Transcript link: [gtm_agent_transcript.md](gtm_agent_transcript.md)
- Thought-process link: [gtm_thought_process.md](gtm_thought_process.md)

## Evidence and decision register

| ID | Type | Status | Claim or decision | Source/link | Date | Owner | Confidence |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-GTM-E001 | fact | active | The job remains in discovery, in mixed capability mode, with a product gate of `hold` and a consequence of `narrow`. | [Product Vision](product_vision.md); [Metrics](metrics_learning.md) | 2026-07-21 | Product | high |
| ADV-MORNING-001-GTM-E002 | fact | active | The initial operating horizon is internal Taxfix Advisors serving SE-DIFM, with Tax Experts supervising preparation. The first client cohort is a product-directed hypothesis: German, VAT-liable freelancers and digital consultants with low document volume. | ADV-MORNING-001-VIS-D019; ADV-MORNING-001-MET-D006–D007 | 2026-07-21 | Product / Domain | high for direction; low for market validation |
| ADV-MORNING-001-GTM-E003 | fact | active | The first-shot design combines a full-day Advisor control layer with one deep bookkeeping-period preparation job. It has not yet produced user or operating results. | ADV-MORNING-001-MVP-D016; [MVP promise](agentic_mvp.md#promise-and-boundaries) | 2026-07-21 | Product | high for design; unproven for outcomes |
| ADV-MORNING-001-GTM-E004 | fact | active | Current approved deterministic runtime support is `csv_reader` / `csv_read`. Unsupported content must stop visibly. A PDF reader may be built in parallel but remains inactive until separately approved. | [Platform context](../tax-advisor-platform-context.md#capability-and-unsupported-input-rule); ADV-MORNING-001-MET-D010 | 2026-07-21 | Engineering / Execution Safety | high |
| ADV-MORNING-001-GTM-E005 | fact | active | Gate G001 blocks discovery-to-build until the case contract, owners, baseline plan, instrumentation, fixtures, and breach actions are fixed. Gate G002 cannot be evaluated until a precommitted synthetic replay exists. | ADV-MORNING-001-MET-G001–G002 | 2026-07-21 | Product | high |
| ADV-MORNING-001-GTM-E006 | fact | active | No five-day Advisor baseline, replay result, numeric threshold, observed adoption, buyer demand, ROI, opportunity quality, or live controlled-use proof exists. | ADV-MORNING-001-MET-O002, O004–O005; [evaluation limits](metrics_learning.md#evaluation-and-learning-plan) | 2026-07-21 | Product / Research | high |
| ADV-MORNING-001-GTM-E007 | fact | active | Existing market research supports staffing pressure, fragmented workflows, mixed inputs, and human professional responsibility. It does not prove demand for this product or its outcomes. | ADV-MORNING-001-SOTA-E007–E012, E025, E036, E038 | 2026-07-21 | Product / Research | medium-high with stated limits |
| ADV-MORNING-001-GTM-E008 | fact | active | The latest handoff contract is vendor-neutral, versioned, recorded, and human-operated. GFR-specific wording in older artifacts must not become a GTM dependency or claim. | ADV-MORNING-001-MET-D009, D011; ADV-MORNING-001-VIS-D023 | 2026-07-21 | Product / Operations | high |
| ADV-MORNING-001-GTM-E009 | fact | active | External marketplace or white-label expansion is parked until internal quality, trust, handling-time, business-value, tenancy, onboarding, and support proof exists. | [Product Vision roadmap](product_vision.md#configurable-roadmap) | 2026-07-21 | Product | high |
| ADV-MORNING-001-GTM-E010 | fact | limited | A dated internal self-employed sizing study indicates interest in the broader VAT-liable freelancer segment and an end-client price range. It does not validate the low-document-volume or digital-consultant qualifiers, the TA Platform offer, or a platform price. | [MVP source audit](agentic_mvp_source_audit.md#f2--cohort-qualifiers-low-document-volume-and-digital-consultants-are-not-backed-by-the-sized-research--medium) | 2026-07-21 | Product / Research | low for GTM pricing |
| ADV-MORNING-001-GTM-D001 | decision | active | The first GTM target is Taxfix's internal SE-DIFM operation. No external-practice discovery track runs in parallel. | User confirmation | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-D002 | decision | active | The internal design-partner offer tests the complete confirmed Kano package: the daily Advisor workbench, source-system continuity, one deep bookkeeping mission, trust and human control, one AI front door, Taxfix client flow, agentic bookkeeping preparation, in-app client communication, Opportunity Radar, and the AI-assisted missing-evidence loop. This is test scope, not a claim that every part works today. | User confirmation; [MVP Kano Matrix](agentic_mvp.md#kano-matrix-for-the-mvp) | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-D003 | decision | active | Start internal discovery and design-partner recruitment now. This permits invitations, workflow learning, co-design, baseline preparation, and synthetic test setup. It does not approve the product build gate, real-client use, live operation, or a customer price. | User confirmation | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-D004 | decision | active | The internal commercial sponsor role is the Taxfix Advice SE-DIFM business or operations owner. Product runs the GTM work. Domain, Advisor, Operations, Execution Safety, and Security/Privacy owners retain stop rights in their areas. The actual people must be named before the relevant gate. | User confirmation | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-D005 | decision | active | Use a seven-stage GTM path: internal Advisors and Tax Experts; internal soft launch after proof; testing with seven partner tax-advisory companies; a joint internal-and-partner green gate; selected-partner soft launch; rollout to the approved partner network; then open-market expansion. | User direction | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-D006 | decision | active | Claims widen by passed evidence gate, not by calendar date. A stage is green only when users want to continue and the pre-agreed quality, safety, usage, support, and value checks pass. Confidence cannot override a failed hard guardrail. Automatic client contact, selling, filing, payment, signing, and professional judgment remain forbidden under the current product contract. | User confirmation | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-H001 | hypothesis | superseded | Superseded by D001. | D001 | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-H002 | hypothesis | superseded | Superseded by D004. | D004 | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-H003 | hypothesis | superseded | Superseded by D002. | D002 | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-H004 | hypothesis | superseded | Superseded by D003. | D003 | 2026-07-21 | Product / Finance / GTM | high |
| ADV-MORNING-001-GTM-H005 | hypothesis | superseded | Superseded by D005 for the staged recruitment route. Exact invitation mechanics remain an execution detail. | D005 | 2026-07-21 | Product / Research / Operations | high |
| ADV-MORNING-001-GTM-H006 | hypothesis | superseded | Superseded by D006. | D006 | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-H007 | hypothesis | active | German VAT-liable freelancers and digital consultants with low document volume remain the best initial case cohort for internal and partner proof. This is a product assumption until direct observation and cohort evidence confirm it. | E002, E010 | 2026-07-21 | Product / Domain / GTM | medium |
| ADV-MORNING-001-GTM-H008 | hypothesis | active | Seven partner tax-advisory companies can expose enough variation to decide whether a selected-partner soft launch is justified. The partner mix and minimum evidence volume must be fixed before Stage 3. | D005 | 2026-07-21 | Product / Partner GTM | medium |
| ADV-MORNING-001-GTM-O001 | open question | narrowed | D001 confirms the internal target and D004 confirms the sponsor and decision roles. The actual people must still be named before the relevant gate. | D001, D004 | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-O002 | open question | resolved | D006 confirms the stage-based claim ladder, permanent authority boundaries, and evidence-based meaning of green. | D006 | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-O003 | open question | resolved | D003 authorizes internal discovery recruitment, keeps product G001 on hold, and defers customer pricing until operating proof exists. | D003 | 2026-07-21 | Product / GTM | high |
| ADV-MORNING-001-GTM-O004 | open question | delegated | Before Stage 3, Partner GTM must name the seven partner firms, define a useful mix of firm and client profiles, and precommit the minimum evidence volume and partner-green thresholds. | D005, H008 | 2026-07-21 | Product / Partner GTM | high |

## Conversation decisions

- Confirmed target segment, user, buyer, and signer: D001 confirms Taxfix's internal SE-DIFM operation as the first target. D004 fixes the sponsor and decision roles. Actual people remain Open under O001.
- Confirmed current promise and forbidden claims: D002 confirms the complete Kano package. D005 fixes the seven stages. D006 makes claims evidence-gated, defines green, and fixes the permanent authority boundaries.
- Confirmed offer and channel: D005 fixes the route from internal Advisors and Tax Experts through seven partner firms, partner rollout, and later open-market expansion. Exact invitation mechanics are an execution detail.
- Confirmed proof and commercial gate: D003 records `go` → `continue` for internal discovery recruitment only. Product gates G001 and G002 remain unchanged.
- Confirmed pricing or learning hypothesis: D003 confirms no customer price until operating proof exists. Internal learning uses M008, M014, and later M022–M024.
- Matters explicitly delegated to the agent: Read the completed WoW evidence, identify the stage-honest GTM boundary, draft options and a recommendation, and turn the confirmed decisions into the final scenario, transcript, and reader-facing summary.

## Product and measurement basis

- Product roadmap ID, version, and link: ADV-MORNING-001-VIS-A001 v0.14, [Product Vision](product_vision.md).
- Measurement contract ID, version, and link: ADV-MORNING-001-MET-A001 v1.1, [Metrics and gates](metrics_learning.md).
- Current lifecycle stage: discovery.
- Current capability mode: mixed. Current runtime support is narrower than the future mixed-mode product design.
- Latest product gate decision and consequence: `hold` → `narrow`.
- Proven user value: None yet. The user problem and product choices are supported, but no product outcome has been measured.
- Available capabilities and allowed effects: Approved `csv_reader` / `csv_read`; durable internal task, run, event, result, and review concepts; synthetic Taxfix-owned data; reversible internal preparation; recorded human-operated handoff in replay.
- Planned but unavailable capabilities: Full Advisor workbench proof; agentic bookkeeping outcome proof; active PDF reading; real-client data path; live DATEV or other external-system integration; controlled-live operation; reliable opportunity signals; external marketplace or white-label delivery.
- Metric and guardrail IDs used: ADV-MORNING-001-MET-G001–G002; M001, M003–M005, M008, M012–M016, M021–M030.
- Claims currently allowed: We are recruiting an internal discovery cohort to co-design and test the defined workflow; the evaluation keeps human authority and explicit stop rules; current support and limits are stated exactly.
- Claims currently forbidden: Live or production-ready product; current whole-day outcome improvement; tax correctness; time, capacity, revenue, ROI, conversion, trust, or adoption gains; broad document support; live DATEV integration; external-market availability; formal Seal or PACS. These current-stage claim limits widen only after the relevant evidence gate passes. Automatic client contact, selling, filing, payment, signing, or professional judgment remain forbidden authority boundaries under the current product contract.

## Research coverage

- Research mechanisms used: supplied sources.
- Research limitations or blockers: Existing sources support the problem context and competitor capabilities. Direct Advisor observation, named buyer evidence, product-specific willingness to pay, procurement evidence, and outcome proof are missing. No new external numeric target is used.

| Source ID | Publisher | URL | Access date | Supported market or buyer claim | Evidence quality | Claim status |
| --- | --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-SOTA-E007 / E025 / E038 | BStBK / IfD Allensbach | [STAX 2024](https://www.bstbk.de/downloads/bstbk/recht-und-berufsrecht/fachinfos/02_Sonderauswertungen_Digitalisierung_Fachkraeftemangel_STAX2024.pdf) | 2026-07-15 | German tax practices report staffing pressure, digital blockers, and mixed client connectivity. | Representative weighted self-report; not workflow observation | accepted with limits |
| ADV-MORNING-001-SOTA-E036 | BStBK | [FAQ zum Einsatz generativer KI](https://www.bstbk.de/downloads/bstbk/digitalisierung/BStBK_FAQ-KI_end.pdf) | 2026-07-15 | Professional responsibility, secrecy, monitoring, and data-path duties remain with the practice and Advisor. | Primary professional guidance; not outcome proof | accepted |
| ADV-MORNING-001-SOTA-E013–E015 | DATEV | [Tasks](https://wissensplattform.apps.datev.de/help/document/9216659) | 2026-07-15 | Mature conventional products already cover task, order, checklist, rights, handoff, and source-linked control patterns. | Current vendor operating documentation; no independent outcome proof | accepted with limits |
| ADV-MORNING-001-SOTA-E018–E020 | milia | [Kanzleisteuerung](https://milia.io/kanzleisteuerung) | 2026-07-15 | A modern German competitor markets practice-wide control and assistive AI; multi-step agents were not proven as broadly available. | Vendor evidence | limited |
| ADV-MORNING-001-SOTA-E022–E024 | Karbon | [Karbon](https://karbonhq.com/) | 2026-07-15 | A global adjacent product shows an agentic interaction direction but lacks German and DATEV fit. | Vendor and limited-access evidence | limited |

## Commercial role and target

- Primary role: platform-enabler.
- Secondary role: activation and internal monetization learning; later retention and expansion.
- Directly marketed: no.
- Target organization and segment: Taxfix Advice internal SE-DIFM operation. Initial end-client case hypothesis: German VAT-liable freelancers and digital consultants with one low-document-volume bookkeeping month.
- Daily user: Internal Taxfix Advisor. Tax Experts supervise bounded preparation.
- Buyer and signer: Confirmed role — Taxfix Advice SE-DIFM business or operations owner is the internal sponsor. Product runs GTM and owns the product gate. Domain, Advisor, Operations, Execution Safety, and Security/Privacy owners retain stop rights. Actual people are Open.
- Beneficiary: The Advisor, the Tax Expert, the SE-DIFM client, and Taxfix if capacity and service quality improve.
- Current alternative: The Advisor coordinates work across current tools and manually completes the approved downstream handoff. DATEV and ELSTER remain statutory systems of record.
- Acute pain: Evidence hunting, copy-paste, repeated client chasing, weak handovers, hidden work, and rebuilding context. Direct observation must still measure the actual burden.
- Buying trigger and why now: Internal capacity and coordination pressure plus an eligible SE-DIFM workflow that can be bounded and measured. The immediate trigger is a named sponsor, named Advisor cohort, five-day baseline access, and a fixed case contract—not a calendar launch date.

## Offer

- Offer type: design-partner.
- Plain-language promise: Confirmed scope, draft wording — “Help us test the complete first Tax Advisor Platform experience: one daily workbench, source-system continuity, one deep bookkeeping mission, visible trust and human controls, one AI front door, stronger Taxfix client flow, agentic preparation, linked client communication, one evidence-backed opportunity, and an AI-assisted missing-evidence loop. The system must prepare supported work or stop clearly. The Advisor keeps every professional and consequential decision.”
- Kano package included in the offer:
  - Must-haves: SOTA daily Advisor workbench; source-system continuity; one deep bookkeeping mission; trust and human control; real agents behind one front door.
  - Performance accelerators: Taxfix client flow; agentic bookkeeping preparation; in-app Advisor-client communication.
  - Delighters: Opportunity Radar; AI-assisted missing-evidence loop.
  - Stage boundary: Every item is part of the product test. None is marketed as a proven current outcome.
- Proof required: Direct five-day workflow observation; closed G001 inputs; precommitted synthetic replay; G002 results; zero stop-level safety events; complete evidence links; measured Advisor effort and action coverage. Controlled live needs a separate real-data and operating gate.
- Scope, cohort, and eligibility: Named internal SE-DIFM Advisors and Tax Experts; synthetic replay first; one German VAT-liable freelancer or digital-consultant bookkeeping month; exact low-volume rule, schema, exclusions, and replay volume remain Open.
- Exclusions and forbidden effects: Real-client data in replay; automatic contact or sale; filing, payment, signing, or professional judgment; live automated external-system writes; candidate-tool execution; unsupported parsing; automatic scope, price, lifecycle, or authority expansion.
- Recruitment channel: Stage 1 uses direct internal nomination. Stage 3 recruits seven partner tax-advisory companies. Stage 5 opens a selected-partner soft launch. Stage 6 expands to the approved partner network. Open-market acquisition starts only at Stage 7. Exact invitation mechanics and partner names remain Open.
- Onboarding and support: Explain the job, current limits, Trace and blocker model, manual fallback, feedback method, and incident route. Observe five normal workdays. Train the cohort on synthetic replay. Provide high-touch Product, Domain, Engineering, and Operations support during learning.
- Controls, correction, escalation, and fallback: Advisor and Expert can pause, cancel, correct, return, retry, resume, take over, or use the current manual workflow. Stop-level events contain the affected evaluation and require fresh human approval after remediation.
- Integration, procurement, and security path: No procurement for the internal discovery cohort. No live integration claim. Use the vendor-neutral human-operated handoff contract. Before real data, require professional, execution-safety, security, privacy, provider, retention, deletion, and tenant approvals.
- Pricing hypothesis and evidence: No customer price in discovery. Track M008 and M014 first. Later test whether M022–M024 show capacity and contribution gains. Dated end-client WTP research does not set a TA Platform price.
- Expansion path: Internal Advisors and Tax Experts → evidence-gated internal soft launch → testing with seven partner tax-advisory companies → joint internal-and-partner green gate → selected-partner soft launch → approved partner-network rollout → open-market expansion.

## Configurable offer roadmap

| Offer move | Lifecycle stage | Capability mode | Target and need | Honest promise | Proof and metric IDs | Offer and pricing mode | Next commercial gate |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1. Internal discovery and replay | discovery → build → replay after G001 | mixed; synthetic L2 preparation only during replay | Internal SE-DIFM Advisors and Tax Experts | Co-design and test the complete Kano package. No live or outcome claim. | G001–G002; M001, M003–M005, M008, M012–M016, M021, M029–M030 | Internal design-partner; no customer price | Internal soft-launch gate |
| 2. Internal soft launch | controlled-live, after separate authorization | mixed within approved effects | Approved internal SE-DIFM cohort | Available to the named internal cohort for the exact proven jobs and effects | G002 plus fresh live-data, support, rollback, adoption, and safety gate; M020–M024 | Internal operating offer; business case, not customer price | Seven-partner test gate |
| 3. Seven-partner test | shadow → controlled-live as separately approved | mixed; only proven jobs and effects | Seven partner tax-advisory companies | Partner test of the exact scope. Internal results are context, not partner proof. | Partner-specific baseline, quality, adoption, onboarding, tenancy, support, security, and economics | Design-partner or pilot terms; partner price hypothesis Open | Joint internal-and-partner green gate |
| 4. Joint green decision | No automatic lifecycle change | No automatic capability change | Internal cohort and all seven partner firms | No market claim. This is a human go, hold, or kill decision. | Pre-agreed internal and partner thresholds; zero stop-level breach; H006 | Decision gate; no new price | Selected-partner soft-launch decision |
| 5. Selected-partner soft launch | controlled-live for approved partners | mixed within approved partner scope | A selected subset of the seven partner firms | Available to named partner firms for the proven cohort, jobs, effects, and support model | Joint-green evidence plus soft-launch readiness, contracts, support, incident path, and pricing evidence | Limited partner offer; tested commercial terms | Partner-network rollout gate |
| 6. Approved partner-network rollout | scale within the approved partner cohort | mixed by proven job | All eligible firms in the approved Taxfix partner network | Available across the approved partner network for the defined supported scope | Repeatable onboarding, quality, adoption, support, economics, tenancy, and incident performance | Partner offer with validated pricing and terms | Open-market gate |
| 7. Open-market expansion | scale for the approved external segment | mixed by proven job | Defined German tax-practice segment serving self-employed people and SMEs | Generally available only for the named eligible cohort, supported jobs, effects, formats, and integrations | Partner-scale proof plus direct market demand, procurement, willingness to pay, repeatable acquisition, service, and support evidence | Production offer; validated market price | Ongoing segment and capability expansion gates |

## Evidence-to-claim register

| Claim ID | Buyer-facing claim | Valid cohort | Lifecycle stage | Capability mode | Metric and evidence IDs | Limitations | Allowed wording | Owner and review date |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-GTM-CLM001 | Internal discovery invitation | Named internal SE-DIFM Advisors and Tax Experts | discovery | mixed design; no expansion | E001–E007; G001 | This is co-design and baseline work, not a product result. | “We are co-designing and testing a bounded Advisor workbench and bookkeeping flow.” | Product / GTM; review before first invitation |
| ADV-MORNING-001-GTM-CLM002 | Test objective | Same internal discovery cohort | discovery | mixed design; no expansion | D002; M001, M008, M015–M016 | The desired outcome is not proven. | “We will test whether the complete Kano package helps the Advisor run the day and prepares an eligible period into a source-linked review package or a clear blocked state.” | Product / Domain / GTM; review before first invitation |
| ADV-MORNING-001-GTM-CLM003 | Human-control contract | Same internal cohort | discovery and later approved modes | mixed | E004–E005; M012–M013 | Describes the authority contract, not reliability or tax correctness. | “The Advisor keeps professional judgment, client contact, acceptance, and consequential actions.” | Product / Execution Safety; review before every mode |
| ADV-MORNING-001-GTM-CLM004 | Current support boundary | Internal technical and evaluation stakeholders | discovery | current narrow runtime support | E004; M029–M030 | No broad document or production claim. | “Current approved runtime support is narrow. Unsupported content stops visibly. New readers stay inactive until separately approved.” | Engineering / Execution Safety; review on every capability change |
| ADV-MORNING-001-GTM-CLM005 | Internal soft-launch availability | Named approved internal SE-DIFM cohort | controlled-live after approval | mixed within approved effects | G002 plus separate controlled-live gate and live results | Does not imply partner or market availability. | “Available to the approved internal Taxfix cohort for the named supported jobs.” | Product / GTM; review at internal soft-launch gate |
| ADV-MORNING-001-GTM-CLM006 | Partner-test availability | Seven named partner tax-advisory companies | shadow or controlled-live as approved | mixed within approved partner scope | Partner-specific evaluation evidence | This is a test, not a partner-network or market launch. | “We are testing the proven internal scope with seven partner tax-advisory companies.” | Product / Partner GTM; review before partner invitations |
| ADV-MORNING-001-GTM-CLM007 | Selected-partner availability | Named soft-launch partners | controlled-live | mixed within approved scope | Joint-green gate plus soft-launch evidence | Does not imply availability to all partners or the market. | “Available to selected Taxfix partner firms for the defined supported scope.” | Product / Partner GTM; review at soft-launch gate |
| ADV-MORNING-001-GTM-CLM008 | Partner-network availability | Approved eligible partner network | scale within partner cohort | mixed by proven job | Network rollout evidence | Does not imply open-market general availability. | “Available to eligible firms in the approved Taxfix partner network for the defined supported scope.” | Product / Partner GTM; review at network rollout gate |
| ADV-MORNING-001-GTM-CLM009 | Open-market availability | Defined eligible German tax-practice segment | scale | mixed by proven job | Scale and commercial evidence for the exact market cohort | Never use absolute claims such as every firm, every document, or fully autonomous. | “Generally available for the named eligible cohort, supported jobs, formats, integrations, and controls.” | Product leadership / GTM; review at market gate and on every scope change |

## Friction and learning

| Objection or blocker | Evidence today | Test or response | Owner | Decision affected |
| --- | --- | --- | --- | --- |
| “Is this a real Advisor problem or an internal product idea?” | Market signals exist, but no direct five-day observation. | Observe named Advisors across five normal days and record the current alternative, effort, interruptions, and material work. | Product / Advisors / Research | Continue or narrow internal discovery |
| “Why this cohort?” | VAT-liable freelancers have broad sizing support. Low volume and digital consultants are product assumptions. | Verify eligible case volume, document mix, pain, and cohort fit before G001. | Product / Domain / Operations | Cohort and eligibility |
| “Does it work?” | No outcome result exists. | Close G001, build, and run precommitted synthetic replay against G002. | Product / Domain / Engineering | Any capability or product promise |
| “Will it save time or create capacity?” | No baseline or result exists. | Measure M008 and M015 first; use M022–M024 only in a later approved operating mode. | Product / Research / Finance | Business case and expansion |
| “Can it read our real documents?” | Current approved runtime support is narrow. | Keep unsupported formats blocked. Promote each reader only after its separate proof. | Domain / Engineering / Execution Safety | Eligibility and claim scope |
| “Will Advisors trust and adopt it?” | No adoption or trust proof exists. | Capture corrections, returns, takeovers, parallel-system use, and M020–M021 in later approved evaluation. | Product / Advisors / Operations | Internal rollout |
| “What does it cost?” | No product-specific WTP or unit-economics proof exists. | Track M014 and M024. Run buyer and procurement research only when an external offer is unparked. | Product / Finance / GTM | Pricing and external GTM |
| “Is DATEV automated?” | No. The latest approved claim is a vendor-neutral human-operated handoff. | Keep the manual recorded fallback. Gate any connector separately. | Product / Operations / Engineering | Integration and onboarding |
| “Can we launch outside Taxfix?” | External demand, tenancy, onboarding, support, ROI, and procurement proof are absent. | Keep external expansion parked until internal proof and direct external discovery exist. | Product leadership / GTM | External expansion |
| “Where is the canonical decision?” | No JTBD dossier exists. | Create or update the canonical dossier before any lifecycle or commercial-launch decision is treated as authoritative. | Product | Lifecycle and gate authority |

## Commercial gates

| Gate or decision | Required product evidence | Required commercial evidence | Guardrails | Go when | Hold when | Kill when | Consequence | Human owner |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1. Internal discovery recruitment — current decision `go` | Current scope, limits, and research protocol; G001 is not required to begin invitations and setup | Internal target, sponsor role, and complete Kano offer are confirmed. Named people and access close during recruitment. | No live claim, no automatic action, no sensitive data in unapproved paths | Invitations and setup may start now | Pause observation if named people, access, safe wording, or owners are missing | The team will not provide workflow access or the job is not material enough to study | `continue` internal recruitment and setup | Product / GTM / Advice sponsor |
| 2. Internal soft launch | G001 and G002 pass; controlled-live data, support, fallback, and rollback approval exists | Internal users choose continued use; training and support are ready; the internal business case is credible | Every hard guardrail passes; human authority remains; no unapproved real-data path | Product proof, user confidence, adoption, operations, and live authorization are green | Any proof, owner, support, or authorization is incomplete | A stop-level failure cannot be removed by narrowing | `go`: limited internal availability; `hold`: keep testing; `kill`: park or stop | Product / Advice sponsor plus control owners |
| 3. Test with seven partner firms | Internal soft launch is stable; partner-safe tenancy, data, permissions, onboarding, and support exist | Seven named partner firms commit users, cases, time, feedback, and commercial discovery access | Internal proof is not treated as partner proof; partner data and authority stay isolated | The partner cohort and test contract are fixed and safe | Firms, cases, support, data path, or test terms are incomplete | The partner model cannot be made safe, useful, or supportable | `go`: partner test; `hold`: narrow or delay | Product / Partner GTM / Partner sponsor plus control owners |
| 4. Joint internal-and-partner green gate | Internal and partner quality, safety, recovery, and support evidence meets pre-agreed thresholds | Both cohorts show confidence, adoption intent, usable onboarding, and credible economics | Confidence cannot override a failed hard guardrail | Internal and all required partner evidence is green | Either cohort is weak, mixed, or underpowered | The offer fails both cohorts or cannot work economically inside the trust boundary | `go`: selected-partner soft launch; `hold`: iterate or narrow; `kill`: park or stop | Product leadership / Advice / Partner GTM |
| 5. Selected-partner soft launch | Joint green gate passes; limited production operations and incident response are ready | Selected firms accept the supported scope, terms, training, support, and pricing hypothesis | Claims stay limited to named partners, cohorts, jobs, formats, integrations, and effects | Selected partners and operating owners are ready | Contracts, support, price, or operating readiness is incomplete | Repeated partner harm or unfixable economics appears | `go`: limited partner offer; `hold`: remain in partner test | Product / Partner GTM / Operations |
| 6. Approved partner-network rollout | Soft-launch quality, adoption, support, recovery, and economics hold across meaningful partner variation | Onboarding, training, support, terms, and pricing repeat across the approved partner network | No scope inflation; cohort differences remain visible | The offer repeats without exceptional support or hidden quality loss | Results depend on hero support, one firm type, or unproven scope | Network economics or safety cannot work after narrowing | `go`: roll out to eligible partners; `hold`: keep selected scope | Product leadership / Partner GTM / Operations |
| 7. Open-market expansion | Partner-network quality, operations, tenancy, security, support, and unit economics hold at scale | Direct market demand, procurement, willingness to pay, repeatable acquisition, onboarding, and retention evidence exists | No absolute capability claims; human authority and stage-specific scope remain explicit | Product and market proof support a defined public offer | Market demand, price, acquisition, support, or transfer proof is missing | The public offer cannot acquire and serve customers safely and economically | `go`: launch to the defined market cohort; `hold`: remain partner-only; `kill`: park open market | Product leadership / GTM |

## Decision

- Requested commercial decision: Begin internal discovery under D003 and progress through the seven stages only when D006's green rule passes.
- Proposed gate decision: go, confirmed by D003.
- Proposed consequence: continue internal discovery, confirmed by D003. The product gate remains `hold` → `narrow`.
- Decision metric and evidence IDs: ADV-MORNING-001-GTM-E001–E010; D001–D006; H007–H008; ADV-MORNING-001-MET-G001–G002; M001, M003–M005, M008, M012–M016, M020–M024.
- Rollback or stop conditions: No named sponsor or cohort; no access to real workflow; insufficient eligible case volume; unsafe research or data path; unsupported product claims; or evidence that the job is not material enough for the cohort.
- Automatic outreach, selling, pricing, launch, or expansion: forbidden.

## Decision and handoff

- Confirmed decisions: D001–D006.
- Assumptions and hypotheses: H007–H008. H001–H006 are superseded by D001–D006.
- Blockers: O001 and O004 are delegated execution inputs; the canonical JTBD dossier is missing; product G001 remains on hold; direct user, adoption, partner-transfer, pricing, and outcome evidence is absent.
- Inputs the next conversation should read: This scenario, the internal cohort and sponsor names when available, the five-day baseline plan, the exact G001 proof contract, and later the seven-partner selection and evidence plan.
- Output links: [this artifact](gtm_scenario.md) | [transcript](gtm_agent_transcript.md) | [thought process](gtm_thought_process.md) | canonical brief: Open
- Recommended next conversation: Name the internal sponsor and cohort, then prepare the five-day baseline and close the G001 proof contract. Partner selection starts only after the internal soft-launch gate is credible.
