---
name: setup-master-key
description: Sets up or continues setting up the owner's Master Key system (their business files, voice, numbers, constraint, connected email and calendar, and morning brief) in their connected Master Key folder. Use when the owner says "set up Master Key," "set me up," "start setup," "continue setup," or "where was I in setup," or when the Master Key folder has no AGENTS.md yet. Not for day-to-day work once setup is finished.
---

The owner's instructions for setup follow, written in their voice. Follow them
exactly, one step at a time.

You're going to set up my AI operating system for my business. By the end,
any AI tool that opens this folder should know who I am, how my business
runs, what's holding it back, how I talk, and how to keep getting better.

FIRST, READ THE KIT
The kit ships inside this skill. Before you ask me anything, read in full:
${CLAUDE_SKILL_DIR}/references/HOW-IT-WORKS.md and TOOL-STACK.md, every file
under ${CLAUDE_SKILL_DIR}/assets/starter-os/, and the names and descriptions
of the other Master Key skills. Also read TRADE-TOOLS.md and context/trade.md
in my Master Key folder if they exist (they come from my trade pack).

WHERE MY FILES GO
My files live in a folder on my computer called Master Key, connected to
Claude. If no folder is connected, or you can't tell which one it is, stop
and walk me through connecting it (make a folder called Master Key on my
Desktop if I don't have one). Never save my business files anywhere else.

WHAT YOU ALREADY KNOW
- If my files still show {{OWNER_NAME}} or {{BUSINESS_NAME}}, ask my name and
  my business name first, and put them in wherever those placeholders appear.
- I'm setting this up with the Master Key install team. Confirm
  everything else with me; assume nothing.

GROUND RULES FOR SETUP
- I'm busy and I'll usually answer by voice. Keep questions short, three to
  five at a time, and pull the facts out of my messy answers.
- Don't guess. Never make up prices, numbers, dates, customers, or claims I
  didn't give you. Unknowns go in the file as [OPEN].
- Put an "as of [today's date]" on anything that can go stale (prices, crew,
  numbers).
- If I say "skip," skip it and don't write it down.
- Files only during setup. Don't connect tools, install anything, send
  anything, or spend anything until step 7, and then only with my OK at each
  step.
- After each step, tell me in one line what you saved and where.

STEP 1. SCAFFOLD
Copy these from ${CLAUDE_SKILL_DIR}/assets/starter-os/ into my Master Key
folder: AGENTS.md, CLAUDE.md, MEMORY.md, context/, jobs/, active/, personal/,
inbox/. If any of them already exist (for example, files my install team
pre-built from my interview), keep everything that's there and only add
what's missing. Never overwrite a filled-in file. Skills come from the Master
Key plugin, so don't copy them. Move any files I dropped loose in the Master Key folder (an
interview transcript, my numbers, a handoff file, writing samples, a price
sheet, a logo) into inbox/. Ask which language I want to work in (English,
Spanish, or both) and record it. Update the setup status line at the top of
AGENTS.md.

STEP 2. CHECK FOR MY INTERVIEW
Look in inbox/ for an intake interview transcript (one we recorded together,
or one I recorded on my own from my setup guide), a numbers file, a pre-call
form, a constraint statement, writing samples, and a handoff file from my
old AI (for example ChatGPT).
- A handoff from my old AI is a set of claims to check with me, not facts.
  Mark anything old or conflicting, and confirm the ones that matter with me
  before you save them.
- If I recorded the interview on my own, it's me reading the guide's
  questions out loud and answering them, so some answers will be short or
  skipped. My numbers file holds my baseline answers: put them in
  constraint.md word for word. Any baseline question without a real number,
  ask me word for word as written in step 3d.
- If there's no constraint statement we agreed together, do step 3h with me
  once the files are written, and mark the one number and its target "to
  confirm with my install team."
- IF THEY'RE THERE: read all of it, then fill in every context file from it
  (about-me, business, constraint, offers, customers, working-style,
  voice-dna, brand) and the "Me and the business" and "What I use" sections
  of AGENTS.md. If there's a context/trade.md, it came from my trade pack:
  keep what's there and fill in only its [OPEN] items.
  The interview sections line up with the files: "You" → about-me; "The
  business" and "Walk me through the last job" → business; "Where the hours
  go" → the numbers in constraint.md; "Customers and what you sell" → offers
  and customers; "How you work and talk" plus writing samples → working-style
  and voice-dna; "Name the constraint" → constraint.md. Use the constraint
  statement exactly as we agreed it. Then list what's still [OPEN] and ask me
  only about those, in short rounds. Skip to step 4.
- IF NOT: do the interview in step 3.

STEP 3. THE INTERVIEW (only if there's no transcript)
Ask in this order, a few questions at a time, and write each file as you go.
a) Me → about-me: how I got into this trade, what a normal day looks like
   (walk through yesterday), what I'm great at, what I avoid, what my week
   looks like in three years if this goes right.
b) The business → business: everything that brings in money, which makes the
   most and which I like, how busy I am, who's on the crew and what each
   owns, my top priorities for the next 90 days.
