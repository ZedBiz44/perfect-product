# 37 — Product Ingredient Company (B2B2C layer)

**Stable catalog ID:** 37
**Group:** Structures
**Existing status:** exploration
**Reviewer:** Manus
**Assessment date:** 2026-09-30
**Assessed product version:** WC1
**Guide:** [v1.2](https://app.notion.com/p/3eba3e33d58181d19eabc5d62f6401f4)
**Rubric / definition pin:** [`8be7c589928ef681577baaa765a90583d824f128`](https://github.com/ZedBiz44/perfect-product/tree/8be7c589928ef681577baaa765a90583d824f128/docs/framework)
**Catalog source commit:** [`6ea8ec21ad60716e11667c353b796f957265147a`](https://github.com/ZedBiz44/perfect-product/tree/6ea8ec21ad60716e11667c353b796f957265147a/docs/products)
**Current entry:** [`docs/products/entries/37-product-ingredient-company-b2b2c-layer.md`](../../../products/entries/37-product-ingredient-company-b2b2c-layer.md)

## Assessment frame
- **Buyer and payer:** A marketing-course company that pays $297/month to provide CourseFinish, an action layer, to its learners; the learners are end users, not the payer.
- **Offer and delivery:** A white-label CourseFinish action layer: AI drafts mapped course tasks and routine reminders, a human approves mappings and exceptions, the course company installs it and invites learners, and course staff handle learner support.
- **Price hypothesis:** $297/month for one marketing-course company's action layer, contingent on an improvement in learner implementation that is useful beyond existing worksheets and reminders.
- **Repeat-payment mechanism:** Successive course cohorts require action support, giving an ongoing course seller a recurring licence reason while it continues selling the course.
- **Founder role:** Jack is assumed to be an occasional product adviser (0–2 hours/week); an operator handles implementation maps and the course company's staff handle learners.
- **Primary satisfaction shape:** Tool in the hand: a learner receives a clear next course task and can experience competence by completing a useful action; the course company sees the course being used.
- **Founder fit:** conditional

## Material assumptions
- Marketing-course companies run successive cohorts and view weak implementation as costly through poorer completion, testimonials, referrals, or repeat sales, enough to support a $297/month licence.
- CourseFinish can use reusable task patterns with bounded course mapping, review, revisions, and maintenance rather than becoming bespoke implementation work for every course company.
- AI can draft usable mappings and routine reminders, while human review remains verification and exceptions rather than routine learner-level fulfillment.
- ZedBiz owns the reusable delivery layer and task templates, and the B2B licences are assignable; course companies retain their lesson IP.
- Course implementers or platform consultants can have sufficient margin and client-results incentive to resell the layer, despite no agreement or access being established.
- Course-company staff, rather than ZedBiz, provide learner support and accountability coaching.

## Sources used
- docs/products/entries/37-product-ingredient-company-b2b2c-layer.md
- docs/products/assessment-context.md
- docs/framework/perfect-product-rubric.md
- docs/framework/perfect-product.md
- docs/current-direction.md
- docs/perspectives/z3.md
- docs/ingredients.md

## Ten-bar assessment

| Bar | Criterion | Score | Confidence | Basis | Reason | Main limitation |
| ---: | --- | ---: | --- | --- | --- | --- |
| 1 | Pays more than once | 2 | Medium | assumption | A monthly licence attached to successive cohorts gives the course company a specific recurring reason to pay while it continues selling the course. | Renewal still depends on the layer improving implementation enough to beat existing low-cost worksheets and reminders. |
| 2 | Build once, sell many with worthwhile margin | 1 | Medium | inference | Shared action formats can be licensed repeatedly, but each new course requires mapping and ongoing alignment work. | At $297/month, unmeasured implementation, support, and maintenance effort may materially constrain margin and turn reuse into client-specific work. |
| 3 | Creates Gold | 2 | Medium | assumption | The reusable delivery layer, task-template library, documented mapping system, and assignable B2B licences can accumulate into a transferable operating asset. | Course lessons remain customer-owned, and rights, licence assignability, and the value of the contract base are not established. |
| 4 | Runs without Jack | 2 | Medium | assumption | Mapping, implementation, and learner support have named roles outside Jack, leaving him only product standards and exceptions rather than daily delivery or hosting. | This holds only if the mapping process and product standards are documented enough for an operator and course staff to perform them. |
| 5 | Satisfaction shape | 2 | Medium | assumption | For the named CourseFinish application, an actionable next task and its completion credibly provide Tool-in-the-hand competence to learners, reinforced by the payer seeing course use. | The experience depends on the mapping producing a useful task rather than another generic prompt. |
| 6 | No Brainer | 1 | Medium | inference | A course company facing weak learner implementation has a recognizable pain and a plausible $297/month B2B value proposition. | The payer must still be persuaded that completion gains are worth more than familiar worksheets, reminders, or other course improvements. |
| 7 | C3PO, AI does core work | 2 | Medium | assumption | AI performs the routine core delivery by drafting mapped tasks and reminders, while humans are limited to shared-map approval and exceptions and course staff handle learners. | If human course mapping, maintenance, or learner intervention becomes substantial routine work per payer, this would no longer be a strong AI-core fit. |
| 8 | Natural route to buyers | 1 | Medium | assumption | Course implementers and platform consultants are a specific possible reseller route, with a plausible incentive in margin and stronger client outcomes. | No partner access, integration relationship, resale terms, or endorsement is established, so founder-led partner recruitment may be required. |
| 9 | Easy to get the value | 1 | Medium | source fact | The payer has a defined path—supply an outline, approve the mapping, install the layer, and invite learners—but it is a bounded implementation project rather than instant value. | Mapping, installation, and approval friction can make the promised learner outcome feel like an extra project for the course company. |
| 10 | Newton's Rule | 1 | Medium | inference | More learners using one mapped course spread the action layer's production cost, creating a real within-course scale benefit. | Each additional course company introduces mapping and maintenance work, so broader customer scale only helps if reusable patterns outweigh that operating burden. |

## Score summary
- **Coverage:** 10/10 numeric bars
- **Concept-fit total /20:** 15/20
- **Strong fits (2s):** 5
- **Zero bars:** None
- **Shortlist signal:** No: score remains conditional and must be judged under the rubric, not inferred from this record alone

## Sensitivities
- If each course requires new diagnosis, custom task design, or frequent lesson-specific rewrites, bars 2, 4, 7, 9, and 10 weaken and the model approaches prohibited custom client work.
- The repeat and No-Brainer assessments depend on a meaningful, attributable implementation improvement relative to free or already-included course aids.
- A reseller route only reduces founder selling if partners can access the right course companies and have incentive to support installation without shifting support costs back to ZedBiz.
- Economics improve most when many learners use a small number of similar course maps; a highly diverse course portfolio has much weaker scale gravity.

## Improvements separate from score
- Specify a standardized course-input format, supported task-pattern catalogue, mapping turnaround, revision cap, and maintenance boundary so the licence remains a product rather than bespoke implementation.
- Define the payer-facing completion or action signal, the licence metric, and the distinction from ordinary worksheets and reminder tools.
- State partner resale, integration, installation, learner-support, data, and escalation responsibilities rather than leaving them implicit.
- Document the AI-to-human mapping workflow and the rights structure for reusable templates, customer material, and licence assignment.

## Unresolved questions
- How much will the defined course-company payer pay for an action layer, and what improvement in completion or downstream economics would make $297/month durable?
- How much operator time and expense do first mapping, lesson changes, integration, and exceptions require for a typical marketing course?
- What installation and data access are needed, and can the layer work without a fragile platform integration?
- Which implementers or platform consultants can actually resell it, under what incentives and support expectations?
- Are the template rights, customer permissions, and B2B licences genuinely transferable and assignable?

## Overall interpretation
For the WC1 CourseFinish application, the structure has a credible recurring B2B2C licence, transferable reusable-IP path, AI-led routine learner delivery, and no inherent community-host requirement. Its central trade-off is that course-specific mapping and partner access are not incidental details: if they are not tightly bounded, the model becomes implementation-heavy custom work with weaker margin, buyer ease, scale, and founder independence. The concept therefore fits conditionally rather than establishing a selected or proven product.

## Scope note
This is an independent concept-fit assessment of the stated WC1/WC1.1 scenario. It is not evidence of demand, customer results, margins, partner access, or a launch decision. Existing status remains unchanged.
