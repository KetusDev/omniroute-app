<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="360" />
  </a>
</p>

<h1 align="center">OmniRoute v0.4.0</h1>

<p align="center"><sub>Platforma VTC dla ETS2 i ATS</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/MINOR--7C3AED?style=flat-square" alt="MINOR" height="22" /> &nbsp; <em>11 czerwca 2026</em>
</p>

<p align="center">
  <a href="https://omniroute.cloud/pl/changelog/11-06-2026"><strong>Zobacz na stronie</strong></a>
 &nbsp;·&nbsp; 
  <a href="https://omniroute.cloud/pl/changelog">Historia aktualizacji</a>
</p>

---

### Nowości

| | Description |
| :--- | :--- |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Dodano plugin opener do Desktop do otwierania zewnętrznych linków, wstrzymywanie checkpointów przy pauzie śledzenia. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Wsparcie skrótu F7 w UI trackera w Desktop 0.3.12. |

### Naprawiono

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Poprawiono walidację zleceń, pipeline ich przesyłania oraz śledzenie tras w Desktop (SP i TruckersMP). |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Naprawiono warstwę transportu w Desktop 0.3.8 i automatyczne usuwanie przestarzałych zleceń po odłączeniu gry. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Korekta teleportów promów i pociągów: prawidłowe commitowanie tras ze specjalnymi zdarzeniami oraz polem drivableKm. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Wykrywanie podejrzanych zleceń z odometrem poniżej 90% planowanego dystansu. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Poprawiono klasyfikator dostaw i śledzenie przychodów, eliminując fałszywe dostawy z TruckersMP. |

### Zmiany

| | Description |
| :--- | :--- |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Pierwszy oficjalny changelog OmniRoute za okres 7–9 czerwca 2026. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: sesje cookie-only w Next.js auth middleware – dashboard przestał przechowywać tokeny bearer po stronie klienta. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: wdrożono Cloudflare Turnstile na endpointach logowania i rejestracji z ochroną przed podwójnym wysłaniem i obsługą limitów 429. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: SSRF-safe proxy dla pobierania release’ów z GitHub oraz sanitizacja HTML w edytorze bloków firm. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: wprowadzono checksum v2 dla przesyłania zleceń i serwerową ocenę podejrzanych zleceń. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: zastosowano wersjonowanie JWT sesji – unieważnienie wszystkich sesji po zmianie hasła. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: opcjonalna autoryzacja na wybranych endpointach zleceń, zaostrzone zasady widoczności publicznych zleceń i zaproszeń firmowych. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: wzmocnione zabezpieczenia przed SSRF na uploadach, webhookach i endpointach admina; szybka walidacja sekretów produkcyjnych. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API i Desktop: utwardzono OAuth Discorda; tokeny API nie są już przechowywane zaszyfrowane w bazie. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Desktop: zabezpieczono powierzchnię IPC, klienta API oraz lokalne przechowywanie sekretów (secure_store). |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Infrastruktura: audyt i poprawki bezpieczeństwa VPS; wzmocnione uprawnienia środowiskowe skryptu deploy.sh. |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/pl/changelog/11-06-2026">Zobacz na stronie</a></sub>
</p>
