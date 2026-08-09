# Flux Principle v0.1

**Status:** WORKING  
**Provenance:** SHARED

## Principle

Change is part of normal system existence.

TAGRO OS should not treat redesign, correction or new information as exceptional failure. It should expect continuous updates and preserve enough structure to understand what changed and what depends on it.

## Information classes

The interface need not expose these labels, but the information process should know the difference between:

- sufficiently established facts
- current design decisions
- uncertain, estimated or changing information
- physical installed reality

## Dependency response

When information changes, the system should determine:

1. what changed
2. what objects or decisions depend on it
3. what remains valid
4. what must be recalculated
5. whether a human decision is required

## Scope

Recalculation should operate at the smallest affected scope and propagate only along real dependencies.

## History

New information may supersede an old estimate, but the previous state remains traceable.

## Governing rule

Never confuse the present answer with permanent truth.