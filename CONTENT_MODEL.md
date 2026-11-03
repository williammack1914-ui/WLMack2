# Information architecture, content and operational rules

## Navigation
Home | Services (Web Design, Brand & Graphic Design, Custom Apparel) | Portfolio | Creative Retainers | About | Contact
Growth & Partnerships should appear in footer and optionally About, not dominate the primary sales navigation.

## Business positioning
Tuscaloosa-based boutique creative agency with 20 years of experience. Core divisions: websites, branding/graphic design, bulk branded apparel. B2B audience: businesses, schools/athletics, civic and community groups, churches, event organizers, corporate/industrial teams. Speak as “we” without implying a large staff.

## Verified proof points from owner
- 20 years operating in design/business
- 40+ paid client websites
- Largest apparel order fulfilled: 300 pieces (do NOT write “300+ apparel orders”)
- Names of clients cannot be publicized
- Apparel methods: screen printing, DTF, embroidery, heat press/vinyl; production via in-house and partners
- Bulk pricing minimum: 30 pieces
- WordPress specialty, Shopify capability

## Portfolio project data shape
`slug`, `title`, `category` (web|branding|print|apparel), `summary`, `services[]`, `coverImage`, `alt`, `gallery[]`, `challenge?`, `approach?`, `deliverables[]`, `outcome?`, `clientDisplayName?` (default “Confidential client”), `featured`.
No invented outcomes or client names. Add 6–12 projects once supplied; start with clearly labeled placeholders and an owner-facing instruction.

## Inquiry form
Required: name, email, projectType, description. Optional: organization, phone, desiredStartDate, budgetRange, quantity, garmentType, deliveryDeadline. Conditional fields may be implemented accessibly, but all data must post successfully to Netlify Forms. Project types: Website, Branding/Graphic Design, Bulk Apparel, Creative Retainer, Growth/Partnership, Other. Add privacy consent checkbox if legally appropriate; owner to review policy.

## Retainer service rules
Public tiers:
- Core Creative Partner: $650–$750/month; up to 6 standard design requests; 2 revision rounds; typical 3–5 business days.
- Growth Creative Partner: $1,100–$1,300/month; up to 12 standard requests; monthly check-in; typical 2–3 business days.
- Dedicated Creative Department: starting $2,000/month; up to 25 standard requests, scope-dependent; prioritized turnaround targets agreed in contract.
Private, optional proposal-only: Starter Creative Partner $350–$400/month, up to 3 simple designs, 1 revision, 5–7 business days, 90-day review. Do NOT publish on pricing grid unless owner requests.
Terms: 3-month initial agreement recommended, month-to-month afterward; unused requests don't roll over; major rebrands, web builds, complex multipage projects and rush work priced separately; one request must be defined by deliverable complexity in contract; clarify concurrent requests, revisions, source file rights and response times.

## Apparel policies
30-piece minimum for bulk pricing, not a claim that single items cannot be purchased. Turnaround varies with decoration, garment availability, approvals and shipping. Quote estimated production window on each project; 5–14 business days is indicative, not guaranteed. Team packages: shirts, sweatshirts/hoodies, polos, staff/team/event packages. DayPartyTees.com redirects to Etsy for retail/single-item purchases.

## Growth page credibility guardrails
Public growth story: expand apparel capacity, ordering workflows, supplier relationships and recurring design partnerships. No implication that financing has been approved, staff hired, facilities expanded, or predictable recurring revenue already contracted. Lenders will require financial statements, cash flow forecasts, use-of-funds and evidence beyond website copy. Include discreet CTA for funding/strategic partnership inquiries.

## SEO
Each page's proposed metadata is in `SITE_COPY.md`. Use one H1 per page, descriptive URLs, internal linking, local context where relevant. Do not keyword stuff. Replace example canonical domain only when owner confirms it.
