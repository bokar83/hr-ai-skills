# HR AI Skills

Plain-English skills for HR AI work: assessing where AI fits, running safe pilots, driving real adoption, and everyday HR drafting. Draft-only, role-based, and honest about what is not known.

Maintained by Boubacar Barry.

## What is in here

36 skills in the open skill format. Each skill is provided in two layouts with identical content: a flat file in the Skills folder (Skills/<skill-name>.md) and a folder per skill (skills/<skill-name>/SKILL.md), so tools that import from either layout can read them. Every skill has a name and a description. Each skill says when to use it, what it needs, the steps, the output, and what to do when information is missing. Every skill follows the same rules: say UNKNOWN instead of guessing, draft only and never send, use roles not names.

### Decide and assess

- **hr-ai-council**: Runs a role-based expert panel on a high-stakes HR AI decision: seven standing seats, on-call seats, an always-on Contrarian and a non-voting Closer who gives a verdict.
- **pressure-test**: Quick five-voice stress test of a plan, proposal or decision, with an optional pre-mortem mode that assumes it failed and works backward.
- **ai-use-case-intake**: Scores a proposed HR task as an AI candidate (good fit, pilot with care, or not yet) and lists what to check before starting.
- **hr-ai-risk-review**: Reviews a proposed AI use in HR for bias, privacy, employee consultation, human oversight and high-risk employment uses, and lists what to check.
- **vendor-ai-evaluation**: Builds a question list and scoring sheet for evaluating an HR technology or AI vendor: data location, bias testing evidence, retention, sub-processors, security, exit.
- **roi-estimate**: Builds a conservative, assumption-first estimate of the time or cost value of an AI use, shown as ranges with the assumptions listed.
- **pii-redaction-before-ai**: Shows what to strip or replace with roles before pasting HR text into an AI tool, and can redact a pasted draft.
- **lateral-leverage**: Finds ways to repurpose or recombine what already exists before anyone builds or buys something new, then filters hard down to one to three survivors.
- **premortem**: Assumes the plan already failed six months from now and works backward to explain why, then gives top causes, tripwires and cheap changes to make now.
- **what-must-be-true**: Turns a goal or promise into checkable conditions scored TRUE, FALSE or UNKNOWN, with a verdict and the cheapest next check.
- **grilling**: The AI interviews the user one hard question at a time to expose weak spots in an idea, plan or position.

### Plan, pilot and roll out

- **pilot-design**: Designs a small, time-boxed AI pilot with a clear question, success measures, guardrails, a stop rule and a review date.
- **change-impact-assessment**: Maps who is affected by an AI or process change, what changes for each group, what they must do differently, and where resistance or harm is likely.
- **global-rollout-planner**: Plans a multi-country rollout of an AI tool or practice, with a per-country checklist for language, consultation, data transfer and local owners.
- **ai-use-policy-draft**: Drafts a plain-English AI acceptable-use policy for HR staff or employees from the facts the user supplies, with open questions marked.
- **discovery-interview-guide**: Prepares questions for a conversation with a stakeholder, employee group or new manager to learn how work really happens and what AI could help or harm.
- **prd**: A short project brief written before work starts: goal, who it is for, what is in, what is explicitly not in, success measure, risks, and a GO, NO-GO or PIVOT call.

### Drive adoption and learn

- **adoption-check-in**: Writes a 10-minute check-in script for people using a new AI tool or way of working, summarizes several check-ins into a pattern report, or logs lessons after a project.
- **training-session-designer**: Designs a short hands-on session that teaches HR colleagues to use AI safely and well, with exercises, a safety segment and a follow-up.
- **ai-champions-network**: Designs and runs a small network of AI champions inside HR: roles, selection, time, meeting rhythm and how to share what works.
- **ai-incident-review**: Walks a team through what to do when an AI output caused harm or nearly did: contain, record, find the cause, tell the right people and change the process.
- **lessons-log**: Turns a week of rough notes into a lessons log entry and decision records, then runs a 20-minute Friday review.
- **rca**: Root cause analysis for something that broke or behaved unexpectedly. Reproduces the problem, isolates one confirmed cause, sets a success check, and records a never-again rule.

### Check and build

- **ai-output-verifier**: Checks an AI-written HR draft claim by claim for facts, numbers, sources, policy accuracy and invented detail, and marks each VERIFIED, UNVERIFIED or WRONG.
- **hr-data-insights**: Guides safe analysis of HR data with AI: protecting small groups, avoiding individual conclusions, stating caveats and checking the numbers.
- **prompt-builder**: Rewrites a rough prompt into a stronger one (sharpen mode) or turns a repeated HR task into a reusable, tested prompt with an example and a check case (library mode).
- **skill-writer**: Turns a repeated task into a new skill file with a name, trigger description, steps and output format.

### Everyday HR drafting

- **hr-policy-qa-draft**: Drafts answers to employee questions using only the policy text the user supplies, quotes the passage, and escalates when the text does not answer.
- **employee-comms-draft**: Drafts a clear message to employees or managers about an AI change, policy, pilot or rule, with a plain-language FAQ and a translation check.
- **job-description-rewrite**: Rewrites a job description to be clear, inclusive and skills-based, flags biased or inflated wording, and separates must-haves from nice-to-haves.
- **structured-interview-kit**: Builds a structured interview kit: competencies, consistent questions, behaviour-based probes and a scoring guide, so every candidate is judged the same way.
- **performance-feedback**: Turns a manager's raw notes into clear feedback built on observed behaviour and impact, with next steps, and checks for bias or vague wording.
- **onboarding-plan-builder**: Builds a structured first 30, 60 and 90 day onboarding plan for a new employee, including how to learn the approved AI tools.
- **executive-brief**: Compresses any HR or AI update into a short brief that lets a leader decide fast (headline, why it matters, the ask), or turns meeting notes into decisions and owned actions.
- **humanize**: Removes the recognizable habits of machine-written text without changing meaning.
- **meeting-actions**: Turns messy meeting notes or a transcript into decisions, actions with owners, open questions, risks and a follow-up message.

## How to import

1. Point your AI tool at this repository's public URL: https://github.com/bokar83/hr-ai-skills (tools that import skills from GitHub will read the Skills folder or the skills folder).
2. Or download the repository and copy the Skills folder (or the skills folder) into the place your tool keeps skills.
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
