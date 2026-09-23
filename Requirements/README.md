# Requirements Management

This directory contains the working requirements-management artifacts for AMV-01.

The requirements hierarchy is planned as:

```text
Stakeholder Needs
      ↓
Stakeholder Requirements (STK-REQ)
      ↓
System Requirements (SYS-REQ)
      ↓
Architecture / Allocation
      ↓
Hardware Requirements (HW-REQ)
Software Requirements (SW-REQ)
Interface Requirements (INT-REQ)
      ↓
Verification Test Cases (TC)
```

## Identifier Scheme

- `NEED-XXX` — stakeholder need
- `STK-REQ-XXX` — stakeholder requirement
- `SYS-REQ-XXX` — system requirement
- `HW-REQ-XXX` — hardware requirement
- `SW-REQ-XXX` — software requirement
- `INT-REQ-XXX` — interface requirement
- `TC-XXX` — test case
- `CR-XXX` — change request

## Rules

Requirements should be necessary, clear, atomic, feasible, consistent, traceable, and verifiable. Requirements will not be invented simply to justify a component already selected.

IBM DOORS / DOORS Next may later be used to manage attributes, links, views, baselines, traceability, and engineering changes when suitable access is available.
