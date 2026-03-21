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
