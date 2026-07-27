# IDE-BoK Authoring Guide

## Purpose

The Constitution protects the identity of the IDE-BoK. This guide protects its editorial and conceptual consistency.

## Core rules

- One concept, one authoritative definition.
- Definitions should fit in one paragraph.
- Canonical definitions must be technology-independent.
- Every concept must explicitly state dependencies and consumers.
- Examples are illustrative, not normative.
- Anti-patterns must explain their consequences.
- Metrics must state limitations, gaming risks, and unsafe conclusions.
- Every major Foundational or Core concept should have a visual model.

## Required concept structure

1. Metadata
2. Definition
3. Purpose
4. Problem Solved
5. Inputs
6. Outputs
7. Dependencies
8. Consumers
9. Quality Criteria
10. Relationships
11. Common Mistakes
12. Examples
13. Open Questions
14. References
15. Change History

## Metadata

```yaml
id: IDE-CONCEPT-XXX
name: Concept Name
classification: foundational | core | operational | experimental
domain: foundation | discovery | readiness | execution-boundary | evidence | evolution | governance
status: draft | proposed | validated | canonical | deprecated
version: 0.1
owner: unassigned
last_reviewed: YYYY-MM-DD
```

## Naming

- Use singular nouns for concepts.
- Prefer plain language.
- Avoid competing synonyms.
- Use stable identifiers in the format `IDE-[DOMAIN]-[NUMBER]`.

## Normative language

- **must**: mandatory.
- **should**: strong recommendation.
- **may**: permitted.
- **must not**: prohibited.

## Change controls

### Foundational
Requires hypothesis, evidence, impact analysis, ADR, review of dependents, and version increment.

### Core
Requires problem statement, evidence, impact analysis, dependency review, and version increment.

### Operational
Requires practical rationale and consistency review.

### Experimental
May evolve freely but remains outside canonical folders until promoted.

## Quality checklist

- [ ] Definition is unambiguous.
- [ ] Concept solves a distinct problem.
- [ ] Boundaries are explicit.
- [ ] Inputs and outputs are clear.
- [ ] Dependencies are correct.
- [ ] Definition is technology-independent.
- [ ] Examples do not become hidden requirements.
- [ ] Related concepts are linked.
- [ ] Common mistakes are documented.
- [ ] Content supports the North Star.
