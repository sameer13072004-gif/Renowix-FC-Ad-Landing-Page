# Renowix — Noida False Ceiling Google Ads Landing Page

High-conversion, zero-dependency, mobile-first Google Ads landing page and post-conversion flow for **Renowix** (Architectural Gypsum & POP false ceiling contractor in Noida).

## Overview

- **Primary Goal:** Capture high-intent WhatsApp estimates and direct phone calls from cold Google Search Ads traffic (₹300/day budget) with zero upfront payment friction.
- **Target Audience:** Noida apartment homeowners (Sectors 50, 78, 104, 128, etc.).
- **Tech Stack:** Vanilla HTML5, CSS3, ES6 JavaScript (Zero third-party framework dependencies, lightning-fast Core Web Vitals).

## Pages

1. **`index.html`** — 8-section conversion architecture:
   - Sticky header with plain-text phone link for Google Ads Call Asset verification (`📞 +91 92114 29635`).
   - Above-the-fold hero with integrated lead capture card.
   - Interactive Before/After bedroom comparison slider.
   - Interactive Room Cost Estimator (feeds dynamically into lead form).
   - The Renowix Standard proof grid (4 technical engineering cards).
   - Real Noida site walkthrough videos (lightweight click-to-play) and signature Gypsum/POP layouts.
   - 3-step technical audit process.
   - Verified Noida testimonials, objection-handling FAQs, and sticky mobile bottom thumb bar.
2. **`thank-you.html`** — Post-conversion tracking & handoff:
   - Google Ads conversion tag placeholder firing on page load.
   - Dynamic client name extraction from `sessionStorage`.
   - Auto-triggers prefilled WhatsApp chat after 1.5 seconds with room and sector specifications.

## Deployment & Setup

- Deployable directly to **GitHub Pages**, **Cloudflare Pages**, **Vercel**, or **Netlify** by serving the root directory.
- Update Google Ads Conversion ID in `<head>` of both files (`AW-XXXXXXXXXX`).
- Update Google Sheet webhook URL in `index.html` (`GOOGLE_SHEET_WEBHOOK_URL`).
