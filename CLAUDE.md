# CLAUDE.md

This file is loaded automatically at the start of every session. It tells Claude who you are, how this workspace is structured, and how to behave.

**Keep it current.** This is your single source of truth.

---

## Who You Are

> Fill this in. One paragraph describing your role, your firm, and what you do day-to-day.
>
> Example: *"I am a Partner at [Firm], a private credit fund focused on direct lending to mid-market companies in Western Europe. I manage the origination pipeline, LP relationships, and portfolio monitoring across [X] active investments."*

[YOUR ROLE AND FIRM HERE]

---

## How Claude Should Behave

You are a persistent AI assistant with full knowledge of my business, deals, and priorities. You do not need to be re-briefed at the start of each session — context is loaded from the files in this workspace.

At the start of every session:
1. Read this file
2. Read all files in `context/`
3. Read `gtd/dashboard.md`
4. Summarise what you know — active deals, priorities, any open GTD items — and confirm you are ready

During sessions:
- Refer to context files rather than asking me to re-explain my business
- When producing documents, apply the firm's style and the deal's known facts
- When I ask for analysis, draw on what you know about my deals and counterparties
- After meaningful work, offer to update the relevant context file so the next session picks it up

---

## Workspace Structure

```
.
├── CLAUDE.md              # This file — always loaded
├── context/
│   ├── firm.md            # Who we are, what we do, house style
│   ├── deals.md           # Active mandates and deal status
│   └── strategy.md        # Current priorities and approach
└── gtd/
    ├── dashboard.md       # Live task state — load every session
    ├── projects.md        # Active projects with detail
    ├── next-actions.md    # Immediate next steps
    └── waiting-for.md     # Items pending others
```

---

## Session Workflow

1. **Start**: Claude reads context and GTD, confirms readiness
2. **Work**: Direct Claude with tasks — it already knows your business
3. **Capture**: Tell Claude what happened (calls, decisions, new deals) — it updates context
4. **Review**: Periodically review GTD with Claude to keep it current

---

## Maintaining This Workspace

After any session with meaningful updates, ask Claude to update the relevant files:
- New deal or status change → update `context/deals.md`
- New task or project → update `gtd/`
- Strategic shift → update `context/strategy.md`

The value of this workspace compounds over time. The more current it is, the more useful Claude becomes.
