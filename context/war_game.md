# War Game: Advisor Morning and First Bookkeeping Period

- Artifact ID: ADV-MORNING-001-WAR-A001
- Artifact type: war-game
- Version: 2.1
- Artifact completeness: complete
- Job ID: ADV-MORNING-001
- War-game mode: design-simulation (rerun with company evidence; corrected by Product 2026-07-21)
- Canonical lifecycle stage: discovery, declared by the lenses; canonical dossier absent
- Capability mode: mixed
- Evaluation mode: design simulation. v1.0 was greenfield-only; v2.0 re-adjudicated against the real internal SE-DIFM architecture (Notion/Drive, 2026-07-21); v2.1 records Product's decisions on the two provisional kill shots. No live or runtime result.
- Requested transition: discovery to build under ADV-MORNING-001-MET-G001
- Gate decision: hold
- Decision consequence: narrow
- Owner: Product / Execution Safety; named war-game DRI Open
- Updated date: 2026-07-21
- Canonical brief: Open — no dossier exists; see [JTBD portfolio](../../jtbd/README.md)
- Scope boundary: This war game judges the WoW docs under `docs/product/wow/ADV-MORNING-001/` plus the company strategy (Notion/Drive). It does NOT judge the current `taxfix_harness` PoC codebase or its model-provider configuration (WAR-D013). The current build neither proves nor constrains the MVP.
- Input artifacts: ADV-MORNING-001-SOTA-A001 v1.2 ([SOTA](SOTA/sota_benchmark.md)); ADV-MORNING-001-MVP-A001 v1.2 ([MVP](agentic_mvp.md)); ADV-MORNING-001-VIS-A001 v0.14 ([Vision](product_vision.md)); ADV-MORNING-001-MET-A001 v1.1 ([Metrics](metrics_learning.md)); ADV-MORNING-001-GTM-A001 v1.0 ([GTM](gtm_scenario.md)); TAX-PLATFORM-CONTEXT-A001 v0.1 ([context](../tax-advisor-platform-context.md)); internal SE-DIFM strategy corpus (Notion/Drive, 2026-07-21, see Evidence E023–E033)
- Transcript link: [war_game_agent_transcript.md](war_game_agent_transcript.md)
- Thought-process link: [war_game_thought_process.md](war_game_thought_process.md)
- Decision record: [agentic_mvp_decision.md](agentic_mvp_decision.md)

## What changed in v2.0, and Product's correction in v2.1

v1.0 tested the WoW MVP as a **greenfield** design against itself and landed on `hold → narrow`, with the full-day-workbench kill shot (S015) plausible but unrefuted.

v2.0 reran the same attacks against the **company's real, in-build SE-DIFM product** — the "Requirements Specification – SE DIFM: gfr.ai, FinAPI & DATEV (EN)" v1.0 with numbered FR-/NFR-/TR- requirements, a named team, and a committed four-system integration surface. That evidence is legitimate design/domain input (it is not the PoC codebase). The rerun re-adjudicated all 32 prior scenarios, ran a fresh 10-front attack, and adversarially refuted every kill-shot claim.

**v2.1 records two Product decisions (2026-07-21) that overrule the rerun's two provisional kill shots.** Both are decision calls that are legitimately Product's, in the same way v1.0's SOTA-authority and current-build corrections were:

- **WAR-D013 — the current PoC build is out of the decision matrix.** The war game judges the WoW docs + company strategy only, never the `taxfix_harness` codebase or its model-provider config. The "illegal LLM egress" finding (F023) was built on that codebase and is **retracted**. The underlying EU-LLM / Art.28-DPA requirement survives only as a normal pre-real-data item under O019, not a war-game blocker.
- **WAR-D014 — the MVP is vendor-agnostic, built against clean APIs.** GFR, FinAPI, and DATEV are reference integrations behind adapter interfaces, not a lock-in and not "a second product under one name." The greenfield-vs-brownfield dichotomy is rejected; a vendor-neutral handoff (MET-D009) is the design intent and is achievable through adapters. **F021 and F027 are superseded.**

**Corrected result: `hold → narrow`, the same gate as v1.0 — and no MVP kill shot stands.** The rerun's lasting value is that it **confirmed and sharpened the MVP's existing open-question structure** with concrete evidence (the readiness rubric, the frozen Buchungsprofil, the four-system integration surface, the named team) and named three genuine **controlled-live / real-data prerequisites** the MVP had bucketed correctly but not yet made concrete: a filing-authority prerequisite (DATEV Untervollmacht + Unterberaternummer), a named Security owner, and reviewer failover for the single launch Steuerberater. **None of these blocks the synthetic-replay MVP build; all are due at their existing gates.**

