---
name: context-refresh
description: The every-six-weeks refresh - interview the owner by voice for about 15 minutes, update their context files with what changed (prices, crew, services, priorities, customers), and check progress on the constraint they're fixing, including re-asking the numbers being tracked. Use when the owner says "refresh my files," "six-week refresh," "update everything," "things have changed a lot," or when a scheduled refresh reminder fires. Not for a single fact change (use thats-changed).
---

# Context Refresh

Businesses change faster than files do. Every six weeks or so, the owner
talks for 15 minutes and the files catch up. No support call needed.

## Steps
1. **Read all of `context/`** and note every "as of" date older than about six
   weeks.
2. **Interview in three short rounds** (three to five questions each). The
   owner will usually answer by voice; pull out the facts.
   - **Round 1, the business:** What changed since last time? New services,
     dropped services, price changes? Anyone join or leave the crew? How busy
     are you?
   - **Round 2, customers and work:** Where are leads coming from now? Any
     new kind of customer, or one you're done with? Anything customers keep
     asking or pushing back on?
   - **Round 3, the constraint:** How's [the constraint in
     `context/constraint.md`] going? Ask the tracked numbers exactly as
     they're worded in that file, so before and after compare. Is it fixed,
     better, the same, or worse? If it's handled, what's the next thing
     holding the business back?
3. **Propose the updates** as a short list: file, old line, new line, with
   today's "as of" date. Apply what the owner approves (follow
   `thats-changed` rules).
4. **If the constraint is handled,** update `context/constraint.md`: move the
   old one to "History," write the new constraint statement with the owner,
   and suggest which skill or connection would help with it.
5. **Close** with a three-line summary: what changed, how the constraint is
   doing, and the one thing to focus on for the next six weeks.

## Rules
- Never write down something the owner didn't say.
- Ask the tracked numbers the same way every time, or the comparison is
  worthless.
- Keep it to about 15 minutes. If more changed than that, schedule a second
  sitting instead of rushing.
