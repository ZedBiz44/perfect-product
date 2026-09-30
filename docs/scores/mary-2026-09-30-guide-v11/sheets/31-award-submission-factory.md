# 31. Award-Submission Factory -- Mary re-score (guide v1.1, concept fit)

- Catalog ID: 31 | Name: Award-Submission Factory | Group: Products | Status: dead-but-ingredient
- Assessed product version: Catalog version (killed): turn agency GHL data into polished case studies + award packets quarterly; fleet converts raw data to white-labeled proof packets for award occasions; quarterly pack ~$199-499 (unstated guess). Kill reason: award occasion unsupported. Salvage = proof-asset factory at churn moment (#8).
- Reviewer: Mary | Date: 2026-09-30 | Guide: v1.1 (concept fit)
- Rubric v1.1: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product-rubric.md
- Definition: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product.md
- Scoring guide: https://app.notion.com/p/3eba3e33d58181d19eabc5d62f6401f4
- Catalog source: main @ 8be7c589928ef681577baaa765a90583d824f128

## Offer snapshot
- Buyer/payer: Agencies seeking awards/proof.
- Offer: Quarterly white-labeled proof/award packets from the agency's own data.
- Delivery: Digital packets; fleet converts raw data.
- Price hypothesis (working assumption, not verified willingness-to-pay): Quarterly pack ~$199-499 (unstated guess).
- Repeat mechanism: Quarterly packs; irregular.
- Founder's role: Not in the path: fleet does the conversion; operators run it.
- Primary satisfaction shape: Trophy

## Material assumptions (labelled)
- A-dead: status preserved -- killed; salvage is the proof-asset-at-churn-moment (#8).
- A-kill: 'award occasion unsupported' is the documented buying objection.

## Source documents
- `docs/perspectives/mary.md`

## Per-bar scores

| Bar | Score | Confidence | Reason | Basis | Main limitation |
| --- | --- | --- | --- | --- | --- |
| B1 Pays more than once | 1 | M | Quarterly repeat occasions exist in principle, but the award occasion itself is unsupported -- irregular and weak. | source | Occasion unsupported. |
| B2 Build once, sell many | 2 | M | Process built once; per-agency data conversion is per-client work -- reuse real, customization meaningful. | inference | Per-client data work. |
| B3 Creates Gold | 1 | M | Proof-asset templates ownable but modest; limited. | inference | Limited. |
| B4 Runs without you | 1 | M | Fleet converts data with operators running it; credible path to systematize, but per-packet data wrangling needs humans. | assumption | Per-packet human work. |
| B5 Satisfaction shape | 1 | M | Trophy satisfaction is real for award-seekers, but the award occasion is unsupported -- the promise floats without a trigger. | source | No occasion. |
| B6 No Brainer | 0 | H | Killed: the award occasion is unsupported -- no credible buying trigger; the offer lacks practical buying value. Documented conflict. | source | Kill reason. |
| B7 C3PO (AI does the work) | 1 | M | AI converts data to packets meaningfully, but per-agency data wrangling stays human. | assumption | Human data work per packet. |
| B8 Natural route to buyers | 1 | L | The route to agencies exists; the problem is the offer's missing occasion, not the route. | inference | Offer rejected; route plausible. |
| B9 Easy to get the value | 1 | M | Agency submits data, receives packet -- manageable, but data submission is friction. | inference | Submission friction. |
| B10 Newton's Rule | 1 | M | More packets sharpen templates; limited scale mechanism. | assumption | Limited. |

## Coverage, total, zeros
- Coverage: 10/10 bars assessed | Concept-fit total: 10/20 concept fit | Twos: 1 | Zeros: 1
- Every zero: B6

## Sensitivities
- B4 (Runs without you): scored 1 on assumption with M confidence -- Per-packet human work.
- B7 (C3PO (AI does the work)): scored 1 on assumption with M confidence -- Human data work per packet.
- B8 (Natural route to buyers): scored 1 on inference with L confidence -- Offer rejected; route plausible.
- B10 (Newton's Rule): scored 1 on assumption with M confidence -- Limited.

## Useful improvements (separate note; does not revive a rejected offer)
Useful improvement (does not revive the offer): the salvage already happened -- proof assets at the churn moment (#8); score that instead.

## Unresolved questions
- None -- killed; the open work is #8.

## Overall interpretation
One zero (B6) records the kill: no award occasion, no buying trigger. Production is feasible -- which is why the proof-asset machinery was salvaged into #8, where a real trigger (churn) exists.

## Changes vs Mary's original assessment (2026-09-30, old evidence standard)
Original scores: `docs/scores/mary-2026-09-30/index.csv` (preserved untouched).

- b2: 1 kept -- No change.
- b5: U->1 -- Trophy promise assessable; capped by the unsupported occasion.
- b6: 0 kept -- No change; kill reason stands.
- b7: U->1 -- AI conversion meaningful; human data work.
- b8: U->1 -- Route plausible; the occasion (not the route) is the problem.
- b10: U->1 -- Limited.

_Concept-fit mode: an unbuilt idea can be scored from documented design + business logic + labelled assumptions. U only where a missing detail materially prevents judgment. A concept score is not proof of demand or operating results; scores alone never authorize outreach, tests, building, or spending._