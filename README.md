<div align="center">

# 👋 Hey, I'm Doyimmi3

[![Discord.js](https://img.shields.io/badge/Discord.js-v14-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.js.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-20+-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![ShardCloud](https://img.shields.io/badge/ShardCloud-Deployments-00C2FF?style=for-the-badge&logo=cloudflare&logoColor=white)](https://shardcloud.app/)

**Senior Discord Bot Engineer**  
*Building scalable, production-grade Discord bots with Discord.js v14 + TypeScript*

</div>

---

## 🧠 What I Build

- 🛰️ **Multi-shard Discord bots** for large-scale communities (100k+ users)
- 🧱 **Modular architectures** with clean separation and strong typing
- 🧪 **Production-ready** systems: logging, metrics, rate limits, error recovery
- ☁️ **ShardCloud deployments** with zero-downtime and environment separation

---

## 🛠 Tech Stack

| Category          | Technologies                                      |
|-------------------|---------------------------------------------------|
| **Core**          | Discord.js v14, Node.js 20+, TypeScript (strict) |
| **Data**          | PostgreSQL, Redis, Prisma ORM                    |
| **Infra**         | ShardCloud, Docker, PM2/systemd                  |
| **Queue**         | BullMQ, Redis Pub/Sub                            |
| **Quality**       | ESLint, Prettier, Husky, Vitest                  |
| **Observability** | Structured logging, health checks                |

---

## 🚀 Discord Bot Expertise

- **Slash commands** with full type-safety and auto-discovery
- **Shard-aware caching** and distributed state management
- Advanced **permission systems** and role modeling
- **Rate limit handling** with exponential backoff
- **i18n-ready** and multi-guild configuration
- **Developer experience** focused architecture

---

## 🧩 Architecture Patterns

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Discord.js    │───▶│   Application    │───▶│   Infrastructure│
│   (Adapters)    │    │   Layer (Domain) │    │   (DB/Cache)    │
└─────────────────┘    └──────────────────┘    └─────────────────┘
         ▲                       ▲                       ▲
         └───────────────────────┼───────────────────────┘
                                 │
                           Modular Commands & Events
```

**Key principles:**
- Commands, events, services → **decoupled and testable**
- Discord.js specifics → **confined to adapters**
- **Clear boundaries** between domain and infrastructure

---

## 📂 Upcoming Open Source

- 🧩 `discord-bot-template` – Production Discord.js v14 + TS starter
- 🛰️ `shardcloud-discord-starter` – Multi-shard deployment ready
- 🔐 `discord-config-kit` – Type-safe config & secrets management
- 📊 `discord-metrics` – Prometheus/Grafana metrics exporter

---

## 🌐 Let's Connect

[![Discord](https://img.shields.io/badge/Discord-DM%20me!-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/yourinvite)
[![Portfolio](https://img.shields.io/badge/Portfolio-Coming%20Soon-0077B5?style=for-the-badge&logo=behance&logoColor=white)](https://doyimmi3.com)
