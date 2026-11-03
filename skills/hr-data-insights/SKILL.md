---
name: hr-data-insights
description: "Guides safe analysis of HR data with AI: protecting small groups, avoiding individual conclusions, stating caveats and checking the numbers. Use when someone says analyze HR data, turnover analysis, survey results, headcount trends, or can I paste this spreadsheet."
---

# Hr data insights

Numbers about people can harm people. Aggregate, protect small groups, state what the data cannot say.

## When to use
- Someone wants patterns from engagement, turnover, pay or similar data.

## When to skip
- The goal is to judge or rank named individuals. Stop and explain why.

## Inputs needed
- The question the analysis should answer.
- A description of the columns and counts, or redacted or aggregated data.
- Minimum group size rule, if the company has one.

## Steps
1. Confirm the question and what decision it informs.
2. Check data handling first: is the tool approved for this data, and has identifying detail been removed (see pii-redaction-before-ai).
3. Set a minimum group size (suggest five unless the user supplies another) and suppress or merge any cell below it.
4. Analyze at group level only. Never draw conclusions about one person.
5. State what the data cannot show: causes, small samples, missing groups, self-report bias.
6. Show arithmetic and counts. Ask the user to verify with ai-output-verifier before sharing.
7. Write findings as: what the data shows, how sure, what it does not show, what to check next.
8. Warn if a result could identify someone by combination (for example a rare role plus location).

## Quality bar
- Nothing is concluded beyond the data. Small groups are protected.

## Output format
Findings with confidence notes, suppressed-cell list, caveats and next checks.

## If input is missing
Ask for the question and a data description.

## Works with
Pairs with ai-output-verifier and hr-ai-risk-review.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
