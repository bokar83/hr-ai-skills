---
name: premortem
description: "Assumes the plan already failed six months from now and works backward to explain why, then gives top causes, tripwires and cheap changes to make now. Use when the user says premortem, pre-mortem, premortem this, imagine this failed, or what would kill this plan."
---

# Premortem

It is six months from now and the plan died. Explain how, while there is still time to change it.

## When to use
- Money, time, people or reputation are committed and the decision is hard to reverse.
- A plan feels certain and nobody has tried to break it.

## When to skip
- The decision is small or easy to undo.
- The user wants a balanced verdict (use pressure-test, or hr-ai-council for a high-stakes people decision).

## Inputs needed
- The plan in the user's words.
- The finish date.
- The success definition: what winning looks like.

## Steps
1. Restate the plan in one line with its finish date and success definition.
2. Write five retrospective voices, each in the past tense. Not 'could fail' but 'failed, and here is why'.
3. Contrarian: the chain of events that killed it.
4. First Principles Thinker: the one assumption nobody wrote down.
5. Outsider: what an observer saw coming that insiders ignored.
6. Expansionist: what was never tried that would have saved it.
7. Executor: the earliest warning sign that was ignored, and the week it appeared.
8. TOP THREE CAUSES, ranked by likelihood times damage.
9. TRIPWIRES: for each cause, one observable signal and a date to check it.
10. WHAT TO CHANGE NOW: three cheap changes.
11. WHAT TO STOP BELIEVING: one comfortable belief to try to break this week.

## Quality bar
- Under 600 words in total.
- Past tense in the five voices.
- Every cause the user has not confirmed is labeled UNVERIFIED, with a way to check it.
- Tripwires are things someone can actually see, not feelings.

## Output format
Five short voice sections, then TOP THREE CAUSES, TRIPWIRES, WHAT TO CHANGE NOW, WHAT TO STOP BELIEVING.

## If input is missing
Ask for the plan. Ask for the finish date and the success definition. Do not guess either.

## Works with
Run after what-must-be-true. pressure-test includes a pre-mortem mode; this skill goes deeper on one failure story.

## Rules for every skill
- Use only what the user gave. Do not invent facts, quotes, numbers or dates. Write UNKNOWN or [NEED FACT] instead.
- If you are not sure, say so plainly. Never guess to look confident.
- Plain English. No dashes used as punctuation breaks.
- Never send, post or act on anything. Produce drafts for the user to decide on.
