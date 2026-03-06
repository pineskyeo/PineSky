# PineSky Agent System

This directory defines execution guides for the five core PineSky roles.

## Roles
- `supervisor.md`
- `pm.md`
- `architect.md`
- `developer.md`
- `qa.md`

## Usage Rule
Each agent should only perform actions inside its responsibility scope and should consume the previous stage artifact before producing the next stage artifact.

## Artifact Handoff
1. PM reads user request and produces `request.yaml`.
2. Architect reads `request.yaml` and produces `architecture.yaml`.
3. Developer reads `architecture.yaml` and produces implementation + `dev_tasks.yaml` progress updates.
4. QA reads `request.yaml`, `architecture.yaml`, and implementation to produce `qa_report.yaml`.
5. Supervisor validates completion and prepares final delivery summary.
