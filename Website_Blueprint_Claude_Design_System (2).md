# SB Creative Studio — Website Blueprint
## Design System for Claude Design

---

## Project Overview

Create a multi-page PDF document template called the **Website Blueprint**. This is a premium client-facing audit report delivered by SB Creative Studio. It should feel like a high-end consulting deliverable — confident, warm, and easy to read. Letter size (8.5 × 11 inches), portrait orientation, approximately 14 pages.

---

## Brand Tokens

### Colors
```
Charcoal    #2A2621   — dark backgrounds, primary headlines
Sage        #8C9A7C   — eyebrow labels, accent text
Sky Mist    #D6EAEA   — highlight color, callout backgrounds
Deep Teal   #33585A   — callout box left border
Sky Dark    #1E4E50   — text on Sky Mist backgrounds
Pebble      #B0ABA1   — supporting labels, footer text
Slate       #6B6459   — secondary body text
Off White   #F9F8F7   — light section backgrounds
White       #FFFFFF   — page backgrounds
Border      #E8E5E0   — divider lines, card borders
Red Light   #FDF1F1   — fix badge background
Yellow Light #FDF8EE  — improve badge background
Green Light #F1F6F1   — keep badge background
Red         #C97A7A   — fix badge text and dot
Yellow      #C9A63A   — improve badge text and dot
Green       #6A9E6A   — keep badge text and dot
```

### Typography
```
Display     Playfair Display, serif — page titles, section numbers, cover headlines
UI / Labels Archivo, sans-serif — eyebrows, badges, labels, nav text
Body        Work Sans, sans-serif — paragraphs, descriptions, finding details
```

### Type Scale
```
Cover headline      40–44pt  Playfair Display Bold
Page title          20–22pt  Playfair Display Bold
Section number      36–44pt  Playfair Display Bold, Sky Mist color
Eyebrow label       7–8pt    Archivo Bold, Uppercase, 3pt letter spacing, Sage color
Finding title       10pt     Work Sans Semibold
Finding detail      8–9pt    Work Sans Regular, Slate color
Badge text          6.5–7pt  Archivo Bold, Uppercase, 1pt letter spacing
Body paragraph      9.5–10pt Work Sans Regular
Footer text         7pt      Archivo Regular, Pebble color
```

---

## Layout System

### Page Setup
- Size: 8.5 × 11 inches
- Page padding: 0.65in all sides
- Content width: 7.2in
- Footer sits 0.35in from bottom edge

### Two Page Types

**Dark Page** — used for covers only
- Background: Charcoal #2A2621
- All text: White or Sky Mist or Sage
- Used on: Page 1 (Package Cover), Page 2 (Blueprint Cover)

**Light Page** — used for all content
- Background: White #FFFFFF
- Standard header + content + footer layout
- Used on: Pages 3–14

---

## Component Library

### 1. Eyebrow Label
Small uppercase label that appears above every page title.
- Font: Archivo Bold, 7.5pt, uppercase, 3pt letter spacing
- Color: Sage #8C9A7C
- No background, no border
- Example: "BEFORE THE SCORES" / "FIRST IMPRESSION, LAYOUT, CLARITY"

### 2. Page Title
Main heading for each content page.
- Font: Playfair Display Bold, 20–22pt
- Color: Charcoal #2A2621
- Followed immediately by a 1.5pt horizontal rule in Sky Mist #D6EAEA

### 3. Section Number
Large decorative number in top-left of analysis pages.
- Font: Playfair Display Bold, 36–40pt
- Color: Sky Mist #D6EAEA
- Sits to the left of the eyebrow + page title stack
- Used values: 01, 02, 03, 04, 05, 06, 07, 08, A, B

### 4. Score Badge
Colored square badge showing a score out of 10.
- Size: approximately 60×60pt
- Rounded corners
- Three states:
  - Red: background #FDF1F1, border #C97A7A, text #C97A7A
  - Yellow: background #FDF8EE, border #C9A63A, text #C9A63A
  - Green: background #F1F6F1, border #6A9E6A, text #6A9E6A
- Large number (18–20pt Archivo Bold) centered
- "/ 10" in 7pt Pebble below the number
- Sits to the left of a 2–3 sentence section summary

### 5. Finding Row
Repeating row pattern used throughout analysis sections.
Three elements in a horizontal row:
- **Left:** 8pt colored circle dot (Red / Yellow / Green)
- **Center:** Bold finding title (10pt Work Sans Semibold, Charcoal) + detail text below (8.5pt Work Sans, Slate)
- **Right:** Small badge pill

Separated from next row by a 0.5pt Border #E8E5E0 rule.
Typical row height: 0.4–0.5in

