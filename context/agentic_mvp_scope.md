# 🎯 Agentic MVP (the scope)

> 🎯 **Outcome.** The thinnest honest slice we can build, put under pressure, and believe: a daily workbench for the whole Advisor day, plus one deep bookkeeping job. Internal Advisors first. Synthetic data first. The AI prepares; the human decides.

## The bet
The first shot is not a chatbot with a bookkeeping demo attached. It is the Advisor's home base: the place where the day can be understood without stitching together DATEV, task lists, and Taxfix systems by hand.
That is the control layer. It must make the book of work legible: what needs attention, for whom, by when, why it is blocked, where the source is, and what happens next. If this layer is incomplete, stale, or decorative, the Advisor still has to keep another system open for the real day. Then we have not earned the right to be the workbench.
Inside that workbench sits one execution layer: prepare one supported bookkeeping period, expose what is missing or conflicting, and route a reviewable package to sign-off. We go narrow on the job so that the promise is testable. We go broad enough on the desk that it feels like a product, not a clever sidecar.

## What it commits to
Two layers, one front door.
- **Control:** the full in-scope day across DATEV, task lists, and Taxfix systems. Clients, deadlines, tasks, waits, blockers, reviews, ownership, freshness, and next actions remain visible.
- **Execution:** one bounded bookkeeping-period mission. The platform scopes the work, plans it, reconciles supported evidence, records gaps and conflicts, builds a package, and brings it to human review.
The Tax Advisor remains accountable for judgment, the client relationship, acceptance, and every consequential downstream action. Autonomy stays at L2: prepare and review, never silently decide, send, file, pay, sell, or post.
This is deliberately not DATEV write automation, client chat, a general calendar, an inbox, or a promise of autonomous bookkeeping. Those are real future surfaces. They are not required to prove this one.

## What "agentic" means here
The agents are not a cast of invisible helpers. Each has a bounded role, a visible plan, a trace, a capability limit, and a stop rule.
The Tax Advisor Agent owns the mission and explains the next human move. DataJanitor Pro inventories and reconciles supported inputs. FristenGuard watches approved work dates, waits, and stale work. The Document Review Agent checks supported evidence. AdvisorLens may surface one evidence-backed opportunity after the bookkeeping work is prepared.
The important rule is simple: a confident-looking answer is not a result. A period is never "ready" when required evidence is missing, a source conflicts, a check has failed, or the system cannot safely perform the necessary work. In those moments, the product should be useful precisely because it stops clearly: what is wrong, who owns it, what would unblock it, and where the evidence lives.

## Made concrete
We start with one case: a new freelancer on EÜR, fewer than 80 transactions a month, no cash, and not a Kleinunternehmer. It is a product assumption, not a claim about the entire market. Its purpose is to create a small, real enough proof contract.
For that client and one period, the platform must either produce a reviewable bookkeeping package or land in an honest state such as `missing_input`, `conflicting_evidence`, `needs_capability`, or `failed_check`. Both outcomes are valuable. A false-ready result is not.
The happy path is not enough. The proof includes a missing bank or invoice input, unsupported evidence, a conflict between sources, a returned package, cancellation, resume after new evidence, and an unknown downstream result. It also includes denial: an agent that tries to cross a tenant boundary, follow an instruction hidden in evidence, or take an unapproved action stops.

## The human moment
The end state is not "the agent finished." The end state is an Advisor seeing a package they can understand and decide on.
The review must show the period, the plan, the sources used, the checks passed, what remains unknown, the material claims, the blockers that were resolved or remain open, and the next downstream step. The Advisor can accept, return, correct, pause, cancel, or take over. Reviewed history is preserved; it is superseded, never quietly erased.
Opportunity Radar is held to the same standard. It may show at most one strong signal, first, overdue receivables and possible cash-flow pressure, with evidence, impact, confidence, unknowns, and an allowed service. It can be saved or dismissed. It never changes bookkeeping readiness, and it never reaches out, sells, prices, or promises on the Advisor's behalf.

## How we prove it
We prove the product on synthetic replay before any real client data. The first question is not whether the interface looks intelligent. It is whether the system can repeatedly produce the right state for the right client and month, with the right evidence, without hiding exceptions.
A passing replay means: the correct scope is bound; required input is accounted for; supported evidence is reconciled; every material claim links to an exact source version; conflicts and unknowns are visible; the Advisor can accept or return; and retry or resume never duplicates an action. One happy path and at least one exception path must complete the full loop: observe, decide, act, check, adapt or stop.
Only after the baseline do we set numeric thresholds and replay volume. Only after the provider and data contract is complete — including access, retention, deletion, tenant controls, and incident ownership — do we discuss controlled use with real client data.

## Status
**Gate: hold, then narrow.** The scope is set. The remaining work is definition, not a reopening of the product shape.

### First: synthetic replay
We can test the MVP on synthetic data before any real client data is involved. Before replay starts, we need to agree the test rules: who reviews when the usual reviewer is unavailable, how escalation works, how many cases we replay, what counts as a pass, how long we watch for later material corrections, and which services Opportunity Radar is allowed to suggest.

### Then: controlled use with real client data
Real client data is a separate, later gate. We do not cross it until the data and operating contract is exact: which DATEV, task-list, and Taxfix data is used; who owns it; how fresh it must be; the eligible case schema; supported evidence; the downstream handoff; and the named people responsible for review, intervention, and incidents. The provider contract must also cover access, retention, deletion, tenant controls, and incident handling.
In short: **synthetic replay first; controlled live use only after the replay evidence and data contract are in place.**
This is a demanding first shot by design. The daily workbench is a must-have, not a later polish layer: if the Advisor has to leave it to understand most of the day, the product has failed the bar. The deep job gives us the place to prove that agents can earn trust, not through autonomy theatre, but through disciplined preparation, visible limits, and better human decisions.
The sub-pages carry the full contract, reasoning, and audit trail.

- [Agentic MVP (full document)](https://app.notion.com/p/3a439357d84781d2b230cb990a11ee9f)
- [Agentic MVP (thought process)](https://app.notion.com/p/3a439357d847817f9c46f277ef1076f2)
- [Agentic MVP (transcript)](https://app.notion.com/p/3a639357d84781e29142cdd974951117)
- [Agentic MVP (source audit)](https://app.notion.com/p/3a639357d847813e9346c9a89259367b)
