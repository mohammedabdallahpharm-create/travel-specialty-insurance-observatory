# Travel Exposure Intelligence Simulator — v0.1

**Repository:** `travel-specialty-insurance-observatory`  
**Prototype route:** `/travel-exposure-simulator.html`  
**Research track:** Predictive Disruption Intelligence  
**Status:** Frontend prototype; historical case facts and synthetic scenario inputs are deliberately separated.

## Purpose

Test whether an external aviation disruption signal can be translated into a structured, passenger-level assistance workflow before a claim is submitted.

This is a workflow simulation, not a production risk engine and not evidence that any UAE insurer currently operates an integrated predictive capability.

## Historical case set

1. **CrowdStrike global IT outage — July 2024.** UAE operational impact was reported as limited. Public operational reporting is not evidence of insured passenger exposure or claims.
2. **Heathrow power failure — March 2025.** UAE–Heathrow services were affected through cancellations and rebooking/diversion responses. Public airport/airline reporting does not identify insured travellers or claim outcomes.
3. **Middle East airspace disruption — June 2025.** UAE GCAA material presented to ICAO documents contingency coordination and airspace measures. It does not establish integration with travel insurers or policyholder data.

The simulator keeps the event-level evidence panel separate from a fictional itinerary assessment. Event-level metrics must never be interpreted as passenger counts, insured exposure, claims or paid losses.

## Five-stage workflow

1. **External signal:** select the historical disruption and inspect the documented event-level facts.
2. **Exposure matching:** enter a synthetic itinerary and disruption outcome. In a live system this stage would require authorised itinerary data and reliable flight-status evidence.
3. **Coverage intelligence:** record whether complete, version-matched policy wording and schedule are available. The simulator does not interpret cover or decide eligibility.
4. **Operational response:** record whether airline rebooking or support is evidenced. Airline/airport recoveries must be identified before assessing residual expense.
5. **Financial outcome:** capture a user-entered illustrative expense only. It is not a verified loss, claim amount or insured payment.

## Demo logic

The prototype may flag a synthetic case for **assistance review** where the selected outcome is material (cancellation, diversion, missed connection, or a delay of at least four hours) and recovery/support is not confirmed or an expense is entered.

This is a deliberately simple triage demonstration, not a validated threshold, market rule, policy trigger or claims prediction model.

## Required data for a real pilot

- Authorised policyholder itinerary and consent / lawful processing basis.
- Flight-status records with source, timestamp, flight number, operating carrier and actual event status.
- Versioned policy wording, schedule, endorsements, definitions and exclusions.
- Airline / airport rebooking, refund, care and other recovery records.
- Passenger-specific receipts and evidence of remaining expense.
- Human review queue, audit trail, correction process and decision accountability.

## Measures not yet available

No reliable public dataset was identified for:
- affected UAE-issued insured travellers across the three cases;
- insurer alert-to-contact time;
- pre-claim exposure match rate;
- assistance resolution rate;
- claim frequency, acceptance or paid-loss amount;
- expense avoided or measurable loss reduction.

Do not fabricate these metrics. They require insurer / assistance-provider operational data and a defined measurement design.

## Governance

- Event facts, hypotheses, synthetic inputs and human decisions must be labelled separately.
- A flight disruption does not itself prove an insured event.
- Passenger welfare, airline recovery and insurance benefits are separate layers.
- Policy wording must be assessed against the correct policy version and individual facts.
- The system can prepare and prioritise work; authorised humans retain all coverage and claim decisions.

**Principle:** AI prepares the work; humans make the decision.
