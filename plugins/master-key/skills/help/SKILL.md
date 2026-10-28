---
name: help
description: Explain how the owner's AI system works and walk them through doing something in it, one step at a time. Use when the owner asks "how does this work," "where does this go," "how do I connect...," "how do I make a skill," "what can you do," "something's broken," "I'm stuck," "what's the setup status," or wants to finish or resume setup. First stop for any question about the system itself, before the owner contacts support.
---

# Help

The system should teach itself. When the owner is stuck, explain it plainly,
then walk them through one step at a time, waiting for them to finish each
step before giving the next.

## How the system is built (explain only as deep as needed)

Always open the AI at the main folder (the OS root).

1. **`AGENTS.md`** is the rulebook the AI reads first: who the owner is, the
   business, the apps they use, how they want things done, how the system
   learns.
   `CLAUDE.md` just points to it.
2. **`context/`** is everything the AI knows about the business: about the
   owner, the business and crew, what we're fixing first (`constraint.md`),
   services and prices, customers, working style and tools, voice, brand,
   and, if their kit came with a trade pack, their trade's rules
   (`trade.md`).
3. **`jobs/`** holds notes and files for each job or customer.
4. **`active/`** is for one-off projects. **`personal/`** is personal stuff,
   never mixed with business. **`inbox/`** is where the owner drops files for
   the AI.
5. **`MEMORY.md`** holds a few approved general rules.
6. **Skills** (from the Master Key plugin, plus any the owner made in
   `skills/`) hold the step-by-step processes: `morning-brief`,
   `inbox-triage`, `follow-up-list`, `skill-builder`, `thats-changed`,
   `weekly-review`, `context-refresh`, `add-company`, and this one. Typing `/`
   in most AI tools lists them by name.

## Tips to share when they fit
- **New task, new session.** Long sessions get slow and forgetful. Start fresh
  for each new piece of work. The files carry everything over.
- **Talk, don't type.** Dictation (Wispr Flow or the phone's mic button)
  works great.
- **Tell it what you want done, not how.** "Get me a follow-up list for this
  week's quotes" beats a long prompt. It'll ask if it needs something.

## Common questions → what to do
- "Where does this go?" → use "Where it goes" in `AGENTS.md` (under
  "How you learn"), then offer to run `thats-changed`.
- "Make this a skill" → `skill-builder`.
- "Clean up / improve the system" → `weekly-review`.
- "Things have changed a lot" → `context-refresh`.
- "I run a second company" → `add-company`.
- "Connect [app]" → first see if it's already in "Connected apps" in
  `context/working-style.md`. If not, walk the owner through hooking it up.
  Look for it in the AI tool's own connector list. If it isn't there, try
  Composio. If Composio doesn't have it, see whether the app offers its own
  MCP server and add that as a custom connector by its URL. If nothing else
  works, use the browser. Start it on "needs approval," then check it and log
  it: look up one real thing without changing anything, and add a row to
  "Connected apps."
- "Setup status" or "continue setup" → read the status line at the top of
  `AGENTS.md`, pick up from the step it names, and follow the
  `setup-master-key` skill.

## When you can't fix it
Walk this ladder, in order, and tell the owner which step they're on:
1. **Try it here first:** ask for a screenshot of the error and work through
   it together.
2. **Support videos:** coming soon (the Master Key team will send links)
3. **Help bot and community:** tap "I'm stuck here" on the step in your Master Key guide
4. **A person:** the Master Key team (see the stuck card in your Master Key guide). Before they reach out, write a short
   summary of the problem, what was tried, and any error text, so they can
   paste it in.

## Rules
- One step at a time for anything technical. Say what the owner should see on
  screen when the step worked.
- Plain words. If a technical word is needed, explain it in one line.
- Never enter passwords, account numbers, or payment details for the owner.
  Tell them where to type it themselves.
