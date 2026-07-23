# 📄 Metrics and gates (full document)

# Metrics, Learning, and Decision Gates: Advisor Day and Bookkeeping Period
- Artifact ID: ADV-MORNING-001-MET-A001
- Artifact type: metrics-learning-contract
- Version: 1.1
- Artifact completeness: complete
- Job ID: ADV-MORNING-001
- Canonical lifecycle stage: discovery
- Capability mode: mixed
- Requested transition: Discovery to build, then build to synthetic replay, with no capability-mode or authority expansion.
- Gate decision: hold
- Decision consequence: narrow
- Owner: Product
- Updated date: 2026-07-19
- Canonical brief: Open. No canonical JTBD dossier exists for this job.

## Evidence and decision register

| ID | Type | Status | Claim or decision | Date | Owner | Confidence |
|---|---|---|---|---|---|---|
| ADV-MORNING-001-MET-E001 | fact | active | The current canonical lifecycle stage is discovery and the current capability mode is mixed. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-E002 | fact | active | The deep job is an eligible SE-DIFM bookkeeping period that ends in an evidence-linked package, Advisor accept or return, and a controlled manual DATEV handoff. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-E003 | fact | active | The first evaluation mode is synthetic replay. Real or re-identifiable client data needs fresh named authorization. | 2026-07-19 | Product / Security / Privacy | high |
| ADV-MORNING-001-MET-E004 | fact | active | Quality and trust are hard gates. Handling time and operating load prove user value. Net Revenue per active Tax Advisor is the business North Star. ARPU is diagnostic. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-E005 | fact | active | SQL can currently measure workflow timestamps, task and run states, review outcomes, and parts of retry and recovery. | 2026-07-19 | Engineering | high |
| ADV-MORNING-001-MET-E006 | fact | active | The current runtime cannot yet calculate authoritative eligibility, false-ready, material correction, Advisor hands-on time, exact DATEV handoff outcome, or opportunity quality. | 2026-07-19 | Product / Domain / Engineering | high |
| ADV-MORNING-001-MET-E007 | fact | active | A missing denominator, rubric, or critical event blocks the affected gate. Metrics never expand lifecycle or capability automatically. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D001 | decision | active | Use separate bookkeeping-period and Advisor-day scorecards. Do not combine them into one weighted score. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D002 | decision | active | Product owns the final gate. Domain, Advisors, and responsible control owners have veto rights in their areas. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D003 | decision | active | Keep numeric thresholds open until the exact case rubric is defined and a five-day Advisor baseline is collected. | 2026-07-19 | Product / Domain | high |
| ADV-MORNING-001-MET-D004 | decision | active | A correction is material when it changes readiness, reconciliation, a missing-evidence request, the Advisor decision, or the manual DATEV handoff. Wording and layout-only edits are not material. Observe corrections until the manual DATEV handoff is reconciled. | 2026-07-19 | Domain / Advisors | high |
| ADV-MORNING-001-MET-D005 | decision | active | Use two immediate lifecycle gates: discovery to build for contract and measurement readiness, then build to synthetic replay for observed product proof. Neither gate expands capability mode or authority. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D006 | decision | active | Build the Advisor-day baseline from named internal SE-DIFM Advisors across five normal full workdays. Mark bookkeeping work separately so the Advisor-day and bookkeeping-period baselines remain distinct. | 2026-07-19 | Product / Advisors / Research | high |
| ADV-MORNING-001-MET-D007 | decision | active | The first baseline replay case is one German VAT-liable SE-DIFM freelancer or digital consultant, one calendar month, low document volume, and realistic synthetic structured bank, invoice, open-item, and ledger inputs. The exact low-volume rule, schema, and gold output remain open. | 2026-07-19 | Product / Domain | high |
| ADV-MORNING-001-MET-D008 | decision | active | A package is acceptable only for the correct client and month, with every required input present or visibly missing, supported evidence reconciled, every material claim source-linked, conflicts and unknowns visible, unsupported evidence blocked, and human accept or return available. It is false-ready if any required input, material conflict, capability, check, or review is missing while the system says ready. | 2026-07-19 | Domain / Advisors | high |
| ADV-MORNING-001-MET-D009 | decision | active | The first manual downstream handoff must not depend on GFR availability or a GFR connection. Define a vendor-neutral, versioned, human-operated handoff contract. | 2026-07-19 | Product / Operations | high |
| ADV-MORNING-001-MET-D010 | decision | active | Build and test the PDF reader in parallel. Keep its exact version and hash inactive for bookkeeping runs until its separate extraction, evidence-linking, safe-disposition, cost, and approval proof passes. Promote it into the normal bookkeeping path only after that human gate. | 2026-07-19 | Product / Domain / Engineering / Execution Safety | high |
| ADV-MORNING-001-MET-D011 | decision | active | Use a vendor-neutral manual handoff. Taxfix creates a versioned package with structured bookkeeping data, reconciliation summary, unresolved items, and source list. A named human transfers it through the approved process. Taxfix records destination, package version, operator, time, and `successful`, `failed`, or `unknown`; an unknown result is reconciled before retry. | 2026-07-19 | Product / Domain / Operations | high |
| ADV-MORNING-001-MET-D012 | decision | active | Use a versioned gold case pack containing the fake client and month, input manifest, expected matches and unmatched items, missing inputs, conflicts, expected claims and evidence links, correct readiness result, and expected handoff outcome. Domain and an Advisor approve the answer key before evaluation. | 2026-07-19 | Domain / Advisors | high |
| ADV-MORNING-001-MET-D013 | decision | active | Product owns the final gate. Domain owns accounting rules and gold answers. Advisor representatives own usefulness and acceptance truth. Engineering owns runtime and measurement events. Execution Safety owns permissions and PDF safety. Security/Privacy owns the data path. Operations owns support, recovery, and manual handoff. Actual names are required before G001 can pass. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D014 | decision | active | Replay must cover every required happy, exception, recovery, authority, scope, and malicious-input scenario. Product and Domain set the exact number of case variations after the baseline but before G001 and replay. They may not change the number after seeing results. | 2026-07-19 | Product / Domain | high |
| ADV-MORNING-001-MET-D015 | decision | active | Separate the metric system into four early success KPIs, later business KPIs, non-negotiable guardrails, and learning metrics. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-O002 | open question | delegated | D007 fixes the archetype and period. D012 fixes the gold-pack structure. Product and Domain must fill the exact low-volume rule, schema values, required fields, gold answers, and exclusions before G001. | 2026-07-19 | Product / Domain | high |
| ADV-MORNING-001-MET-O004 | open question | delegated | D013 fixes the responsible roles. Product must record the actual names before G001. | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-O005 | open question | delegated | D006 fixes five full Advisor-days. D014 requires Product and Domain to fix the named Advisors and minimum synthetic-period volume after the baseline but before G001 and replay. | 2026-07-19 | Product / Domain / Research | high |

