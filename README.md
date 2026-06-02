<div align="center">

<img src="https://omniroute.cloud/logo.png" alt="OmniRoute Logo" width="120" />

# OmniRoute

### Next-gen platform for Virtual Trucking Companies

[![Status](https://img.shields.io/badge/Status-Closed%20Beta-7C6FCD?style=for-the-badge)](https://omniroute.cloud)
[![Website](https://img.shields.io/badge/Website-omniroute.cloud-0A0A0F?style=for-the-badge&logo=firefox&logoColor=white)](https://omniroute.cloud)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/omniroute)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](./LICENSE)

**Automatic trip tracking for ETS2 & ATS Virtual Trucking Companies — no manual reporting, ever.**

[🌐 Website](https://omniroute.cloud) · [📋 Changelog](#-changelog) · [🗺️ Roadmap](#️-roadmap)

</div>

---

## 🚛 What is OmniRoute?

OmniRoute is a platform built for Virtual Trucking Companies (VTCs) in **Euro Truck Simulator 2** and **American Truck Simulator**. Instead of drivers manually submitting trip reports, OmniRoute reads telemetry data directly from the game in real-time — the platform knows when you started, where you went, and when you delivered.

It supports both **singleplayer** and **TruckersMP multiplayer**, handles edge cases like ferry crossings, F7 teleports and game saves, and provides company managers with a full dashboard to manage their fleet.

> This repository is a **public showcase**. The full source code is proprietary and not publicly available.

---

## ✨ Key Features

<table>
<tr>
<td width="50%" valign="top">

### 🖥️ Desktop Client (Tauri 2)
- Automatic trip detection via **SCS SDK shared memory**
- Real-time telemetry: position, speed, fuel, cargo damage
- Smart state machine: Loading → Active → Delivered
- Handles ferry crossings, F7 teleports, save/loads
- Anti-cheat: suspicious job detection
- Encrypted local storage (AES-256-GCM)
- Suspend & resume on game close / profile switch

</td>
<td width="50%" valign="top">

### 🌐 Web Platform (Next.js)
- Full VTC management dashboard
- Company ranks, badges, webhooks
- Driver profiles & activity tracking
- Discord OAuth2 integration
- TruckersMP & Steam account linking
- Interactive route map (MapLibre GL)
- Polish 🇵🇱 & English 🇬🇧 localization

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ API (Fastify 4)
- RESTful API with cookie-based sessions
- Admin panel & system roles
- Discord bot integration via webhook
- Company settings: 8 configuration tabs
- Cloudflare R2 for media storage
- BetterStack status monitoring

</td>
<td width="50%" valign="top">

### 🤖 Discord Bot (Discord.js v14)
- VTC notifications & announcements
- Trip delivery alerts
- Company leaderboards
- Role sync with web platform
- Webhook-driven event system

</td>
</tr>
</table>

---

## 🏗️ Architecture

OmniRoute is a **pnpm monorepo** powered by Turborepo, consisting of four apps and a shared packages layer:

```
omniroute/
├── apps/
│   ├── web/          # Next.js 14 — web platform (App Router, next-intl)
│   ├── api/          # Fastify 4 — REST API
│   ├── desktop/      # Tauri 2 — desktop client (Rust + React)
│   └── bot/          # Discord.js v14 — Discord bot
└── packages/
    └── database/     # Prisma 5 + PostgreSQL 16 (shared schema)
```

### Desktop Telemetry Pipeline

```
ETS2/ATS Game
     │
     │  SCS SDK Plugin (shared memory)
     ▼
 Tauri Desktop App (Rust)
     │
     ├── TelemetryReader (100ms polling)
     ├── StateMachine (Idle → Loading → Active → Ending)
     ├── DistanceIntegrator (world position, teleport guard)
     ├── DeliveryClassifier (SP vs TruckersMP)
     └── RouteRecorder (GPS points → RDP simplification)
     │
     │  HTTP (submit + route)
     ▼
  Fastify API → PostgreSQL
```

---

## 🛠️ Tech Stack

<table>
<tr>
<td valign="top" width="25%">

### Frontend
![Next JS](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

</td>
<td valign="top" width="25%">

### Backend
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)

</td>
<td valign="top" width="25%">

### Desktop
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)

</td>
<td valign="top" width="25%">

### Infrastructure
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-D70A53?style=flat-square&logo=debian&logoColor=white)
![OVH](https://img.shields.io/badge/OVH-123F6D?style=flat-square&logo=ovh)

</td>
</tr>
</table>

---

## 🗺️ Roadmap

| Status | Feature |
|--------|---------|
| ✅ Done | Desktop client (Tauri 2) — telemetry, job tracking, anti-cheat |
| ✅ Done | Web platform — VTC management, ranks, webhooks, badges |
| ✅ Done | API — sessions, Discord OAuth2, admin panel |
| ✅ Done | Discord bot — notifications, leaderboards |
| ✅ Done | Legal pages (GDPR/RODO compliant) |
| 🔄 In Progress | Interactive game map (ETS2 + ProMods, MapLibre GL) |
| 🔄 In Progress | Route GPS tracking & visualization |
| 🔄 In Progress | Anti-cheat v2 (position-based suspicion score) |
| 📅 Planned | Closed Beta — Q3 2026 |
| 📅 Planned | Public launch — 2026 |

---

## 📋 Changelog

### v0.9 — Pre-Beta *(current)*
- Desktop client ~90% complete
- Anti-cheat: suspicious job detection
- Encrypted local storage (AES-256-GCM, Windows DPAPI)
- Job suspend/resume system
- Admin panel + SystemRole
- Company settings UI (8 tabs), country flags, heartbeat
- Discord OAuth2 full flow
- Legal pages (Terms of Service, Privacy Policy)
- Registration disabled (closed beta screen)

### v0.8
- Auth migrated from JWT to httpOnly cookie sessions
- Prisma schema: CompanyRank, CompanyWebhook, CompanyBadge, CompanyNameHistory
- Discord/Steam/TruckersMP IDs immutable once set
- SEO overhaul: structured data, sitemap, robots.txt, canonical fix

---

## 🌍 Supported Games

| Game | Singleplayer | TruckersMP | ProMods |
|------|:---:|:---:|:---:|
| Euro Truck Simulator 2 | ✅ | ✅ | 🔄 |
| American Truck Simulator | ✅ | ✅ | — |

---

## 📸 Screenshots

> Screenshots coming with the closed beta release.

---

## 🤝 Community

OmniRoute is built for the Polish VTC community but supports English from day one.

- 🌐 **Website:** [omniroute.cloud](https://omniroute.cloud)
- 💬 **Discord:** coming soon
- 📧 **Contact:** [omniroute.cloud/contact](https://omniroute.cloud/contact)

---

## 📄 License

OmniRoute is **proprietary software**. This repository exists as a public showcase only.  
All rights reserved © 2026 OmniRoute / KetusDev.

---

<div align="center">

Built with ❤️ by [KetusDev](https://github.com/KetusDev) · [ketus.dev](https://ketus.dev)

</div>
