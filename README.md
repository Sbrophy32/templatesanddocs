# SB Creative Studio — Website Blueprint

## What This Is

The Website Blueprint is a $497 paid offer from SB Creative Studio. It's a premium client-facing audit report covering six areas of a business's website — design, conversion, local SEO, AI visibility, content, and competitive landscape — delivered as a designed PDF with a 1:1 walkthrough call included.

This repo contains everything needed to produce and deliver a Website Blueprint for any client.

---

## File Map

### Core Production Files (use these every time)

| File | What It Is | Where to Use It |
|------|-----------|-----------------|
| `SB_Website_Blueprint_Claude_Prompt.md` | Step-by-step internal workflow for producing each Blueprint — intake checklist, Claude analysis prompt, review checklist, delivery email, and walkthrough call structure | Open this at the start of every new client Blueprint |
| `SB_Website_Blueprint_Template.html` | The master blank report template with all placeholders intact | Reference for Claude Design or any design tool to produce the PDF |
| `Website_Blueprint_Claude_Design_System.md` | Design system brief for Claude Design — colors, fonts, components, and page structure | Upload to Claude Design when building or updating the PDF template |
| `Website_Blueprint_Design_Brief.md` | Page-by-page content brief describing what goes on each of the 14 pages | Use as a reference when briefing a designer or Claude Design |

### Brand Files

| File | What It Is |
|------|-----------|
| `SB_Creative_Studio_Brand_Kit_2026__1_.html` | Full brand reference — colors, fonts, logo usage, SVG icons |
| `SB_Main_Logo.png` | Primary logo |
| `Horizontal_Logo.png` | Horizontal logo variant |
| `Stacked_Logo_2.png` | Stacked logo variant |

### Reference / Example Files

| File | What It Is |
|------|-----------|
| `J5_Plumbing_Website_Blueprint_V2.html` | Completed example Blueprint for J5 Plumbing Co. (Benbrook TX) — practice run, July 2026 |

### Other Business Documents (in project, not Blueprint-specific)

| File | What It Is |
|------|-----------|
| `SB_Website_Blueprint_Template.html` | Master blank Blueprint template |
| `How_I_Work_With_Claude_v7.md` | Working style guide for Claude sessions |
| `Client_Project_Starter_Template__2_.md` | Template for setting up new client Claude Projects |
| `SB_Creative_Studio_Core_Values__3_.md` | Studio core values document |
| `SB_Creative_Studio_Onboarding_Discovery_Guide__1_.md` | Client onboarding and discovery process guide |
| `SB_Creative_Studio_Tracker.xlsx` | Master business tracker (11 tabs) |
| `SB_Creative_Studio_Process_Map.xlsx` | Internal process map |
| `SB_Website_Reference_Guide.html` | Website component reference |
| `SB_Homepage_Mockup.html` | SB Creative Studio homepage mockup |
| `daily-time-log__2_.html` | Daily time tracking tool |

---

## The Workflow (How to Produce a Blueprint)

**Step 1 — Client submits intake form**
They fill out name, business name, URL, phone, email, and notes about their site.

**Step 2 — Open `SB_Website_Blueprint_Claude_Prompt.md`**
This is your production guide. Follow Steps 1–5 in order.

**Step 3 — Run Step 1 research (15–30 min)**
- View site on desktop and mobile
- Run PageSpeed Insights
- Pull sitemap
- Run keyword visibility check (Ubersuggest or GSC)
- Search competitors
- Check GBP map pack status

**Step 4 — Paste the Claude analysis prompt**
Copy the prompt from the production guide into a Claude Project chat. Feed in your Step 1 observations. Get structured findings back.

**Step 5 — Fill in the template**
Take Claude's output and fill in the Blueprint template through Claude Design or your design tool of choice.

**Step 6 — Review pass (15 min)**
Check the review checklist in the production guide before sending.

**Step 7 — Deliver**
Export as PDF. Send with the delivery email template from the production guide. Schedule the walkthrough call.

**Target time:** Under 2 hours total.

---

## Pricing

| Offer | Price | What's Included |
|-------|-------|----------------|
| Website Blueprint | $497 | 14-page audit report, PageSpeed report, sitemap export, keyword snapshot, 1:1 walkthrough call |
| Free Website Review | Free | Verbal audit on a discovery call — leads into the $497 offer |

---

## File Hygiene Notes

- **This repo is private.** Client names and audit findings should never be in a public repo.
- The master template always lives at `SB_Website_Blueprint_Template.html` — never rename or version it. Edit in place.
- Client-specific completed Blueprints should be saved as `[ClientName]_Website_Blueprint.html` and kept in a separate `/clients` folder (not committed unless private).
- The Claude Design system file (`Website_Blueprint_Claude_Design_System.md`) is the single source of truth for design decisions. Update it whenever the template design changes.

---

## Still To Build

- [ ] Free lead magnet offer (lighter version of the Blueprint)
- [ ] Cover page tagline (placeholder currently in the template)
- [ ] Finalized PDF template from Claude Design
- [ ] Ads management and landing page pricing

---

*Last updated: July 19, 2026*
*Built in: SB Creative Studio Home Base Claude Project*
