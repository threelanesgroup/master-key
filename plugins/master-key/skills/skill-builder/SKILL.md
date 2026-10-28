---
name: skill-builder
description: Turn something the owner has the AI do over and over into a reusable skill (a written step-by-step process the AI follows every time), or fix a skill that gave a wrong result. Use when the owner says "make this a skill," "save this as a process," "do it the same way every time," "build a skill for...," or when the same kind of task has come up two or three times. Not for one-off tasks or for facts about the business (those go in context files via thats-changed).
---

# Skill Builder

A skill is a written process for the AI: when to use it, what to read first,
the steps, the rules, and what good output looks like. It turns "explain it
again every time" into one sentence: "run the estimate follow-up for Smith."

## When a skill is worth building
- The task has come up two or three times, or the owner knows it will.
- Doing it right needs steps, rules, or know-how a fresh chat wouldn't have.
- A wrong result costs real time, money, or a customer.

A single fact or preference isn't a skill. Route it with `thats-changed`.

## Two ways to build one
- **Do it first (most skills):** do the task with the owner once, step by
  step, until the result is right. Then the owner says "make this a skill"
  and you package everything you learned, including their corrections and
  the final result as an example.
- **From a document:** the owner hands over a price sheet, checklist, or how
  they train a new hire, and says "build a skill from this."

If your tool has a built-in skill creator, use it for the file format. This
skill adds the owner's rules on top.

## Steps
1. **Find the real example.** Use the task you just did together, or ask for
   the last time the owner did it.
2. **Ask three to six short questions,** only what you can't figure out:
   - What words will the owner use when they want this?
   - What does the finished result look like? Who gets it?
   - What should it read first (context files, a job folder)?
   - What are the rules, mistakes to avoid, and what needs the owner's OK?
   - What tools does it touch, and what's it allowed to do in them?
3. **Check for overlap.** Read the names and descriptions of the skills you have
   (the Master Key plugin's skills and any in `skills/` in the Master Key folder). Improve an existing skill instead of making a near-copy.
4. **Write it** at `skills/<name>/SKILL.md` in the Master Key folder, then offer to
   also save it as one of the owner's Claude skills so it loads everywhere:
   - Name: lowercase with dashes (`estimate-follow-up`).
   - The `description` line says what it does, the exact phrases that should
     trigger it, and what it's NOT for. This line decides whether the skill
     gets used, so make it specific.
   - Body, in order: what it's for (two lines), what to read first, the
     steps, the rules, what good output looks like, one short example.
   - Long reference material (price tables, checklists) goes in a
     `references/` file next to it.
5. **Show the owner** in plain words: when it runs, what it does, what it
   won't do. Adjust.
6. **Test it on a real case.** Compare the result to what the owner would
   have done. Fix the skill, not just the output.

## Fixing a skill that missed
The first version is never the final one. Good skills get there through
small fixes after real use.
1. Ask what was wrong, or compare the result to what the owner wanted.
2. Find the line in the skill that caused it, or the missing line.
3. Propose the exact change. After the owner says OK, make it and re-run.

## Chaining skills
When a bigger job is really several skills in a row (site-visit notes →
estimate → follow-up), build one skill whose steps say "run skill A, then
skill B." Keep each one working on its own too.

## Rules
- Never put passwords or account numbers in a skill.
- A skill never sends, posts, spends, books, or deletes without the owner's
  OK, even if the steps say to.
- Prices, crew, and links that change belong in context files. The skill
  says where to read them; it doesn't copy them.
