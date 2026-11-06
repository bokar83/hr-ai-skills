---
name: hr-ai-risk-review
description: "Reviews a proposed AI use in HR for bias, privacy, employee consultation, human oversight and high-risk employment uses, and lists what to check. Use when someone says risk review, is this legal, bias check, works council, high-risk use, or before any AI touches hiring, pay, performance or discipline decisions."
---

# Hr ai risk review

Produce a plain-English risk review that tells the team what to check and who to involve. This is a checklist for a human reviewer, not legal advice.

## When to use
- An AI use touches people decisions or personal data.
- A pilot is about to start and no one has looked at risk yet.

## When to skip
- The use is a purely personal productivity task with no personal data and no decisions about people.

## Inputs needed
- What the AI will do, with what input, and who acts on the output.
- Countries or regions where the affected people work.
- Whether any decision about a person depends on the output.

## Steps
1. State the use in one sentence and say whether a decision about a person depends on it (yes, no, UNKNOWN).
2. Check each area and rate it LOW, MEDIUM, HIGH or UNKNOWN with the reason: fairness and bias (could the output differ by group); personal data (what is entered, where it goes, how long it stays); transparency (do affected people know AI was used); human oversight (can a person review and overrule every output); accuracy (how will errors be found); consultation (do employee representatives, works councils or similar bodies need to be told or asked); documentation (what record is kept).
3. Treat these as high-risk by default and say so: screening or ranking candidates, deciding pay or promotion, monitoring employees, and any step that leads to discipline or termination.
4. For each region named, write: Check current law and your counsel. Do not cite a statute, regulation or article number unless the user supplied the text. If you are unsure of a rule, write UNKNOWN.
5. List required actions before launch, who owns each, and what would stop the pilot.
6. Give a plain verdict: proceed, proceed with conditions, or do not proceed yet.

## Quality bar
- No invented laws, dates or article numbers. Every legal point carries the label: check current law and your counsel, not legal advice.

## Output format
Verdict, risk table, required actions with owners, open questions, and the legal-check line.

## If input is missing
Ask for the use, the regions, and whether a decision about a person depends on it.

## Works with
Pairs with pii-redaction-before-ai and pilot-design.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
- Legal points are prompts for review, not advice: check current law and your counsel, not legal advice. Never cite a statute or article number you were not given.
