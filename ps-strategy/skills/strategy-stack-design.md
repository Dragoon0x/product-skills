---
id: strategy-stack-design
name: Strategy Stack Design
domain: ps-strategy
version: 1.0.0
---
# Strategy Stack Design
**Purpose:** Apply strategy stack design with the strategic depth, analytical rigor, and execution discipline that separates product teams that ship outcomes from product teams that ship features — where every decision is backed by evidence, connected to strategy, and measurable in impact.

## Why This Matters

Product strategy is the set of decisions that determine what the product becomes — who it serves, what problem it solves, how it's positioned, and how it wins. Most products fail not because they're built poorly but because they're built strategically — they solve the wrong problem, for the wrong audience, at the wrong time. Strategy is the discipline of making these choices explicit, evidence-based, and revisable.

For strategy stack design specifically, this is one of the product decisions that compounds — get it right and everything downstream works better. Get it wrong and the team spends months building confidently in the wrong direction. The difference between high-performing product teams and struggling ones is usually 5-10 decisions like this one, made with frameworks instead of gut feeling.

## The Frameworks

The Product Vision Framework: A product vision answers three questions: (1) Who are we building for? (specific user, not 'everyone'). (2) What world are we creating? (the outcome, not the feature). (3) Why will we win? (the unfair advantage — technology, insight, distribution, or brand). A vision that can't answer all three is incomplete. A vision where the answer to #3 is 'we'll work harder' is a plan, not a strategy. Example: Figma's vision — 'Make design accessible to everyone who shapes digital products' — names the audience (anyone who shapes digital products), the world (design is accessible), and the advantage (browser-based = zero barrier).

The Strategy Stack: Vision (10-year destination) → Strategy (3-year bets — the 2-3 big moves that create the advantage) → Roadmap (1-year plan — themes and outcomes) → Sprints (2-week execution — features and fixes). Each layer constrains the layer below. Sprints that don't serve the roadmap are waste. Roadmap items that don't serve the strategy are distraction. Strategy that doesn't serve the vision is drift. The most common failure: sprints disconnected from strategy because the middle layers (strategy → roadmap) were never defined.

Competitive Positioning (April Dunford): (1) What alternatives would customers use if you didn't exist? (2) What unique capabilities do you have? (3) What value do those capabilities enable? (4) Who cares most about that value? (5) What market category makes the value obvious? The sequence matters — start with alternatives, not with the category. The category is the last decision, not the first. Most positioning fails because it starts with 'we're a [category]' instead of starting with 'customers currently use [alternative] and hate [specific thing].'

## Mental Models for Product Thinking

**The Two-Way Door Test (Bezos):** Is this decision reversible? If yes (two-way door), decide quickly — you can always walk back. If no (one-way door), decide carefully. Most product decisions are two-way doors that teams treat as one-way doors, causing unnecessary paralysis. Pricing, positioning, and architecture decisions are one-way doors. Feature decisions, copy changes, and experiment designs are almost always two-way doors.

**First Principles Thinking:** Strip the problem to its fundamental truths and reason up from there. Not 'what does the competitor do?' but 'what does the user actually need?' Not 'what's the industry standard?' but 'what would we build if no standard existed?' First principles thinking produces original solutions. Analogical thinking produces copies.

**The Inversion Technique (Munger):** Instead of asking 'how do I succeed at strategy stack design?' ask 'how would I definitely fail?' Then avoid those failure modes. Common inversions: How would I definitely ship a bad product? (Skip user research, ignore feedback, optimize for stakeholder approval.) How would I definitely miss the market? (Build for the average user instead of the passionate early adopter.)

**The Regret Minimization Framework (Bezos):** When deciding, ask: 'In 10 years, will I regret not doing this?' If the opportunity is rare, the learning irreplaceable, or the market window closing — bias toward action. If the opportunity will come again, the decision is reversible, or the stakes are low — bias toward patience.

## How to Execute

**Step 1: Diagnose.** Before changing anything, understand the current state. What does the data say? What do users say? Where's the gap between assumption and reality? Diagnosis prevents solving the wrong problem.

**Step 2: Hypothesize.** Form a specific hypothesis: 'We believe [change] will produce [measurable outcome] because [mechanism].' All three parts required. If you can't articulate the mechanism, you don't understand the problem well enough.

**Step 3: Test cheaply.** Find the smallest experiment that validates or invalidates the hypothesis. Can you test with 10 users before building for 10,000? Can you mock it up before coding it? The cost of testing is always lower than the cost of building wrong.

**Step 4: Measure honestly.** Did the change produce the predicted result? If yes, scale. If no, diagnose why. The discipline of honest measurement separates learning organizations from self-deluding ones.

**Step 5: Ship or kill.** Ship what works. Kill what doesn't. The speed of this cycle — test, measure, decide — is the team's competitive advantage. Every week spent deliberating is a week the competitor spent learning.

## Real-World Application

**Pre-PMF (0-100 users):** At this stage, strategy stack design is about finding signal in noise. The sample size is too small for statistical significance. Optimize for speed of learning: 5-10 experiments per month, each producing a clear insight. The founder should be directly involved in every strategy stack design decision.

