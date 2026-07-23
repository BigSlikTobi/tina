# ⚡ Codex for Tax Advisors - Agentic MVP

> ### *Context is all you need*
> *In 2017, researchers at Google and their collaborators published a paper with a five-word title: "Attention Is All You Need."*
> *The title wasn't modest. Its claim was precise: for a new architecture, attention could replace recurrence and convolution. You just needed to know where to look.*
> *Tax advisors have known this for a long time.*
> *Every morning, a Steuerberater opens the same case. The client is there. The evidence is there. The deadline is there. Most of it is buried across five different tools, an inbox, a spreadsheet, and their own memory. Before they can do anything useful, they have to rebuild the picture.*
> *That's not a talent problem. That's a context problem.*

We're building the Codex for Tax Advisors because we believe the same thing that team believed in 2017. The answer isn't more tools. It's not a smarter model on its own. It's the right context, in one place, honest about what it knows and what it doesn't.

> **Context is all you need.**

The agent works inside that context. The advisor owns it. Every claim should link to a source. Every gap should be visible. Every decision stays with the human who's accountable for it.

> Context is the foundation. Controlled execution creates the outcome.

## Advisor Desk MVP: the build

> We're building the thinnest honest slice of an agentic tax-advisor workbench, **a vendor-agnostic, governed surface that prepares one bookkeeping period and routes it to a human for sign-off**. We've tested the scope hard enough to be clear about what we build now, what we defer, and why.

### What we're building as an MVP
A daily workbench for tax advisors, plus one deep job: prepare one bookkeeping period and route it to the Steuerberater for sign-off.
It's vendor-agnostic. We build against clean APIs, so the bookkeeping engine, bank connector, and DATEV sit behind adapters we can swap.
The AI prepares. The human decides. We prove it on synthetic data first.

### The story in seven steps
1. **The problem.** A German tax advisor's day is fragmented: evidence-hunting, copy-paste, chasing clients, hidden work. [See the SOTA benchmark →](https://app.notion.com/p/3a439357d847819a99cbf4284b3f834a)
2. **The bet.** Make Taxfix the "Codex for Tax Advisors": the advisor gives one mission; the platform plans → works → shows its trace → stops at human gates. [See the manifesto →](https://app.notion.com/p/3a439357d84781d78b1cece4dfdc49cb)
3. **The thinnest honest slice.** A daily control workbench plus one deep job (prepare one bookkeeping period), for the internal SE-DIFM team, synthetic-replay first, AI prepares / human decides. [See the Agentic MVP →](https://app.notion.com/p/3a439357d84781f89e95d5dc6c92345c)
4. **Made concrete.** One deliberately narrow test case: a new freelancer using EÜR, about 50–80 transactions a month, no cash, and outside the Kleinunternehmerregelung. [See the Agentic MVP scope →](https://app.notion.com/p/3a439357d84781f89e95d5dc6c92345c)
5. **How we'll know it works.** Two separate scorecards, two gates (build, then replay), hard guardrails, and the non-negotiable: no false-ready. [See metrics and gates →](https://app.notion.com/p/3a439357d84781368da5ebd9f07a7fdb)
6. **We attacked it.** A full 360° war game — twice. Two hard findings became explicit decisions, not defects (vendor-agnostic via APIs; the prototype is out of scope). It found no blocker to the synthetic-replay MVP. [See the war game →](https://app.notion.com/p/3a439357d847816f841df35b94532b0d)
7. **What we build and why.** Three safety rails first, everything else iterative. Every decision is traceable. Failing is OK — as long as we can explain the choice. [See the build decision →](https://app.notion.com/p/3a439357d84781bdb2f1fd75d1c3675b)

### How to read the pages below
You don't need to read all of it! Use  to ask questions and let's you guide through the context documents.
If you want to read, each piece of work has three connected parts:
- **Outcome page:** what we decided and where it stands (brief, in plain words).
- **Full document:** the complete artifact with full evidence register.
- **Thought process:** how we got there, in plain words.
During the agent conversation every elaboration was transcribed to capture the thought process of the agents and the creator. Those transcripts are attached to each artifact where they exist.
Supporting pages (product vision, SOTA-to-Codex direction, todo before MVP, strategy alignment) carry the context behind these artifacts.

---

- [Advisor Desk MVP: the red line (start here)](https://app.notion.com/p/3a439357d847817597c5e13b1c92862f)
- [The Agentic Tax Practice (manifesto)](https://app.notion.com/p/3a439357d84781d78b1cece4dfdc49cb)
- [SOTA benchmark (market reality)](https://app.notion.com/p/3a439357d847819a99cbf4284b3f834a)
- [Agentic MVP (the scope)](https://app.notion.com/p/3a439357d84781f89e95d5dc6c92345c)
- [War game (we tried to break it)](https://app.notion.com/p/3a439357d847816f841df35b94532b0d)
- [Metrics and gates (how we'll know)](https://app.notion.com/p/3a439357d84781368da5ebd9f07a7fdb)
- [Go-to-market (who we serve first)](https://app.notion.com/p/3a439357d84781ab90f4d38d8bbb1c6a)
- [Build decision (what we build now, and why)](https://app.notion.com/p/3a439357d84781bdb2f1fd75d1c3675b)
- [Product vision (roadmap)](https://app.notion.com/p/3a639357d84781b5bbedc7a49ab61676)
- [SOTA to Codex: the product direction](https://app.notion.com/p/3a639357d847818ea093ee2c8a9f3622)
- [Todo before MVP](https://app.notion.com/p/3a639357d847815eab95c30734d446aa)
- [Strategy alignment: vision ↔ internal strategy](https://app.notion.com/p/3a639357d84781c7a6a6daa41c0fce78)
