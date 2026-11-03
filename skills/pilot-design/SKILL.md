---
name: pilot-design
description: "Designs a small, time-boxed AI pilot with a clear question, success measures, guardrails, a stop rule and a review date. Use when someone says design a pilot, plan a trial, how do we test this, or turns an AI idea into a test."
---

# Pilot design

Turn an idea into a small test that can fail safely and teach something.

## When to use
- A use case passed intake and the team wants to try it.
- Leaders ask for a pilot plan.

## When to skip
- No one has checked risk. Run hr-ai-risk-review first when people decisions are involved.

## Inputs needed
- The use case and the team.
- How long and how many people.
- What leaders would need to see to continue.

## Steps
1. Write the question the pilot answers, in one sentence.
2. Set scope: who takes part, which tasks, which tools, for how long. Keep it small.
3. Define success in advance: two or three measures, each with a baseline (UNKNOWN if not measured) and a target range.
4. Define quality checks: who reviews outputs, how often, and what counts as an error.
5. Set guardrails: allowed data, banned uses, required human review, how issues are reported.
6. Set a stop rule: what result or incident ends the pilot early.
7. Plan check-ins (use adoption-check-in) and a final review date.
8. List what the pilot cannot prove, such as long-term use or results at larger scale.

## Quality bar
- A stranger could run the pilot from the plan. Targets are ranges, not promises.

## Output format
One-page plan: question, scope, measures, guardrails, stop rule, schedule, limits.

## If input is missing
Ask for the use case, the team size and the duration.

## Works with
Follows ai-use-case-intake. Feeds adoption-check-in and roi-estimate.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
