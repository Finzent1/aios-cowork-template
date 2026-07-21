# AIOS — AI Operating System
### Workspace Template for Claude Cowork

---

## What This Is

A structured workspace that gives Claude persistent knowledge of your business — your firm, your active deals, your priorities, and your tasks. Every Cowork session starts with Claude already briefed and ready to work.

No re-explaining. No re-briefing. Just open a session and go.

---

## Setup (~10 minutes)

### Step 1 — Download this folder

1. Click the green **Code** button at the top of this page on GitHub
2. Select **Download ZIP**
3. Once downloaded, unzip the file
4. Move the unzipped folder somewhere permanent on your computer (e.g. Documents or Desktop) — Claude will read from it every session

> **Technical users:** You can also run `git clone https://github.com/Finzent1/aios-cowork-template.git` if you prefer.

---

### Step 2 — Create a Cowork Project

1. Open **Claude Desktop** and find **Projects** in the left navigation panel
2. Click the **+** button to create a new project
3. When prompted, choose **Use an existing folder on your computer**
4. Select the folder you downloaded in Step 1
5. Give your project a name (e.g. "AIOS — My Firm")
6. Choose where to save it on your computer
7. In the **Instructions** field, open `INSTRUCTIONS.md` from the folder, copy all the text, and paste it in
8. Click **Create**

**After creating the project**, you can add reference URLs (e.g. your firm website) via the project's **Context** section — look for the option to paste in a URL.

---

### Step 3 — Fill in your context files (with Claude's help)

Start a new session inside your project and send this message:

> "I'm setting this up for the first time. Help me fill in my context files."

Claude will ask you questions about your firm, your active deals, and your priorities — then write the answers directly into the context files. This takes about 5–10 minutes.

---

### Step 4 — You're set up

From now on, every session starts with Claude reading your context files and briefing you on your deals, priorities, and open tasks. No re-explaining. Just open a session and go.

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
