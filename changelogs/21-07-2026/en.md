<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="360" />
  </a>
</p>

<h1 align="center">OmniRoute v0.5.1</h1>

<p align="center"><sub>VTC platform for ETS2 and ATS</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/MINOR--7C3AED?style=flat-square" alt="MINOR" height="22" /> &nbsp; <em>21 July 2026</em>
</p>

<p align="center">
  <a href="https://omniroute.cloud/en/changelog/21-07-2026"><strong>View on web</strong></a>
 &nbsp;·&nbsp; 
  <a href="https://omniroute.cloud/en/changelog">Release history</a>
</p>

---

### Added

| | Description |
| :--- | :--- |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add dashed line on ferry segment, ferry icon at boarding port, support two ferries per job |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Load today's routes, km, and OmniCoin from online account; local log clear no longer resets stats |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add Ferry distance row on delivery details for routes using ferry crossings |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add green truck icon at job start and flag icon at delivery point on route map |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Display ferry marker tooltip with ferry cost and route (e.g. Calais → Dover) when available |

### Fixed

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Keep route progress when closing game mid-route; resume on relaunch |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Auto-commit and upload route after finishing delivery if previously suspended |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Match driven km with game even when SDK telemetry timestamp stalls |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Allow more time to auto-reconnect route after game restart or long loading |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Prevent ferry deliveries from inheriting km or payout data from previous job |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Count distance and route map from loading point, not only after ferry crossing |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Show progress bar with actual km driven against contract plan; no inflation after ferry |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Prevent ferry crossings from wrongly ending active jobs |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Reduce ferry routes getting stuck as suspended without cause |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Keep backup of failed uploads in deliveries folder for retry |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix km counter after ferry crossing and speed up route commit after delivery |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix dashboard km freezing after ferry or profile edge cases |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Flush route state correctly when switching game profile mid-session |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Align dashboard stats and route scoring with new desktop settlement model |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Stop ferry jobs with short land km from auto-queuing for admin review due to ferry math |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Use anti-cheat client signals for suspicious-route queue, not naive km vs plan check |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Cap OmniCoin payout based on driven km versus contract plan |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix ferry route progress bar stuck near 0% if navigation distance exceeds land contract |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix driven km on ferry jobs to match actual land driving with game map DLCs |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Record ferry boarding at terminal, not job start or wrong map point |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Remove rest-break icon during ferry loading or delivery yard unload screens |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Count TruckersMP deliveries only at summary/unload screen, not while driving |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Include clearer error reasons in batch API responses on failed route uploads |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Calculate OmniCoin payout and accepted km on server to prevent client earnings inflation |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Allow legal ferry crossings without marking as suspicious due to shorter land km |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Send suspicious routes to staff only when anti-cheat signals are real, not ferry math alone |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Store, compare, and display American Truck Simulator distances consistently in miles |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Remember ferry crossings correctly after desktop app retries upload post-crash or offline |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Require 7-day wait to recreate a deleted company under same account to reduce spam |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Show ferry icon only at boarding port, not arrival port, on route map |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/en/changelog/21-07-2026">View on web</a></sub>
</p>
