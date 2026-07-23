# From SOTA to Codex for Tax Advisors

- Status: current direction
- Owner: Product
- Updated: 2026-07-17
- Scope: Advisor Desk and the first SE-DIFM bookkeeping job
- SOTA source: [The Current SOTA Advisor Desk](SOTA/sota_advisor_desk.md)
- Product vision: [Agentic Product Roadmap](product_vision.md)
- Live mock: [Codex for Tax Advisors](https://taxfix-codex-ta-platform.bigsliktobi.chatgpt.site)

## The decision

We are not building a better dashboard.

We are turning the Advisor Desk into the Codex for Tax Advisors.

The Desk starts as the best place to understand work.

It becomes the place where work gets prepared, checked, reviewed, and resumed.

The Advisor keeps professional judgment and every consequential external action.

The platform takes over the coordination and routine preparation around those decisions.

The operating plan is nine months.

The month count starts only when the SE-DIFM workspace, eligible case volume, and first Advisor cohort are verified.

## Where we start

The current SOTA is a control tower.

It connects the important state across specialist tools.

It shows what changed, what is urgent, what is blocked, and what needs the Advisor.

It brings sources, unknowns, options, and the next decision into one place.

It can move bounded internal work.

It stops before professional judgment, client contact, filing, payment, or selling.

That is the right market bar for the later whole-book Desk.

It is not the first product promise.

The first product promise is smaller:

```text
One eligible SE-DIFM bookkeeping period
-> evidence-linked preparation
-> Advisor accept or return
-> manual, controlled DATEV handoff
```

DATEV and ELSTER stay authoritative for their production records.

Taxfix owns the client workspace, mission, tasks, runs, evidence, review, blockers, and history around the work.

## What is still broken

The control tower helps the Advisor organize the day.

It does not yet carry enough of the work.

The Advisor still has to open the case, rebuild the plan, collect the evidence, follow the waits, and move the process forward.

The Advisor is still the workflow engine.

This is the jump the vision must make:

```text
SOTA Desk
understands and organizes work

Codex for Tax Advisors
prepares and advances approved work
```

We should not wait several months to show this difference.

The first increment needs one real agentic loop.

## The first agentic difference

The Advisor opens one client mission.

The platform proposes a short plan.

The Advisor starts or edits the run.

The platform performs the approved preparation.

It shows every material source, change, unknown, and blocker in Trace.

The Advisor accepts, returns, corrects, pauses, retries, or takes over.

The work resumes from the recorded state.

The loop is:

```text
Mission -> Plan -> Work -> Trace -> Review -> Resume
```

Example:

> Prepare May bookkeeping for review.

The platform checks the supported bank and invoice evidence.

It matches what it can support.

It lists unmatched transactions and missing receipts.

It states whether the period is ready for review.

It drafts the missing client questions.

It does not send them.

It stops if a file format is unsupported or a professional decision is needed.

This is small enough to prove.

It is different enough to matter.

## How the Advisor journey changes

Today, the Advisor searches, coordinates, checks, and decides.

At the start, the Desk organizes the work and one mission prepares a real outcome.

Over time, proven preparation becomes the default for eligible work.

The Advisor moves from driving every step to supervising exceptions and making the decisions that need judgment.

The handover must stay calm.

First we show what the platform sees.

Then we show what it plans.

Then we let the Advisor delegate a bounded mission.

Then we make proven preparation the default.

At every step, the Advisor can inspect, correct, reject, pause, or take over.

## The nine-month path

These are relative operating months. They are not calendar promises.

| Month | What the Advisor wants to do | What changes in the product | What stays with the Advisor |
| --- | --- | --- | --- |
| Entry gate | Start with real work and a real cohort | Verify the workspace, eligible cases, named Advisors, and baseline | Decide whether the operating plan can start |
| 1 | Know what needs attention and move one case forward | SOTA Desk plus one mission, short plan, bounded run, and Trace | Start or edit the run. Review the result |
| 2 | Finish one bookkeeping period without rebuilding context | Complete the supported preparation and record the manual DATEV handoff | Accept or return. Complete the external handoff |
| 3 | Repeat the job without losing state | Add reliable retry, resume, correction, and visible blocker handling | Correct weak work and choose fallback |
| 4 | Stop chasing waits | Keep proven missions alive through waits and new evidence | Handle exceptions and client decisions |
| 5 | Cover more real evidence | Add formats or tools only when job tests prove them | Approve support expansion. Review uncertain evidence |
| 6 | Handle more preparation behind one mission | Add specialist capabilities behind one plan and one Trace | Resolve conflicts and professional questions |
| 7 | See the whole eligible book by exception | Monitor proven jobs across clients and rank changed states | Set priorities and take over where needed |
| 8 | Let routine preparation happen by default | Make proven internal preparation the normal path for the cohort | Review exceptions, returns, and consequential steps |
| 9 | Run the eligible book from one workbench | Codex becomes the default workbench for the named cohort and proven jobs | Own judgment, client relationships, and external action |

Opportunity signals run in parallel from the start.

They stay in shadow mode until the evidence and Advisor decisions show that they are useful.

The system may surface a client need.

It may not contact the client or turn that need into a sale.

## What technology progress changes

The plan must not assume that today's model limits stay fixed for nine months.

Each month, we check what the frontier can now do for the first job.

Better multimodal models may unlock more invoices, statements, notices, and mixed evidence.

Better background agents may keep missions alive through waits, retries, and new input.

Better tool use may complete more approved steps inside Taxfix systems.

Better verification and routing may reduce false-ready results, review effort, latency, and cost.

Better specialist coordination may let several capabilities work behind one mission without splitting the Advisor experience.

If a gain passes the job-specific tests, we can pull a roadmap item forward.

The proof still needs source coverage, quality, privacy, recovery, cost, and Advisor control.

A stronger model never grants itself more authority.

## The product artifacts that change

| Artifact | What it becomes |
| --- | --- |
| Client workspace | The durable home for the client, mandate, evidence, communication, and history |
| Workstream or case | One defined body of work with a period, scope, goal, and accepted end state |
| Mission | The outcome the Advisor asks the platform to prepare |
| Plan and tasks | The visible steps, owners, dependencies, checks, and human stops |
| Run and events | The durable execution state, progress, retries, pauses, and resume point |
| Evidence and Trace | The sources, actions, changes, checks, unknowns, and review decisions |
| Review package | The evidence-linked result the Advisor accepts or returns |
| Blocker and wait | A visible reason, owner, next step, and next check |
| Capability and permission | The exact tools and actions approved for this job and cohort |
| Opportunity | An evidenced client need with confidence, unknowns, and an Advisor decision |
| Handoff | The controlled move into DATEV or another external system, manual first |
| Metrics and gates | Quality and trust first, handling time second, business value after that |

The artifacts tell one story.

Chat, tasks, evidence, review, and state cannot disagree about what happened.

## The final Month 9 state

The Advisor gives a mission instead of rebuilding a process.

The platform plans and prepares the proven work.

It keeps the work alive.

It explains what changed.

It brings the Advisor only the exceptions, questions, and approvals that need a human.

The Advisor can inspect the Trace, interrupt the run, correct it, return it, or take over.

The platform resumes without losing the case.

This is the Codex relationship.

It is not a terminal copy.

It is not a chatbot.

It is not an autonomous tax practice.

It is the operating system for agentic Tax Advisory, with the Advisor still accountable.

## What is decided

- The product is the TA Platform.
- Advisor Desk is its workbench.
- Codex for Tax Advisors is the north-star experience.
- The operating plan is nine months after a verified entry gate.
- The first deep job is bookkeeping-period preparation for an eligible SE-DIFM cohort.
- The first release combines SOTA quality with one real agentic loop.
- The manual DATEV handoff stays until a sanctioned route earns approval.
- Opportunity learning starts early, in shadow mode, and stays Advisor-gated.
- Frontier progress is reviewed monthly and may pull proven work forward.
- Professional judgment and consequential external actions stay human-controlled.
- PACS and formal sealing are not part of this plan.

## What we still assume

- One deep job will create reusable context, permission, review, and recovery patterns.
- Advisors will accept a gradual transfer from visible assistance to proven default preparation.
- One mission and one Trace can hide specialist complexity without hiding material facts.
- Model progress will improve the pace, coverage, and economics of the plan.

These are working assumptions.

They are not proof.

## What remains open

- Who owns the Month 1 entry gate?
- How many eligible cases are enough to start?
- Which named Advisors join the first cohort?
- What exact acceptance rubric defines an Advisor-ready bookkeeping period?
- What counts as a material correction or false-ready result?
- Which file format earns support next?
- Which sanctioned DATEV route is viable later?
- What threshold lets an opportunity signal leave shadow mode?
- Which agent family earns the next investment after the first job?

## Revisit this direction when

- direct Advisor observation changes the job;
- the first bookkeeping evaluation fails its quality or trust gate;
- handling time does not improve;
- the entry cohort is not available;
- a frontier capability passes or fails the job-specific proof;
- the sanctioned integration path changes;
- opportunity signals create noise or weak client value; or
- a new company decision changes the TA Platform strategy.

## What happens next

Use the [live Codex mock](https://taxfix-codex-ta-platform.bigsliktobi.chatgpt.site) with real internal Advisors.

Test one simple question:

> Can an Advisor understand the mission, trust the Trace, make the review decision, and know what happens next?

Then define the first bookkeeping evaluation pack and the Month 1 entry record.
