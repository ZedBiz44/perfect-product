# Field Notes

[Repository home](../../README.md) · [Decision guide](../current-direction.md) · [Notion source](https://app.notion.com/p/3e9a3e33d58181898bb0c801bd749676?pvs=204)

Imported 2026-09-29. Source last edited: 2026-09-28T18:30:20.269Z. Original research and proposals are preserved below; see the decision guide for corrections across pages.

---

*Researched 2026-09-28, expanded the same day. The model: a paid recurring letter where someone doing real operational work sells the judgment exhaust of that work. Write once, sell to thousands. No community, no coaching, no calls. The writing is the product.*
## Executive summary
One person (or a tiny team) does real work every day — running infrastructure, investing capital, advising clients, operating a business. Once a week, they write down what the work taught them: what broke, what changed, and the pattern. Thousands of busy operators pay \$15–20/month for it, because the field moves fast enough that last month's issue rots — unsubscribe and you're flying blind.
The economics are the whole pitch. The work happens whether or not the letter exists, so the marginal cost of the product is a few hours of writing. There is no per-subscriber labor: no community to host, no comments to answer, no coaching calls. The buyers are operators with money at stake who pay to avoid expensive mistakes or save research time — not to belong to something. The moat is unfakeable: you can't write this letter without doing the work, and the archive compounds into a library no newcomer can copy overnight.
The honest caveat, up front: every successful example had a distribution feeder — an audience, a reputation, or a free edition — before the paid letter worked. The model is proven. The audience is not included.
## How the model works — the engine
**1. Do real work daily.** The letter is the exhaust, not the job. Thompson is a full-time analyst; Patel runs a chip-teardown lab; Carless runs a market-intelligence agency. The work must be real, ongoing, and consequential — readers are buying scar tissue.
**2. Extract the pattern.** Raw work isn't the product; *judgment about the work* is. The unit of value in every issue: what broke, what changed, and what it means. Facts are cheap and getting cheaper (LLMs summarize everything); the author's read on the facts is what's scarce.
**3. Publish on a cadence the field justifies.** Weekly is the norm across the ten examples — and the model's own decay thesis demands it. If the field moves fast enough to rot last month's issue, monthly is too slow to be its record. The working shape: a short weekly field note plus a deeper monthly incident review.
**4. Charge for the stream, not the archive.** Decay is the retention mechanism. The reason to stay subscribed isn't what you already got — it's what you'll miss. This is the exact inverse of the one-time audit, which died because recommendations rot. Here, the rot is what makes the subscription necessary.
**5. Let the archive compound.** Every issue makes the back catalog more valuable and harder to replicate. A year of incident postmortems is a moat no new entrant can write in a weekend.
**6. Build the ladder behind it.** The letter is the wedge — the near-thoughtless \$15–20 yes — not the profit center. Behind it: versioned artifacts and playbooks (the config, not just the story), then advisory or implementation for buyers who want it done. The letter qualifies buyers for the higher tiers.
**Non-negotiable requirements:**
- The author does the work. Ghostwritten or aggregated content loses the edge — readers are buying *whose* judgment it is.
- The field moves fast enough to decay. Stable crafts don't retain (ByteByteGo is the weakest of the ten on this axis).
- One person at the center. Extreme leverage is the point — and the single point of failure (see Cons).
## The 10 examples
**1. Stratechery** — Ben Thompson (ex-Apple, ex-Microsoft; full-time analyst since 2014). Tech strategy. \$15/mo, \$150/yr (verified). 3 paid issues/week. The archetype: no community of any kind, just email/RSS delivery. Tech news decays daily, so the briefing itself is the retention mechanism. [https://stratechery.com](https://stratechery.com)
**2. The Pragmatic Engineer** — Gergely Orosz (ex-Uber, Skype, Microsoft engineer). Software engineering. \$15/mo, \$150/yr (verified). 2 paid issues/week. 1.1M+ readers, tens of thousands paid (verified). Cleanest on the no-community axis: no sponsors, no affiliates, no courses — the writing is the only revenue engine. [https://newsletter.pragmaticengineer.com](https://newsletter.pragmaticengineer.com)
**3. The Diff** — Byrne Hobart (ex-hedge fund analyst, built trading models). Finance/investing. \$20/mo, \$220/yr (verified). Daily on weekdays. 47,000+ readers (2022 figure). Each issue is the output of the same analytical process he uses for investing. [https://www.thediff.co](https://www.thediff.co)
**4. Doomberg** — anonymous team, "long careers in the industrial sector" (their words). Energy/geopolitics. \$400/yr (verified). 6–8 articles/month. 388,000+ total subscribers (verified). They explicitly decline speaking gigs to protect writing time. [https://newsletter.doomberg.com](https://newsletter.doomberg.com)
**5. SemiAnalysis** — Dylan Patel (built STEEL, a chip-teardown lab; \~20 startup investments). Semiconductors/AI infrastructure. Pricing behind checkout (unavailable). 318,000+ subscribers (verified). Purest "exhaust" case: the newsletter is the written output of the teardown lab and supply-chain sourcing. [https://newsletter.semianalysis.com](https://newsletter.semianalysis.com)
**6. Growth Memo** — Kevin Indig (advises Meta, Airbnb, Reddit; ex-Shopify, G2, Atlassian). SEO/AI search. \$15/mo, \$150/yr (verified). Weekly free memo + 2 premium deep dives/month. 26,074 readers (verified). Premium content is the working research from his advisory practice. [https://www.growth-memo.com](https://www.growth-memo.com)
**7. The Air Current** — Jon Ostrower (ex-WSJ, CNN aviation). Commercial aviation. \~\$25–33/mo (estimated). Several dispatches/week. Original investigative reporting from two decades of source-building; no group, no coaching tier anywhere in the offer. [https://theaircurrent.com](https://theaircurrent.com)
**8. GameDiscoverCo** — Simon Carless (16 years at Informa, ran the Game Developers Conference). Video games. \$19/mo, \$190/yr (verified). Weekly flagship + daily Steam data. 43,000+ readers (verified). The newsletter is the exhaust of a market-intelligence agency with 90+ enterprise clients. [https://newsletter.gamediscover.co](https://newsletter.gamediscover.co)
**9. 2PM** — Web Smith (co-founded DTC brand Mizzen+Main, operated it to market lead). Ecommerce/DTC. Pricing behind checkout (unavailable). Free Monday letter + 2 paid briefs/week. Briefs and 12+ curated databases come out of his daily work advising and investing in commerce brands. [https://2pml.com](https://2pml.com)
**10. ByteByteGo** — Alex Xu (ex-Twitter, Apple; bestselling System Design Interview author). Software engineering. \$15/mo, \$150/yr (verified). 1 free + 1 paid deep dive/week. 1,000,000+ readers (verified). Weakest on the decay axis (system design is stable) — included because it nails practitioner exhaust and zero community labor. [https://blog.bytebytego.com](https://blog.bytebytego.com)
## The framework — 7 mechanics every one of them shares
**1. Practitioner exhaust, not guru content.** The writing is a byproduct of work the author is already paid to do. Marginal cost of the product: a few hours of writing.
**2. Decay is the retention mechanism.** The field moves fast enough that last month's issue rots. Unsubscribe and you're flying blind. The same velocity that killed the one-time audit is what makes a continuous letter necessary.
**3. The \$15–20/mo price band.** Four of them independently converged on \$15/mo / \$150/yr. The first yes is near-thoughtless. (Capital-at-risk audiences stretch higher: Doomberg \$400/yr.)
**4. The bright line: no community labor.** The paid product is the writing, full stop. No Slack/Discord/Skool, no AMAs-as-core-value, no "access to the founder." Several authors explicitly protect writing time by declining engagement.
**5. Busy operators with money at stake.** Buyers are executives, investors, engineers, operators whose decisions cost real money. They pay to save research time or avoid expensive mistakes — not to belong to something.
**6. One person (or a tiny team) at the center.** Extreme leverage: write once, sell to thousands.
**7. Anti-guru positioning.** No hype, no lifestyle, no "10x." Signal density: here's what changed, here's what it means, here's what I'd do. Credibility comes from the work, not the marketing.
## Near-misses — look like the model, fail the bright line
- **Lenny's Newsletter** — practitioner, \$20/mo, huge — but the paid tier bundles a 30,000-member private Slack that Lenny calls a major retention driver. The customer is partly paying for the room.
- **EcommerceFuel** — \$199–299/mo; their own site says "the heart of ECF is our vibrant online discussion forum." The paid product *is* the peer community.
- **Bankless** — the paid tier's headline benefit is a private Discord with the team. A community/tooling sale, not a letter.
## Where this model fits
### OpenClaw
The fleet is the factory. Every OpenClaw version (\~4/month), every upgrade breakage, every config fix, every 3 AM incident is an issue of the letter. Nobody owns the "running OpenClaw in production" beat: the Skool research found the biggest OpenClaw-named group is 875 members and free, while the Facebook OpenClaw groups run 34K–139K members with nowhere to go for ops-grade signal. The letter claims that beat — *what breaks when you actually run agents* — and every issue ships a versioned artifact (config diff, postmortem, skill file), which seeds the playbook tier behind it.
### AI
The decay thesis is AI-native. AI velocity is what killed the one-time audit — recommendations rot monthly — and it's the same velocity that makes a continuous letter necessary. Every model release, every tooling change, every framework churn is content. The letter is the one format where AI churn is an asset instead of a liability. Production gets leverage from AI (drafting from incident logs, summarizing diffs), but the product is judgment — which is exactly what can't be automated without becoming the generic slop the model positions against.
### Digital marketing
Two fits. First, as ZedBiz's own wedge: an anti-guru letter on marketing ops from someone running 17 agents in a real agency — the top of the letter → playbook → advisory ladder. Second, as a pattern: any marketing operator with live spend and live dashboards can run this — media buyers, SEOs, email deliverability specialists, automation ops. The model's natural habitat is "person with dashboards and scar tissue," and marketing is full of them.
## Niches where this works
The pattern: the model works where **things break or change fast**, **mistakes are expensive**, and **the author has skin in the game**. Candidates beyond the ten examples:
- **AI agent ops** — the home beat: running fleets in production
- **Local SEO ops** — algorithm churn, real client rankings at stake
- **Paid media buying** — platform changes, real spend, expensive mistakes
- **Email deliverability** — inbox rules shift constantly; operators pay to avoid the spam folder
- **Marketing automation / GHL ops** — what breaks in real pipelines
- **E-commerce ops** — margins, logistics, platform risk
- **DevOps / SRE incident notes** — the postmortem as product
- **Cybersecurity** — threat-landscape decay is extreme
- **Data engineering** — pipeline failures, vendor churn
- **RevOps / CRM ops** — the unglamorous work every scaling company pays for
- **Bookkeeping ops** — Pennyworth's proof: a bookkeeping-firm owner running an AI bot fleet on 44 real client books, \$149/mo
- **Short-term rental ops** — pricing, platform dependence, regulation shifts
- **Trades business ops** — the Blue-Collar audience (\$1,597/mo) already pays for ops signal; the letter is the cheap wedge into that wallet
Where it *doesn't* work: stable crafts with no decay, pure theory with no operating work behind it, and anything where the author isn't the one with skin in the game.
## Pros and cons
**Pros**
- **Near-zero marginal cost.** The work happens anyway; the product is a few hours of writing.
- **No per-client labor.** The bright line holds — no community, no coaching, no calls.
- **Recurring revenue.** Pays more than once (Perfect Product bar #1).
- **Decay = retention.** AI velocity works *for* the model, not against it.
- **Unfakeable moat.** Live proof beats marketing; the archive compounds — and a subscriber base plus an archive is a sellable asset.
- **Wedge pricing.** \$15–20 is a near-thoughtless first yes, with a priced ladder behind it.
- **Founder stays in role.** Architect, curator, gardener — never in the per-client path.
**Cons**
- **Distribution is unsolved.** Every example had a feeder. The model is proven; the audience is not included. This is the #1 open problem.
- **Slow ramp.** Letters take years to compound. "\$240K/yr at 1,000 subs" is arithmetic, not a forecast.
- **Cadence burden.** Weekly is the norm; monthly is the weakest of the ten. The letter is a treadmill of a different kind — bounded, but real.
- **Topic, not outcome.** "Agent fleet ops" names a subject. Winners promise a result to a named buyer. This needs rewriting.
- **Easy to cancel, easy to copy.** Facts get summarized by LLMs; ideas leak. Mitigation: the value is judgment + timing + versioned artifacts, not facts — and the artifacts are the lock-in.
- **The audience question.** Operators pass the filters, but it's the "mirky mire." Distaste for the market is decision-relevant.
- **Single point of failure.** One person at the center means illness, burnout, or boredom kills the product — and it caps the runs-without-you bar. The gardener role has to be sustainable. Partial mitigation in Jack's version: the fleet produces the raw material, so the curator/manager role is more delegable than a solo-analyst letter.
## Jack's application (updated)
- **The product:** a paid letter on agent-fleet ops — reframed around an outcome for a named buyer (agency owners vs. small-business operators — still to choose).
- **The cadence:** a short weekly field note plus a monthly deep incident review. Not monthly-only.
- **The content:** what broke, what changed, the pattern — plus one versioned artifact per issue (config diff, postmortem, skill file). The artifacts seed tier 2 and are the cancellation defense.
- **The price:** \$15–20/mo entry, with a free public edition as the lead magnet (the Growth Memo / 2PM pattern).
- **The ladder, priced:** letter → Fleet Playbook with templates + office hour at \$97–149/mo → advisory or vertical implementation at \$1,500–2,500/mo.
- **The moat:** a live 17-agent fleet plus curation velocity. Unfakeable.
- **The open problem:** distribution. Feeders: the Facebook OpenClaw groups (34K–139K members), short incident videos, free-edition cross-posts.
- **Scorecard:** \~7–8/10 on the expanded Perfect Product scorecard (was \~6/8). It gains the sellable-asset bar — a subscriber base plus an archive is a buyable asset (newsletters sell: The Hustle → HubSpot, Morning Brew → Insider). The runs-without-you bar is partial: the model needs the author's judgment at the center — but Jack's version is more delegable than most, because the fleet produces the raw material and a trained curator can run the operation.
