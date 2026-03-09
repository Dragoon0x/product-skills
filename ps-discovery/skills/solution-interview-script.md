---
id: solution-interview-script
name: Solution Interview Script
domain: ps-discovery
version: 1.0.0
---
# Solution Interview Script
**Purpose:** Apply solution interview script — placeholder for expansion.
## When to use
When this product skill is the active constraint.


## Advanced Discovery Practice

### The Discovery Operating System
Discovery shouldn't be a phase — it should be a continuous operating system:

**Weekly rhythm:** 1-2 customer conversations per week, minimum. These can be 20-minute calls, not formal research projects. The goal is maintaining contact with user reality so assumptions don't calcify.

**Monthly synthesis:** Once per month, the PM reviews the last 4-8 conversations and updates the Opportunity Solution Tree. What new opportunities emerged? What existing hypotheses were validated or invalidated? What experiments should run next month?

**Quarterly strategy update:** Once per quarter, discovery insights inform the roadmap review. Are the planned initiatives still addressing the highest-priority opportunities? Has the competitive landscape shifted? Have user needs evolved?

This operating system prevents the common failure mode: discovery as a one-time project at the start of a product initiative, followed by 6 months of building without customer contact.

### Case Study: How Spotify Uses Continuous Discovery
Spotify's product teams (squads) are required to maintain continuous contact with users. Each squad has access to a user research panel and is expected to test assumptions weekly. The 'Think It, Build It, Ship It, Tweak It' model embeds discovery into every phase: Think It (discover the opportunity), Build It (prototype and test), Ship It (release to a subset), Tweak It (iterate based on real usage data). The result: Spotify ships features that are validated at every stage, reducing the risk of building things nobody wants.

### The Discovery Anti-Patterns

**The Research Report Graveyard:** Teams conduct discovery, produce a 50-page report, and file it. Nobody reads it. No decisions change. The fix: discovery outputs should be decision documents, not research reports. 'Based on 12 interviews, we recommend X because Y' — not 'Here's everything we learned.'

**The Confirmation Bias Loop:** Teams conduct discovery to validate what they've already decided to build. Interview questions are leading. Data is selectively interpreted. The fix: assign a 'red team' member whose job is to argue against the favored hypothesis. Include disconfirming evidence in every synthesis.

**The Discovery → Development Handoff Gap:** Discovery produces insights. Development starts building. The insights get lost in translation. By the time the feature ships, it doesn't match the user need it was supposed to address. The fix: the PM who led discovery stays involved through development, ensuring the insight survives implementation.

### The Research Method Decision Tree
**Need to discover new problems?** → Generative research (interviews, contextual inquiry, diary studies)
**Need to validate a specific solution?** → Evaluative research (usability testing, prototype testing, A/B testing)
**Need to measure scale?** → Quantitative research (surveys, analytics, funnel analysis)
**Need to understand behavior?** → Behavioral research (session recordings, analytics, contextual inquiry)
**Need to understand motivation?** → Attitudinal research (interviews, surveys, JTBD interviews)
**Limited time?** → 5-user usability test (catches 85% of usability issues in 1 day)
**Limited access to users?** → Analytics-driven discovery + competitive user reviews + support ticket analysis


## The Practitioner's Notebook

### Discovery Patterns I've Seen Work

**The 5-user rule:** Testing with 5 users catches 85% of usability issues (Nielsen/Norman Group). You don't need 50 users for evaluative research. For generative research (discovering new opportunities), 8-12 interviews usually reach saturation — you start hearing the same themes repeated.

**The interview recording paradox:** Recording interviews makes analysis better (you can revisit exact quotes). But it also makes participants more guarded. The fix: record with permission, but take notes as if the recording doesn't exist. The notes force you to listen for patterns in real-time. The recording is for verification, not primary analysis.

**The most valuable question:** 'Tell me about the last time you...' Past behavior is the best predictor of future behavior. 'Would you use this?' predicts nothing. 'When was the last time you needed this and what did you do?' predicts everything.

**The synthesis bottleneck:** Teams do research but don't synthesize. They have 20 interview transcripts and no insights. The fix: synthesize after every 3-5 interviews, not after all interviews are complete. Rolling synthesis surfaces patterns early and focuses remaining interviews on the most promising threads.

**Discovery doesn't end at the spec.** The biggest discovery mistake: conducting research, writing a spec, and then building for 3 months without talking to another user. By the time you ship, the insights are stale and the assumptions have drifted. Keep one weekly user touchpoint running through the entire build phase.

