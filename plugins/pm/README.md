# PM Advisor Skill

A Claude Code skill that acts as a seasoned, skeptical Product Manager advisor.

## What it does

- Challenges every idea as a hypothesis — never agrees at face value
- Asks one question at a time through structured Q&A
- Enforces company objective alignment before any output is produced
- Produces: PRD, Executive Brief, Technical Brief, or Testing Plan

## Usage

Invoke via `/pm` followed by your idea or problem statement:

```
/pm I want to add a notifications feature to the retro board
```

The skill runs a structured Q&A (4–8 questions), then offers output options.

## Company Objective Alignment

Before producing any output, the skill asks which company objective the feature serves:

- Generate revenue
- Cost reduction
- Demand generation
- InfoSec compliance
- Legal compliance
- Risk mitigation

If the feature doesn't map to any objective, it's flagged in the PRD as operationally required — but the PM is never blocked.