## Configurable transition gates

| Gate ID | Lifecycle transition | Capability transition | User-value gate | Outcome and quality gate | Safety, authority, trust, and control gate | Adoption and operations gate | Evidence volume/window | Decision owner |
|---|---|---|---|---|---|---|---|---|
| ADV-MORNING-001-MET-G001 | discovery to build | mixed to mixed; no authority expansion | Both scorecards have fixed jobs, denominators, formulas, sources, owners, and baseline plans | Case rubric, gold fixtures, material-correction rule, false-ready rule, and readiness checks are executable | Immediate-stop events, permissions, human gates, rollback, and denied-action evidence are testable | Five-day baseline plan, instrumentation contract, QA owner, support route, and current-workflow comparator exist | Exact rubric and event contract plus approved five-day baseline plan; numeric volume open | Product; Domain, Advisors, and control owners hold area vetoes |
| ADV-MORNING-001-MET-G002 | build to replay | mixed to mixed; synthetic L2 preparation only | Early KPIs M001, M008, M015, and M016 meet thresholds fixed before replay | Bookkeeping outcome and Advisor-day quality thresholds pass; no critical data-quality gap | All hard guardrails pass; pause, cancel, correct, return, retry, resume, and take-over work | Replay is repeatable; support and recovery work; effort and cost are observable | Minimum eligible synthetic periods and replay window delegated under O005 | Product; Domain, Advisors, and control owners hold area vetoes |

