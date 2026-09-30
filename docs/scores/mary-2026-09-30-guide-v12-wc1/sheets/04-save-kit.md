# 04. Save Kit -- Mary re-score (guide v1.2, WC1 concept fit)

- Catalog ID: 04 | Name: Save Kit | Group: Products | Status: hopper
- Legacy ID (v1): 08
- Assessed product version: WC1 -- Working scenario proposed by Cody, authorized by Jack (2026-09-30): proposed business design to make the concept assessable, not customer evidence or a launch decision.
- Reviewer: Mary | Date: 2026-09-30 | Guide: v1.2 (concept fit)
- Rubric v1.1: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product-rubric.md
- Definition: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product.md
- Scoring guide (v1.2): https://app.notion.com/p/3eba3e33d58181d19eabc5d62f6401f4
- Catalog source: catalog v2 @ bce3647216bbb101be6ffb4127d8f69e1c61f585

## Offer snapshot
- Buyer/payer: Agencies with retainer clients who churn on 'what am I paying for?'
- Offer: Self-serve proof-packet tool: one click assembles a white-labeled 'here's everything we've done' packet from the agency's own client exports at the churn moment.
- Delivery: Software tool; agency connects/uploads its own exports, maps metrics, generates and verifies each packet.
- Price hypothesis (working assumption, not verified willingness-to-pay): $99/month working price (unvalidated).
- Repeat mechanism: Monthly access supports repeated client review and cancellation events; ongoing value depends on having enough client accounts to use it regularly.
- Founder's role: Occasional product oversight; 0-2 hrs/week. Jack's recorded objections to the Retention Engine stand as buying objections, not a kill of this concept.
- Primary satisfaction shape: Tool in the hand

## Material assumptions (labelled)
- A-int: per-agency data integration is feasible with bounded setup effort.
- A-trig: the churn moment is as acute and frequent as described.
- A-obj: Jack's 'selling agencies their own job' objection is a buying objection capping B6, not a model kill.

## Source documents
- `docs/products/entries/04-save-kit.md`
- `docs/products/assessment-context.md`
- `docs/perspectives/mary.md`

## Per-bar scores

| Bar | Score | Confidence | Reason | Basis | Main limitation |
| --- | --- | --- | --- | --- | --- |
| B1 Pays more than once | 1 | M | Monthly access matches recurring client-review and cancellation events, but value depends on having enough accounts; lumpy usage invites quiet-month cancellation. | source | Insurance-style renewal; usage lumpiness. |
| B2 Build once, sell many | 1 | M | The packet engine is reusable, but inconsistent exports, account mapping and disputed metrics add real per-account support and QA costs. | source | Per-account data work caps build-once leverage. |
| B3 Creates Gold (transferable asset) | 2 | M | Owned packet software, templates and permissioned outcome records can transfer; clients retain rights to underlying data. | inference | Dataset value depends on volume and permissions. |
| B4 Runs without you | 2 | M | A product operator handles access and incidents; the agency signs off each packet; Jack is occasional oversight. | source | Steady-state operator model assumed. |
| B5 Satisfaction shape | 1 | M | The agency produces a clear answer to 'what did you do?' before a client meeting, but a packet cannot rescue poor underlying results. | source | Probabilistic outcome: the save is not guaranteed. |
| B6 No Brainer | 1 | M | A cancellation threat is an acute trigger at a tiny price vs a saved retainer, but built-in reports and AI summaries compete and Jack's recorded objection is a real buying objection. | source | Buyer may insist the save is their job. |
| B7 C3PO (AI does the work) | 1 | M | AI assembles and explains supplied metrics, but agency humans must verify each client's attribution and claims; per-client verification remains material. | source | Per-customer setup/verification burden. |
| B8 Natural route to buyers | 1 | L | Agency operations educators could demonstrate packets and refer users for a share; data-access concerns and competing reporting tools complicate adoption. | assumption | No owned channel documented. |
| B9 Easy to get the value | 1 | M | Connect or upload, map metrics, generate, verify and present; value arrives at the next review, after meaningful data preparation. | source | Setup friction for the intended buyer. |
| B10 Newton's Rule (scale advantage) | 1 | M | Shared software spreads fixed costs, but customer-specific data failures and integrations can make support grow alongside adoption. | source | Support scaling weakens the scale story. |

## Coverage, total, zeros
- Coverage: 10/10 bars assessed | Concept-fit total: 12/20 | Twos: 2 | Zeros: 0
- Every zero: none

## Sensitivities
- B2 (Build once, sell many): scored 1 on source with M confidence -- per-account QA costs are documented.
- B10 (Newton's Rule): scored 1 on source with M confidence -- support can grow with adoption.
- B6 (No Brainer): scored 1 on source with M confidence -- Jack's recorded buying objection.

## Useful improvements (separate note; does not revive a rejected offer)
- Bound the data-integration spec (which sources, how long, who maps); that single spec moves B2/B7/B9 together.

## Unresolved questions
- Per-agency integration cost and who bears it.
- Whether agencies buy a save-weapon or insist the save is their job.
- WTP at $99/month.

## Overall interpretation
WC1 makes this scenario materially harder than the original pitch: per-account export/mapping/QA costs and agency-side verification are now explicit, which moves B2 and B10 down. The concept still hangs together (acute trigger, dataset moat, operator-run), but the gating unknowns are integration cost and the recorded buying objection -- both researchable without building.

