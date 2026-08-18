# Contributing to PAICHAI NEXUS

PAICHAI NEXUS projects are interdisciplinary by design. Contributions should be technically clear, domain-aware, reviewable, and documented.

## Before You Start

1. Read the project README and current status.
2. Confirm the problem, scope, and owner of the task.
3. Check related Issues and Pull Requests.
4. Define how the change will be verified.

## Branch Naming

```text
feature/<short-description>
fix/<short-description>
docs/<short-description>
research/<short-description>
experiment/<short-description>
```

Examples:

```text
feature/seedling-detection-pipeline
research/growth-metric-baseline
docs/update-validation-plan
fix/camera-reconnect
```

## Commit Style

Prefer small, understandable commits.

```text
feat: add seedling image preprocessing
fix: handle camera reconnect failure
docs: document validation criteria
test: add growth metric regression test
research: add baseline experiment results
```

## Pull Requests

Every PR should explain:

- **What changed?**
- **Why is it needed?**
- **How was it verified?**
- **What remains unverified?**
- **Are there screenshots, logs, datasets, or experiment results?**

Avoid merging work whose status cannot be explained.

## Evidence Rule

Use precise status language:

```text
Implemented
Demonstrated
Validated
Field Verified
```

Do not use these terms interchangeably.

## Interdisciplinary Review

When a change affects domain assumptions, request review from the relevant domain contributor in addition to technical review.

Examples:

- agriculture / horticulture assumptions
- healthcare workflows
- nutrition or food safety
- civil / geological interpretation
- human-subject or user-research design

## Documentation

Significant decisions should remain discoverable in:

- README
- Issues
- Pull Requests
- `/docs`
- experiment notes
- architecture or research-design documents
