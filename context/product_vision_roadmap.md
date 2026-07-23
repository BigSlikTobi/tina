# 🗣️ Product vision (roadmap)

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

This v0.14 increment makes the product north star and the moving AI frontier explicit. It keeps the v0.13 TA Platform structure, stable IDs, operating gates, and current-capability boundaries.

## Product north star

**The TA Platform is the Codex for Tax Advisors. Advisor Desk is its workbench.**

The Advisor gives one client mission. The platform plans it, works it through approved capabilities, shows the Trace, stops at human gates, and resumes after correction. The working loop is:

`Mission → Plan → Work → Trace → Review → Resume`

This means one Desk, one mission, one source-linked record, and one exception stream. The Advisor can inspect, interrupt, correct, return, retry, or take over. "Codex" describes the working relationship. It does not mean copying a terminal or adding a chatbot to today's Desk.

## Key confirmed decisions

| ID | Decision | Date | Owner |
|---|---|---|---|
| ADV-MORNING-001-VIS-D001 | The product direction is AI-first. | 2026-07-16 | Product |
| ADV-MORNING-001-VIS-D004 | The Advisor uses an agentic workbench, not a copilot or autonomous practice manager. | 2026-07-16 | Product |
| ADV-MORNING-001-VIS-D007 | Control transfers progressively, visibly, correctably, and reversibly. | 2026-07-16 | Product |
| ADV-MORNING-001-VIS-D008 | The start combines a trusted Desk with one real agentic loop. | 2026-07-16 | Product |
| ADV-MORNING-001-VIS-D009 | The first differentiator is intervention to handled outcome. | 2026-07-16 | Product |
| ADV-MORNING-001-VIS-D011 | The first release proves one deep executable job. Unsupported work stays explain-or-prepare only. | 2026-07-16 | Product |
| ADV-MORNING-001-VIS-D013 | Organize work, process approved work, and decide consequential matters remain separate responsibilities. | 2026-07-16 | Product |
| ADV-MORNING-001-VIS-D018 | The product is the TA Platform. Advisor Desk is its user-facing workbench. | 2026-07-17 | Product |
| ADV-MORNING-001-VIS-D019 | The initial operating horizon is internal Taxfix Advisors serving SE-DIFM, starting with low-document-volume VAT-liable freelancers and digital consultants. | 2026-07-17 | Product |
| ADV-MORNING-001-VIS-D020 | Build through operational tool, working machine, and opportunity machine. Start opportunity signals in parallel, shadow-first, and Tax Advisor-gated. | 2026-07-17 | Product |
| ADV-MORNING-001-VIS-D021 | Quality and trust are hard gates. Falling handling time is operating proof. Net Revenue per active Tax Advisor is the business North Star; ARPU is a diagnostic. | 2026-07-17 | Product |
| ADV-MORNING-001-VIS-D022 | Month 1 begins only after verified SE-DIFM workspace availability and enough eligible case volume. No calendar date is claimed as live here. | 2026-07-17 | Product |
| ADV-MORNING-001-VIS-D023 | Start with manual GFR CSV to DATEV import and manual Bescheid upload. Use a sanctioned API or connector only as later, separately approved automation. No computer-use path is committed. | 2026-07-17 | Product |
| ADV-MORNING-001-VIS-D024 | Trace is the present evidence-and-review promise: source links, what changed, reviewer decision, and visible blockers. | 2026-07-17 | Product |
| ADV-MORNING-001-VIS-D025 | The named agent families are future target capabilities. Keep harness-now, Monitor substrate, and future TA Platform clearly separate. | 2026-07-17 | Product |
| ADV-MORNING-001-VIS-D026 | "Codex for Tax Advisors" is the explicit north-star experience for the TA Platform. | 2026-07-17 | Product |
| ADV-MORNING-001-VIS-D027 | The moving AI frontier is a visible monthly roadmap lane. Proven frontier gains may pull work forward, but they never expand product support or human authority automatically. | 2026-07-17 | Product |

## Current user truth
- User and job: An internal Taxfix Advisor needs to complete and supervise SE-DIFM work without losing the evidence, state, or professional decision.
- Current needs: Turn a low-volume, VAT-liable freelancer or digital-consultant bookkeeping period into an evidence-linked review outcome. Make the next human action obvious. Measure whether handling time falls.
- Current process: GFR prepares a CSV; the Advisor imports it into DATEV manually; later, the Bescheid is uploaded manually back to the workspace. DATEV and ELSTER remain the statutory record.
- What works and must be preserved: Human review, manual completion, source links, visible blockers, durable history, and the ability to correct or take over.
- Main pain: The Advisor still coordinates systems and waits. A desk without real execution leaves that burden in place; fake automation creates false-ready risk.
- Missing user evidence: We do not yet have verified eligible case volume, direct observation, observed handling-time change, or proof that this cohort will trust the flow.

### Three layers that must not be conflated

