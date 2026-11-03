# WLMack Design LLC — Claude Code / Codex Website Handoff

A complete content and implementation specification for a modern minimalist agency site deployed from GitHub to Netlify.

## Start here
1. Create a GitHub repository and place these files at the repository root (or ask your coding agent to do so).
2. Open the repository in Claude Code or Codex.
3. Paste the instructions in `AGENT_PROMPT.md`.
4. Review generated pages, replace placeholder project assets, and test forms before publishing.
5. Connect the repository in Netlify: build command `npm run build`; publish directory `dist`.

This package is **a specification and copy deck**, not an already coded website. The coding agent is expected to generate the application.

## Files
- `AGENT_PROMPT.md`: implementation instructions and acceptance criteria
- `SITE_COPY.md`: complete editable copy for every page
- `CONTENT_MODEL.md`: navigation, portfolio schema, forms, SEO and business rules
- `netlify.toml`: initial Netlify configuration (Astro static output)

## Business details to verify before launch
- Brand display name: WLMack Design LLC (use consistently)
- Location: Tuscaloosa, Alabama
- Contact email, phone, domain, social URLs: **confirm**; do not invent
- Company logo and portfolio images: to be supplied
- Do not name confidential clients or fabricate testimonials
- Public retainer prices are starting prices, subject to scope and signed agreement
- Apparel turnaround is an estimate confirmed on quote; do not promise universal 5-day delivery
- Growth plans are aspirations, not funded or completed accomplishments
