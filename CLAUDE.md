# BEAUTELLO BEAUTY PARLOUR — PROJECT RULES

Read this entire file before writing code.

Build a premium, elegant, long-term beauty parlour website for Beautello Beauty Parlour, Kattakada.
The website is NOT an ecommerce cosmetics website. It is a real salon website focused on:
services, hair care, facial & skin care, nail art, bridal beauty, gallery, appointment booking,
contact/location and customer trust.

## Implementation
- Everything in index.html (HTML + CSS + JavaScript). No React, no npm, no package.json, no build tools.
- GSAP + ScrollTrigger (cdnjs) for animation. Respect prefers-reduced-motion.
- Fully responsive (desktop, tablet, mobile). Sticky Call / Book bar on mobile.

## Business facts (use exactly)
- Name: Beautello Beauty Parlour
- Location: Near New Mammal Hospital, Kattakada
- Calling phone: 8714901099 (tel:+918714901099). WhatsApp bookings: 7510787039 (wa.me/917510787039). Book buttons open the booking drawer, which sends the request to WhatsApp. No database.
- Bridal message: Special offers available for upcoming brides!

## Long-term rules
- No date-specific offers, countdowns or expiry timers anywhere.
- Prices live only in the OFFERS / NAIL_ART objects at the top of the <script>; set `active:false` to hide an offer.
- Do not invent awards, certifications, years of experience, reviews, street addresses or social handles.
  Add the real Instagram URL in SITE.instagramUrl when available.

## Visual identity
Black & champagne gold luxury palette with ivory light sections; kasavu-stripe gold dividers; full-bleed editorial photography; GSAP motion (curtain reveals, word reveals, tilt, velocity marquee); Cormorant Garamond + Jost; editorial photography.
