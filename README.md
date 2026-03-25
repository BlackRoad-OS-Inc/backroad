<!-- BlackRoad SEO Enhanced -->

# uackroad

> Part of **[BlackRoad OS](https://blackroad.io)** — Sovereign Computing for Everyone

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad-OS-ff1d6c?style=for-the-badge)](https://blackroad.io)
[![BlackRoad-OS-Inc](https://img.shields.io/badge/Org-BlackRoad-OS-Inc-2979ff?style=for-the-badge)](https://github.com/BlackRoad-OS-Inc)

**uackroad** is part of the **BlackRoad OS** ecosystem — a sovereign, distributed operating system built on edge computing, local AI, and mesh networking by **BlackRoad OS, Inc.**

### BlackRoad Ecosystem
| Org | Focus |
|---|---|
| [BlackRoad OS](https://github.com/BlackRoad-OS) | Core platform |
| [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc) | Corporate |
| [BlackRoad AI](https://github.com/BlackRoad-AI) | AI/ML |
| [BlackRoad Hardware](https://github.com/BlackRoad-Hardware) | Edge hardware |
| [BlackRoad Security](https://github.com/BlackRoad-Security) | Cybersecurity |
| [BlackRoad Quantum](https://github.com/BlackRoad-Quantum) | Quantum computing |
| [BlackRoad Agents](https://github.com/BlackRoad-Agents) | AI agents |
| [BlackRoad Network](https://github.com/BlackRoad-Network) | Mesh networking |

**Website**: [blackroad.io](https://blackroad.io) | **Chat**: [chat.blackroad.io](https://chat.blackroad.io) | **Search**: [search.blackroad.io](https://search.blackroad.io)

---


> BackRoad — Sovereign container management. BlackRoad fork of Portainer. Fleet-wide Docker orchestration.

Part of the [BlackRoad OS](https://blackroad.io) ecosystem — [BlackRoad-OS-Inc](https://github.com/BlackRoad-OS-Inc)

---

# BackRoad — BlackRoad Road Fleet

> **Sovereign container management.** Fork of [Portainer](https://github.com/portainer/portainer).

---

**BackRoad** is BlackRoad's sovereign fork of Portainer — manage Docker containers, stacks, and services across the entire Pi fleet from one dashboard.

## What's Different

- **Fleet-wide view** — see all containers across Alice, Cecilia, Octavia, Aria, Lucidia
- **BlackRoad branding** — hot pink (#FF1D6C) theme, Road Fleet identity
- **Pre-configured stacks** — Ollama, NATS, MinIO, Qdrant, Redis one-click deploy
- **Sovereign-first** — no Portainer Cloud, no telemetry, no external dependencies

## Quick Start

```bash
docker run -d -p 9443:9443 --name backroad \
  --restart=always \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v backroad_data:/data \
  blackroad/backroad:latest
```

## Fleet Endpoints

| Node | Docker | BackRoad UI |
|------|--------|-------------|
| Octavia | :2375 | :9443 |
| Alice | :2375 | — |
| Cecilia | :2375 | — |

## Upstream

Forked from [portainer/portainer](https://github.com/portainer/portainer) (zlib License upstream).
All BlackRoad modifications are proprietary.

---

**BlackRoad OS, Inc.** — Pave Tomorrow.

*Proprietary. All rights reserved.*
