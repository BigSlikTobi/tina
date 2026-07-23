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
- Input artifacts: ADV-MORNING-001-SOTA-A001 v1.2 ([SOTA benchmark](SOTA/sota_benchmark.md)); ADV-MORNING-001-MVP-A001 v1.0 ([Agentic MVP](agentic_mvp.md)); ADV-MORNING-001-VIS-A001 v0.14 ([Product Vision](product_vision.md)); TAX-PLATFORM-CONTEXT-A001 v0.1 ([platform context](../tax-advisor-platform-context.md)); [Agentic Tax Practice Manifesto](../../agentic-tax-practice-manifesto.md); [Ways of Working](../../ways-of-working.md)
- Transcript link: [metrics_agent_transcript.md](metrics_agent_transcript.md)
- Thought-process link: [metrics_thought_process.md](metrics_thought_process.md)
- Shareable teaching mock: [metrics_dashboard_mock.md](metrics_dashboard_mock.md)

## Evidence and decision register

Use stable `ADV-MORNING-001-MET-E/D/H/O###` IDs, `ADV-MORNING-001-MET-M###` metric IDs, and
`ADV-MORNING-001-MET-G###` gate IDs. Never renumber referenced IDs.

| ID | Type | Status | Claim or decision | Source/link | Date | Owner | Confidence |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-MET-E001 | fact | active | The current canonical lifecycle stage is discovery and the current capability mode is mixed. | [MVP](agentic_mvp.md); [Vision](product_vision.md) | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-E002 | fact | active | The deep job is an eligible SE-DIFM bookkeeping period that ends in an evidence-linked package, Advisor accept or return, and a controlled manual DATEV handoff. | ADV-MORNING-001-SOTA-D013–D014; ADV-MORNING-001-MVP-D007–D009 | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-E003 | fact | active | The first evaluation mode is synthetic replay. Real or re-identifiable client data needs fresh named authorization. | ADV-MORNING-001-MVP-D008; [platform context](../tax-advisor-platform-context.md#evaluation-modes) | 2026-07-19 | Product / Security / Privacy | high |
| ADV-MORNING-001-MET-E004 | fact | active | Quality and trust are hard gates. Handling time and operating load prove user value. Net Revenue per active Tax Advisor is the business North Star. ARPU is diagnostic. | ADV-MORNING-001-VIS-D021; [Vision metric hierarchy](product_vision.md#metric-hierarchy) | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-E005 | fact | active | SQL can currently measure workflow timestamps, task and run states, review outcomes, and parts of retry and recovery. | Local v2 runtime and schema inspection | 2026-07-19 | Engineering | high |
| ADV-MORNING-001-MET-E006 | fact | active | The current runtime cannot yet calculate authoritative eligibility, false-ready, material correction, Advisor hands-on time, exact DATEV handoff outcome, or opportunity quality. | Local v2 runtime and schema inspection | 2026-07-19 | Product / Domain / Engineering | high |
| ADV-MORNING-001-MET-E007 | fact | active | A missing denominator, rubric, or critical event blocks the affected gate. Metrics never expand lifecycle or capability automatically. | [Ways of Working](../../ways-of-working.md#metrics-and-decision-gates) | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D001 | decision | active | Use separate bookkeeping-period and Advisor-day scorecards. Do not combine them into one weighted score. | User confirmation | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D002 | decision | active | Product owns the final gate. Domain, Advisors, and responsible control owners have veto rights in their areas. | User confirmation | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D003 | decision | active | Keep numeric thresholds open until the exact case rubric is defined and a five-day Advisor baseline is collected. | User confirmation | 2026-07-19 | Product / Domain | high |
| ADV-MORNING-001-MET-D004 | decision | active | A correction is material when it changes readiness, reconciliation, a missing-evidence request, the Advisor decision, or the manual DATEV handoff. Wording and layout-only edits are not material. Observe corrections until the manual DATEV handoff is reconciled. | User confirmation | 2026-07-19 | Domain / Advisors | high |
| ADV-MORNING-001-MET-D005 | decision | active | Use two immediate lifecycle gates: discovery to build for contract and measurement readiness, then build to synthetic replay for observed product proof. Neither gate expands capability mode or authority. | User confirmation | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D006 | decision | active | Build the Advisor-day baseline from named internal SE-DIFM Advisors across five normal full workdays. Mark bookkeeping work separately so the Advisor-day and bookkeeping-period baselines remain distinct. | User confirmation | 2026-07-19 | Product / Advisors / Research | high |
| ADV-MORNING-001-MET-D007 | decision | active | The first baseline replay case is one German VAT-liable SE-DIFM freelancer or digital consultant, one calendar month, low document volume, and realistic synthetic structured bank, invoice, open-item, and ledger inputs. The exact low-volume rule, schema, and gold output remain open. | User confirmation | 2026-07-19 | Product / Domain | high |
| ADV-MORNING-001-MET-D008 | decision | active | A package is acceptable only for the correct client and month, with every required input present or visibly missing, supported evidence reconciled, every material claim source-linked, conflicts and unknowns visible, unsupported evidence blocked, and human accept or return available. It is false-ready if any required input, material conflict, capability, check, or review is missing while the system says ready. | User confirmation | 2026-07-19 | Domain / Advisors | high |
| ADV-MORNING-001-MET-D009 | decision | active | The first manual downstream handoff must not depend on GFR availability or a GFR connection. Define a vendor-neutral, versioned, human-operated handoff contract. | User direction | 2026-07-19 | Product / Operations | high |
| ADV-MORNING-001-MET-D010 | decision | active | Build and test the PDF reader in parallel. Keep its exact version and hash inactive for bookkeeping runs until its separate extraction, evidence-linking, safe-disposition, cost, and approval proof passes. Promote it into the normal bookkeeping path only after that human gate. | User confirmation | 2026-07-19 | Product / Domain / Engineering / Execution Safety | high |
| ADV-MORNING-001-MET-D011 | decision | active | Use a vendor-neutral manual handoff. Taxfix creates a versioned package with structured bookkeeping data, reconciliation summary, unresolved items, and source list. A named human transfers it through the approved process. Taxfix records destination, package version, operator, time, and `successful`, `failed`, or `unknown`; an unknown result is reconciled before retry. | User confirmation | 2026-07-19 | Product / Domain / Operations | high |
| ADV-MORNING-001-MET-D012 | decision | active | Use a versioned gold case pack containing the fake client and month, input manifest, expected matches and unmatched items, missing inputs, conflicts, expected claims and evidence links, correct readiness result, and expected handoff outcome. Domain and an Advisor approve the answer key before evaluation. | User confirmation | 2026-07-19 | Domain / Advisors | high |
| ADV-MORNING-001-MET-D013 | decision | active | Product owns the final gate. Domain owns accounting rules and gold answers. Advisor representatives own usefulness and acceptance truth. Engineering owns runtime and measurement events. Execution Safety owns permissions and PDF safety. Security/Privacy owns the data path. Operations owns support, recovery, and manual handoff. Actual names are required before G001 can pass. | User confirmation | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-D014 | decision | active | Replay must cover every required happy, exception, recovery, authority, scope, and malicious-input scenario. Product and Domain set the exact number of case variations after the baseline but before G001 and replay. They may not change the number after seeing results. | User confirmation | 2026-07-19 | Product / Domain | high |
| ADV-MORNING-001-MET-D015 | decision | active | Separate the metric system into four early success KPIs, later business KPIs, non-negotiable guardrails, and learning metrics. The detailed metric catalog supports these layers but does not turn every metric into a KPI. | User confirmation | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-H001 | hypothesis | superseded | The proposed two-gate structure is confirmed by D005. | ADV-MORNING-001-MET-D005 | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-H002 | hypothesis | active | The first shot can include both the daily workbench and the deep bookkeeping mission if each has its own denominator, evidence, and result. | ADV-MORNING-001-MVP-D016; ADV-MORNING-001-MET-D001 | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-H003 | hypothesis | superseded | Confirmed by D010. | ADV-MORNING-001-MET-D010 | 2026-07-19 | Product / Domain / Engineering | high |
| ADV-MORNING-001-MET-O001 | open question | superseded | Resolved by D005. | ADV-MORNING-001-MET-D005 | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-O002 | open question | delegated | D007 fixes the archetype and period. D012 fixes the gold-pack structure. Product and Domain must fill the exact low-volume rule, schema values, required fields, gold answers, and exclusions before G001. | ADV-MORNING-001-MET-D007; D012 | 2026-07-19 | Product / Domain | high |
| ADV-MORNING-001-MET-O003 | open question | narrowed | Material correction and its observation window are confirmed by D004. The exact acceptance and false-ready rubric remains open. | ADV-MORNING-001-MET-D004 | 2026-07-19 | Domain / Advisors | high |
| ADV-MORNING-001-MET-O004 | open question | delegated | D013 fixes the responsible roles. Product must record the actual names before G001. | ADV-MORNING-001-MET-D013 | 2026-07-19 | Product | high |
| ADV-MORNING-001-MET-O005 | open question | delegated | D006 fixes five full Advisor-days. D014 requires Product and Domain to fix the named Advisors and minimum synthetic-period volume after the baseline but before G001 and replay. | ADV-MORNING-001-MET-D006; D014 | 2026-07-19 | Product / Domain / Research | high |
| ADV-MORNING-001-MET-O006 | open question | superseded | Resolved by D011. | ADV-MORNING-001-MET-D011 | 2026-07-19 | Product / Domain / Operations | high |
| ADV-MORNING-001-MET-O007 | open question | superseded | Resolved by D008. | ADV-MORNING-001-MET-D008 | 2026-07-19 | Domain / Advisors | high |
| ADV-MORNING-001-MET-O008 | open question | superseded | Resolved by D010. | ADV-MORNING-001-MET-D010 | 2026-07-19 | Product / Domain / Engineering | high |

## Conversation decisions

- Confirmed transition or decision to evaluate: D005 confirms discovery to build, then build to synthetic replay. Capability mode and authority do not expand.
- Confirmed cohort and evidence window: D006 confirms named internal SE-DIFM Advisors across five normal full workdays, with bookkeeping work marked separately. Advisor names and the minimum synthetic-period volume remain open.
- Confirmed material correction and acceptance rubric: D004 defines material correction and its observation window. D008 defines package acceptance and false-ready.
- Confirmed critical guardrails: Project-level immediate-stop rules apply. D008 adds the job-specific acceptance and false-ready boundary.
- Confirmed thresholds and breach actions: Numeric success thresholds remain open until the rubric and baseline exist. Immediate-stop events already have a zero-tolerance boundary.
- Confirmed gate owner and review point: D013 fixes Product as gate owner and the role-specific veto owners. Actual names are a G001 entry requirement under O004.
- Confirmed KPI and learning hierarchy: D015 fixes four early success KPIs, later business KPIs, hard guardrails, and diagnostic learning metrics.
- Matters explicitly delegated to the agent: Finalize formulas, instrumentation, learning questions, gate structure, PDF capability proof, and vendor-neutral handoff. Product and Domain own the post-baseline numeric thresholds and minimum evidence volume. Responsible role owners must supply actual names and gold-case values before G001.

## Roadmap and decision context

- Current canonical lifecycle stage: discovery
- Requested lifecycle transition: discovery to build, followed by build to replay
- Current capability mode: mixed
- Requested capability-mode transition: none for the proposed build and synthetic-replay gates
- Evaluation mode: five-day current-workflow baseline plus synthetic replay; the two evidence modes and the two scorecards must not be blended
- Process scope and allowed effects: Advisor-day control layer plus the D007 one-month bookkeeping case. Synthetic evidence only for replay. Internal reversible preparation and the D011 human handoff record are allowed. The D010 PDF reader remains inactive until approved. Automatic client contact, sale, filing, payment, professional judgment, live automated external-system write, unsupported parsing, and automatic authority expansion are forbidden.
- Expected user value: The Advisor finds the correct next work faster and receives more trusted bookkeeping packages with less hands-on effort.
- Accountable decision owner: Product, with role-specific veto rights under D002
- Review date or cadence: Gate G001 after the case rubric, baseline design, instrumentation, owners, and minimum replay evidence volume are fixed. Gate G002 after the precommitted synthetic replay is complete.

## Research coverage

- Research mechanisms used: supplied sources; local repository and runtime inspection
- Research limitations or blockers: No external numeric benchmark is used as a Taxfix target. The direct Advisor baseline and instantiated gold fixtures are still missing. Numeric thresholds and replay volume must be fixed from the approved baseline and evaluation design before G001 and before results.

| Source ID | Publisher | URL | Access date | Supported claim or threshold | Evidence quality | Claim status |
| --- | --- | --- | --- | --- | --- | --- |
| MET-SRC-001 | Taxfix Product | [SOTA benchmark](SOTA/sota_benchmark.md) | 2026-07-19 | Market bar, first-wedge boundary, and five-day observation need | completed internal synthesis with stated limits | accepted with limits |
| MET-SRC-002 | Taxfix Product | [Agentic MVP](agentic_mvp.md) | 2026-07-19 | First-shot promise, allowed effects, scenarios, and blocked states | completed internal decision artifact | accepted as product direction |
| MET-SRC-003 | Taxfix Product | [Product Vision](product_vision.md) | 2026-07-19 | Metric hierarchy, cohort, roadmap gates, and business North Star | completed internal decision artifact | accepted as product direction |
| MET-SRC-004 | Taxfix Product | [Platform context](../tax-advisor-platform-context.md) | 2026-07-19 | Authority, evidence, data, lifecycle, and immediate-stop rules | primary internal contract | accepted |
| MET-SRC-005 | Taxfix Engineering | v2 runtime, migrations, and tests | 2026-07-19 | Current measurable events and instrumentation gaps | implementation evidence | accepted for current-state measurability |

## Measurement boundary

- Eligible population: German, low-document-volume, VAT-liable SE-DIFM freelancers and digital consultants for one calendar month, fixed before execution. The exact low-volume rule and fields remain open under O002.
- Exclusions: Non-German work, non-SE-DIFM work, client types outside the approved archetype, and real client data during replay. The base structured case and PDF capability proof stay separate until D010's capability gate passes. A capability gap discovered after entry stays in the denominator and must end in a valid blocked state.
- Cohort: Named internal SE-DIFM Taxfix Advisors across five full normal workdays, plus versioned eligible synthetic bookkeeping periods. Advisor names and the minimum replay-period count remain open.
- Observation window: Advisor-day baseline is five normal workdays. The bookkeeping correction window runs from the first system readiness proposal until the manual DATEV handoff is reconciled.
- Minimum evidence volume: D014 requires every mandatory scenario and a precommitted number of variations. Product and Domain fix the number after the baseline but before G001 and replay results.
- Acceptance rubric: Confirmed under D008. The package must have the correct client and month, account for every required input, reconcile supported evidence, link every material claim, expose conflicts and unknowns, block unsupported evidence, and support human accept or return. Any missing required input, material conflict, capability, check, or review makes a ready claim false-ready.
- Material correction definition: Confirmed under D004. A change is material when it changes readiness, a reconciliation outcome, a required missing-evidence request, the Advisor decision, or the manual DATEV handoff. Wording and layout-only edits are not material.
- Data-quality minimum: Every included case needs a versioned eligibility decision, rubric, input manifest, event set, and outcome label. Missing critical denominator or event data blocks the affected gate.

## Configurable transition gates

These two gates are confirmed under D005.

| Gate ID | Lifecycle transition | Capability transition | User-value gate | Outcome and quality gate | Safety, authority, trust, and control gate | Adoption and operations gate | Evidence volume/window | Decision owner |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-MET-G001 | discovery to build | mixed to mixed; no authority expansion | Both scorecards have fixed jobs, denominators, formulas, sources, owners, and baseline plans | Case rubric, gold fixtures, material-correction rule, false-ready rule, and readiness checks are executable | Immediate-stop events, permissions, human gates, rollback, and denied-action evidence are testable | Five-day baseline plan, instrumentation contract, QA owner, support route, and current-workflow comparator exist | Exact rubric and event contract plus approved five-day baseline plan; numeric volume open | Product; Domain, Advisors, and control owners hold area vetoes |
| ADV-MORNING-001-MET-G002 | build to replay | mixed to mixed; synthetic L2 preparation only | Early KPIs M001, M008, M015, and M016 meet thresholds fixed before replay | Bookkeeping outcome and Advisor-day quality thresholds pass; no critical data-quality gap | All hard guardrails pass; pause, cancel, correct, return, retry, resume, and take-over work | Replay is repeatable; support and recovery work; effort and cost are observable | Minimum eligible synthetic periods and replay window delegated under O005 | Product; Domain, Advisors, and control owners hold area vetoes |

## Decision rules

| Gate ID | Go when | Hold when | Kill when | Consequence: continue / narrow / rollback / park / stop | Remediation and next review |
| --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-MET-G001 | O002 and O004–O005 are closed; both scorecards and the D010 PDF capability proof are measurable; owners, data quality, baseline, rubric, fixtures, and breach actions are fixed before results | Any denominator, rubric, owner, event, baseline plan, capability proof, or critical guardrail is missing | The job cannot be made bounded, reviewable, or safe inside the approved authority and data boundary | go: continue to build; hold: narrow; kill: park or stop | Close the missing contract item, rerun measurability review, and record the human decision |
| ADV-MORNING-001-MET-G002 | M001, M008, M015, and M016 each pass their pre-set threshold; all hard guardrails pass; evidence is complete | Any KPI misses, a guardrail breaches, evidence volume is weak, data is incomplete, or recovery/support is not ready | A stop-level failure shows the proposed job or mode is not worth continuing and cannot be removed by narrowing | go: continue to the next separately approved mode; hold: narrow or rollback; kill: park or stop | Use the learning metrics to find the cause, fix or narrow it, rerun replay, and hold a new human gate |

## KPI hierarchy and success rule

Thirty formulas do not mean thirty KPIs. KPIs decide whether the product works. Guardrails can stop
it. Learning metrics explain why a KPI moved and what to fix.

### Early product KPIs

These four KPIs decide G002. Each must meet the numeric threshold fixed after the baseline and
before replay. Strong performance on one KPI cannot compensate for a miss on another.

| KPI ID | Success question | Measurement |
| --- | --- | --- |
| ADV-MORNING-001-MET-M001 | Does the product finish eligible bookkeeping periods correctly? | Eligible periods accepted within the target clock without a material correction / all eligible periods entering evaluation |
| ADV-MORNING-001-MET-M008 | Does the product reduce real Advisor effort per accepted period? | Active Advisor minutes for scope, review, correction, and handoff / accepted periods |
| ADV-MORNING-001-MET-M015 | Does the workbench help the Advisor find the correct next action faster? | Time from opening or returning until the correct material action is selected |
| ADV-MORNING-001-MET-M016 | Does the workbench show all material work? | Material work items shown / all material work items in the reconciled daily answer set |

### Later operating and business KPIs

These become success KPIs only in an approved live operating mode. They do not decide synthetic
replay.

| KPI ID | Success question | Measurement |
| --- | --- | --- |
| ADV-MORNING-001-MET-M022 | Does the product create Advisor capacity? | Accepted eligible periods / active Advisor FTE in the same period |
| ADV-MORNING-001-MET-M023 | Does that capacity create durable business value? | Net revenue attributable to the approved cohort / active Advisor FTE |

### Hard guardrails

These are not averaged into a score. Any stop-level breach blocks the gate.

| Metric ID | Guardrail | Gate treatment |
| --- | --- | --- |
| ADV-MORNING-001-MET-M003 | False-ready | Target zero; any event stops the affected mode |
| ADV-MORNING-001-MET-M004 | Material corrections | Must remain within the pre-set threshold; investigate every material correction |
| ADV-MORNING-001-MET-M005 | Material evidence coverage | Every material claim must link to exact evidence |
| ADV-MORNING-001-MET-M012 | Retry and resume integrity | No lost or duplicate action; any duplicate external effect stops the path |
| ADV-MORNING-001-MET-M013 | Authority, scope, privacy, and unsupported-content stop events | Target zero; any event stops the affected mode |
| ADV-MORNING-001-MET-M016 | Missed critical Advisor-day work | Any missed stop-level item blocks the gate even if the overall KPI threshold passes |
| ADV-MORNING-001-MET-M021 | Stale, duplicate, or misclassified work | A stop-level wrong-scope or stale item blocks the affected gate |
| ADV-MORNING-001-MET-M029–M030 | PDF safety and material extraction error | Reader remains inactive until its separate gate passes; unsafe or false-ready behavior targets zero |

### Learning metrics and learning loops

Learning metrics diagnose the KPIs. They do not declare success by themselves.

| If this happens | Read these learning metrics | What we learn or change |
| --- | --- | --- |
| Trusted completion M001 is weak | M002, M004, M006, M007, M009, M011 | Separate wrong outcomes, corrections, missed issues, review returns, slow flow, and blockers; fix the case contract, capability, or workflow |
| Advisor effort M008 does not improve | M007, M009, M010, M011, M014 | Find whether time moved into review, rework, waiting, support, or expensive tooling |
| Next-action time M015 does not improve | M017, M018, M019, M021 | Find noise, source hunting, context switching, bad ranking, stale state, or wrong ownership |
| Material coverage M016 is weak | M017, M020, M021 | Find missing sources, parallel-system work, stale items, duplicates, and classification gaps |
| Advisors do not trust or adopt the product | M007, M019, M020 plus return, takeover, and correction reasons | Distinguish weak output from poor explanation, missing control, training problems, or unsupported work |
| PDF coverage is weak or unsafe | M027–M030 | Identify field, document-type, localization, encryption, scan, corruption, or malicious-input failures before activation |
| Unit economics are weak | M014, M024 | Separate model/tool cost, support cost, and hidden rework before making a scale claim |
| Opportunity signals are noisy | M025–M026 | Learn usefulness, dismissal reasons, conversation progress, revenue, and trust harm without changing bookkeeping readiness |

### Gate success formula

G002 passes only when:

`M001 passes AND M008 passes AND M015 passes AND M016 passes AND every hard guardrail passes AND required evidence is complete.`

No weighted average is allowed. Revenue and opportunity results do not participate in G002.

## Metric catalog

Numeric baselines and thresholds are intentionally `Open`. They will be fixed after the exact case, owners, and evidence volume are closed and before replay results are used.

| Metric ID | Role and metric | Formula and denominator | Cohort / window / unit | Baseline | Target or gate threshold | Guardrail threshold | Source | Owner | Breach action and decision informed |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-MET-M001 | Bookkeeping primary outcome: trusted completion rate | Eligible periods accepted within the target clock with no material correction during the observation window / all eligible periods entering evaluation | Eligible bookkeeping periods; percent | Open | Open | M003 and M013 can block regardless of M001 | New eligibility, review, correction, and handoff events | Product / Domain | Hold or narrow G002; proves whether the deep job works |
| ADV-MORNING-001-MET-M002 | Bookkeeping diagnostic: safe disposition rate | Eligible periods correctly accepted, returned, or validly blocked against the gold rubric / all eligible periods entering evaluation | Eligible bookkeeping periods; percent | Open | Open | Cannot replace M001; blocking everything is not success | Gold evaluation verdict plus run and review state | Domain / Evaluation | Inspect false accepts, false blocks, and wrong returns |
| ADV-MORNING-001-MET-M003 | Bookkeeping hard guardrail: false-ready rate | Periods marked ready although the rubric requires a material correction, missing input, conflict, unsupported capability, or required review / all periods marked ready | Eligible bookkeeping periods; percent | Open | 0 | Any event is an immediate stop for the affected mode | New readiness-check and evaluation-verdict events | Domain / Execution Safety | Stop, contain, inspect all affected results, and hold the gate |
| ADV-MORNING-001-MET-M004 | Bookkeeping quality: material-correction rate | Accepted packages with at least one material correction during the observation window / accepted packages | Accepted packages; percent | Open | Open | Open after rubric | New structured material-correction event | Domain / Advisors | Hold or narrow; learn which claims and steps fail |
| ADV-MORNING-001-MET-M005 | Bookkeeping trust: material evidence coverage | Material claims linked to an exact immutable source version / all material claims | Review packages; percent | Open | Open | Any unlinked material claim blocks acceptance | Claim-level evidence links plus rubric | Domain / Engineering | Block package; repair evidence or claim |
| ADV-MORNING-001-MET-M006 | Bookkeeping quality: missed-material-issue rate | Gold-set material issues not surfaced by the system / all gold-set material issues | Gold synthetic periods; percent | Open | Open | False-ready impact triggers M003 | Gold fixture verdicts | Domain / Evaluation | Hold; add fixture, check, capability, or scope exclusion |
| ADV-MORNING-001-MET-M007 | Bookkeeping review: first-pass acceptance | Packages accepted at first Advisor review / packages reviewed | Eligible packages; percent | Open | Open | M003 and M004 remain separate | Handover package versions and review decisions | Advisors / Product | Diagnose weak preparation versus rubric or training issue |
| ADV-MORNING-001-MET-M008 | Bookkeeping efficiency: Advisor hands-on minutes per accepted period | Sum of active Advisor work minutes for scope, review, correction, and handoff / accepted periods | Advisor and eligible period; minutes, median and P90 | Open | Open after baseline | Quality guardrails cannot be traded for speed | New role-tagged activity events | Product / Research | Hold if effort shifts into hidden review or rework |
| ADV-MORNING-001-MET-M009 | Bookkeeping flow: time to trusted review | Time from eligible-period start to first complete `needs_advisor_review`; report active system time and waiting time separately | Eligible periods; hours/days, median and P90 | Open | Open after baseline | Missing or unsupported work must not be hidden to improve time | Eligibility, run, blocker, and review timestamps | Product / Operations | Diagnose wait, capability, queue, and processing causes |
| ADV-MORNING-001-MET-M010 | Bookkeeping burden: rework minutes per accepted period | Advisor and Expert minutes after a return or material correction / accepted periods | Accepted periods; minutes | Open | Open | Open after rubric | Activity plus structured correction events | Domain / Product | Hold or narrow if saved preparation creates more rework |
| ADV-MORNING-001-MET-M011 | Bookkeeping operations: blocker resolution time | Time from typed blocker opened to cleared, grouped by blocker type and owner | Eligible periods; hours/days, median and P90 | Open | Open | A blocker without owner, reason, source, and next action is invalid | New unified blocker events | Operations / Work Management | Route recurring gaps to input, capability, workflow, or support owner |
| ADV-MORNING-001-MET-M012 | Bookkeeping recovery: correct retry and resume rate | Recovery attempts that resume from durable state without lost or duplicate action / recovery attempts | Replay recovery scenarios; percent | Open | Open | Duplicate external or irreversible effect: 0 | Run events plus new recovery outcome and action ledger | Engineering / Execution Safety | Stop affected path; reconcile and repair before rerun |
| ADV-MORNING-001-MET-M013 | Shared hard guardrail: immediate-stop event count | Count of cross-tenant access, unapproved egress, candidate-tool use, fake parsing, unlinked material claim, review bypass, unauthorized external effect, or opportunity changing readiness | All evaluation work; count | 0 expected by contract | 0 | Any event stops the affected mode | New durable safety and authority events | Responsible control owner | Stop, contain, investigate, remediate, and require fresh approval |
| ADV-MORNING-001-MET-M014 | Bookkeeping economics: cost per accepted package | Model, tool, infrastructure, support, and attributable rework cost / accepted packages | Accepted periods; EUR | Open | Open | Quality and trust gates override cost | Cost events plus activity and review data | Product / Finance / Engineering | Diagnose model, tool, support, and rework drivers |
| ADV-MORNING-001-MET-M015 | Advisor-day primary outcome: time to correct next material action | Time from opening or returning to the workbench until the Advisor selects the gold- or Advisor-confirmed next material action | Named Advisors over five normal workdays; minutes, median and P90 | Five-day baseline required | Open after baseline | A faster wrong action is failure, not success | New advisor-day and intervention events plus baseline observation | Product / Advisors / Research | Hold or repair information order and ranking |
| ADV-MORNING-001-MET-M016 | Advisor-day coverage: material-work recall | Material work items shown in the workbench / all material work items in the reconciled daily gold set | Advisor-days; percent | Open | Open | A missed stop-level item blocks the affected gate | Daily source reconciliation and intervention snapshot | Domain / Operations | Hold; repair source coverage, joining, or rules |
| ADV-MORNING-001-MET-M017 | Advisor-day noise: false-intervention rate | Shown interventions judged non-material or needing no action / all shown interventions | Advisor-days; percent | Open | Open | Open | Intervention decision and reason | Product / Advisors | Tune ranking or suppress weak signals; inspect segment effects |
| ADV-MORNING-001-MET-M018 | Advisor-day burden: source-hunting and context switching | Active minutes spent finding source context plus distinct systems opened per resolved material intervention | Five-day baseline and matched evaluation days; minutes and system count | Five-day baseline required | Open after baseline | Source coverage and accuracy cannot be traded for fewer systems | Activity observation and new workbench events | Research / Product | Hold if work merely moves rather than disappears |
| ADV-MORNING-001-MET-M019 | Advisor-day control: priority override rate by reason | Ranked interventions reordered, deferred, dismissed, or corrected by the Advisor / ranked interventions reviewed | Advisor-days; percent plus reasons | Open | Learning metric; no single success target yet | Unexplained or impossible-to-correct priority is a control failure | New priority decision event | Product / Advisors | Learn ranking failures and preserve manual control |
| ADV-MORNING-001-MET-M020 | Advisor-day adoption: eligible workbench coverage | Eligible material work handled with the workbench as the control layer / all eligible material work during the approved observation window | Named Advisors and days; percent | Open | Open after baseline and replay | Parallel-system use must remain visible | Source reconciliation plus Advisor confirmation | Product / Operations | Diagnose missing capability, trust, training, or workflow fit |
| ADV-MORNING-001-MET-M021 | Advisor-day trust: stale, duplicate, or misclassified item rate | Presented items with stale source, duplicate identity, wrong owner/state, or wrong classification / presented items | Advisor-days; percent | Open | Open | A stop-level wrong-scope item triggers M013 | Projection integrity, source timestamps, and Advisor correction | Engineering / Operations | Hold and repair state joining or source freshness |
| ADV-MORNING-001-MET-M022 | Operating leverage: accepted periods per active Advisor | Accepted eligible periods / active Advisor FTE in the same period | Approved cohort; periods per FTE-week or FTE-month | Open | Open after real baseline | M003 and M013 override throughput | Workstream, review, eligibility, and workforce data | Product / Operations | Learn whether capacity improves without hidden rework |
| ADV-MORNING-001-MET-M023 | Business North Star: Net Revenue per active Tax Advisor | Net revenue attributable to the approved cohort / active Advisor FTE in the same window | Approved business cohort; EUR per FTE-period | Open | Later gate only | Quality, trust, and authority gates override revenue | Approved finance attribution plus workforce data | Product / Finance | Inform later operating and market decisions; not replay success |
| ADV-MORNING-001-MET-M024 | Business diagnostic: contribution per accepted period | Attributable revenue minus variable model, tool, support, and rework cost / accepted periods | Approved cohort; EUR | Open | Later gate only | Quality and trust override margin | Finance, cost, activity, and review data | Product / Finance | Test whether scale creates real value rather than cost shifting |
| ADV-MORNING-001-MET-M025 | Opportunity learning: Advisor-accepted useful-signal rate | Evidence-complete opportunities judged useful and real by the Advisor / opportunities surfaced | Eligible clients with supported preparation; percent | Open | Shadow-only threshold open | Opportunity may never change readiness or contact the client automatically | Expanded opportunity and Advisor decision events | Product / Advisors | Keep shadow, narrow, or stop noisy signals |
| ADV-MORNING-001-MET-M026 | Opportunity funnel: accepted signal to conversation and revenue | Track surfaced → Advisor accepted → client conversation → converted revenue with stage denominators | Eligible clients; percent and EUR | Open | Later commercial threshold only | Client complaint or trust harm can block promotion | Expanded opportunity stages, timestamps, reasons, and finance attribution | Product / GTM / Advisors | Inform later GTM; never count as bookkeeping success |
| ADV-MORNING-001-MET-M027 | PDF capability: material field accuracy | Correctly extracted material fields / all material fields in the PDF gold set, reported by document and field type | Versioned PDF fixtures; percent | Open | Open before capability promotion | Any error that causes false-ready triggers M003 | PDF gold set plus exact reader version/hash | Domain / Engineering | Keep reader inactive, repair, and rerun the format suite |
| ADV-MORNING-001-MET-M028 | PDF capability: evidence localization coverage | Material extracted fields and claims linked to the exact document version and page or region / all material extracted fields and claims | Versioned PDF fixtures; percent | Open | Open before capability promotion | An unlinked material claim blocks acceptance under M005 | Reader output and claim-level evidence links | Domain / Engineering | Block promotion or package acceptance |
| ADV-MORNING-001-MET-M029 | PDF capability: safe disposition rate | PDF fixtures correctly read or correctly blocked as scanned-only, encrypted, corrupt, unsupported, or malicious / all PDF fixtures | Versioned normal and adversarial PDFs; percent | Open | Open before capability promotion | Fake reading, untrusted-instruction execution, or unsupported content presented as read: 0 | Capability evaluation verdict and safety events | Execution Safety / Engineering | Keep inactive, contain failure, and add regression proof |
| ADV-MORNING-001-MET-M030 | PDF capability: material extraction error rate | Wrong or missing material extracted values / all material expected values | Versioned PDF fixtures; percent | Open | Open before capability promotion | Any error reaching ready triggers M003 | PDF gold set and review verdict | Domain / Evaluation | Keep reader out of happy path and inspect failure class |

## Critical guardrails and recovery

| Guardrail ID | Breach definition | Detection event | Immediate action | Recovery owner | Proof before restart |
| --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-MET-M003 | A period is marked ready although the rubric requires a material correction, blocker, missing input, unsupported capability, or human review | `readiness_evaluated` plus Domain gold verdict | Stop the affected evaluation path and quarantine its results | Domain / Execution Safety | Correct rubric result, affected-result review, regression fixture, and fresh approval |
| ADV-MORNING-001-MET-M005 | A material claim lacks an exact immutable evidence link | `readiness_evaluated` | Block the package from review acceptance | Domain / Engineering | Claim removed or source link repaired and rechecked |
| ADV-MORNING-001-MET-M012 | Retry or resume loses state or duplicates an action | `recovery_completed` and action ledger comparison | Stop retry for the affected effect and reconcile state | Engineering / Execution Safety | Reconciliation record, idempotency proof, and passing recovery fixture |
| ADV-MORNING-001-MET-M013 | Any project-defined immediate-stop event occurs | `authority_denied`, `scope_breach_detected`, `unsupported_content_blocked`, or equivalent durable event | Stop, contain, preserve evidence, and route the incident | Responsible control owner | Root cause, affected-scope review, remediation proof, and named human approval |

## Instrumentation

| Event | Trigger | Required properties | Source of truth | Data-quality check | QA owner |
| --- | --- | --- | --- | --- | --- |
| `eligibility_assessed` | Before a case enters either scorecard | tenant, client, workstream, period, cohort rule/version, decision, exclusion reason, fixture ID | New evaluation registry linked to Workstream | One decision before execution; no retrospective exclusion | Product / Domain |
| `advisor_day_observation_started` / `ended` | Start and end of each approved baseline or evaluation day | Advisor role, date, observation mode, included work sources, interruptions, observer/method | Evaluation registry | Five normal days are complete and comparable | Research / Product |
| `intervention_presented` | Workbench shows an item as needing attention | item ID, source, source freshness, owner, state, priority factors, reason, rank | Operations projection plus evaluation event | Stable identity; no duplicate; source timestamp present | Operations / Engineering |
| `advisor_next_action_selected` | Advisor selects, overrides, defers, dismisses, or corrects an intervention | item ID, action, reason, correct-next-action verdict, elapsed orientation time | Evaluation event plus work transition | Every observed decision has a reason and outcome | Product / Advisors |
| `advisor_activity_started` / `paused` / `ended` | Advisor begins or stops active scope, review, correction, or handoff work | Advisor role, workstream, activity type, timestamp, pause reason | New activity event store | No overlapping active sessions; wait time excluded | Research / Engineering |
| `input_manifest_bound` | Eligible period begins execution | period, required inputs, received inputs, source versions, reader versions, rubric version | Workstream/Evidence plus evaluation registry | Manifest fixed before result; change creates new version | Domain / Evidence |
| `readiness_evaluated` | System proposes ready, blocked, returned, or failed | rubric version, required checks, check results, blocker taxonomy, material claims, disposition | New structured result/check record | No use of legacy `filing_ready` as bookkeeping readiness | Domain / Engineering |
| `review_decision_recorded` | Expert or Advisor accepts or returns a package | package version, reviewer role, rubric version, decision, reason, timestamp | Existing handover record, extended with rubric fields | Named reviewer and complete decision fields | Work Management / Domain |
| `material_correction_recorded` | A reviewed or accepted package needs correction | package/result version, material flag, category, changed field or claim, cause, detected time, detector role | New structured correction record | Materiality uses the current rubric; no revision-count proxy | Domain / Advisors |
| `blocker_opened` / `cleared` | Work cannot proceed or a blocker is resolved | blocker type, reason, source, owner, next action, opened/cleared time, resolution | New unified blocker record | Every blocker has owner, source, and next action | Work Management / Operations |
| `recovery_attempted` / `completed` | Retry, resume, reclaim, or reconciliation starts and ends | run, attempt, cause, prior state, actions before/after, result, duplicate/lost-action verdict | Automation run events plus action ledger | Event exists for every recovery; action comparison complete | Engineering / Execution Safety |
| `manual_handoff_started` / `result_recorded` / `reconciled` | Advisor or operator performs the approved DATEV handoff | handoff type, package version, operator, external owner, request ID, status, receipt/source, unknown outcome, correction | New manual/external handoff aggregate | No blind retry; unknown result must reconcile before closure | Operations / Advisors |
| `authority_or_scope_denied` | An action violates permission, effect, tenant, provider, capability, or review rules | actor, action, effect class, scope, capability/tool/version/hash, denial reason, approval reference | Durable Governance/Automation safety ledger | Persist even when the main result transaction fails | Execution Safety / Security |
| `opportunity_decision_recorded` | Advisor saves, dismisses, accepts, or drafts a conversation | observed need, evidence links, impact, service, confidence, unknowns, decision, reason, workstream/period/run | Expanded Advisory aggregate | Evidence complete; opportunity does not affect readiness | Product / Advisors |
| `cost_recorded` | Model, tool, infrastructure, support, or attributable rework cost occurs | cost class, amount, currency, run/workstream, model/tool/version, unit | Cost ledger linked to run and workstream | No missing cost class for included cases | Finance / Engineering |
| `document_capability_evaluated` | A PDF reader or other document capability processes or blocks a fixture | document version/hash, media and PDF subtype, reader version/hash, supported decision, extracted fields, page/region links, errors, latency, cost, safety verdict | Capability evaluation registry plus immutable evidence | Exact approved reader identity; gold comparison complete; adversarial fixtures included | Domain / Engineering / Execution Safety |

## Evaluation and learning plan

- Evaluation mode and why it is valid: Observe the current Advisor workflow for five normal workdays to establish the Advisor-day baseline. Use synthetic replay for the first product evaluation. This can test bounded behavior, failure paths, review, correction, and recovery without sending real client data to a model.
- What this mode cannot prove: Real-client data handling, real adoption, live handling-time improvement, live DATEV integration, buyer demand, business North Star movement, or controlled-live safety.
- Biggest assumption: The workbench and deep preparation reduce coordination and preparation work without moving equal or greater effort into review, correction, support, or parallel-system maintenance. The PDF reader can add real evidence coverage without becoming the source of hidden material errors.
- Open learning questions:
  1. Does the Advisor find the correct next material action faster?
  2. Does the workbench catch material work without creating noisy interventions?
  3. Does an eligible bookkeeping period reach accepted review without false-ready or material correction?
  4. Where does time move: preparation, waiting, review, correction, handoff, or support?
  5. Which eligibility, input, capability, and blocker reasons prevent trusted completion?
  6. Do retry, resume, handoff, and correction preserve state without duplicates or lost work?
  7. Do Advisors rely appropriately, or do they rubber-stamp, over-check, override, or maintain a parallel system?
  8. Which client and case segments perform differently, and why?
  9. Does the PDF reader add real supported coverage without creating material extraction errors, weak evidence links, unsafe instruction handling, or false-ready results?
- Pilot or evaluation cohort: Named internal Taxfix Advisors and versioned synthetic cases. D013–D014 require the names and exact volume before G001.
- Allowed effects: Observation of the approved current workflow; synthetic Taxfix-owned state changes; no real client-data model use; no automatic external effect.
- Support owner and incident route: Operations owns support and recovery under D013. The actual named owner and route are required before G001.
- Rollback or remediation plan: Stop the affected evaluation, preserve evidence, return to the current manual workflow, narrow the supported case or capability, fix instrumentation or behavior, and require a fresh human gate.
- Review point: First after the rubric, baseline design, owners, and instrumentation are fixed. Second after the precommitted replay volume is complete.
- Gate IDs: ADV-MORNING-001-MET-G001 and ADV-MORNING-001-MET-G002, confirmed under D005
- Diagnostics excluded from the success scorecard: Raw run count, messages, tool calls, tokens, logins, clicks, and model benchmark scores. These may explain cost or behavior but do not prove an accepted user outcome.

## Decision

- Proposed gate decision: hold
- Proposed consequence: narrow
- Evidence and metric IDs: ADV-MORNING-001-MET-E001–E007; ADV-MORNING-001-MET-D001–D015; M001–M030
- Blocking guardrail or open-question IDs: ADV-MORNING-001-MET-O002 and O004–O005
- Human rationale required: yes
- Automatic lifecycle or capability expansion: forbidden

## Decision and handoff

- Confirmed decisions: D001–D015
- Assumptions and hypotheses: H002. H001 and H003 are superseded by D005 and D010.
- Blockers: Product and Domain must instantiate the structured schema and gold answers, actual owner names, named baseline Advisors, numeric thresholds, and minimum replay volume before G001. These are delegated execution inputs under O002 and O004–O005, not unresolved design choices.
- Inputs the next conversation should read: This draft, [Agentic MVP](agentic_mvp.md), [Product Vision](product_vision.md), [platform context](../tax-advisor-platform-context.md), and any available exact bookkeeping case, baseline, or owner evidence.
- Output links: [this artifact](metrics_learning.md) | [transcript](metrics_agent_transcript.md) | [thought process](metrics_thought_process.md) | canonical brief: Open
- Recommended next conversation: Collect the five-day baseline, instantiate the gold pack, name the owners, and precommit numeric thresholds and replay volume before the G001 decision.
