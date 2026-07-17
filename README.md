# AIOS — AI Operating System
### Free Workspace Template for Claude Cowork

---

## What This Is

This is a structured workspace that gives Claude persistent knowledge of your business — so every session starts with your AI fully briefed and ready to work.

No re-briefing. No re-explaining your deals, your firm, or your priorities. Just open a session and go.

---

## Setup (5 minutes)

**1. Fill in your context files**

Open each file in `context/` and fill in the details:

- `context/firm.md` — who you are, what your firm does, house style
- `context/deals.md` — your active mandates (use the template provided)
- `context/strategy.md` — current priorities, revenue target, BD focus

**2. Start your first session**

Open Claude Cowork, point it at this folder, and type:

> `/prime`

Claude will read your context and confirm it's ready. From that point on, it knows your business.

**3. Keep it current**

After any meaningful session — a deal update, a new project, a decision made — ask Claude to update the relevant file. The workspace gets more valuable the more current it is.

---

## What You Can Do With It

**Deal work**
> "Draft a teaser for [Deal Name] — two pages, executive summary up front."
> "Prepare me for my call with [Counterparty] tomorrow."
> "What's the current status of each active mandate?"

**Task management**
> "What are my open next actions?"
> "Add a waiting-for item: NDA from [Lender], sent today."
> "Let's do a weekly review."

**Document production**
> "Draft an email to [Contact] following up on the term sheet."
> "Write a one-page credit summary for [Deal] based on what you know."
> "Create a meeting agenda for tomorrow's call with [Company]."

**Research and analysis**
> "What do you know about [Counterparty] from our previous interactions?"
> "Summarise the key risks on [Deal] as you understand them."

---

## Folder Structure

```
├── CLAUDE.md              # Core instructions — always loaded
├── context/
│   ├── firm.md            # Who you are
│   ├── deals.md           # Active mandates
│   └── strategy.md        # Priorities and targets
└── gtd/
    ├── dashboard.md       # Live task state
    ├── projects.md        # Project detail
    ├── next-actions.md    # Immediate actions
    └── waiting-for.md     # Pending others
```

---

## Want the Full Version?

This template gives you persistent context, task management, and document production.

The full AIOS setup adds:
- **Live data** — pipeline metrics, revenue vs target, and lender outreach progress auto-surfaced every morning
- **Meeting intelligence** — meetings captured, classified, and summarised automatically
- **Daily news briefing** — curated market intelligence delivered before you sit down

Built on Claude Code with scripted automation and live Excel/database integration.

**To discuss a full setup:** [contact details]

---

*Created by Ciarán Flynn, Finzent*
