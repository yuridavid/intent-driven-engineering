# Governance Decision Log

| ID | Date | Decision | Status |
|---|---|---|---|
| GOV-001 | 2026-07-27 | Establish IDE-BoK as the source of truth | Accepted |
| GOV-002 | 2026-07-27 | Separate canonical knowledge from research | Accepted |
| GOV-003 | 2026-07-27 | Use concepts as first-class knowledge entities | Accepted |
| GOV-004 | 2026-07-27 | Keep canonical definitions technology-independent | Accepted |
| GOV-005 | 2026-07-28 | Approve the Engineering Capability Architecture | Accepted |

## GOV-005 — Approve the Engineering Capability Architecture

**Date:** 2026-07-28

**Status:** Accepted

**Decision owner:** IDE-BoK Steward

**Approving authority:** Repository Owner

**Approved architecture version:** 1.0

### Context

The initial Engineering Capability Architecture required correction before it
could govern future capabilities. The architecture review identified source of
truth, relationship semantics, qualification, lifecycle, contract, ownership,
and evolution issues in findings F-001 through F-009.

Task 0.1 moved the sole governed architecture source to
`ide-bok/architecture/engineering-capability.md`, converted the document under
`docs/` into a derived reference, and resolved the required findings. The
subsequent review verdict was `APPROVE WITH MINOR CHANGES`. The remaining
changes were governance metadata, ownership, authority wording, navigation, and
promotion.

### Decision

The Repository Owner approves Engineering Capability Architecture version 1.0
with the IDE-BoK Steward as its role-based owner.

The decision establishes that:

- `ide-bok/architecture/engineering-capability.md` is the sole canonical source
  for the Engineering Capability Architecture;
- `docs/architecture/engineering-capability.md` is a derived navigation
  reference only;
- architecture review findings F-001 through F-009 are resolved;
- the architecture is approved for promotion from `proposed` to `canonical`;
- derived material must not duplicate or redefine the architecture;
- Task 1 may begin after repository consistency checks confirm the promotion.

### Rationale

The architecture now provides the minimum stable rules required to define
future Engineering Capabilities without coupling them to agents, prompts,
models, platforms, or tools. Promotion provides one discoverable source of
truth and prevents Task 1 from inventing missing structural rules.

### Alternatives Considered

- **Retain `proposed` status:** rejected because the required findings are
  resolved and the follow-up review permits approval.
- **Keep the canonical definition under `docs/`:** rejected because repository
  governance defines `docs/` as derived documentation.
- **Redesign the architecture:** rejected because no unresolved finding
  requires substantive architectural change.
- **Create a new architecture governance role:** rejected because the existing
  IDE-BoK Steward role already owns coherence and is the closest established
  convention.

### Consequences

- Engineering Capability Architecture version 1.0 becomes the stable canonical
  baseline.
- The IDE-BoK Steward becomes accountable for architectural coherence, periodic
  review, impact assessment, and coordination of breaking changes.
- Capability Realizations, Skills, agents, prompts, tools, and platforms remain
  derived or supporting concerns and cannot redefine the architecture.
- Task 1 is unblocked after the consistency validation required by this
  decision passes.
- Future breaking changes require evidence, impact review, governance approval,
  migration guidance, version increment, and change-history updates.

### Affected Files

- `ide-bok/architecture/engineering-capability.md`
- `docs/architecture/engineering-capability.md`
- `docs/architecture/repository-map.md`
- `README.md`
- `governance/ownership-model.md`
- `governance/decision-log.md`

### Review Evidence

- `docs/architecture/reviews/engineering-capability-architecture-review.md`
- Task 0.1 validation confirming one authoritative definition and resolution of
  F-001 through F-009
- Follow-up review verdict: `APPROVE WITH MINOR CHANGES`

### Conditions for Future Changes

Changes to the canonical definition, qualification rules, Engineering
Capability Contract, typed relationship model, lifecycle, or ownership rules
must:

1. state the problem and supporting Evidence;
2. assess affected capabilities and repository references;
3. preserve single semantic ownership;
4. receive IDE-BoK Steward review and Repository Owner approval;
5. provide migration guidance for breaking changes;
6. increment the architecture version and update its change history.
