---
id: shipping-cadence-optimization
name: Shipping Cadence Optimization
domain: ps-execution
version: 1.0.0
---
# Shipping Cadence Optimization
**Purpose:** Apply shipping cadence optimization — placeholder for expansion.
## When to use
When this product skill is the active constraint.


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


## The Practitioner's Notebook

### Execution Patterns I've Seen Work

**The 'two-pizza team' reality:** Small autonomous teams (5-8 people) ship faster than large teams. But autonomy requires alignment — the team must know the strategy well enough to make decisions without asking. Invest upfront in alignment (clear strategy, clear metrics, clear boundaries) to enable downstream autonomy.

**The sprint anti-pattern nobody talks about:** Sprints that start with 'what can we fit in?' instead of 'what's the most important outcome this week?' Feature-stuffed sprints feel productive. Outcome-focused sprints ARE productive. The test: at sprint review, can you describe what user behavior changed? If you can only describe what code was deployed, the sprint was output-focused, not outcome-focused.

**The estimation paradox:** The more detailed the estimate, the less accurate it is. Detailed estimates create false precision — '47 hours' feels more accurate than '1-2 weeks' but isn't. The fix: estimate in t-shirt sizes (S/M/L/XL) and convert to time ranges. S = 1-3 days, M = 3-5 days, L = 1-2 weeks, XL = 2-4 weeks. Anything estimated as XL should be broken into smaller pieces before committing.

**The launch energy principle:** The energy level at launch determines the trajectory. A team that's exhausted and anxious at launch produces a cautious, defensive post-launch experience. A team that's energized and confident at launch produces a proactive, learning-oriented post-launch experience. Protect the team's energy in the final week — no all-nighters, no last-minute scope additions, no unnecessary meetings.

