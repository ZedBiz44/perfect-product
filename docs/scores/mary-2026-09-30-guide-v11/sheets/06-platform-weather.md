# 6. Platform Weather -- Mary re-score (guide v1.1, concept fit)

- Catalog ID: 06 | Name: Platform Weather | Group: Products | Status: hopper
- Assessed product version: Catalog version: early warning + white-labeled client comms when Meta/Google/Twilio/GHL storms hit agency clients; monitor enforcement waves, alert agencies, ship pre-written comms and fixes; archive waves as dataset; ~$49-149/mo. Positioned as reputation armor, not generic news.
- Reviewer: Mary | Date: 2026-09-30 | Guide: v1.1 (concept fit)
- Rubric v1.1: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product-rubric.md
- Definition: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product.md
- Scoring guide: https://app.notion.com/p/3eba3e33d58181f8add6e84f8ee733bd
- Catalog source: main @ 8be7c589928ef681577baaa765a90583d824f128

## Offer snapshot
- Buyer/payer: GHL/marketing agencies built on rented platforms (broader later).
- Offer: Early warning of platform enforcement waves plus ready-to-send client communications and fixes.
- Delivery: Digital alerts + comms library; automated monitoring, human-reviewed.
- Price hypothesis (working assumption, not verified willingness-to-pay): ~$49-149/mo (unvalidated).
- Repeat mechanism: Monthly subscription with insurance logic: platform storms recur, agencies stay covered.
- Founder's role: Not in the path: fleet monitors, drafts, alerts; operators run the system; Jack curates at asset level.
- Primary satisfaction shape: Tool in the hand

## Material assumptions (labelled)
- A-monitor: enforcement waves are detectable early enough to warn (monitoring assumed effective).
- A-price: unvalidated; platform-enforcement pain is documented in owner-language research.

## Source documents
- `docs/perspectives/mary.md`
- `docs/ingredients.md`

## Per-bar scores

| Bar | Score | Confidence | Reason | Basis | Main limitation |
| --- | --- | --- | --- | --- | --- |
| B1 Pays more than once | 1 | M | Insurance logic is real (storms recur), but quiet periods invite cancellation; subscription label alone does not renew. | assumption | Cancellation risk in quiet periods. |
| B2 Build once, sell many | 2 | M | One monitoring system + comms library sold to many agencies; digital; shared production; credible margin. | inference | Acquisition cost unproven. |
| B3 Creates Gold | 2 | M | The wave archive + comms library is a named, ownable, appreciating, transferable dataset asset. | inference | Archive value depends on wave frequency. |
| B4 Runs without you | 2 | M | Fleet monitors, AI drafts comms, humans review; alerts automated -- a realistic operator-run model with Jack out of the path. | inference | Monitoring effectiveness assumed. |
| B5 Satisfaction shape | 2 | M | Tool-in-hand at the moment of need: warning + ready comms = the agency acts fast and looks professional; calm during a storm is the felt result. | inference | Depends on warning lead time. |
| B6 No Brainer | 2 | M | Specific buyer, documented painful problem (platform-enforcement risk), acute trigger (a wave hits), tiny price vs lost clients. | source | Willingness-to-pay unproven; assumed demand. |
| B7 C3PO (AI does the work) | 2 | M | AI monitors and drafts (core work); humans verify waves and review comms; exceptions only. | inference | Monitoring/drafting split assumed workable. |
| B8 Natural route to buyers | 1 | L | Plausible agency routes (communities, GHL ecosystem) but no documented owned access. | assumption | Access not secured. |
| B9 Easy to get the value | 2 | M | Agency receives alert + pre-written comms and sends to clients; effort clear and small. | inference | Agency must act on the alert (usage). |
| B10 Newton's Rule | 2 | M | More agencies = more wave reports = earlier, better warnings (network data effect); comms library grows with each wave. | inference | Network effect needs participation. |

## Coverage, total, zeros
- Coverage: 10/10 bars assessed | Concept-fit total: 18/20 concept fit | Twos: 8 | Zeros: 0
- Every zero: none

## Sensitivities
- B1 (Pays more than once): scored 1 on assumption with M confidence -- Cancellation risk in quiet periods.
- B8 (Natural route to buyers): scored 1 on assumption with L confidence -- Access not secured.

## Useful improvements (separate note; does not revive a rejected offer)
Useful improvement: define the detection spec (which signals, what lead time) -- that single spec moves B5/B7 together.

## Unresolved questions
- How early waves are actually detectable.
- Which channel reaches platform-dependent agencies first.

## Overall interpretation
Reaches the shortlist signal (18/20, eight 2s, no zeros). The thesis is unusually specific: a documented pain, an acute trigger, a dataset moat, and a network effect. Key sensitivities: B1 quiet-period retention and B8 channel access.

## Changes vs Mary's original assessment (2026-09-30, old evidence standard)
Original scores: `docs/scores/mary-2026-09-30/index.csv` (preserved untouched).

- b1: 2->1 -- Insurance logic is real but quiet-period cancellation risk is a meaningful limitation.
- b3: 1->2 -- Concept-fit: the wave archive is a named appreciating dataset.
- b4: 1->2 -- Concept-fit: monitor/draft/alert pipeline is a realistic operator-run model.
- b5: U->2 -- Warning + ready comms credibly delivers the tool-in-hand result.
- b6: U->2 -- Documented pain, acute trigger, price-to-benefit all assessable.
- b7: U->2 -- AI monitoring/drafting is the core work; humans verify.
- b9: 1->2 -- Clear small-effort path for the intended buyer.
- b10: U->2 -- Network data effect across agencies is a specific scale mechanism.

_Concept-fit mode: an unbuilt idea can be scored from documented design + business logic + labelled assumptions. U only where a missing detail materially prevents judgment. A concept score is not proof of demand or operating results; scores alone never authorize outreach, tests, building, or spending._