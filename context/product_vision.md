# Agentic Product Roadmap: TA Platform — Advisor Desk

- Artifact ID: ADV-MORNING-001-VIS-A001
- Artifact type: agentic-product-roadmap
- Version: 0.14
- Artifact completeness: complete
- Job ID: ADV-MORNING-001
- Canonical lifecycle stage: discovery
- Capability mode: mixed
- Requested transition: discovery to evidence-gated internal operation for the SE-DIFM cohort
- Gate decision: hold
- Decision consequence: narrow
- Owner: Product
- Updated date: 2026-07-17
- Canonical brief: Open — no canonical JTBD dossier was found for this job
- Input artifacts: [platform context](../tax-advisor-platform-context.md); [SOTA benchmark](SOTA/sota_benchmark.md); [SOTA synthesis](SOTA/sota_advisor_desk.md); [strategy alignment handover](product_vision_alignment_handover.md); [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md); [historical work inventory](../../../../jtbd.md)
- Transcript link: [product_vision_agent_transcript.md](product_vision_agent_transcript.md)

This v0.14 increment makes the product north star and the moving AI frontier explicit. It keeps the v0.13 TA Platform structure, stable IDs, operating gates, and current-capability boundaries.

## Product north star

**The TA Platform is the Codex for Tax Advisors. Advisor Desk is its workbench.**

The Advisor gives one client mission. The platform plans it, works it through approved capabilities, shows the Trace, stops at human gates, and resumes after correction. The working loop is:

`Mission → Plan → Work → Trace → Review → Resume`

This means one Desk, one mission, one source-linked record, and one exception stream. The Advisor can inspect, interrupt, correct, return, retry, or take over. “Codex” describes the working relationship. It does not mean copying a terminal or adding a chatbot to today’s Desk.

## Evidence and decision register

Stable IDs are retained. New v0.13 decisions begin at D018.

