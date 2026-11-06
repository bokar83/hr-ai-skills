---
name: ai-use-case-intake
description: "Scores a proposed HR task as an AI candidate (good fit, pilot with care, or not yet) and lists what to check before starting. Use when someone says should we use AI for this, is this a good AI use case, score this workflow, or brings a new idea for automating an HR task."
---

# Ai use case intake

Decide whether an HR task is a sound candidate for AI, using a short scored check instead of enthusiasm.

## When to use
- Someone proposes using AI for a recurring HR task or process.
- Several ideas need ranking before any pilot is chosen.

## When to skip
- The task is already running and the question is how well it works. Use adoption-check-in.

## Inputs needed
- The task in plain words, who does it today, how often, and roughly how long it takes.
- What the output is used for and who sees it.
- What data goes in (describe the kind, not the real records).

## Steps
1. Restate the task in one sentence. Ask one question if the task is unclear, then stop.
2. Score each criterion 0 (poor), 1 (mixed) or 2 (strong), with one line of evidence from the user's input: volume and repetition; clear right answer or checkable output; low harm if the draft is wrong; human review is easy to keep; input data is available and can be protected; time saved is meaningful.
3. Flag as a RISK GATE any task that affects hiring, pay, promotion, discipline, termination, or access to benefits. Do not score these as simple wins. Route them to hr-ai-risk-review first.
4. Total the score out of 12. Suggest a band: 9 to 12 good candidate; 5 to 8 pilot with care; 0 to 4 not yet. Say the bands are a guide, not a rule.
5. List the three facts that would most change the score and mark each UNKNOWN until the user confirms.
6. Name the smallest safe first test: one task, one team, a small set of cases, human review on every output.
7. Recommend one of: go to pilot-design, run hr-ai-risk-review first, redesign the task, or do not use AI for this.

## Quality bar
- Every score has a reason in the user's own facts. Unknowns are shown as unknowns, never filled in.

## Output format
A one-line verdict, a scored table, the risk gate flag if any, three unknowns, and the next step.

## If input is missing
Ask for the task, the frequency, and what the output is used for.

## Works with
Next: hr-ai-risk-review, pilot-design, roi-estimate.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