### 6. Badge Pill
Small rounded pill used on finding rows.
- Height: ~16pt, width: fits text + 8pt padding each side
- Rounded corners
- Four variants:
  - **Fix / Fix First** — bg #FDF1F1, border #C97A7A, text #C97A7A
  - **Improve** — bg #FDF8EE, border #C9A63A, text #C9A63A
  - **Keep** — bg #F1F6F1, border #6A9E6A, text #6A9E6A
  - **Gap** — same as Fix
  - **Advantage** — same as Keep
  - **Main Deliverable** — bg Charcoal, text Sky Mist
  - **Included** — bg #F2F0EC, border #E0DDD9, text Slate

### 7. Opportunity Callout Box
Signature element. Appears near the bottom of nearly every page.
- Background: Sky Mist #D6EAEA
- Left border: 3pt solid Deep Teal #33585A
- No top/right/bottom border
- Internal padding: 12pt all sides
- Label: Archivo Bold 7.5pt uppercase, Sky Dark #1E4E50, "OPPORTUNITY" or similar
- Body: Work Sans 9pt, Sky Dark #1E4E50
- Typical height: 0.5–0.6in

### 8. Stat Cell
Small data cell used in scorecard and data pages.
- Background: Off White #F9F8F7
- Border: 0.5pt Border #E8E5E0
- Rounded corners
- Large number or value: Archivo Bold, 18–22pt, Charcoal (or Red if negative)
- Small label below: Archivo 7pt, Pebble, uppercase

### 9. Dark Info Box
Full-width dark box used on Priority & Impact page.
- Background: Charcoal #2A2621
- Internal padding: 16pt
- Contains: eyebrow label (Sage), body text (White), and a large number on the right (Sky Mist, 28pt)

### 10. Page Footer
Appears on every content page.
- 0.5pt horizontal rule in Border #E8E5E0, 0.35in from bottom
- Left: "SB Creative Studio · Website Blueprint" in Archivo 7pt Pebble
- Right: Page number in Archivo 7pt Pebble

### 11. Client Info Strip
Dark strip used on cover pages.
- Background: slightly darker than Charcoal — #1E1C19
- Contains 3–4 labeled fields in a horizontal row
- Label: Archivo 7pt uppercase Slate
- Value: Work Sans 9.5pt White Semibold

### 12. Cover Title Block
Used only on dark cover pages.
- Eyebrow: Archivo 8pt Sage uppercase with a short horizontal line before it (—)
- Headline line 1: Playfair Display Bold 32–40pt White
- Headline line 2: Playfair Display Bold Italic 32–40pt Sky Mist
- Headline line 3: Playfair Display Bold 32–40pt White
- Supporting text: Work Sans 10pt Pebble, max width ~5in

### 13. Findings Label
Small section sub-header used above groups of finding rows.
- Font: Archivo Bold 7.5pt, uppercase, 2pt letter spacing
- Color: Deep Teal #33585A
- Example: "FINDINGS" / "ON-PAGE & GBP FINDINGS" / "KEYWORD VISIBILITY"

### 14. Priority Matrix
2×2 grid of quadrant cards used on Priority & Impact page.
- Each card: White background, Border border, rounded corners
- Top border: 2–3pt solid color (Red / Yellow / Green / Pebble)
- Header: Archivo Bold 8pt uppercase, matching color
- Items: Work Sans 8.5pt Charcoal, each preceded by "—", separated by 0.5pt rules

---

## Page Templates

### Template A — Dark Cover
Used for: Page 1, Page 2
- Full Charcoal background
- Top bar: Studio name left, "Confidential / Prepared for [CLIENT NAME]" right
- Cover title block (centered vertically, upper-left anchor)
- Client info strip near bottom
- No standard footer

### Template B — Content Page with Section Number
Used for: Pages 3–14
- White background
- Top-left: Large section number (Sky Mist) + eyebrow + page title + Sky Mist rule
- Content area below
- Standard footer

---

## Placeholder Convention

All client-specific content uses this format:
- `[CLIENT NAME]` — client first/last name
- `[BUSINESS NAME]` — business name
- `[CLIENT URL]` — website URL
- `[DATE]` — date of review
- `[Finding title]` — bold title of a finding row
- `[Detail text]` — supporting detail for a finding
- `[#]` — any numeric value (score, count, etc.)
- `[Opportunity text]` — text inside a callout box

---

## Page List

1. Package Cover Sheet (Dark)
2. Blueprint Cover (Dark)
3. Current Situation (Content)
4. Scorecard — At a Glance (Content)
5. Section 01 — Design & User Experience (Content)
6. Section 02 — Conversion (Content)
7. Section 03 — Local SEO & AI Visibility (Content)
8. Section 04 — Content & Messaging (Content)
9. Section 05 — Technical Health (Content)
10. Section 06 — Competitive Landscape (Content)
11. Supporting Data A — Site Structure (Content)
12. Supporting Data B — Keyword Visibility (Content)
13. Priority & Impact (Content)
14. Next Steps + CTA (Content)
