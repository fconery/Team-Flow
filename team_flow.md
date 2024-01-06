```mermaid
---
Title: Scanning and Validation Flow
---
flowchart TD
    A{{Enumeration: change?}} -- YES --> C
    A -- NO --> A
    C{{Triage: IOC?}} -- YES --> E
    C -- NO --> G
    E[Intel] --> F
    F[IOC Validation] --> G
    G[Report] ---> A
    











