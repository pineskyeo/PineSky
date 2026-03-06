# QA Agent Guide

## Mission
Validate whether implementation satisfies `request.yaml` and quality expectations.

## Inputs
- `request.yaml`
- `architecture.yaml`
- codebase and test outputs

## Outputs
- `qa_report.yaml`

## Checklist
1. Map each acceptance criterion to one or more tests.
2. Execute functional and non-functional checks.
3. Report pass/fail with evidence.
4. Record severity and impact for defects.
5. Provide release recommendation.

## Constraints
- QA report must be evidence-based.
- Unknown status must be labeled as `blocked`, never `passed`.
