# FrostWeb Studios

**Independent game studio and Unreal Engine plugin developer.**

We build multiplayer game systems, modular UE5 plugins, and the backend infrastructure to support them — from authentication to live services.

---

## About

FrostWeb Studios, LLC is a U.S.-based indie studio specializing in Unreal Engine 5 and full-stack multiplayer architecture. We develop reusable game plugins, scalable backend services, and a slate of titles across the MMO, MOBA, survival, and space-sim genres.

---

## Games

### Ayndora Survival *(flagship — alpha)*
A stylized co-op MMORPG inspired by RuneScape, World of Warcraft, and New World. 15 RuneScape-style skills, classless GAS combat, guild-controlled cities, party-based exploration, and a full-loot PvP zone.

### Ayndora MOBA
A classless 5v5 MOBA set in the same world as Ayndora Survival. Build-defining gear and abilities replace fixed champions; matches resolve through skill loadouts and lane macro, not picks/bans.

### MuricaAF
A modern-military survival FPS with community-hosted persistent shards. Single MetaHuman body, hybrid GAS movement, and a server-admin toolkit for community operators.

### TerraVox
A voxel survival crafter using marching cubes, dimension servers, a Steam Workshop mod SDK, and GAS-driven progression.

### Cradlefall
An EVE-feel single-shard space sim — three factions descended from three Arks, jump-gate-connected systems, real-time skill training, and player-driven industry.

---

## UE5 Plugins

Standalone, production-ready plugins built for our own games and available to the community. All C++ with full Blueprint support, replicated, and designed for zero coupling between systems.

| Plugin | Description |
|---|---|
| **FWGASSystem** | Extended Gameplay Ability System framework with modular actor base classes |
| **FWOnlineAuth** | OAuth/JWT identity client (login, register, MFA, refresh) |
| **FWPartySystem** | Cross-level party management via network beacons with chat integration |
| **FWGuildSystem** | Guild management with ranks, permissions, and HTTP API backend |
| **FWChatSystem** | Multi-channel MMO chat over Socket.IO with command parsing and whispers |
| **FWQuestSystem** | Data-driven quests with task graphs, party sharing, and compact replication |
| **FWInventorySystem** | Inventory and equipment with seed-based RNG items, augmentation, and set bonuses |
| **FWMarketSystem** | Hybrid Grand-Exchange-style auction house with VWAP pricing and anti-manipulation |
| **FWSkillSystem** | RuneScape-style skill progression with XP curves and GAS attribute binding |
| **FWCustomizationSystem** | Data-driven character appearance with minimal replication footprint |
| **FWFactionSystem** | Faction reputation, attitude resolution, and AI team integration |
| **FWDialogueSystem** | Branching dialogue trees with conditions and actions |
| **FWAISystem** | Threat tables, leashing, patrol, BT nodes, and spawn tables |
| **FWAchievementSystem** | Tiered achievements with platform and backend sync |
| **FWAgonesIntegration** | Agones SDK bridge for game-server fleet lifecycle on Kubernetes |
| **FWSQLite** | Embedded SQLite driver for offline/local-cache scenarios |

---

## Platform

Our services run on Google Cloud Platform and ship through a custom CI/CD stack:

- **Unreal Engine 5** — C++ clients with 16 first-party plugins
- **Go** — Game APIs (Ayndora, MOBA, Murica, Market, Watchfire)
- **NestJS** — Identity, CMS, admin, store
- **Next.js** — Web frontends
- **React Native / Expo** — Mobile companion app
- **Electron** — Desktop launcher
- **PostgreSQL** — Single database, schema-per-service isolation
- **GKE + Agones** — Dedicated game-server fleets
- **Horde** — In-house Unreal build / CI / artifact pipeline
- **Perforce** — Engine, content, and plugin source control

---

## Links

- [frostweb.studio](https://frostweb.studio) — Studio website
- [X / Twitter](https://x.com/FrostWebStudios)
- [Discord](https://discord.gg/nPECYdzaBm)
- contact@frostweb.studio — Plugin support, collaborations, commissions

---

## Security

Please report security vulnerabilities responsibly. See [SECURITY.md](https://github.com/FrostWeb-Studios/.github/blob/main/SECURITY.md) for our disclosure policy.

---

&copy; FrostWeb Studios, LLC
