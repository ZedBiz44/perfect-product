# Perfect Product Rubric

[Repository home](../../README.md) · [Perfect Product definition](perfect-product.md) · [Satisfaction shapes](satisfaction-shapes.md) · [Product catalog](../products/README.md) · [Decision guide](../current-direction.md)

**Purpose:** Score any product idea against Jack's ten bars so every AI agent uses the same definitions, pass/fail criteria, and total rule. Do not invent new bars. Do not soft-pass a hard fail.

**Scoring scale (use everywhere):** **0 = Fail · 1 = Partial · 2 = Pass**

---

## How agents use this

1. **Read** [perfect-product.md](perfect-product.md) for the live bar wording, then score with this rubric.
2. **Name the idea** (working title + one sentence). Pull buyer, price hypothesis, and status from the [product catalog](../products/catalog.md) when available.
3. **Score each of the 10 bars 0 / 1 / 2.** Write one sentence of evidence per bar (source path or observed fact). No evidence → score at most 1.
4. **Check bar 5:** the idea must map to **exactly one** of the seven satisfaction shapes (checklist below). If none fit, bar 5 = 0.
5. **Total = sum of 10 scores (max 20).** Interpret with the rule below — do **not** average away a zero.
6. **Verdict rule (recommended for agents):**
   - **Must-not-fail:** any bar scored **0** → idea is **not** a Perfect Product candidate (park, rework, or kill).
   - **Partial bars (1s):** allowed only with a dated note on what evidence would raise them to 2.
   - **Proceed to proof:** all bars ≥ 1, at least 7 bars = 2, and founder constraints in [current-direction.md](../current-direction.md) still hold.
7. **Do not** treat a high total as approval to build. Record scores in [templates/product-evaluation.md](../../templates/product-evaluation.md); willingness to pay still needs experiments.
8. **Do not** score catalog entries unless Jack or the task asks. Catalog first, rubric later.

---

## How to total and interpret

| Total | Meaning |
| --- | --- |
| **Any bar = 0** | **Hard fail.** Not a Perfect Product. Keep as hopper/ingredient only if salvageable. |
| **1–10** | Weak / many gaps. Do not treat as a core candidate. |
| **11–14** | Mixed. Several Partials. Needs rework before proof gate. |
| **15–17** | Strong shape. Run commercial proof before build. |
| **18–20** | Clears the bars on paper. Still unproven until buyers pay and reuse. |

**Weighted scoring is optional notes only.** Default for agents: **must-not-fail any bar**, then prefer more Passes over Partials. Bars 4 (runs without you), 8 (route to buyers), and 9 (easy value) are frequent Jack-specific kill switches — call them out explicitly when Partial.

---

## The ten bars

### 1. Pays more than once

**Definition:** Recurring revenue (subscription/SaaS), repeat/multiple purchases from the same buyer, or a market so large that one sale each still scales.

**PASS (2):** Clear recurring or repeat mechanic named (e.g. weekly sub, seasonal rebuy, refill). Or mass one-time market with continuous fresh buyers.

**PARTIAL (1):** One-time sale with a plausible ladder/renewal, but mechanic unproven or optional.

**FAIL (0):** Single consulting engagement, one custom project, or no path to a second payment.

**Example:** Laurel's $7/mo ad coaching — membership bills again every month.

---

### 2. Build once, sell many

**Definition:** Software, content, a platform, kit, or manufactured unit. The next sale keeps a worthwhile margin after reaching, serving, and supporting the customer, and does **not** require rebuilding the product.

**PASS (2):** Same asset sold many times; delivery is copy/install/download; support is bounded and amortizes.

**PARTIAL (1):** Mostly reusable but still needs light per-buyer customization that could creep.

**FAIL (0):** Each sale is custom diagnosis, rebuild, or managed service hours.

**Example:** Carex Hip Kit — one SKU manufactured once, sold forever through shelves and therapists.

---

### 3. Sellable asset

**Definition:** Subscribers, archive, brand, systems, customer list, IP, or data that a business buyer would pay for. You're building something you can exit, not only income.

**PASS (2):** Named transferable assets (list + catalog + systems + brand) that survive without Jack's daily presence.

**PARTIAL (1):** Some assets exist but value is still tied to Jack personally (personal brand, founder Q&A as the product).

**FAIL (0):** Pure billable hours / reputation with nothing a buyer could acquire.

**Example:** OnlineJobs.ph — marketplace, profiles, and brand are the asset, not John's calendar.

---

### 4. Runs without you

**Definition:** With systems in place, a trained manager or partner can run it. Depends on systems, not the founder's daily presence. Includes: **no community-host treadmill**.

**PASS (2):** Ops documented; support batched; founder optional for exceptions; no daily comment-section duty.

**PARTIAL (1):** Could systemize, but today still needs Jack weekly for core delivery or hosting.

**FAIL (0):** Product dies if Jack goes quiet; or requires daily charm / hosting.

**Example:** Zoom — cloud platform + team; founder not in every meeting.

---

### 5. Satisfaction shape (one of seven)

**Definition:** The buyer experiences a clear satisfaction shape. Cold beer is only one shape. Full write-up: [satisfaction-shapes.md](satisfaction-shapes.md).

