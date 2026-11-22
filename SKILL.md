---
name: kdp-distribution-audience-strategy-addon
description: Decide an ebook's Amazon KDP Select or wide-distribution route and turn it into a realistic, no-guarantee reader acquisition plan. Use after niche positioning and before outlining, metadata lock, or ebook production.
---
# KDP Distribution and Audience Strategy Add-on

Choose distribution before final retailer-specific metadata, cover promises, or launch planning. This produces a documented recommendation; the author retains all account and enrollment actions.

## Required inputs
Require title/project ID, rights and territories, language, genre, ebook formats, intended retailers/libraries, audience geography, author assets, budget, proposed price test, previous distribution commitments, and a current official policy capture. Missing rights information or an unverified KDP Select conflict is `BLOCKED`.

## Decision procedure
1. Define the goal and constraints: Amazon-first, exclusive KU/Select test, wide retail, library reach, no-upfront-cost preference, or combination. Distinguish platform availability from reader discovery.
2. Verify current KDP Select terms from official Amazon sources. Capture 90-day term/renewal and opt-out mechanics, digital exclusivity scope, eligibility, promotional choices, territory limitations, and what ends exclusivity. If the official terms are unclear, label `NOT VERIFIED` and stop the route recommendation.
3. For non-Select wide plans, check official retailer portals such as Kobo Writing Life and Google Play Books and any proposed aggregator. Capture current fees, rights grant, territories, supported formats, retailer reach claims, payment/tax setup, store overlap, and delisting/switching constraints. Never call a channel zero-cost based only on a free signup or revenue-share model.
4. Make a retailer-by-edition distribution matrix. For every retailer, record `DIRECT`, `AGGREGATOR`, `NONE`, or `UNKNOWN`; do not send the same edition to the same store through two distributors without verified compatibility and a documented deduplication plan.
5. Compare the two feasible routes on costs, control, exclusivity, formats, territories, metadata portability, promotion eligibility, tax/payout friction, and reversibility. Cite official sources with access dates. Treat vendor audience counts as vendor claims, not expected buyers.
6. Recommend one primary route and one fallback. Include the conditions that would change the recommendation. Record `AUTHOR DECISION: APPROVED | REJECTED | PENDING`; pending blocks metadata lock and retailer-specific production.

## Organic audience plan
1. Inventory actual assets: website/domain, email list and consent source, social channels, existing readers, relevant communities, and available weekly time.
2. Select no more than three initial channels. For each, specify the audience fit, useful content, frequency, call to action, owner, effort/cost, permission rules, and measurable signal. Do not assume any channel has guaranteed reach.
3. Use opt-in email collection only with appropriate consent. Reader copies or ARC outreach must not require positive reviews. Never buy, swap, or incentivize reviews; do not spam or access private groups without permission.
4. Set a baseline and a test: tagged link/UTM where available, landing-page visits, opt-ins, retailer click-outs, and a review date. Do not translate rank into sales or claim causality from a small sample.
5. Provide a fallback for each unavailable channel and an accessible plain-text alternative for visual promotions.

## Required output
Create `02_Knowledge_Base/PLATFORM_RULES/distribution_decision_<shortname>_<yyyymmdd>.md` with project assumptions; source-linked Select/wide comparison; retailer-by-edition map; current costs and rights; duplicate-listing safeguards; preferred route/fallback and author approval; up to three channel experiments; metrics/baseline/review date; and unresolved risks.

End with `AUTHOR DECISION: APPROVED | REJECTED | PENDING`. No publication, enrollment, or payment action is performed by this skill.