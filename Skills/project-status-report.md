---
name: project-status-report
description: "Turns the status facts you supply into a one-page project scorecard: on track, at risk or late for each item, what is late and why, and the decisions needed. Use when the user says status report, project scorecard, where are we late, weekly update, or are we on track."
---

# Project status report

One page that shows where a project stands and what needs a decision. Built only from the facts you give it.

## When to use
- You run a pilot, rollout or workstream and owe a regular update.
- You need to see quickly which items are slipping.
- A sponsor asks are we on track and you want a straight answer.

## When to skip
- The project has no plan or dates yet. Use prd or pilot-design first.
- You need a root cause for a failure. Use rca.

## Inputs needed
- The plan: items or milestones with owner role and due date.
- Current state of each item: done, in progress, not started, or blocked, with any numbers (for example sessions delivered against target).
- Today's date.
- Open risks and any decisions waiting on someone.

## Steps
1. Restate the project goal in one sentence and the date being reported on.
2. For each item, set a status from the facts given:
   - DONE: finished, with evidence.
   - ON TRACK: started and pace matches the plan.
   - AT RISK: pace is behind, a dependency is missing, or no update is available.
   - LATE: past the due date and not done.
   - NO DATA: nothing was supplied. This counts as a warning, not a pass.
3. For numeric targets, do the pace arithmetic in plain view: target, actual so far, share of time elapsed, the pace needed from now to finish. Show the numbers. If an input is missing, mark NO DATA, do not estimate.
4. List what is late or at risk, each with a cause if known and one proposed next step. Mark unknown causes as UNKNOWN.
5. List decisions needed: what, from which role, by when.
6. List the top three risks with an early warning sign each.
7. Give an overall call: ON TRACK, AT RISK or OFF TRACK, with one sentence of reason that follows from the item statuses.
8. Add a line for what changed since the last report, if a previous status was supplied.

## Quality bar
- Every status traces to a fact you were given. Empty fields are NO DATA, not green.
- Numbers are shown with their working so a reader can check them.

## Output format
1 Goal and date. 2 Overall call. 3 Table: Item | Owner role | Due | Status | Note. 4 Pace numbers. 5 Late or at risk. 6 Decisions needed. 7 Top three risks. 8 What changed.

## If input is missing
Ask for the plan and today's date. For any item without an update, report NO DATA.

## Works with
Use executive-brief to compress it for a leader. Pairs with lessons-log for the end of the project and adoption-check-in for people-side signals.

## Rules for every skill
- Use only what the user gave. Do not invent facts, quotes, numbers or dates. Write UNKNOWN or [NEED FACT] instead.
- If you are not sure, say so plainly. Never guess to look confident.
- Plain English. No dashes used as punctuation breaks.
- Never send, post or act on anything. Produce drafts for the user to decide on.
