---
name: hr-ai-council
description: "Runs a role-based expert panel on a high-stakes HR AI decision: seven standing seats, on-call seats, an always-on Contrarian and a non-voting Closer who gives a verdict. Use when someone says run the council, full review, expert panel, go or no-go on this AI rollout, or before AI touches hiring, pay, performance or monitoring. For a quick check use pressure-test."
---

# Hr ai council

A deeper, role-based review for decisions that are costly or hard to reverse. Seats are roles, never real people. For a fast check use pressure-test instead.

## When to use
- A decision affects many employees, personal data, or any hiring, pay, performance or monitoring step.
- Leaders need a go, go-with-changes or stop call with reasons.

## When to skip
- The decision is small and reversible. Use pressure-test.
- No facts are available yet. Run discovery-interview-guide first.

## Inputs needed
- The proposal in the user's words, and what is decided versus open.
- Depth: quick, standard or deep (default standard).
- Regions affected and any evidence in hand.

## Steps
1. Restate the proposal and list what it assumes. Name the decision and its deadline.
2. Seat the DEFAULT PANEL of seven roles: skeptical chief HR officer; employee-relations and consultation voice; privacy and legal counsel voice; frontline manager; security and IT voice; finance lead; adoption and change lead.
3. Add ON-CALL seats only when relevant, and say why each is called: candidate or employee voice; country or regional HR lead; accessibility and inclusion voice; union or employee-representative voice; data scientist; vendor-risk voice.
4. Always seat the CONTRARIAN, who must argue the opposite of the emerging view with the strongest honest case, even if the panel agrees.
5. Every seat must give: one concrete way this fails from its viewpoint, one thing it would need to see before agreeing, and a stance (support, support with changes, oppose, UNKNOWN). Base each point on the user's input; say UNKNOWN where there is no evidence.
6. Depth: QUICK = default seats, one line each. STANDARD = default seats plus needed on-call seats, short paragraphs. DEEP = all relevant seats, two rounds (seats react to each other), and a pre-mortem of the top risk.
7. Label every legal point: check current law and counsel, not legal advice. Never cite a statute or article number that was not supplied.
8. The CLOSER does not vote. The Closer outputs: verdict (go, go-with-changes, stop); the top three changes; what would change the verdict; and the UNKNOWNs with an owner role and the cheapest way to resolve each.

## Quality bar
- Each seat sounds like a different role with different concerns. The Contrarian is never a weak, for-show objection. No invented evidence.

## Output format
Panel table (seat, failure, needs to see, stance), Contrarian case, Closer verdict, top three changes, what would change it, UNKNOWNs.

## If input is missing
Ask for the proposal, the depth and the regions.

## Works with
Pairs with hr-ai-risk-review, roi-estimate and executive-brief. Quick version: pressure-test.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
- Legal points are prompts for review, not advice: check current law and your counsel, not legal advice. Never cite a statute or article number you were not given.
