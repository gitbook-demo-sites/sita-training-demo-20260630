---
description: "Stakeholder review and feedback workflow."
icon: comments
---

# Review and feedback flow

```mermaid
stateDiagram-v2
    [*] --> Draft
    Draft --> Review
    Review --> Draft: requested edits
    Review --> Approved
    Approved --> Published
    Published --> Feedback
    Feedback --> Draft
```

{% stepper %}
{% step %}
## Reader flags a gap

A reader leaves page feedback or a reviewer comments on a draft.
{% endstep %}
{% step %}
## Instructional designer applies feedback

The page owner updates language, visuals or structure.
{% endstep %}
{% step %}
## Product team approves

A reviewer validates the technical accuracy before publishing.
{% endstep %}
{% endstepper %}
