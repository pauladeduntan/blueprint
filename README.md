# KinCart: Blueprint (Research Artefact)

KinCart is a **non-commercial research artefact** for studying how shared intent is made visible in Households without drifting into enforcement, surveillance, or judgement. It takes the form of a mobile-first prototype, but it is not a task manager, accounting tool, or behavioural enforcement mechanism.

The artefact is intentionally designed around explicit interaction invariants (system-owned language, reversibility by default, and boundary clarity) so that breakdown, repair, and interpretation can be studied as coordination work rather than optimised task execution. **Handoff Items** are treated as **High-Stakes** coordination surfaces to amplify blame risk and reveal breakdown and repair dynamics without introducing reminders or pressure.

Activity is treated as an immutable, read-only record of shared intent and must not become a performance feed or a notification centre. Actor names may be shown for active Members, but Activity must not support per-person views, counts, sorting, grouping, filtering, or any performance-like interpretation. When membership ends, historical entries must immediately re-render the actor as “Former Member” by default.

## Research Governance (Binding Decisions Live Here)

Research governance in KinCart functions as a methodological control mechanism, not an organisational or engineering process. Decisions are recorded to prevent interpretive drift (for example, accidental introduction of enforcement or judgement cues) and to preserve invariant integrity across iterations of the research artefact during study.

This blueprint repository is governed by the KinCart governance repository:

- Decisions become truth only when committed in governance.
- Blueprint changes should link back to the governing decision record.
- Public artefacts avoid implementation recipes by design.

Binding decisions and drift-prevention gates are recorded in the governance repository:

- [Governance Repository](https://github.com/pauladeduntan/governance)
- [Decision Register](https://github.com/pauladeduntan/governance/blob/main/decision-register.md)
- [Decision Records](https://github.com/pauladeduntan/governance/tree/main/decisions)
- [Action Gates](https://github.com/pauladeduntan/governance/tree/main/action-gates)

## For Supervisors and Reviewers

- [Research Contribution (One Page)](./appendix/research-contribution.md)
- [Domain Language](./domain-language.md)
- [Invariants](./invariants.md)
- [System Flows (Current Research Prototype)](./system-flows.md)

This repository contains frozen research artefact constraints (Domain Language, Invariants, and narrative System Flows). When something here becomes committed truth, it should be backed by a governance decision record.

## Status (Research-Only)

KinCart is a **non-commercial research artefact**. This repository documents research framing, design invariants, and prototype materials. It is not a product launch, a service offering, or a commercial operation.

**Mechanics Policy:** Implementation details that would enable cloning are intentionally not published in public.

Any use of KinCart beyond its role as a research artefact would require separate ethical review under the relevant institutional framework. Until such conditions exist, KinCart is treated exclusively as a research probe and documented accordingly.

Start here: [START_HERE.md](./START_HERE.md)

## What This Repository Contains

- A frozen research blueprint: Domain Language, Invariants, and narrative System Flows.
- Reference appendices used to keep the prototype coherent and failure-aware.

## What is Intentionally not Published

Implementation mechanics are intentionally not included in this public repository (for example, operational scripts, and build instructions). This is a non-commercial research record, not a delivery tracker.

## Core Files

- `domain-language.md`
- `invariants.md`
- `artefact-definition.md`
- `system-flows.md`
- `appendix/`
