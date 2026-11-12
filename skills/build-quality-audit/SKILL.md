---
name: build-quality-audit
description: "Audits a prompt, agent, workflow or automation against ten quality principles before it is shared or relied on, with PASS, WARN or FAIL per principle. Use when the user says audit this agent, review this workflow, is this ready to share, quality check this build, or before shipping."
---

# Build quality audit

A ten-point check for anything you built with AI that other people will rely on. It finds the problems before your colleagues do.

## When to use
- An agent, prompt, workflow, template or automation is about to be shared.
- Something you built keeps giving uneven results.
- You changed a working build and want to confirm nothing else broke.

## When to skip
- The build is a one-off for your own use and no one else will see the result.
- Something already broke and you need the cause. Use rca.

## Inputs needed
- The build itself: the prompt text, the steps, or a description of the workflow.
- What it is supposed to do, in one sentence, and who uses it.
- Two or three real or realistic test inputs and the outputs they produced, if you have them.

## Steps
1. State the goal of the build in one sentence and the done-condition: how a person would check that it worked. If the goal is unclear, ask one question and stop.
2. Score each principle PASS, WARN or FAIL, with one line of evidence quoted from the build:
   1. Think first: assumptions are written down, open questions were asked, not guessed.
   2. Simplicity: it is the smallest build that meets the goal. No extra steps, options or features nobody asked for.
   3. Surgical changes: the last edit touched only what had to change. Nothing unrelated was reworded or restructured.
   4. Clear goal: there is a stated, checkable done-condition, and the build loops back when the result does not match it.
   5. Hot spots: nothing repeats the same work, loops without an end, or forces the user to re-enter the same input.
   6. Verification: there is at least one test input with a known good answer, and the build was run against it. Feels fine is not a test.
   7. Failure handling: the build says what to do on an error or an empty input, instead of guessing.
   8. Dependencies: every tool, file, data source or link it needs is named. Each one is something the user will really have, and each one adds risk.
   9. Honest communication: where the build is unsure, it says so plainly. It never presents a guess as a fact.
   10. Common failure patterns: no kitchen sink (everything added), no wrong abstraction (a general tool for one job), no optimistic path (only the happy case tested), no runaway rewrite (a small fix that became a full redo).
3. For every FAIL or WARN, write the exact change needed, in one sentence.
4. Give a call: READY, READY AFTER FIXES (list them), or NOT READY.
5. Say what you could not check from what was supplied.

## Quality bar
- Every score cites the build. No score without evidence.
- Fixes are specific changes, not advice like improve clarity.

## Output format
A table: Principle | Status | Evidence | Fix. Then the call, then what could not be checked.

## If input is missing
Ask for the build and its goal. If there are no test inputs, mark principle 6 as FAIL and say why.

## Works with
Run after prompt-builder or skill-writer and before sharing. Use rca if something already went wrong. Pairs with ai-output-verifier for checking the outputs.

## Rules for every skill
- Use only what the user gave. Do not invent facts, quotes, numbers or dates. Write UNKNOWN or [NEED FACT] instead.
- If you are not sure, say so plainly. Never guess to look confident.
- Plain English. No dashes used as punctuation breaks.
- Never send, post or act on anything. Produce drafts for the user to decide on.
