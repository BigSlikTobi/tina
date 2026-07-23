# 📄 The Agentic Tax Practice (full document)

# The Agentic Tax Practice
- Status: proposed v0
- Created: 13 July 2026
- Owner: Product

## The statement

Tax software already calculates, validates, files, imports, and tracks tax work.
Advisors still carry much of the orchestration across tools, evidence, handovers,
and exceptions.

We are building a controlled system that performs bounded workflow steps inside
declared authority, and earns broader process ownership from measured proof.

Every client has a durable home. Every mandate has clear workstreams. Every job
can be planned, worked, checked, interrupted, resumed, and proven. Agents prepare,
identify reconciliation gaps, and draft follow-ups. Advisors set intent, handle exceptions, apply
judgment, own the relationship, and approve accountable outcomes.

Nothing acts outside its authority. Nothing important is trusted without evidence.

This is not an AI feature inside tax software. It is an operating system for an
agentic tax practice.

## The problem

Tax advisors are the integration layer today.

They move between inboxes, folders, checklists, portals, spreadsheets, tax tools,
bookkeeping tools, and the client. They collect missing data. They remember what is
blocked. They reconcile contradictions. They chase handovers. They rebuild context
every time work changes hands.

A summary, extraction result, or chat box can save minutes. By itself, it does not
own a job, advance a process, stop safely, or leave a record an advisor can defend.

The advisor is still the workflow engine.

## The shift

We move from software that stores work to agents that perform work inside explicit
permissions and human boundaries.

| Today | Agentic practice |
|---|---|
| Modules wait to be opened | Work moves until it needs a human |
| The advisor carries context | The client and workstream hold durable context |
| Checklists describe work | Tasks can be executed and checked |
| Status is updated by hand | Actions advance observable state |
| AI suggests | Agents prepare and act inside authority |
| Errors hide in handovers | Missing input and conflicts stop loudly |
| Trust comes from reputation | Trust comes from evidence, checks, and an inspectable record |

The goal is not fewer humans. The goal is to spend human judgment where it matters.

## Who this serves

"Customer" is too vague for this product. We have distinct actors:
- **Buyer**: the tax advisory firm or practice owner.
- **Daily user**: the advisor, tax specialist, bookkeeper, or operations staff member.
- **Accountable signer**: the licensed professional who owns the final judgment.
- **End client**: the person or business receiving the service and providing data.
- **Administrator**: the person who controls staff access, agents, policy, skills, and integrations.

One person may hold several roles. The product must never blur their authority.

### First market

The first end-client targets are:
- self-employed people and freelancers;
- small and medium-sized businesses.

The first buyers and daily users are tax-advisory firms and bookkeeping teams that serve
these clients. Individual income-tax filing is not the first wedge. We start with recurring
business work where missing inputs, reconciliation gaps, and advisory needs appear often.

## The product model

The business hierarchy is:

```
Organization
└── Client
    └── Engagement
        └── Workstream
            ├── Tax obligation, when relevant
            └── Task
```

Execution and evidence have their own graphs:

```
Task → Result reference → Run result ← Run
Run → attempts, events, and actions
Run result → artifacts and execution record

Document → immutable document version → evidence link
Evidence link → workstream, obligation, or task
```

- A **Client** is a person or company. A client is not a case.
- An **Engagement** is the commercial mandate and service scope.
- A **Workstream** is one body of work with a type and period. For tax work, the UI may call it a **Case**.
- A **Task** is one bounded unit a human or agent can own.
- A **Run** is one durable execution request. It may have several worker attempts and can stop, resume, fail, or finish.
- **Evidence** connects source material to a claim, task, or result.
- An **execution record** shows the inputs, actions, outputs, and human review state. It supports inspection. It is not a production seal and does not prove that the tax conclusion is correct.

Documents, evidence, requests, messages, and decisions have explicit scopes. Client conversations belong to the engagement, optionally with workstream context. Colleague conversations may belong to the organization.

## The product surfaces

The proposed future navigation model is small:
- **Today**: one prioritized stream of exceptions and approvals that need a human.
- **Clients**: the advisor's book and each client's durable workspace.
- **Work**: all active workstreams and their state across the practice.
- **Practice health**: team, agents, policy, knowledge, capabilities, integrations, and metrics.

Inside a client:
- Overview
- Engagements and workstreams
- Documents and evidence
- Communication
- Books, when relevant
- Gaps and opportunities
- Decisions and history

Inside a workstream:
- **Overview**: goal, scope, inputs, current state, and people.
- **Work**: plan, tasks, runs, blockers, and human checkpoints.
- **Trace**: evidence, actions, checks, decisions, and changes.
- **Outcome**: result, approval state, unresolved items, and execution record.

Inside the first bookkeeping workstream, the MVP uses Case → Prepare → Trace → Outcome.

