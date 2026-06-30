---
description: "Review workflow for Vista Flight Display."
icon: comments
---

# Review workflow

| Role | Permissions in the demo |
| --- | --- |
| Instructional designer | Creator or editor |
| Product reviewer | Reviewer |
| Product team lead | Admin or reviewer |
| External partner | Viewer |

```mermaid
sequenceDiagram
    participant ID as Instructional Designer
    participant PT as Product Team
    participant GB as GitBook
    ID->>GB: Draft page update
    ID->>PT: Request review
    PT-->>GB: Comment or approve
    ID->>GB: Apply feedback
    GB-->>Readers: Publish approved page
```
