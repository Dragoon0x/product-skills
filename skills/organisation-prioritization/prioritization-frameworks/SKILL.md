---
name: prioritization-frameworks
description: "Apply structured prioritization methods to decide what to build and what to cut. Covers RICE, ICE, MoSCoW, and knowing when each framework fits. Use when the backlog is overwhelming, stakeholders disagree on priorities, or when everything feels like P0."
---

# Prioritization Frameworks (PM Craft)

Decide what to build — and more importantly, what not to build.

## How to use

- `/prioritization-frameworks` Apply prioritization constraints to this conversation.
- `/prioritization-frameworks <backlog>` Prioritize the described set of initiatives.

## Constraints

### Framework Selection
- RICE (Reach, Impact, Confidence, Effort): best for large backlogs needing rigorous comparison
- ICE (Impact, Confidence, Ease): best for quick decisions, smaller teams
- MoSCoW (Must, Should, Could, Won't): best for scope negotiation within a fixed release
- MUST pick one framework and use it consistently. Switching methods mid-cycle creates confusion.
- SHOULD match framework to decision type: strategic decisions need RICE, sprint decisions can use ICE

### Scoring Discipline
- MUST score in batches, not individually. Relative comparison improves accuracy.
- MUST require evidence for high Impact scores. "This is important" is not evidence.
- Items within 10% of each other are effectively tied — group into tiers, don't strict-rank
- MUST include the "won't do" list. Saying no is the most important part of prioritization.
- NEVER let scoring become a political exercise where everyone inflates their pet project

### Prioritization Inputs
- MUST balance: customer demand, business impact, strategic alignment, and technical investment
- SHOULD weight recent data higher than old requests
- MUST consider dependencies: can you build X without building Y first?
- SHOULD factor in team energy — all infrastructure sprints drain morale; all feature sprints create debt
- NEVER prioritize based solely on who asked loudest

### Decision Quality
- MUST set a clear decision-maker. Group prioritization produces mediocre outcomes.
- SHOULD timebox prioritization sessions — spending longer on scoring than building defeats the purpose
- MUST communicate priorities and rationale to the team after deciding
- SHOULD reserve 10-20% of capacity for things that don't score well but matter strategically (experiments, debt)
- MUST re-prioritize when significant new information arrives, not on a fixed schedule

### Anti-Patterns
- The Infinite P0 List: everything is critical, nothing is prioritized
- The Democratic Backlog: letting everyone vote on priorities regardless of strategic context
- Priority by Recency: whatever came in last goes to the top
- The Immovable Roadmap: refusing to re-prioritize when the world changes
- Prioritization Theater: going through the motions but building what leadership already decided