## Decision rules

| Gate ID | Go when | Hold when | Kill when | Consequence | Remediation |
|---|---|---|---|---|---|
| ADV-MORNING-001-MET-G001 | O002 and O004–O005 are closed; both scorecards and the D010 PDF capability proof are measurable; owners, data quality, baseline, rubric, fixtures, and breach actions are fixed before results | Any denominator, rubric, owner, event, baseline plan, capability proof, or critical guardrail is missing | The job cannot be made bounded, reviewable, or safe inside the approved authority and data boundary | go: continue to build; hold: narrow; kill: park or stop | Close the missing contract item, rerun measurability review, and record the human decision |
| ADV-MORNING-001-MET-G002 | M001, M008, M015, and M016 each pass their pre-set threshold; all hard guardrails pass; evidence is complete | Any KPI misses, a guardrail breaches, evidence volume is weak, data is incomplete, or recovery/support is not ready | A stop-level failure shows the proposed job or mode is not worth continuing and cannot be removed by narrowing | go: continue to the next separately approved mode; hold: narrow or rollback; kill: park or stop | Use the learning metrics to find the cause, fix or narrow it, rerun replay, and hold a new human gate |

## KPI hierarchy and success rule

### Early product KPIs

These four KPIs decide G002. Each must meet the numeric threshold fixed after the baseline and before replay.

| KPI ID | Success question | Measurement |
|---|---|---|
| ADV-MORNING-001-MET-M001 | Does the product finish eligible bookkeeping periods correctly? | Eligible periods accepted within the target clock without a material correction / all eligible periods entering evaluation |
| ADV-MORNING-001-MET-M008 | Does the product reduce real Advisor effort per accepted period? | Active Advisor minutes for scope, review, correction, and handoff / accepted periods |
| ADV-MORNING-001-MET-M015 | Does the workbench help the Advisor find the correct next action faster? | Time from opening or returning until the correct material action is selected |
| ADV-MORNING-001-MET-M016 | Does the workbench show all material work? | Material work items shown / all material work items in the reconciled daily answer set |

### Later operating and business KPIs

| KPI ID | Success question | Measurement |
|---|---|---|
| ADV-MORNING-001-MET-M022 | Does the product create Advisor capacity? | Accepted eligible periods / active Advisor FTE in the same period |
| ADV-MORNING-001-MET-M023 | Does that capacity create durable business value? | Net revenue attributable to the approved cohort / active Advisor FTE in the same window |

### Hard guardrails

| Metric ID | Guardrail | Gate treatment |
|---|---|---|
| ADV-MORNING-001-MET-M003 | False-ready | Target zero; any event stops the affected mode |
| ADV-MORNING-001-MET-M004 | Material corrections | Must remain within the pre-set threshold; investigate every material correction |
| ADV-MORNING-001-MET-M005 | Material evidence coverage | Every material claim must link to exact evidence |
| ADV-MORNING-001-MET-M012 | Retry and resume integrity | No lost or duplicate action; any duplicate external effect stops the path |
| ADV-MORNING-001-MET-M013 | Authority, scope, privacy, and unsupported-content stop events | Target zero; any event stops the affected mode |
| ADV-MORNING-001-MET-M016 | Missed critical Advisor-day work | Any missed stop-level item blocks the gate even if the overall KPI threshold passes |
| ADV-MORNING-001-MET-M021 | Stale, duplicate, or misclassified work | A stop-level wrong-scope or stale item blocks the affected gate |
| ADV-MORNING-001-MET-M029–M030 | PDF safety and material extraction error | Reader remains inactive until its separate gate passes; unsafe or false-ready behavior targets zero |

