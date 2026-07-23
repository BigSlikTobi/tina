# 📊 Metrics and gates (how we'll know)

> 📊 **Outcome.** Two scorecards, two gates, hard guardrails. The line we never cross: nothing is called ready when it isn't.

## How we measure

We keep the daily-workbench scorecard and the bookkeeping-period scorecard separate. A good result on one cannot hide a failure on the other. The first asks whether an Advisor can see the work, understand what matters, and reach the right next action without hunting through parallel systems. The second asks whether an eligible period can reach a reviewable, evidence-linked package and a controlled manual handoff without creating hidden risk.

Four early KPIs decide the first product-proof gate. Does the product finish eligible periods correctly? Does it reduce real Advisor effort per accepted period, rather than simply moving effort into review or rework? Does it help the Advisor find the next material action faster? And does the workbench show all the material work that the Advisor needs to act on?

Later measures tell us whether that value compounds: more accepted periods per active Advisor, durable net revenue per active Advisor, and economics that still work once support, recovery, and tooling costs are visible. They matter, but they do not buy a pass at the early gate.

## The two gates

**G001 — ready to build.** Before we write our way into confidence, we fix the contract: the case rubric, gold fixtures, material-correction and false-ready definitions, named owners, baseline plan, instrumentation, support route, and breach actions. Every score needs a denominator, source, formula, and accountable person. If one is missing, the gate holds.

**G002 — ready for synthetic replay.** The built product earns this only through observed proof. The four early KPIs must each clear thresholds set *before* replay, every hard guardrail must pass, and the evidence must be complete. No weighted average. No offsetting a critical miss with a strong average. If the product fails, we learn why, narrow the case or capability, fix it, and return to a new human decision.

## The guardrails that can stop it

False-ready is target zero. A package is only ready when it is for the right client and month; required inputs are present or visibly missing; evidence reconciles; material claims link to sources; conflicts and unknowns are visible; unsupported content is blocked; and an Advisor can accept or return it. If the system says ready while a required input, material conflict, check, capability, or review is missing, we stop the affected mode.

The same rule applies to cross-scope action, unauthorized access, privacy breach, unsafe or fake parsing, lost or duplicate action during retry or resume, and missed stop-level Advisor work. We do not trade safety for speed. A good average never buys back a critical miss.

The first evaluation is deliberately bounded: five normal Advisor workdays establish the baseline; the product is tested through synthetic replay using a versioned gold case pack. No real or re-identifiable client data, no automatic external effect, and no authority expansion. The manual downstream handoff stays vendor-neutral and human-operated, with destination, operator, package version, time, and outcome recorded. An unknown handoff result is reconciled before retry.

## Status

The design is set; the proof contract is not complete yet. We still need to instantiate the gold case schema and answers, name the responsible people and baseline Advisors, and commit the numeric thresholds and minimum replay volume after the five-day baseline—but before we see replay results. That discipline is the point: we decide what good looks like before the product has a chance to persuade us.

Until then, the decision remains **hold / narrow**. We can build only the bounded path we can measure, review, stop, and recover. Nothing here automatically expands lifecycle, capability, or authority.

- [Metrics and gates (full document)](https://app.notion.com/p/3a639357d84781ecb4f8eb6c78588893)
- [Metrics and gates (thought process)](https://app.notion.com/p/3a639357d84781328abffdff54f8e839)
- [Metrics and gates (transcript)](https://app.notion.com/p/3a639357d847818995e6df49db3d39ad)
- [Metrics and gates (dashboard mock)](https://app.notion.com/p/3a639357d8478198b639eca9f253cf29)
