# Product-Skills

Agent skills for product thinking and PM craft. Help AI coding agents reason about strategy, conversion, pricing, retention, analytics, competitive intelligence, roadmapping, and the people side of product management before they build.

> **⚠️ Experimental Software.** This project is in active development. Skills may change or break without notice. Not professional advice. All output requires human review. Do your own research. [Read full disclaimer →](./DISCLAIMER.md) | [Full terms →](./TERMS.md)

## Why

Agents are great at building interfaces. They're terrible at deciding what to build, what to say, and why anyone should care. These skills fill that gap.

Each skill is a set of opinionated constraints and patterns. When an agent uses them, it checks its own output against product principles before shipping anything.

This is not a design system. Not a component library. This is the thinking layer.

## Install

```bash
# Add all skills
npx github:Dragoon0x/product-skills add --all

# Add a specific skill
npx github:Dragoon0x/product-skills add positioning

# Add multiple skills
npx github:Dragoon0x/product-skills add conversion-copy landing-structure pricing-page

# List available skills
npx github:Dragoon0x/product-skills list

# Show skill details
npx github:Dragoon0x/product-skills info positioning

# Custom directory
npx github:Dragoon0x/product-skills add --all --dir ./agent-skills
```

Skills are installed to `.product-skills/` by default. Point your agent to this directory.

## Compatibility

Works with any agent that supports SKILL.md files:

- Claude Code
- Cursor
- Windsurf
- OpenCode
- Cline
- Codex
- Aider
- Continue

## Product Thinking Skills

### Strategy (5)

| Skill | Description |
|---|---|
| `positioning` | Articulate why this product exists, who it serves, and what it replaces |
| `zero-to-one` | First principles decisions for products that don't exist yet |
| `competitive-framing` | Position against alternatives without being negative |
| `feature-prioritization` | Decide what to build next based on impact, not excitement |
| `market-validation` | Test assumptions before committing resources |

### Conversion (5)

| Skill | Description |
|---|---|
| `landing-structure` | Information architecture from curiosity to commitment |
| `pricing-page` | Present pricing that reduces friction and increases clarity |
| `trust-signals` | Build credibility through evidence, not claims |
| `cta-patterns` | Design calls-to-action that people actually click |
| `form-optimization` | Reduce abandonment in forms, signups, and checkout flows |

### Experience (5)

| Skill | Description |
|---|---|
| `onboarding-flow` | First-run experiences that create the aha moment fast |
| `empty-states` | Turn dead ends into moments that guide action |
| `notification-design` | Communicate without annoying |
| `settings-architecture` | Organize preferences so people find what they need |
| `error-recovery` | Guide people forward when things break |

### Communication (4)

| Skill | Description |
|---|---|
| `conversion-copy` | Headlines, CTAs, and value props that move people to act |
| `microcopy` | The small words that shape big experiences |
| `product-narrative` | Tell the product story in a way that sticks |
| `changelog-voice` | Ship updates people actually want to read |

### Research (4)

| Skill | Description |
|---|---|
| `user-psychology` | Motivation, friction, and trust patterns for product decisions |
| `feedback-synthesis` | Turn raw feedback into actionable product decisions |
| `persona-mapping` | User models that actually inform decisions |
| `jobs-to-be-done` | Understand what people hire your product to do |

### Growth (4)

| Skill | Description |
|---|---|
| `retention-patterns` | Design for the second visit, not just the first |
| `launch-checklist` | Everything that needs to be true before real people see this |
| `referral-mechanics` | Build sharing into the product without it feeling forced |
| `value-metrics` | Measure what matters, ignore what doesn't |

### Pricing & Monetization (4)

| Skill | Description |
|---|---|
| `pricing-page-teardown` | Analyze a pricing page for what's working and what's leaving money on the table |
| `freemium-vs-paid-gate` | Decide between free tier, free trial, or straight to paid |
| `willingness-to-pay` | Determine what customers will actually pay using structured frameworks |
| `packaging-strategy` | Bundle features into plans that feel natural for each segment |

### Competitive Intelligence (3)

| Skill | Description |
|---|---|
| `competitive-battlecard` | Tactical guides for positioning against specific competitors |
| `feature-gap-analysis` | Identify which competitive gaps matter, which don't, and which should stay |
| `switching-cost-evaluation` | Analyze the real cost of switching — financial, technical, political, emotional |

### Retention & Activation (3)

| Skill | Description |
|---|---|
| `aha-moment-mapping` | Find the moment users experience core value and get them there faster |
| `cohort-retention-analysis` | Understand retention by isolating who joined when and what they did after |
| `churn-signal-identification` | Spot warning signs before customers leave, not after |

### Product Analytics (3)

| Skill | Description |
|---|---|
| `funnel-drop-off-diagnosis` | Find why users drop off at specific steps and fix the right thing |
| `metric-interpretation` | Understand what metrics mean in context with proper benchmarks |
| `feature-adoption-diagnosis` | Diagnose why a feature isn't getting used and decide what to do |

### Prioritization & Roadmapping (3)

| Skill | Description |
|---|---|
| `prioritization-frameworks` | Score and rank initiatives using RICE, ICE, and value-effort frameworks |
| `opportunity-sizing` | Estimate potential value before committing resources |
| `roadmap-planning` | Build a roadmap that communicates strategy, not just features with dates |

## PM Craft Skills