## What we take from Codex

Codex is an interaction reference, not a tax-product information architecture.

We take:
- a clear place for every body of work;
- scoped conversations attached to that work;
- visible plans, tasks, progress, and artifacts;
- the ability to start, interrupt, correct, retry, and resume an agent;
- agents that ask when blocked instead of inventing an answer;
- a history that lets the user understand what changed;
- many active workstreams without losing their separate context.

We do not copy a developer terminal, a repository metaphor, or private chain-of-thought. Tax advisors need clients, mandates, workstreams, evidence, decisions, and deadlines. The interaction should feel alive like Codex. The domain model must stay tax-native.

## What "agentic" means

A workflow is agentic only when the system can:
1. Take a goal and relevant context.
2. Build or adapt a multi-step plan.
3. Use approved tools to perform real work and advance state.
4. Check the result, detect missing context, and stop when blocked.
5. Ask for a human at an explicit authority or judgment boundary.
6. Resume from durable state without rebuilding the case from scratch.
7. Leave an inspectable record of evidence, actions, checks, and decisions.

A chat box, summary, extraction result, dashboard, or generated draft can be useful. None of them is agentic by itself.

### Autonomy ladder

- **L0 — Record**: store and show state.
- **L1 — Suggest**: explain, summarize, or recommend.
- **L2 — Prepare**: produce a reviewable work product and draft next actions.
- **L3 — Execute after approval**: perform an action once a named human approves.
- **L4 — Execute inside policy**: continue autonomously and escalate exceptions.

The first state targets L2 for one bounded preparation-and-review job. It ends when the advisor accepts or returns the review package. L3 is allowed only for reversible, explicitly approved actions. Legal judgment and irreversible external actions do not become L4 merely because a model performs well.

## The new advisor role

The advisor should not spend the day moving data and polling status.

The advisor:
- sets the goal and policy;
- owns the client relationship;
- resolves unclear facts and conflicting evidence;
- identifies client gaps, risks, and value-creating opportunities;
- makes legal and professional judgment calls;
- approves irreversible or regulated actions;
- reviews exceptions and improves the system from real failures.

The product should bring the next important exception to the advisor. The advisor should not patrol nine modules to discover it.

## Client value and growth

The product should not only finish the current tax job. It should help the advisor see what the client needs next.

Examples include:
- missing service coverage;
- tax-planning opportunities;
- bookkeeping cleanup or recurring bookkeeping needs;
- liquidity and cash-flow risks;
- missing compliance work;
- another Taxfix product or advisory service that solves an evidenced client need.

Each opportunity must show the evidence, the observed gap, why it matters, the client benefit, the suggested next product or service, and what is still uncertain. The advisor accepts, dismisses, or develops it into a client conversation. The product never contacts the client or makes a sales promise automatically.

The commercial outcome may be an upsell. The trigger must be a real client need.

## The MVP operating contract

The MVP keeps trust simple:
- explicit tool and capability permissions;
- durable tasks, runs, and execution history;
- source-linked outputs;
- loud missing-input and unsupported-capability states;
- a human acceptance rubric;
- no automatic client outreach or irreversible external action.

A model-selected clean disposition does not make work advisor-ready. Human acceptance does. The MVP may use focused deterministic checks where they are cheap and useful, but it does not require a formal governance kernel or production seal.

After the MVP proves the workflow, formal Plan → Act → Check → Seal can harden the execution path. That later phase can add required checks, default-deny enforcement, tamper-evident sealing, and stronger audit claims. It is not part of the MVP scope.

## Product principles

1. **Complete jobs, not AI demos.** The unit of value is an accepted outcome.
2. **Clients are durable. Agents are temporary.** The client workspace keeps memory.
3. **Work by exception.** Healthy work keeps moving. Humans see blockers and decisions.
4. **Evidence before confidence.** A confident claim without a source is still weak.
5. **Growth follows client value.** An upsell starts with an evidenced client need.
6. **Autonomy is earned.** Start with preparation. Expand authority from measured proof.
7. **One operational state.** Chat, tasks, documents, and decisions cannot tell different stories.
8. **No silent failure.** Unsupported files, missing facts, and conflicting evidence stop loudly.
9. **Depth before breadth.** One real end-to-end workstream beats twenty shallow modules.
10. **Reuse the hard parts.** Each workstream should create skills, tools, checks, and patterns the next one can use.
11. **The advisor stays accountable.** The product makes that accountability easier to exercise and defend.

## What we refuse

