# TA Platform: Decisions Needed, Cross-Checked Against Notion

- Status: For review
- Owner: Tobias Latta
- Updated: 2026-07-26
- Freshness: Current
- Confidence: Medium. Sourced from dated Notion pages, not from a single approved plan.
- Strategy draft: [TA Platform Strategy](./ta_platform_canonical_strategy.md)
- Purpose: Check each of the 8 open decisions in the canonical strategy against what Notion actually says, and flag contradictions.

## 1. TA-count definition: which milestone counts as one of the 200 TAs

No stage taxonomy exists in Notion. Nothing defines "200" as registered, verified, contracted, qualified, activated, or first-paid-case.

Still open. No Notion source answers this.

## 2. Target dates for 200 and 1,000 TAs, and whether either matches the "1,000+ in Year 1" slide

"TA Platform Strategy Rundown V0.3" sets 100 to 300 TAs live by EOY 2026, and 1,000 TAs live by EOY 2027. A footnote says the 1,000 figure needs a second acquisition motion, TAs bringing their own clients, that isn't built yet. "Strategy alignment: vision ↔ internal strategy" confirms white-label Kanzleien start Q1 2027.

So internally, 1,000 is a 2027 to 2028 horizon, not Year 1.

This contradicts the leadership slide. Nothing else in Notion supports "1,000+ in Year 1." Worth asking leadership directly what "Year 1" means, since no internal plan hits 1,000 in the current year.

## 3. CaseOps and TalentOps sequencing and ownership: do the two tracks run on the same timeline, and who owns each

The "TA Platform — H2 Initiative List" status tracker shows CaseOps items (TA Backoffice Dashboard, DATEV Roundtrip) as In Delivery for Q3 2026. Marketplace MVP, which covers register, qualify, train, and quality-check (TalentOps), is In Discovery for Q4 2026, one quarter behind.

Ownership on that same tracker: Product is Tobias Latta. Engineering Manager, Design, Tax Experts, Engineering, Data, and Research are all listed empty.

The two tracks are not moving at the same pace today, and TalentOps has no named owner beyond Product. This doesn't confirm they can't run in parallel. It shows that right now, they aren't.

## 4. Monitor as the B2C delivery system: is it the system Tax Advisors will use to deliver B2C cases

Yes. "2026 H2 Opportunities" and "Scale Assisted Delivery via TA Platform (B2C)" both name it directly: evolve Monitor into a B2C Tax Advisor Platform so it scales to a larger advisor network. This is an active H2 2026 bet, not a proposal.

Answered.

## 5. Role permissions for tax work: which roles may prepare, review, and hold liability for each type of work

"TA Dashboard JTBDs" describes a two-tier split. The TA owner, or Berufsträger, carries liability, does QA, and gives final approval. TA staff, or Sachbearbeiter, prepares cases and talks to clients. A four-eyes check happens before anything goes to DATEV or filing.

This matches how the agentic MVP treats AI: prepare and review, never decide.

Partially answered. Nothing defines where freelancers or Minijobber roles, both named in the leadership message, fit into this two-tier model.

## 6. Cross-practice case handling: can one case be handled by more than one practice, and under what mandate, liability, and data-access rules

No. Each case binds to a single providerID at assignment. A Monitor team Slack thread says there is currently no way to even reassign a case to a different advisor through Monitor, let alone split it across two. No mandate, liability, or data-access model for multi-practice work exists anywhere in Notion.

Answered, and the gap is bigger than the strategy doc implies. This isn't an unresolved policy question. The system can't do single-practice reassignment yet, so splitting across practices is further out than a decision away.

## 7. Contract, pricing, and payout model: routed cases vs. a TA's own clients

A Q3 2026 planning item says Monitor doesn't yet reflect the process in the updated T&Cs and TA contracts, and calls the mismatch a legal and operational risk.

Payment timing for routed cases is still being decided: paid at invoice, or paid at subscription expiry. Discounts can only come out of the company's share, never the TA's share.

Advisor-facing billing, meaning charging Kanzleien and paying advisors, is explicitly scoped for 2027, not before.

Answered as a live risk, not just an open question. Payout mechanics for a TA's own, white-label clients don't exist anywhere yet.

## 8. White-label timing: does it need to launch before 200 TAs, or only later while scaling toward 1,000

Every dated source agrees: white-label starts Q1 2027, after the 2026 push and alongside the climb toward 1,000.

Answered. It is not a prerequisite for reaching 200.

## What's worth flagging to leadership

- The "200 by end of year" framing in the leadership message doesn't match the internal plan's own 100 to 300 range for EOY 2026.
- The contracts and payouts gap isn't a decision waiting to be made. It's a live mismatch between signed TA contracts and what Monitor actually does today.
- CaseOps is in delivery. TalentOps is one quarter behind in discovery, with no named owner beyond Product. Confirm whether that's the intended sequencing or whether TalentOps needs to be pulled forward and staffed to hit any TA count by end of year.
