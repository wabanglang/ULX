# ULX Public Specification Boundary

**Status:** Experimental public specification surface

## Purpose

This document defines what the public ULX project claims, what it does not claim, and which implementation details remain outside the public release.

## Public definition

ULX is an experimental framework for representing selected meaning, relationships, constraints, provenance, and reusable context in a more compact and structured form than repeatedly restating the original natural-language source.

A valid ULX research artifact should aim to preserve enough information that a reviewer can determine what was retained, transformed, omitted, or made uncertain.

## Public design principles

1. **Meaning before shorthand.** Smaller representations are useful only if relevant meaning survives.
2. **Recoverability.** Where possible, transformations should retain a traceable path back to source meaning.
3. **Provenance.** Claims and derived structures should identify their source or derivation context.
4. **Explicit uncertainty.** Ambiguity, contradiction, and information loss should be surfaced rather than silently resolved.
5. **Model independence as a test, not an assumption.** Cross-model portability must be measured.
6. **Compression is not success by itself.** Byte, token, or character reduction must be evaluated alongside semantic retention.
7. **Human interpretability matters.** Public artifacts should remain inspectable enough to audit claims and failures.

## What the public release does not expose

This repository does not publish the complete private ULX notation system, full translation grammar, internal semantic maps, proprietary operator tables, unreleased compiler/runtime logic, private corpora, or other implementation details whose publication would materially reconstruct the private system.

## Claim classes

Every substantive result should use one of these labels:

- **DEMONSTRATED** — independently reproducible from public fixtures or directly supported by a published artifact.
- **EXPERIMENTAL** — observed during development but not yet independently reproduced to the desired standard.
- **PROPOSED** — a design target, hypothesis, or future capability.

## Minimum acceptance test for a public ULX transformation

A public transformation should disclose:

- the source fixture;
- the transformed representation or safe public surrogate;
- the metric being optimized;
- the recovery or interpretation procedure used for the test;
- the semantic criteria used to score retention;
- the observed failure modes;
- the model/tool/version environment when relevant;
- enough information for another party to challenge the result.

## Non-claims

The public project does not currently claim that ULX:

- is lossless for arbitrary natural language;
- universally reduces tokens across all models;
- is a universal replacement for natural language or code;
- guarantees identical reconstruction across different AI systems;
- has solved semantic compression in the general case;
- has been independently validated at scale.

Any future claim in those directions should be supported by public evidence before being treated as established.

## Research objective

The central public objective is straightforward:

> Determine whether selected complex human–AI context can be represented more efficiently while preserving the meaning, relationships, provenance, and uncertainty required for useful reconstruction and continued work.