**PASS (2):** Exactly one shape named; buyer experience matches it; shape is designed into the offer.

**PARTIAL (1):** Shape guessed but experience is muddy or mixes conflicting shapes without design.

**FAIL (0):** No shape fits, or "content library" with no felt satisfaction.

#### Satisfaction shapes checklist (pick one)

- [ ] **Six Pack of Beer Desire** — instant thirst; rebuy within the week.
- [ ] **Coat of paint** — transformational reveal; buy again when a fresh surface appears.
- [ ] **Event Excitement** — anticipation → peak night → afterglow.
- [ ] **Harvest Gala** — seasonal pile of countable results.
- [ ] **Tool in the hand** — competence on first use.
- [ ] **Trophy** — displayable status / scored proof.
- [ ] **Belonging without hosting** — peer energy; product is the OS; someone else runs the room.

**Example:** Stream Deck = Tool in the hand — capable on first press.

---

### 6. No Brainer

**Definition:** The buyer immediately understands the value, already spends money or suffers measurable pain around the problem, and the price feels small relative to the payoff. The first yes should not require a long explanation or sales call.

**PASS (2):** Named buyer already pays for this or a painful workaround; price is cheap vs. the cost of the problem; trigger is clear.

**PARTIAL (1):** Desire plausible but price untested, or want exists without open wallets.

**FAIL (0):** Vitamin with no budget line, no trigger, or price requires a sales call to justify.

**Example:** Hip Kit ~$54–65 at hospital discharge — obvious vs. struggle without it.

---

### 7. Creates Gold

**Definition:** Each year of operation strengthens an asset: reputation, relationships, knowledge, distribution, catalog, or systems. Progress accumulates instead of being constantly replaced. (Bar 3 = can someone buy the business; bar 7 = does operating it make what you own more valuable over time.)

**PASS (2):** Named accumulating asset (dataset, catalog, install base, reputation loop) that compounds with use.

**PARTIAL (1):** Some accumulation possible, but core value resets often (throwaway content with no learning loop).

**FAIL (0):** Work resets every client/week with nothing retained.

**Example:** PLR.me — growing library + creator base; archived packs resold as value packs.

---

### 8. Natural route to buyers

**Definition:** People who want it find it through a repeatable channel that does **not** depend on constant personal selling — supplier, retailer, search, existing audience, partner, or customers introducing customers.

**PASS (2):** Named channel owner or built-in distribution; repeatable access without Jack performing daily.

**PARTIAL (1):** Channel hypothesized (e.g. "Skool owners") but no owned path or partner commitment yet.

**FAIL (0):** Requires Jack to cold-outbound forever or build a personal audience from zero as the only path.

**Example:** Carex kit rides surgeons, OTs, and pharmacy shelves — product carries acquisition.

---

### 9. Easy to get the value

**Definition:** Buyer reaches the promised satisfaction without an unexpected second project, extensive learning, or hand-holding. Effort should be clear and part of the expected experience. Buying should make life easier, not create another unfinished job.

**PASS (2):** Self-serve path; time-to-value measured in minutes/hours; prerequisites clear; no discovery call required.

**PARTIAL (1):** Usable by capable buyers but install/setup still friction-heavy.

**FAIL (0):** Needs training calls, custom setup, or creates a new unfinished project for the buyer.

**Example:** "Comment EDGES, get the checklist" — member gets the asset in one action.

---

### 10. Newton's Rule

**Definition:** Increase mass → increase gravity → it gets stronger as it grows. More customers, content, data, or partners make the next sale or next year easier, not harder. (Bar 7 = asset quality over time; bar 10 = flywheel / network strength as scale increases.)

**PASS (2):** Clear flywheel (invites, data, plugins, catalog gravity, partner density) where scale reduces CAC or increases pull.

**PARTIAL (1):** Mild scale benefits (more testimonials) but no structural flywheel.

**FAIL (0):** More customers make ops harder linearly (or worse) with no network/data effect.

**Example:** Zoom — every meeting invite recruits new users; density increases gravity.

---

## Quick scoring worksheet

Copy into notes or [templates/product-evaluation.md](../../templates/product-evaluation.md):

```
Idea:
Buyer:
Shape (bar 5):

1 Pays more than once:     _ / 2 — evidence:
2 Build once, sell many:   _ / 2 — evidence:
3 Sellable asset:          _ / 2 — evidence:
4 Runs without you:        _ / 2 — evidence:
5 Satisfaction shape:      _ / 2 — evidence:
6 No Brainer:              _ / 2 — evidence:
7 Creates Gold:            _ / 2 — evidence:
8 Natural route to buyers: _ / 2 — evidence:
9 Easy to get the value:   _ / 2 — evidence:
10 Newton's Rule:          _ / 2 — evidence:

TOTAL: _ / 20
Any zeros? Y/N → if Y, NOT a Perfect Product candidate.
Verdict: park / rework / proof-gate / kill
```

## Related

- [Perfect Product definition](perfect-product.md)
- [Satisfaction shapes](satisfaction-shapes.md)
- [Definition feedback](definition-feedback.md)
- [Product catalog](../products/README.md)
- [Ingredient register](../ingredients.md)
