<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="360" />
  </a>
</p>

<h1 align="center">OmniRoute v0.6.2</h1>

<p align="center"><sub>VTC platform for ETS2 and ATS</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/MINOR--7C3AED?style=flat-square" alt="MINOR" height="22" /> &nbsp; <em>2 September 2026</em>
</p>

<p align="center">
  <a href="https://omniroute.cloud/en/changelog/02-09-2026"><strong>View on web</strong></a>
 &nbsp;·&nbsp; 
  <a href="https://omniroute.cloud/en/changelog">Release history</a>
</p>

---

### Added

| | Description |
| :--- | :--- |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | ATS routes in the dashboard show miles, mph, gallons, MPG, and weight in pounds |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | ATS rankings display distance in miles (ETS2 still uses km) |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Profile shows ETS2 (km) and ATS (mi) stats split; combined total still in km |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Company monthly and global ATS limits in the admin panel use miles |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Desktop Journal and Profile use in-game units for ATS (mi, gal, mph) |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Staff can correct accepted route distance from moderation — recalculates driver OmniCoin and company share |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Delivery page shows a (Correction) badge with distance change history |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Rankings and stats use corrected distance, not raw driven km |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Country picker moved to profile settings |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Community catalog remembers the open tab in the URL |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Profile timeline shows Premium events (start, renewal, expiry) |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Route map: new History / Legend tab |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Desktop: autostart on Windows login |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Desktop: Send diagnostic logs button in settings |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Company member cap enforced on every join path |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Company OmniCoin balance visible only to members with economy read permission |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Refreshed Discord job notifications (route line, mode color, stat cards) |

### Fixed

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop SP: fixed premature job close after parking at the delivery point |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Route map: gap in the line on sudden position jumps instead of a straight line across the map |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Route map: speed tooltip on hover |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Route map: ferry icon at crossing and corrected road color after disembarking |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: more reliable in-game profile switch detection — jobs no longer merge by accident |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: fixed false rejection of long routes and GPS reset counted as a ferry |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: fixed fuel usage in stats (wrong unit from game data) |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: fixed double and missing toll charges |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: refuel liters no longer lost after suspend and resume |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: job state restored correctly after app restart mid-route |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: PC sleep no longer counted as driven kilometers |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: teleport detection threshold adapts to the polling interval |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fixed company tag validation on creation (uppercase, max 5 characters) |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fixed image upload error in the company creation form |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Company member list sorts correctly by role and activity |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fixed role color picker and role label translations |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Company stats no longer count jobs driven before the member joined |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Managers can no longer overwrite their own role permissions |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fixed route integrity cap incorrectly shared with OC payout cap |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fixed route rejection after sync from desktop v0.7.3 |

### Changed

| | Description |
| :--- | :--- |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Improved Polish names for selected ATS cargo and trailers in the dashboard |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Desktop: safer per-job route storage |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Settlement distance from integrated world position, not the cab odometer |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/en/changelog/02-09-2026">View on web</a></sub>
</p>
