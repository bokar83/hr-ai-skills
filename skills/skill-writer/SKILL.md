---
name: skill-writer
description: "Turns a repeated task into a new skill file with a name, trigger description, steps and output format. Use when someone says make this a skill, write a skill for, turn this into a reusable skill, or has done the same task three times."
---

# Skill writer

A skill is a short instruction file an AI follows the same way every time. Write one that a stranger can use.

## When to use
- The same kind of task keeps coming back.
- A good prompt should become a shared, named routine.

## When to skip
- The task happens once. Just do it.

## Inputs needed
- A description of the task, or a transcript of how the user did it.
- An example input and a good output, if available.
- Who will use it.

## Steps
1. Ask for one real example if none was given.
2. Pick a kebab-case name of one to three words. The folder and the name field must match.
3. Write the description in one or two sentences: what it does, then phrases a user would say to trigger it.
4. Write sections: When to use, When to skip, Inputs, Steps (numbered, one action each), Quality bar, Output format, If input is missing, Works with.
5. Include the standing rules: say UNKNOWN instead of guessing, draft only and never send, use roles not names.
6. Keep it under 120 lines. Cut anything the AI already does by default.
7. Write one test: an input and the output it should produce. Run it mentally and fix gaps.
8. Output the file with its folder path.

## Quality bar
- No personal or company detail. Plain English. A reader can follow the steps without asking questions.

## Output format
The complete SKILL.md in one block, the folder path, and the test case.

## If input is missing
Ask for the task and one real example.

## Works with
Pairs with prompt-builder.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
