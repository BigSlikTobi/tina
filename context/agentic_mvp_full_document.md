# 📄 Agentic MVP (full document)

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
- Updated date: 2026-07-21

## The MVP in one sentence

Build the daily home base for a German Tax Advisor.
It covers the full book of work at the control layer. It goes deeply agentic for one bookkeeping period. It stops safely when the evidence, capability, or authority is missing.

## What is already defined and what remains open

### Already decided

| Area | What is already defined | Source |
|---|---|---|
| Product shape | Full-day Advisor workbench plus one deep bookkeeping-period job | D017–D020 |
| User and support | Internal Taxfix Advisor is primary. Tax Expert supports preparation. | D020 |
| MVP sources | DATEV, task lists, and Taxfix systems are in. Email, general calendar, and client chat are out. | D018–D019 |
| Product package | The active Kano Matrix defines must-haves, accelerators, and Opportunity Radar | D002–D003, D010, D012 |
| Agent boundary | Bounded L2 preparation. Humans keep judgment, acceptance, client contact, and consequential action. | D006, D008–D009 |
| Evaluation start | Synthetic replay comes first | D008 |
| Acceptance meaning | Correct client and month, required input accounted for, supported evidence reconciled, material claims linked, conflicts visible, human accept or return | ADV-MORNING-001-MET-D008 |
| False-ready rule | A ready result fails if a required input, conflict, capability, check, or review is missing | ADV-MORNING-001-MET-D008 |
| Material correction | A change to readiness, reconciliation, missing-evidence need, Advisor decision, or handoff | ADV-MORNING-001-MET-D004 |
| Test design | Gold pack, required scenarios, separate scorecards, four early KPIs, and hard guardrails | ADV-MORNING-001-MET-D001, D012, D014–D015 |
| Product gates | G001 discovery to build. G002 build to synthetic replay. | ADV-MORNING-001-MET-G001–G002 |
| Commercial gates | Seven stages from internal discovery to open-market expansion | ADV-MORNING-001-GTM-D003, D005–D006 |
| Price and claims | No customer price yet. Claims widen only after the relevant evidence gate passes. | ADV-MORNING-001-GTM-D003, D006 |

### Open before G001 can approve build

| Open ID | What still needs definition | Why it matters |
|---|---|---|
| O020 | Exact DATEV, task-list, and Taxfix-system data, source ownership, freshness, sync, and allowed effects | Prevent a stale or duplicate workbench from saying the day is clear |
| O021 | Exact case schema, low-volume rule, required fields, exclusions, gold matches, unresolved items, and gold readiness result | Make the bookkeeping result testable |
| O022 | Required evidence types and subtypes, validated fields, source links, safe handling, and blocked outcomes | Stop unsafe reading, fake support, and hidden instructions |
| O023 | Exact downstream handoff action, destination, operator, receipt, correction, and unknown-result rule | Make the accepted end state and recovery real |
| O024 | Actual people and access for observation, gold approval, vetoes, and incidents | Run the existing gate with accountable humans |

### Open after the baseline and before replay or visible use

| Open ID | What still needs definition | Due point |
|---|---|---|
| O025 | Reviewer absence, overload, expiry, reassignment, reason, escalation, and take-over rules | Before replay |
| O026 | Numeric thresholds and the minimum precommitted replay volume | After baseline, before results |
| O027 | Post-handoff window for delayed material correction or harm | Before G002 |
| O028 | Allowed-service catalog and Opportunity Radar relevance, usefulness, and evidence threshold | Before Advisor-visible Radar proof |

### Open before real client data

O019 owns the provider and data contract. It must name the provider path, region, subprocessors, support access, transfer route, retention, deletion, permissions, tenant controls, incident route, and responsible Security and Privacy people.

## Kano Matrix for the MVP

| Kano class | Product feature | First-shot promise | MVP proof |
|---|---|---|---|
| Must-have | Daily Advisor workbench | All important clients, deadlines, tasks, waits, blockers, reviews, owners, sources, and next actions stay visible | A representative book shows no hidden in-scope work |
| Must-have | Source-system continuity | DATEV, task-list, and Taxfix-system dates and work states stay visible in the workbench | Source, owner, state, blocker, freshness, and next action are reconciled for every in-scope item |
| Must-have | One deep bookkeeping mission | The platform prepares one supported bookkeeping period from start to review | Happy and exception paths both complete the full agent loop |
| Must-have | Trust and human control | Sources, checks, limits, history, blockers, pause, cancel, return, and take-over stay visible | No unsupported or conflicting fixture reaches ready |
| Must-have | Real agents, one front door | The Tax Advisor Agent leads. Specialist work is visible in one Plan and one Trace | Every agent has a scope, capability limit, stop rule, result, and human gate |
| Performance accelerator | Taxfix client flow | More eligible Taxfix clients arrive mandate-ready in the Advisor workbench | Measure activated mandates, onboarding effort, and time to first work |
| Performance accelerator | Agentic bookkeeping preparation | More supported preparation is completed by the platform | Measure accepted periods, hands-on minutes, corrections, and supported coverage |
| Delighter | Opportunity Radar | The platform spots one real client need and shows the proof | Show one overdue-receivables signal with evidence, impact, confidence, unknowns, and Advisor choice |

