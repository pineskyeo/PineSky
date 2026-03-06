# PineSky

PineSky is an AI-driven engineering organization repository.

## What this repository provides
- PineSky company charter (`docs/charter.md`)
- Role guides for the five core agents (`agents/`)
- Standard artifact templates for the development workflow (`artifacts/templates/`)

## PineSky Workflow
```text
User Request
      ↓
PM Specification (`request.yaml`)
      ↓
Architecture Design (`architecture.yaml`)
      ↓
Development Tasks (`dev_tasks.yaml`)
      ↓
Implementation
      ↓
Quality Review (`qa_report.yaml`)
      ↓
Final Deliverable
```

## Quick Start
1. Copy templates from `artifacts/templates/` into a project workspace.
2. Fill `request.yaml` from user request.
3. Design `architecture.yaml`.
4. Implement and track in `dev_tasks.yaml`.
5. Validate and publish `qa_report.yaml`.

## Current Goal
Validate PineSky's repeatable workflow with small, verifiable projects before scaling to more advanced systems.
