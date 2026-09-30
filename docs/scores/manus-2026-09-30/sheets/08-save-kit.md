# Perfect Product assessment — 08 Save Kit

## Assessment identity

- **Stable GitHub catalog ID:** 08
- **Candidate name, group and existing status:** **Save Kit** — product; catalog tier **mid–high**; **hopper**. It is not approved or revived by this assessment.
- **Reviewer and date:** Manus independent assessment — 2026-09-30
- **Assessment type:** Concept fit
- **Guide version:** Scoring Guide v1.1, dated 2026-09-30
- **Pinned rubric version, commit and date:** Perfect Product Rubric v1.1 — `8be7c589928ef681577baaa765a90583d824f128`, 2026-09-30
- **Pinned definition commit and date:** `8be7c589928ef681577baaa765a90583d824f128`, 2026-09-30
- **Catalog source commit and assessed product version:** `8be7c589928ef681577baaa765a90583d824f128`; `docs/products/entries/08-save-kit.md` (Git blob `b66789ce73550863875874d8f3c2aaecab5d6ac3`), headed **“8. Save Kit.”**

## Product and assumptions

- **Buyer and payer:** The buyer and payer is an agency with retainer clients who question what they are paying for or may churn. The agency operates the tool. The at-risk retainer client is the recipient of the agency’s white-labeled proof packet, not the payer for Save Kit.
- **Promise and delivery:** At the churn/questioning moment, the agency clicks once to assemble a white-labeled “here’s everything we’ve done” proof packet from its own GHL/data: described source fields include automation runs, leads touched, follow-ups, reviews, and dollarized results where possible. This is a designed mechanism, not proof the required data or packet quality is available.
- **Price hypothesis and repeat-payment mechanism:** The catalog states **~$49–$149/month**, or **~$199–$499 one-time plus updates**; it labels both as unvalidated hypotheses. The monthly option is standing access for future client-wobble moments in an agency’s continuing retainer book; the one-time route relies only on optional updates.
- **Founder role:** Not specified. The sources do not allocate implementation, data mapping, packet-quality review, customer support, or exception handling between Jack, AI, and staff.
- **Primary and supporting satisfaction shapes:** **Primary: Tool in the hand.** The proposed click-to-assemble packet aims to make an agency capable of responding at a named moment. **Supporting: none stated.** The Hip-Kit-trigger analogy describes timing, not a separately delivered satisfaction shape.

### Material assumptions

1. **A1 — data access:** Each agency can authorize access to GHL and other required data, and the necessary workflow-execution/contact-touch fields are exposed. Mary explicitly records this as open validation; if unavailable, the concept “dies here.”
2. **A2 — usable proof:** The retrieved data is complete, accurate, timely, and comprehensible enough for a churn conversation; a packet does not itself establish that a client will stay.
3. **A3 — paid recurrence:** Agencies view standing access at the stated monthly price, or later updates after a one-time purchase, as worthwhile relative to avoided client churn. No willingness-to-pay or renewal evidence is claimed.
4. **A4 — data rights:** ZedBiz can lawfully retain sufficiently anonymized save/lose outcome data and reasons to form the stated proprietary dataset.
5. **A5 — repeatable operations:** Agency-specific authorization, branding, mapping, validation, and support can be standardized rather than requiring Jack’s continuing per-agency work.
6. **A6 — acquisition:** No route to reach agency payers is assumed. The cited sources identify an agency category and objections, not an available repeatable channel.

## Sources used

