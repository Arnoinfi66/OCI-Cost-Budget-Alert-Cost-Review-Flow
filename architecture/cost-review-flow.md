# Cost Review Flow

This diagram shows a simple OCI cost review flow.

```mermaid
flowchart TD
    A[OCI Usage and Cost Data] --> B[Cost Analysis]
    B --> C[Review Cost Trend]
    C --> D[Group by Service or Compartment]
    D --> E[Identify Spend Area]
    E --> F[Review Budget Need]
    F --> G[Define Follow-up Action]
```

Cost review starts with visibility.

Cost Analysis helps review usage and cost information so the spend can be understood by service, compartment, or other available filters.

---

## What I Understood

My main understanding is that cost review should start with the cost trend.
Before creating or changing a budget, the spend area should be reviewed. The review should make clear where the cost is coming from and whether a budget or alert is needed.
