# FrostWeb Studios

**Independent game studio and Unreal Engine plugin developer.**

We build multiplayer games, modular UE5 plugins, and the online services behind them — from accounts and authentication to stores, chat and dedicated servers.

---

## About

FrostWeb Studios, LLC is a U.S.-based indie studio working in Unreal Engine 5 and full-stack multiplayer architecture. We develop our own games, a set of reusable game plugins, and the FrostWeb account platform that ties them together.

---

## Games

### AyndoraMMO
A high-fantasy MMORPG built on skills rather than classes. Players train combat, gathering, crafting and utility skill lines, fight with GAS-driven abilities, join parties and guilds, trade on a player-driven market, and take on dungeons, raids and an open full-loot PvP zone.

### MuricaAF
Third-person persistent-world zombie survival in a post-apocalyptic USA, on community-hosted shards. A seasonal Drift of infection moves across the map, condemning settled districts and reopening others, so the world never stands still.

---

## UE5 Plugins

Plugins built for our own games. All C++ with Blueprint support, replicated, and designed as an optional set: no plugin forces another one on.

| Plugin | Description |
|---|---|
| **FWGASSystem** | Gameplay Ability System framework with modular actor base classes |
| **FWOnlineAuth** | FrostWeb account client: login, register, MFA, token refresh and auth UI |
| **FWPartySystem** | Beacon-based parties that persist across level transfers, with chat integration |
| **FWGuildSystem** | Guilds with ranks, permissions, invitations and an HTTP API backend |
| **FWChatSystem** | Multi-channel chat over Socket.IO with party support |
| **FWQuestSystem** | Data-driven quests with instanced tasks, party sharing and daily/weekly resets |
| **FWInventorySystem** | Inventory and equipment with random affixes, augmentation and database serialization |
| **FWMarketSystem** | Player auction house with listings, buy orders, guide prices and price history |
| **FWSkillSystem** | Skill progression with XP curves, levelling and skill-gated content |
| **FWCustomizationSystem** | Data-driven character appearance with unlock tracking |
| **FWFactionSystem** | Faction reputation with AI integration and replication |
| **FWDialogueSystem** | Branching dialogue trees with conditions and actions |
| **FWAISystem** | NPC behaviour: threat tables, leashing, patrol and spawning |
| **FWAchievementSystem** | Tiered achievements with progress tracking and backend sync |
| **FWAgonesIntegration** | Agones SDK bridge for dedicated-server lifecycle |
| **FWSQLite** | SQLite wrapper with a simple Execute/Query API |

Plugin documentation: [FrostWeb-Studios/docs](https://github.com/FrostWeb-Studios/docs)

---

## Platform

- **Unreal Engine 5** — C++ games and the 16 FW plugins above
- **Go** — Game APIs (Ayndora, MuricaAF, market)
- **NestJS** — Identity, CMS, store and support services
- **Next.js** — Studio site, store, support centre and player portals
- **Electron + React** — FrostLauncher, the desktop launcher
- **Kotlin Multiplatform + Compose** — The native FrostWeb mobile app (Android first): authenticator, friends and news
- **Discourse** — Community forums with FrostWeb chat built in
- **PostgreSQL** — Schema-per-service isolation on Google Cloud
- **Google Cloud Run + Cloudflare** — Service hosting and edge
- **Docker / Agones** — Dedicated game servers
- **Horde** — Unreal build and CI pipeline
- **Perforce** — Engine, content and plugin source control

---

## Links

- [frostweb.studio](https://frostweb.studio) — Studio website
- [X / Twitter](https://x.com/FrostWebStudios)
- [Discord](https://discord.gg/nPECYdzaBm)
- contact@frostweb.studio — Plugin support and collaborations

---

## Security

Please report security vulnerabilities responsibly. See [SECURITY.md](https://github.com/FrostWeb-Studios/.github/blob/master/SECURITY.md) for our disclosure policy.

---

&copy; FrostWeb Studios, LLC
