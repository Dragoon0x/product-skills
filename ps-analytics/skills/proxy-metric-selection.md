---
id: proxy-metric-selection
name: Proxy Metric Selection
domain: ps-analytics
version: 1.0.0
---
# Proxy Metric Selection
**Purpose:** Apply proxy metric selection — placeholder for expansion.
## When to use
When this product skill is the active constraint.


## Advanced Analytics Craft

### The Analytics Maturity Model
Level 1 — **Tracking:** Basic page views and events are tracked. 'We have data.'
Level 2 — **Reporting:** Dashboards show key metrics. 'We can see what's happening.'
Level 3 — **Analysis:** The team investigates why metrics move. 'We understand what happened.'
Level 4 — **Experimentation:** The team runs tests to validate hypotheses. 'We can predict what will happen.'
Level 5 — **Optimization:** Experimentation is continuous and systematic. 'We're always improving.'

Most product teams are at Level 2 (dashboards) and think they're at Level 3 (analysis). The jump from dashboards to analysis requires asking 'why' for every metric movement and having the skills to investigate.

### Case Study: How Airbnb Built Experiment Infrastructure
Airbnb built an internal experimentation platform that enables any product team to run A/B tests with proper statistical rigor. The platform handles: random assignment, sample size calculation, statistical significance, and guardrail metrics (counter-metrics that catch unintended negative effects). The result: Airbnb runs hundreds of concurrent experiments. The key insight: experimentation velocity (how many tests you can run per quarter) is a competitive advantage because each test produces learning that compounds.

### The Metric Hierarchy
**North Star Metric** — the ONE metric that best captures the value you deliver to users. This is your compass.

**Input Metrics** (3-5) — the levers that drive the North Star. These are what teams optimize day-to-day.

**Health Metrics** (3-5) — the guardrails that prevent optimization from causing harm. Revenue growth is good, but not if churn is rising. Engagement is good, but not if users feel manipulated.

**Team Metrics** — the operational measures of team effectiveness. Sprint velocity, estimate accuracy, deployment frequency. These tell you whether the machine is running well.

The hierarchy ensures everyone knows: what we're ultimately optimizing for (North Star), what we can control this quarter (Input Metrics), what we're protecting (Health Metrics), and how well we're executing (Team Metrics).

### The Counter-Metric Principle
For every metric you optimize, name the metric that could degrade:
- Optimizing **signup rate**? Watch **activation rate** (easy signups may attract wrong users)
- Optimizing **engagement**? Watch **churn** (addictive patterns create backlash)
- Optimizing **revenue per user**? Watch **NPS** (extractive monetization erodes satisfaction)
- Optimizing **deployment speed**? Watch **error rate** (shipping faster without quality degrades reliability)

Counter-metrics prevent 'Goodhart's Law' — when a measure becomes a target, it ceases to be a good measure. The counter-metric keeps the optimization honest.


## The Practitioner's Notebook

### Analytics Patterns I've Seen Work

**The dashboard graveyard:** Most product dashboards are created, viewed for 2 weeks, and then forgotten. The fix: don't build a dashboard — build a decision. For every metric, define: 'If this number is above X, we do Y. If below Z, we do W.' Metrics without decision thresholds are trivia. Metrics with decision thresholds are management tools.

**The experiment velocity principle:** The team that runs 10 experiments per quarter learns 5x faster than the team that runs 2. Most teams under-experiment because each experiment feels like a big investment. The fix: reduce experiment cost. Use feature flags. Use segmentation. Use smaller sample sizes for directional signals. A 2-day experiment with 80% confidence is usually better than a 2-week experiment with 95% confidence, because you can run 5x more experiments.

**The attribution illusion:** Multi-touch attribution models are more sophisticated than last-touch models. But all attribution models are wrong — they just vary in how useful their wrongness is. Don't optimize attribution. Optimize the thing that attribution tries to measure: are your marketing investments producing qualified pipeline? Track at the investment level (channel), not the click level (attribution).

**The data literacy gap:** PMs who can write SQL make better product decisions because they can answer their own questions instead of waiting 3 days for a data analyst. Learn basic SQL (SELECT, JOIN, WHERE, GROUP BY, window functions). Build 10 queries that answer your most common questions. Save them. This investment pays dividends for years.

