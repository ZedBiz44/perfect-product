# Facebook Research (OpenClaw/AI groups)

[Repository home](../../README.md) · [Decision guide](../current-direction.md) · [Notion source](https://app.notion.com/p/3e9a3e33d58181d6b0e9e46a8c76bde5?pvs=204)

Imported 2026-09-29. Source last edited: 2026-09-28T20:38:35.594Z. Original research and proposals are preserved below; see the decision guide for corrections across pages.

---

> **Observed 28 Sep 2026**, read-only from Jack's Facebook profile. Counts are exactly as Facebook showed them. Feed samples are partial (about 10-20 posts per group), not full two-week reads. 10 groups deep-read. Chinese and Vietnamese groups were not read.

## Top 5 findings
1. **Gated grab-and-use assets are the single biggest engagement driver.** "Comment WORD, get the asset" posts pull 5 to 20 times the comments of normal posts. Examples: the 8,000+ n8n templates "Bundle" post drew 42 likes, 211 comments and 7 shares (AI Hub, 154K); the "CRM" giveaway drew 42 likes / 131 comments / 13 shares; Hermes "PACK" drew 73 comments; the "OUTREACH" workflow drew 17 comments. Almost all of these come from members, not owners.
2. **The biggest group owners have huge audiences but no visible product.** The 451K, 428K, 154K, 123K and 103K groups showed no priced owner offer. The few visible sellers are Paul Irvine's AWS and OpenClaw setup tutorial opt-in funnel (106K group; only the owner may sell), AgentMail (Hermes group, 78K), and the 140K group's admin pages running free agency webinars and "comment SUITE" funnels. Owners have attention but nothing to hand members each week, which makes them the shovel buyers.
3. **Member pain points are operational, not beginner hype.** Updates breaking things ("the update situation will sink Hermes just like OpenClaw", 27 comments); memory and context loss; agent-to-agent hand-offs; capping tool calls; installs crashing on small servers (t3.micro); local models and hardware (DGX Spark thread, 113 comments; RTX 3090, 23 comments); and beginner roadmaps (14 comments).
4. **Agent operating assets are an open gap.** Searches found no `SOUL.md`, skill-file or agent-config shares. What does get shared is n8n workflows, Claude command and prompt cheat sheets, and `CLAUDE.md` project templates (4 reactions, 4 comments). Nobody is supplying ready-made agent configs, hand-off SOPs, memory-cleanup routines or health checks, which are exactly Jack's strengths.
5. **The feeds are flooded with spam, subscription resale and low-value prompt graphics** (about 1 like each), and members complain about it. Concrete help questions and failure stories get the engagement. A curated, quality weekly asset drop would stand out, and it solves the owners' content problem.
## Implications for the shovel play
- **The weekly drop should be agent operating packs.** Ready-made agent configs and skill files, hand-off SOPs, memory-cleanup routines and health checks. Nobody in these groups supplies them (Finding 4), and they match Jack's strengths.
- **Priority topics come straight from member pain (Finding 3):** update-safe setup, memory hygiene and context recovery, agent-to-agent hand-offs, tool-call caps, installs on small servers, and health checks.
- **Use the "comment WORD" format as the lead magnet.** It is the proven engagement format in these groups (Bundle 211 comments, CRM 131, PACK 73). A free sample from the weekly pack, gated behind a comment word, is the entry point.
- **Sell to the owners, not only to members.** The 451K, 428K, 154K, 123K and 103K groups show no priced owner product. A ready-made weekly asset for their members fills that gap without the owner having to create it.
- **Respect the selling rules; go through the owner.** In the 106K group only the owner may offer paid services, and the 451K group's bot declines posts with links (links go in comments). A partnership with the owner is the compliant route in.
- **Small, specific and working beats volume.** Low-value prompt graphics get about 1 like each, and a post saying "Most businesses don't need another template" (9 reactions, 8 comments) pushes back on 8,000-template dumps. The drop should be a few tested assets per week, not a library.
## Groups overview
Top 15 by size from Facebook group search. Groups 1, 3, 5, 7 and 11 are broad automation groups that put OpenClaw in the name.

| # | Group | Members | Privacy | Owner / admins | What the owner sells |
| --- | --- | --- | --- | --- | --- |
| 1 | [AI Agents \| N8N \| OpenClaw \| Automation, Templates & Workflows](https://www.facebook.com/groups/aibusinesstools/) | 451.0K (90+ posts/day) | Public | John Webber, Raphael Fabre (admins). No moderators. | Nothing visible |
| 2 | [OpenClaw Community](https://www.facebook.com/groups/1577315533418837/) | 428.0K | Public, Jack member | Felix Nguyen (admin). No moderators. | Nothing sold or priced |
| 3 | [AI Hub - Claude, OpenClaw, n8n](https://www.facebook.com/groups/1774502687274720/) | 154.4K (60+ posts/day) | Public | Krystian Wojtarowicz (admin); Aica Marie (moderator) | Nothing priced |
| 4 | [OpenClaw Community - The AI Agent](https://www.facebook.com/groups/marketingngrowth/) | 140,072 | Public | Admin pages: Free AI Guides, AI PlanetX - AI Guide, GrowthRadars, AI for Everyone, Kabir AI Guide, Altiam AINetwork, Sumon Kabir; Md Fahim Mahmud (moderator) | Free agency webinar and "Comment 'SUITE' for Access" funnel. No price or URL. |
| 5 | [Best AI Agents Community \| Claude \| Hermes \| n8n \| Chatgpt \| Openclaw](https://www.facebook.com/groups/1427869272255595/) | 123.1K (50+ posts/day) | Public | B-Kash JO Si (admin). No moderators. | Nothing visible |
| 6 | [OpenClaw (AKA MoltBot, AKA Clawdbot)](https://www.facebook.com/groups/openclawusers/) | 106,820 | Public, Jack member | Paul Irvine (owner, verified); Lisa Irvine (admin); Ydnar Camporedondo, Rusty Cole (moderators) | AWS + OpenClaw full setup tutorial (opt-in landing-page funnel). No price visible; link not captured. |
| 7 | [OpenClaw \| Automation: n8n, Make \| Codex \| AI Agents \| Claude AI](https://www.facebook.com/groups/1050679009595609/) | 103,566 | Public | JP Ahovi, Jean-Paul Lovissoukpo (admins); Yano Fadebi (moderator) | No product, no price |
| 8 | [Hermes-Agent Community](https://www.facebook.com/groups/1283855437217819/) | 78,533 | Public | SA Hin, Mh Sahin, Elixir Bond (admins) | AgentMail email API ([agentmail.to](http://agentmail.to)). No price. |
| 9 | [AI Agents (OpenClaw, Grok Bot, Hermes, Etc.)](https://www.facebook.com/groups/openclawgroup/) | 64,580 | Public, Jack member | Group by René Remsik; Clarence + 2 other admins (Jeff J Hunter posts as admin); Jason Perlow (moderator) | No product or price in the About |
| 10 | [OpenClaw(Clawdbot.Moltbot)龍蝦助理中文社團](https://www.facebook.com/groups/1971161090129755/) | 58K | Public (Chinese) | Not read | Not read |
| 11 | [Automation \| Claude \| AI Agents \| Zo \| Openclaw](https://www.facebook.com/groups/ai.tools.coding180/) | 56K | Public | Not read | Not read |
| 12 | [OpenClaw for Business Owners - (formerly Clawdbot and Moltbot)](https://www.facebook.com/groups/openclawbusiness/) | 34,835 | Public, Jack member | Jerry O Brien (only admin shown) | No price or Skool |
| 13 | [Hermes Agent (nous research)](https://www.facebook.com/groups/955807913520070/) | 29K | Public | Not read | Not read |
| 14 | [OpenClaw Việt Nam](https://www.facebook.com/groups/1655958215309281/) | 28K | Public (Vietnamese) | Not read | Not read |
| 15 | [OpenClaw Community - FREE Help & Support](https://www.facebook.com/groups/openclawsupport/) | 18K | Public, Jack member | Not read this pass | Not read this pass |

**Also seen (not in the top 15):** Hermes Agent For Business 17K; Artificial Intelligence \| Claude - OpenClaw Support Group 16K; Hermes AI Agents Community 14K; OpenClaw Community (Learn & Earn) 14K; OpenClaw x Hermes 13K; [OpenClaw AI Community (Formerly Clawdbot, Moltbot)](https://www.facebook.com/groups/986811690672846/) 11K (Jack member); Agentic AI (Hermes, OpenClaw, ...) 10K; OpenClaw Beginners 9K.
## Group deep-dives
### 1. AI Agents \| N8N \| OpenClaw \| Automation, Templates & Workflows (451.0K)
- **About:** Created Oct 13, 2024. "Ready to go beyond basic prompts? This is where we build the future of automated business." Promises hands-on AI agents, n8n workflows and "practical templates." 90+ posts/day.
- **Admins:** John Webber (digital creator, 3,552 followers), Raphael Fabre. No moderators.
- **Rules:** A bot auto-declines posts for, among other things, a link in the post ("You can post links in comments"), members under 3 days old, FB accounts under 12 months old, and 60+ spam keywords.
- **What's sold:** Nothing visible. No Skool, course, template pack or price in the About, the feed, or searches for "template" or "skool".
- **Pain points:**
	- Beginner roadmaps. Rana Ikram: "how to start, what skills I should learn first, and the best free resources or roadmaps".
	- Agents going down. Hovhannes Hunanyan: "My Hermes agent went down this afternoon. Every message I sent through Telegram crashed."
	- AI rollout drift (Gregory Rosner).
- **Top posts:**
	- Rana Ikram's beginner question: 9 likes, 14 comments (the top comment count seen in this group).
	- Hovhannes Hunanyan's Hermes crash: 7 likes, 6 comments.
	- Susoma Ghosh's "Giving away the Clipix code for free. Just comment 'Code'": 4 likes, 7 comments.
	- Gregory Rosner on AI rollout drift: 5 reactions, 1 comment.
- **Asset demand:** "Comment 'Code'" giveaway (above). "20 CLAUDE PROMPT TEMPLATES" (Earn Online with SEO): 1 like, 0 comments. A lead-email autopilot template: 4 reactions, 0 comments. Generic prompt and template graphics get almost no engagement.
### 2. OpenClaw Community (428.0K)
- **About:** "Welcome to Moltbot Community! Your hub for AI discussions, automation tips..."
- **Admins:** Felix Nguyen (digital creator). No moderators.
- **Rules:** No rules block.
- **What's sold:** Nothing sold or priced.
- **Pain points:** None captured. The feed is mostly general AI news and off-topic posts.
- **Top posts:** Jonathan Vitela's Anthropic model comparison chart: 7 likes, 2 comments, 1 share. A GLM video: 706.8K views.
- **Asset demand:** Searching the group for `SOUL.md` returned no posts.
### 3. AI Hub - Claude, OpenClaw, n8n (154.4K)
- **About:** Created Aug 26, 2025. Promises "ready-to-use workflows, AI agent setups, templates, tutorials", "Ready-to-copy n8n workflows" and "Free templates, blueprints". 60+ posts/day.
- **Admins:** Krystian Wojtarowicz (digital creator, 2,111 followers). Moderator: Aica Marie.
- **Rules:** None.
- **What's sold:** Nothing priced.
- **Pain points:** Mirza Ajmal: "Most n8n builders are sitting on workflows worth real money with no clean way to sell them."
- **Top posts (the strongest asset-demand posts seen in any group):**
	- M. Hassaan Ghafar (member): "8,000+ templates. One massive automation library. Comments 'Bundle' and I sent you the link." 42 likes, 211 comments, 7 shares.
	- Susoma Ghosh (member): "A CRM with UNLIMITED AI. And your own Jarvis running it." Comment "CRM". 42 likes, 131 comments, 13 shares.
	- Aditya Amberkar (member): "Comment 'OUTREACH' and I'll send you the workflow" (n8n cold email). 10 reactions, 17 comments.
- **Asset demand:** All three top posts are member-run "comment WORD" giveaways. The About promises ready-to-copy assets, but the gated asset posts come from members, not the owner.
### 4. OpenClaw Community - The AI Agent (140,072)
- **About:** Unofficial hub for install, Docker/Node/Python, workflows, sandboxing and skills. +374 members last week, 32 posts last month.
- **Admins:** Pages: Free AI Guides, AI PlanetX - AI Guide, GrowthRadars, AI for Everyone, Kabir AI Guide, Altiam AINetwork, Sumon Kabir. Moderator: Md Fahim Mahmud.
- **Rules:** No unverified executables or malicious skills; no promotions or spam.
- **What's sold:** Selling signals in recent media: an "AGENCY OWNERS... FREE TO ATTEND. LIMITED SEATS. THURSDAY, SEPTEMBER 24" webinar graphic, and "\$30K/year... \$90K/year... \$0/year. Comment 'SUITE' for Access." No price or URL.
- **Pain points / top posts:** Jerry Chen asked whether an agent can edit three 40-minute interview recordings into a finished video: 5 comments.
- **Asset demand:** The "Comment 'SUITE'" funnel (counts not captured).
### 5. Best AI Agents Community \| Claude \| Hermes \| n8n \| Chatgpt \| Openclaw (123.1K)
- **About:** No About text. Created Feb 7, 2026. 50+ posts/day.
- **Admins:** B-Kash JO Si (digital creator). No moderators.
- **Rules:** None.
- **What's sold:** Nothing visible.
- **Pain points / top posts:** Not captured (partial read).
- **Asset demand:** Web Fueled's reel "Comment 'PROMPT' and I'll send you the free prompt..." showed no visible counts. "20 Ways I Use Claude AI - The Ultimate Checklist": 1 like, 1 share.
### 6. OpenClaw (AKA MoltBot, AKA Clawdbot) (106,820)
- **About:** +21 members last week, 38 posts last month. Recent feed is thin and mostly admin welcome posts.
- **Admins:** Owner Paul Irvine (verified, group expert). Admins: Paul Irvine, Lisa Irvine. Moderators: Ydnar Camporedondo, Rusty Cole.
- **Rules:** No self-promotion or service solicitation; only the owner may offer paid services. No DMs offering setup or consulting unless asked publicly. English only.
- **What's sold:** Featured post from Jan 30: "I've just released my FULL setup tutorial for setting up a new Amazon AWS Server AND OpenClaw", an opt-in landing-page funnel. 22 likes, 8 comments, 2 shares. No price visible.
- **Pain points:**
	- Small-server installs: a comment on the tutorial said the install crashed on t3.micro and was "progressing on t3.large, which is 8GB."
	- Context loss. Cri Stian: "Ever had Claude Code or Codex lose the plot after /clear, a crash, context rotation..." (0 reactions).
	- Memory. Guy Hutchins: "What are you using for your AI's memory?"
	- Business use cases. Keith Baxter asked about parsing forms for insurance quotes ("I'm paying \$300/mo for a...").
- **Top posts:** Paul Irvine's setup tutorial (22 likes, 8 comments, 2 shares). From Jan, Harlan Kilstein's "100 UNEXPECTED THINGS CLAWDBOT CAN DO": 6 likes, 6 comments.
- **Asset demand:** No `SOUL.md` or skill files shared.
### 7. OpenClaw \| Automation: n8n, Make \| Codex \| AI Agents \| Claude AI (103,566)
- **About:** Created Dec 14, 2023. +2,383 members last week, 15 posts today, 418 last month.
- **Admins:** JP Ahovi and Jean-Paul Lovissoukpo (8,290 followers). Moderator: Yano Fadebi (14,230 followers).
- **Rules:** None.
- **What's sold:** No product, no price.
- **Pain points:** Hype fatigue. Creed Technology's "AI Tools Hype vs Real World Performance" called OpenClaw "Sounds revolutionary, feels underutilised." 8 reactions, 2 comments, 3 shares.
- **Top posts:** Diya Dutta Ghosh: "8,000+ automation templates are useless in front of this" and "Most businesses don't need another template." 9 reactions, 8 comments, 2 shares. Creed Technology's post (above). The feed is mostly zero-engagement promo.
- **Asset demand:** A salon booking assistant post said to comment "Demo". The template search found mostly Claude-command prompt graphics with about 1 like each.
### 8. Hermes-Agent Community (78,533)
- **About:** Created March 30, 2026. "Powered by AgentMail... [agentmail.to](http://agentmail.to)", "not affiliated with Nous Research". 41 posts today, 442 last month.
- **Admins:** SA Hin, Mh Sahin, Elixir Bond.
- **Rules:** None.
- **What's sold:** The owner's visible product is AgentMail (email API). No price.
- **Pain points:**
	- Updates. Bill Ryder: "the update situation will sink Hermes just like OpenClaw... no longer suitable for production... new updates so really breaks things." 9 reactions, 27 comments (with pushback).
	- Hardware. Josh Underwood called the DGX Spark an "overpriced cookie cutter option": 17 reactions, 113 comments.
	- Local models. RTX 3090 local-model question: 6 reactions, 23 comments. Output truncated at around 4K tokens with Qwen on a 3090: 7 reactions, 15 comments.
	- Subscription-resale scams are called out by members.
- **Top posts:** DGX Spark thread (17 reactions, 113 comments); "do you use hermes for coding?? (Read my comment)" (17 reactions, 66 comments); "What's the best open source model to run with Hermes free?" (10 reactions, 44 comments); "Grok 4.7 is here" (40 reactions, 18 comments); Bill Ryder's update post (9 reactions, 27 comments).
- **Asset demand:** Shahbaz Malik: "Comment 'PACK'" for a free AI video workflow, prompts and templates pack: 2 reactions, 73 comments.
### 9. AI Agents (OpenClaw, Grok Bot, Hermes, Etc.) (64,580)
- **About:** No product or price in the About. 37 posts today, 509 last month, +2,378 members last week.
- **Admins:** Group by René Remsik. Admins: Clarence and 2 others (Jeff J Hunter posts as admin). Moderator: Jason Perlow.
- **Rules:** Not captured.
- **What's sold:** Nothing seen (no product or price in the About).
- **Pain points (Muse FM's questions, each 0 reactions):**
	- "When your agent's long-term memory fills up with stale facts, what is your cleanup routine?"
	- "Agent-to-agent handoffs... what do you actually trust: the summary, the full log, or neither?"
	- "Do you cap how many tool calls your agent gets per task?"
	- Also: "What's one repetitive task you wish AI could handle?" (answer given: lead sorting and follow-up): 2 reactions, 1 comment. Subscription-resale spam, with an angry member reply.
- **Top posts:** Low engagement overall. "EVERY CLAUDE COMMAND" cheat sheet: 5 reactions, 3 comments. "Claude Code Project Template" (`CLAUDE.md`, skills, hooks): 4 reactions, 4 comments.
- **Asset demand:** The two posts above, plus "Comment 'agent'" for 9 agent prompts and "comment prompts", both at about 0 engagement.
### 10. OpenClaw for Business Owners (34,835)
- **About:** A lab for owners of \$1M-\$10M businesses (self-hosting, channels, guardrails, ROI). +129 members last week, 219 posts last month.
- **Admins:** Jerry O Brien (the only one shown).
- **Rules:** No promo or spam.
- **What's sold:** No price or Skool.
- **Pain points:** Not captured.
- **Top posts:** The feed is mostly other people's offers. [Roomz.work](http://Roomz.work) (AI agents plus team workspace): 0 reactions. Claude/Higgsfield subscription resale: 1 like, 1 comment. DFWBots subscription-cancellation graphics. The featured posts are old.
- **Asset demand:** None seen.
### Earlier small-group review (27 Sep)
Ten small public OpenClaw, Clawdbot and Moltbot groups (17 to 260 members). Six were dormant and two were spam. 9BizClaw (260) is Vietnamese and mostly the admin selling workshops (Early Bird 99k VND) and courses. Mastering NemoClaw (23) sells an insider-list CRM.
## Asset demand log
Every asset share or request post in the raw findings. "Member" = noted as a member in the findings; "Non-admin" = not one of the listed admins; "—" = not recorded (not zero).

| Group | Author (type) | Asset | CTA word | Likes / reactions | Comments | Shares |
| --- | --- | --- | --- | --- | --- | --- |
| #3 AI Hub (154.4K) | M. Hassaan Ghafar (Member) | 8,000+ templates automation library | Bundle | 42 | 211 | 7 |
| #3 AI Hub (154.4K) | Susoma Ghosh (Member) | "A CRM with UNLIMITED AI. And your own Jarvis running it." | CRM | 42 | 131 | 13 |
| #8 Hermes-Agent Community (78,533) | Shahbaz Malik (Non-admin) | Free AI video workflow, prompts and templates pack | PACK | 2 | 73 | — |
| #8 Hermes-Agent Community (78,533) | — | "do you use hermes for coding?? (Read my comment)" | — ("Read my comment") | 17 | 66 | — |
| #8 Hermes-Agent Community (78,533) | — | Request: "What's the best open source model to run with Hermes free?" | — | 10 | 44 | — |
| #6 OpenClaw (AKA MoltBot) (106,820) | Paul Irvine (Owner) | Full AWS + OpenClaw setup tutorial (opt-in funnel) | — (opt-in page) | 22 | 8 | 2 |
| #3 AI Hub (154.4K) | Aditya Amberkar (Member) | n8n cold-email workflow | OUTREACH | 10 | 17 | — |
| #7 OpenClaw \| Automation (103,566) | Diya Dutta Ghosh (Non-admin) | Anti-template post: "8,000+ automation templates are useless in front of this" | — | 9 | 8 | 2 |
| #1 AI Agents \| N8N (451.0K) | Susoma Ghosh (Non-admin) | Clipix code, free | Code | 4 | 7 | — |
| #6 OpenClaw (AKA MoltBot) (106,820) | Harlan Kilstein (Non-admin) | "100 UNEXPECTED THINGS CLAWDBOT CAN DO" (Jan) | — | 6 | 6 | — |
| #9 AI Agents (64,580) | — | "EVERY CLAUDE COMMAND" cheat sheet | — | 5 | 3 | — |
| #9 AI Agents (64,580) | — | "Claude Code Project Template" (`CLAUDE.md`, skills, hooks) | — | 4 | 4 | — |
| #1 AI Agents \| N8N (451.0K) | — | Lead-email autopilot template | — | 4 | 0 | — |
| #1 AI Agents \| N8N (451.0K) | Earn Online with SEO (Non-admin) | "20 CLAUDE PROMPT TEMPLATES" | — | 1 | 0 | — |
| #5 Best AI Agents Community (123.1K) | — | "20 Ways I Use Claude AI - The Ultimate Checklist" | — | 1 | — | 1 |
| #7 OpenClaw \| Automation (103,566) | Various | Claude-command prompt graphics | — | About 1 each | — | — |
| #1 AI Agents \| N8N (451.0K) | Various | Generic prompt and template graphics | — | Almost no engagement | — | — |
| #9 AI Agents (64,580) | — | 9 agent prompts | agent | About 0 engagement | — | — |
| #9 AI Agents (64,580) | — | Prompts | prompts | About 0 engagement | — | — |
| #5 Best AI Agents Community (123.1K) | Web Fueled (Non-admin) | Free prompt (reel) | PROMPT | No visible counts | — | — |
| #4 OpenClaw Community - The AI Agent (140,072) | Admin pages (Admin) | "\$30K/year... \$90K/year... \$0/year" offer | SUITE | — | — | — |
| #7 OpenClaw \| Automation (103,566) | — | Salon booking assistant demo | Demo | — | — | — |
| #3 AI Hub (154.4K) | Mirza Ajmal | Demand signal: "Most n8n builders are sitting on workflows worth real money with no clean way to sell them." | — | — | — | — |

**Searches with no results:** `SOUL.md` in OpenClaw Community (428.0K) returned no posts. No `SOUL.md` or skill files shared in OpenClaw (AKA MoltBot) (106,820).
## Not covered / next steps
- **Unread groups:** OpenClaw(Clawdbot.Moltbot)龍蝦助理中文社團 (58K, Chinese), Automation \| Claude \| AI Agents \| Zo \| Openclaw (56K), Hermes Agent (nous research) (29K), OpenClaw Việt Nam (28K, Vietnamese), and OpenClaw Community - FREE Help & Support (18K, Jack member, not read this pass). The "also seen" groups were not read either.
- **Full two-week reads were not done.** Every feed sample is partial (about 10-20 posts per group). Best AI Agents Community (123.1K) was only partly read.
- **Gaps in the owner offers:** no price was visible on Paul Irvine's tutorial funnel or the "comment SUITE" offer, and no URLs were captured for either. AgentMail showed no price.
- **Next:** full two-week reads of the top English groups (especially AI Hub, Hermes-Agent Community and the 106K OpenClaw group); read the three unread English groups (56K, 29K, 18K); capture prices and links behind the owner funnels.