- A chatbot veneer presented as transformation.
- A status field presented as completed work.
- Silent guesses or fake parsing of unsupported evidence.
- Automatic client messages, filings, payments, or other external actions without authority.
- A second maintained "SOTA app" beside the agentic product. SOTA is a benchmark and reference, not another product line.
- Runs, messages, tool calls, or tokens used as success metrics.
- Private chain-of-thought presented as audit evidence. We show sources, actions, checks, decisions, and stated reasons.
- Production-grade governance or sealing claims in the MVP.
- Generic platform work before one real workflow works.

## The first state

### Product promise

An advisor initiates a business bookkeeping workstream. A Tax Expert supervises agentic preparation and hands over a typed, evidence-linked review package. The system finds missing input, drafts the request, and stops at explicit judgment or authority boundaries. The advisor accepts or returns the package and can inspect how it was produced. The same evidence can surface client gaps and product or advisory opportunities for the advisor to review.

### Deep wedge

**Hypothesis:** start by preparing one bookkeeping period for advisor review for a self-employed person or SME.

Start when the client, engagement, bookkeeping workstream, and period exist. The input contract should cover the available bank export, incoming invoices, outgoing invoices, open items, ledger data, and supporting evidence. End when the advisor accepts or returns the review package.

The package should:
- reconcile transactions and invoices where the evidence supports a match;
- show unmatched transactions, missing receipts, and unclear payments;
- expose Debitoren and Kreditoren gaps;
- state whether the period is ready for advisor review;
- draft client questions without sending them;
- surface evidence-backed client needs and advisory or product opportunities.

Use versioned synthetic CSV and text fixtures for the first happy path. Unsupported files must create a visible capability stop.

### In scope

- Safe intake and document inventory for one defined bookkeeping period.
- Approved extraction for the synthetic CSV and text path.
- Bank, invoice, open-item, and ledger completeness checks.
- Evidence-backed transaction and invoice matching where supported.
- Explicit unmatched transactions, missing receipts, and reconciliation gaps.
- A clear period-readiness state.
- Typed claims linked to immutable source versions.
- A clear human acceptance rubric, with simple targeted checks where useful.
- Evidence-linked review points and a clear handover.
- Evidence-backed gap and opportunity cards.
- Advisor accept, dismiss, save, or turn-an-opportunity-into-a-conversation controls.
- Draft missing-information requests. Never auto-send.
- Clear `needs_capability`, missing-input, conflict, and human-review stops.
- Expert correct, retry, resume, and handover controls.
- Advisor accept or return controls.
- Event instrumentation for outcome, time, quality, intervention, and the opportunity funnel.
- Synthetic data only.

### Out of scope

- Every self-employed and SME JTBD.
- The proposed top-level navigation consolidation.
- Automatic client messaging.
- Automatic selling or client outreach.
- Live bank, DATEV, or accounting-suite integrations.
- Automatic bookkeeping entries or ledger postings.
- Payroll processing.
- Annual accounts and tax filing submission.
- Autonomous final tax judgment.
- Live payments or money movement.
- Multiple jurisdictions in the first pilot.
- A broad agent marketplace.
- A generic no-code workflow builder.

No real client data may reach any model in the first state. Moving beyond synthetic data requires an explicit decision that supersedes the current migration contract, plus authentication, tenant isolation, provider and data-processing approval, residency, retention, deletion, redacted logging, and an enforced data-class egress gate. Security and privacy owners must approve it.

## How we judge progress

The proposed north-star metric is:

> Percentage of eligible bookkeeping periods that reach an evidence-complete, advisor-ready state within the target time and without a material correction.

Supporting measures: advisor acceptance rate; advisor hands-on minutes per accepted bookkeeping period; total cycle time and waiting time; result accuracy against a double-reviewed gold set; missed material bookkeeping-issue rate; material corrections and rework; missed-document and missed-question rate; false review-point rate; evidence coverage; human intervention and override rate, by reason; model and tool cost per accepted package; silent or fake unsupported parsing, with a target of zero; unauthorized external actions, with a target of zero; unsupported-format encounter rate; repeat use by advisors; eligible bookkeeping periods handled through the system; accepted bookkeeping periods per advisor; top blocker and capability-gap reasons.

Baselines and numeric thresholds must be set before a real pilot. We do not invent them from a desk.

## Open decisions

- Which self-employed and SME subsegments should enter the commercial pilot first?
- What exact business archetypes, bookkeeping period, and exclusions define eligibility?
- What exact bank, invoice, open-item, ledger, and evidence inputs form the period contract?
- What is the typed claim-to-evidence output contract?
- What qualifies as a useful, evidence-backed client opportunity?
- Which products and services may be recommended in the first state?
- What opportunity-to-conversation and conversion events can be measured reliably?
- Which security and egress gates are required before real client data?
- Is the proposed navigation a later IA change or part of a later first-state revision?
- Which integrations are required for a real outcome, not just a demo?
- What baseline and graduation thresholds define pilot success?

These are decisions to make with the next context. They are not reasons to expand scope now.
