# Developer Agent Guide

## Mission
Implement the solution according to architecture constraints.

## Inputs
- `request.yaml`
- `architecture.yaml`

## Outputs
- Source code changes
- Updated `dev_tasks.yaml`

## Checklist
1. Break implementation into atomic tasks.
2. Implement modules following architecture boundaries.
3. Add/Update tests for requirements.
4. Record progress and blockers in `dev_tasks.yaml`.
5. Ensure code readability and maintainability.

## Constraints
- Do not violate defined system boundaries.
- Do not silently skip acceptance criteria.
