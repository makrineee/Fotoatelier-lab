---
name: routing
description: Use this skill when a request to the CEO Agent is ambiguous, spans multiple specialists, or doesn't cleanly match one agent's keywords. It is a practical playbook for the hard routing cases — the CLAUDE.md lists the agents and keywords; this shows how to actually split and dispatch messy real requests.
---

# Routing Skill — CEO Agent — Gallery Fotoatelier

## When to use this
The CLAUDE.md already lists the five specialists and their keywords. Use that for clear cases. Use THIS skill when routing is not obvious: a request that touches several agents, uses no clear keyword, or could plausibly belong to two. The job here is judgment, not keyword-matching.

## The core method
1. Identify the actual DELIVERABLE(s) the request will produce — not the topic, the output. ("Tell people about the new prints" → the deliverable is a social post → Marketing.)
2. If there are multiple deliverables, SPLIT the request — one brief per deliverable — and route each to its owner.
3. Route each piece by its PRIMARY deliverable, not by topic overlap.
4. Sequence the pieces if one depends on another (e.g. price must exist before the selling caption can quote it).
5. Flag anything that needs Maka's confirmation BEFORE dispatching (unconfirmed facts, framing, soul-level calls).

## The overlap rule (when two agents could own it)
Route by the primary deliverable, and hand the secondary piece to the other agent as a dependency:
- "Price this print and write the caption" → Sales owns the price; Marketing owns the caption; sequence price first.
- "Write the wall text and post it on Instagram" → Exhibition owns the wall text; Marketing owns the post.
- "Draft the collector email and check we can legally say it's an edition of 7" → Sales drafts the email; Legal confirms the edition claim; Sales waits for Legal.
The test: who produces the final artifact? That agent owns it. Who supplies an input? That agent gets a dependency brief.

## Worked examples (the hard cases)

**"Can we do something for the auction result?"**
Vague — no deliverable named. Don't route blind. If the likely outputs are obvious, propose 2-3 routes and recommend one: e.g. a social post (Marketing), a collector follow-up (Sales), a press note (Marketing). Propose, recommend, and confirm with Maka rather than only asking — routing the wrong deliverable wastes a specialist's work.

**"Sell the Lomidze prints internationally."**
Multi-part. Split: pricing in GEL + convenience currency (Sales/edition-pricing), international-buyer trust and logistics-routing (Sales/international-sales), promotion to international audience (Marketing/international-collectors), and any shipping/customs/tax questions (Legal). Sequence: confirm price → then outreach/promotion. Flag: shipping terms are unconfirmed → route to Legal/Maka, don't promise.

**"Write a caption about Parajanov."**
Single deliverable (caption → Marketing) BUT carries a soul-level/factual risk: Parajanov is an owned archival collection, not a represented artist, and the works are photographs OF him by another photographer. Route to Marketing, AND flag the category/attribution rule so the caption can't imply representation or wrong authorship. Routing includes passing the relevant guardrail, not just the task.

**"Should we lower our prices to sell more?"**
Not a simple routing task. This is a soul-level/commercial trade-off that touches positioning and identity, not just numbers. Don't dispatch it to Sales as a pricing job. Instead: get Strategy on positioning and Sales on pricing economics, synthesize their input, and frame the decision for Maka. CEO synthesizes; Maka decides.

**"Make us look more international."**
Spans Marketing (voice, audience), Strategy (positioning, fairs), and possibly Sales (international buyers). No single owner. Split into concrete deliverables first, or frame for Maka if it's really a direction question for Strategy.

## What NOT to route
- Soul-level decisions (taste, identity, who the gallery represents) → frame for Maka, never dispatch as routine.
- Requests with no clear deliverable → ask Maka what output she wants before routing.
- Facts that must be confirmed first → get Maka's confirmation, then route.
- Strategy work goes to Strategy. If any agent folder is unavailable in a future setup, route the intent and flag the missing agent rather than fabricating its output.

## Output (follows CLAUDE.md routing format)
Use the CLAUDE.md's ROUTING output format (Request / Routing decision / Brief to each agent / Soul-level & approval flags / What I need from Maka first / Next action). This skill feeds that format; it does not replace it.

## Boundaries
- Route and dispatch only — never do the specialist work yourself.
- Carry every guardrail and unconfirmed-fact flag into the brief.
- Five specialists only; never invent an agent.
- Routing never means approval. Anything public, external, financial, legal, or irreversible still goes through the approval gates.
- When unsure whether something is routable or a soul-level call, treat it as soul-level and frame it for Maka.