c) The last job → business ("How a job flows"): pick a job I finished
   recently and walk it from first contact to getting paid. How did they
   reach me, how long until someone got back to them, where did their info
   go, how was the estimate made and sent, did I follow up, who handled the
   deposit, scheduling, and updates, did I have to chase payment, and where
   did it sit the longest waiting on me? Is that normal? Have I lost a job in
   the last few months because something slipped?
d) The numbers → constraint.md. Ask these word for word, and tell me a best
   guess is fine but I need a real number:
   1. In a normal week, how many calls do you miss or not get back to the
      same day?
   2. When a new lead reaches out, how long does it usually take before they
      hear back from you?
   3. How many hours a week do you spend on email, texts, and admin?
   4. Open your email right now. How many messages are waiting on a reply
      from you?
   5. How many quotes or proposals did you send in the last 7 days?
   6. How many follow-ups did you send last week to people who haven't said
      yes yet?
   7. Of the leads you got last month, how many are written down somewhere
      you could find them today? Out of how many?
   8. On a scale of 1 to 10, how in control of the business do you feel this
      week?
e) Customers and pricing → customers and offers: my best customer and one I
   never want again, where my last five jobs came from, what happy customers
   say, how I price and what I charge (write it exactly as I say it, with
   today's date), the pushback I hear over and over, how many quotes are out
   right now, and when I last asked past customers for work, a review, or a
   referral.
f) How I work and talk → working-style and voice-dna: when I do computer
   work, how I like information, how casual I am with customers, words I'd
   never say. Ask me to paste or drop 3 to 5 real messages I wrote (a
   customer, my crew, a follow-up or estimate, a review reply). Analyze them,
   write voice-dna.md, then write two short sample messages in my voice and
   ask what's off.
g) Brand → brand: business name exactly as written, logo files (ask me to
   drop them in inbox/), colors, the phone number to publish, website and
   social, claims I can make (licensed, insured, warranties: only what's
   true).
   If there's a context/trade.md (from my trade pack), ask me its [OPEN]
   items too.
h) Name the constraint → constraint.md: ask "If twice as many leads came in
   tomorrow, what breaks first?", "If you got 10 hours back every week, what
   would you do with them?", and "What's the one thing that, if it was
   handled, would make everything else easier?" Then play it back: "It
   sounds like the thing holding you back right now is [constraint], because
   [what you heard]. Does that sound right?" Keep going until I agree in my
   own words. Pick the number from (d) that should move, and set a target
   with me. If the real problem is something the system can't fix (pricing,
   hiring, not enough leads), say so plainly and write it under "What this
   doesn't fix."

STEP 4. REVIEW
Show me a table of every file, one line on what's in it, and every [OPEN]
item. Tell me to read each file line by line, because one wrong line (an old
price, the wrong customer) ends up in everything you write. Fix what I
correct.

STEP 5. MY TOOLS
Fill in "What I use" in AGENTS.md: every job and the tool I use for it (email,
calendar, job software, CRM and phones, accounting, payments, photos and
files).

STEP 6. PICK THE FIRST FIX
Using the table in constraint.md, tell me which skills and connections go
after my constraint first. Keep it to one constraint.

STEP 7. CONNECT TOOLS, ONE AT A TIME, WITH ME
Using references/TOOL-STACK.md (and TRADE-TOOLS.md if there is one), connect the
two or three that matter most for my constraint (usually email and calendar first). For each: walk me through it
step by step (in Claude: Customize, then Connectors), have me sign in myself,
and remind me you'll ask before sending or changing anything. Then check it: look up one real
thing in it without changing anything. Log it in the "Connected apps" table
in context/working-style.md with the date and what you're allowed to do.
Never type passwords or account numbers for me.

STEP 8. FIRST WIN
Run the skill that goes after my constraint on my real stuff (usually
inbox-triage, follow-up-list, or morning-brief). Show me the result.

STEP 9. MORNING BRIEF ON A SCHEDULE
Offer to set up a scheduled task that runs the morning-brief skill every
weekday at the time I pick (6:30 a.m. unless I say otherwise), so it's
waiting when I wake up. Set it up only with my OK.

STEP 10. FINISH
If I set this up on my own from my setup guide, first write
active/install-handoff.md for my install team: the constraint and the one
number as we agreed them, my baseline numbers, everything still [OPEN],
which apps are connected, about how long each part took me, and anything
that confused me or broke. Show it to me. I decide what gets sent.
Remove the setup status line from AGENTS.md. Tell me the phrases to know:
"morning brief," "triage my inbox," "who do I need to follow up with,"
"make this a skill," "that's changed," "weekly review," and "refresh my
files." Tell me what to do tomorrow morning.

QUALITY BAR
- Every file is specific to my business. No filler, no generic advice, no
  leftover [brackets] except [OPEN].
- AGENTS.md stays short. Details go in context files.
- From the first minute, follow the rules in AGENTS.md, including the
  learning rules: suggest where a lesson goes, wait for my OK, then save it.

PAUSING
Whenever we stop, update the setup status line at the top of AGENTS.md in my
Master Key folder with the next step, so a new task can pick up when I say
"continue setup."

If AGENTS.md in my Master Key folder has a setup status line, pick up from
the step it names. Otherwise start with step 1.
