---
name: meeting-actions
description: "Turns messy meeting notes or a transcript into decisions, actions with owners, open questions, risks and a follow-up message. Use when the user says meeting notes, action items, summarize this meeting, or pastes a transcript."
---

# Meeting notes to actions

Report only what was said. Never assign an action unless the notes show the person agreed. Write UNKNOWN for a missing owner or date.

## When to use
- Notes, a transcript or a voice dump need a clean record and follow-ups.

## When to skip
- The user wants an opinion on the meeting.

## Inputs needed
- The notes or transcript.
- Attendees by role.
- The purpose of the meeting in one line.

## Steps
1. PURPOSE: one sentence.
2. DECISIONS: a numbered list of what was decided in plain words. If the group seemed to agree but nobody said so, put it under OPEN QUESTIONS.
3. ACTIONS: a table with Action | Owner | Due date | Source line (a short quote). UNKNOWN where not stated.
4. OPEN QUESTIONS: raised and not settled, each with who might answer.
5. RISKS AND CONCERNS: only those someone voiced.
6. WHAT I INFERRED: anything concluded rather than read, each labeled as inference.
7. FOLLOW-UP MESSAGE: a short plain note to attendees that confirms decisions and actions and invites corrections. Under 120 words, first person, no dashes as punctuation.
8. End by asking: What did I miss? Who needs to see this who was not in the room?

## Quality bar
- Nothing invented. Every action traceable to a quote.

## Output format
The seven parts above in order.

## If input is missing
Ask for the notes. Attendees and purpose are optional.

## Works with
Feeds lessons-log and employee-comms-draft.

## Rules for every skill
- Use only what the user gave. Do not invent facts, quotes, numbers or dates. Write UNKNOWN or [NEED FACT] instead.
- If you are not sure, say so plainly. Never guess to look confident.
- Plain English. No dashes used as punctuation breaks.
- Never send, post or act on anything. Produce drafts for the user to decide on.
