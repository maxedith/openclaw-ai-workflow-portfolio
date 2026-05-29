# OpenClaw Overall Architecture

This diagram shows OpenClaw as a local AI workflow operating layer. The Enterprise Email Agent is the main business case.

```mermaid
flowchart TD
    A["Business User"]
    B["OpenClaw Workflow Runtime"]
    C["Business Agents"]
    D["Enterprise Email Agent"]
    E["Office Agent"]
    F["Future Procurement Agent"]
    G["Future Meeting Agent"]
    H["Shared Context and Memory"]
    I["Structured Outputs"]
    J["Business Decision"]

    A --> B
    B --> C
    C --> D
    C --> E
    C --> F
    C --> G
    D --> H
    E --> H
    F --> H
    G --> H
    H --> I
    I --> J
```

The `.mmd` file is kept as the editable source version: [01_openclaw_architecture.mmd](01_openclaw_architecture.mmd).

Back to [Diagrams](README.md).

