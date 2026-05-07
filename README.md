# XO Sweets Miami — Landing Page

A luxury, editorial landing page for **XO Sweets Miami**, a Miami-based couture patisserie crafting bespoke cakes, cupcakes, cake pops, cookies, brownies, flan, and tres leches for weddings, birthdays, and high-end events.

## Design

- **Direction**: Parisian Patisserie — soft, ornamental, gold-accented
- **Palette**: Warm neutrals (paper white, ink black, cocoa) with blush rose and champagne gold accents
- **Typography**: Playfair Display (display), Cormorant Garamond (serif), Cormorant Infant (italic), Inter (sans)
- **Audience**: High-value private clientele

## Sections

1. **Hero** — Brand crest, tagline, dual CTAs, atelier collage with seal
2. **Strip** — Offerings band (Cakes · Cupcakes · Cake Pops · Cookies · Brownies · Flan · Tres Leches)
3. **Signatures** — 5-card gallery of signature creations
4. **La Carte** — Full menu with starting prices
5. **Le Journal** — Instagram feed grid (links to [@xosweetsmiami](https://www.instagram.com/xosweetsmiami/))
6. **Réservez** — Inquiry form + testimonial
7. **Footer** — Studio, contact, social, inquiries

## Local preview

Open `index.html` directly in a browser, or serve from the directory:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Contact

- **Phone**: 786 354 7439
- **Email**: xosweetsmiami@gmail.com
- **Instagram**: [@xosweetsmiami](https://www.instagram.com/xosweetsmiami/)
- **Service area**: Miami-Dade & Broward Counties

## Notes for the owner

- All product imagery is currently sourced from Unsplash as placeholders. Swap each `<img>` `src` for real XO Sweets product photography when ready.
- The inquiry form uses a `mailto:` action by default. For a production form, wire it to a service such as Formspree, Netlify Forms, or a custom endpoint.
- Hosting suggestion: GitHub Pages, Netlify, or Vercel — this is a static, single-file site.
