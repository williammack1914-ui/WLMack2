# BUILD INSTRUCTIONS FOR CLAUDE CODE / CODEX

You are a senior front-end engineer and UX designer. Build a production-quality, modern minimalist, multi-page agency website for **WLMack Design LLC** based on the adjacent `SITE_COPY.md` and `CONTENT_MODEL.md`. Treat the copy as approved draft text, preserving its substance and avoiding fabricated claims. Do not ask for unnecessary confirmations; use clearly labeled placeholders for missing assets/contact information.

## Stack and hosting
- Astro (latest stable compatible version) with TypeScript and Tailwind CSS.
- Static output suitable for Netlify (`dist/`). No WordPress, PHP server, database, or required paid APIs.
- Content collections or typed local data for portfolio projects and plan definitions; easy editing without a CMS.
- Minimal client-side JS; accessible mobile navigation and category filters.
- `netlify.toml` in repo root. GitHub-connected deploy with `npm run build`.
- Netlify Forms: use a real static HTML form with `name`, `method="POST"`, `data-netlify="true"`, hidden `form-name`, honeypot, accessible labels, success/error UX; if using Astro component hydration, ensure Netlify detects the form in built HTML. Test actual submission on a deployed preview. Avoid exposing secrets.

## Pages and routes
- `/` Home
- `/about/` About
- `/services/` Services overview
- `/services/web-design/`
- `/services/brand-graphic-design/`
- `/services/custom-apparel/`
- `/portfolio/` with filters for Web, Branding, Print & Large Format, Apparel
- `/creative-retainers/` public packages and inquiry CTA
- `/growth-partnerships/` expansion and funding-related partnership page
- `/contact/` with project/retainer/apparel/partnership inquiry types
- `/privacy/` simple placeholder privacy policy clearly marked for owner/legal review (do not invent compliance claims)
- custom 404 page

## Design and UX
- Modern minimalist, premium, polished, confident, approachable; generous whitespace, excellent typography, disciplined grid, refined motion and hover states, high contrast.
- Owner controls final colors, typography, logo and imagery. Use a restrained neutral starter theme with easily edited CSS tokens; do not force an elaborate palette.
- Hero: “We design brands, build websites, and produce apparel that make businesses look as strong as they are.”
- Main CTAs: Request a Quote, View Our Work, Explore Services; contextual CTAs on each service page.
- Sticky or clearly accessible header; responsive navigation; footer with services, location, contact placeholders, legal links.
- Portfolio: responsive project grid, accessible filter controls, individual project cards with optional case study fields. Never invent client identities, metrics, or images. Use tasteful labeled placeholders.
- Retainer pricing cards: three public tiers; optional starter plan should NOT appear in public pricing by default.
- Growth page should emphasize demonstrated experience and prospective growth plans; do not claim financing, investment returns, or existing recurring contracts without evidence.

## Technical acceptance criteria
- Responsive from 320px through desktop; semantic headings, keyboard navigation, visible focus, reduced-motion support, alt text, color contrast.
- Unique title/meta description, canonical URLs once domain is known, Open Graph/Twitter metadata, sitemap, robots.txt; local business structured data only with verified contact details.
- Optimized images via Astro assets where practical; lazy loading for below-fold images; no large JS framework solely for filters.
- No fake testimonials, partner logos, client names, financial numbers, revenue claims, or claims of universal turnaround guarantees.
- Make navigation, links, buttons and forms functional. External DayPartyTees.com link must be labeled as shopping for individual items and is known to redirect to Etsy; bulk requests remain on this site.
- Provide `README.md` with local development (`npm install`, `npm run dev`, `npm run build`, `npm run preview`), deployment steps, and exact locations for editing copy and adding portfolio items.
- Run install/build/check and fix errors before completing. Summarize what was built and list owner inputs still required.

## Implementation sequence
1. Scaffold Astro/Tailwind and global layout/theme.
2. Create typed content data and reusable Hero, ServiceCard, ProjectCard, PricingCard, CTA, FAQ, ContactForm components.
3. Build all routes using `SITE_COPY.md`, preserving full copy rather than using lorem ipsum.
4. Add portfolio content structure with placeholder projects only (clearly labeled samples, not represented as real completed work).
5. Implement Netlify form and deployment configuration.
6. Add SEO, accessibility, responsive testing, and documentation.
