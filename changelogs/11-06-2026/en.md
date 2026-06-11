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
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add Cloudflare Turnstile on login and register (client IP forwarded, error reset, double-submit protection, 429 handling). |

### Fixed

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Improve desktop job validation, submission pipeline, and route tracking (SP + TruckersMP). |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop v0.3.8: fix transport layer, auto-prune stale jobs after game disconnect. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop v0.3.12: add F7 shortcut support in tracker UI. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Handle ferry/train teleports with drivableKm and SCS special_events — commit routes correctly; flag suspicious if driven distance <90% expected. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix delivery classification and income tracking for TruckersMP false deliveries. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Web: implement SSRF-safe GitHub release download proxy; sanitize HTML in company block editor. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | API: add optional auth on selected job endpoints; tighten public job visibility and company invitation rules. |

### Changed

| | Description |
| :--- | :--- |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Publish first official OmniRoute platform changelog, scope: commits 7–9 June 2026. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: migrate to cookie-only sessions with Next.js auth middleware — dashboard no longer stores bearer tokens client-side. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: deploy checksum v2 for job submissions and server-side suspicion scoring. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: JWT session version — invalidate all sessions on password reset. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: add SSRF guards on uploads, webhooks and admin endpoints; fail-fast production secrets validation. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Harden Discord OAuth on API and desktop; stop storing API tokens encrypted in database. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Harden desktop IPC surface, API client, and local secret storage (secure_store). |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Infrastructure: VPS security audit and remediation scripts; tighten deploy.sh environment permissions. |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/en/changelog/11-06-2026">View on web</a></sub>
</p>
