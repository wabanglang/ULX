# ULX Benchmark Protocol

ULX should be evaluated as an information-preservation system, not merely as visual shorthand.

## Core measurements

For each public fixture, record at minimum:

| Metric | Purpose |
|---|---|
| Source bytes / characters / tokens | Establish baseline size |
| Representation bytes / characters / tokens | Measure reduction |
| Reconstruction size | Measure expansion cost |
| Semantic retention score | Measure preservation of required meaning |
| Provenance retention | Verify source links survive |
| Constraint retention | Verify requirements remain intact |
| Contradiction exposure | Verify conflicts are not silently erased |
| Ambiguity exposure | Verify unresolved ambiguity remains visible |
| Cross-model variance | Measure portability rather than assume it |
| Round-trip result | Compare reconstructed result with source criteria |

## Recommended test structure

1. Freeze a source fixture.
2. Define the semantic facts, relationships, constraints, and uncertainties that must survive.
3. Transform the fixture.
4. Measure representation size.
5. Reconstruct or interpret it in a clean evaluation context.
6. Score retention against the frozen criteria.
7. Repeat across models or environments where relevant.
8. Publish failures as well as successes.

## Minimum success condition

A smaller representation does not count as an improvement if the reduction is purchased by silently losing material meaning.

A benchmark result should therefore report compression and retention together.

## Failure classes

- `SEMANTIC_LOSS` — required meaning did not survive.
- `CONSTRAINT_LOSS` — a requirement or boundary disappeared.
- `PROVENANCE_LOSS` — source traceability was broken.
- `AMBIGUITY_COLLAPSE` — unresolved ambiguity was silently forced into one reading.
- `CONTRADICTION_COLLAPSE` — conflicting propositions were merged or hidden.
- `MODEL_DRIFT` — different evaluators produced materially incompatible interpretations.
- `ROUNDTRIP_FAILURE` — reconstruction failed the declared acceptance criteria.
- `SIZE_REGRESSION` — representation became larger without a compensating measurable benefit.

## Reporting rule

Do not publish a compression percentage alone. Pair it with semantic-retention criteria and the observed failure profile.

## Public benchmark goal

The public ULX benchmark program should make it increasingly difficult to confuse elegant notation with actual information efficiency.
