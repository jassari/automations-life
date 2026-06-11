# PRD — automations.life Landing Page
**Version:** 1.0  
**Date:** 2026-06-10  
**Status:** Active

---

## 1. Objective

Generate qualified leads from Latin American businesses looking to automate their critical processes using conversational AI agents. The primary conversion goal is for visitors to click "Talk to an advisor" and reach out via WhatsApp.

---

## 2. Target Audience

- **Profile:** Owners or managers of SMBs in Latin America
- **Primary sectors:** Healthcare (clinics, diagnostic imaging centers), B2C/B2B sales, businesses with overdue receivables
- **Languages:** Spanish (primary), English (secondary)

---

## 3. Page Structure

The page is a **single-page** with anchor-based navigation. Sections in order:

| # | Section | ID | Description |
|---|---------|-----|-------------|
| 1 | Nav | — | Logo, nav links, language toggle, CTA |
| 2 | Hero | — | Headline, subtitle, primary CTA button, stats |
| 3 | How to start | `#como-funciona` | 3 steps to get started |
| 4 | Agents | `#soluciones` | 3 solution cards |
| 5 | Pricing | `#precios` | Base price and advisor CTA |
| 6 | Contact | `#contacto` | Final conversion CTA |
| 7 | Footer | — | Logo, legal links, copyright |

---

## 4. Navigation

| Button | Destination |
|--------|-------------|
| Home | Top of page (`#`) |
| How to start | `#como-funciona` |
| Agents | `#soluciones` |
| Pricing | `#precios` |
| Talk to an advisor | WhatsApp `https://wa.me/573204701302` |

---

## 5. Content by Section

### 5.1 Hero
- **Headline:** "Never miss an appointment, a sale or a payment."
- **Subtitle:** "We automate with AI to reduce your costs and increase your revenue."
- **CTA:** "Talk to an advisor" → WhatsApp
- **Stats:**
  - +40% more appointments booked
  - 3x more sales follow-up
  - -60% in overdue receivables

### 5.2 How to Start
- **Tag:** How to start
- **Title:** Get started in 3 steps
- **Subtitle:** "No months of implementation. No technical teams. Your agent running in days."
- **Steps:**
  1. You tell us your process — 30-min call
  2. We configure your agent — tone, schedules, scripts
  3. Your agent starts working — 24/7

### 5.3 Agents
- **Tag:** Our solutions
- **Title:** An agent for every critical process
- **Cards:**
  1. **Scheduling Agent** — Medical offices · Diagnostic imaging centers
  2. **AI Sales Executive** — Any business with a sales process
  3. **Collections Agent** — Businesses with overdue receivables

### 5.4 Pricing
- **Tag:** Pricing
- **Title:** Starting at 150 USD
- **Subtitle:** "Talk to an advisor and we'll build a plan for your operation."

### 5.5 Contact CTA
- **Tag:** Get started today
- **Title:** "How much is your business losing today?"
- **Subtitle:** "Every missed appointment, every unanswered lead, and every unmanaged collection is money walking out the door. Let's talk."
- **CTA:** "Talk to an advisor" → WhatsApp

### 5.6 Footer
- Links: Privacy · Terms of use · Contact
- Copyright: © 2026 automations.life

---

## 6. Features

| Feature | Status |
|---------|--------|
| ES / EN language toggle | ✅ Implemented |
| Anchor-based navigation (smooth scroll) | ✅ Implemented |
| Fixed nav with blur | ✅ Implemented |
| SVG favicon | ✅ Implemented |
| Bilingual meta description | ✅ Implemented |
| Bilingual page title | ✅ Implemented |
| Responsive design (mobile first) | ✅ Implemented |
| Testimonials / social proof | ❌ Pending |
| FAQ section | ❌ Pending |
| Detailed pricing plans | ❌ Pending |

---

## 7. Technical

- **Stack:** Vanilla HTML + CSS + JS (no external dependencies)
- **Main file:** `index.html`
- **Favicon:** `favicon.svg`
- **Font:** Segoe UI / system-ui
- **Primary colors:**
  - Background: `#080C14`
  - Accent: `#00D4FF`
  - Text: `#F0F4FF`

---

## 8. Identified Backlog

1. **Social proof** — Add testimonials or client logos
2. **FAQ** — Frequently asked questions to reduce friction
3. **Detailed pricing** — Expand section with what each plan includes
4. **Legal pages** — Privacy policy and Terms of use
5. **Analytics** — Integrate Google Analytics or equivalent

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2026-06-10 | Initial version — full landing page structure |