### PM Communication (3)

| Skill | Description |
|---|---|
| `prd-writing` | Write PRDs that engineers want to read and can actually build from |
| `stakeholder-updates` | Write status updates that executives actually read and act on |
| `presentation-storytelling` | Structure presentations that persuade through narrative, not slide count |

### Alignment & Influence (3)

| Skill | Description |
|---|---|
| `influencing-without-authority` | Get buy-in when you have no direct power over the people you need to move |
| `cross-functional-alignment` | Bring engineering, design, marketing, and sales onto the same page |
| `managing-up` | Build productive relationships with leadership through transparency and candor |

### PM Strategy & Vision (3)

| Skill | Description |
|---|---|
| `north-star-setting` | Define a north star metric and vision that guides daily decisions |
| `competitive-positioning` | Understand the competitive landscape and position clearly within it |
| `roadmap-planning` | Build and communicate roadmaps that balance needs and capacity |

### Execution Discipline (3)

| Skill | Description |
|---|---|
| `sprint-delivery-management` | Drive predictable delivery without micromanaging engineering |
| `risk-management` | Identify and mitigate product risks before they become fires |
| `launch-planning` | Plan launches that drive adoption, not just announcements |

### Collaboration (3)

| Skill | Description |
|---|---|
| `working-with-engineering` | Partner with engineers as collaborators, not ticket-writers |
| `working-with-design` | Partner with design to solve problems, not just make things pretty |
| `working-with-gtm` | Partner with marketing, sales, and CS to bring products to market |

### Product Sense (3)

| Skill | Description |
|---|---|
| `ux-intuition` | Know what makes a product feel right, beyond what data tells you |
| `trade-off-evaluation` | Make trade-offs explicit and defend them clearly |
| `quality-judgment` | Know when something is good enough to ship and when it needs more work |

### Customer Empathy (3)

| Skill | Description |
|---|---|
| `user-research-integration` | Turn research into product decisions, not just reports |
| `problem-articulation` | Define user problems clearly enough that solutions become obvious |
| `feedback-synthesis` | Turn raw customer feedback into clear priorities |

### Decision-Making (3)

| Skill | Description |
|---|---|
| `decision-frameworks` | Make product decisions with structure and speed, even with imperfect info |
| `data-informed-decisions` | Use data to inform decisions without becoming a slave to metrics |
| `communicating-decisions` | Communicate decisions so teams understand what and why |

### Impact Orientation (3)

| Skill | Description |
|---|---|
| `outcome-thinking` | Measure success by what changed, not what shipped |
| `metrics-measurement` | Design a metrics framework that tells you if the product is healthy |
| `business-acumen` | Connect product decisions to business outcomes and commercial reality |

### Organisation & Prioritization (3)

| Skill | Description |
|---|---|
| `prioritization-frameworks` | Apply structured methods to decide what to build and what to cut |
| `backlog-management` | Keep the backlog useful instead of a graveyard of stale ideas |
| `time-energy-management` | Protect PM time for strategic work without burning out |

## How skills work

Each skill is a markdown file (SKILL.md) containing constraints and patterns that an agent can follow. When you add a skill to your project, it becomes part of the agent's context and guides its output.

```
.product-skills/
├── positioning/
│   └── SKILL.md
├── conversion-copy/
│   └── SKILL.md
├── pricing-page-teardown/
│   └── SKILL.md
├── prd-writing/
│   └── SKILL.md
├── competitive-battlecard/
│   └── SKILL.md
└── ...
```

You can edit any skill to fit your specific context. They're just markdown files.

## ⚠️ Important Notices

### Experimental Software

This project is **experimental**. It has not been independently audited, peer-reviewed, or formally verified. Skills, commands, and behaviors may change or break at any time without notice. Do not rely on this software for production-critical decisions without independent verification and qualified human oversight.

### Do Your Own Research (DYOR)

These skills encode opinionated product heuristics, not universal truths. They reflect patterns observed across specific contexts and the subjective experience of the contributors. Every product, market, user base, and regulatory environment is different. Any benchmarks, numbers, or reference points are illustrative approximations only.

- Test all assumptions against your own data
- Validate with your own users
- Consult qualified professionals for legal, financial, and business decisions
- No AI-generated output should ship without human review
- Do not treat any output as professional advice of any kind

### Not Professional Advice

Nothing in this software constitutes professional business, legal, financial, marketing, or strategic advice. The authors are not licensed professionals in any field. The authors are not responsible for decisions made based on the output of this software.

### AI-Generated Output

All AI-generated output produced through these skills may be inaccurate, misleading, incomplete, or unsuitable for your context. Output should be reviewed, validated, and approved by a qualified human before use in any production or commercial context. The authors accept no responsibility for AI-generated content.

### No Guarantee of Results

Use of this software does not guarantee any specific outcome. Past patterns are not predictive of future results. Individual results depend on factors entirely outside the control of this software and its authors.

### Assumption of Risk

By using this software, you assume all risks associated with its use. See [DISCLAIMER.md](./DISCLAIMER.md) for full details.

## License

MIT License. See [LICENSE](./LICENSE).

Full disclaimer: [DISCLAIMER.md](./DISCLAIMER.md).

Full terms of use: [TERMS.md](./TERMS.md).

---

Built for agents that need to think about products, not just build them.

**Experimental software. Not professional advice. DYOR. All output requires human review.**
