# 39. Collective purchasing engine -- Mary re-score (guide v1.2, WC1.1 concept fit)

- Catalog ID: 39 | Name: Collective purchasing engine | Group: Structures | Status: exploration
- Legacy ID (v1): 41
- Assessed product version: WC1.1 -- WC1.1 per Jack's recorded clarification (2026-09-30), superseding Cody's illustrative scenarios: proposed business design, not customer evidence or a launch decision.
- Reviewer: Mary | Date: 2026-09-30 | Guide: v1.2 (concept fit)
- Rubric v1.1: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product-rubric.md
- Definition: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product.md
- Scoring guide (v1.2): https://app.notion.com/p/3eba3e33d58181d19eabc5d62f6401f4
- Catalog numbering reference: v2 @ bce3647216bbb101be6ffb4127d8f69e1c61f585 (numbering migration only).
- Working-concept reference verified by Cody, 2026-10-02: [WC1 / WC1.1 catalog snapshot](https://github.com/ZedBiz44/perfect-product/tree/6ea8ec21ad60716e11667c353b796f957265147a/docs/products). This snapshot contains the declared working concepts. Mary’s exact originally accessed working-concept commit was not recorded; this correction does not certify it or alter her assumptions, scores, reasons or confidence.

## Offer snapshot
- Buyer/payer: Local businesses / operators buying together (cooperative-services variant).
- Offer: Vendasta-style shelf: curated supplier directory, group buying power, quarterly deal drops and concierge setup; members buy together, the engine negotiates.
- Delivery: Directory + deal drops; operator curates suppliers and negotiates; concierge handles setup.
- Price hypothesis (working assumption, not verified willingness-to-pay): Membership/participation pricing (unvalidated).
- Repeat mechanism: Quarterly deal drops and ongoing supplier savings give members a continuing reason to stay in the buying group.
- Founder's role: Sets curation standards; 0-2 hrs/week.
- Primary satisfaction shape: Tool in the hand (supporting: plus Harvest Gala (the group-deal win))

## Material assumptions (labelled)
- A-coop: assessed as the cooperative-services variant per WC1.1, not a two-sided marketplace.
- A-supp: suppliers offer genuine group discounts worth the coordination.
- A-price: unvalidated.

## Source documents
- `docs/products/entries/39-collective-purchasing-engine.md`
- `docs/products/assessment-context.md`

## Per-bar scores

| Bar | Score | Confidence | Reason | Basis | Main limitation |
| --- | --- | --- | --- | --- | --- |
| B1 Pays more than once | 2 | M | Quarterly deal drops and ongoing supplier savings give members a continuing reason to stay in the buying group. | source | Deal-driven recurrence. |
| B2 Build once, sell many | 1 | M | Deal mechanics are reused, but supplier curation, negotiation and concierge setup recur per cycle. | source | Per-cycle negotiation caps build-once leverage. |
| B3 Creates Gold (transferable asset) | 2 | M | Owned supplier relationships, deal history and buying-group membership accumulate as transferable assets. | inference | Supplier network appreciates. |
| B4 Runs without you | 1 | M | An operator curates and negotiates; Jack sets standards -- but supplier relations and concierge work are ongoing. | source | Ongoing supplier/concierge load caps B4. |
| B5 Satisfaction shape | 1 | M | A member saves real money on a needed purchase; the group-deal win is the harvest, but it depends on deal quality each cycle. | source | Deal-quality dependence. |
| B6 No Brainer | 2 | M | A needed purchase with a visible group discount is a strong trigger; the member buys something they already intended to buy, cheaper. | source | Already-intended purchase, cheaper. |
| B7 C3PO (AI does the work) | 1 | M | AI matches members to deals and drafts communications; humans negotiate with suppliers and handle concierge setup. | source | Human negotiation is the core. |
| B8 Natural route to buyers | 1 | M | Trade groups and buying cooperatives can refer members for a share; supplier participation and member recruitment are unproven. | assumption | Both sides of the route unproven. |
| B9 Easy to get the value | 1 | M | Member joins, browses deals, claims a discount and completes the purchase; value depends on relevant deals being available. | source | Deal availability gates value. |
| B10 Newton's Rule (scale advantage) | 2 | M | More members strengthen negotiating power and spread curation cost -- the buying group genuinely improves with scale. | source | Network effect is real here. |

## Coverage, total, zeros
- Coverage: 10/10 bars assessed | Concept-fit total: 14/20 | Twos: 4 | Zeros: 0
- Every zero: none

## Sensitivities
- B1 (Pays more than once): resolved U->2 -- WC1.1: quarterly deal drops are a concrete recurrence mechanism.
- B6 (No Brainer): resolved U->2 -- WC1.1: already-intended purchase, cheaper, is a strong trigger.
- B10 (Newton's Rule): scored 2 on source with M confidence -- negotiating power genuinely improves with scale.

## Useful improvements (separate note; does not revive a rejected offer)
- Sign the first supplier deals before recruiting members; the shelf without deals is an empty directory.

## Unresolved questions
- Supplier willingness to discount.
- Member recruitment cost.
- WTP / fee structure.

## Overall interpretation
WC1.1's Vendasta-style cooperative variant is what makes this assessable: quarterly deal drops (B1=2), the already-intended-purchase trigger (B6=2), and a genuine network effect on negotiating power (B10=2). The risk is all execution -- supplier deals must exist before members arrive. 14/20, no zeros.

