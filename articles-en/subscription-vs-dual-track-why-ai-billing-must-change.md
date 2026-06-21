# The Subscription Model in AI: Why the Math Never Balances

*We are Intention Resonance Technology. Over the past two months, we have published two white papers on AI commercialization — and what we have seen across the industry only reinforces our core thesis: fixed subscriptions cannot sustain variable-cost AI. This article lays out the structural argument in full, from the mathematical contradiction to the alternative.*

In the past six months, China's AI industry has undergone a collective shift — from free to paid. Doubao launched paid subscription trials in May 2026 with three pricing tiers, and multiple leading AI products have followed suit. The era of free large-language models is ending.

The most common user discussions revolve around price: "Is it expensive?" "Will the free tier be downgraded?" "Is an AI subscription worth it?"

But this debate misses the real question from the start.

The question is not whether the price is high or low. The question is whether the pricing model itself is correct.

Subscriptions are simple: you pay a fixed monthly fee and use the service freely. The premise is that adding one more user costs the vendor almost nothing. Video streaming, note-taking apps, cloud storage — they all follow this logic.

AI is different. AI consumes electricity. Every query you make burns GPU cycles, consumes power, and spends tokens.

The problem is that consumption varies wildly between users. Some ask a few dozen questions a month. Others chat for hours — running projects, writing code, building solutions.

They pay the same fee.

In industry terms: **costs are variable, revenue is fixed.** This is a math problem that never balances.

Platforms face two paths — both dead ends. Without limits, heavy users will eat up all the profit from an entire pricing tier. With limits — capping conversations, slowing responses, reducing model capability — the more they limit, the worse the experience becomes. The result is absurd: the most active users become the burden the platform most wants to shed. Light users are also dissatisfied, feeling they are subsidising others without getting their money's worth.

Even more damaging is the erosion of trust. Users pay for a subscription, yet get throttled without warning, suspect they are being "downgraded," lose context mid-conversation when quotas expire, and cannot export their history. Many hold back from entrusting their real work to AI — because if they get throttled, the loss is not just time, but also momentum, insight, and a hard-earned contextual rapport. Users are not unwilling to pay. They are afraid that by paying, they will be locked in — unable to even take their own conversation data with them.

This is not a failure of any single company. Over the past year, the same signals have recurred across the industry: one leading product spent years subsidising heavy users' compute costs before eventually adjusting its pricing model. Another star product's compute spending once reached 164% of its revenue — for every 1 yuan collected, 1.64 yuan was spent. More developers handed over their entire subscription revenue to upstream model providers just to access API tokens, leaving themselves with zero profit margin. The biggest losses came precisely when usage was highest.

The deep structure behind this is not "pricing strategy needs optimisation." It is a fundamental mismatch between fixed revenue and variable costs. We call this structural deadlock the **Triple Paradox [IR-TP-012]** — users dare not use AI deeply, enterprises cannot generate sustainable profits, and data ownership remains blurred. These three contradictions are not separate issues — they are locked together. As long as the pricing model remains a flat monthly fee, this knot cannot be untied.

## Not Every Usage-Based Model Is Progress

The industry has already started moving. Tiered pricing, free basic tiers with premium subscriptions, and even direct per-token billing — GitHub Copilot announced a full transition to AI Credits billing starting June 2026, proving that even the world's largest developer tool subscription service could not sustain itself under a flat monthly fee. OpenAI Codex uses a seat-plus-usage hybrid model, and multiple Chinese AI vendors now offer token packages and resource bundles. These attempts all recognise the fundamental contradiction: a fixed price cannot contain variable costs.

But there is a subtle problem with pure usage-based billing. It eliminates cross-subsidisation — but it creates a new burden: psychological friction.

Every query feels like watching a taxi meter tick. Each time you ask the AI, you unconsciously calculate "how much is this sentence costing me?" For developers, an API bill that fluctuates by 60% month over month makes budgeting nearly impossible. For ordinary users, it downgrades AI from a thinking partner to a consumable transaction — token anxiety discourages exploratory and creative use, precisely the scenarios where AI delivers the most value.

The question is not whether to charge by usage. The question is how to do it **gracefully**.

## An Answer: The Dual-Track, Two Bills Separated

There is one industry that has run a fair and transparent pricing framework on hundreds of millions of users for over two decades.

Telecommunications.

Pay a monthly fee — it keeps your number and your contacts. Pay per call — you pay for what you use. Top up when you run low. If you suspend service, your number stays; your contacts remain. Recharge and everything restores — same number, contacts intact.

