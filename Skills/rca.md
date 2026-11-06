---
name: rca
description: "Root cause analysis for something that broke or behaved unexpectedly. Reproduces the problem, isolates one confirmed cause, sets a success check, and records a never-again rule. Use when the user says rca, root cause, why did this break, incident review, or post-incident."
---

# RCA: root cause analysis

No fix until the root cause is confirmed in writing.

## When to use
- Something broke, behaved unexpectedly, or failed silently and the cause is not yet known.
- A fix was already tried and did not hold.

## When to skip
- The cause is already known and proven.
- A simple local bug that can be traced step by step (use ordinary debugging).

## Inputs needed
- The exact symptom: an error message, a log line, or what was seen.
- Which system or process is affected.
- Any earlier fixes tried, and what happened.

## Steps
1. Check whether this has happened before. If prior notes exist, read them first. If none are found, say 'I did not find a prior incident', never 'this has never happened'.
2. Reproduce. Treat the report as untrustworthy until you have made the failure happen yourself. Check: is it already fixed on the current version, is it already being tracked, can it be reproduced at all.
3. Write two lines: Symptom confirmed (an exact quote) and Repro (the exact steps and what was observed). If it cannot be reproduced, write UNREPRODUCED and hand it to a person with what was tried.
4. Isolate. Read the suspect source, search for the error, run one targeted check. Diagnosis only, no edits.
5. Write one line: Root cause, one sentence, with the location if known.
6. Propose a success check: a specific action and the result that proves it is fixed. Ask the user to confirm it.
7. Fix, then run the success check. If it fails twice, stop and bring in a second pair of eyes with a summary of every attempt.
8. Write the handoff: root cause, fix applied, success check and its actual result, and one never-again rule.

## Quality bar
- The root cause is one sentence, not a list of suspects.
- A stored failure reason is not proof. Re-run before trusting an old error note.
- If two earlier fixes on the same area already failed, run premortem on the proposed fix first.

## Output format
Symptom, Repro, Root cause, Success check, Fix applied, Result, Never-again rule.

## If input is missing
Ask for the exact symptom in one sentence. Do not start from a guess.

## Works with
Pairs with premortem when earlier fixes failed.

## Rules for every skill
- Use only what the user gave. Do not invent facts, quotes, numbers or dates. Write UNKNOWN or [NEED FACT] instead.
- If you are not sure, say so plainly. Never guess to look confident.
- Plain English. No dashes used as punctuation breaks.
- Never send, post or act on anything. Produce drafts for the user to decide on.
