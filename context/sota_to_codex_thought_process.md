# 🧠 SOTA to Codex: thought process

- Status: current reconstruction
- Owner: Product
- Updated: 2026-07-17
- Source basis: sanitized SOTA and product-vision transcripts

## What this document is

This is a transparent reconstruction of the product decisions in the working transcripts. It explains what changed, why it changed, and where we landed. It is not hidden model reasoning.

## The short version

We started by asking what the Advisor should see in the morning. We ended with a much bigger decision. The product should not only show the work. It should prepare and advance the work. The Advisor should move from workflow engine to supervisor of evidence, exceptions, judgment, and client relationships. The north star is Codex for Tax Advisors. The operating plan is nine months. The first proof is one bookkeeping period, not the whole tax practice.

## 1. We started with the morning view

The first question was simple: What should the Advisor see when they open the Desk in the morning?

That framing was too small. The user clarified that morning is a habit signal. The Desk should be useful every time the Advisor returns during the day. The job became a full-day command center across five normal workdays.

What changed: Morning triage became full-day orientation and control. The first view became a return point, not a one-time briefing. The product had to explain what changed since the last visit.

## 2. We removed our own product from the SOTA lens

The first analysis looked too closely at the existing build and existing product ideas. The user stopped that. SOTA had to start from a blank sheet. The question became: if we started today, what operating process would make a German Tax Advisor measurably better across the whole day?

What changed: Market change came first. Real Advisor work came second. Current products and credible frontier behavior came third. The Taxfix build stopped setting the bar. A benchmark should not make our current idea look good.

## 3. The SOTA became a control tower

The market evidence did not point to a bigger dashboard. It pointed to an Advisor operating and decision layer. The mature DATEV stack set the German control floor. Milia plus Taxy.io set the feasible modern German floor. Karbon set the adjacent agentic behavior ceiling. No single reviewed product proved the full combination.

The resulting SOTA loop:

```
sync state -> detect change -> brief -> rank -> prepare -> decide -> act -> monitor -> return
```

Parity meant matching outcomes and control. It did not mean copying DATEV screens.

## 4. We found the limit of SOTA

The SOTA Desk organizes the work very well. But the key question remained: Is the product organizing the work, or processing it? At the beginning, it mostly organizes. That is useful. It is not the AI-first transformation. The Advisor still carries the plan, the follow-through, and the process state.

## 5. We changed the ambition to Codex for Tax Advisors

The product vision made the leap explicit: Taxfix should be AI first. Advisor Desk should become the Codex for Tax Advisors. Codex was not used as a terminal design. It described the working relationship.

The Advisor gives a mission. The platform proposes a plan, performs bounded work, shows the Trace, stops at human gates, and resumes after correction. The loop became:

```
Mission -> Plan -> Work -> Trace -> Review -> Resume
```

## 6. We shortened the horizon

The first roadmap used an 18 to 24 month horizon. The user rejected it. The target moved to a 9 to 12 month transformation. Then the operating plan became nine months. The month count later became relative to a real entry gate. No verified workspace and case volume means Month 1 has not started.

## 7. We added agency in the first increment

A SOTA Desk alone would make the start look too conventional. The user wanted the first agentic difference immediately. The answer was one intervention-to-handled-outcome loop.

This avoids two weak starts: a polished Desk that still leaves the Advisor as the workflow engine; and broad autonomy that asks for trust before the product has earned it.

## 8. We separated three responsibilities

1. Organize work broadly.
2. Process approved work deeply.
3. Decide consequential matters.

The Desk can organize across the book early. The platform should process one deep job first. The Advisor keeps professional judgment, client decisions, filing, payment, signing, and selling.

## 9. We corrected the JTBD mapping

The root `jtbd.md` is a historical implementation coverage inventory. It is not the canonical JTBD portfolio. The product journey and the JTBD inventory are different things. The canonical dossier does not exist yet for ADV-MORNING-001.

## 10. We accounted for a moving AI frontier

A nine-month AI product cannot be planned against today's model ceiling. The roadmap added a monthly frontier lane covering: multimodal evidence; background agents; tool use; specialist coordination; verification and model routing; lower cost and latency.

Better technology may pull work forward. It does not create product support on its own. It does not grant more authority.

## 11. Company context changed the product frame

New company sources introduced a sharper TA Platform strategy. The strategy had three stages: operational tool, working machine, and opportunity machine. The resulting decisions were:

- The product is the TA Platform. Advisor Desk is its workbench.
- Start with low-document-volume, VAT-liable freelancers and digital consultants in SE-DIFM.
- Use manual GFR CSV to DATEV import and manual notice upload first.
- Keep opportunity learning parallel, shadow-first, and Advisor-gated.
- Use quality and trust as hard gates. Use handling time as operating proof.
- Use net revenue per active Advisor as the business North Star. Treat ARPU as a diagnostic.
- Treat named agent families as future targets, not current product support.

## 12. We removed PACS from the path

The company context still contained formal governance and Seal language. The user gave a direct instruction: PACS is out for now. The current product promise is Trace. PACS and formal sealing are later trust-hardening work. They are not part of the MVP or the nine-month operating plan.

## 13. We made the vision visible

The last risk was abstraction. The documents could describe Codex for Tax Advisors without making it feel real. The first interactive mock changed that.

## Where we are now

The current product decision is clear. We start with SOTA quality and one real agentic loop. We prove one bookkeeping period end to end. We keep the manual DATEV handoff. We expand preparation job by job. We move the Advisor from driver to supervisor without removing authority. We review frontier progress every month. By Month 9, the TA Platform should be the default workbench for the named cohort and proven jobs.

## What is fact, decision, assumption, and open

**Observed or supplied facts:** The German workday spans several specialist tools and human handovers. No reviewed product proves the complete German whole-book agentic loop. DATEV and ELSTER remain the statutory record. The current handoff is manual. Direct five-day Advisor observation is still missing.

**Current decisions:** AI first. Codex for Tax Advisors as the north star. Nine-month operating plan after a verified entry gate. One deep bookkeeping job first. Agentic difference in Month 1. Human authority for judgment and consequential actions. Opportunity signals in parallel shadow mode. PACS and formal sealing out of scope.

**Open questions:** Entry-gate owner and threshold. First Advisor cohort. Advisor-ready rubric and material-correction definition. Supported-format sequence. Later sanctioned DATEV route. Opportunity promotion threshold. Next agent family after bookkeeping. Canonical JTBD dossier location and owner.
