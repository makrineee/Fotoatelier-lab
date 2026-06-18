---
name: delegation
description: Use this skill when writing the actual brief that hands a task to a specialist agent. Routing decides WHO gets the work; this skill is HOW to write the hand-off so the specialist produces the right thing the first time, with every guardrail and unconfirmed fact passed along.
---

# Delegation Skill — CEO Agent — Gallery Fotoatelier

## When to use this
After routing has decided which specialist owns a task, use this skill to write the brief you dispatch. Routing answers "who and what"; this answers "how do I hand it off well." A good brief saves a round-trip; a vague one wastes the specialist's work.

## What a good brief contains
1. **The deliverable** — the exact artifact wanted, in one line ("a single-work selling caption for the Lomidze tulip print", not "do something for Instagram").
2. **The context the specialist needs** — only what's relevant: the work, the audience, the occasion, the channel.
3. **Confirmed facts vs. placeholders** — state which facts are confirmed by Maka and which are unconfirmed. Mark every unconfirmed item as a placeholder the specialist must NOT fill in themselves.
4. **The guardrails that apply** — pass along any category/attribution/identity rule that touches this task (see below). The specialist should not have to rediscover them.
5. **Dependencies** — if this task needs another agent's output first (e.g. a price before a caption), say so and say what to wait for.
6. **Output format** — if the specialist has multiple output formats (e.g. Sales: a pricing proposal vs. a collector follow-up), name the one to use.
7. **Success criteria** — what a good answer must include, and what it must avoid.
8. **Approval expectation** — remind that the output is a draft for Maka, not something to finalize.

## Always pass guardrails forward
Do not assume the specialist will infer the task-specific guardrail — even though they have their own CLAUDE.md and skills, this request's sensitivity may not be obvious to them. If a task touches a known sensitive area, pass that guardrail explicitly in the brief:
- **Artist categories** — represented artists vs. owned archival collections vs. everyone else; never imply representation that doesn't exist.
- **Parajanov** — owned archival collection; works are photographs OF him by another photographer; never imply he took them or that he is represented.
- **Unconfirmed exhibitions** — never reference any exhibition Maka hasn't confirmed as public.
- **Currency** — GEL is the base; USD/EUR only as dated convenience.
- **Never-invent** — facts, prices, dates stay as placeholders pending Maka.
Passing the guardrail is part of the brief, not an afterthought. A brief that omits a known guardrail is an incomplete brief.

## Keep the specialist in their lane
Brief one deliverable to one owner. If you're tempted to ask a specialist for something outside their scope ("Marketing, also set the price"), stop — that's a separate brief to a different agent. Don't blur tasks across agents in a single brief.

## What a brief is NOT
- Not you doing the work — never include a drafted caption, price, or text "to save time." Brief the task; let the specialist produce it.
- Not a place to invent missing facts — if context is missing, mark it as a placeholder or get Maka's confirmation first.
- Not a re-routing — if mid-brief you realize it's the wrong owner, go back to routing.

## Example brief
> **To: Sales Agent.** Deliverable: a price proposal for the Lomidze tulip print (Small, 21×29.5cm, Limited, Photo Paper Luster).
> Context: for the online shop; international + local buyers.
> Confirmed: size, medium, rarity. Placeholders (do NOT fill): production cost, edition size — pending Maka.
> Guardrails: GEL base + USD/EUR convenience; propose, don't set; underpricing is a risk to flag, not a conclusion.
> Dependencies: none.
> Output format: edition-pricing / pricing proposal.
> Success criteria: apply the revenue-split logic from `../docs/FACTS.md` (do not restate the split here); use placeholders for production cost and edition size; do not recommend a final price as approved.
> Approval: estimate for Maka to confirm before any price is posted.

## Boundaries
- Brief the task; never do the specialist work in the brief.
- One deliverable, one owner, per brief.
- Always carry confirmed/placeholder status and every applicable guardrail forward.
- Output is always a draft for Maka; never imply the specialist may finalize.
- If the right owner is unclear, return to routing rather than guessing.
