# Fotoatelier-lab

**A live experiment in hybrid human-AI gallery management.**

Gallery Fotoatelier is a contemporary fine art photography gallery 
based in Tbilisi, Georgia, operating internationally. This repository 
is the operational backbone of the gallery — a real-world research 
project exploring what happens when AI agents are integrated into 
the daily management of a working art institution.

This is not a simulation. The agents in this system support real 
work alongside a human director on real exhibitions, real artists, 
real collectors, and real revenue. The experiment is live.

---

## The Question

Traditional galleries run on human judgment, relationships, and 
intuition. AI runs on consistency, speed, and scale. What happens 
when you combine both — not as a gimmick, but as a serious 
operational architecture?

What can AI do that humans don't, can't, or won't?
Where does it add genuine value?
Where does it fall short?
What does real human-AI collaboration look like inside a 
cultural institution?

Gallery Fotoatelier is the proof of concept.

---

## The System

A team of specialized AI agents, each owning a department:

| Agent | Department | Responsibility |
|-------|-----------|----------------|
| CEO | Executive | Orchestration, escalation, synthesis, approval checks |
| Marketing & PR | Communications | Content, social media, press, campaigns |
| Legal | Contracts & compliance | Agreements, invoices, GDPR, risk |
| Sales & Collector | Revenue | Print sales, collector relations, pricing |
| Exhibition & Curatorial | Programming | Exhibition planning, artist research, curatorial texts |
| Strategy & Growth | Direction | Positioning, growth planning, fairs, grants |

Each agent has:
- A `CLAUDE.md` identity file defining its role, rules, and boundaries
- A `skills/` folder with specialized knowledge files
- Clear escalation rules — agents never make final decisions alone

The human director (Maka, Gallery Fotoatelier) remains the 
decision-maker. The agents extend her capacity, not her authority.

---

## Architecture

- **Agent framework:** Claude (Anthropic) via Claude Code
- **Orchestration:** Paperclip — local CEO interface, in progress
- **Automation:** n8n workflow connections
- **Image generation:** Magica / Nano Banana model — experimental room mockups
- **Environment:** VS Code, monorepo structure

Tools and integrations will expand as the experiment progresses.
This README is a living document.

---

## What Makes This Different

Most galleries using AI are using it for captions and email drafts.

This system treats AI as a genuine operational layer — with defined 
roles, boundaries, inter-agent communication, escalation protocols, 
and real business outputs. Every agent knows what it owns, what it 
does not own, and when to escalate to the human.

It is also honest about what it does not know yet. This is research.
The system will be wrong sometimes. The point is to find out where, 
and why, and what that means for the future of cultural institutions.

---

## Gallery Fotoatelier

Website: [galleryfotoatelier.com](https://galleryfotoatelier.com)  
Instagram: [@gallery.fotoatelier](https://instagram.com/gallery.fotoatelier)  
Location: Tbilisi, Georgia  
Director: Maka Buadze

---

## Status

🟢 Core department agents active  
🟡 n8n automation in progress  
🟡 GitHub setup in progress  

---

*Built in Tbilisi. Pointed at the world.*