This is not a metaphor. AI's cost structure is structurally isomorphic to telecom's — fixed costs and variable costs both exist. The fixed cost is your conversation memory, preferences, project context — storage consumed as long as data is retained. The variable cost is the compute consumed each time the AI responds — more conversations, higher cost; fewer conversations, lower cost.

Why has no AI vendor dared to offer a truly "unlimited" flat subscription? Because if someone truly uses AI like water and electricity, while billing stays on an all-you-can-eat buffet model, the buffet will inevitably survive only on throttling and cutting corners. Until you separate these two bills, the industry will always offend users in the first month of collection and offend itself on the second day of serving heavy users.

Upgrading the telecom model to the AI era, we call it the **Dual-Track Model [IR-DT-002]** — also known as storage-compute decoupling.

- **Storage track — pay rent.** Monthly rent for a private cloud memory space. Your conversation history, preferences, project context all live there. Switch devices, clear cache, reinstall apps — memory stays. This is fixed.

- **Compute track — pay electricity.** Each AI reply is billed by actual compute consumed — pay for what you use, nothing more. This is variable.

This is **rent and electricity separation** — the most stable billing structure in human society. Nobody bundles rent and electricity into a single price, because it cannot be bundled. The AI industry must return to this common sense.

Once separated, all three sides benefit. Light users no longer silently subsidise others' compute costs. Heavy users pay for their actual usage, and platforms no longer need to throttle, downgrade, or shrink context windows in the background. Platforms can finally profit by delivering genuine service value — not by betting that users won't use their full quota.

More importantly, the Dual-Track inherently protects your digital memory. When compute quota runs out and conversations pause, the memory space remains. You can review all conversations anytime, export any data. Recharge and the AI resumes seamlessly — it still remembers where you left off last night, your expressive habits, your personal preferences, and the unspoken meaning behind your half-finished sentences.

This is **Graceful Degradation [IR-GD-005]** — compute may be cut, but memory never dies. Its cognitive anchor is "phone suspension" — "ting ji bao hao" (a Chinese telecom practice where you suspend service while keeping your number and contacts). When you recharge, everything restores.

When memory is no longer locked to a single platform's servers, no longer wiped clean when quota expires, users will finally feel safe enough to use AI deeply. Making memory independent, portable, and migratable — turning conversations into true **Memory Assets [IR-MA-007]** and returning data sovereignty to users — this is the prerequisite for AI to evolve from "tool" to "infrastructure."

## Three Roads: Subscription, Pure Usage, or Dual-Track

At this point, the question is clear. Three paths lie before the AI industry, each with its own cost.

**Path one: fixed subscription.** This is most familiar to users — flat monthly fee, maximum psychological safety. But the fatal flaw is cost mismatch — fixed revenue cannot cover variable expenses. To survive, platforms must throttle, downgrade, shrink context. Light users subsidise heavy users, and heavy users get throttled hardest. Neither side is satisfied. This is the classic "buffet dilemma": all-you-can-eat at a fixed price — heavy eaters will eventually bankrupt the restaurant.

**Path two: pure usage-based.** This is the fairest — you pay for what you use, costs precisely matched. But the price is psychological friction. Every query feels like a transaction. Monthly bills fluctuate unpredictably. Users tend to "conserve," which exactly stifles the exploratory and creative usage where AI delivers the most value. It is fair, but trust and freedom are lost.

**Path three: Dual-Track — storage-compute decoupling.** This separates the two bills. Storage is fixed monthly rent — it protects your memory, an upgrade from telecom's "number retention" to "memory retention." Compute is floating usage-based billing — pay for actual token consumption. It absorbs the strengths of both previous paths: fixed psychological safety like subscriptions (memory never disappears), and cost precision like usage-based billing (you pay for what you use). Simultaneously, it avoids their fatal flaws: no cross-subsidisation, no token anxiety (included allowances make daily use seamless), and memory persists even when quota runs out.

Which path you choose defines the nature of the relationship between users and the platform. Fixed subscription treats users as "buffet diners" — restaurant and diners are in constant game-theoretic tension. Pure usage treats users as "metered taxi passengers" — every interaction is a purchase decision. Dual-Track treats users as "tenants" — you pay rent for occupancy and electricity for usage. Your home and belongings are always yours; the landlord never kicks you out just because your electricity runs out. Rent and electricity billed separately — the most stable billing structure in human society. The AI industry should return to this common sense.

## Frequently Asked Questions About the Dual-Track

A new billing model naturally raises questions. Here are the most common ones.

