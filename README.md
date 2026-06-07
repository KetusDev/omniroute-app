<div align="center">

# OmniRoute

### Next-gen platform for Virtual Trucking Companies

[![Status](https://img.shields.io/badge/Status-Closed%20Beta-7C6FCD?style=for-the-badge)](https://omniroute.cloud)
[![Website](https://img.shields.io/badge/Website-omniroute.cloud-0A0A0F?style=for-the-badge&logo=firefox&logoColor=white)](https://omniroute.cloud)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.omniroute.cloud)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](./LICENSE)

**Automatic trip tracking for ETS2 & ATS Virtual Trucking Companies — no manual reporting, ever.**

[🌐 Website](https://omniroute.cloud) · [💬 Discord](https://discord.omniroute.cloud) · [📋 Changelog](./CHANGELOG) · [🗺️ Roadmap](#️-roadmap)

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
- Smart state machine: Loading → Active → Completing → Delivered
- Handles ferry crossings, F7 teleports, save/loads gracefully
- Anti-cheat: position-based suspicion score
- Encrypted local storage (AES-256-GCM + Windows DPAPI)
- Suspend & resume on game close / profile switch
- NSIS/MSI installer with auto-updater

</td>
<td width="50%" valign="top">

### 🌐 Web Platform (Next.js)
- Full VTC management dashboard
- Company ranks, badges, webhooks, name history
- Driver profiles, public pages & activity tracking
- Discord OAuth2 + Steam + TruckersMP account linking
- Invitation & application system
- Interactive game map with route visualization
- Economy dashboard with PDF/CSV export
- Polish 🇵🇱 & English 🇬🇧 localization

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ API (Fastify 4)
- RESTful API with httpOnly cookie sessions
- Role hierarchy: FOUNDER → MODERATOR → SUPPORT → USER
- Discord-gated registration with role verification
- Discord webhook dispatcher (job completions, member events)
- Redis for rate limiting, stats cache, JWT blacklist
- Cloudflare Turnstile enforcement
- BetterStack status monitoring

</td>
<td width="50%" valign="top">

### 🤖 Discord Bot (Discord.js v14)
- Verification system with two-step embed panel
- Country & language role assignment
- Announcements system
- Discord DM notifications for job deliveries
- Company leaderboards
- Webhook-driven event system

</td>
</tr>
</table>

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
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

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

## 📸 Screenshots

> Screenshots available in [`/screenshots`](./screenshots). Full preview coming with the closed beta release.

---

## 🗺️ Roadmap

| Status | Feature |
|--------|--------|
| ✅ Done | Desktop client — telemetry, job tracking, state machine, anti-cheat |
| ✅ Done | Web platform — VTC management, ranks, webhooks, badges, economy |
| ✅ Done | API — sessions, Discord OAuth2, admin panel, Redis caching |
| ✅ Done | Discord bot — verification, notifications, announcements |
| ✅ Done | Game map — ETS2/ATS tile rendering with route overlay |
| ✅ Done | Legal pages — GDPR/RODO compliant Terms & Privacy |
| 🔄 In Progress | Route GPS tracking — full polyline per trip, speed gradient |
| 🔄 In Progress | Anti-cheat v2 — position-based suspicion score |
| 🔄 In Progress | ProMods map support |
| 📅 Planned | Closed Beta — Q3 2026 |
| 📅 Planned | Public launch — 2026 |

---

## 📋 Changelog

Full changelogs are in the [`/CHANGELOG`](./CHANGELOG) folder.

| Version | Date | Highlights |
|---------|------|------------|
| [v0.9.x](./CHANGELOG/v0.9.x.md) | June 2026 | Game map, route visualization, telemetry pipeline refactor, Turnstile, VPS hardening |
| [v0.8.x](./CHANGELOG/v0.8.x.md) | May 2026 | Invitation system, role hierarchy, Redis, economy dashboard, email templates |
| [v0.7.x](./CHANGELOG/v0.7.x.md) | April 2026 | Discord bot, httpOnly auth, company settings, PM2 infra, legal pages |

---

## 🌍 Supported Games

| Game | Singleplayer | TruckersMP | ProMods |
|------|:---:|:---:|:---:|
| Euro Truck Simulator 2 | ✅ | ✅ | 🔄 |
| American Truck Simulator | ✅ | ✅ | — |

---

## 🤝 Community

OmniRoute is built for the Polish VTC community but supports English from day one.

- 🌐 **Website:** [omniroute.cloud](https://omniroute.cloud)
- 💬 **Discord:** [discord.omniroute.cloud](https://discord.omniroute.cloud)

---

## 📄 License

OmniRoute is **proprietary software**. This repository exists as a public showcase only.  
All rights reserved © 2026 OmniRoute / KetusDev.

---

<div align="center">

Built by [KetusDev](https://github.com/KetusDev) · [ketus.dev](https://ketus.dev)

</div>
