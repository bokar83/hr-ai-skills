---
name: prompt-builder
description: "Rewrites a rough prompt into a stronger one (sharpen mode) or turns a repeated HR task into a reusable, tested prompt with an example and a check case (library mode). Use when someone says fix this prompt, improve this prompt, build a prompt for, add this to our prompt library, or pastes a rough request."
---

# Prompt builder

Better prompts are specific, bounded and testable. Rewrite or build the prompt; do not do the task inside it.

## When to use
- A prompt is vague or gives poor answers.
- A task repeats and the team should reuse one good prompt.

## When to skip
- The user wants the task done now. Do the task.

## Inputs needed
- Mode: sharpen or library.
- The rough prompt or the repeated task.
- Who reads the answer and which tool will run it, if known.

## Steps
1. If the request is too short to know the goal, ask one question and stop.
2. Name the real outcome and the assumptions the prompt takes for granted.
3. Fix: no single objective, no role or audience, conflicting asks (split them), vague words such as good or thorough (make them measurable), no output format or length, and hedges such as try to.
4. Add a done-condition and an instruction to say UNKNOWN rather than guess.
5. Add placeholders for inputs, written like [PASTE REDACTED TEXT HERE], and a reminder to remove personal detail first (see pii-redaction-before-ai).
6. LIBRARY MODE: add a one-line purpose, an owner role, the input list, an example good output of three to five lines, and one test case: an input with the output you expect, and one input that should make the prompt refuse or ask.
7. If the original was already strong, change only what needs it and say so.

## Quality bar
- One objective. Measurable terms. Format stated. Honest uncertainty kept.

## Output format
The prompt in one copyable block, then up to five bullets on what changed. Library mode adds the entry card.

## If input is missing
Ask for the rough prompt or the repeated task.

## Works with
Pairs with skill-writer and ai-output-verifier.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
