<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="360" />
  </a>
</p>

<h1 align="center">OmniRoute v0.5.0</h1>

<p align="center"><sub>VTC platform for ETS2 and ATS</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/MINOR--7C3AED?style=flat-square" alt="MINOR" height="22" /> &nbsp; <em>24 June 2026</em>
</p>

<p align="center">
  <a href="https://omniroute.cloud/en/changelog/24-06-2026"><strong>View on web</strong></a>
 &nbsp;·&nbsp; 
  <a href="https://omniroute.cloud/en/changelog">Release history</a>
</p>

---

### Added

| | Description |
| :--- | :--- |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Preview bio, banner, and timeline on My Profile; link to settings for edits instead of on profile page |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Edit bio, avatar, banner, and linked accounts (Steam, Discord, TruckersMP) together in Settings → External profiles |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Allow bio editor to manage text, BBCode, and photos in any order with live preview before saving |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Show timeline events (company activity, routes, username changes) under driving style card instantly |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add cropping for avatar and banner uploads to adjust visible area |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Enable BBCode on public VTC company description matching player bio features |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Show dashboard bell notifications for announcements, support replies, company changes, and staff decisions without page refresh |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Create support center menu to submit tickets and follow threads live with OmniRoute team |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Allow moderators to see new messages and status changes in support tickets in real time |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Improve support ticket form with custom dark theme category picker |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add admin MVP modules: KPI overview, user list with ban and role management, and contact form messages |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Track staff action history with audit log covering route reviews, bans, role changes, and messages |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Organize admin navigation with collapsible categories and separate suspicious routes queue |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Show staff detailed driver profiles with account, linked accounts, company, recent routes, and expanded KPIs |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Manage companies and premium accounts: VTC list, profiles, Premium management, and detailed route browser |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Provide dedicated views for bans, roles, and a global queue for VTC applications |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Display platform announcements as a banner on the driver dashboard with admin-set active messages |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Enable staff to accept and review player reports; allow players to submit violation reports |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Show OmniCoins economy overview and account rankings for staff |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Allow staff to remove inappropriate avatars and banners from profiles via asset moderation |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add single sticky filter bar to Rankings with mode, game, sort, and country options |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Reorder community menu to Rankings → Drivers → Company catalog |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Redesign company and driver cards with taller layout, logo/avatar on top, tags, country flags, and Premium badges |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add search by company name, tag, country and driver nickname, profile number, and country |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Combine recruitment status, applicant requirements, and application text in one tab; move driver monthly km targets to global settings |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Show public company profile with single card including rules, recruitment status with color coding, and apply button |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Enable animated GIF logos for Premium VTC accounts |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Display application counters with sidebar and Applications tab showing pending counts (1–4 or 5+) |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Improve driver table with clearer layout: role, rank, activity status, and join date |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Show driver history below active list with join/leave dates and reasons (voluntary, kicked, or company deleted) |

### Fixed

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix bio widgets to display embeds from allowed sources correctly on public profiles |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Prevent page freezes when typing BBCode tags or opening brackets in bio editor |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix public profile bio display and load fresh data immediately after saving |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Add working buttons to remove avatar and banner that clear graphics after saving |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Crop company logos and banners on upload; fix company banner upload and enable removal in VTC settings |

### Changed

| | Description |
| :--- | :--- |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Implement shared staff role matrix with server validation for SUPPORT, MOD, ADMIN, and FOUNDER roles |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Add admin layout without main dashboard sidebar and include sidebar navigation for admin modules only |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/en/changelog/24-06-2026">View on web</a></sub>
</p>
