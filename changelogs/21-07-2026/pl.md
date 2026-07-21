<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="360" />
  </a>
</p>

<h1 align="center">OmniRoute v0.5.1</h1>

<p align="center"><sub>Platforma VTC dla ETS2 i ATS</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/MINOR--7C3AED?style=flat-square" alt="MINOR" height="22" /> &nbsp; <em>21 lipca 2026</em>
</p>

<p align="center">
  <a href="https://omniroute.cloud/pl/changelog/21-07-2026"><strong>Zobacz na stronie</strong></a>
 &nbsp;·&nbsp; 
  <a href="https://omniroute.cloud/pl/changelog">Historia aktualizacji</a>
</p>

---

### Naprawiono

| | Description |
| :--- | :--- |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Zamknięcie gry w trasie nie zawiesza już od razu trasy, postęp jest wznowiony po restarcie gry |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Dostawa zakończona po wznowieniu zawieszonej trasy wysyła się automatycznie do panelu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Kilometry pokonane zgodne z grą nawet przy zatrzymaniu timera telemetrycznego |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Po restarcie gry i długim ładowaniu trasa dłużej próbuje się automatycznie połączyć |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Dostawy promowe: następne zlecenie nie dziedziczy kilometrów ani płatności z poprzedniego ekranu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Liczenie kilometrów i mapa trasy uwzględnia dystans przed promem, nie tylko po przeprawie |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Pasek postępu pokazuje faktycznie przejechane km względem planu, bez nadmiaru po promie |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Przeprawy promowe już nie kończą zlecenia omyłkowo |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Trasy z promem rzadziej zawieszają się bez powodu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | W razie problemów z wysyłką trasy, backup pozostaje w folderze dostaw do ponownego wysłania |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Poprawiono licznik km po przeprawie, trasy szybciej zapisują się po dostawie |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Mapa trasy: przerywana linia na odcinku promowym, ikona promu przy porcie, wsparcie drugiego promu w zleceniu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Statystyki km na dashboardzie nie zawieszają się po promie lub zmianie profilu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Zmiana profilu w trakcie sesji poprawnie czyści stan trasy, bez mieszania danych |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Statystyki i oceny tras na panelu zgodne z nowym modelem rozliczeń desktopu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Zlecenia promowe z krótszym lądowym km niż nawigacja nie trafiają już automatycznie do admina |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Kolejka tras podejrzanych korzysta z sygnałów antycheatowych klienta, nie tylko z porównania km |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Wypłata OmniCoin według przejechanych km z limitem nadmiaru względem planu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Pasek postępu na trasach promowych nie zaciąga się blisko 0%, gdy dystans nawigacji jest dłuższy |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Kilometry na trasach promowych poprawnie skalowane z DLC map (np. UK, Grecja) |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Wejście na prom zapisywane jest przy terminalu, nie na starcie zlecenia ani w złym miejscu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Ikona przerwy na odpoczynek nie pokazuje się na ekranie załadunku promu ani rozładunku |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | TruckersMP liczy dostawy po dotarciu do ekranu podsumowania, nie podczas jazdy do punktu |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Błędniejszy powód błędu przy nieudanej wysyłce trasy w odpowiedzi z API ułatwia wsparcie |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Serwer wylicza wypłatę OmniCoin i zaakceptowane km z uwzględnieniem przejechanych km i planu, klienci nie mogą już manipulować |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Legalne przeprawy morskie nie są już oznaczane jako podejrzane tylko przez krótszy lądowy dystans |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Podejrzane trasy kierowane są do review tylko jeśli antycheat wykryje prawdziwe sygnały, nie z powodu promów |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | ATS: dystanse przechowywane i porównywane spójnie, UI pokazuje mile tam gdzie trzeba |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Po restarcie/crashu desktop poprawnie pamięta przeprawy promowe przy ponownej wysyłce trasy |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Po usunięciu firmy założenie nowej z tym samym kontem wymaga 7 dni przerwy, by zapobiec spamowi |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Dashboard: dzisiejsze trasy, km i OmniCoiny ładują się z konta online; czyszczenie lokalnych logów nie resetuje statystyk |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Szczegóły dostaw na stronie: nowy wiersz Dystans promu w trasach z przeprawą morską |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Mapa trasy: zielona ikona ciężarówki na starcie, flaga na punkcie dostawy |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Ikona promu pokazuje się tylko w porcie wejścia, nie w porcie wyjścia |
| ![fix](https://img.shields.io/badge/fix--10B981?style=flat-square) | Tooltip markera promu wyświetla koszt i trasę przeprawy (np. Calais → Dover) |

---

<p align="center">
  <a href="https://omniroute.cloud">
    <img src="https://omniroute.cloud/omniroute.png" alt="OmniRoute" width="168" />
  </a>
</p>

<p align="center">
  <sub>OmniRoute Changelog · <a href="https://omniroute.cloud/pl/changelog/21-07-2026">Zobacz na stronie</a></sub>
</p>
