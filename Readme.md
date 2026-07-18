# Aincrad

> Transforming an old Lenovo IdeaPad into a modern self-hosted Linux homelab.

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Ubuntu](https://img.shields.io/badge/OS-Ubuntu%20Server-E95420?logo=ubuntu)
![Learning](https://img.shields.io/badge/Purpose-Learning-blue)

---

## About

Aincrad is my personal homelab built on an old Lenovo IdeaPad that would have otherwise been retired.

Rather than buying new hardware, I decided to turn an aging laptop into a secure Linux server to learn:

- Linux system administration
- Networking
- SSH
- Docker
- Self-hosting
- Automation
- Infrastructure

This repository documents the entire journey—from a fresh Ubuntu installation to a fully featured home server.

---

## Hardware

| Component | Specification |
|-----------|---------------|
| Device | Lenovo IdeaPad 3 15IIL05 |
| CPU | Intel Core i5-1035G1 |
| RAM | 4 GB |
| Storage | 512 GB SSD |
| Operating System | Ubuntu Server LTS |

---

## Current Progress

### Completed

- Ubuntu Server installation
- Wi-Fi configuration
- SSH server
- Passwordless SSH
- Tailscale remote access
- NetworkManager setup
- Quality-of-life tools
  - btop
  - tmux
  - git
  - tree
  - vim
  - nano
  - curl
  - wget

### In Progress

- Documentation

### Planned

- Docker
- Docker Compose
- Homepage Dashboard
- Portainer
- File Browser
- Uptime Kuma
- Reverse Proxy
- Automated Backups
- Monitoring
- Personal Portfolio Hosting

---

## Philosophy

This project isn't about installing as many services as possible.

Every addition should either:

- solve a real problem,
- teach a valuable skill,
- or improve the server in a meaningful way.

---

## Roadmap

- [x] Ubuntu Server
- [x] Networking
- [x] SSH
- [x] Passwordless SSH
- [x] Tailscale
- [x] Quality-of-life setup
- [ ] Docker
- [ ] Docker Compose
- [ ] Homepage
- [ ] Portainer
- [ ] Monitoring
- [ ] Self-hosted Applications
- [ ] Reverse Proxy
- [ ] Automated Backups

---

## Repository Structure

```
aincrad/
├── docs/
├── diagrams/
├── screenshots/
├── README.md
├── CHANGELOG.md
├── LICENSE
└── .gitignore
```

Each major milestone is documented with:
- Architecture diagrams
- Screenshots
- Lessons learned
- Changelog entries
- Version tags

## Project Status

This project is actively being developed and documented as I continue learning Linux and self-hosting.