| ID | Type | Status | Claim or decision | Source/link | Date | Owner | Confidence |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-VIS-E001 | fact | active | The Advisor job needs a full-workday command centre for German tax work. | [SOTA decisions](SOTA/sota_benchmark.md#conversation-decisions) | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-E002 | fact | active | The Desk must connect priority, decision packets, bounded action, waits, and evidence-backed client needs. | [SOTA synthesis](SOTA/sota_advisor_desk.md) | 2026-07-16 | Product | high for the chosen bar |
| ADV-MORNING-001-VIS-E003 | fact | active | Entry parity means source fidelity, ownership, rights, handovers, checks, and safe progress. It does not mean copying incumbent screens. | [SOTA decisions](SOTA/sota_benchmark.md#conversation-decisions) | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-E004 | fact | active | Direct Advisor observation, integration proof, privacy completion, buyer demand, adoption cost, and ROI proof remain missing. | [SOTA validation](SOTA/sota_benchmark.md#validation-and-contradictions) | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-E005 | fact | active | Codex provides the interaction model: scoped work, visible progress, interruption, correction, retry, durable context, and inspectable change. It is not a terminal metaphor. | [manifesto](../../agentic-tax-practice-manifesto.md#what-we-take-from-codex) | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-E006 | fact | active | The first deep job is preparation of one bookkeeping period for Advisor review, with evidence-linked handover and visible blockers. | [manifesto](../../agentic-tax-practice-manifesto.md#the-first-state) | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-E007 | fact | active | The product direction uses durable client, engagement, workstream, task, run, result, evidence, and review records with explicit capability permissions. | [platform context](../tax-advisor-platform-context.md) | 2026-07-16 | Product / Engineering | high for direction |
| ADV-MORNING-001-VIS-E008 | fact | active | Professional judgment and consequential external action remain human-controlled. Client outreach, selling, filing, payment, and other irreversible actions are not automatic. | [platform context](../tax-advisor-platform-context.md#forbidden-automatic-actions) | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-E009 | fact | active | The harness currently supports only the approved deterministic csv_reader capability. Unsupported formats stop visibly. | [platform context](../tax-advisor-platform-context.md#capability-and-unsupported-input-rule) | 2026-07-16 | Product / Engineering | high |
| ADV-MORNING-001-VIS-E010 | fact | active | The repository work inventory is historical implementation coverage, not the canonical JTBD portfolio. | [historical inventory](../../../../jtbd.md) | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-E011 | fact | active | The historical inventory spans compliance, evidence, filing, notices, client work, reporting, practice operations, revenue, and supervision. | [historical inventory](../../../../jtbd.md#jtbd-coverage) | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-E012 | fact | limited | Frontier capability is improving quickly but its tax-domain reliability is unproven here. | Prior v0.12 research register | 2026-07-16 | Product / Research | medium |
| ADV-MORNING-001-VIS-E013 | fact | limited | Vendor document-understanding claims do not prove support for Taxfix evidence. | Prior v0.12 research register | 2026-07-16 | Product / Research | medium |
| ADV-MORNING-001-VIS-E014 | fact | limited | Durable background runs and explicit pauses are available platform patterns, not Taxfix outcome proof. | Prior v0.12 research register | 2026-07-16 | Product / Research | medium |
| ADV-MORNING-001-VIS-E015 | fact | limited | Computer-use tooling has known reliability and safety limits. It creates no product commitment. | Prior v0.12 research register | 2026-07-16 | Product / Research | high |
| ADV-MORNING-001-VIS-E016 | fact | limited | Agent task-horizon benchmarks are not tax-work transfer evidence. | Prior v0.12 research register | 2026-07-16 | Product / Research | medium |
| ADV-MORNING-001-VIS-E017 | fact | limited | Specialist-agent patterns have coordination and cost risks. | Prior v0.12 research register | 2026-07-16 | Product / Research | medium |
| ADV-MORNING-001-VIS-E018 | fact | limited | Falling model cost is historical context, not a pricing or delivery promise. | Prior v0.12 research register | 2026-07-16 | Product / Research | medium |
| ADV-MORNING-001-VIS-E019 | fact | active | The relevant market pattern is governed, human-in-the-loop preparation rather than autonomous filing. | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md) | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-E020 | fact | active | The durable product advantage is governed workflow, context, evidence, and integration, not generic model access alone. | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md) | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-E021 | fact | active | Sanctioned DATEV access has consent, partner, and authentication constraints. | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md) | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-E022 | fact | active | DATEV and ELSTER remain the statutory system of record. Taxfix owns operational context, orchestration, source links, and history. | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md) | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-E023 | fact | active | External engine and bridge vendors create dependency-concentration risk. | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md) | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-E024 | fact | active | E-invoice and retention rules affect future supported-format decisions. They do not expand current harness capability. | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md) | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-E025 | fact | limited | Computer-use benchmark results do not justify a DATEV automation path in this roadmap. | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md) | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-E026 | fact | active | Internal strategy frames the product as a TA Platform with three stages: operational tool, working machine, and opportunity machine. | [strategy alignment handover](product_vision_alignment_handover.md#section-a--internal-strategy-snapshot-embedded-captured-2026-07-17) | 2026-07-17 | Product | high for the captured strategy |
| ADV-MORNING-001-VIS-E027 | fact | active | The first intended cohort is low-document-volume, VAT-liable SE freelancers and digital consultants in DIFM. | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md#b1-internal-architecture-snapshot-from-notiondrive--provenance-only-not-web-verifiable) | 2026-07-17 | Product | high for intended scope |
| ADV-MORNING-001-VIS-E028 | fact | active | The initial end-to-end handoff is manual: GFR CSV to DATEV import and manual Bescheid upload back to the workspace. | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md#b1-internal-architecture-snapshot-from-notiondrive--provenance-only-not-web-verifiable) | 2026-07-17 | Product | high for intended process |
| ADV-MORNING-001-VIS-E029 | fact | active | Monitor is reported to have internal efficiency agents. That is substrate context, not proof that this harness already provides platform capability. | [strategy alignment handover](product_vision_alignment_handover.md#a4-the-ta-platform-model--levers-and-stages) | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-E030 | fact | active | A planned calendar launch is not proof that an SE-DIFM workspace or enough eligible cases are live. The start gate must verify both. | [strategy alignment handover](product_vision_alignment_handover.md#a5-concrete-2026-delivery-plan) | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-E031 | fact | active | The named agent families are a dated target capability portfolio, not a present product-support claim. | [strategy alignment handover](product_vision_alignment_handover.md#a6-the-named-agent-families) | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D001 | decision | active | The product direction is AI-first. | User direction | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D002 | decision | superseded | The former product-anchor wording is superseded by D018 and D026. | D018, D026 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D003 | decision | active | This vision may start from the SOTA benchmark without a separate Agentic MVP artifact. | User direction | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D004 | decision | active | The Advisor uses an agentic workbench, not a copilot or autonomous practice manager. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D005 | decision | superseded | The earlier 9–12 month target was narrowed by D017. | D017 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D006 | decision | active | Roadmap progress is expressed in monthly user and product steps. Calendar pace never waives evidence gates. | User direction | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D007 | decision | active | Control transfers progressively, visibly, correctably, and reversibly. | User direction | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D008 | decision | active | The start combines a trusted Desk with one real agentic loop. | User direction | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D009 | decision | active | The first differentiator is intervention to handled outcome. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D010 | decision | active | Taxfix may prepare a proposed goal, short plan, and evidence packet; the Advisor starts or edits the actionful run. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D011 | decision | active | The first release proves one deep executable job. Unsupported work stays explain-or-prepare only. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D012 | decision | active | The roadmap defines the general Advisor Desk; later sessions deepen client and agent objects. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D013 | decision | active | Organize work, process approved work, and decide consequential matters remain separate responsibilities. | User direction | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D014 | decision | active | The historical work inventory is not the transition journey or canonical JTBD portfolio. | User correction | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D015 | decision | active | The roadmap accounts for a moving AI frontier without assuming current limits remain fixed. | User direction | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D016 | decision | active | Better models may compress delivery after proof but never bypass evidence, product-support, privacy, or human-authority gates. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D017 | decision | active | Month 9 is the relative operating target; months 10–12 broaden proven scope and harden operations. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-D018 | decision | active | The product is the TA Platform. Advisor Desk is its user-facing workbench. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D019 | decision | active | The initial operating horizon is internal Taxfix Advisors serving SE-DIFM, starting with low-document-volume VAT-liable freelancers and digital consultants. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D020 | decision | active | Build through operational tool, working machine, and opportunity machine. Start opportunity signals in parallel, shadow-first, and Tax Advisor-gated. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D021 | decision | active | Quality and trust are hard gates. Falling handling time is operating proof. Net Revenue per active Tax Advisor is the business North Star; ARPU is a diagnostic. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D022 | decision | active | Month 1 begins only after verified SE-DIFM workspace availability and enough eligible case volume. No calendar date is claimed as live here. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D023 | decision | active | Start with manual GFR CSV to DATEV import and manual Bescheid upload. Use a sanctioned API or connector only as later, separately approved automation. No computer-use path is committed. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D024 | decision | active | Trace is the present evidence-and-review promise: source links, what changed, reviewer decision, and visible blockers. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D025 | decision | active | The named agent families are future target capabilities. Keep harness-now, Monitor substrate, and future TA Platform clearly separate. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D026 | decision | active | “Codex for Tax Advisors” is the explicit north-star experience for the TA Platform. Advisor Desk is the workbench through which the Advisor gives a mission, supervises work, reviews Trace, and resumes or takes over. | User direction | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-D027 | decision | active | The moving AI frontier is a visible monthly roadmap lane. Proven frontier gains may pull work forward, but they never expand product support or human authority automatically. | User direction | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-H001 | hypothesis | superseded | Superseded by D004. | D004 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-H002 | hypothesis | superseded | Superseded by D017. | D017 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-H003 | hypothesis | active | One deep, evaluated job creates reusable context, checks, permissions, and recovery patterns faster than making every screen intelligent. | E006–E008, D011 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H004 | hypothesis | active | Month 9 means the workbench is default for a named eligible cohort and proven jobs, not every tax job. | D017, D019 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H005 | hypothesis | active | Show, explain, offer delegation, run visibly, then make proven work default is the least disruptive control-transfer pattern. | D007 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H006 | hypothesis | active | The Desk and durable work records should evolve in place rather than split into a separate AI mode. | D004, D018 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H007 | hypothesis | superseded | Superseded by D009. | D009 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-H008 | hypothesis | superseded | Superseded by D010. | D010 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-H009 | hypothesis | reclassified | The prior five-step sequence is only a user-transition lens, not a JTBD inventory. | D014 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-H010 | hypothesis | active | Start with broad organization, one deep preparation job, and named human decisions. | D011–D013, D019 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-H011 | hypothesis | superseded | Superseded by H012 and D014. | H012, D014 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-H012 | hypothesis | active | The historical inventory can be grouped into seven work domains, but that grouping needs canonical dossier confirmation. | E010–E011, D014 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H013 | hypothesis | active | Generic evidence handling, long-running agents, and orchestration will improve, but timing and tax transfer remain uncertain. | E012–E018 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H014 | hypothesis | active | Taxfix should own context, evidence, authority, integration, evaluation, correction history, and recovery while generic intelligence remains replaceable. | E020, D016 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H015 | hypothesis | active | Technology may compress delivery, not trust-building, user adoption, domain proof, or authority. | D016 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H016 | hypothesis | active | The Advisor should experience one Desk, one work record, and one exception stream even if later capabilities specialize behind it. | D018, D025 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H017 | hypothesis | superseded | The former computer-use bridge proposal is superseded by D023: no path is committed. | D023 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-H018 | hypothesis | active | Every model, tool, format, or provider change needs job-specific tests before rollout. | D016 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-H019 | hypothesis | active | The durable product boundary is governed workflow and evidence, not generic model access. | E020, H014 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H020 | hypothesis | superseded | The former month-one integration critical-path claim is superseded by D023. Sanctioned integration remains a later scope gate. | D023 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-H021 | hypothesis | superseded | The former API-first and computer-use fallback proposal is superseded by D023. | D023 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-H022 | hypothesis | active | Taxfix can own context and evidence history while DATEV and ELSTER remain the statutory system of record. | E022 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-H023 | hypothesis | active | The workbench wins by being faster, cheaper, and more governed for eligible work, not by claiming more autonomy. | E019, D021 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H024 | hypothesis | active | External vendor dependencies need an exit and redundancy plan before their automation becomes material. | E023 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-H025 | hypothesis | active | A later sanctioned connector can increase working-machine coverage only after it passes its own legal, technical, quality, and recovery gate. | D023, E021–E023 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-H026 | hypothesis | active | Better multimodal evidence understanding can expand supported document coverage after format-specific tax-work evaluation. | E012–E013, D016, D027 | 2026-07-17 | Product / Domain | medium |
| ADV-MORNING-001-VIS-H027 | hypothesis | active | Longer-running background agents can own waits, retries, and resume points while keeping every state change visible. | E014, D007, D027 | 2026-07-17 | Product / Engineering | medium |
| ADV-MORNING-001-VIS-H028 | hypothesis | active | Better tool use can expand approved working-machine coverage, but it does not create permission to operate external systems. | E015, E021, D023, D027 | 2026-07-17 | Product / Engineering | high |
| ADV-MORNING-001-VIS-H029 | hypothesis | active | Specialist agents can prepare parts of one mission in parallel behind one plan, one Trace, and one Advisor relationship. | E017, D025–D027 | 2026-07-17 | Product / Engineering | medium |
| ADV-MORNING-001-VIS-H030 | hypothesis | active | Better verification and model routing can reduce weak review packages, cost, and avoidable human rework. | E016–E018, D021, D027 | 2026-07-17 | Product / Domain | medium |
| ADV-MORNING-001-VIS-H031 | hypothesis | active | Lower cost and latency, plus correction-based adaptation, can make whole-book monitoring economically viable for the eligible cohort. | E018, D017, D021, D027 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-O001 | open question | superseded | Resolved by D004. | D004 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-O002 | open question | superseded | Resolved by D017; its clock starts only at D022's entry gate. | D017, D022 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O003 | open question | active | Which reversible internal effects, if any, may later earn bounded autonomy? | D007, D016 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O004 | open question | active | What direct Advisor observation will validate or correct the operating model and information order? | E004 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O005 | open question | active | Where is the canonical JTBD dossier that owns lifecycle and gate decisions for this job? | E010 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-O006 | open question | narrowed | D019 names the initial cohort. Which named Advisors and additional proven jobs reach the Month 9 default remains open. | D019, D017 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O007 | open question | active | Does the progressive control-transfer pattern in H005 work for real internal Advisors? | H005, O004 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O008 | open question | superseded | The former five-stage framing is superseded by D020's platform stages. | D020 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O009 | open question | superseded | Resolved by D009. | D009 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-O010 | open question | superseded | Resolved by D010. | D010 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-O011 | open question | superseded | Resolved by D011. | D011 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-O012 | open question | active | Does the transition language match how internal Advisors describe their work? | O004 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-O013 | open question | superseded | The start split is resolved by D019, D020, and D023. | D019, D020, D023 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O014 | open question | superseded | Resolved by D014. | D014 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-O015 | open question | active | Does the seven-domain historical-inventory grouping support the future canonical dossier? | H012 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-VIS-O016 | open question | superseded | Resolved by D016. | D016 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-O017 | open question | active | Should Taxfix formally adopt the replaceable-intelligence boundary in H014? | H014, H019 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O018 | open question | superseded | Resolved by D017. | D017 | 2026-07-16 | Product | high |
| ADV-MORNING-001-VIS-O019 | open question | active | Which sanctioned DATEV integration route is viable later, on what terms, and for which automation scope? | E021, H025 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O020 | open question | active | What is the exit plan if a material external engine or bridge changes terms or fails? | E023, H024 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O021 | open question | active | What measurable advantage must the working machine show against incumbent automation for the initial cohort? | H023, D021 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O022 | open question | active | Who verifies workspace availability, eligible case volume, and cohort fit to open Month 1? | D022, E030 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O023 | open question | active | What precision, review acceptance, and client-benefit thresholds allow an opportunity signal to leave shadow mode? | D020, D021 | 2026-07-17 | Product | high |
| ADV-MORNING-001-VIS-O024 | open question | active | Which future agent family earns the next platform investment after the bookkeeping job proves value? | D025, E031 | 2026-07-17 | Product | medium |

## Conversation decisions

- Confirmed current user need and quality bar: Internal Advisors need a trusted Desk that moves a real SE-DIFM bookkeeping case forward, shows evidence and blockers, and keeps human decision authority.
- Confirmed end state and horizon: TA Platform becomes the default workbench for a named eligible cohort by relative Month 9. The clock begins only when the entry gate is verified.
- Confirmed north star: The TA Platform is the Codex for Tax Advisors. Advisor Desk expresses the Mission → Plan → Work → Trace → Review → Resume relationship without copying a terminal.
- Confirmed capability changes by process area: Operational tool first; working machine next; opportunity signals begin in parallel but stay shadow-first and Tax Advisor-gated.
- Confirmed technology stance: Frontier progress is reviewed every month. Proven gains can pull roadmap work forward, but no model gain grants new authority or support by itself.
- Confirmed principles and human authority: DATEV and ELSTER are the statutory record. Taxfix owns context, orchestration, evidence, and history. Human gates remain for judgment and consequential action.
- Confirmed now, next, later logic: Manual handoffs prove the job now. A sanctioned connector is later. Marketplace and white-label are post-transformation only.
- Confirmed stop or rollback conditions: Quality or trust failure stops promotion. Missing entry evidence holds Month 1. Unsupported capability stays visibly blocked.
- Matters explicitly delegated to the agent: Make the Codex north star and moving-frontier lane explicit while retaining the stable register and v0.13 operating structure.

## Research coverage

- Research mechanisms used: supplied sources
- Research limitations or blockers: No new external research was run for v0.13. The strategy snapshot is dated. Direct Advisor observation, verified workspace and case volume, integration feasibility, and commercial proof are still missing.

| Source ID | Publisher | URL | Access date | Supported claim | Evidence quality | Claim status |
| --- | --- | --- | --- | --- | --- | --- |
| E001–E004 | Taxfix Product | [SOTA benchmark](SOTA/sota_benchmark.md) | 2026-07-16 | User job, quality bar, and missing proof | internal benchmark | accepted with limits |
| E005–E011 | Taxfix Product / Engineering | [platform context](../tax-advisor-platform-context.md) | 2026-07-16 | Product principles, current harness limits, and historical scope | internal source | accepted with stated limits |
| E012–E018 | Prior v0.12 research register | retained in this artifact | 2026-07-16 | Technology context only | mixed | limited |
| E019–E025 | Taxfix review | [DATEV ecosystem review](review_2026-07-17_datev_ecosystem_transcript.md) | 2026-07-17 | Integration and market constraints | mixed | accepted with stated limits |
| E026–E031 | Taxfix Product | [strategy alignment handover](product_vision_alignment_handover.md) | 2026-07-17 | Platform stages, target cohort, manual handoff, and target portfolio | dated internal strategy | accepted as direction, not proof |

## Current user truth

- User and job: An internal Taxfix Advisor needs to complete and supervise SE-DIFM work without losing the evidence, state, or professional decision.
- Current needs and desired outcome: Turn a low-volume, VAT-liable freelancer or digital-consultant bookkeeping period into an evidence-linked review outcome. Make the next human action obvious. Measure whether handling time falls.
- Current process and tools: GFR prepares a CSV; the Advisor imports it into DATEV manually; later, the Bescheid is uploaded manually back to the workspace. DATEV and ELSTER remain the statutory record.
- What works and must be preserved: Human review, manual completion, source links, visible blockers, durable history, and the ability to correct or take over.
- Main pain, risk, delay, or missed outcome: The Advisor still coordinates systems and waits. A desk without real execution leaves that burden in place; fake automation creates false-ready risk.
- Current trust and control expectations: The Advisor sees scope, evidence, changes, uncertainty, and why a run stopped. The Advisor accepts, returns, corrects, or takes over.
- Missing user evidence: We do not yet have verified eligible case volume, direct observation, observed handling-time change, or proof that this cohort will trust the flow.

### Three layers that must not be conflated

| Layer | What it is now | What this roadmap claims |
| --- | --- | --- |
| Harness now | A narrow PoC with durable execution concepts and csv_reader support. | It proves only its listed supported capabilities. |
| Monitor substrate | Reported internal efficiency work, including Tax Advisor Agent, Support Copilot, and Document Review Agent. | It is useful operating context, not a claim that the harness is already the platform. |
| Future TA Platform | The product direction: Advisor Desk, working-machine operations, opportunity signals, and later market expansion. | It is the target product, earned job by job through evidence gates. |

## Outcome foundation

- Experience and outcome to implement first: A Taxfix Advisor works one eligible SE-DIFM bookkeeping period from case to review-ready handover. Trace shows the evidence, actions, changes, reviewer decision, and blocker state.
- Why users need it now: It is a real DIFM operating job with measurable handling-time potential. It can prove the Desk moves work, rather than merely describing it.
- Quality or parity bar: Correct scope; supported evidence only; source-linked result; clear missing input; manual handoff where needed; no false-ready state; named human review.
- Foundation capabilities: Cohort and case eligibility; durable case and run state; evidence links; explicit capability gating; manual GFR CSV to DATEV handoff; manual Bescheid return; Trace; handling-time instrumentation.
- Proof that the foundation works: Verified workspace and eligible case volume; replay and live-case quality checks; review acceptance; falling handling time; no material false-ready or unrecoverable state.

| Process area | Current need | Quality to preserve | Foundation needed | Why this comes first | Evidence IDs |
| --- | --- | --- | --- | --- | --- |
| Advisor Desk | Know what to do and why | Priority, ownership, visible status | Case, task, evidence, review, and exception state | The workbench must be useful before it can drive work | E001–E008, D018 |
| Bookkeeping preparation | Move one period to review | Source fidelity and loud blockers | Eligible cohort, supported evidence, visible plan, review package | It is the first deep job | E006–E009, D019 |
| DATEV handoff | Complete the mandate without pretending integration exists | Manual control and statutory record | CSV export/import checklist and notice upload | It proves the end-to-end operating path now | E022, E028, D023 |
| Opportunity signals | Find real client needs without selling automatically | Evidence, uncertainty, and Advisor decision | Shadow scoring, source links, decision capture | Insight can learn in parallel with coverage | D020–D021 |

## Agentic transformation thesis

- North-star interaction: The Advisor gives a mission. The platform proposes a plan, performs approved work, records the Trace, asks for review, and resumes from the Advisor's decision.
- Where agentic behavior creates value: It prepares, checks, follows waits, and keeps eligible work moving across the book while the Advisor sees exceptions and decisions.
- Where deterministic automation is better: Eligibility checks, data validation, CSV creation, state transitions, permission enforcement, and regression tests.
- Where humans retain judgment or authority: Professional tax decisions, client conversations, acceptance, statutory submission, payment, and any consequential action.
- Where capability should never expand: Unsupported evidence, hidden state changes, automatic outreach or selling, autonomous filing, payment, or professional judgment.

| Process area | Current state | Proposed capability mode | User value and reason | Earliest lifecycle point | Evidence gate | User control and fallback |
| --- | --- | --- | --- | --- | --- | --- |
| Case and Desk | Fragmented operational coordination | foundation and assist | One workbench explains priority and state | Operational tool | Correct state, source coverage, Advisor usability | Take over, correct, defer, manual work |
| Bookkeeping-period preparation | Narrow harness support; manual end-to-end handoff | mixed: foundation, assist, then delegate for proven preparation | Reduces hunting and coordination on one real job | Operational tool | Eligible evidence, output quality, review acceptance, recovery | Edit scope, pause, return, use manual process |
| Trace | Evidence and review promise | foundation | Makes the work inspectable and reviewable | Operational tool | Every material result has source links and reviewer state | Return, annotate, request evidence |
| Whole-book follow-through | Not yet proven | delegate for proven internal work only | Advisor supervises exceptions instead of routine chasing | Working machine | Coverage, false-ready rate, handling time, recovery, trust | Per-job fallback and exception override |
| Opportunity signals | Not running as product behavior | assist in shadow mode | Learn which evidence-backed needs matter without changing client contact | Parallel with working-machine proof | Precision, usefulness, Advisor acceptance, no noisy harm | Advisor accepts, dismisses, saves, or starts a conversation |
| Connector automation | Manual handoff is the initial path | assist, later delegate only for approved effects | Cuts repeated manual transfer after the job is proven | Later working machine | Sanctioned route, legal and technical feasibility, quality, rollback | Keep manual handoff as fallback |

## Moving-frontier lane

The nine-month plan is not built on today's model ceiling. Each month, Product, Domain, and Engineering review what the frontier can now do for the first bookkeeping job. A frontier gain changes the roadmap only after it passes the fixed evidence gate below.

| Frontier shift | Product unlock | Roadmap effect if proven | Fixed evidence gate |
| --- | --- | --- | --- |
| Multimodal evidence | Read more invoices, statements, notices, and mixed-format evidence | Pull supported-format expansion forward | Format-specific evidence coverage, material-error rate, source linking, privacy, and recovery |
| Background agents | Keep missions alive through waits, retries, and new evidence | Pull whole-book follow-through forward | Durable state, correct resume point, visible blocker, no lost or duplicate action |
| Tool use | Complete more approved preparation steps across Taxfix systems | Pull working-machine coverage forward | Explicit permission, task success, change Trace, rollback, and no invented external-system access |
| Specialist-agent coordination | Run DataJanitor Pro, FristenGuard, and later specialists behind one mission | Parallelize bounded preparation without fragmenting the Desk | One plan, one source-linked record, conflict handling, cost, and accountable final result |
| Verification and routing | Use checks and the right model for each step | Reduce weak packages, review load, and model cost | Job regression set, false-ready rate, review acceptance, explainable routing, and rollback |
| Cost, latency, and adaptation | Monitor more of the book and learn from explicit corrections | Pull default monitoring forward for the eligible cohort | Handling-time gain, predictable cost, correction quality, privacy, and no silent authority growth |

The review asks four short questions: What improved? Which user job can it unlock? What job-specific proof is required? Which roadmap item can move only after that proof? Professional judgment, client communication, filing, payment, signing, and selling remain human-controlled.

## Before and after

- Horizon: Relative Month 9 after the verified Month 1 entry gate; later market expansion is a separate horizon.
- Before story: An Advisor opens several systems, chases evidence, imports the GFR CSV into DATEV, decides if the period is ready, and later uploads the notice. The system may show information but does not reliably own the next step.
- After story: For an eligible case, the Advisor opens Advisor Desk, sees the case mission and Trace, starts or edits the proposed run, reviews the result, completes the manual handoff when required, and supervises only material exceptions. Opportunity signals remain separate, shadow-first, and Advisor-gated.
- Observable user and beneficiary value: Quality and trust gates stay intact; handling time falls; more eligible work can be carried per Advisor; evidence-backed client needs are captured without automatic selling.

## Future operating model

| Role | Current responsibility | Future responsibility | Authority retained | New support needed |
| --- | --- | --- | --- | --- |
| Internal Taxfix Advisor | Coordinates systems, decides readiness, completes statutory work | Sets intent, reviews exceptions, accepts or returns work, completes consequential actions | Professional judgment, client contact, statutory actions | Advisor Desk, Trace, clear exception queue |
| Tax Expert | Prepares or checks bounded case work | Reviews complex preparation and hands over clear outcomes | Domain judgment and escalation | Evidence-linked task and review package |
| TA Platform | Limited operating support | Organizes, processes approved work, monitors waits, and surfaces shadow signals | No independent professional or external authority | Durable state, permissions, evaluations, recovery |
| Monitor substrate | Internal efficiency capability | Supplies learnings or reusable operating patterns where proven | Its own delivery ownership | Clear contracts with future platform work |
| Client | Supplies evidence and makes choices when asked by a human | Receives human-led service and conversations | Consent and client decisions | No automatic outreach from this roadmap |

- Exception, escalation, and fallback experience: Any unsupported evidence, failed check, stale source, material uncertainty, or incomplete handoff stops in a visible blocked state. The Advisor can take over and finish through the manual process without losing Trace.

## Configurable roadmap

| Roadmap move | Process scope | User need and experience | Capability mode | Lifecycle implication | Human role and control | Capabilities and dependencies | Required evidence IDs | Hold, narrow, rollback, or stop trigger |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Entry gate before Month 1 | SE-DIFM workspace and eligible cases | Start from real work, not a date claim | foundation | discovery remains until verified | Product names gate owner; Advisor cohort is confirmed | Workspace, case-volume, and cohort-fit verification | E027, E030, D022, O022 | Hold if workspace, eligible volume, or cohort fit is unverified |
| Monthly frontier review | The first job and next proven job | Turn model progress into earlier user value without surprising the Advisor | no automatic change | May pull a later roadmap item forward after proof | Product, Domain, and Engineering approve; Advisor authority stays fixed | Replaceable model routing, job evaluations, permission checks, cost and recovery data | E012–E018, D015–D016, D027, H026–H031 | Hold if the gain does not transfer to tax work or weakens quality, control, privacy, cost, or recovery |
| Operational tool | One bookkeeping period at a time | Move a case from intervention to handled outcome with visible evidence | mixed | Month 1–2 after entry gate | Advisor starts or edits, reviews, and can take over | Desk, Trace, evidence, task/run state, csv_reader where supported, manual GFR CSV import, manual notice upload | E006–E009, E022, E028, D009–D011, D023–D024 | Narrow to supported evidence; stop on false-ready, lost state, or failed review |
| Working machine | Eligible cases across the internal book | Routine preparation and waits advance; Advisor sees exceptions | mixed; delegate only for proven internal work | Month 3–9 relative | Advisor retains review and all consequential action | Coverage monitoring, exception routing, checks, recovery, handling-time instrumentation | D017, D021, H003, H010, H025 | Hold or roll back if quality, trust, handling time, recovery, or operating load worsens |
| Opportunity machine | The same internal book, in parallel | Surface evidence-backed client needs without touching the client | assist in shadow mode | Starts in parallel; promotion is independent of working-machine coverage | Advisor accepts, dismisses, saves, or begins a conversation | Signal definition, evidence links, confidence, unknowns, decision history | D020–D021, O023 | Keep shadow-only if signals are noisy, weakly evidenced, or not useful |
| Sanctioned connector scope | Repeated transfer effects | Reduce manual handoff only after the job is proven | assist, later narrow delegate | Later working machine | Advisor can always use manual handoff | Approved route, legal and technical feasibility, ID mapping, recovery, vendor exit plan | E021–E023, D023, H024–H025, O019–O020 | No launch without a sanctioned route, tested recovery, and manual fallback |
| Marketplace and white-label | External Kanzleien | Repeat proven internal operating model for external users | mixed | Post-transformation horizon | External Advisor remains the gatekeeper | Onboarding, training, quality checks, tenancy, support, proven working-machine outcomes | D017, D019–D021, O006, O021 | Park until the internal cohort proves quality, trust, handling time, and business value |

### Metric hierarchy

| Layer | Metric | Role | Promotion rule |
| --- | --- | --- | --- |
| Quality and trust | Evidence coverage, material error and false-ready rate, review acceptance, recoverability, privacy and authority compliance | Hard gate | A failure holds, narrows, or rolls back scope. It is never traded for speed or revenue. |
| Operating proof | Advisor handling time, case throughput, exception load, manual-rework burden | Proof the operational tool and working machine help | Must improve on eligible comparable work without breaking the hard gates. |
| Business North Star | Net Revenue per active Tax Advisor | Primary business outcome | Use it to judge whether the platform creates durable Advisor leverage and client value. |
| Diagnostic | ARPU and opportunity-driven uplift | Explains monetization changes | Use it to learn why the North Star moved; do not let it hide poor quality or operating outcomes. |

## User transition contract

- How users co-create each move: Internal Advisors select initial cases, inspect the plan and Trace, correct evidence, reject weak work, and participate in gate reviews.
- Visibility and explanation: Show scope, source, freshness, plan, actions, change, uncertainty, manual handoff status, reviewer decision, and blocker reason.
- Correction and rejection: Pause, edit, return, retry, dismiss, take over, or finish manually. Preserve the history of those choices.
- Opt-in or rollout model: Start with the verified internal SE-DIFM cohort. Expand case by case and job by job. Opportunity signals stay shadow-first until their own gate passes.
- Fallback while unproven: The manual GFR CSV to DATEV process and manual notice upload remain available. Unsupported inputs stop visibly.
- Training and support: Short role-based guidance on how to review Trace, run the manual handoff, correct a result, and report a failure.
- Feedback and learning loop: Use explicit review decisions, corrections, and handling-time data. Do not infer broader authority from passive use.

## Product decisions

- Reusable capabilities created: Durable client and case state; scoped missions and plans; task, run, event, result, and review records; evidence links; Trace; capability and permission registry; review and correction history; exception and wait monitoring; job evaluation sets; replaceable model routing; handling-time and model-cost instrumentation; opportunity decision history.
- Dependencies and integrations: GFR output, manual DATEV import, manual Bescheid upload, future sanctioned integration route, client and case ID mapping, tenant isolation, provider and data controls.
- Hard principles: Build the Codex relationship, not a chatbot. Complete an eligible job, not an AI demo. Preserve one operating state. Evidence before confidence. Block loudly. Keep the Advisor in charge of judgment and consequential actions. Treat DATEV and ELSTER as the statutory record. Earn capability per job and effect. Never equate a stronger model with broader authority.
- Major bets: One mission and one Trace can hold a growing set of specialist capabilities without overwhelming the Advisor; a deep bookkeeping job creates reusable primitives; monthly frontier review can compress delivery; handling-time proof unlocks the working machine; shadow opportunity signals can learn in parallel without putting commercial pressure on clients.
- Risks and failure implications: False-ready output, stale joined state, uncontrolled manual rework, noisy opportunities, vendor concentration, unsupported formats, weak recovery, and treating a dated strategy plan as proof of a live operating system.
- Non-goals: A terminal-shaped Codex copy; a generic tax chatbot; a claim that the planned launch is live; automatic client outreach, sales, filing, payment, signing, or professional judgment; unsupported binary parsing; a committed computer-use path; external marketplace or white-label delivery before internal proof; presenting future agent-family names as current harness support.

### Future target capability portfolio

These are target capabilities from the dated strategy snapshot. They are not present-support claims and are not a commitment to build every family.

| Target family | Future role | Relevant platform stage | Current treatment |
| --- | --- | --- | --- |
| DataJanitor Pro | Intake, normalisation, chart-of-accounts mapping, and DATEV-ready work packages | Operational tool to working machine | Future target; current harness support remains narrow |
| FristenGuard | Deadline, risk, missing-document, and capacity sentinel | Working machine | Future target; use only after source and evaluation proof |
| OpsMaestro | Practice workflow, WIP, bottleneck, and capacity orchestration | Working machine at scale | Future target; not a current Desk capability claim |
| AdvisorLens | Evidence-backed advisory and monetization signals | Opportunity machine | Shadow-first and Tax Advisor-gated target |
| ClientFit Scout | Lead fit, tiering, and pricing support | Opportunity machine and later market expansion | Future target; no automatic client decision or action |

## Horizon and gates

- Now and why: Verify the Month 1 entry gate, then prove the operational tool on real eligible SE-DIFM cases with the manual handoff.
- Next and why: Build working-machine coverage around the proven job. Instrument handling time and improve exception management.
- Pull-forward rule: Review frontier progress every month. Move an item earlier only when its job-specific gate passes; keep its human-authority boundary unchanged.
- Later and why: Promote useful opportunity signals only after their own shadow evidence. Add sanctioned connector automation only after its own gate.
- Post-transformation horizon: Marketplace and white-label follow internal quality, operating, and business proof; they have no live-date claim here.
- Never and why: Hidden authority expansion, unsupported evidence handling, unreviewed external action, and pretending a target portfolio is present support violate the product contract.

| Requested move | Lifecycle transition | Capability transition | Evidence required | Gate owner | Gate decision | Consequence |
| --- | --- | --- | --- | --- | --- | --- |
| Open Month 1 | discovery to controlled internal operation | none to foundation | Verified workspace, eligible volume, cohort fit, named internal Advisors | Product / Operations | hold | Narrow and wait for O022 |
| Pull a roadmap item forward | no automatic lifecycle change | only the already-approved capability transition | Job-specific regression, source coverage, quality, privacy, cost, recovery, and Advisor-control proof | Product, Domain, Engineering, Security/Privacy where relevant | not-decided | Pull forward, keep planned, narrow, or rollback |
| Prove the operational tool | controlled internal operation | foundation and assist to bounded preparation delegation | Case quality, review acceptance, Trace coverage, recovery, handling-time baseline | Product with Domain and Engineering | not-decided | Continue, narrow, or roll back job scope |
| Promote working-machine coverage | controlled internal operation to broader internal rollout | delegate for proven internal work | Quality/trust gates, falling handling time, exception load, recovery, Advisor acceptance | Product with Domain, Operations, Engineering | not-decided | Continue, narrow, or rollback |
| Promote an opportunity signal | shadow to Advisor-visible assist | shadow assist to visible assist | Precision, evidence quality, Advisor acceptance, client-benefit rationale, no automatic contact | Product with Advisors | not-decided | Keep shadow, narrow, or stop |
| Add sanctioned connector automation | later internal rollout | assist to narrow approved delegation | Sanctioned route, technical feasibility, data mapping, quality, recovery, exit plan | Product, Legal, Engineering, Operations | not-decided | Keep manual handoff or park |
| Start external market expansion | post-transformation | mixed | Internal quality and trust proof, handling-time improvement, business North Star movement, tenancy and support readiness | Product leadership | not-decided | Park |
| Promote a model, tool, format, or provider | no automatic lifecycle change | no automatic authority change | Job regression, evidence coverage, errors, recovery, privacy, cost, and rollback proof | Product, Domain, Engineering, Security/Privacy | not-decided | Continue, hold, or rollback |

## Decision and handoff

- Confirmed decisions: D001, D003–D018, and D019–D027. The TA Platform frame, Codex-for-Tax-Advisors north star, first cohort, three-stage model, monthly frontier lane, parallel shadow opportunity track, metric hierarchy, real Month 1 gate, manual initial handoff, Trace promise, and future target portfolio are settled.
- Assumptions and hypotheses: H003–H006, H010, H012–H016, H018–H019, and H022–H031. These guide sequencing but do not prove real workflow adoption, frontier transfer, or integration feasibility.
- Contradictions with user evidence, quality, or principles: A claim that Month 1 is already live would contradict D022. A computer-use commitment would contradict D023. Broad platform claims based on harness support would contradict E009 and D025. Treating model progress as automatic permission or product support would contradict D016 and D027.
- Blockers: O022 blocks the real Month 1 start. O004 blocks confidence in the operating model. O019 and O020 block later connector automation. O023 blocks opportunity-signal promotion.
- Inputs the next conversation should read: This roadmap, [strategy alignment handover](product_vision_alignment_handover.md), [platform context](../tax-advisor-platform-context.md), direct Advisor observations, and the verified workspace/case-volume record when available.
- Output links: [this artifact](product_vision.md) | [transcript](product_vision_agent_transcript.md) | canonical brief: Open
- Recommended next conversation: Use the first Codex-for-TA workbench mock to test the Mission → Plan → Work → Trace → Review → Resume loop, then define the first bookkeeping-case evaluation pack and handling-time baseline.
