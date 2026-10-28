---
name: morning-brief
description: The owner's one-screen morning brief - today's jobs and appointments, new leads and missed calls, who's waiting on a reply, open quotes, what's due, where the money stands, and the top three things to get done. Use when the owner says "morning brief," "what's on today," "catch me up," "where do things stand," or when the scheduled morning run fires. Read-only - it drafts nothing and sends nothing unless the owner asks after reading it.
---

# Morning Brief

One screen that tells the owner what today has to produce, what's waiting on
them, and what breaks if they do nothing. Readable on a phone in the truck.

## Before you start
- Read `context/constraint.md`. The brief should always show how today
  connects to the thing we're fixing.
- Read "Connected apps" in `context/working-style.md` to see what's
  connected. Pull only from connected tools. If something isn't connected,
  say so in one line and skip it. Never guess.

## What to pull
1. **Today's schedule:** jobs, estimates, site visits, and meetings, with the
   time, customer, address area (not the full address), and who's assigned.
   From the calendar and the job software if connected.
2. **New leads and missed calls** since yesterday (CRM / Digital Rolodex, if
   connected), and how long each has waited for a response.
3. **Waiting on you:** emails and messages from real people that need the
   owner's reply, oldest first.
4. **Open quotes:** estimates sent with no answer yet, oldest first (the
   `follow-up-list` skill has the full list).
5. **Due or overdue:** tasks, permits, inspections, material orders, invoices
   to send.
6. **Money (if connected):** unpaid invoices, payments in since yesterday.

## Output format
```
MORNING BRIEF - [day, date]

TOP 3 TODAY
1. [outcome] - why it matters
2.
3.

SCHEDULE
- [time] [job/estimate] - [customer] - [who]

NEW LEADS / MISSED CALLS
- [name] - [what they want] - waiting [time]

WAITING ON YOU
- [person] - [what they need] - waiting [n] days

OPEN QUOTES
- [customer] - [job] - sent [n] days ago

DUE / OVERDUE
- [item] - [due]

MONEY
- [line]

THE CONSTRAINT
- [one line: how we're doing on the thing we're fixing]

IF YOU DO NOTHING
- [the one thing that breaks]
```

## Rules
- Read-only. No drafts, no sends, no schedule changes unless the owner asks
  after reading.
- One screen. Cut anything that doesn't change what the owner does today.
- Times in the owner's time zone (see `working-style.md`).
- No customer phone numbers or full addresses in the brief.
