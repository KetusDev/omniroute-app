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
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add desktop opener plugin for external links; suspend checkpoints when tracking is paused. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add F7 shortcut support in tracker UI (Desktop 0.3.12). |

### Fixed

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Improve job validation, submission pipeline and route tracking in Desktop (SP + TruckersMP). |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix Desktop 0.3.8 transport layer and auto-prune stale jobs after game disconnect. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix ferry and train teleports: commit routes correctly with special events and drivableKm field. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Flag suspicious jobs with driven distance below 90% of planned odometer. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix delivery classifier and income tracking to exclude false deliveries on TruckersMP. |

### Changed

| | Description |
| :--- | :--- |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Publish first official OmniRoute changelog for 7–9 June 2026. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: implement cookie-only sessions with Next.js auth middleware; dashboard no longer stores bearer tokens client-side. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: add Cloudflare Turnstile on login and register endpoints with client IP forwarding, error resets, double-submit protection and 429 handling. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: add SSRF-safe GitHub release download proxy; sanitize HTML in company block editor. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: introduce checksum v2 for job submissions and server-side suspicion scoring. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: apply JWT session versioning; invalidate all sessions after password reset. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: add optional auth on selected job endpoints; tighten public job visibility and company invitation rules. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: add SSRF protection on uploads, webhooks and admin endpoints; fail-fast validation of production secrets. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API and Desktop: harden Discord OAuth; stop storing API tokens encrypted in database. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Desktop: harden IPC surface, API client, and local secret storage (secure_store). |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Infrastructure: conduct VPS security audit and remediation; harden deploy.sh environment permissions. |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/en/changelog/11-06-2026">View on web</a></sub>
</p>
