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

- `data/` — structured signal, entity, domain and company-neutral policy registries consumed by the interface.
- `research/` — methodology, market context, domain research and detailed signal records.
- `data/policy-comparison.json` — initial anonymized UAE travel-policy comparison (provisional; revalidation required).
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

The Travel Insurance Intelligence Framework currently includes a five-stage analytical flow, three initial research signals, and an anonymized comparison of two reviewed policy documents. The policy comparison is provisional and is not a coverage determination.

## Research prototype

- **Travel Exposure Intelligence Simulator v0.1:** [Open simulator](https://travel-specialty-insurance-observat.vercel.app/travel-exposure-simulator.html)
- Methodology and limitations: [`research/travel-exposure-intelligence-simulator.md`](research/travel-exposure-intelligence-simulator.md)

The simulator separates historical aviation event evidence from synthetic itinerary inputs. It does not access live flight feeds or policyholder records and does not determine insurance coverage or claim outcomes.

## Local development

This is a static application. Serve the repository root with any static HTTP server. No package installation or backend is required for the initial MVP.

## Deployment

The intended hosting platform is Vercel. The site should deploy from the repository's production branch with no build step and the repository root as the output directory.

## Status

Initial Travel Insurance Intelligence Framework deployed. Three signals and two provisional policy records are registered. Signal evidence is separated from unestablished insurance exposure; policy terms remain subject to full-document revalidation.

**Live observatory:** https://travel-specialty-insurance-observat.vercel.app

## Strategic principle

**AI prepares the work; humans make the decision.**
