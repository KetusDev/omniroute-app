<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="360" />
  </a>
</p>

<h1 align="center">OmniRoute v0.6.0</h1>

<p align="center"><sub>VTC platform for ETS2 and ATS</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/MINOR--7C3AED?style=flat-square" alt="MINOR" height="22" /> &nbsp; <em>3 August 2026</em>
</p>

<p align="center">
  <a href="https://omniroute.cloud/en/changelog/03-08-2026"><strong>View on web</strong></a>
 &nbsp;·&nbsp; 
  <a href="https://omniroute.cloud/en/changelog">Release history</a>
</p>

---

### Added

| | Description |
| :--- | :--- |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add monthly community rankings for drivers, companies, and countries based on UTC calendar months. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Allow navigating and viewing previous monthly rankings via month selector arrows. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Store finalized monthly rankings as snapshots for fast loading without rescanning past routes. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add Stripe self-serve checkout in dashboard Premium section. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Enable automatic Premium activation upon purchase and allow subscription management or cancellation directly in panel. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add dedicated redirect pages for completed and canceled checkout sessions. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Import Discord avatars on registration or account linking, and restrict Steam/Discord avatar source toggles to linked accounts. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Implement Steam OpenID authentication for direct profile linking. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Display actual Discord avatar preview in account settings. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Require current password verification before sending a password reset link in settings. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add option to log out of all active devices during password reset. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Automatically sign in users upon post-registration email verification and improve auth form UX. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add live availability checking for username and email during sign-up. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add pagination with 20 entries per page across community rankings and directories. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Update driver and company ranking cards to match directory card design. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Introduce Seats, Roles, and Other tabs in Company Shop for purchasing member slots, role slots, and custom social link packs. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Update member slot pack pricing and scale custom role/link limits based on purchases and Premium status. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add custom role colors and an option to display selected roles in company administration. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Hide administrative roles from the standard member role assignment selector. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Separate distance (km) and economy (OC) metrics cleanly in community rankings. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Redesign country rankings with square cards, large flags, rank badges, and single-metric focus. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Sort driver and company directories by registration ID ascending (#). |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Display a staff badge next to OmniRoute team members in the driver directory. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Replace account deletion with account deactivation, allowing account restoration after a 48-hour period. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Reserve usernames and linked profiles during account deactivation and display an Inactive Account badge. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Apply an escalating cooldown period for subsequent account deactivations. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Allow selecting preset role templates or starting from scratch when creating a company. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add dynamic role management and a full permission matrix editor in company settings. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Support assigning dynamic custom company roles to members. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Implement client-side data caching across key panel views to reduce unnecessary page reloads. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Optimize company settings save action to refresh mutated state only. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Replace browser alert popups with styled in-app confirmation modals for key actions. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Align web dashboard colors, spacing, and surface styles with the desktop application design. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Adjust container width constraints for profile and company pages. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Redesign Support page with improved visual hierarchy and larger callouts. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Enhance Discord authentication to automatically log in existing accounts or transition to sign-up. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Remember and highlight the last used login method on the sign-in screen. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Ensure full state synchronization immediately following company creation. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Remove redundant First Route milestone entries from profile timeline. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Add dashboard toggle for switching stats between overall totals and ETS2/ATS game breakdown. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Display full flat grid in community directories when country filter is set to All. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Allow companies to add custom social media links. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Redesign community rankings layout featuring a top-3 podium and structured standings. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Draw ferry route segments as distinct dashed lines on route detail maps. |

### Fixed

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix company owner transfer suggestions dropdown being hidden behind lower UI elements. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix profile wallet section showing total earned OmniCoins instead of current balance. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix minimum driver age and required Steam hours failing to update visually in company settings. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix OmniCoins balance parsing crash right after company creation. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Fix formatting errors in dynamic cooldown status messages. |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/en/changelog/03-08-2026">View on web</a></sub>
</p>
