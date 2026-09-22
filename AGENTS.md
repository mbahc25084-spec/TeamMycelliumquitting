# The Slot Agent — operating constraints

1. No network calls. The prototype runs fully offline.
2. Do not fabricate evidence, statistics, quotes, research results, or testimonials.
3. Agent explanations must derive from the current policy decision.
4. User-visible state changes must append an event before rendering in the audit trace.
5. Data and capability provenance must be visible: `SIMULATED`, `LOCAL`, or `REAL`.
6. Keep the demo deterministic and legible.