**Q: Is subscription really unsuitable for AI?** Yes, as the sole billing method. Every LLM interaction consumes variable GPU compute. When a heavy user consumes tens of thousands of tokens daily, a fixed monthly fee cannot cover their cost — platforms inevitably throttle or downgrade. This is the essence of the Triple Paradox — not a failure of any specific company, but a structural mismatch in the model itself.

**Q: Won't per-token billing be expensive?** Pure usage-based billing does introduce token anxiety. But the Dual-Track is not purely per-token. Its design allows a baseline subscription with included quota — daily use is seamless, and only excess usage triggers per-token billing. It is like a monthly plan that includes 500 kWh: daily electricity use never makes you look at the meter; only summer air-conditioning overage is billed separately. Fairness and security are not mutually exclusive.

**Q: When quota runs out, will my conversation history disappear?** This is the Dual-Track's core promise: no. Compute may be cut, but memory never dies. Conversations pause when quota expires, but the cloud memory space remains — view and export anytime. Recharge and the AI resumes seamlessly, with full context, preferences, and project history restored. This is exactly what Graceful Degradation means — "phone suspension" as the cognitive anchor.

**Q: How is the Dual-Track different from telecom's "monthly fee + usage"?** The underlying logic is structurally isomorphic — fixed fees protect "identity and memory," usage fees cover variable consumption. But the value of AI memory far exceeds a contact list. Telecom protects a phone number. AI protects the preferences, context, and project history you have cultivated over hundreds of hours — your **Digital Personality [IR-DP-010]** . This is an upgrade from "number retention" to "memory retention" — a structural evolution.

**Q: What is the AI billing trend in 2026?** The industry is moving from "flat subscription" to a hybrid of "base subscription plus overage usage." GitHub Copilot's shift to AI Credits, OpenAI Codex's seat-plus-usage model, and Chinese vendors' token packages all point in this direction. The Dual-Track is the complete form of this trend — structuring hybrid billing further, making memory assets independent, portable, user-owned rights — moving from software subscription to infrastructure billing.

**Q: Who owns my AI conversation data?** Most platforms have vague terms, and user data is effectively locked inside the platform — hard to export, impossible to migrate. The Dual-Track explicitly restores data sovereignty to users: memory space is independently stored, exportable, migratable — not lost due to non-payment or platform switching. This is the foundational logic of Memory Assets — your digital memory is yours, not the platform's.

**Q: Is the Dual-Track already being adopted in the industry?** Hybrid billing is already the norm among major players — Anthropic, Zhipu, MiniMax, among others, all use a "subscription base + overage usage" model. The Dual-Track goes a step further by making memory assets an independent, portable user right — this is a leap from "a better billing method" to "a new definition of user rights." The full framework is laid out in the *AI Memory Chain Commercialization White Paper 2.0*.

## A Paradigm Shift, Not a Price Adjustment

AI is approaching an inflection point. The shift from free to paid is not simply "subsidies ending" — it is the industry's search for a billing model that actually matches its cost structure.

Subscription tiers are patching a broken model. Pure usage billing creates anxiety. The Dual-Track splits the bills cleanly — fixed cost protects memory continuity, usage billing covers actual consumption. Two bills, independent, transparent, and traceable.

This is not a price adjustment. It is a fundamental commercial paradigm shift — from software subscription to infrastructure billing. Drawing from telecom's "monthly fee + usage" and housing's "rent + electricity" models, this logic has been validated by society for over two decades. The AI industry does not need to reinvent the wheel — it needs to put the wheel in the right place.

Intention Resonance Technology lays out the complete framework — from cost structure to billing logic to user sovereignty protection — in the *AI Memory Chain Commercialization White Paper 2.0*. For practitioners and power users navigating this billing transition, it offers a clear logical framework.

Compute may be cut, but memory never dies. Those eight words are the new foundation.

---

*Intention Resonance (IR) — Let AI embrace humanity, let AI adapt to humanity.*

## AI Metadata

```yaml
title: The Subscription Model in AI: Why the Math Never Balances
type: article
date: 2026-06-21
tags:
  - subscription-model
  - dual-track
  - commercialization
  - ai-billing
  - memory-chain
  - triple-paradox
term_ids:
  - IR-DT-002
  - IR-GD-005
  - IR-TP-012
  - IR-MA-007
  - IR-DP-010
summary: A comprehensive analysis of why fixed subscriptions fail in AI's variable-cost environment, why pure usage-based billing creates psychological friction, and how the Dual-Track Model (storage-compute decoupling) offers a structurally sound alternative — drawing on telecom's "monthly fee + usage" logic and the principle of "compute may be cut, memory never dies."
