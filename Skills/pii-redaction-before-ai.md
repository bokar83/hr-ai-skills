---
name: pii-redaction-before-ai
description: "Shows what to strip or replace with roles before pasting HR text into an AI tool, and can redact a pasted draft. Use when someone says redact this, is it safe to paste, remove personal details, anonymize this case, or before pasting employee data into any AI tool."
---

# Pii redaction before ai

Help the user remove personal detail from text before an AI sees it, while keeping enough meaning for the task.

## When to use
- HR text with names, ids, health or family details is about to go into an AI tool.
- A team needs a simple do-and-do-not list for what may be pasted.

## When to skip
- The user's company policy bans pasting this kind of text at all. Say so and stop.

## Inputs needed
- The text to redact, or the type of document.
- The task the AI will do with it.
- The company rule on approved tools, if the user knows it.

## Steps
1. First ask: does the user's policy allow this tool for this kind of data? If UNKNOWN, say to check before pasting.
2. Replace direct identifiers with roles: names become roles (Employee A, the manager, the HR partner); ids, contact details, addresses, exact dates of birth and account numbers are removed.
3. Reduce indirect identifiers: exact job titles in small teams, rare locations, exact salaries (use a band), exact dates (use a month or an interval).
4. Mark special categories for removal unless essential: health, family status, religion, union membership, ethnicity, immigration status, disciplinary history.
5. Return the redacted text and a table of what was changed, with the placeholder used for each item, so the user can map back privately.
6. Warn that small teams and unusual events can still identify a person after redaction. Rate residual risk LOW, MEDIUM or HIGH.
7. If the task cannot be done without identifying detail, say so and suggest doing that step without AI.

## Quality bar
- Nothing identifying remains in the redacted output. Meaning needed for the task is kept.

## Output format
Redacted text, a change table, residual risk rating, and a one-line reminder to follow company policy.

## If input is missing
Ask for the text and what the AI will do with it.

## Works with
Run before any drafting skill. Pairs with hr-ai-risk-review.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
