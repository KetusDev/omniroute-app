<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="360" />
  </a>
</p>

<h1 align="center">OmniRoute v0.4.0</h1>

<p align="center"><sub>VTC platform for ETS2 and ATS</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/MINOR--7C3AED?style=flat-square" alt="MINOR" height="22" /> &nbsp; <em>11 June 2026</em>
</p>

<p align="center">
  <a href="https://omniroute.cloud/en/changelog/11-06-2026"><strong>View on web</strong></a>
 &nbsp;·&nbsp; 
  <a href="https://omniroute.cloud/en/changelog">Release history</a>
</p>

---

### Added

| | Description |
| :--- | :--- |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add desktop opener plugin for external links; suspend checkpoints during tracking pause. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add F7 shortcut support in desktop tracker UI (v0.3.12). |

### Fixed

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Improve job validation and submission pipeline on desktop; enhance route tracking for SP and TruckersMP. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix transport layer issues in desktop v0.3.8; auto-prune stale jobs after game disconnect. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix ferry and train teleport route commits using drivableKm and SCS special_events; flag jobs as suspicious if driven <90% planned distance. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix delivery classification and income tracking for false TruckersMP deliveries. |

### Changed

| | Description |
| :--- | :--- |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Publish first official OmniRoute changelog covering commits from 7–9 June 2026. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Implement cookie-only sessions on web with Next.js auth middleware; remove bearer tokens from client dashboard code. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Integrate Cloudflare Turnstile on login/register with client IP forwarding, error reset, double-submit protection, and 429 handling. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Add SSRF-safe GitHub release download proxy and HTML sanitization in company block editor on web. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Upgrade API with checksum v2 for jobs and server-side suspicion scoring. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Version JWT sessions and invalidate all sessions after password reset in API. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Add optional auth on selected job endpoints; tighten public job visibility and company invite rules. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Add SSRF protections on uploads, webhooks, admin endpoints; implement fail-fast validation of production secrets. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Harden Discord OAuth in API and desktop; stop storing API tokens encrypted in database. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Harden desktop IPC interface, API client, and local secret storage (secure_store). |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Perform VPS security audit and remediation; harden deploy.sh environment permissions. |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/en/changelog/11-06-2026">View on web</a></sub>
</p>
