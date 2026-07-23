# 🛡️ War game (we tried to break it)

> 🛡️ **Outcome.** We attacked the whole design, twice. No kill shot survived. The gate stays hold, then narrow.

## What happened
We tried to break the design first in the abstract, then with its feet on the ground.
Round one attacked the WoW MVP as a greenfield proposition: can a full-day workbench and one deep bookkeeping-period job coexist without becoming a fuzzy promise, a duplicate system of record, or a very polished demo with no safe path to value? The answer was uncomfortable but not fatal: the job is real, the control layer has a legal reason to exist, and too much of the proof contract was still implicit.
Round two put the same attack deck against the real, in-build SE-DIFM architecture: GFR, FinAPI, DATEV/ELSTER, Taxfix surfaces, one launch Steuerberater, actual Buchungsprofil boundaries, actual review rules, actual operating constraints. That is where the war game got properly sharp.
It surfaced two dramatic-looking kill shots. Neither survived contact with the decision record:
- We build **vendor-agnostic**, against clean APIs. GFR, FinAPI and DATEV are reference integrations behind adapters — not a second product smuggled into the MVP, and not a lock-in disguised as a roadmap.
- The current prototype and its model configuration are **out of scope**. We judge the plan and its architecture, not a PoC that neither proves nor constrains the MVP.
Once those corrections were made, the alleged product-shape failure disappeared. What remained was harder and more useful: a set of requirements that must be designed in, measured honestly, and closed at the right gate.

## What it did give us
Not permission to relax. A cleaner definition of what must be true and when.
Three things are real prerequisites for live operation, correctly parked at later gates rather than pretended away:
- **Reviewer failover.** A single Berufsträger is not a launch model. Before controlled live, there must be a second qualified reviewer / §69 representation path, an absence rule, and a hard ceiling on what one signer can safely carry.
- **Filing authority.** The MVP can prepare and route; it cannot claim to complete a filing until Untervollmacht, Unterberaternummer, sanctioned DATEV access and ELSTER-confirmation reconciliation are actually in place.
- **Security ownership.** Before real client data, someone named must own the provider allowlist, signed DPAs/AVVs, retention boundaries and the Art. 33 incident clock. "Legal will handle it" is not an operating model.
And it made the build contract less romantic, more concrete:
- The execution layer governs, verifies and source-links the bookkeeping engine's output. It does not rebuild bookkeeping computation for the pleasure of feeling independent.
- Every source-derived signal needs freshness: poll-age, a maximum staleness rule, and a fail-closed path when the desk cannot honestly say "ready."
- The first Buchungsprofil is a boundary, not a suggestion. Hard exclusions must refuse upstream; missing Ausgangsrechnungen need a real human-ops recovery path, not a sad blocked state.
- PDFs, bank feeds and e-invoices arrive as evidence — and as untrusted input. EN-16931 needs parse-or-stop; document text stays out of the instruction channel.
- Replay needs to prove something connected to the business: fixed denominators, live calibration, cost per case, downstream error latency. A high match rate without a denominator is theatre.
That is the useful pressure from the exercise: no grand re-scope, no fake certainty, no escape hatch. Just a narrower proof contract and a more adult design.

## Status
**Gate: hold, then narrow. Not kill.**
Hold means: do not wave this through on optimism, a strong demo, or vendor names. Narrow means: keep the product shape, reduce the claim surface, and make the next proof deliberately smaller and harder to cheat.
The job is real. The four-eyes workbench is not decorative; it is where professional accountability lives. The bookkeeping-period job has a bounded first cohort. The vendor-neutral architecture is a decision that now has to earn its keep in interfaces, data boundaries and integration sequencing.
The earlier drama came from bad framing: treating reference integrations as lock-in, and treating an out-of-scope PoC as the product verdict. Correct those, and there is no kill shot. There is still work. The right next move is to build the vendor-agnostic MVP under the tighter contract then earn the right to cross into replay, real data and controlled live one gate at a time.

- [War game (full document)](https://app.notion.com/p/3a439357d84781d395fdee0eb5003e9a)
- [War game (thought process)](https://app.notion.com/p/3a439357d8478121a6b3f1b7e4dc2cae)
- [War game (transcript)](https://app.notion.com/p/3a639357d8478180b6e7ede4be7fec79)
