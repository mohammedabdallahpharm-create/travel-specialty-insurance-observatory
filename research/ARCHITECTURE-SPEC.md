# Architecture Specification — v1.0

## Approved decisions
- Market: UAE-first.
- Domains: Travel Insurance and Pet Insurance, maintained separately.
- Baggage Protection: a Travel Insurance subdomain.
- Methodology: shared evidence-led research methodology.
- Repository: independent from the GCC Health Insurance Observatory.
- First research priority: Claims Operations.

## Product areas
1. Observatory Overview
2. Travel Insurance
3. Pet Insurance
4. Claims Operations
5. AI, Technology and Workforce
6. Entity Registry
7. Signal Registry
8. Methodology

## Technical architecture
- Static-first HTML, CSS and Vanilla JavaScript.
- JSON structured data; Markdown research records.
- No backend, database or external API in the MVP.
- JSON Schema validation for signals and entities.
- Vercel hosting and GitHub version control.
- English LTR and Arabic RTL support.

## Data flow
Research → Evidence Review → Signal Record → Structured Registry → Observatory Interface → Vercel Deployment.

The structured registry drives the interface. Markdown records preserve research narrative and evidence trails. A record's presence in JSON does not itself establish verification.

## Domain boundaries
Travel includes emergency medical coverage, trip cancellation, trip interruption, flight delay, emergency assistance and baggage protection.

Pet initially covers companion animals: accidental injury, illness, veterinary expenses, surgery, diagnostics and medication, emergency veterinary care and third-party liability where covered. Livestock and agricultural animal insurance are out of scope.

## Claims Operations
Travel and Pet claims have separate reference workflows. These are analytical models, not claims that every organisation follows an identical process. See the Domain Blueprint and methodology as these are expanded.

## Expansion
The data model carries a market field so additional GCC markets can be introduced without merging the two domains or redesigning the application.
