# 06. Platform Weather -- Mary re-score (guide v1.2, WC1 concept fit)

- Catalog ID: 06 | Name: Platform Weather | Group: Products | Status: hopper
- Legacy ID (v1): 11
- Assessed product version: WC1 -- Working scenario proposed by Cody, authorized by Jack (2026-09-30): proposed business design to make the concept assessable, not customer evidence or a launch decision.
- Reviewer: Mary | Date: 2026-09-30 | Guide: v1.2 (concept fit)
- Rubric v1.1: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product-rubric.md
- Definition: https://github.com/ZedBiz44/perfect-product/blob/8be7c589928ef681577baaa765a90583d824f128/docs/framework/perfect-product.md
- Scoring guide (v1.2): https://app.notion.com/p/3eba3e33d58181d19eabc5d62f6401f4
- Catalog source: catalog v2 @ bce3647216bbb101be6ffb4127d8f69e1c61f585

## Offer snapshot
- Buyer/payer: GHL/marketing agencies built on rented platforms (Meta/Google/Twilio/GHL).
- Offer: Early-warning subscription: monitored enforcement waves and outages plus pre-written white-labeled client comms and fixes; incident archive as dataset.
- Delivery: Alert subscription; operator verifies incidents and sends notices on an escalation rota.
- Price hypothesis (working assumption, not verified willingness-to-pay): $99/month working price inside the recorded $49-149 band (unvalidated).
- Repeat mechanism: New outages and policy changes continually recreate the monitoring and client-communication job, giving subscribers a reason to retain coverage.
- Founder's role: Occasional policy decisions; 0-2 hrs/week.
- Primary satisfaction shape: Tool in the hand

## Material assumptions (labelled)
- A-mon: reliable monitoring with acceptable false-alarm rates is achievable.
- A-syn: the synthesis adds value beyond free status pages and peer groups.
- A-price: $99/month unvalidated.

## Source documents
- `docs/products/entries/06-platform-weather.md`
- `docs/products/assessment-context.md`
- `docs/perspectives/mary.md`

## Per-bar scores

| Bar | Score | Confidence | Reason | Basis | Main limitation |
| --- | --- | --- | --- | --- | --- |
| B1 Pays more than once | 1 | M | Outages and policy changes continually recreate the job, but quiet periods carry insurance-style cancellation risk. | source | Value arrives only when a covered incident occurs. |
| B2 Build once, sell many | 2 | M | One verified alert serves many agencies; monitoring, false alarms and editorial availability are significant ongoing costs but not per-buyer. | source | Ongoing costs are operating costs, not per-sale. |
| B3 Creates Gold (transferable asset) | 2 | M | An owned incident archive, taxonomy, communication templates and subscriber relationships accumulate; source rights and provenance must be maintained. | inference | Archive appreciates with incident history. |
| B4 Runs without you | 2 | M | A monitoring operator verifies incidents and sends notices on an escalation rota; Jack is occasional policy input. | source | Operator-run; no founder in the path. |
| B5 Satisfaction shape | 2 | M | An agency identifies an incident and sends a clear client message promptly; the usable message and avoided confusion provide immediate competence. | source | Reputation armor, not generic news. |
| B6 No Brainer | 2 | M | An active outage makes the need obvious at a tiny price vs lost clients; the bar is that $99 must buy useful synthesis beyond repeating notices. | source | Specific buyer, acute trigger, small price. |
| B7 C3PO (AI does the work) | 2 | M | AI collects signals, clusters incidents and drafts notices; humans verify one incident-level bulletin and handle exceptions. | source | Human verification is per incident, not per customer. |
| B8 Natural route to buyers | 1 | L | Agency newsletters and operations communities can carry a useful public alert and paid referral link; credibility and placement need to be earned. | assumption | No owned channel documented. |
| B9 Easy to get the value | 2 | M | Subscribe, choose platforms, receive a relevant alert, check applicability and adapt the client message; value arrives when a covered incident occurs. | source | Bounded journey; value timing is incident-driven. |
| B10 Newton's Rule (scale advantage) | 2 | M | The same verified incident serves more agencies at lower per-subscriber cost; permissioned reports can improve detection coverage. | source | Real per-subscriber cost decline with scale. |

## Coverage, total, zeros
- Coverage: 10/10 bars assessed | Concept-fit total: 18/20 | Twos: 8 | Zeros: 0
- Every zero: none

## Sensitivities
- B8 (Natural route to buyers): scored 1 on assumption with L confidence -- the single weakest bar; credibility must be earned before scale.
- B1 (Pays more than once): scored 1 on source with M confidence -- quiet-period retention untested.
- B6 (No Brainer): scored 2 on source with M confidence -- hinges on synthesis quality vs free status pages.

## Useful improvements (separate note; does not revive a rejected offer)
- Publish a public sample alert during the next real platform incident; that artifact is the B6/B8 proof in one move.

## Unresolved questions
- WTP at $99/month.
- False-alarm tolerance and monitoring cost.
- Whether newsletters/communities will carry the referral link.

## Overall interpretation
The strongest WC1 profile in the catalog: a specific painful problem (platform storms cancel clients), a recurring job, one-verified-alert-serves-many economics, and an operator-run model with no founder in the path. The two questions are buyer-behavior: quiet-period retention and whether the synthesis beats free sources. SHORTLIST SIGNAL.

## Changes vs previous assessment (Mary guide v1.1, old v1 ID 11 -> new v2 ID 06)
Previous scores: `docs/scores/mary-2026-09-30-guide-v11/index.csv` (preserved untouched).

Old bars: 1 2 2 2 2 2 2 1 2 2
New bars: 1 2 2 2 2 2 2 1 2 2

- No changes vs Mary's guide v1.1 pass; WC1 scenario confirms the earlier read.

_Concept-fit mode: an unbuilt idea can be scored from documented design + business logic + labelled assumptions. U only where a missing detail materially prevents judgment. A concept score is not proof of demand or operating results; scores alone never authorize outreach, tests, building, or spending._
