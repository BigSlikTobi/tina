# Todo Before Building the MVP

- Job ID: ADV-MORNING-001
- Status: Open checklist
- Owner: Product
- Updated: 2026-07-21
- Source: [Agentic MVP](agentic_mvp.md#what-is-already-defined-and-what-remains-open), [Metrics and gates](metrics_learning.md), and [War game](war_game.md)

## What this list means

The MVP scope is already decided.

This list contains the work needed before Metrics Gate G001 can approve the build. It does not ask
us to redefine the user, Kano Matrix, product scope, or gate structure.

## Checklist

- [ ] **Observe five normal Advisor workdays.**
  Record which systems Advisors use, what changes during the day, what gets missed, and where time
  is spent on coordination.

- [ ] **Define the connected-source contract.**
  Name the exact DATEV data, task-list system, and Taxfix systems. Define ownership, freshness,
  synchronization, read-only actions, and any human handoff. This closes MVP-O020.

- [ ] **Define the first bookkeeping case.**
  Fix the client type, one-month period, meaning of low document volume, required fields, and
  exclusions. This is part of MVP-O021.

- [ ] **Create the gold answer pack.**
  Define the expected matches, unmatched items, missing evidence, conflicts, unresolved work,
  source links, and correct ready or not-ready result. This completes MVP-O021.

- [ ] **Define required evidence and document support.**
  List the required bank, invoice, ledger, and e-invoice types. For each subtype, define the fields
  to read, source proof, safe handling, and the result when it cannot be handled. This closes
  MVP-O022.

- [ ] **Define the human-operated downstream handoff.**
  Name the action, destination, responsible person, package contents, receipt, success states,
  correction path, and unknown-result rule. This closes MVP-O023.

- [ ] **Name the people who will run the gate.**
  Name the sponsor, participating Advisors, Domain approver, Product owner, and responsible
  Engineering, Execution Safety, Security/Privacy, Operations, Research, and GTM people. Confirm
  their access and stop rights. This closes MVP-O024. It does not redefine the product user.

- [ ] **Set the test thresholds and replay volume.**
  Use the five-day baseline to set the numeric success limits and minimum number of synthetic cases.
  Record them before replay results are seen. This closes MVP-O026.

- [ ] **Clean up the dependent documents.**
  Remove or mark stale current-build limits, separate PDF-reader assumptions, GFR-only handoff
  wording, and old client-chat or calendar scope in Metrics, GTM, Vision, and the context overlay.
  Keep SOTA as As-Is and market analysis only.

- [ ] **Create the canonical JTBD dossier.**
  Put lifecycle status, gate decisions, owners, and approved scope in one canonical place. This is
  documentation control. It does not reopen confirmed MVP decisions.

- [ ] **Run Metrics Gate G001.**
  Product makes the final build decision. Domain, Advisors, and the responsible control owners may
  stop the gate in their areas. A passed G001 approves build only. It does not approve real client
  data, broader authority, or launch.

## Not required before the first build

- Email integration.
- General calendar integration.
- Client chat or AI-written client messages.
- DATEV write automation.
- Real-client data or its provider contract.
- Partner rollout and open-market launch.
- Customer pricing.
- Full scale and unit-economics proof.

These items have later gates. They should not block the first synthetic MVP build.
