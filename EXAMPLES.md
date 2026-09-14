# ULX Public Examples

These examples illustrate the research idea without publishing the private ULX grammar or internal operator system.

## Example 1 — Repeated project constraint

### Source pattern

A project repeatedly states:

- mobile first;
- high contrast;
- keyboard accessible;
- reduced-motion compatible.

The same constraints appear across many later instructions.

### Public ULX idea

Instead of restating those four constraints every time, define a reusable context object once and refer back to it in later work.

### What must survive

- all four constraints;
- their applicability to later tasks;
- any later exception or modification;
- provenance showing where the constraints originated.

### Failure example

If the compact representation later reconstructs only “mobile friendly,” it has compressed the text but lost material meaning. That is a failure.

---

## Example 2 — Contradictory requirements

### Source pattern

A project says both:

- “Use no JavaScript.”
- “Use JavaScript if it is necessary for the required interaction.”

### Public ULX idea

A compact representation should not silently choose one statement. It should preserve the conflict or encode the conditional relationship explicitly.

### What must survive

- both propositions;
- their ordering or provenance when relevant;
- the unresolved or conditional relationship between them.

### Failure example

A representation that outputs only “JavaScript allowed” has hidden important context.

---

## Example 3 — Long conversation becomes a knowledge object

### Source pattern

A long conversation contains definitions, decisions, corrections, accepted constraints, rejected alternatives, benchmark results, and unresolved questions.

### Public ULX idea

Transform the conversation into an inspectable structure containing the relationships needed for future work instead of carrying the entire transcript verbatim in every subsequent interaction.

### What must survive

- active definitions;
- superseded definitions where provenance matters;
- accepted constraints;
- unresolved questions;
- material decisions;
- evidence links;
- contradictions and uncertainty.

The research challenge is to determine how much textual redundancy can be removed without damaging those functions.

## Important distinction

These examples describe the **public concept**, not the unreleased private ULX encoding syntax.
