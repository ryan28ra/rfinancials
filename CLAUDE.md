# R Financials — Website Project

This repo is the production website for **R Financials**, a boutique institutional
finance and strategic advisory practice founded by Ryan (former Nomura M&A banker,
Consumer & Retail, New York). Read this file at the start of every session.

## The single most important thing
R Financials is positioned as an **embedded, long-term analytical resource** — "your
finance team, extended" — NOT a one-off project consultant. Every page should
reinforce ongoing / retainer relationships over one-time gigs. The business objective
is recurring clients.

## Who it speaks to
1. **Investment firms** — family offices, private equity, independent sponsors, search
   funds, VC, holding companies, boutique investment banks, corporate development.
2. **Operating companies** — founder-led and growth-stage businesses (~$20M–$500M+
   revenue), preparing to raise, evaluating M&A, or needing senior finance capacity.

## Brand system (match exactly — the homepage design already uses these)
Colours:
- Navy (primary dark):        #0B1E3D
- Navy deep (bands/footer bg): #081730
- Ink (serif text):           #14161A
- Gold (accent, hairlines):   #B4915A
- Gold light (highlights):    #C9A96A
- Forest green (rare accent): #2E4A34
- Paper (warm off-white bg):  #FBFAF7
- Paper 2:                    #F4F1EA
- Slate (secondary text):     #5B6470
- Hairline / border:          #E4DFD4

Type (Google Fonts):
- **Cinzel** — the logo wordmark + small letterspaced ALL-CAPS labels/eyebrows. Use sparingly.
- **Cormorant Garamond** — large editorial display headlines (h1/h2).
- **Inter** — body copy and UI.

Signature motif:
- The **concentric gold diamond** from the logo. Used as: a faint oversized watermark
  behind navy sections, and small diamond glyphs as section markers / list bullets.
- IMPORTANT: diamonds are squares rotated 45° that MUST be centred on their rotation
  point (x = cx − size/2, y = cy − size/2), or they drift off-axis. See the homepage.

Logo files (in /design):
- `logo-dark-text.png`  — black wordmark, for LIGHT backgrounds.
- `logo-light-text.png` — cream wordmark, gold diamonds, for DARK (navy) backgrounds.
- Generate the favicon from the diamond mark only.

## Voice
Premium, institutional, understated — closer to a boutique investment bank than a
freelancer. Plain, specific, confident. Active voice. Sentence case.
- **Do NOT use em dashes (—) anywhere.** Use commas, colons, or separate sentences.
- Avoid: startup tone, generic consulting stock photos, loud gradients/animation,
  cartoon graphics, keyword stuffing.

## Copy facts (keep consistent)
- Founder is referred to as **"Ryan"** (not full name in body copy).
- Former **Nomura** investment banker, ~**3.5 years**, Consumer & Retail group, New York.
- Operating since **2022**, working remotely with investment firms and operating companies.
- Industry agnostic: consumer, technology, digital assets, healthcare, financial
  services, insurance, real estate, e-commerce.
- Contact: ryan@rfinancials.co and info@rfinancials.co. Site: rfinancials.co.
- Representative work must NOT reveal confidential client data. Use the anonymised
  case framing already in the homepage (Family Office, Healthcare IB, Growth Companies,
  Real Estate).

## Tech direction
- **Astro**, static output, SEO-first.
- Shared layout + design-token CSS so every page is consistent with the homepage.
- **Insights** blog as Markdown content collections: per-post SEO (title, meta
  description, canonical, OpenGraph), clean URLs, H1/H2 structure, author + date,
  related posts.
- Site-wide: sitemap.xml, robots.txt, meta tags, favicon, accessible + responsive,
  reduced-motion respected, visible keyboard focus.

## Page set (from the brief)
Home · Services · Outsourced Finance & Analytical Support · Transaction & Project
Support · Representative Work · About · Insights (blog) · Contact.

The two engagement models: **Transaction & Project Support** and (emphasised as the
core offering) **Outsourced / Embedded Resource**.

## Primary CTAs
- "Discuss an Engagement" (primary) · "Request the Services Overview" (secondary).
Every major page ends with a CTA.
