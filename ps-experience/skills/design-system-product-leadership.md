---
id: design-system-product-leadership
name: Design System Product Leadership
domain: ps-experience
version: 1.0.0
---
# Design System Product Leadership
**Purpose:** Apply design system product leadership — placeholder for expansion.
## When to use
When this product skill is the active constraint.


## Advanced Experience Craft

### The Product Sense Development Program
Product sense — the ability to evaluate experience quality intuitively — is developed through deliberate practice:

**Month 1-3: The Collection Phase.** Use 50 products in your category and adjacent categories. For each, write one sentence about what specific interaction or design choice makes it good or bad. The specificity matters: not 'it's clean' but 'the 8px spacing between list items creates scannable density without crowding.'

**Month 4-6: The Evaluation Phase.** For every feature your team ships, do a post-ship experience review. Walk through the feature as a new user. Where do you hesitate? Where do you feel delighted? Where do you feel confused? Document these observations and compare with user feedback — are you noticing the same things users notice?

**Month 7-12: The Prediction Phase.** Before usability tests, predict what users will struggle with. After the test, compare your predictions with reality. The gap between prediction and reality is the gap in your product sense. Over time, the gap shrinks — your predictions become more accurate, which means your upfront design reviews catch more issues.

### Case Study: How Notion Designed for Delight
Notion's product experience is built on a specific philosophy: the tool should feel like a blank canvas, not a rigid template. Every design decision serves this philosophy: blocks (everything is a block that can be moved and transformed), slash commands (type / to create anything), drag-and-drop (rearrange freely), and templates (starting points, not constraints). The experience is consistent across all content types because the underlying model (blocks) is universal. The delight comes from the feeling of capability — users discover new things they can do with blocks long after initial onboarding.

### The State Design Checklist
For every feature, verify these states are designed:

- [ ] **Ideal state** — working perfectly with good data
- [ ] **Empty state** — no data yet (with helpful guidance)
- [ ] **Loading state** — data is being fetched (with indication of progress)
- [ ] **Error state** — something went wrong (with specific fix instruction)
- [ ] **Partial state** — some data available, some missing
- [ ] **Edge state** — extreme data (very long text, very large numbers, missing fields)
- [ ] **First-use state** — user's first encounter (with onboarding guidance)
- [ ] **Permission state** — user doesn't have access (with clear explanation)
- [ ] **Offline state** — no internet connection (with offline capability or clear message)
- [ ] **Bulk state** — many items (100+, performance tested)

Missing any state means the feature will break for some users in production. The most commonly missed: empty, error, and edge states.


## The Practitioner's Notebook

### Experience Patterns I've Seen Work

**The 'two-click test':** For any task the user performs regularly (daily or weekly), it should be accomplishable in 2 clicks or fewer. If it takes 5 clicks, the user does it 5 times and then finds a workaround. If it takes 2 clicks, the user does it 100 times and builds a habit. The click count for high-frequency tasks is a direct predictor of adoption.

**The empty state opportunity:** Every empty state is a teaching moment — the moment when the user is most open to learning because they've arrived somewhere new and don't know what to do. The worst empty state: 'No data.' The best empty state: 'This is where your [thing] will live. Here's how to create your first one: [specific instruction with CTA].' Transform every empty state from a dead end into an onramp.

**The error message that builds trust:** 'Something went wrong. Please try again.' destroys trust. 'We couldn't save your changes because the connection was interrupted. Your work is saved locally — we'll sync when the connection is restored.' builds trust. The difference: specificity, honesty, and a path forward. Every error message is a trust moment. Invest in them.

**The settings page test:** The settings page reveals the team's craft commitment. A clean, organized, searchable settings page = team that cares about details. A flat list of 50 options with technical jargon = team that treats non-core pages as afterthoughts. Users notice because they visit settings when they're already frustrated (something isn't working the way they want). A bad settings experience compounds the frustration.

