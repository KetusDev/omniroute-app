<div align="center">

<img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="120" />

# OmniRoute

### The platform for Virtual Trucking Companies

[![Status](https://img.shields.io/badge/Status-Closed%20Beta-7C3AED?style=for-the-badge)](https://omniroute.cloud)
[![Website](https://img.shields.io/badge/Website-omniroute.cloud-0A0A0F?style=for-the-badge&logo=firefox&logoColor=white)](https://omniroute.cloud)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.omniroute.cloud)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](./LICENSE)

**Automatic trip tracking for ETS2 & ATS Virtual Trucking Companies — no manual reporting, ever.**

[🌐 Website](https://omniroute.cloud) · [💬 Discord](https://discord.omniroute.cloud) · [📋 Changelog](./changelogs) · [🗺️ Roadmap](#️-roadmap)

</div>

---

## 🚛 What is OmniRoute?

OmniRoute is a platform built for Virtual Trucking Companies (VTCs) in **Euro Truck Simulator 2** and **American Truck Simulator**. It connects directly to the game and handles everything automatically — every job, every kilometre, every event on the road is tracked and submitted without drivers lifting a finger.

It supports both **singleplayer** and **TruckersMP multiplayer**, and provides company managers with a full dashboard to run their organisation.

> This repository is a **public showcase**. The full source code is proprietary and not publicly available.

---

## ✨ Why OmniRoute?

There are other VTC systems out there. Here's what makes OmniRoute different:

🗺️ **Route GPS tracking** — every trip recorded as a full GPS path on an interactive map. See exactly where you drove, at what speed, and what happened along the way.

🏆 **Leaderboards** — built-in competitive rankings within your company. See who's driven the most, earned the most, delivered the most.

💰 **OmniCoin** — a virtual currency earned per kilometre driven. The more you drive, the more you earn — across singleplayer and TruckersMP alike.

🎨 **Modern interface** — designed from scratch in 2026, not carried over from a decade ago. Dark UI, clean layout, works on any screen.

🇵🇱 **Built for the Polish VTC scene** — developed by someone from this community, with Polish and English supported from day one.

---

## 🔧 Key Features

<table>
<tr>
<td width="50%" valign="top">

### 🖥️ Desktop Client
- Automatic job detection — no manual input required
- Real-time connection to the game via SCS SDK
- Handles ferry crossings, F7 teleports and save/load events
- Works in the background, no performance impact
- Suspend & resume on game close or profile switch
- Supports ETS2 and ATS, singleplayer and TruckersMP

</td>
<td width="50%" valign="top">

### 🌐 Web Platform
- Full VTC management dashboard
- Company ranks, badges, webhooks, name history
- Driver profiles, public pages & activity tracking
- Discord OAuth2 + TruckersMP account linking
- Invitation & application system
- Interactive game map with full route visualisation
- Polish 🇵🇱 & English 🇬🇧 localisation

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ API
- RESTful API with secure session management
- Role hierarchy: FOUNDER → MODERATOR → SUPPORT → USER
- Discord-gated registration with role verification
- Discord webhook dispatcher for job and fleet events
- Bot protection via Cloudflare Turnstile

</td>
<td width="50%" valign="top">

### 🤖 Discord Bot
- Verification system with two-step embed panel
- Country & language role assignment
- Announcements system
- DM notifications for job deliveries
- Company leaderboard commands

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

## 🌍 Supported Games

| Game | Singleplayer | TruckersMP | ProMods |
|------|:---:|:---:|:---:|
| Euro Truck Simulator 2 | ✅ | ✅ | 🔄 |
| American Truck Simulator | ✅ | ✅ | — |

---

## 🗺️ Roadmap

| Status | Feature |
|--------|---------|
| ✅ Done | Desktop client — telemetry, job tracking, state machine |
| ✅ Done | Web platform — VTC management, ranks, webhooks, badges, economy |
| ✅ Done | API — sessions, Discord OAuth2, admin panel, caching |
| ✅ Done | Discord bot — verification, notifications, announcements |
| ✅ Done | Game map — ETS2/ATS tile rendering with route overlay |
| ✅ Done | Route GPS tracking — full polyline per trip, speed gradient |
| ✅ Done | Legal pages — GDPR/RODO compliant Terms & Privacy |
| 🔄 In Progress | ProMods full map support |
| 🔄 In Progress | Anti-cheat v2 — position-based suspicion scoring |
| 📅 Planned | Closed Beta — Q3 2026 |
| 📅 Planned | Dispatcher panel |
| 📅 Planned | Fleet management (trucks & trailers) |
| 📅 Planned | Company chat |
| 📅 Planned | Public launch — 2026 |

---

## 📋 Changelog

Changelogs are published regularly in three places simultaneously: here on GitHub, on the [website](https://omniroute.cloud/en/changelog), and on [Discord](https://discord.omniroute.cloud).

| Date | Version | Highlights |
|------|---------|------------|
| [11 Jun 2026](./changelogs/11-06-2026/en.md) | v0.4.0 | Ferry/train teleport handling, TruckersMP delivery fixes, Cloudflare Turnstile, security hardening |

---

## 📸 Screenshots

> Full preview coming with the closed beta release.

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
