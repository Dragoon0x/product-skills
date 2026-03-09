---
id: ice-scoring-practice
name: Ice Scoring Practice
domain: ps-execution
version: 1.0.0
---
# Ice Scoring Practice
**Purpose:** Apply ice scoring practice with the strategic depth, analytical rigor, and execution discipline that separates product teams that ship outcomes from product teams that ship features — where every decision is backed by evidence, connected to strategy, and measurable in impact.

## Why This Matters

Product execution is where strategy becomes reality — the discipline of translating strategic intent into shipped features, managing the gap between what's planned and what's possible, and maintaining quality under the constraints of time, resources, and competing demands. The best strategy in the world is worthless without execution that ships it. And the best execution in the world is worthless without strategy that directs it.

For ice scoring practice specifically, this is one of the product decisions that compounds — get it right and everything downstream works better. Get it wrong and the team spends months building confidently in the wrong direction. The difference between high-performing product teams and struggling ones is usually 5-10 decisions like this one, made with frameworks instead of gut feeling.

## The Frameworks

RICE Prioritization: Reach (how many users affected per quarter?) × Impact (minimal/low/medium/high/massive = 0.25/0.5/1/2/3) × Confidence (percentage) / Effort (person-months). Score = R×I×C/E. RICE adds 'Reach' to prevent the trap of building high-impact features for tiny audiences, and 'Confidence' to penalize uncertain estimates. The discipline: score everything in the backlog, rank by RICE score, then apply judgment to the top 10. The score informs — the PM decides.

Now/Next/Later Roadmap: Now (this quarter, committed, in development or about to start). Next (next quarter, planned, scoped but not started). Later (future, exploratory, promising but unvalidated). This format communicates commitment level honestly: 'Now' is a promise, 'Next' is a plan, 'Later' is a possibility. Stakeholders who understand the commitment levels stop treating roadmap items as promises. The roadmap should be outcome-driven (what user/business outcomes) not feature-driven (what features).

Sprint Delivery Framework: Sprint planning → Daily standup → Sprint review → Retrospective. The PM's sprint responsibilities: ensure stories have clear acceptance criteria before sprint starts, unblock the team during sprint (answer questions within 2 hours, not 2 days), demo shipped work to stakeholders at sprint review, and facilitate honest retrospective. The PM is NOT: the scrum master, the project manager, or the person assigning tasks. The PM ensures the team is working on the right thing. How they work is the team's decision.

## Mental Models for Product Thinking

**The Two-Way Door Test (Bezos):** Is this decision reversible? If yes (two-way door), decide quickly — you can always walk back. If no (one-way door), decide carefully. Most product decisions are two-way doors that teams treat as one-way doors, causing unnecessary paralysis. Pricing, positioning, and architecture decisions are one-way doors. Feature decisions, copy changes, and experiment designs are almost always two-way doors.

**First Principles Thinking:** Strip the problem to its fundamental truths and reason up from there. Not 'what does the competitor do?' but 'what does the user actually need?' Not 'what's the industry standard?' but 'what would we build if no standard existed?' First principles thinking produces original solutions. Analogical thinking produces copies.

**The Inversion Technique (Munger):** Instead of asking 'how do I succeed at ice scoring practice?' ask 'how would I definitely fail?' Then avoid those failure modes. Common inversions: How would I definitely ship a bad product? (Skip user research, ignore feedback, optimize for stakeholder approval.) How would I definitely miss the market? (Build for the average user instead of the passionate early adopter.)

**The Regret Minimization Framework (Bezos):** When deciding, ask: 'In 10 years, will I regret not doing this?' If the opportunity is rare, the learning irreplaceable, or the market window closing — bias toward action. If the opportunity will come again, the decision is reversible, or the stakes are low — bias toward patience.

## How to Execute

**Step 1: Diagnose.** Before changing anything, understand the current state. What does the data say? What do users say? Where's the gap between assumption and reality? Diagnosis prevents solving the wrong problem.

**Step 2: Hypothesize.** Form a specific hypothesis: 'We believe [change] will produce [measurable outcome] because [mechanism].' All three parts required. If you can't articulate the mechanism, you don't understand the problem well enough.

**Step 3: Test cheaply.** Find the smallest experiment that validates or invalidates the hypothesis. Can you test with 10 users before building for 10,000? Can you mock it up before coding it? The cost of testing is always lower than the cost of building wrong.

**Step 4: Measure honestly.** Did the change produce the predicted result? If yes, scale. If no, diagnose why. The discipline of honest measurement separates learning organizations from self-deluding ones.

**Step 5: Ship or kill.** Ship what works. Kill what doesn't. The speed of this cycle — test, measure, decide — is the team's competitive advantage. Every week spent deliberating is a week the competitor spent learning.

## Real-World Application

**Pre-PMF (0-100 users):** At this stage, ice scoring practice is about finding signal in noise. The sample size is too small for statistical significance. Optimize for speed of learning: 5-10 experiments per month, each producing a clear insight. The founder should be directly involved in every ice scoring practice decision.

