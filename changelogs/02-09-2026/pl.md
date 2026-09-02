<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="360" />
  </a>
</p>

<h1 align="center">OmniRoute v0.6.2</h1>

<p align="center"><sub>Platforma VTC dla ETS2 i ATS</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/MINOR--7C3AED?style=flat-square" alt="MINOR" height="22" /> &nbsp; <em>2 września 2026</em>
</p>

<p align="center">
  <a href="https://omniroute.cloud/pl/changelog/02-09-2026"><strong>Zobacz na stronie</strong></a>
 &nbsp;·&nbsp; 
  <a href="https://omniroute.cloud/pl/changelog">Historia aktualizacji</a>
</p>

---

### Nowości

| | Description |
| :--- | :--- |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Trasy ATS w panelu pokazują mile, prędkość w mph, paliwo w galonach i MPG, wagę w funtach |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Rankingi ATS wyświetlają dystans w milach (ETS2 nadal w km) |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Na profilu widać podział statystyk ETS2 (km) i ATS (mi); suma łączna nadal w km |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Limity miesięczne i globalne firmy dla ATS w panelu admina w milach |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Desktop: Dziennik i Profil używają jednostek z gry przy ATS (mi, gal, mph) |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Staff może skorygować zaakceptowany dystans trasy z moderacji — przelicza się OmniCoin i udział firmy |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Na stronie dostawy oznaczenie (Korekta) z historią zmian dystansu |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Rankingi i statystyki liczą skorygowany dystans, nie surowy przejechany |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Wybór kraju przeniesiony do ustawień profilu |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Katalog społeczności zapamiętuje otwartą zakładkę w adresie URL |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Na osi czasu profilu widać zdarzenia Premium (start, odnowienie, wygaśnięcie) |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Mapa trasy: nowa zakładka Historia / Legenda |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Desktop: autostart aplikacji po zalogowaniu do Windows |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Desktop: przycisk Wyślij logi diagnostyczne w ustawieniach |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Limit miejsc w firmie egzekwowany przy każdym dołączeniu |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Saldo OmniCoin firmy widzą tylko członkowie z uprawnieniem do ekonomii |
| ![feat](https://img.shields.io/badge/feat--7C3AED?style=flat-square) | Odświeżone powiadomienia o zleceniach na Discordzie (trasa, tryb, statystyki) |

### Naprawiono

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop SP: naprawione przedwczesne zamykanie zlecenia po zaparkowaniu na miejscu dostawy |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Mapa trasy: przerwa w linii przy nagłym skoku pozycji zamiast prostej przez pół mapy |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Mapa trasy: dymek z prędkością po najechaniu na trasę |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Mapa trasy: ikona promu w miejscu przeprawy i poprawiony kolor drogi po zjeździe |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: pewniejsze wykrywanie zmiany profilu w trakcie zlecenia — przejazdy nie łączą się przypadkiem |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: naprawione błędne odrzucanie długich tras i mylne liczenie resetu GPS jako promu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: poprawione zużycie paliwa w statystykach (błędna jednostka z gry) |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: naprawione podwójne i gubione liczenie opłat za bramki |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: doładowane litry paliwa nie giną po zawieszeniu i wznowieniu aplikacji |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: przywracanie stanu zlecenia po restarcie aplikacji w trakcie jazdy |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: uśpienie komputera nie jest już liczone jako przejechane kilometry |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Desktop: próg wykrywania skoków pozycji dopasowuje się do odstępu między pomiarami |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Naprawiona walidacja tagu firmy przy tworzeniu (wielkie litery, max. 5 znaków) |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Naprawiony błąd przy wgrywaniu obrazka w formularzu tworzenia firmy |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Lista członków firmy sortuje się poprawnie po roli i aktywności |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Naprawiony wybór koloru roli i tłumaczenia etykiet ról |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Statystyki firmy nie liczą zleceń sprzed dołączenia gracza |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Zarządzający nie może nadpisać własnej roli uprawnień w firmie |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Naprawiony limit integralności trasy błędnie współdzielony z limitem wypłaty OC |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Naprawione odrzucanie tras po synchronizacji z wersji 0.7.3 |

### Zmiany

| | Description |
| :--- | :--- |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Ulepszone polskie nazwy wybranych ładunków i naczep ATS w panelu |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Desktop: bezpieczniejszy zapis tras osobno dla każdego zlecenia |
| ![chore](https://img.shields.io/badge/chore--64748B?style=flat-square) | Dystans rozliczeniowy z przebytej drogi na mapie, nie z licznika w kabinie |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/pl/changelog/02-09-2026">Zobacz na stronie</a></sub>
</p>
