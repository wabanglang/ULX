# Contributing to ULX

ULX is experimental. The most valuable contributions are not praise; they are precise tests, counterexamples, failure cases, benchmark improvements, and reproducible critiques.

## Good contributions

- a fixture that exposes semantic loss;
- a better retention metric;
- a contradiction or ambiguity case the current benchmark misses;
- an independent cross-model comparison;
- a baseline showing that a simpler method performs as well or better;
- a reproducible bug in a public tool or example;
- a documentation correction that makes a claim more precise.

## Contribution rules

1. Separate observation from inference.
2. Include enough detail for reproduction.
3. Do not upgrade experimental findings into proven claims without evidence.
4. Report negative results.
5. Preserve source provenance where relevant.
6. Do not submit confidential, private, or personally identifying source material.
7. Do not attempt to smuggle proprietary or private ULX implementation details into the public repository.

## Suggested issue format

**Claim or component:**

**Fixture / source:**

**Expected result:**

**Observed result:**

**Environment / model / version:**

**Failure class, if applicable:**

**Reproduction steps:**

**Evidence:**

## Research posture

The project should prefer a discovered failure over an unsupported success claim. A benchmark that breaks ULX is useful information.
