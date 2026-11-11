# Travel & Specialty Insurance Observatory

An independent, evidence-led research observatory examining how travel and companion-animal (pet) insurance markets operate, how claims responsibilities are distributed, and how technology changes operational work and decision authority.

**Initial market:** United Arab Emirates (UAE)  
**Research domains:** Travel Insurance and Pet Insurance  
**Coverage subdomain:** Baggage Protection (within Travel)  
**Initial operational priority:** Claims Operations  
**Architecture:** Static-first HTML, CSS, Vanilla JavaScript and JSON; deployed on Vercel.

## Research principles

- Evidence before interpretation; every published signal must have a traceable source trail.
- Distinguish verified facts, partial evidence, hypotheses, disputed claims and historical information.
- Separate event, publication and observation dates.
- Do not infer contractual responsibility, operational deployment or measurable impact without evidence.
- Treat reference claims workflows as research models, not universal descriptions of insurer practice.
- Keep Travel and Pet as separate domains while sharing the research methodology.
- Build UAE research credibility before extending coverage to other GCC markets.

## Repository map

- `data/` — structured registry consumed by the interface.
- `research/` — methodology, market context, domain research and detailed signal records.
- `schemas/` — JSON schemas for validating structured records.
- `assets/` — frontend CSS, JavaScript and images.

## Source of truth

- `data/signals.json` is the structured signal index.
- `research/signals/` contains the detailed research record for each signal.
- A signal ID must match exactly between the registry and its Markdown record.
- `data/entities.json` is the structured entity registry.

No signal is considered verified merely because it is present in the interface. The evidence status recorded for each signal governs how it is presented.

## MVP scope

The MVP does not provide quotations, policy recommendations, claims processing, customer-data collection, claim-outcome prediction, automated scraping or a claim of comprehensive UAE market coverage.

## Local development

This is a static application. Serve the repository root with any static HTTP server. No package installation or backend is required for the initial MVP.

## Deployment

The intended hosting platform is Vercel. The site should deploy from the repository's production branch with no build step and the repository root as the output directory.

## Status

Repository foundation initialized. Research records and interface features will be added only after evidence and data structures are defined and validated.

## Strategic principle

**AI prepares the work; humans make the decision.**
