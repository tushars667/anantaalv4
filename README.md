# Anantaal V4 — A Space to Feel Again

**A brand-new, mobile-first, conversion-led visual prototype for Anantaal.**

## Quick deploy to Vercel
1. Create an empty GitHub repository (`anantaal-v4`).
2. Extract this ZIP and upload its **contents**, not the ZIP file, to the repository root.
3. In Vercel: **Add New → Project → Import Git Repository**.
4. Framework Preset: **Other**. Root Directory: `./`. Build Command: **none**. Output Directory: **blank/default**.
5. Deploy; you will get a separate `*.vercel.app` demo URL. Your real `anantaal.com` domain is unaffected.

This is plain HTML/CSS/JavaScript with local optimized `.webp` images. There is no build step or third-party JS dependency. You can also open `index.html` locally in a browser to preview it.

## Mobile interactions
- Cinematic editorial entrance, giant fluid typography and touchable hero resonance button
- Canvas-based resonance field: tap and drag to create visual ripples and short generated notes
- Ambient original synthesized drone (never autoplay; user must opt in); auto-mutes on page background
- Interactive mood-to-session matchmaker: calm / connect / explore
- Horizontal, swipeable session cards with tap-to-enquire actions
- A gentle 30-second guided breathing exercise
- Calendar date selection for a **preferred enquiry date** (NOT confirmed inventory)
- Three-step-feeling enquiry bottom sheet: session, date, participants, name → **pre-filled WhatsApp**
- Always-present mobile booking and WhatsApp access after the hero
- Instrument enquiry via WhatsApp
- Reduced motion and keyboard/mobile navigation support

## What is real vs. prototype
✅ Real Anantaal business name, service categories, public contact details and photos adapted from provided source screenshots / earlier Anantaal prototypes.
✅ WhatsApp enquiry links currently address **+91 92512 44844** (verify before sharing the demo broadly).
✅ Selectable calendar and enquiry form work in the browser; nothing is stored or charged.
⚠️ Calendar deliberately makes **no claim of current availability**. There are no hard-coded fictional session dates, seat counts, fees or reviews.
⚠️ This **does not** include Razorpay charges/transactions, persistent bookings/admin DB, Meta API campaigns, Shiprocket shipments or actual inventory. Their setup and server side implementation are a separate production phase.
⚠️ Website uses Google-hosted fonts with local serif/system fallbacks. If strictly offline, typography will render with fallbacks.
⚠️ Ambient audio uses the Web Audio API and requires user gesture; some browsers disable output under low-power or muted conditions.

## Changing contact details
Edit `PHONE` in `app.js`, plus the `tel:`, `wa.me` and `mailto:` links in `index.html`. Verify the physical address and company name on the current client website before publishing.

## Project files
- `index.html` — SEO, mobile-first page structure and dialogs
- `styles.css` — full responsive design, animations, themes, reduced motion
- `app.js` — interactions, Web Audio synth, calendar, WhatsApp enquiry
- `assets/` — repurposed Anantaal imagery, optimized WEBP and favicon
- `vercel.json` — static website configuration and safety headers

## Visual acceptance tests before client handoff
Check iPhone at 320/375/390px; Android at 412px; tablet at 768px; desktop at 1440px. Try menu, touch gong, ambient sound on/off, sound field gesture, mood selector, calendar month navigation, booking form WhatsApp handoff, breath exercise, and product enquiries. Confirm text, dates and contact details with client. No payment claims should be made until integrations and backend are complete.
