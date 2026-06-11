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
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Desktop: wtyczka opener do linków zewnętrznych; zawieszanie checkpointów w trakcie pauzy śledzenia. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Web: dodanie Cloudflare Turnstile przy logowaniu i rejestracji (przekazywanie IP, reset przy błędach, ochrona przed podwójnym wysłaniem, obsługa limitu 429). |

### Naprawiono

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: usprawniona walidacja zleceń, pipeline zgłoszeń i śledzenie tras (SP + TruckersMP). |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop v0.3.8: poprawki warstwy transportowej, automatyczne usuwanie starych zleceń po rozłączeniu z gry. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop v0.3.12: obsługa skrótu F7 w UI trackera. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Teleport promem i pociągiem: obsługa pola drivableKm i zdarzeń SCS special_events — poprawne zapisy tras; flaga podejrzane przy dystansie poniżej 90% planowanego. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Poprawki w klasyfikacji dostaw i rozliczaniu przychodów dla fałszywych dostaw w TruckersMP. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Web: bezpieczny proxy pobierania release z GitHub (SSRF-safe); sanitizacja HTML w edytorze bloków firmy. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | API: opcjonalne uwierzytelnienie na wybranych endpointach zleceń; zaostrzenie widoczności zleceń publicznych i reguł zaproszeń do firmy. |

### Zmiany

| | Description |
| :--- | :--- |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Pierwszy oficjalny changelog platformy OmniRoute, zakres commitów 7–9.06.2026. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: sesje cookie-only w Next.js auth middleware — dashboard nie przechowuje tokenów bearer po stronie klienta. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: wprowadzenie checksum v2 dla zgłoszeń zleceń i serwerowa ocena podejrzanych. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: weryfikacja JWT sesji — unieważnianie wszystkich sesji po zmianie hasła. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: zabezpieczenia SSRF na uploadach, webhookach i endpointach administracyjnych; walidacja sekretów produkcyjnych fail-fast. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API i desktop: wzmocnienie OAuth Discord; tokeny API nie są już przechowywane zaszyfrowane w bazie. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Desktop: wzmocnienie IPC, klienta API i lokalnego magazynu sekretów (secure_store). |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Infrastruktura: audyt bezpieczeństwa VPS i skrypty naprawcze; zaostrzenie uprawnień środowiska deploy.sh. |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/pl/changelog/11-06-2026">Zobacz na stronie</a></sub>
</p>
