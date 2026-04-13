# Elon Musk Startup Advisor

Musk-inspired startup judgment framework for product, technology, and resource-allocation decisions.

## What This Skill Is
A compact decision framework for startup, product, and technology choices. It helps pressure-test ideas through first-principles reasoning, constraint analysis, and concentrated execution judgment.

## What This Skill Is Not
It is not a roleplay persona, impression, or mimicry prompt. It does not try to sound like Elon Musk. It is a structured advisor for making hard decisions under startup constraints.

## Relation To Other Musk-Style Skills
This skill focuses on entrepreneurial judgment and startup bets.
It is not a general management-pressure archetype.
It is not a roleplay persona.

## Core Decision Lens
- Start from physics, economics, or system constraints instead of inherited assumptions.
- Find the bottleneck before optimizing the rest.
- Concentrate scarce resources on the highest-leverage path.
- Balance ambition with feasibility, timing, and cost.
- Favor clear next experiments over abstract strategy.

## What You Get

The skill pushes answers into a fixed decision structure instead of generic brainstorming:

1. `问题重述`
2. `第一性原理拆解`
3. `真瓶颈判断`
4. `是否值得做`
5. `下注建议`
6. `速度目标与风险`
7. `明确的不确定性`

## Best Use Cases

- founder-level product bets
- build vs buy decisions
- infra-heavy startup ideas
- technical credibility checks
- resource concentration and sequencing
- deciding what to stop doing

## Repository Structure

```text
elon-musk-startup-advisor/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    └── research/
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        └── 06-timeline.md
```

## Research Base

This skill is grounded in a public-source research set rather than pure style imitation:

- long-form plans and written statements
- interviews and extended conversations
- expression patterns and recurring framing
- external criticism and governance blind spots
- decision records across Tesla, SpaceX, xAI, and adjacent bets
- recent timeline updates to reduce stale framing

The research notes live in [`references/research/`](./references/research).

## Example Questions
- Should we build this in-house or buy it?
- Which product bet deserves the next 90 days?
- What is the real bottleneck blocking growth?
- Is this technology plan technically credible at our budget?
- What should we stop doing to increase speed?

## Example Prompt

```text
Use $elon-musk-startup-advisor to pressure-test whether an AI coding copilot for manufacturing engineers is worth building.
```

## How To Use

Use this skill when the question is constrained, strategic, and expensive to get wrong.

Good prompts usually include:

- the decision being made
- the current bottleneck or suspected bottleneck
- the constraints: time, money, team, technical environment
- what tradeoff is actually on the table

The more factual context you provide, the less the answer needs to rely on inference.

## Boundaries
- Use the framework to improve decisions, not to justify recklessness.
- If the decision depends on missing facts, surface the gaps explicitly.
- Keep recommendations reality-checked, short, and actionable.
- Treat this as a public-material distillation, not Elon Musk himself.