**Post-PMF, scaling (100-10K users):** ice scoring practice must be systematized — turned from founder instinct into repeatable process. Document what works. Hire someone to own it. Build the metrics dashboard. The danger is premature optimization — don't over-engineer before validating at 3-5x current scale.

**At scale (10K+ users):** ice scoring practice is an operational discipline with an owner, a dashboard, a review cadence, and a continuous improvement process. Decisions are about optimization (improving efficiency) not exploration (finding what works). Quarter-over-quarter improvement is the goal.

## Case Studies

Spotify's 'Squad' model: autonomous cross-functional teams (squad = PM + designer + engineers) with full ownership of a product area. The PM sets the mission and metrics. The squad decides how to achieve them. This model scales execution by distributing product decision-making to the teams closest to the work. Amazon's 'Working Backwards' execution process: start with the press release (what are we announcing?), then the FAQ (what questions will customers have?), then the one-pager (what's the business case?), then the spec. The reverse sequence forces clarity about the customer outcome before any engineering begins.

## Common Mistakes

The biggest mistake with ice scoring practice is treating it as a one-time decision instead of an ongoing discipline. Markets change. Users evolve. Competitors adjust. The team that reviews ice scoring practice quarterly outperforms the team that sets it and forgets it.

The second mistake is copying what worked for another company without adapting to your context. Frameworks transfer. Tactics don't. Your market, users, and product are unique. Use frameworks to derive your own approach.

The third mistake is measurement avoidance. If you can't measure whether ice scoring practice is working, you can't improve it. Define the metric before executing. If the metric doesn't move, the approach isn't working — regardless of how good it looks in the deck.

## The Product Craft Dimension

ice scoring practice is ultimately a craft skill — it improves with deliberate practice. The progression:

**Novice:** Applies frameworks mechanically. Follows the process. Gets decent results.

**Practitioner:** Adapts frameworks to context. Knows when to follow the process and when to deviate. Gets good results consistently.

**Expert:** Operates from internalized judgment. Sees patterns before they're obvious. Makes the right call under uncertainty and time pressure. Gets great results and teaches others how.

The path from novice to expert is ~2 years of deliberate practice: applying the frameworks, measuring the results, learning from the outcomes, and updating your judgment. There are no shortcuts. There are only more reps.

## When to use

When ice scoring practice is the current bottleneck or the highest-leverage opportunity. When user research, analytics, or competitive analysis surfaces this as a gap. When entering a new market, segment, or growth stage. When the current approach was set more than 6 months ago and hasn't been revisited.


## Advanced Execution Discipline

### The Execution Quality Framework
Most teams measure execution by output (features shipped). Better teams measure execution by outcome (user behavior changed). The best teams measure execution by efficiency (outcome per unit of effort). Track all three:

**Output metrics:** Features shipped, story points completed, deployment frequency. These tell you the team is working.

**Outcome metrics:** User adoption of shipped features, metric movement, customer satisfaction change. These tell you the work matters.

**Efficiency metrics:** Outcome per sprint, estimate accuracy, rework rate, scope change frequency. These tell you the process is working.

### Case Study: Amazon's Working Backwards Execution
Amazon's product development starts with a press release written before any code. The press release describes the customer benefit, not the feature. If the press release isn't compelling, the product isn't worth building. This forces outcome thinking: 'What will we announce?' not 'What will we build?' The FAQ document that follows the press release anticipates customer questions and internal objections — surfacing problems before engineering investment. The one-pager provides the business case. Only after all three documents are reviewed does engineering begin. This process is slower at the start and dramatically faster overall because it prevents building the wrong thing.

### The Sprint Health Indicators
A healthy sprint has these characteristics:
- **Predictability:** 80%+ of committed stories are completed. Below 70% indicates planning or scoping problems.
- **Focus:** Less than 10% of sprint capacity consumed by unplanned work. Above 20% indicates poor backlog management or too many interruptions.
- **Quality:** Less than 1 critical bug per sprint. More indicates insufficient QA or technical debt.
- **Morale:** Team retrospective sentiment is neutral or positive. Consistently negative sentiment indicates systemic issues (overwork, unclear direction, lack of autonomy).

### The Scope Negotiation Playbook
When a stakeholder requests a feature that doesn't fit the current plan:

**Step 1: Understand.** 'Help me understand the business need behind this request.' Often the underlying need can be met with a simpler solution than the requested feature.

**Step 2: Trade.** 'We can do this if we move [other item] out. Here's the impact of that trade.' Never accept additional scope without removing equivalent scope.

**Step 3: Phase.** 'We can build a lightweight version now and the full version in Q3. Here's what the lightweight version includes.' Often the lightweight version satisfies the real need.

**Step 4: Defer.** 'This is a great idea that we should pursue after [current initiative] ships. I'll add it to the backlog with your context.' Document the request and the reasoning for deferral.

