# 06 — Platform Weather

**Stable catalog ID:** 06
**Group:** Products
**Existing status:** hopper
**Reviewer:** Manus
**Assessment date:** 2026-09-30
**Assessed product version:** WC1
**Guide:** [v1.2](https://app.notion.com/p/3eba3e33d58181d19eabc5d62f6401f4)
**Rubric / definition pin:** [`8be7c589928ef681577baaa765a90583d824f128`](https://github.com/ZedBiz44/perfect-product/tree/8be7c589928ef681577baaa765a90583d824f128/docs/framework)
**Catalog source commit:** [`6ea8ec21ad60716e11667c353b796f957265147a`](https://github.com/ZedBiz44/perfect-product/tree/6ea8ec21ad60716e11667c353b796f957265147a/docs/products)
**Current entry:** [`docs/products/entries/06-platform-weather.md`](../../../products/entries/06-platform-weather.md)

## Assessment frame
- **Buyer and payer:** A marketing/GHL agency that depends on a bounded set of rented platforms; the agency pays the proposed subscription.
- **Offer and delivery:** A shared incident-monitoring subscription: AI collects and clusters signals and drafts notices; a monitoring operator verifies an incident-level bulletin, then agencies receive relevant alerts and white-label client communications to adapt. The scenario does not establish customer-specific technical remediation as included delivery.
- **Price hypothesis:** $99/month per marketing agency for coverage of a bounded platform set; this is an unvalidated working-scenario price.
- **Repeat-payment mechanism:** Recurring outages, enforcement waves, policy changes, and platform deprecations continually recreate the need for timely warning and client communication.
- **Founder role:** Under WC1, a monitoring operator and escalation rota verify and distribute bulletins; Jack handles occasional policy decisions, assumed at 0–2 hours per week.
- **Primary satisfaction shape:** Tool in the hand: during a covered platform storm, the agency has a ready, usable alert and client message that lets it respond promptly and competently rather than look uninformed.
- **Founder fit:** conditional

## Material assumptions
- Permitted, sufficiently reliable sources can be monitored to detect meaningful platform incidents early enough to matter, and a human operator can verify them without per-agency investigation.
- At a viable subscriber count, the $99 fee can cover monitoring tools, incident verification, escalation coverage, and support while retaining worthwhile margin.
- Agencies value synthesized, actionable, white-label communications enough to pay beyond free status pages, public alerts, and peer-group information.
- The product can retain rights to its incident taxonomy, templates, and permissioned observations; customer data and public-source material are not automatically owned assets.
- Included delivery remains a shared incident bulletin and adaptable communication template, rather than bespoke fixes or ongoing technical implementation for each agency or client.
- Agency newsletters and operations communities will provide a repeatable placement or referral path once the product's credibility is established; no such access is evidenced.

## Sources used
- docs/products/entries/06-platform-weather.md
- docs/products/assessment-context.md
- docs/framework/perfect-product-rubric.md
- docs/framework/perfect-product.md
- docs/current-direction.md
- docs/perspectives/mary.md
- docs/ingredients.md
- docs/framework/satisfaction-shapes.md
- docs/products/entries/16-field-notes-practitioner-briefing.md

## Ten-bar assessment

| Bar | Criterion | Score | Confidence | Basis | Reason | Main limitation |
| ---: | --- | ---: | --- | --- | --- | --- |
| 1 | Pays more than once | 2 | Medium | inference | The proposed $99 subscription covers a job that recurs whenever platforms change, fail, or enforce policy. | Renewal depends on enough relevant storms and useful coverage to remain preferable to free sources. |
| 2 | Build once, sell many with worthwhile margin | 1 | Medium | inference | One verified incident bulletin and communication template can serve many agencies without rebuilding it per subscriber. | Reliable monitoring, false-alarm handling, platform breadth, and any promised fixes impose meaningful ongoing operating and margin pressure. |
| 3 | Creates Gold | 2 | Medium | assumption | An incident archive, taxonomy, proven communication templates, systems, and subscriber relationships can accumulate into a transferable operating asset. | The archive needs durable rights, provenance, and differentiated usefulness; a collection of public notices alone would be weak Gold. |
| 4 | Runs without Jack | 2 | Medium | assumption | WC1 assigns verification, routing, and distribution to an operator and escalation rota, leaving Jack only occasional policy exceptions. | This strong fit depends on the stated transferable operating split and on keeping technical remediation out of Jack's regular work. |
| 5 | Satisfaction shape | 2 | Medium | inference | At an incident, an agency can immediately use the supplied alert and client message to act with visible competence, fitting Tool in the hand. | The satisfaction fails if alerts are late, irrelevant, or too generic to use safely. |
| 6 | No Brainer | 1 | Medium | inference | Platform-risk churn and reputation damage create a recognizable trigger, and one protected agency-client relationship could make $99 small relative to the loss avoided. | Free status pages and peer groups are close substitutes, so the recurring price requires synthesis and response value beyond repeating news. |
| 7 | C3PO, AI does core work | 2 | Medium | assumption | AI performs the shared unit's signal collection, clustering, and notice drafting; human work is verification and exceptions for one incident bulletin rather than each agency message. | The split is only strong if human compliance judgment and customer-specific fixes do not become routine work for every alert or subscriber. |
| 8 | Natural route to buyers | 1 | Medium | assumption | Useful public alerts can plausibly travel through agency newsletters and operations communities to a paid referral or subscription path. | No placement, audience access, referral terms, or established credibility is evidenced, so the channel may require substantial founder-led effort initially. |
| 9 | Easy to get the value | 2 | Medium | inference | The stated journey is limited and clear: subscribe, choose covered platforms, receive a relevant alert, and adapt the supplied client message when an incident occurs. | Value is contingent on a timely covered event; customer-specific technical remediation would add a second project outside this scored communication scope. |
| 10 | Newton's Rule | 2 | Medium | assumption | The same verified wave can serve more subscribers at a lower per-subscriber cost, while permissioned reports can improve detection coverage. | Additional platforms, source verification, and false alarms can increase coordination burden unless the alert process remains standardized. |

## Score summary
- **Coverage:** 10/10 numeric bars
- **Concept-fit total /20:** 17/20
- **Strong fits (2s):** 7
- **Zero bars:** None
- **Shortlist signal:** No: score remains conditional and must be judged under the rubric, not inferred from this record alone

## Sensitivities
- If reliable early detection requires dedicated platform specialists, continuous manual review, or a bespoke fix for each agency, bars 2, 4, 7, and 9 weaken and the model risks violating the no-custom-client-work constraint.
- If agencies regard free status pages, vendor notices, and peer groups as sufficient, the $99 price and retention rationale weaken materially despite the underlying platform-risk pain.
- If public alerts do not earn credible newsletter or operations-community placement, the named buyer route remains a founder-dependent acquisition hurdle.
- The Gold and scale mechanisms depend on lawful data provenance, a useful incident taxonomy, and evidence that the archive improves future detection or response.

## Improvements separate from score
- Specify a bounded platform list, source hierarchy, alert-service standard, and the definition of a verified incident-level bulletin.
- Separate included white-label communication from any technical remediation so the offer remains a shared product rather than a client service.
- Define the rights, retention, anonymization, and handover rules for the incident archive and any subscriber-contributed observations.
- Make the public-alert-to-paid-subscription path and the channel owner's incentive explicit without treating a potential partner as secured.

## Unresolved questions
- Which permitted sources provide enough early signal to make alerts faster or more useful than vendor status pages and peer communities?
- What exact response is included under the word 'fixes,' and can it stay shared rather than agency- or client-specific?
- What incident frequency, subscriber count, and operator coverage are needed for the $99 subscription to support worthwhile margin?
- Will agencies pay to retain coverage between incidents, and which proof makes the synthesis meaningfully different from free information?
- Which newsletter or operations-community routes can carry the offer without relying on Jack's continuing personal sales or public performance?

## Overall interpretation
WC1 describes a credible shared-alert product whose recurring incident job, AI-assisted incident workflow, reusable archive, and scale economics fit strongly under its stated assumptions. Its concept fit remains conditional rather than settled: trusted early detection, differentiated paid value, a non-founder acquisition route, and a strict boundary against bespoke remediation are all material to preserving the model.

## Scope note
This is an independent concept-fit assessment of the stated WC1/WC1.1 scenario. It is not evidence of demand, customer results, margins, partner access, or a launch decision. Existing status remains unchanged.
