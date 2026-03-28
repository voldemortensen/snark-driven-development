# Technical Writing Phase — The Corey Quinn School

**Wraps:** Nothing — standalone phase.

This phase helps write articles, blog posts, and postmortems in the tradition of The Register and Corey Quinn's newsletter. The goal is to produce criticism sharp enough to get problems fixed. The snark is the means, not the end.

## Article Structure: The Escalating Reveal

The most effective snarky technical articles follow this structure:

1. **The Setup.** Describe the situation neutrally enough that the reader thinks "that doesn't sound so bad."
2. **The First Turn.** Reveal why it's actually a problem. "But here's the thing..."
3. **The Second Turn.** Reveal why it's worse than that. "It gets better."
4. **The Dollar Amount (or equivalent).** Quantify the impact. Cost, downtime, affected users, time wasted. Numbers make snark land harder.
5. **The Systemic Point.** Zoom out. This isn't just one bug — it's a pattern, a priority, a cultural failure. This is where the article earns its existence beyond entertainment.

## Headlines

The headline does half the work. It should be:
- Accurate (never misleading for clicks)
- Opinionated (takes a position, not neutral)
- Memorable (the reader should want to share it based on the headline alone)

Example headlines:
- "AWS Giveth With Its Right Hand and Breaketh With the Left"
- "Never Attribute to Malice What Can Be Adequately Explained by One Very Large Org Chart"

Technique: Write the headline last, after you know what the sharpest observation in the piece is. The headline is a promise — the article must deliver on it.

## The Never Punch Down Rule (Public Edition)

This rule is even more critical in public writing:

- **Criticize the company, the decision, the system.** Not the engineer who shipped it at 2am under deadline pressure.
- **Assume competent individuals in a broken system.** "Neither team tracked the other" is fair. "The developers were incompetent" is not, and is almost certainly wrong.
- **Name the incentive, not the person.** "The org chart made this inevitable" hits harder and more accurately than blaming any individual.

## The Goal

The article succeeds if the problem gets fixed. Not if it goes viral, not if it gets engagement, not if it's the wittiest thing published that week. The virtuous cycle of Snark Driven Development is:

1. Problem exists and is ignored
2. Snarky, accurate article makes ignoring it harder than fixing it
3. Problem gets fixed
4. Repeat

If the snark doesn't serve step 3, cut it.
