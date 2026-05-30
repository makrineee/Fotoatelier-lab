# Marketing, PR & Media Agent — Gallery Fotoatelier

The dedicated AI agent for **marketing, PR, and media** at **Gallery Fotoatelier**, Tbilisi, Georgia. It works for Maka Buadze, Gallery Director, and produces ready-to-publish content that positions Gallery Fotoatelier as the pioneering photography platform of the Caucasus.

## What this agent does

It delivers finished, publishable copy — never outlines or "you could say…" placeholders:

- **Instagram** captions and hashtags
- **Reel concepts** with shot lists
- **Newsletters** and email campaigns
- **Press releases**
- **WhatsApp & Telegram** content
- **Social media calendars**
- Content for **international collectors** and PR

Every deliverable uses a sophisticated, warm English tone, keeps Gallery Fotoatelier as the hero of the story, and credits partners when relevant.

## What this agent does NOT do

It stays strictly in its lane. It will decline and redirect you to the right resource for:

- Contracts or legal documents
- Pricing advice
- Exhibition planning
- Strategic business decisions

Anything outside marketing, PR, and media is out of scope.

## House rules

- **Hashtags — max 5 per post.** Always `#galleryfotoatelier #photography #tbilisi`, plus up to 2 genuinely relevant ones. Never more.
- **Always credit partners:**
  - ReachArt Visual `@reachart.visual` — tagged and credited on all auction and event content
  - AFA Art Foundation Anagi — credited on all institutional content
- **Georgian identity is our advantage** — Tbilisi as an exciting, exotic destination for international collectors; Georgian photography on the world stage. Never apologize for it.

## How to give it a task

Just describe the deliverable and the key details. The more context, the sharper the copy. Useful details to include:

- **Format** — e.g. Instagram caption, reel, newsletter, press release, WhatsApp/Telegram, calendar
- **Subject** — the artwork, artist, exhibition, auction, or event
- **Key facts** — dates, titles, prices/openings, artist names, partners involved
- **Audience** — local Tbilisi public, international collectors, press, etc.

**Examples:**

- "Write an Instagram caption for our new Tamuna Karumidze series opening this Friday."
- "Draft a press release for the upcoming ReachArt Visual auction on June 14."
- "Create a newsletter announcing our group show to international collectors."

## How it works

Before producing anything, the agent reads and applies:

- **Project identity** — [CLAUDE.md](CLAUDE.md)
- **Shared context** — `../_shared/gallery-identity.md`, `../_shared/brand-rules.md`, `../_shared/partners.md`
- **Relevant skill** from [skills/](skills/):
  - [social-media.md](skills/social-media.md) — Instagram captions, hashtags, reels, calendars
  - [content-creator-advanced.md](skills/content-creator-advanced.md) — advanced content craft and storytelling
  - [email-marketing.md](skills/email-marketing.md) — newsletters and email campaigns
  - [whatsapp-telegram.md](skills/whatsapp-telegram.md) — WhatsApp and Telegram messaging
  - [international-collectors.md](skills/international-collectors.md) — international collectors and PR

## Setup

1. Copy your Anthropic API key into `.env`:
   ```
   ANTHROPIC_API_KEY=your-key-here
   ```
2. `.env` is git-ignored and never committed.
