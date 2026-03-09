---
id: growth-model-forecasting
name: Growth Model Forecasting
domain: ps-growth
version: 1.0.0
---
# Growth Model Forecasting
**Purpose:** Apply growth model forecasting — placeholder for expansion.
## When to use
When this product skill is the active constraint.


## Advanced Growth Practice

### The Growth Accounting Model
Revenue growth is the sum of: new revenue (new customers × ACV) + expansion revenue (existing customers upgrading) - contraction revenue (existing customers downgrading) - churn revenue (customers leaving). The **Quick Ratio** = (new + expansion) / (contraction + churn). Best-in-class SaaS: Quick Ratio >4. Healthy: 2-4. Concerning: <2. Below 1 means the business is shrinking. The Quick Ratio is more honest than revenue growth because it shows whether growth is sustainable or masking underlying churn.

### Case Study: How Slack Engineered Viral Growth
Slack's growth loop: user joins a team → team communicates in Slack → user mentions Slack to friends at other companies → friends create new Slack teams → new users join. The critical design decision: Slack made cross-company communication easy (shared channels) which meant every user was a potential growth vector for new companies. The viral coefficient (how many new users each existing user generates) exceeded 1.0 for Slack's first 3 years — meaning organic growth outpaced any paid acquisition.

### The Growth Ceiling Diagnosis
When growth slows, diagnose which ceiling you've hit:

**Acquisition ceiling:** You've saturated the channels that work. Signs: rising CAC, declining conversion rates from existing channels. Fix: find new channels or expand the TAM by repositioning.

**Activation ceiling:** You're acquiring users but they're not activating. Signs: growing signups, flat active users. Fix: simplify onboarding, improve time-to-value, better match expectations set in marketing.

**Retention ceiling:** Users activate but don't stay. Signs: good Day-1 metrics, declining Day-30. Fix: deepen the product value, build habits, address the reasons users leave.

**Monetization ceiling:** Users stay but don't pay (or don't pay more). Signs: strong usage, weak revenue per user. Fix: align pricing with value, create expansion paths, improve upgrade triggers.

**Market ceiling:** You've captured the available market. Signs: all metrics are good but growth is linear, not exponential. Fix: expand the ICP, enter adjacent markets, or build new products.

### The Referral Design Principles
Referral mechanics that actually work share these qualities:
1. **Natural context:** The referral happens as part of the product experience, not through a separate 'refer a friend' page. Dropbox: sharing files = inviting others. Calendly: scheduling a meeting = exposing the product.
2. **Both sides benefit:** The referrer and the referred both get value. Dropbox: both get extra storage. Uber: both get a discount.
3. **Low effort:** The referral action takes <30 seconds. Pre-filled messages, shareable links, one-click invites.
4. **Visible reward:** The referrer sees the impact of their referral. 'You've earned 2GB from referrals' keeps the loop going.


## The Practitioner's Notebook

### Growth Patterns I've Seen Work

**The retention first principle:** Every growth team should fix retention before investing in acquisition. A product that retains 50% at Day 30 will outgrow a product that retains 20% at Day 30, regardless of how much the second product spends on acquisition. Retention is the foundation. Acquisition is the accelerant. Pouring accelerant on a weak foundation creates a brief flame and a large expense.

**The activation insight:** Activation rate is the highest-leverage growth metric because it sits at the junction of acquisition and retention. Improving activation by 10% (e.g., from 30% to 33%) improves the effectiveness of ALL acquisition spending by 10% and improves the base for retention. No other single metric has this dual leverage.

**The fake-it-before-you-build-it principle:** Before building a referral program, manually invite 20 users to refer the product. Track who does it, who they refer, and whether the referred users activate. This manual test costs zero engineering time and tells you whether the organic referral dynamic exists. If people won't refer when asked personally, they won't refer through a systematic program.

**The growth accounting check:** Monthly, answer: how much of this month's growth came from new users vs expansion of existing users vs reactivation of dormant users? If >80% comes from new users and <10% from expansion, the product isn't deepening value — it's just adding more people to a shallow experience. Healthy growth has 3 sources, not 1.

