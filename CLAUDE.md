# CLAUDE.md — Personal Page for Noor Nafiz

## Your Mission

Build a **single-file `index.html` personal page** for Noor Nafiz — a military officer, UN peacekeeper, and man of deep purpose. This page must feel **handcrafted, human, and memorable**. It should look like a thoughtful designer spent weeks on it, not like an AI churned it out in seconds.

---

## Mandatory Skill: Frontend Design

**Before writing a single line of code**, read and follow the frontend design skill at:

```
/mnt/skills/public/frontend-design/SKILL.md
```

This is non-negotiable. The skill contains specific guidance on typography, color, motion, layout, and what makes a page feel handcrafted vs. AI-generated. Read it first. Then design.

---

## Who Is Noor Nafiz?

**Known facts — use these directly. Do not use placeholder values.**

```
Full Name:        Noor Nafiz Islam
Rank:             Lieutenant Colonel (Lt Col)
                  Promoted to Lt Col in 2025
Decoration:       OSP — Outstanding Service Performance (Bangladesh Army honour)
Current Role:     Commanding Officer, Bangladesh Army
Command Scale:    Commands a high-performance battalion of 850+ soldiers & civilians
Research Affil.:  Military Institute of Science and Technology (MIST), Dhaka
Research Areas:   Artificial Intelligence, Internet of Things, Machine Learning
Google Scholar:   197 citations — https://scholar.google.com/citations?user=oYdUtWwAAAAJ
IEEE:             Verified member (email at ieee.org)
Personality:      Sophisticated, calm under pressure, quietly formidable, worldly

Key Achievements:
  - Promoted to Lt Col in 2025; commands a 850+ person high-performance battalion
  - Built the CMH Plasma Bank App (2020) — used in Combined Military Hospital during COVID-19
  - Published at iiWAS 2021 (Linz, Austria): physical exercise monitoring for athletes
  - Co-authored wearable health monitoring research for quarantined COVID-19 patients
  - OSP decoration — awarded for exceptional performance in military service
  - 197 academic citations as a serving military officer

Photo context:
  He is photographed in what appears to be an African savanna (likely a UN
  peacekeeping deployment) — sunglasses, olive clothing, leaning against a 
  vehicle on a vast open plain. He looks assured, grounded, and like someone
  who has seen the world. Use this as the emotional anchor for the page's tone.

Contact / Links:
  Google Scholar: https://scholar.google.com/citations?user=oYdUtWwAAAAJ
  Email:          [user to fill in]
```
## Design Philosophy

### Tone
**Dignified. Understated. Human.**
This is not a startup landing page. Not a dev portfolio. Not a resume site.
Think: a documentary film about a person who has seen real things and done real work.
The page should feel like *him* — grounded, principled, quietly compelling.

### Aesthetic Direction
- **Color palette**: Deep, rich tones — think midnight navy, olive green, warm stone, or dark slate. One sharp accent color (gold, rust, or forest green). NOT purple gradients. NOT pastels. NOT neon.
- **Typography**: Use Google Fonts. Choose something with real character — a strong serif for headings (e.g. `Playfair Display`, `Cormorant Garamond`, `Libre Baskerville`), paired with a humanist sans for body (e.g. `Source Sans 3`, `Lato`, `Nunito`). NEVER use Inter, Roboto, or Arial.
- **Layout**: Asymmetric, editorial. One full-bleed hero section. Content should breathe — generous whitespace, not crammed. A strong visual hierarchy.
- **Background**: Not solid white or solid black. Use a subtle texture (SVG noise pattern or CSS grain overlay), layered gradients, or a muted photographic vibe (CSS-only, no images required).
- **Animations**: Slow, confident reveals on scroll. Nothing bouncy or playful. Think a flag being raised, not a notification popping up.

### What It Must NOT Look Like
- A generic Bootstrap template
- A Wix or WordPress site from 2018
- Any page with a purple-blue gradient hero
- Anything with a "👋 Hi, I'm [Name]" opener
- Cookie-cutter card grids
- Emoji in headings

---

## Page Structure

Build these sections in one `index.html` file:

### 1. Hero Section
- Full viewport height
- His name in a large, commanding serif font
- His title/role beneath it — understated, in small caps or light weight
- A one-line ethos or motto (can be a quote from him, or something like: *"In service of peace."*)
- Subtle background texture or gradient — dark and atmospheric
- Smooth fade-in animation on load

### 2. About / The Man
- 2–3 paragraphs of bio
- Written in **first person or close third** — warm, human, not a Wikipedia stub
- Pull out one key phrase or sentence as a large blockquote — give it visual emphasis
- No bullet points here — pure prose

### 3. Service & Missions
- A clean timeline or card layout showing key postings/missions
- Include years, locations, roles
- Keep it visual but not flashy — dignified like a service record

### 4. Recognition / Awards (if applicable)
- Simple list or minimal card layout
- Let the names of awards speak for themselves

### 5. Beyond the Uniform (optional but powerful)
- A short human moment — his interests, what he values outside of service
- This section makes him feel real, not institutional
- Keep it brief: 2–4 sentences max

### 6. Contact / Connect
- Minimal footer-style section
- Email link (if provided), LinkedIn button, nothing else
- His name again in large type — bookending the page

---

## Technical Requirements

- **Single file**: Everything in one `index.html` — CSS in `<style>`, JS in `<script>`, no external files except Google Fonts CDN
- **Mobile responsive**: Must look great on phone — this is non-negotiable
- **No frameworks**: Pure HTML, CSS, JS only — no Bootstrap, no Tailwind, no React
- **No placeholder images**: Use CSS-only visuals — gradients, geometric shapes, SVG patterns, typography as art
- **Fast loading**: No heavy libraries. Google Fonts only external dependency
- **Accessible**: Semantic HTML (`<main>`, `<section>`, `<nav>`), good contrast ratios, meaningful alt text if any images used

---

## Voice & Copywriting Guidelines

- Write bio and section text **as if you deeply respect this person** — because you should
- Avoid corporate-speak: *"results-driven leader with a passion for excellence"* → ❌
- Prefer direct, honest language: *"He has spent 18 years doing the work most people only read about"* → ✅
- Military service deserves gravity — acknowledge the weight of it without being melodramatic
- UN peacekeeping context: mention the complexity, the stakes, the human dimension
- Don't over-abbreviate — spell things out with dignity

---

## Final Check Before Delivering

Ask yourself:
- [ ] Does this look like it was made specifically for this person?
- [ ] Would someone reading it feel they understand who Noor Nafiz is?
- [ ] Is there a single element — a font choice, a color, a line of copy — that is truly memorable?
- [ ] Does it work on mobile?
- [ ] Does it look NOTHING like a default AI page?

If all five are yes — it's ready.

---

*Built with care for a man who has served with care.*
