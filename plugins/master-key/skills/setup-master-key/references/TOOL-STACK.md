# Tool Stack

Out of the box, your AI only knows what you type or paste into the chat.
Connectors let it look things up in the apps you already use: your inbox,
your calendar, your jobs, your unpaid invoices. Then it works from the real
thing instead of asking you.

You don't need all of these. Connect the critical ones first, then add others
only when you use that app for real work.

**Key:**
- ★ **Critical.** Connect these first.
- ● **Worth it** once you're using that app.
- ○ **Optional.** Only if your business needs it.

(App availability checked October 2026. Things change; ask your AI to check
before you connect.)

## The basics (not connectors, but you need them)

| Tool | | Why you'd want it |
|---|---|---|
| Claude desktop app, Code tab | ★ | It's the workspace that reads and writes the files in your `Master Key` folder. |
| Dictation (Wispr Flow or your keyboard's mic) | ★ | Talk instead of type, from the truck or the job site. |
| Scheduled tasks (built into Claude) | ● | Runs your morning brief or inbox triage on a timer without you asking. |

## Critical connectors

| Connector | How to connect | Why you'd want it |
|---|---|---|
| ★ **Email** (Gmail or Google Workspace) | Claude's connector list | Reads threads, finds who's waiting on you, drafts replies in your voice for you to send. |
| ★ **Calendar** (Google Calendar) | Claude's connector list | Knows your day, preps you for estimates and site visits, finds open time. |
| ★ **CRM, phones, and texting** (Digital Rolodex) | GoHighLevel connector, set up with your install team | Sees new leads, missed calls, and your pipeline, so the morning brief and follow-up list are complete. |
| ★ **Job software** (Jobber, ServiceTitan, Workiz, ServiceM8) | Through Composio | Pulls today's jobs, open estimates, and unscheduled work into your brief and follow-ups. |
| ★ **Accounting** (QuickBooks) | Through Composio | Unpaid invoices and cash, read-only, so you know where the money is. |

**Outlook instead of Gmail?** Outlook connects through Composio. Mention it to
your install team so setup matches.

**Housecall Pro?** As of October 2026 there isn't a direct connector. Your AI
can work in it through your browser (see "Browser" below), or you can drop an
export of open estimates into `inbox/`.

## Worth it

| Connector | Why you'd want it |
|---|---|
| ● **Composio** (composio.dev) | A go-between for apps that don't have their own connector in Claude, like Jobber or QuickBooks. You sign in to each app there one time. Several of the apps above come in this way. |
| ● **Google Drive** | Reads your files, photos, and price sheets where they already live. |
| ● **Payments** (Square or Stripe) | Payment and invoice status, read-only. |
| ● **Google Business Profile and reviews** | Managed in Digital Rolodex; paste or forward a review and your AI drafts the reply for you to post. |
| ● **Facebook and Instagram** | If they're connected in your Digital Rolodex, your AI can see what's posted and how it did, and draft the next post. |
| ● **Canva** | Turns "make me a door hanger for spring tune-ups" into a design from your templates. |
| ● **Browser** (Claude in Chrome) | Lets your AI work in websites with no connector, like supplier portals or Housecall Pro, using your logged-in browser. |

## Optional

| Connector | Why you'd want it |
|---|---|
| ○ **Firecrawl** | Pulls the text off any web page so your AI can read it properly, like a competitor's price page or a supplier's spec sheet. |
| ○ **Apify** | Builds lists from Google Maps, Facebook, and other sites, like every builder within 30 miles. |
| ○ **Zoom or Fireflies** | If you take sales or builder meetings on Zoom, the AI can read the notes and draft the follow-up. |
| ○ **Higgsfield** | Makes AI images and video for ads and posts. It runs on paid credits, so your AI tells you the cost before it starts. |

## How to add a connector in Claude

1. In the Claude desktop app, open the connectors page (Customize →
   Connectors, then Browse). Find the app, click it, sign in.
2. If the app isn't listed, check Composio, or ask your AI to walk you
   through adding it.
3. Set each connector to **"needs approval"** to start. Loosen it only after
   you trust it.
4. Then say **"check it and log it."** Your AI looks up one real thing
   without changing anything (like tomorrow's schedule) and adds the app to
   your working-style file. If the check fails, it isn't connected, no matter
   what the settings page says.

## Rules worth keeping

1. **Finish one app before starting another.** Don't hook up the next until
   the last one is checked and logged.
2. **Reading is fine. Drafting is fine.** Sending, posting, booking, changing,
   deleting, or spending needs your OK every time.
3. **Use the app's own connector** when there is one; it usually has better
   access than going through a hub.
4. **Check them once a month.** Logins expire, especially Facebook and
   Instagram. Say "test all my connections."
5. **Anything that costs credits** shows you the cost and waits for your OK.
6. **Never paste passwords or account numbers into the chat.** You type them
   into the app yourself.