### Gate success formula

G002 passes only when:

`M001 passes AND M008 passes AND M015 passes AND M016 passes AND every hard guardrail passes AND required evidence is complete.`

No weighted average is allowed. Revenue and opportunity results do not participate in G002.

## Learning loops

| If this happens | Read these learning metrics | What we learn or change |
|---|---|---|
| Trusted completion M001 is weak | M002, M004, M006, M007, M009, M011 | Separate wrong outcomes, corrections, missed issues, review returns, slow flow, and blockers; fix the case contract, capability, or workflow |
| Advisor effort M008 does not improve | M007, M009, M010, M011, M014 | Find whether time moved into review, rework, waiting, support, or expensive tooling |
| Next-action time M015 does not improve | M017, M018, M019, M021 | Find noise, source hunting, context switching, bad ranking, stale state, or wrong ownership |
| Material coverage M016 is weak | M017, M020, M021 | Find missing sources, parallel-system work, stale items, duplicates, and classification gaps |
| Advisors do not trust or adopt the product | M007, M019, M020 plus return, takeover, and correction reasons | Distinguish weak output from poor explanation, missing control, training problems, or unsupported work |
| Unit economics are weak | M014, M024 | Separate model/tool cost, support cost, and hidden rework before making a scale claim |
| Opportunity signals are noisy | M025–M026 | Learn usefulness, dismissal reasons, conversation progress, revenue, and trust harm without changing bookkeeping readiness |

## Evaluation and learning plan

- Evaluation mode: Observe the current Advisor workflow for five normal workdays to establish the Advisor-day baseline. Use synthetic replay for the first product evaluation.
- What this mode cannot prove: Real-client data handling, real adoption, live handling-time improvement, live DATEV integration, buyer demand, business North Star movement, or controlled-live safety.
- Biggest assumption: The workbench and deep preparation reduce coordination and preparation work without moving equal or greater effort into review, correction, support, or parallel-system maintenance.
- Open learning questions: (1) Does the Advisor find the correct next material action faster? (2) Does the workbench catch material work without creating noisy interventions? (3) Does an eligible bookkeeping period reach accepted review without false-ready or material correction? (4) Where does time move: preparation, waiting, review, correction, handoff, or support? (5) Which eligibility, input, capability, and blocker reasons prevent trusted completion? (6) Do retry, resume, handoff, and correction preserve state without duplicates or lost work? (7) Do Advisors rely appropriately, or do they rubber-stamp, over-check, override, or maintain a parallel system? (8) Which client and case segments perform differently, and why?
- Allowed effects: Observation of the approved current workflow; synthetic Taxfix-owned state changes; no real client-data model use; no automatic external effect.
- Rollback or remediation plan: Stop the affected evaluation, preserve evidence, return to the current manual workflow, narrow the supported case or capability, fix instrumentation or behavior, and require a fresh human gate.

## Decision

- Proposed gate decision: hold
- Proposed consequence: narrow
- Blocking guardrail or open-question IDs: ADV-MORNING-001-MET-O002 and O004–O005
- Automatic lifecycle or capability expansion: forbidden

## Decision and handoff

- Confirmed decisions: D001–D015
- Blockers: Product and Domain must instantiate the structured schema and gold answers, actual owner names, named baseline Advisors, numeric thresholds, and minimum replay volume before G001.
- Recommended next conversation: Collect the five-day baseline, instantiate the gold case pack, name the owners, and precommit numeric thresholds and replay volume before the G001 decision.
