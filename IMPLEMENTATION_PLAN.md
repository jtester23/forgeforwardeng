# Forge Forward Engineering Website Refresh Plan

## Goal

Build a polished static refresh for Forge Forward Engineering using the current public site content and media as the source material, while replacing the Wix-template feel with a faster, clearer, professional brand surface.

## Source Content

- Home page: `https://www.forgeforwardeng.com/`
- About page: `https://www.forgeforwardeng.com/about-1`
- Preserve the current navigation concepts, service areas, contact fields, contact email, and phone number.

## Build Strategy

1. Use static `index.html` and `styles.css` so the site can be opened locally, committed immediately, and later moved to GitHub Pages, Netlify, Vercel, or another host.
2. Keep content in semantic sections: hero, positioning, services, about, consultation CTA, contact, footer.
3. Link current public Wix image assets for the first pass, with alt text and lazy loading.
4. Implement a contact form shell with current field labels and a direct email fallback.
5. Add responsive CSS, focus states, reduced-motion handling, and metadata.

## Design Direction

Forge Forward should feel precise, durable, and calm. The layout should borrow from engineering documentation and facility-readiness checklists without looking like a terminal or generic tech startup. Use restrained color, decisive typography, and a visible service hierarchy.

## Verification

1. Open the static HTML locally.
2. Check mobile and desktop layout behavior.
3. Confirm navigation anchors, contact links, and external image loading.
4. Run a simple file/status check before committing.