| Source | What it establishes for this assessment |
| --- | --- |
| [`08-save-kit.md`](../../products/entries/08-save-kit.md) | Catalogued buyer, trigger, delivery claim, price hypotheses, Tool-in-the-hand label, hopper status, and unvalidated-price caveat. |
| [`perspectives/mary.md`](../../perspectives/mary.md) — “Save Kit,” especially lines 63–69 | Original proposed one-click proof-packet mechanism, tracked save/lose/why dataset, underlying “what am I paying for?” quote, and explicit unresolved GHL API/data-access dependency. |
| [`perspectives/grok.md`](../../perspectives/grok.md) — lines 96–100 and 168–174 | The broader GHL-agency-product rejection and Jack’s recorded objection: “if you need a save kit, you’re already dead”; Save Kit remains hopper only. |
| [`ingredients.md`](../../ingredients.md) — lines 14 and 35 | Save Kit is hopper; only the buying moment and reusable proof assets are retained; Jack’s objection still stands; it is distinct from the dead Client Retention Engine. |
| [`products/entries/30-client-retention-engine.md`](../../products/entries/30-client-retention-engine.md) | The linked predecessor is dead because it sold agencies their own retention job; its retained ingredient is the “what am I paying for?” moment. |
| [Scoring Guide v1.1](/home/ubuntu/[Scoring Guide v1.1](https://app.notion.com/p/3eba3e33d58181d19eabc5d62f6401f4)), [`perfect-product-rubric.md`](../../framework/perfect-product-rubric.md), [`perfect-product.md`](../../framework/perfect-product.md), [`satisfaction-shapes.md`](../../framework/satisfaction-shapes.md), and [`current-direction.md`](../../current-direction.md) | The applicable procedure, ten bars, named shapes, score meanings, founder constraints, and documented hopper/rejection conflict. |

### Status and conflict handling

Save Kit is assessed **as the catalogued hopper version**, not as the dead Client Retention Engine and not as an improved product. The retained trigger/proof-asset ingredients make it distinct from the killed retention service. However, the later, recorded objection — that a Save Kit is already too late if it is needed — remains a material limitation on its reactive value and lowers confidence in satisfaction and first-purchase value. It does not change the existing hopper status or, by itself, establish a zero on a particular bar.

## Ten-bar record

| Bar | U/0/1/2 | Reason | Source fact / inference / assumption | Confidence: High/Medium/Low | Main limitation or missing detail |
| --- | --- | --- | --- | --- | --- |
| 1. Pays more than once | **2** | The stated $49–$149/month option provides ongoing access when future clients wobble; a continuing retainer book gives a credible repeat-use reason. | **Source fact + inference:** Monthly price is catalogued; recurring future churn moments are inferred from agencies retaining clients. | Medium | Price is explicitly unvalidated. The one-time-plus-updates alternative has only optional recurrence, and no renewals are evidenced. |
| 2. Build once, sell many | **1** | A shared proof-packet product can be reused across agencies rather than rewritten as a managed narrative for every client. | **Source fact + inference:** The packet is described as one-click/assembled from agency data; per-agency authorization, mapping, and support are reasonably expected. | Low | The required GHL/data fields are unvalidated, and the entry does not show that onboarding, white-label configuration, output checks, and support fit a worthwhile margin at the stated prices. |
| 3. Creates Gold | **2** | Tracking each attempt as fired, saved/lost, and why is a named accumulating outcome dataset that could be transferable and improve in value beyond Jack’s labor. | **Source fact:** The entry and Mary proposal expressly name the save/lose dataset as a proprietary/sellable moat. | Medium | Data rights, consent, outcome completeness, and ZedBiz ownership are not specified; the dataset is planned, not demonstrated. |
| 4. Runs without you | **U** | No operating design says who builds or maintains integrations, maps agency data, verifies packet claims, supports users, or resolves failures. | **Source fact:** The catalog entry and cited sources provide no Jack/staff/system responsibility split. | High | Founder dependence is an essential missing detail; self-service wording alone cannot establish an operation that runs without Jack. |
| 5. Satisfaction shape (primary plus supporting shapes) | **1** | As a **Tool in the hand**, a proof packet at the exact “what am I paying for?” moment could give an agency immediate competence to respond. | **Source fact + inference:** The entry specifies the tool and trigger; Tool in the hand is its stated shape. | Medium | It is a reactive, high-stakes tool after value is already questioned. API/data completeness and the packet’s ability to satisfy the client are unproved; Jack’s “already dead” objection directly limits the experience. |
| 6. No Brainer | **1** | The payer, churn-related pain, trigger, and low stated monthly range are specific; avoiding even one lost retainer could plausibly outweigh the price. | **Source fact + inference:** Sources report the question/churn pain and the price hypothesis; price-to-benefit is an inference, not a sale. | Medium | No paid demand, retention effect, existing budget line, or reason an agency would buy before the crisis is established. The documented objection says it may be too late when needed. |
| 7. C3PO (AI does the work) | **U** | “One click” and data assembly do not identify an AI core-production task or say what people verify versus do routinely. | **Source fact:** Neither the entry nor its cited sources specifies an AI/human task split. | High | The mechanism may be software automation, AI-assisted generation, or human fulfillment; that missing split prevents a C3PO judgment. |
| 8. Natural route to buyers | **U** | A category of agency buyer is named, but no repeatable way to reach its payer is described. | **Source fact:** The entry names no channel; the direction documents do not supply one for Save Kit. | High | GHL/agency audiences are not automatically an acquisition channel, and the cited records include a rejection of the GHL agency product direction. |
| 9. Easy to get the value | **1** | The intended use at the crisis moment is presented as a one-click packet, which is a manageable path to the promised tool output once configured. | **Source fact + inference:** One-click assembly is stated; simple use after setup is inferred. | Low | Authorization, setup, data mapping, proof review, and any save conversation are unspecified. The unvalidated API may turn the apparent one-click use into an unexpected project. |
| 10. Newton’s Rule | **2** | More tracked save attempts and save/lose reasons can make future packets smarter, creating a data-based customer-value advantage as use scales. | **Source fact:** Mary explicitly proposes the growing performance dataset to improve every future kit. | Medium | The scale benefit depends on lawful data retention, enough comparable outcomes, and feedback actually being incorporated; none is demonstrated. |

## Result

- **Coverage /10:** **7/10**
- **Concept-fit total /20 (blank if any U):**
- **Strong fits /10:** **3/10** (bars 1, 3, and 10)
- **Every zero and its conflict:** **None.** No bar is scored 0: the record contains material missing details and unvalidated mechanisms, which are scored U or 1 rather than treated as model conflicts. The documented hopper/rejection tension is recorded above and limits bars 5–6.
- **Shortlist signal under rubric v1.1:** **No.** Three essential bars are U, so no total is permitted; it also has only three strong fits. This is not approval, revival, validation, or authorization to build or sell.
- **Assumptions that could change scores:** A1–A6 above. In particular, a feasible data/API and privacy design plus a specified AI/human operating model could resolve bars 2, 4, 7, and 9; a named repeatable acquisition channel could resolve bar 8. Those would be changes or new evidence, not facts about this assessed version.
- **Unresolved question:** **Can GHL and connected agency data lawfully expose the automation-run and contact-touch data needed to generate an accurate proof packet without per-agency manual reconstruction?**

### Possible improvement — not part of the assessed version

Before treating this hopper item as a build candidate, specify and test the exact data sources/permissions, packet-quality controls, AI-versus-human exception path, and a payer acquisition route. That would create a different, better-specified version; it has **not** been included in the scores above.

- **Previous assessment link and changed-score reasons:** Not consulted. This is an independent Manus assessment; prior Grok, Cody, and Mary score sheets were intentionally not used as evidence.
- **For reconciliation: author, source reviewers, agreements and unresolved differences:** Not applicable.
