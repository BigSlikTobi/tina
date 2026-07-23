# 🧭 Advisor Desk MVP: the red line (start here)

*(archived)*

> We're building the thinnest honest slice of an agentic tax-advisor workbench — a vendor-agnostic, governed surface that prepares one bookkeeping period and routes it to a human for sign-off — and we've stress-tested it hard enough to know exactly what to build now, what to defer, and why.

## What we're building as an MVP
A daily workbench for tax advisors, plus one deep job: prepare one bookkeeping period and route it to the Steuerberater for sign-off.
It's vendor-agnostic. We build against clean APIs, so the bookkeeping engine, bank connector, and DATEV sit behind adapters we can swap.
The AI prepares. The human decides. We prove it on synthetic data first.

## The story in seven steps
1. **The problem.** A German tax advisor's day is fragmented: evidence-hunting, copy-paste, chasing clients, hidden work.
2. **The bet.** Make Taxfix the "Codex for Tax Advisors": the advisor gives one mission; the platform plans → works → shows its trace → stops at human gates.
3. **The thinnest honest slice.** A daily control workbench plus one deep job (prepare one bookkeeping period), for the internal SE-DIFM team, synthetic-replay first, AI prepares / human decides.
4. **Made concrete.** One case: a new freelancer, EÜR, ≤50–80 transactions a month, no cash, not a Kleinunternehmer.
5. **How we'll know it works.** Two separate scorecards, two gates (build, then replay), hard guardrails, and the non-negotiable: no false-ready.
6. **We attacked it.** A full 360° war game — twice. Two scary findings turned out to be decisions, not defects (vendor-agnostic via APIs; the prototype is out of scope). No kill shot survived.
7. **What we build and why.** Three safety rails first, everything else iterative. Every decision is traceable. Failing is OK — as long as we can explain the choice.

## How to read the pages below
Each piece of work has three connected parts:
- **Outcome page:** what we decided and where it stands (brief, in plain words).
- **Full document:** the complete artifact with full evidence register.
- **Thought process:** how we got there, in plain words.
Transcripts are attached to each artifact where they exist.
Read in order: this page → manifesto → SOTA benchmark → agentic MVP → war game → metrics → go-to-market → build decision.
Supporting pages (product vision, SOTA-to-Codex direction, todo before MVP, strategy alignment) carry the context behind these artifacts.

## One principle underneath all of it

> ⚖️ Context is the foundation. Controlled execution creates the outcome. The human keeps authority.