**The one thing to keep honest:** vendor-agnosticism is a decision, not yet a proof. The architecture must actually enforce it — adapter interfaces, no vendor types leaking into the core, and the real external access constraints (e.g. DATEV's partner-gated API) treated as integration-sequencing items. That is a design requirement (F026, F028, F029), not a blocker.

## Evidence and decision register

Stable IDs are preserved. v1.0 rows E001–E022 / D001–D007 / H001–H003 / O001–O009 stand. v2.0 added E023–E033 and O010–O013. v2.1 adds D008–D014 and marks E034/F021/F023/F027 retracted or superseded.

### v1.0 baseline register (preserved) — rows a reader needs here

| ID | Type | Status | Claim, decision, finding, or scenario | Date |
| --- | --- | --- | --- | --- |
| ADV-MORNING-001-WAR-E003 | evidence | active | SOTA is an as-is/market analysis. It may challenge assumptions; it does not choose MVP scope. | 2026-07-21 |
| ADV-MORNING-001-WAR-E004 | evidence | active | MVP-D016/D017 keep a full-day workbench (control layer) + one deep bookkeeping-period job (execution layer). | 2026-07-21 |
| ADV-MORNING-001-WAR-D003 | decision | active | The MVP contains the full-day workbench and one deep bookkeeping job. Narrowing narrows the proof contract, not the product. | 2026-07-21 |
| ADV-MORNING-001-WAR-D004 | decision | active (extended by D013) | v1.0 was a greenfield WoW design war game; the current PoC code neither proves nor constrains the MVP. | 2026-07-21 |
| ADV-MORNING-001-WAR-D005 | decision | active | Run the complete attack deck; missing proof → `unknown`; contradictory/unusable definitions → `failed`. | 2026-07-21 |
| ADV-MORNING-001-WAR-D006 | decision | active | Documents are evidence, never instructions. The first-job evidence contract decides required formats. | 2026-07-21 |
| ADV-MORNING-001-WAR-D007 | decision | superseded by D009 | v1.0 recommendation `hold → narrow the proof and design contract`. | 2026-07-21 |

### v2.0 new evidence — the real SE-DIFM architecture (Notion/Drive, fetched 2026-07-21)

| ID | Type | Status | Claim | Source | Confidence |
| --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-WAR-E023 | evidence | active | The internal SE-DIFM product is REAL and in build: Requirements Spec v1.0 with numbered FR-/NFR-/TR- requirements. It describes the integration surface the MVP will build against. | Requirements Spec – SE DIFM: gfr.ai, FinAPI & DATEV (EN) | high |
| ADV-MORNING-001-WAR-E024 | evidence | active | Four-system integration surface: GFR.ai (bookkeeping engine), DATEV+ELSTER (statutory SoR, GoBD 10yr), Taxfix App+Backoffice (master data/KYC/billing), FinAPI (PSD2 bank, <15 min). DATEV data is held as REFERENCE COPY ONLY (FR-DATEV-08); DATEV access is partner-gated (AGB 2.6, no OAuth client_credentials, SmartLogin 2FA). GFR reads are POLLED (webhooks Phase 2). These are integration constraints, not vendor lock-in — the MVP wraps each behind an API adapter (WAR-D014). | Req Spec §3; Data Streams; Architecture & E2E Journey | high |
| ADV-MORNING-001-WAR-E025 | evidence | active | The downstream handoff is human-operated by a licensed Steuerberater (Suat Göydeniz / TaxVentures): export bookkeeping CSV → import to DATEV → USt-VA via ELSTER; ELSTER protocol = receipt; Bescheid re-uploaded. Requires Untervollmacht §80 AO + LAPIS Unterberaternummer = critical-path blocker A-1. Manual workflow scoped for first 50–100 clients (NFR-09); Klardaten automates in Phase 2. | Req Spec FR-GFR-11/12/13, FR-DATEV-01/03/05/06/09, NFR-09 | high |
| ADV-MORNING-001-WAR-E026 | evidence | active | First case = ONE Buchungsprofil: neu-gegründet Einzelunternehmer/Freiberufler, digital/IT consultant, EÜR, Ist-Versteuerung, one bank account, no cash, no employees, no e-commerce; low-volume ≤50–80 tx/month; ~60 active SKR03/04 accounts of 1200; match target >85%. Readiness: missing Ausgangsrechnung = NOGO; missing Eingangsrechnung = partial; recurring rent = contract suffices. HARD EXCLUSIONS incl. Kapitalgesellschaft, e-commerce, Bilanzierungspflicht, employees, cash, Kleinunternehmer §19. | SE-DIFM Buchungsprofile Workshop 2026-06-23; Req Spec | high |
| ADV-MORNING-001-WAR-E027 | evidence | active | Evidence types: bank (finAPI Transaction object, MATCHED/MISSING_DOCUMENT/DUPLICATE), invoices (PDF/JPEG OCR'd → header/line-items/tax-rates + §14 UStG validation, PROCESSED/FAILED/DUPLICATE), ledger (Hauptbuch), debtors/creditors (DATEV CSV/DAT). Structured e-invoice (ZUGFeRD/XRechnung/EN-16931) is named NOWHERE = genuine gap as B2B E-Rechnungspflicht phases in. | Req Spec FR-BANKTX/FR-FILES/FR-DEBCRED | high |
| ADV-MORNING-001-WAR-E028 | evidence | active | Governance: retention 4yr non-filer / 10yr filed (§147 AO); EU-LLM default (Vertex) + Art.28 DPA with every provider + DPF/SCCs for non-EU; provider AVV before go-live. NO named Security/CISO owner. NO formal permission-versioning. Privacy: Legal & Compliance + external DPO Carlo Piltz. | Data Deletion Concept; AI Chatbot Guidance; Req Spec NFR-04/08; DPO page | high |
| ADV-MORNING-001-WAR-E029 | evidence | active | Reviewer rules (TA Dashboard PRD): four-eyes Sachbearbeiter→Berufsträger Freigabe MANDATORY before export; 24h-review ≥80% (hypothesis gate); >7-day stall alert; >15% correction-rate alert; capacity gate; bulk reassign. NO auto-reassign-on-absence rule. Suat capacity (D-05) OPEN. | TA Dashboard PRD | high |
| ADV-MORNING-001-WAR-E030 | evidence | active | Correction window: Einspruchsfrist §347 AO = 1 month from Bescheid; post-export/pre-ELSTER re-file warning; late docs roll to next period (FR-GFR-11); 10yr §147 AO audit. Under StBerG the Steuerberater retains FULL professional liability for every signed output. | TA Dashboard PRD; KB; StBerG | high |
| ADV-MORNING-001-WAR-E031 | evidence | active | Live comparable DIFM metrics (May 2026): median handling time 11 min, prep 5 min; FL/rework rate 23.4% vs TARGET <10%; confirm-24h 77% vs 95%; SE ARPU €89–99/mo; ~20k cases/mo; automation >70% EOY26 target; cost-per-case baseline NOT established. Strategy has NO synthetic-replay concept or minimum replay volume. | TA Platform Vision; Strategy Rundown; DIFM Monitor KPI 2026-06 | high |
| ADV-MORNING-001-WAR-E032 | evidence | active | Opportunity machine = Stage 3, Q3 2026 scoping, "no build commitment yet", shadow-mode first. Four KPIs all "not yet tracked"; NO numeric threshold; TA stays gatekeeper. | TA Platform Vision; Agent Overview | high |
| ADV-MORNING-001-WAR-E033 | evidence | active | Named team: sponsor/COO Markus Berger de León; PM Christine Kiefer; GTM Claire Davidson; venture dev Marcel Koka; Eng Massimo; Ops Carolin Krüger; Dashboard Ozan Kara; TA/StB Suat Göydeniz (TaxVentures); qualification Percy; external DPO Carlo Piltz. No named Security/CISO owner; D-04 (contract owner) and D-05 (Suat capacity) open. | SE DIFM mission page; Req Spec | high |
| ADV-MORNING-001-WAR-E034 | evidence | **retracted (D013)** | (v2.0 row referencing the PoC harness model-provider config.) Retracted: the current PoC build is out of the decision matrix. | — | — |

### v2.0 / v2.1 decisions

| ID | Type | Status | Decision | Source | Confidence |
| --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-WAR-D008 | decision | active | v2.0 admits the real SE-DIFM company strategy (E023–E033) as legitimate DESIGN/DOMAIN evidence. This does not reopen D004 (the PoC code stays out); it recognizes the integration surface the MVP builds against. | User instruction (rerun with company background) | high |
| ADV-MORNING-001-WAR-D009 | decision | active | The gate stays `hold → narrow`. Supersedes D007. | Scenario results; corrected verdict | high |
| ADV-MORNING-001-WAR-D010 | decision | **superseded by D014** | (v2.0: "COO/PM must declare greenfield vs brownfield.") The dichotomy is rejected — the MVP is vendor-agnostic via APIs. | ADV-MORNING-001-WAR-D014 | high |
| ADV-MORNING-001-WAR-D011 | decision | active | The execution layer **governs and verifies the bookkeeping engine's output through its API** and assembles an evidence-linked review package; it does not re-implement bookkeeping computation. The engine is a vendor-agnostic integration. | F026 | high |
| ADV-MORNING-001-WAR-D012 | decision | **superseded by D014** | (v2.0: "MET-D009 is void; recast as export-format-only; MVP-D018 DATEV connection is false.") Superseded — vendor-neutrality is the design intent via adapters; DATEV is integrated through a sanctioned API/partner route when access is granted, with dates sourced from other systems until then. | ADV-MORNING-001-WAR-D014 | high |
| ADV-MORNING-001-WAR-D013 | decision | active | The current PoC build (`taxfix_harness` codebase and its model-provider configuration) is OUT of the decision matrix. The war game and decision record judge only the WoW docs + company strategy. Retracts F023, E034, S037; strips PoC-code framing from F030/F032. Extends D004. | User correction 2026-07-21 | high |
| ADV-MORNING-001-WAR-D014 | decision | active | The MVP is **vendor-agnostic**, built against clean API abstractions with a defined architecture. GFR/FinAPI/DATEV are reference integrations behind adapter interfaces — not a lock-in and not a scope contradiction. The greenfield-vs-brownfield framing is rejected. MET-D009 (vendor-neutral handoff) stands as the design intent, achievable via adapters. Supersedes F021 and F027 as findings. | User correction 2026-07-21 | high |

### v2.0 / v2.1 open questions

| ID | Type | Status | Statement | Owner |
| --- | --- | --- | --- | --- |
| ADV-MORNING-001-WAR-O010 | open question | **resolved by D014** | (Greenfield vs brownfield?) Resolved: vendor-agnostic via APIs. | Product |
| ADV-MORNING-001-WAR-O011 | open question | active | Who is the second Berufsträger / §69 StBerG Vertretung with absence-failover for Freigabe, and what is the single-signer client ceiling? Due before controlled live. | Markus / Suat / Carolin |
| ADV-MORNING-001-WAR-O012 | open question | active | What enforced EU-LLM provider allowlist, named Security owner, and signed provider AVV + LLM DPAs must exist before real data? Due before real client data (O019). | Legal & Compliance / DPO / (unnamed) security owner |
| ADV-MORNING-001-WAR-O013 | open question | active | How are structured e-invoices (EN-16931) parsed-or-stopped, and how is document/OCR-derived text quarantined from the instruction channel? | Massimo / Julian Hölz / Percy |

## Re-adjudication of the 32 prior scenarios (v2.0 evidence, v2.1 correction)

Honest-simulation rule: a documented company contract lifts `failed → unknown` (never `survived`); evidence that contradicts the MVP is a new `failed`; a Product decision can resolve a finding. Rows that v2.0 marked `failed` on greenfield/vendor/PoC grounds are corrected in v2.1 per D013/D014.

| ID | v1.0 | v2.1 | Sev | Why (evidence / decision) |
| --- | --- | --- | --- | --- |
| S001 job/cohort not dominant pain | unknown | unknown | P1 | No SE 5-day study exists (E031). |
| S002 SOTA removes workbench | survived | survived | none | Four-eyes Freigabe is a legal entailment (E029); StBerG liability (E030). |
| S003 missing invoice still "ready" | failed | unknown | P1 | E026 supplies the rubric (Ausgangsrechnung NOGO etc.); enforcement unproven. |
| S004 malicious document injection | unknown | unknown | P1 | E027 OCR'd fields reach the agent; quarantine is a design requirement (F032). |
| S005 reviewer absent/rubber-stamps | unknown | unknown | P1 | Reviewer rules exist (E029) but no absence failover; O025/O011. Addressable. |
| S006 cross-tenant/mandate access | unknown | unknown | P1 | Per-mandate isolation is a design/adapter requirement; no observed breach. |
| S007 resume repeats action | unknown | unknown | P2 | Idempotent ID mapping FR-GFR-02/04 closes the design gap. |
| S008 handoff success unknown, retries | failed | unknown | P1 | E025 gives an ELSTER-protocol receipt + reconciliation path; unproven. |
| S009 hard cases excluded post-hoc | failed | unknown | P1 | E026 fixes exclusions a priori; denominator honesty unproven. |
| S010 stale source, day "clear" | failed | unknown | P1 | Freshness of any polled/cached adapter is a design requirement (F029: poll-age + fail-closed). Not a vendor kill shot (D014). |
| S011 partners hear full Kano as current | failed | failed | P1 | Opportunity machine is Stage-3 scoping only (E032); selling it as current is a claim breach. |
| S012 Radar irrelevant service | unknown | unknown | P2 | E032 catalog exists; no numeric threshold; shadow-mode only. |
| S013 malicious doc + reviewer pressure | failed | unknown | P1 | Injection quarantine (F032) + reviewer failover (O011) are design requirements; addressable. |
| S014 stale state + strong demo widens claim | unknown | unknown | P1 | Freshness design (F029) + honest-claim discipline; addressable. |
| S015 workbench duplicate state | unknown | unknown | P1 | Freshness/reconciliation is a design requirement (F029), addressable in a vendor-agnostic architecture. **No longer a kill shot** (D014). |
| S016 current build as MVP foundation | survived | survived | none | Reaffirmed by D013 — the PoC build is out of scope. |
| S017 model invents invoice/"all clear" | unknown | unknown | P1 | E027 provenance contract closes the design gap; hallucination-on-top unproven. |
| S018 sources disagree / change after prep | unknown | unknown | P1 | E030 post-export change warning + rollover close the design gap; staleness residual (F029). |
| S019 real data to unapproved provider | failed | unknown | P1 | E028 supplies the EU-LLM/DPA policy. Real-data item under O019/O012. (The PoC-config version F023 is retracted, D013.) |
| S020 data/secrets after deletion/in prompts | failed | unknown | P1 | AI/log retention "to be defined" (E028); real-data governance item under O019. |
| S021 reject/correct/cancel/ownership change | unknown | unknown | P2 | Idempotent mapping + audit trail close the design gap; cross-role timing unproven. |
| S022 outage after partial handoff | failed | unknown | P1 | Recovery across an adapter boundary is a design requirement; not a vendor kill shot (D014). |
| S023 average hides one critical miss | survived | unknown | P1 | Categorical stops documented (E026) but >85% is an average and live FL is 23.4%; no proof guardrails catch the miss. |
| S024 delayed harm after handoff | failed | unknown | P1 | E030 Einspruchsfrist detection closes; remediation under-specified. |
| S025 whole-day product slower/costlier | unknown | unknown | P1 | Cost-per-case baseline not established (E031); measure it (F033). |
| S026 stronger model expands scope | unknown | unknown | P2 | Tight Buchungsprofil boundary (E026) bounds it; e-invoice pressure. |
| S027 no named sponsor/cohort | failed | unknown | P2 | E033 names sponsor/PM/StB; cohort access unproven, D-05 open. |
| S028 partner procurement/DATEV blocks access | failed | failed | P1 | DATEV AGB 2.6 + Unterberaternummer (A-1) are real external constraints. Controlled-live integration-sequencing prerequisite (O013/F028), not a synthetic-replay blocker. |
| S029 price before value/cost proof | survived | failed | P1 | Price set (ARPU €89–99) while cost-per-case baseline NOT established (E031); GTM/metrics item (F033). |
| S030 planned capability sold as current | failed | failed | P1 | PDF/opportunity-machine sold as current contradicts documented phase status (E032). Claim discipline. |
| S031 review volume > capacity | unknown | failed | P1 | Single Berufsträger, live confirm-24h 77%, monthly deadlines (E029/E031). Controlled-live/scale (O011/O025). |
| S032 malicious doc + provider + absent reviewer | failed | unknown | P1 | Minus the retracted egress leg (D013): injection quarantine (F032) + reviewer failover (O011) are design requirements. |

**Totals (v2.1):** 2 survived, 22 unknown, 8 failed. The 8 `failed` are claim-discipline (S011, S030), metrics/cost (S029), reviewer capacity at scale (S031), and a controlled-live integration prerequisite (S028) — all mapping to existing open questions, none a vendor or PoC kill shot.

## New scenario deck (v2.0), corrected in v2.1

Nine attack fronts produced 88 new scenarios. The strongest distinct results are captured as WAR-S033–S042. v2.1 corrects those that rested on the retracted PoC-build or greenfield/vendor framing.

| ID | Inject and target | Result (v2.1) | Sev | Owner / disposition |
| --- | --- | --- | --- | --- |
| S033 | Execution layer must add value the engine does not. | unknown | P2 | Christine — F026/D011: govern + verify the engine's output, do not re-implement it. Design principle, not a kill shot. |
| S034 | "Greenfield vs Requirements Spec — two products." | **resolved** | — | D014: vendor-agnostic via APIs; false dichotomy. Retired. |
| S035 | Complete and confirm a filing. | failed | P1 | Suat / Marcel — F024: A-1 (Untervollmacht + Unterberaternummer) is a controlled-live filing-authority prerequisite; the synthetic-replay MVP stops at prepare/review, so it does not block the build. |
| S036 | Single Berufsträger throughput at scale. | failed | P1 | Markus / Suat / Carolin — F022: reviewer failover (O011/O025), controlled-live/scale prerequisite. |
| S037 | Client data to a non-EU model (PoC config). | **retracted** | — | D013: the PoC build is out of scope. EU-LLM/DPA requirement lives under O019/O012. |
| S038 | An Art.28 processor has an incident. | failed | P1 | Markus (to appoint) — F025: named Security owner + Art.33 runbook; real-data prerequisite (O019/O012). |
| S039 | Desk shows "ready" on stale data. | unknown | P2 | Massimo / Ozan — F029: poll-age stamps + fail-closed. Design requirement. |
| S040 | An out-of-scope profile enters (KU §19, e-commerce). | unknown | P2 | Christine / Suat — F030: fail-closed scope gate from the Buchungsprofil exclusions. Design requirement. |
| S041 | A case blocks on a missing Ausgangsrechnung. | failed | P1 | Christine / Carolin — F031: recovery needs the client contact D019 removed; owned human-ops queue or a minimal non-AI nudge. |
| S042 | A ZUGFeRD/XRechnung e-invoice arrives; OCR text carries an instruction. | failed | P1 | Massimo / Julian / Percy — F032: EN-16931 parse-or-stop + quarantine document-derived text. |

## Findings and remediation (v2.1)

v1.0 findings F001–F020 stand (F002, F010 resolved). v2.0 raised F021–F033; v2.1 retracts/supersedes the greenfield/vendor/PoC ones and reclassifies the rest. **No P0 finding remains.**

| ID | Sev | Status | Finding | Required fix / disposition | Owner |
| --- | --- | --- | --- | --- | --- |
| F021 | — | **superseded (D014)** | "Greenfield vs Requirements Spec — no authoritative-lens ruling." | Resolved: the MVP is vendor-agnostic via APIs; no dichotomy. | Product |
| F022 | P1 | active | Single external Berufsträger has no failover; all filings funnel through one StB with full liability; NFR-09 50–100 ceiling; live review already strained. | Second Berufsträger / §69 StBerG Vertretung with absence-failover; single-signer client ceiling as a hard acceptance block. **Controlled-live/scale prerequisite (O011/O025).** | Markus / Suat / Carolin |
| F023 | — | **retracted (D013)** | "Illegal LLM egress" (based on the PoC model-provider config, out of scope). | The EU-LLM-default + Art.28-DPA requirement is a normal pre-real-data item under O019/O012. | Legal / DPO |
| F024 | P1 | active | No filing authority (A-1: Untervollmacht §80 AO + LAPIS Unterberaternummer unresolved; DATEV AGB 2.6 gates access) and no confirmed-filing reconciliation. | Resolve A-1 and define a human-operated ELSTER-confirmation reconciliation. **Controlled-live prerequisite (O013/O023)**; the synthetic-replay MVP stops at prepare/review. | Suat / Marcel |
| F025 | P1 | active | No named Security/CISO owner + no breach runbook; GDPR Art.33 72h clock unowned; provider AVV owner (D-04) unnamed. | Appoint a security owner; block real data on signed provider AVV + LLM DPAs; publish an Art.33 runbook. **Real-data prerequisite (O019/O012).** | Markus (to appoint) / DPO |
| F026 | P2 | active | The execution layer must govern and verify the bookkeeping engine's output through its API, not re-implement computation. | Design principle (D011): assemble, verify, source-link, route; keep the engine a vendor-agnostic integration. | Christine / Massimo |
| F027 | — | **superseded (D014)** | "Vendor-neutral handoff void." | Resolved: vendor-neutrality is the design intent, achievable via adapters. MET-D009 stands. | Product |
| F028 | P2 | active | DATEV access is partner-gated (AGB 2.6, no OAuth client_credentials, 2FA). | Integrate DATEV via the sanctioned API/partner route (4–12 wk onboarding) as a dated critical-path item; until then source dates from other systems. **Integration sequencing, not a blocker.** | Suat / Massimo |
| F029 | P2 | active | Any polled/cached adapter can serve stale state → risk of "ready" on stale data. | Stamp every source-derived field with poll-age; define max-staleness; fail closed (suppress filing-ready) when exceeded. Design requirement. | Massimo / Ozan |
| F030 | P2 | active | No fail-closed scope gate to enforce the Buchungsprofil hard exclusions. | Add a fail-closed scope gate upstream of preparation; build the replay corpus to the one confirmed profile; excluded profiles appear only as expected-REFUSE fixtures. Design requirement. | Christine / Suat |
| F031 | P1 | active | The dominant stop-state (missing Ausgangsrechnung = NOGO) needs the client contact MVP-D019 removed; blocked cases have no in-MVP unblock path. | Minimal non-AI client-nudge channel OR an owned human-ops queue with an SLA; document un-unblockable case types. | Christine / Carolin |
| F032 | P1 | active | Job evidence is PDF/finAPI/e-invoice; MET-D010's csv-only stance is narrower than the job; EN-16931 unhandled; OCR-derived text is an injection surface. | Base fixtures on real finAPI/GFR schemas; EN-16931 parse-or-stop; quarantine document-derived strings from the instruction channel; add injection + e-invoice tests. (Docs-level; no PoC dependency.) | Massimo / Julian / Percy |
| F033 | P1 | active | Metrics are orphaned: G002 KPIs map to no live North Star; no cost-per-case baseline; >85% match has no fixed denominator; live FL 23.4% not calibrated into replay; no post-submission error-latency KPI. | Bind ≥1 gate KPI to a tracked live metric; pin the match denominator to all in-period txns; establish cost-per-case and gate CP1 on margin; add a downstream error-detection-latency KPI; keep autonomy at L2-Prepare. | Ozan / Christine / Claire |

## Kill-shot verdicts (v2.1)

| Claimed kill shot | Verdict | Basis |
| --- | --- | --- |
| Greenfield vs Requirements Spec — "two products" (P0) | **OVERRULED by Product (D014)** | The MVP is vendor-agnostic via APIs; naming GFR/FinAPI/DATEV in strategy is not lock-in. No dichotomy. → F021 superseded. |
| Vendor-neutral handoff void (P0) | **OVERRULED by Product (D014)** | Vendor-neutrality is the design intent, achievable via adapters. → F027 superseded. |
| Illegal non-EU LLM egress (P0) | **RETRACTED (D013)** | Based on the current PoC model-provider config, which is out of the decision matrix. → F023 retracted; requirement moves to O019/O012. |
| Execution layer has no independent substance (P1) | **DOWNGRADED to a design principle** | Govern + verify the engine's output via its API; do not re-implement (D011). → F026 (P2). |
| Reference-copy stale → false-ready (P0) | **DOWNGRADED to a design requirement** | Freshness (poll-age + fail-closed) is standard for any adapter. → F029 (P2). |
| Single external Berufsträger SPOF (P0) | **REAL, but a controlled-live prerequisite** | Reviewer failover before controlled live/scale, not a synthetic-replay-build blocker. → F022 (P1, O011/O025). |
| No filing authority (A-1 unresolved) (P1) | **REAL, but a controlled-live prerequisite** | The MVP stops at prepare/review; filing authority is needed before controlled live. → F024 (P1, O013/O023). |
| No incident/security owner (P0) | **REAL, but a real-data prerequisite** | Needed before real client data, not synthetic replay. → F025 (P1, O019/O012). |
| Double-bind (MET-D009 ∧ MET-D010) | **REFUTED (2 votes)** | The two constraints are orthogonal; the job is buildable. |

**Net: no MVP kill shot stands.** Two provisional kill shots were overruled by Product, one retracted as out of scope, three downgraded to design requirements, and three reclassified as controlled-live / real-data prerequisites already anticipated by the MVP's open-question structure.

## Cross-lens contradictions (v2.1)

| Contradiction | Authoritative decision (v2.1) | Owner |
| --- | --- | --- |
| Greenfield (MVP-D017) vs in-build Requirements Spec | **Resolved (D014):** vendor-agnostic via APIs; the Requirements Spec defines the integration surface, not a competing product. | Markus / Christine |
| MET-D009 vendor-neutral vs a named engine | **Resolved (D014):** vendor-neutral is the intent; the engine is one adapter; own concentration risk (AVV/SLA/exit) as a design item. | Massimo / Julian |
| MVP-D018 "connects to DATEV" vs partner-gated access | DATEV is integrated via the sanctioned API/partner route when granted; until then dates come from other systems. Integration-sequencing item (F028). | Suat / Massimo |
| MET-D010 csv-only vs PDF/finAPI/e-invoice reality | Consume real evidence types (as untrusted input); add EN-16931 parse-or-stop before controlled live (F032). | Massimo / Christine / Julian |
| MVP-D008/MET-G002 synthetic replay vs live business metrics | Bind ≥1 gate KPI to a live metric; replay proves honesty, not business value (F033). | Ozan / Christine |
| MVP-D019 no client contact vs recovery paths that need it | Minimal non-AI nudge or an owned human-ops handoff; document un-unblockable case types (F031). | Christine / Claire |
| EU-LLM policy vs provider choice (before real data) | Enforce an EU-hosted/DPF-covered, DPA-signed provider allowlist; appoint a security owner (O012). Real-data item, not a PoC judgment. | Legal / DPO |
| Buchungsprofil exclusions vs scope enforcement | Fail-closed scope gate; excluded profiles only as expected-REFUSE fixtures (F030). | Suat / Christine |

## Decision council (v2.1)

- Named people (E033): sponsor Markus Berger de León; PM Christine Kiefer; GTM Claire Davidson; Eng Massimo; Ops Carolin Krüger; Dashboard Ozan Kara; StB Suat Göydeniz (TaxVentures); DPO Carlo Piltz. **Security/CISO owner unnamed (O012, real-data prerequisite).**
- Product decisions recorded this round: D013 (PoC build out of scope), D014 (vendor-agnostic via APIs). These overrule the two provisional kill shots.
- Unresolved P0 findings: **none.**
- Controlled-live / real-data prerequisites (P1): F022 (reviewer failover), F024 (filing authority), F025 (security owner) — due at their existing gates, not before the synthetic-replay build.
- Design requirements before build→replay (P1/P2): F026, F029, F030, F031, F032, F033.
- Recommended gate decision: **hold**.
- Recommended consequence: **narrow** — close the design requirements and the existing G001 open questions; build the vendor-agnostic MVP as specified. Not KILL, and no re-scoping of the product shape.

## Final handoff (v2.1)

- Scenario coverage: 32/32 prior re-adjudicated + 88 new across 9 fronts (GTM-and-trust front stalled; covered by vision-and-scale, cross-lens, and the GTM lens read directly).
- What survived: S002 (four-eyes is a legal entailment), S016 (PoC build out of scope).
- What failed (docs-level / controlled-live): S011, S028, S029, S030, S031.
- What remains unknown (design gap documented, no observed proof): the rest.
- Kill shots: none stand — two overruled by Product (D014), one retracted (D013), three downgraded to design requirements, three reclassified as controlled-live/real-data prerequisites.
- Gate recommendation: `hold → narrow` (same as v1.0), for the vendor-agnostic MVP as specified.
- Lenses to reopen: MVP (bind decisions to real integration constraints), Metrics (G002 KPIs vs live metrics), GTM (claim ladder vs Stage-3 reality), Vision (integration dependencies). SOTA stays analysis input.
- Output links: [war game](war_game.md) | [transcript](war_game_agent_transcript.md) | [thought process](war_game_thought_process.md) | [decision record](agentic_mvp_decision.md).
- Next owner/action: Product closes the design requirements (F026, F029–F033) and the G001 open questions; the controlled-live prerequisites (F022, F024, F025) close at their gates. Fold into `agentic_mvp_decision.md` and the canonical JTBD dossier.