**Post-PMF, scaling (100-10K users):** strategy stack design must be systematized — turned from founder instinct into repeatable process. Document what works. Hire someone to own it. Build the metrics dashboard. The danger is premature optimization — don't over-engineer before validating at 3-5x current scale.

**At scale (10K+ users):** strategy stack design is an operational discipline with an owner, a dashboard, a review cadence, and a continuous improvement process. Decisions are about optimization (improving efficiency) not exploration (finding what works). Quarter-over-quarter improvement is the goal.

## Case Studies

Notion started as a note-taking app, realized the market was fragmented tools (Confluence for docs, Trello for tasks, Google Docs for collaboration), and repositioned as 'the connected workspace' — a strategy that attacked the fragmentation problem rather than competing in any single tool category. Linear positioned against Jira not on features but on experience — 'the issue tracker built for speed.' The strategy wasn't 'better Jira' but 'different philosophy about how software teams should work.' Superhuman found PMF by measuring the Sean Ellis 'Very Disappointed' metric — asking users 'How would you feel if you could no longer use this product?' — and only scaling when 40%+ said 'very disappointed.'

## Common Mistakes

The biggest mistake with strategy stack design is treating it as a one-time decision instead of an ongoing discipline. Markets change. Users evolve. Competitors adjust. The team that reviews strategy stack design quarterly outperforms the team that sets it and forgets it.

The second mistake is copying what worked for another company without adapting to your context. Frameworks transfer. Tactics don't. Your market, users, and product are unique. Use frameworks to derive your own approach.

The third mistake is measurement avoidance. If you can't measure whether strategy stack design is working, you can't improve it. Define the metric before executing. If the metric doesn't move, the approach isn't working — regardless of how good it looks in the deck.

## The Product Craft Dimension

strategy stack design is ultimately a craft skill — it improves with deliberate practice. The progression:

**Novice:** Applies frameworks mechanically. Follows the process. Gets decent results.

**Practitioner:** Adapts frameworks to context. Knows when to follow the process and when to deviate. Gets good results consistently.

**Expert:** Operates from internalized judgment. Sees patterns before they're obvious. Makes the right call under uncertainty and time pressure. Gets great results and teaches others how.

The path from novice to expert is ~2 years of deliberate practice: applying the frameworks, measuring the results, learning from the outcomes, and updating your judgment. There are no shortcuts. There are only more reps.

## When to use

When strategy stack design is the current bottleneck or the highest-leverage opportunity. When user research, analytics, or competitive analysis surfaces this as a gap. When entering a new market, segment, or growth stage. When the current approach was set more than 6 months ago and hasn't been revisited.


## Advanced Strategy Craft

### The Strategy Stress Test
Before committing to a strategy, run it through these 5 tests:

**The Alternative Test:** What would we do if this strategy fails? If there's no Plan B, the strategy is a bet, not a plan. Bets are acceptable — but name them as such and define the kill criteria.

**The Resource Test:** Do we have the team, budget, and timeline to execute this strategy? A strategy that requires 2x the available resources is a fantasy. The best strategy is the best strategy you can actually execute.

**The Evidence Test:** What evidence supports this strategy? Customer interviews, market data, competitive analysis, or gut feeling? Strategies built on evidence are hypotheses. Strategies built on gut feeling are wishes. Both can work — but only hypotheses can be improved through measurement.

**The Contrarian Test:** What would a smart person who disagrees with this strategy say? If you can't articulate the strongest counter-argument, you don't understand the decision space well enough. The best strategies survive the strongest objections.

**The Clarity Test:** Can every team member explain this strategy in one sentence? If the strategy requires a 30-minute presentation to understand, it's not clear enough to execute. Strategy should be a compass, not a manual.

### Case Study: How Linear Won With Product Strategy
Linear entered the project management space dominated by Jira, Asana, and Monday. Their strategy was contrarian: instead of adding features to compete, they removed features to differentiate. The strategic bet: software teams don't want more project management features — they want less friction in their workflow. The execution: keyboard-first interaction, opinionated defaults instead of customization, speed as the #1 design principle. The result: $400M+ valuation and the default tool for modern engineering teams. The lesson: positioning against the dominant paradigm (more features) with a clear alternative paradigm (less friction) is a viable strategy when the audience is frustrated with the status quo.

### The Strategy Communication Framework
A strategy that lives in a document nobody reads is not a strategy — it's a file. Strategies must be communicated:

**The Headline:** One sentence that captures the strategic direction. 'We're going all-in on developer experience as our competitive moat.' This headline should be repeated in every all-hands, every planning session, every prioritization discussion.

**The Rationale:** One paragraph that explains why. What evidence supports this direction? What alternatives were considered and rejected? Why now?

**The Implications:** What does this strategy mean for each team? For engineering: what should they prioritize? For design: what experience principles does this create? For sales: what story should they tell? For marketing: what positioning does this create? The implications make the strategy actionable for every function.

**The Metrics:** How will we know if the strategy is working? Define 2-3 metrics that would indicate strategic success within 6 months. Review these metrics monthly. If the metrics aren't moving, either the strategy or the execution needs adjustment.

