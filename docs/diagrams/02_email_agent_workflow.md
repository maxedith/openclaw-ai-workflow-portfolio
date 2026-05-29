# Enterprise Email Agent Workflow

This diagram shows how the Email Agent turns messy inbox activity into structured daily priorities and suggested actions.

```mermaid
flowchart TD
    A["Messy Inbox"]
    B["Normalize Messages"]
    C["Classify Domain and Intent"]
    D["Detect Required Actions"]
    E["Rank Priority"]
    F["Suppress Noise"]
    G["Suggest Reply and Label"]
    H["Generate Daily Brief"]
    I["Business User Review"]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
```

The `.mmd` file is kept as the editable source version: [02_email_agent_workflow.mmd](02_email_agent_workflow.mmd).

Back to [Diagrams](README.md).

