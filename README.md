# SEEFA by Alef — Novera Real Estate Landing Page

Landing page for SEEFA by Alef (Al Khan, Sharjah), built for Novera Real Estate.

## Structure
```
index.html          — the full page (single file, no build step)
assets/img/          — project renders (supplied by Novera) + Novera logo + Alef wordmark
assets/fonts/        — self-hosted EB Garamond + Montserrat (woff2)
```

## Deploy on Vercel
Plain static site — same as the Florence project.
Framework preset: **Other**. No build command. Output directory: root.

## CTA behaviour (matches Florence)
- Nav "Register Your Interest" → scrolls to the enquiry form
- Hero "Register Your Interest" → scrolls to the enquiry form
- Final CTA "Chat on WhatsApp" (label only) → scrolls to the enquiry form
- Final CTA "Call" button → direct `tel:` link, unaffected
- Form submit → opens WhatsApp pre-filled with the visitor's details

## Flagged for confirmation before going live
The following figures came from a third-party broker's own SEEFA marketing site
(not Alef's official channel) and are marked with an asterisk on the page itself:
- 30/70 payment plan (10% booking / 20% construction / 70% handover)
- 7.5–8.8% projected rental yield
- Golden Visa qualifying threshold
- Q4 2028 handover date (not currently shown on page — add once confirmed)

**Please verify these with Alef/Aboude/Swaliha before removing the disclaimer note
in the "Why Invest" section.**

## Developer logo
The "A DEVELOPMENT BY" credit currently uses a plain text wordmark for Alef Group —
no clean logo file was available. Swap in `assets/img/alef-wordmark.png` with an
official Alef logo file if/when supplied, same as we did for Azizi on the Florence page.

## Contact
Novera Real Estate — +971 58 542 4430 — noverarealty.ae
