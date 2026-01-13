# KinCart — blueprint (research artefacts)

KinCart is a **research-led coordination artefact** for studying how shared intent is made visible in households without drifting into enforcement, surveillance, or judgement. It takes the form of a mobile-first prototype, but it is not a task manager, accounting tool, or behavioural enforcement mechanism.

The artefact is intentionally designed around explicit interaction invariants (e.g., system-owned language, reversibility by default, boundary clarity) so that breakdown, repair, and interpretation can be studied as coordination work rather than optimised task execution.

## Research Governance (binding decisions live here)

Research governance in KinCart functions as a methodological control mechanism, not an organisational or engineering process. Decisions are recorded to prevent interpretive drift (e.g., accidental introduction of enforcement or judgement cues) and to preserve invariant integrity across iterations of the research artefact during study.

This repository is governed by the KinCart governance repo:
- Decisions become truth only when committed in governance.
- Blueprint changes should link back to the governing decision record.
- Public artefacts avoid implementation recipes by design.

Binding decisions and drift-prevention gates are recorded in the **governance** repository:

- Governance repo: https://github.com/pauladeduntan/governance
- Decision register: https://github.com/pauladeduntan/governance/blob/main/decision-register.md
- Decision records: https://github.com/pauladeduntan/governance/tree/main/decisions
- Action gates: https://github.com/pauladeduntan/governance/tree/main/action-gates

## For supervisors/reviewers
- [Research contribution (1 page)](./appendix/research-contribution.md)

This blueprint repository contains the frozen research artefact constraints (domain language, invariants, and narrative system flows).
When something here becomes **committed truth**, it should be backed by a governance decision record.

## Status (research-only)

KinCart is a **non-commercial research artefact**. This repository documents research framing, design invariants, and prototype evidence. It is **not** a product launch, a service offering, or a commercial operation.

**Mechanics policy:** Implementation details that would enable cloning (schemas/RLS/RPC specifics, deploy steps, paste-ready backend scripts) are intentionally **not** published in public.

Any use of KinCart beyond its role as a research artefact would require separate ethical review under the relevant institutional framework. Until such conditions exist, KinCart is treated exclusively as a research probe and documented accordingly.

**Start here:** [START_HERE.md](https://github.com/pauladeduntan/blueprint/blob/main/START_HERE.md)

## What this repository contains
- A frozen research blueprint: domain language, invariants, and narrative system flows.
- Reference appendices used to keep the prototype coherent and failure-aware.

## What is intentionally not published
Implementation mechanics are intentionally not included in this public repository (e.g., schema/RLS/RPC specifics, operational scripts, “how to build” steps). This is a non-commercial research record, not a delivery tracker.

## Core files
- `domain-language.md`
- `invariants.md`
- `product-definition.md`
- `system-flows.md`
- `appendix/`
