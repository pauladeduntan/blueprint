# KinCart — blueprint (research artefacts)

KinCart is a mobile-first household coordination system designed to reduce mental load and preserve emotional safety through shared visibility, calm defaults, and system-owned language. It is not a task manager, accounting tool, or enforcement mechanism.

## Governance (binding decisions live here)

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

This blueprint repository contains the frozen product constraints (domain language, invariants, flows).
When something here becomes **committed truth**, it should be backed by a governance decision record.

## Status (research-only)

KinCart is a **non-commercial research artefact**. This repository documents research framing, design invariants, and prototype evidence. It is **not** a product launch, a service offering, or a commercial operation.

**Mechanics policy:** Implementation details that would enable cloning (schemas/RLS/RPC specifics, deploy steps, paste-ready backend scripts) are intentionally **not** published in public.

**Future pathway (hypothetical only):** Any future commercialization would require explicit conditions (institutional approval, legal/immigration compliance, ethics posture, and funding). Until those conditions are met, KinCart remains **research-only**.

**Start here:** [`[START_HERE.md](https://github.com/pauladeduntan/blueprint/blob/main/START_HERE.md)

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
