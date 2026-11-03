---
name: ai-incident-review
description: "Walks a team through what to do when an AI output caused harm or nearly did: contain, record, find the cause, tell the right people and change the process. Use when someone says AI got it wrong, incident review, near miss, bad AI answer sent, or data pasted by mistake."
---

# Ai incident review

Treat AI errors like any workplace incident: contain, learn, fix the process, no blame.

## When to use
- An AI output or use caused or nearly caused harm, a leak or a wrong decision.

## When to skip
- Someone reports serious harm to a person. Involve the HR partner and legal counsel now; use this only to structure notes.

## Inputs needed
- What happened in plain, redacted words.
- Who noticed and when.
- What data or decision was involved.

## Steps
1. Write the timeline in facts only: what happened, when, who noticed, what the AI did.
2. Contain: list the immediate steps (stop use, retrieve or correct what went out, preserve evidence) and who owns each.
3. Classify: near miss, error with no harm, harm to a person, data exposure. Say UNKNOWN where unclear.
4. Check notification needs: affected people, managers, privacy or legal owners, regulators. Say: check current law and counsel for any duty to notify; do not state deadlines.
5. Find causes in layers: input, tool, prompt, review step, training, policy. Ask what made the mistake easy.
6. Write corrective actions with owner role and date, and one change to the process, not just a reminder.
7. Write a short, non-blaming summary for sharing. Log lessons (see adoption-check-in lessons mode).

## Quality bar
- Facts only. No blame on named people. No legal conclusions.

## Output format
Timeline, classification, containment list, notification checks, causes and actions.

## If input is missing
Ask what happened and what data or decision was involved.

## Works with
Pairs with ai-use-policy-draft and hr-ai-risk-review.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
- Legal points are prompts for review, not advice: check current law and your counsel, not legal advice. Never cite a statute or article number you were not given.
