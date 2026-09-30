# 04 — Save Kit

**Stable catalog ID:** 04
**Group:** Products
**Existing status:** hopper
**Reviewer:** Manus
**Assessment date:** 2026-09-30
**Assessed product version:** WC1
**Guide:** [v1.2](https://app.notion.com/p/3eba3e33d58181d19eabc5d62f6401f4)
**Rubric / definition pin:** [`8be7c589928ef681577baaa765a90583d824f128`](https://github.com/ZedBiz44/perfect-product/tree/8be7c589928ef681577baaa765a90583d824f128/docs/framework)
**Catalog source commit:** [`6ea8ec21ad60716e11667c353b796f957265147a`](https://github.com/ZedBiz44/perfect-product/tree/6ea8ec21ad60716e11667c353b796f957265147a/docs/products)
**Current entry:** [`docs/products/entries/04-save-kit.md`](../../../products/entries/04-save-kit.md)

## Assessment frame
- **Buyer and payer:** Agency owner or operator paying for a self-serve tool to prepare a client-facing proof packet when a retainer client questions value or signals cancellation.
- **Offer and delivery:** The agency connects or uploads its client data, maps metrics, has AI assemble and explain a white-labeled proof packet, verifies attribution and claims, then presents it in the next client review or save conversation.
- **Price hypothesis:** $99/month for self-serve access; the entry also records unvalidated $49–$149/month or $199–$499 one-time-plus-updates alternatives.
- **Repeat-payment mechanism:** Monthly access is intended for recurring client reviews and intermittent churn conversations, conditional on the agency having enough client accounts and repeat occasions to use the tool.
- **Founder role:** Jack is assumed to provide only occasional product oversight (0–2 hours per week); a product operator handles access and incidents, while the purchasing agency maps and verifies each packet.
- **Primary satisfaction shape:** Tool in the hand: at a tense client conversation, the agency can produce a concrete, client-branded answer to ‘what did you do?’; accurate evidence is the immediate success signal.
- **Founder fit:** conflict

## Material assumptions
- Agency data exports or connections contain enough reliable workflow, lead, follow-up, review, and outcome evidence to substantiate a client-facing packet.
- Account mapping and claim verification can remain the agency's bounded responsibility rather than turn into recurring vendor-side custom fulfillment.
- Avoiding or delaying a single client cancellation makes a $99 monthly price plausibly small relative to the agency's retained revenue.
- Agency operations educators can reach relevant payers and find a referral incentive worthwhile, despite competing reporting tools and data-access concerns.
- Any accumulated save/lose records are permissioned and can be owned and transferred; agencies and their clients retain rights to underlying data.

## Sources used
- docs/products/entries/04-save-kit.md
- docs/products/assessment-context.md
- docs/framework/perfect-product-rubric.md
- docs/framework/perfect-product.md
- docs/current-direction.md
- docs/perspectives/mary.md
- docs/perspectives/grok.md
- docs/ingredients.md
- docs/products/entries/17-client-retention-engine.md

## Ten-bar assessment

| Bar | Criterion | Score | Confidence | Basis | Reason | Main limitation |
| ---: | --- | ---: | --- | --- | --- | --- |
| 1 | Pays more than once | 2 | Medium | inference | Monthly access has a stated recurring use in regular client reviews and fresh cancellation threats. | Renewal depends on agencies having enough accounts and perceiving repeat value beyond built-in reporting. |
| 2 | Build once, sell many with worthwhile margin | 1 | Medium | source fact | The packet engine and templates are reusable, but export inconsistency, mapping, disputed metrics, support, and QA create material account-level cost. | At the proposed low monthly price, recurring data exceptions can constrain worthwhile margin. |
| 3 | Creates Gold | 1 | Medium | assumption | Software and templates are transferable, and permissioned save/lose records could become a more valuable outcome archive. | Underlying client data is not owned, and permissioned outcome records may be too thin or restricted to create a strong transferable asset. |
| 4 | Runs without Jack | 2 | Medium | assumption | The stated steady-state split assigns access and incident handling to an operator, agency-specific verification to the buyer, and Jack only occasional oversight. | This fit relies on standardized integrations and exception handling; recurring bespoke data rescue would reintroduce founder or specialist dependence. |
| 5 | Satisfaction shape | 2 | Medium | inference | A usable, accurate proof packet gives the agency a tangible Tool-in-the-hand result immediately before a difficult client meeting. | It provides competence in explaining work, not a guaranteed saved client, and weak underlying results limit satisfaction. |
| 6 | No Brainer | 1 | Medium | inference | The buyer, payer, urgent churn trigger, and plausible value of retaining one client make the offer understandable at $99/month. | Built-in reports and AI summaries compete, data setup complicates the first yes, and Jack's recorded view is that needing a save kit may mean the agency is already too late. |
| 7 | C3PO, AI does core work | 1 | Medium | source fact | AI performs meaningful packet assembly and metric explanation from supplied data. | The agency must materially verify attribution and claims for every client packet, so human work remains a substantive part of the delivered unit. |
| 8 | Natural route to buyers | 1 | Low | assumption | Agency operations educators are a specific potential demonstrator-and-referrer route to agency payers. | No access, referral terms, or educator incentive is established, and competing reporting products plus data-access concerns weaken adoption. |
| 9 | Easy to get the value | 1 | Medium | source fact | The use path is explicit: connect or upload, map, generate, verify, and present the packet at a review. | Meaningful data preparation, attribution checking, and per-client verification make value less immediate than the one-click promise. |
| 10 | Newton's Rule | 1 | Medium | inference | Shared software and templates spread fixed production costs across more agencies. | Customer-specific integrations and data failures can make support rise alongside adoption, while the outcome-data advantage is conditional on permissions. |

## Score summary
- **Coverage:** 10/10 numeric bars
- **Concept-fit total /20:** 13/20
- **Strong fits (2s):** 3
- **Zero bars:** None
- **Shortlist signal:** No: score remains conditional and must be judged under the rubric, not inferred from this record alone

## Sensitivities
- If reliable, standardized data access is unavailable, both the core packet promise and the self-serve margin deteriorate sharply.
- If agencies use the tool only in rare emergency saves rather than routine reviews, monthly retention and willingness to pay weaken.
- If agencies must routinely ask the vendor to resolve mapping, attribution, or disputed metrics, bars 2, 4, 7, 9, and 10 weaken together.
- If the packet is perceived as a generic report rather than credible proof, it cannot overcome the recorded ‘already dead’ objection at the churn moment.

## Improvements separate from score
- A more standardized evidence schema and explicit boundary between agency verification and vendor support would reduce the custom-work pressure without changing this assessment.
- A differentiated proof element beyond an AI summary or native report would make the urgent buyer value more distinct.
- A consent and rights design for aggregate save/lose observations would determine whether the proposed dataset can become transferable Gold.

## Unresolved questions
- Do relevant data sources expose the execution, contact-touch, and outcome data required for accurate automatic assembly?
- Will agencies trust the packet's attribution enough to use it in a cancellation conversation, and what errors are acceptable?
- Do agencies repeatedly use this at ordinary reviews, or only after a cancellation threat when it may be too late?
- Will a reachable distribution intermediary carry a tool that overlaps reporting alternatives?
- Does the agency-tool focus remain incompatible with the current direction that GHL is production infrastructure rather than the product or market?

## Overall interpretation
Save Kit is a plausible recurring self-serve proof tool with a sharp churn trigger and a real Tool-in-the-hand experience, but its commercial and operating fit is only partial because data mapping and verification remain material, acquisition is conditional, and the packet cannot repair poor results. The scenario conflicts with the recorded founder direction rejecting a GHL/agency product focus and with Jack's standing objection that a save kit arrives after the retention problem is already lost; hopper status is therefore preserved.

## Scope note
This is an independent concept-fit assessment of the stated WC1/WC1.1 scenario. It is not evidence of demand, customer results, margins, partner access, or a launch decision. Existing status remains unchanged.
