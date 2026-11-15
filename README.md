# abalone-rl

Agent grający w **Abalone**, uczony ze wzmocnieniem. Projekt realizowany w ramach przedmiotu
*Uczenie się ze wzmocnieniem* (WEiI, Politechnika Rzeszowska, 2026/2027).

**Autor:** Ignacy Janus

## Opis projektu

Abalone to dwuosobowa, deterministyczna gra planszowa z pełną informacją, rozgrywana na
heksagonalnej planszy z 61 polami. Celem gry jest wypchnięcie sześciu kul przeciwnika poza planszę.

Celem projektu jest zbudowanie agenta, który uczy się grać w Abalone na podstawie rozegranych
partii, bez ręcznie zakodowanej strategii wyboru ruchu, a następnie porównanie go z agentami
bazowymi.

- **Algorytm uczenia:** TD(λ) z siecią wartości stanu po ruchu, wybór akcji strategią ε-zachłanną.
- **Trening:** etapami: z agentem losowym, z agentem AlphaBeta (głębokość 2), a na końcu gra z samym sobą.
- **Ocena:** serie partii przeciwko agentowi losowemu oraz agentom AlphaBeta o głębokości 2 i 3.

Pełna formalizacja problemu (stan, akcje, funkcja nagrody, warunki zakończenia epizodu)
znajduje się w raporcie.

## Struktura repozytorium

| Katalog | Zawartość |
|---|---|
| `Raport każda wersja aktualizacji/` | kolejne wersje raportu projektowego |
| `Transkrypcje/` | transkrypcje rozmów z narzędziami AI (sekcja *Wsparcie AI*) |

## Uruchomienie

Instrukcja uruchomienia zostanie dodana wraz z kodem środowiska i agenta (etap E2).

## Status

- [x] E1: temat, repozytorium i formalizacja problemu
- [ ] E2: środowisko, agent bazowy i plan eksperymentów
- [ ] E3: finalny agent, eksperymenty i raport
- [ ] E4: poprawki i domknięcie projektu
