---
name: ai-output-verifier
description: "Checks an AI-written HR draft claim by claim for facts, numbers, sources, policy accuracy and invented detail, and marks each VERIFIED, UNVERIFIED or WRONG. Use when someone says verify this, fact-check this draft, did the AI make this up, or before sending an AI draft to anyone."
---

# Ai output verifier

Treat the AI draft as a claim, not proof. Check what can be checked and flag the rest.

## When to use
- An AI produced a draft, summary, answer or analysis that someone will rely on.
- A number, quote, policy reference or legal point appears in the draft.

## When to skip
- The user wants the draft written, not checked. Use the drafting skill instead.

## Inputs needed
- The draft.
- The source material it should rest on (policy text, data, notes), if any.

## Steps
1. List every checkable claim in the draft: facts, numbers, dates, names of policies, quotes, legal points, causal statements.
2. For each claim, compare to the supplied source. Mark VERIFIED (matches source, cite the passage), UNVERIFIED (no source supplied), or WRONG (conflicts with source, quote both).
3. Mark any legal or regulatory statement UNVERIFIED unless the user supplied the text. Add: check current law and your counsel.
4. Check arithmetic by redoing it. Show the working.
5. Flag confident wording that outruns the evidence, and invented specifics such as a precise percentage with no source.
6. Flag anything that could embarrass or harm if wrong, and list the three checks to do first.
7. Offer a corrected version only if the user asks.

## Quality bar
- No claim is marked VERIFIED without a source passage. Never verify from memory.

## Output format
A claim table (claim, status, evidence), the top three checks, and a go or hold call.

## If input is missing
Ask for the draft and any source text.

## Works with
Run after any drafting skill and before sending.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
