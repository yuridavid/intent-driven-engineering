---
status: draft
category: Foundational Research
authors:
  - IDE Research Group
created: 2026-07-28
last_review: 2026-07-28
related_documents:
  - ../../VISION.md
  - ../../ide-bok/00-governance/constitution.md
  - ../../ide-bok/01-foundation/intent.md
  - ../../ide-bok/01-foundation/transformation.md
  - ../../ide-bok/01-foundation/evidence.md
  - ../../ide-bok/07-governance/research-promotion-process.md
---

# R-001 — Defining the Scientific Object of Intent-Driven Engineering

## Purpose

Establish the scientific object of Intent-Driven Engineering (IDE) and define
the boundaries of the discipline before formalizing its Body of Knowledge.

## 1. Background

Software Engineering has historically focused on the construction, maintenance,
and evolution of software systems.

As software development enters the AI era, implementation itself is becoming
increasingly automated. Large Language Models and autonomous execution systems
are capable of transforming specifications into working software with limited
human intervention.

This shift fundamentally changes where engineering effort creates value.

Implementation is no longer the primary bottleneck.

The new challenge is preserving business intent while autonomous systems
perform increasing portions of the implementation.

This observation motivates the need for a new engineering discipline.

## 2. Problem Statement

Current software engineering practices primarily optimize implementation
activities.

Examples include:

- coding;
- testing;
- deployment;
- estimation;
- project management.

However, none of these disciplines explicitly studies how business intent is
preserved across successive transformations performed by both humans and
autonomous agents.

As AI capabilities increase, this gap becomes progressively more significant.

## 3. Research Question

What is the scientific object of Intent-Driven Engineering?

## 4. Initial Hypothesis

Intent-Driven Engineering studies the preservation, transformation, and
validation of business intent throughout the lifecycle of software delivery,
regardless of who—or what—performs implementation.

## 5. Candidate Scientific Object

The proposed scientific object is:

> The controlled transformation of business intent into validated operational
> behavior.

Several characteristics distinguish this object:

- it begins before implementation;
- it remains technology independent;
- it encompasses both human and AI execution;
- it concludes only when the intended business outcome is demonstrably
  achieved.

## 6. Alternative Scientific Objects

The current formulation uses **Business Intent**, but that choice remains a
research hypothesis rather than a settled definition. Four candidate objects
need to be compared:

| Candidate | Strengths | Limitations and open issues |
|---|---|---|
| **Business Intent** | Connects engineering work directly to business value, constraints, and expected change. It is consistent with the current IDE North Star and foundational concepts. | It may be too narrow for public-interest, regulatory, nonprofit, infrastructure, or internal technical work where no single business intent is identifiable. |
| **Stakeholder Intent** | Broadens the object to include users, operators, regulators, communities, sponsors, and other affected parties. | Stakeholders can hold conflicting intentions, making it unclear which intent should govern a transformation or how conflicts should be resolved. |
| **Desired Outcome** | Emphasizes observable results rather than the identity of the intent holder. It aligns well with validation and evidence. | An outcome alone may omit the reasoning, values, constraints, and unacceptable consequences that give the outcome meaning. |
| **Operational Objective** | Provides a concrete, execution-oriented target that can often be measured in operation. | It risks starting too late in the lifecycle and reducing IDE to operational optimization instead of preserving meaning from the original need. |

The document intentionally leaves the choice open because selecting a scientific
object determines the boundary of the discipline, its terminology, its
validation model, and the kinds of change it can legitimately govern. Further
research must test each candidate against varied organizational contexts,
conflicting interests, non-commercial systems, and end-to-end transformation
cases before one formulation becomes canonical.

Until that validation is complete, **Business Intent** remains the working
candidate and must not be interpreted as a final exclusion of broader forms of
intent or outcome.

## 7. Scope

IDE studies:

- intent definition;
- context acquisition;
- decision quality;
- specification quality;
- readiness assessment;
- transformation integrity;
- evidence generation;
- validation loops;
- learning from outcomes;
- human–AI collaboration;
- autonomous execution governance.

IDE does not primarily study:

- programming languages;
- framework selection;
- UI implementation;
- infrastructure configuration;
- CI/CD tooling;
- algorithm optimization.

These remain within existing engineering disciplines.

## 8. Central Hypothesis

Implementation is no longer the primary engineering activity.

The primary engineering activity becomes preserving intent across
transformations.

## 9. Consequences

If the hypothesis is valid:

- specifications become first-class engineering artifacts;
- context becomes an engineering asset;
- AI becomes an execution capability rather than the center of the discipline;
- engineering quality is measured by intent preservation instead of
  implementation effort.

## 10. Questions to Validate

The research remains open regarding:

- Is "business intent" sufficiently general, or should the discipline use the
  broader concept of "stakeholder intent"?
- Does the lifecycle end at operational behavior, or only after measurable
  business outcomes?
- Is transformation the fundamental abstraction, or merely the observable
  mechanism?
- Can intent integrity be objectively measured?
- Are autonomous systems execution capabilities or engineering actors?

## 11. Expected Contributions

If validated, this research establishes:

- the scientific object of IDE;
- the boundary between IDE and Software Engineering;
- the conceptual foundation for the IDE Body of Knowledge;
- a consistent vocabulary for future domains.