| Layer | What it is now | What this roadmap claims |
|---|---|---|
| Harness now | A narrow PoC with durable execution concepts and csv_reader support. | It proves only its listed supported capabilities. |
| Monitor substrate | Reported internal efficiency work, including Tax Advisor Agent, Support Copilot, and Document Review Agent. | It is useful operating context, not a claim that the harness is already the platform. |
| Future TA Platform | The product direction: Advisor Desk, working-machine operations, opportunity signals, and later market expansion. | It is the target product, earned job by job through evidence gates. |

## Agentic transformation thesis
- North-star interaction: The Advisor gives a mission. The platform proposes a plan, performs approved work, records the Trace, asks for review, and resumes from the Advisor's decision.
- Where agentic behavior creates value: It prepares, checks, follows waits, and keeps eligible work moving across the book while the Advisor sees exceptions and decisions.
- Where deterministic automation is better: Eligibility checks, data validation, CSV creation, state transitions, permission enforcement, and regression tests.
- Where humans retain judgment or authority: Professional tax decisions, client conversations, acceptance, statutory submission, payment, and any consequential action.
- Where capability should never expand: Unsupported evidence, hidden state changes, automatic outreach or selling, autonomous filing, payment, or professional judgment.

## Configurable roadmap

| Roadmap move | Process scope | Capability mode | Lifecycle implication | Human role and control | Hold or stop trigger |
|---|---|---|---|---|---|
| Entry gate before Month 1 | SE-DIFM workspace and eligible cases | foundation | discovery remains until verified | Product names gate owner; Advisor cohort is confirmed | Hold if workspace, eligible volume, or cohort fit is unverified |
| Monthly frontier review | The first job and next proven job | no automatic change | May pull a later roadmap item forward after proof | Product, Domain, and Engineering approve; Advisor authority stays fixed | Hold if the gain does not transfer to tax work or weakens quality, control, privacy, cost, or recovery |
| Operational tool | One bookkeeping period at a time | mixed | Month 1–2 after entry gate | Advisor starts or edits, reviews, and can take over | Narrow to supported evidence; stop on false-ready, lost state, or failed review |
| Working machine | Eligible cases across the internal book | mixed; delegate only for proven internal work | Month 3–9 relative | Advisor retains review and all consequential action | Hold or roll back if quality, trust, handling time, recovery, or operating load worsens |
| Opportunity machine | The same internal book, in parallel | assist in shadow mode | Starts in parallel; promotion is independent | Advisor accepts, dismisses, saves, or begins a conversation | Keep shadow-only if signals are noisy, weakly evidenced, or not useful |
| Sanctioned connector scope | Repeated transfer effects | assist, later narrow delegate | Later working machine | Advisor can always use manual handoff | No launch without a sanctioned route, tested recovery, and manual fallback |
| Marketplace and white-label | External Kanzleien | mixed | Post-transformation horizon | External Advisor remains the gatekeeper | Park until the internal cohort proves quality, trust, handling time, and business value |

### Metric hierarchy

| Layer | Metric | Role | Promotion rule |
|---|---|---|---|
| Quality and trust | Evidence coverage, material error and false-ready rate, review acceptance, recoverability, privacy and authority compliance | Hard gate | A failure holds, narrows, or rolls back scope. It is never traded for speed or revenue. |
| Operating proof | Advisor handling time, case throughput, exception load, manual-rework burden | Proof the operational tool and working machine help | Must improve on eligible comparable work without breaking the hard gates. |
| Business North Star | Net Revenue per active Tax Advisor | Primary business outcome | Use it to judge whether the platform creates durable Advisor leverage and client value. |
| Diagnostic | ARPU and opportunity-driven uplift | Explains monetization changes | Use it to learn why the North Star moved; do not let it hide poor quality or operating outcomes. |

## Future target capability portfolio

These are target capabilities from the dated strategy snapshot. They are not present-support claims.

| Target family | Future role | Relevant platform stage | Current treatment |
|---|---|---|---|
| DataJanitor Pro | Intake, normalisation, chart-of-accounts mapping, and DATEV-ready work packages | Operational tool to working machine | Future target; current harness support remains narrow |
| FristenGuard | Deadline, risk, missing-document, and capacity sentinel | Working machine | Future target; use only after source and evaluation proof |
| OpsMaestro | Practice workflow, WIP, bottleneck, and capacity orchestration | Working machine at scale | Future target; not a current Desk capability claim |
| AdvisorLens | Evidence-backed advisory and monetization signals | Opportunity machine | Shadow-first and Tax Advisor-gated target |
| ClientFit Scout | Lead fit, tiering, and pricing support | Opportunity machine and later market expansion | Future target; no automatic client decision or action |

## Decision and handoff
- Confirmed decisions: D001, D003–D018, and D019–D027. The TA Platform frame, Codex north star, first cohort, three-stage model, monthly frontier lane, parallel shadow opportunity track, metric hierarchy, real Month 1 gate, manual initial handoff, Trace promise, and future target portfolio are settled.
- Blockers: O022 blocks the real Month 1 start. O004 blocks confidence in the operating model. O019 and O020 block later connector automation. O023 blocks opportunity-signal promotion.
- Gate decision: hold → narrow.
