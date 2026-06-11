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
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Desktop: opener plugin dla linków zewnętrznych; wstrzymywanie checkpointów podczas pauzy śledzenia. |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Desktop v0.3.12: wsparcie skrótu klawiszowego F7 w UI trackera. |

### Naprawiono

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Poprawione walidacje i pipeline zgłaszania zleceń na desktopie; śledzenie tras SP i TruckersMP usprawnione. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop v0.3.8: naprawy warstwy transportu; automatyczne usuwanie przeterminowanych zleceń po odłączeniu od gry. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Teleport promowy i kolejowy: poprawne commitowanie tras z uwzględnieniem drivableKm i special_events; flaga podejrzanych zleceń gdy przejechano <90% planu. |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Naprawa klasyfikatora dostaw i śledzenia przychodów dla fałszywych dostaw TruckersMP. |

### Zmiany

| | Description |
| :--- | :--- |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Pierwszy oficjalny changelog OmniRoute: zakres commity 7–9.06.2026. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: sesje oparte wyłącznie na ciasteczkach z Next.js auth middleware; dashboard nie przechowuje bearer tokenów po stronie klienta. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: Cloudflare Turnstile na logowanie i rejestrację; przekazywanie IP, reset na błędy, ochrona przed podwójnym przesłaniem, obsługa kodu 429. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Web: SSRF-safe proxy pobierania release GitHub; sanitizacja HTML w edytorze bloków firmy. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: checksum v2 dla zleceń i server-side scoring podejrzanych zleceń. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: wersjonowanie sesji JWT - unieważnianie wszystkich sesji po zmianie hasła. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: opcjonalna autoryzacja na wybranych endpointach zleceń; zaostrzone reguły widoczności zleceń publicznych i zaproszeń firmowych. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API: ochrony SSRF na uploadach, webhookach i endpointach administracyjnych; szybka walidacja sekretów produkcyjnych. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | API i desktop: wzmocnione OAuth Discord; tokeny API nie są już szyfrowane w bazie. |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Desktop: utwardzona komunikacja IPC, klient API i lokalne przechowywanie sekretów (secure_store). |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Infrastruktura: audyt bezpieczeństwa VPS i skrypty naprawcze; utwardzone uprawnienia deploy.sh. |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/pl/changelog/11-06-2026">Zobacz na stronie</a></sub>
</p>
