# AIOS — AI Operating System
### Workspace Template for Claude Cowork

---

## What This Is

A structured workspace that gives Claude persistent knowledge of your business — your firm, your active deals, your priorities, and your tasks. Every Cowork session starts with Claude already briefed and ready to work.

No re-explaining. No re-briefing. Just open a session and go.

---

## Setup (~10 minutes)

### Step 1 — Download this folder

Clone or download this repository to your computer. Put it somewhere permanent — Claude will read from it every session.

```
git clone https://github.com/Finzent1/aios-cowork-template.git
```

Or download as a ZIP from GitHub and unzip it.

---

### Step 2 — Fill in your context files

Open each file in `context/` and fill in your details:

- `context/firm.md` — who you are, what your firm does, house style
- `context/deals.md` — your active mandates
- `context/strategy.md` — current priorities, revenue target, BD focus

Leave `gtd/` files as-is — Claude will help you populate them.

---

### Step 3 — Create a Cowork Project

Open **Claude Desktop** and go to the **Cowork** tab.

Create a new Project and set it up as follows:

**Description:**
> My AI business assistant — briefed on my firm, deals, and priorities.

**Folders:**
> Add the folder you downloaded in Step 1. This gives Claude access to all your context and GTD files.

**Instructions:**
> Copy the entire contents of `INSTRUCTIONS.md` from this folder and paste it here.

**Links:** *(optional)*
> Add any reference URLs you want Claude to be able to access (e.g. your firm website, key documents).

**Memory:**
> Leave this as default — Claude will build memory as you work.

---

### Step 4 — Start your first session

Open a new session inside your Cowork Project. Claude will automatically read your context files and brief you on your active deals, priorities, and open tasks.

From here, just work. Claude knows your business.

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
> "Summarise the key risks on [Deal] as you understand them."
> "What do you know about [Counterparty] from our previous interactions?"

---

## Keeping It Current

The workspace gets more valuable the more current it is. After any meaningful session:

- New deal or status change → ask Claude to update `context/deals.md`
- New task or project → ask Claude to update `gtd/`
- Strategic shift → ask Claude to update `context/strategy.md`

Claude will offer to do this automatically at the end of sessions where something significant happened.

---

## Folder Structure

```
├── README.md              # This file
├── INSTRUCTIONS.md        # Paste into Cowork Project Instructions field
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
