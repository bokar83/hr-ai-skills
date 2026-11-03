# HR AI Skills

Plain-English skills for HR AI work: assessing where AI fits, running safe pilots, driving real adoption, and everyday HR drafting. Draft-only, role-based, and honest about what is not known.

Maintained by Boubacar Barry.

## What is in here

18 skills in the open skill format (skills/<name>/SKILL.md with a name and a description). Each skill says when to use it, what it needs, the steps, the output, and what to do when information is missing. Every skill follows the same rules: say UNKNOWN instead of guessing, draft only and never send, use roles not names.

### Decide and assess

- **ai-use-case-intake**: Scores a proposed HR task as an AI candidate (good fit, pilot with care, or not yet) and lists what to check before starting.
- **hr-ai-risk-review**: Reviews a proposed AI use in HR for bias, privacy, employee consultation, human oversight and high-risk employment uses, and lists what to check.
- **pii-redaction-before-ai**: Shows what to strip or replace with roles before pasting HR text into an AI tool, and can redact a pasted draft.
- **pressure-test**: Stress-tests a plan, proposal, decision or deliverable from five angles, with an optional pre-mortem mode that assumes it failed and works backward.
- **roi-estimate**: Builds a conservative, assumption-first estimate of the time or cost value of an AI use, shown as ranges with the assumptions listed.

### Run a pilot and drive adoption

- **pilot-design**: Designs a small, time-boxed AI pilot with a clear question, success measures, guardrails, a stop rule and a review date.
- **adoption-check-in**: Writes a 10-minute check-in script for people using a new AI tool or way of working, summarizes several check-ins into a pattern report, or logs lessons after a project.
- **training-session-designer**: Designs a short hands-on session that teaches HR colleagues to use AI safely and well, with exercises, a safety segment and a follow-up.
- **discovery-interview-guide**: Prepares questions for a conversation with a stakeholder, employee group or new manager to learn how work really happens and what AI could help or harm.

### Check and build

- **ai-output-verifier**: Checks an AI-written HR draft claim by claim for facts, numbers, sources, policy accuracy and invented detail, and marks each VERIFIED, UNVERIFIED or WRONG.
- **prompt-builder**: Rewrites a rough prompt into a stronger one (sharpen mode) or turns a repeated HR task into a reusable, tested prompt with an example and a check case (library mode).
- **skill-writer**: Turns a repeated task into a new skill file with a name, trigger description, steps and output format.

### Everyday HR drafting

- **hr-policy-qa-draft**: Drafts answers to employee questions using only the policy text the user supplies, quotes the passage, and escalates when the text does not answer.
- **employee-comms-draft**: Drafts a clear message to employees or managers about an AI change, policy, pilot or rule, with a plain-language FAQ and a translation check.
- **job-description-rewrite**: Rewrites a job description to be clear, inclusive and skills-based, flags biased or inflated wording, and separates must-haves from nice-to-haves.
- **structured-interview-kit**: Builds a structured interview kit: competencies, consistent questions, behaviour-based probes and a scoring guide, so every candidate is judged the same way.
- **performance-feedback**: Turns a manager's raw notes into clear feedback built on observed behaviour and impact, with next steps, and checks for bias or vague wording.
- **executive-brief**: Compresses any HR or AI update into a short brief that lets a leader decide fast (headline, why it matters, the ask), or turns meeting notes into decisions and owned actions.

## How to import

1. Point your AI tool at this repository's public URL: https://github.com/bokar83/hr-ai-skills (tools that import skills from GitHub will read the skills folder).
2. Or download the repository and copy the skills folder into the place your tool keeps skills.
3. Or, if your tool cannot import files, paste the whole of IMPORT_PROMPT.txt into a chat. It asks the tool to create every skill, or to hold them as callable blocks.

## How to test

After import, type one of these (all examples are hypothetical):

- `Use ai-use-case-intake. Imagine we want AI to draft first replies to common payroll questions. Score it.`
- `Use pii-redaction-before-ai on: "Imagine a note about an employee in a small team returning from leave."`
- `Use roi-estimate. Imagine 40 tasks a month, 30 minutes each, 10 minutes with AI plus review.`
- `Use pressure-test on: "We will roll out an AI assistant to all HR staff in one month."`

## Notes

- Nothing here is legal advice. Legal and regulatory points are marked for review: check current law and your counsel.
- Skills never send, post or act. They produce drafts for a person to decide on.
- Use hypothetical or redacted examples. Do not paste real employee records unless your company policy allows it for the tool you use.

## License

MIT. See LICENSE.