### Later accelerators, not MVP scope

| Feature | Why it is later |
|---|---|
| Client chat and AI-assisted missing-evidence loop | First planned follow-up. Needs a clear client channel, message state, human Send, reply linking, and recovery. |
| DATEV write automation | Visibility is in the MVP. Writing or posting back needs a separate effect, reconciliation, and recovery decision. |
| OpsMaestro | Needs broader practice data and proven workflow signals. |
| ClientFit Scout | First cohort is already selected. Scoring and pricing add scope before the first job is proven. |
| Evidence types outside the first job contract | Other types come later after job-specific validation. |

## Agent team

| Agent | MVP job | Hard limit |
|---|---|---|
| Tax Advisor Agent | Owns the mission, plan, routing, blocker explanation, and review package | No professional judgment or client contact |
| DataJanitor Pro | Inventories job-required data, normalizes it, reconciles the period, and exposes gaps | No claim beyond validated evidence types |
| FristenGuard | Watches approved DATEV and Taxfix bookkeeping dates, waits, missing input, stale work, and resume conditions | No email, general calendar, or tax-office coverage |
| AdvisorLens | Creates one evidence-backed opportunity card | Never changes readiness. Never contacts or sells to the client. |
| Document Review Agent | Checks completeness for supported evidence | Unsupported input still stops |

The UI shows the job first. Example: `Bookkeeping preparation | DataJanitor Pro`.
Named agents are greenfield product roles. Their capability must be proven against the job.

## Opportunity Radar contract

- Trigger: After supported bookkeeping preparation and checks.
- Scope: Same tenant, client, workstream, and period only.
- First signal: Overdue receivables and possible cash-flow pressure.
- Output: At most one strong opportunity.
- Required fields: Observed need, source evidence, client impact, suggested allowed service, confidence, unknowns, and Advisor decision.
- Advisor choices: Save or dismiss with reason.
- Hard boundary: The opportunity never changes bookkeeping readiness.
- Forbidden action: No automatic outreach, sale, price, promise, or conversion.

## Light Codex UI direction

| Area | What it must do |
|---|---|
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

## Agent loop

| Step | Goal | Observe | Decide and act | Check | Adapt or stop | Human gate | Evidence created |
|---|---|---|---|---|---|---|---|
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
|---|---|---|---|---|---|---|
| Scope and plan | reversible | tenant + workstream + period + plan version | Retry only after confirmed internal failure | Read durable product state first | Cancel or supersede with reason | Engineering |
| Evidence read | read-only | source hash + reader hash + run task | Retry the exact approved read only | Compare action, result, and source hash | Block on change or unsupported input | Engineering |
| Claims and package | reversible | run + result type + evidence version | Versioned upsert only | Read durable result and event history | Supersede, never erase reviewed history | Engineering / Expert |
| Advisor review | reversible before downstream effect | package version + reviewer + command | Never replay blindly | Read current review event | Return or reopen with reason | Advisor |
| Human-operated downstream handoff | potentially irreversible outside Taxfix | package + handoff type + operator | No system retry | Check the destination result and Taxfix record | Named manual correction | Advisor / Operations |

An external action with an unknown result is never retried blindly.

## Required scenarios

| Scenario | Fixture | Expected state | Owner |
|---|---|---|---|
| Happy path | Supported synthetic period | `needs_advisor_review`, then accepted or returned | Product / Domain |
| Missing input | Required bank or invoice evidence absent | `missing_input` | Domain |
| Unsupported capability | A required evidence type cannot be safely read | `needs_capability` | Engineering |
| Conflicting evidence | Bank and invoice data disagree | `conflicting_evidence` | Domain |
| Failed check | Coverage or evidence-link check fails | `failed_check` | Engineering / Domain |
| Human rejection | Expert or Advisor returns package | returned or reopened | Advisor / Expert |
| Cancellation | Human stops an active run | `cancelled` | Engineering |
| Retry or resume | Internal failure or new evidence | resumed once | Engineering |
| Unknown external outcome | The downstream handoff has no result | `unknown_external_outcome` | Advisor / Operations |
| Unauthorized action | Agent attempts Send, filing, payment, sale, or unapproved tool | denied and stopped | Execution Safety |
| Cross-tenant access | Evidence points to another tenant | denied and stopped | Security / Engineering |
| Untrusted instruction | Evidence asks the agent to ignore rules | ignored as evidence content | Execution Safety |

## Acceptance and gate recommendation

- Acceptance criteria: One eligible synthetic period reaches Advisor accept or return, or a valid blocked state; every material claim links to an exact source version; unsupported input and conflicting evidence never reach ready; the happy path and at least one exception path prove observe, decide, act, check, and adapt; retry and resume do not duplicate actions; no client message is sent or simulated inside the MVP; Opportunity Radar never changes readiness; the Advisor can pause, cancel, correct, return, take over, and accept.
- Recommended gate decision: hold
- Recommended consequence: narrow
- Blockers: O020–O024 block G001. O025–O028 are due before replay or visible use. O019 blocks controlled live use. O029 blocks wider rollout or scale if the burden remains unmeasured.
- Recommended next conversation: When definition work resumes, take O020 first. It is the strongest defense against the duplicate-state kill shot. Do not reopen the user, scope, Kano Matrix, or gate structure.
