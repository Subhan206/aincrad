# Aincrad Architecture

## Foundation (v0.1.0)

```mermaid
flowchart TB

    User["💻 Royz-Laptop"]
    TS["🌐 Tailscale"]
    Server["🖥️ Aincrad"]

    User -->|SSH| TS
    TS --> Server

    Server --> SSH["OpenSSH"]
    Server --> UFW["UFW Firewall"]
    Server --> NM["NetworkManager"]
    Server --> Tools["QoL Tools"]
```