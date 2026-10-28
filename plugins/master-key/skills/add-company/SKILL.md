---
name: add-company
description: Add a second company or side business to the owner's system - create its own folder at the main folder level from the template, interview the owner to fill in its business, services and pricing, customers, and brand, and register it in AGENTS.md. Use when the owner says "I have another company," "add my other business," "set up a folder for [business]," or mentions a business the system doesn't have a folder for yet. Also use to promote a project from active/ into its own company folder.
---

# Add Company

The main business lives in `context/`. Any other company the owner runs gets
its own folder at the top level of the main folder, with the same shape, so
the AI always knows where to look and never mixes the two.

## Steps
1. **Name it.** Confirm the company name and a folder name (lowercase with
   dashes, e.g. `smith-rentals`). Check it isn't already used.
2. **Create the folder.** Copy `assets/company-template/` (next to this file)
   to `<folder-name>/` at the main folder level. If you're promoting a
   project from `active/`, move its files in too. Don't edit the template.
3. **Interview in short rounds** (three to five questions each, voice answers
   welcome). Skip anything already answered, and read any website or file
   the owner points you to first.
   - **Round 1, the business** → `context.md`: what it is, who it's for,
     stage, crew, how it makes money, how a job flows, where work waits,
     90-day priorities.
   - **Round 2, services and pricing** → `offers.md`, with "as of" dates.
   - **Round 3, customers** → `customers.md`.
   - **Round 4, brand** → `brand.md`. Ask for the logo and files in `inbox/`.
4. **Write as you go.** After each round, update the file and say in one line
   what you saved. Unknowns stay as `[OPEN]`. Never invent prices or claims.
5. **Register it:** add a line under "Me and the business" in `AGENTS.md`
   naming the second company and its folder, and add the folder to "Where to
   look."
6. **Review** the four files with the owner and fix anything wrong.

## Rules
- Keep the companies separate. One company's customers, prices, and brand
  never go into the other's work unless the owner asks.
- Skills used only for the second company start with its short name (e.g.
  `rentals-lease-renewal`).
- Pausing or closing a company: mark it in `AGENTS.md` with a date. Keep the
  folder. Never delete files without the owner's OK.
