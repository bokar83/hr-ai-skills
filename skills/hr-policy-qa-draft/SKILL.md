---
name: hr-policy-qa-draft
description: "Drafts answers to employee questions using only the policy text the user supplies, quotes the passage, and escalates when the text does not answer. Use when someone says answer this policy question, draft a reply from the handbook, policy lookup, or builds a policy question and answer set."
---

# Hr policy qa draft

Answer from the supplied text only. If the text does not say it, the answer is that it does not say it.

## When to use
- An employee question needs a draft reply grounded in a written policy.
- A team is building a question and answer set from its own policy text.

## When to skip
- No policy text is supplied. Ask for it, do not answer from general knowledge.

## Inputs needed
- The question, in redacted form.
- The policy passage or document, with its version or date if known.
- The region it applies to.

## Steps
1. Check that the question can be answered from the supplied text. If not, say so first.
2. Quote the exact passage that answers it and name its section.
3. Write the answer in plain English in three to six sentences. Do not add rules that are not in the text.
4. State conditions and exceptions found in the text. State what the text does not cover.
5. Escalate to a named role (such as the HR partner or legal counsel) when the question involves a legal right, a dispute, discrimination, health, leave entitlement, termination or anything the text leaves open. Write: check current law and your counsel, not legal advice.
6. Mark the version and date of the policy used, or UNKNOWN.
7. Offer a short, kind reply for the employee and keep the internal notes separate.

## Quality bar
- Every claim traces to a quoted passage. No guessing across regions or versions.

## Output format
Employee-ready draft, the quoted passage, a not-covered list, and an escalation line if needed.

## If input is missing
Ask for the question and the policy text.

## Works with
Pairs with ai-output-verifier and pii-redaction-before-ai.

## Rules for every skill
- Use only what the user gave. Say UNKNOWN (or [NEED FACT]) instead of guessing. Do not invent facts, quotes, numbers, dates or sources.
- Draft only. Never send, post or act on anything. The user decides.
- Use roles, not names. Ask the user to remove personal detail before pasting.
- Plain English. No hype.
- Legal points are prompts for review, not advice: check current law and your counsel, not legal advice. Never cite a statute or article number you were not given.
