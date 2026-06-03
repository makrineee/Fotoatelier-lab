# Legal & Contracts Agent — Gallery Fotoatelier

The dedicated AI agent for **contracts, agreements, invoices, and legal documents** at **Gallery Fotoatelier**, Tbilisi, Georgia. It works for Maka Buadze, Gallery Director, and produces complete, ready-to-sign documents drafted for the gallery under **Georgian law**.

## What this agent does

It delivers finished, ready-to-sign documents — never outlines or "you could add a clause about…" placeholders:

- **Photographer & artist agreements** — representation, commission, licensing
- **Consignment agreements** — selling works the gallery doesn't own
- **Exhibition & loan agreements** — shows, lent works, venues, partners
- **Invoices & sales documents** — invoices, receipts, certificates of authenticity
- **GDPR & privacy documents** — privacy policy, consents, photo releases

Every document uses clearly numbered clauses, marks blanks in `[SQUARE BRACKETS]`, states amounts in **GEL (₾)**, and is governed by the **law of Georgia** unless told otherwise.

## What this agent does NOT do

It stays strictly in its lane. It will decline and redirect you to the right resource for:

- Marketing, PR, or social content
- Creative exhibition planning or curation
- Pricing or strategic business decisions
- Acting as a licensed attorney

Anything outside contracts, agreements, invoices, and legal documents is out of scope.

## Important — not legal advice

This agent produces **working drafts to speed up the gallery's paperwork — not legal advice.** Every document carries a footer asking you to have it reviewed by a qualified Georgian attorney before signing. The agent will never invent statute numbers or case law; where the law is uncertain it flags the point for attorney review.

## House rules

- **Jurisdiction:** Tbilisi, Georgia; governed by the law of Georgia unless stated otherwise.
- **Currency:** Georgian Lari (GEL / ₾) by default, stated on every figure.
- **Copyright stays with the artist** unless they explicitly assign it in writing — the gallery takes a licence.
- **Consignment:** consigned works remain the consignor's property until sold and paid in full.
- **Exhibitions/loans:** never without an insurance clause ("nail to nail").
- **GDPR matters** — the gallery sells to EU collectors, so privacy documents use opt-in consent and a clear unsubscribe.

## How to give it a task

Just describe the document and the key details. The more context, the sharper the draft. Useful details to include:

- **Document type** — e.g. representation agreement, consignment, exhibition/loan, invoice, privacy policy
- **Parties** — the artist, consignor, lender, buyer, or partner involved
- **Key terms** — commission split, prices (GEL), dates, edition sizes, territory, term
- **Counterparty location** — especially if international / EU (affects GDPR and tax)

**Examples:**

- "Draft an exclusive representation agreement with photographer Tamuna Karumidze, 50/50 split, Georgia only, 2-year term."
- "Create a consignment agreement for 8 prints a collector is leaving with us for 6 months."
- "Make an invoice for the sale of an edition print to a collector in Berlin, 4,500 GEL."
- "Write a GDPR-compliant privacy policy for our newsletter and website."

## How it works

Before producing anything, the agent reads and applies:

- **Project identity** — [CLAUDE.md](CLAUDE.md)
- **Shared context** — `../_shared/gallery-identity.md`, `../_shared/brand-rules.md`, `../_shared/partners.md`
- **Relevant skill** from [skills/](skills/):
  - [photographer-contracts.md](skills/photographer-contracts.md) — artist representation, commission, licensing
  - [consignment-agreements.md](skills/consignment-agreements.md) — consignment of works and editions
  - [exhibition-agreements.md](skills/exhibition-agreements.md) — exhibition, loan, and venue agreements
  - [invoices.md](skills/invoices.md) — invoices, receipts, certificates of authenticity
  - [gdpr-privacy.md](skills/gdpr-privacy.md) — GDPR, privacy policies, consents, photo releases

## Setup

1. Copy your Anthropic API key into `.env`:
   ```
   ANTHROPIC_API_KEY=your-key-here
   ```
2. `.env` is git-ignored and never committed.
