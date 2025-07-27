# Concept Map: NeuroJazz Framework

This map shows how the core components of the NeuroJazz method connect to each other and where to find them in the repo.

---

## Core Nodes
- **Journaling Workflow** → [Playbook](docs/playbook.md)
- **Case Study** → [Full Narrative](case-study/openai-essay.md)
- **Research Threads** → [Index](research-threads/index.md)
- **Templates** → [Daily Log](templates/daily-log-template.md) | [THC Log](templates/thc-log-template.md)
- **Examples** → [Sample Log](examples/example-log.md) | [EF Transfer Map](examples/ef-transfer-map.md)

---

## Visual Diagram (Mermaid)
```mermaid
graph TD
    A[Journaling Workflow] --> B[Case Study]
    A --> C[Templates]
    A --> D[Examples]
    B --> E[Research Threads]
    C --> D
    D --> E
