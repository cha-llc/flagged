# 🔴 Flagged — AI Relationship Pattern Analyzer

**"Your gut says something's off."**

Flagged is a fully automated $4.99 relationship pattern analyzer. Describe what's happening, get an instant AI analysis of behavioral patterns — manipulation tactics, emotional unavailability, communication styles — with a risk score and personalized advice.

## What It Does
- Detects 12 behavioral patterns including gaslighting, love bombing, intermittent reinforcement, and emotional coercion
- Generates a risk score (0–100%)
- Provides named pattern cards with explanations
- Delivers personalized advice based on findings
- 100% private — data analyzed immediately, never stored

## Tech Stack
- Pure HTML/CSS/JS — single file, zero dependencies
- Stripe Payment Links for checkout ($4.99 one-time)
- Gmail for automated report delivery
- Zero data retention by design

## Setup
1. Open `index.html`
2. Replace the Stripe comment with your Payment Link:
   ```js
   window.location.href = 'https://buy.stripe.com/YOUR_LINK';
   ```
3. Deploy to Netlify Drop, Vercel, or any static host
4. Connect Stripe webhook → Gmail for report delivery

## Important
Flagged is an awareness tool for educational purposes only. It is not a clinical diagnosis and does not replace professional mental health support.

**Crisis resources included in all email reports:**
- National Domestic Violence Hotline: 1-800-799-7233
- Crisis Text Line: Text HOME to 741741

## Pricing
- **$4.99 one-time** per analysis
- Target: people in confusing relationships who need language for what they're experiencing

## License
© 2026 C.H.A. LLC — All rights reserved
