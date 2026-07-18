# Network Topology

## Current Network

```mermaid
flowchart LR

    Laptop["Royz-Laptop"]
    Tail["Tailscale"]
    Aincrad["Aincrad"]

    Laptop --> Tail
    Tail --> Aincrad
```