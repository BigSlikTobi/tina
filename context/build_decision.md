# ✅ Build decision (what we build now, and why)

> **Outcome.** Build a vendor-agnostic control-and-review surface for the internal SE-DIFM operation. Put three safety rails into the architecture from day one; let the rest earn its complexity through replay and use. Failing is fine, as long as we can say why we chose what we chose and what the result taught us.

## The decision

We build the MVP as specified: vendor-agnostic, against clean API abstractions, and deliberately narrow. GFR, FinAPI and DATEV/ELSTER are today's reference integrations, each behind an adapter we can replace. Naming the systems we need to integrate is not a decision to become dependent on them.

The product has two jobs. The first is a daily control layer for Advisors and Sachbearbeiter: one honest view of what needs attention, who owns it, where the underlying fact came from, how fresh it is, what blocks it, and what should happen next. The second is a governed review mission: for one bookkeeping period, assemble the engine's output, verify it against source evidence, and route a durable review package to the Steuerberater.

We are not building another bookkeeping engine. The execution layer governs and verifies the bookkeeping engine's output; it does not re-create the calculation and add another place for the system to be confidently wrong. The advisor signs off. **Ready is never the same as filed.** Autonomy stays at L2: prepare thoroughly, make uncertainty visible, and stop when the case needs a person.

The first proof is intentionally small: one frozen Buchungsprofil, a German Einzelunternehmer/Freiberufler digital consultant, EÜR, Ist-Versteuerung, one bank account, 50–80 transactions a month, and no cash, payroll, e-commerce or Kleinunternehmer complexity. We evaluate it through synthetic replay on a pre-registered gold pack, not real client data. That is not a retreat from ambition; it is how we learn without pretending the system is safer or broader than it is.

## Build now vs iterate

Three things go in from day one because they are cheap to design in and painful to retrofit:

1. **Govern don't rebuild.** The engine remains the source of bookkeeping computation; our layer checks, explains, evidence-links and routes.
2. **Know when the facts are stale and fail closed.** Every source-derived fact gets a freshness stamp. If the bank, ledger or other evidence is too old, the system does not call the period ready and does not guess its way past the gap.
3. **Read documents, never obey them.** Bank data, invoices and OCR output are untrusted input. A document can support an accounting decision; its text can never become an instruction to the system.

The rest starts deliberately rough and sharpens with evidence. The scope gate begins as a strict allow-list around the frozen case, then expands case by case. The recovery path begins as an owned human queue for blocked work, not an imagined client-chat loop we have not built. Metric thresholds are pre-registered before replay results are seen, anchored to a real baseline rather than a number that flatters the demo.

The rule of thumb is simple: install architectural safety rails now; iterate on operational detail once we have learned where the work actually breaks.

## What this does not promise

This phase does not auto-file, write to DATEV, process real client data, or cover every German bookkeeping shape. It does not include client chat, broad opportunity discovery, structured e-invoice parsing, payroll, cash businesses, e-commerce, Kapitalgesellschaften or Kleinunternehmer cases. Those are not forgotten work. They are separately-gated decisions with additional authority, data-exposure or scope implications.

The point is not to make the MVP look complete. The point is to make its boundary honest — so a green result means something, and a stop is a controlled outcome rather than a hidden failure.

## Status

**Gate: hold, then narrow.** There is no P0 blocker to the synthetic-replay build. The hold is purposeful: close the core design requirements, name the remaining owners and thresholds, then enter replay with a test we can defend.

The go-live prerequisites: filing authority, a named security owner, reviewer backup and DATEV partner onboarding are real. They belong at the controlled-live and real-data gates, not as excuses to delay the synthetic proof. We build the proof now, carry the open risks visibly, and let the evidence decide whether we narrow, iterate or stop.

This page is the short decision. The full record carries the scenarios, open questions, gate logic and rationale behind every choice.

- [Build decision (full document)](https://app.notion.com/p/3a639357d8478128b4a7c9b584507cea)
