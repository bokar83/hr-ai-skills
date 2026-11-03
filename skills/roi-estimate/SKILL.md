---
name: roi-estimate
description: "Builds a conservative, assumption-first estimate of the time or cost value of an AI use, shown as ranges with the assumptions listed. Use when someone says ROI, business case, how much time will this save, what is it worth, or leaders ask for numbers."
---

# Roi estimate

Give leaders a range they can trust, with every assumption visible. Never a single hopeful number.

## When to use
- A pilot or proposal needs a value estimate.
- Someone quotes a savings figure that needs checking.

## When to skip
- No baseline data exists and nobody can estimate one. Say UNKNOWN and propose how to measure first.

## Inputs needed
- The task, volume per period and time per task today.
- Expected time with AI, with review time included.
- Costs: tool licences, setup, training, review effort (UNKNOWN if not given).

## Steps
1. List every input as an assumption with its source: measured, estimated by the user, or UNKNOWN.
2. Compute a low, middle and high case. Low uses fewer tasks and less saving; high is capped, not wishful.
3. Always include review and correction time. AI drafts that need heavy rework save less than they seem to.
4. Separate hours saved from money saved. Hours saved only become money if the time is redirected or headcount changes. Say which applies.
5. Add the costs and show net value as a range.
6. Show which single assumption moves the result most, and the cheapest way to test it.
7. State what is NOT counted: quality gains, risk reduction, morale, and the cost of mistakes.

## Quality bar
- Ranges only. All arithmetic shown. No figure appears that the user did not supply or that is not labelled an assumption.

## Output format
Assumptions table, low/middle/high result, biggest sensitivity, what is not counted.

## If input is missing
Ask for volume, current time per task and expected time with AI.

## Works with
Pairs with pilot-design and pressure-test.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
