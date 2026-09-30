# 33. Mary's one-job shelf -- Mary re-score (guide v1.1, concept fit)

- Catalog ID: 33 | Name: Mary's one-job shelf | Group: Structures | Status: hopper
- Assessed product version: Catalog version: tiny ruthless catalog of one-job kits labeled by job (not guru), self-serve; start with a few real kits ($29-79), add only after demand; buyers: midnight operators first, agencies/chambers as distributors later.
- Reviewer: Mary | Date: 2026-09-30 | Guide: v1.1 (concept fit)
- Rubric v1.1: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product-rubric.md
- Definition: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product.md
- Scoring guide: https://app.notion.com/p/3eba3e33d58181f8add6e84f8ee733bd
- Catalog source: main @ 8be7c589928ef681577baaa765a90583d824f128

## Offer snapshot
- Buyer/payer: Operators who buy at midnight (blunt buyers); later agencies/chambers as distributors.
- Offer: Fixed one-job kits, each labeled by the job it does; a shelf (catalog + customer list + transaction history) that becomes a product line.
- Delivery: Digital self-serve purchase and download.
- Price hypothesis (working assumption, not verified willingness-to-pay): $29-79 per kit (unvalidated).
- Repeat mechanism: Buyer returns for the next job's kit; irregular multi-kit purchases; no subscription.
- Founder's role: Architect/curator of the shelf (which kits earn a slot) at asset level; operators + AI build kits; never in per-client path.
- Primary satisfaction shape: Tool in the hand

## Material assumptions (labelled)
- A-fixed: kits stay fixed-scope and one-job; no custom creep.
- A-demand: kits are added only after demand (documented rule).
- A-price: $29-79 unvalidated; distributor channel is future, not secured.

## Source documents
- `docs/hopper/marys-shelf.md`
- `docs/perspectives/mary.md`

## Per-bar scores

| Bar | Score | Confidence | Reason | Basis | Main limitation |
| --- | --- | --- | --- | --- | --- |
| B1 Pays more than once | 1 | M | Repeat purchases ('come back for the next job') are plausible and the operator market is broad, but recurrence is irregular with no subscription mechanism. | inference | No recurring mechanism; irregular return visits. |
| B2 Build once, sell many | 2 | M | Each kit built once and sold many times; digital delivery, bounded support; credible margin under stated assumptions. | inference | Acquisition cost unproven; cheap copying alone does not establish margin. |
| B3 Creates Gold | 2 | M | The shelf itself -- catalog IP, customer list, transaction history -- accumulates with operation and transfers to a buyer as a product line. | inference | Asset value depends on kits staying one-job. |
| B4 Runs without you | 2 | M | Self-serve catalog with automated fulfillment; a trained operator runs it; Jack curates which kits earn a slot (asset-level). | inference | Operating model unbuilt. |
| B5 Satisfaction shape | 2 | M | Tool in the hand by design: 'competence on first use, not coaching'; fixed scope and job-labeling make the satisfaction credible. | inference | Assumes kits stay fixed-scope. |
| B6 No Brainer | 2 | M | Specific buyer (midnight operators), recognizable buying moment (the job is in front of them), small price, no explanation needed. | assumption | Buyer persona and willingness-to-pay unproven. |
| B7 C3PO (AI does the work) | 2 | M | AI + operators build kits once; automated delivery; humans for verification/exceptions; growth needs no fulfillment headcount. | inference | Kit-production split named, not fully specified. |
| B8 Natural route to buyers | 1 | L | Distributor channel (agencies/chambers) named but future; initial route to midnight operators unspecified. | assumption | No owned channel documented; access not secured. |
| B9 Easy to get the value | 2 | M | Self-serve buy, download, do the job; effort is the expected experience and minimal. | inference | Assumes kits are truly one-job. |
| B10 Newton's Rule | 2 | M | Bigger catalog = more reasons to visit (assortment gravity); transaction data shows what to build next; each kit amortizes the platform. | inference | Assortment effect is real but modest. |

## Coverage, total, zeros
- Coverage: 10/10 bars assessed | Concept-fit total: 18/20 concept fit | Twos: 8 | Zeros: 0
- Every zero: none

## Sensitivities
- B8 (Natural route to buyers): scored 1 on assumption with L confidence -- No owned channel documented; access not secured.

## Useful improvements (separate note; does not revive a rejected offer)
Useful improvement: name the first acquisition route for midnight operators (search? marketplace? partner?) with its access requirement; that is the single biggest unlock for B8 and B2.

## Unresolved questions
- The first channel to midnight operators: who controls it, why they'd participate, what access requires.

## Overall interpretation
Reaches the shortlist signal (18/20, eight 2s, no zeros). The concept is coherent end-to-end; the single gating unknown is distribution -- B8 is the key sensitivity, and a named first channel would confirm or break the thesis.

## Changes vs Mary's original assessment (2026-09-30, old evidence standard)
Original scores: `docs/scores/mary-2026-09-30/index.csv` (preserved untouched).

- b1: 2->1 -- No subscription mechanism; 'come back for the next job' is plausible but irregular -- subscription label rules cut both ways.
- b3: 1->2 -- Concept-fit: the shelf (catalog IP + customer list + transaction history) is a named transferable asset.
- b4: 1->2 -- Concept-fit: self-serve + automated fulfillment is a realistic operator-run model.
- b5: U->2 -- Fixed-scope, job-labeled design credibly delivers tool-in-hand.
- b6: U->2 -- Specific buyer, recognizable moment, small price.
- b7: U->2 -- AI/operator production with automated delivery; no per-buyer fulfillment.
- b8: U->1 -- Distributor channel named but future; initial route unspecified.
- b9: 1->2 -- Minimal effort for the intended buyer.
- b10: U->2 -- Assortment gravity + transaction-data loop are specific scale mechanisms.

_Concept-fit mode: an unbuilt idea can be scored from documented design + business logic + labelled assumptions. U only where a missing detail materially prevents judgment. A concept score is not proof of demand or operating results; scores alone never authorize outreach, tests, building, or spending._