---
description: "Why GitBook sits before LMS and source repositories."
icon: layer-group
---

# Why this layer

```mermaid
flowchart LR
    Docs[Technical writer docs] --> Hub[GitBook product hub]
    Files[PDFs, PPTs, SharePoint] --> Hub
    Hub --> Employee[Employees]
    Hub --> External[Partners and contractors]
    Hub --> LMS[Oracle LMS]
    Feedback[Comments, feedback, AI gaps] --> Hub
```

| System | Good at | GitBook adds |
| --- | --- | --- |
| SharePoint | File storage | Curated pages and search |
| PDFs and PPTs | Formal collateral | Maintained answers with source links |
| Oracle LMS | Deep training | Pre-learning knowledge and external access |
| Product teams | Accuracy | Review comments and change requests |
