# CPP-game-binding-of-isaac
A clone of "The binding of isaac" game written from scratch in C++ using SFML. All the graphics are original.
Made with [@Wojciech-Mazurowski](https://github.com/Wojciech-Mazurowski) as a additional project for JIPP (Języki i Paradygmaty Programowania).

## Project specifications
Zaprojektuj i zaimplementuj 2-wymiarową grę losową z gatunku rougelike (zręcznościową), w której gracz wciela się jedną z kilku dostępnych postaci.
### Cel gry:
Gracz ma za zadanie przechodzić kolejne, rozmieszczone na planszy pokoje, które prowadzą do nowych, coraz trudniejszych plansz (poziomów). Przejście na kolejny poziom wymaga pokonania jednego z głównych przeciwników, znajdującego się w losowym, odpowiednio oznaczonym pokoju. Gracz przemierza trasę w poszukiwaniu tego pokoju, "czyszcząc" obowiązkowo wszystkie pokoje, które znajdą się na tej trasie (wyczyszczenie pokoju polega, w zależności od jego rodzaju, na pokonaniu wszystkich znajdujących się tam przeciwników lub na rozwiązaniu prostej łamigłówki). Po drodze gracz ma możliwość odnalezienia przedmiotów, które zwiększą jego statystyki. Celem gry jest dotarcie na najniższy możliwy poziom. Rozgrywka kończy się po upłynięciu zadanego czasu.
### Funkcjonalność aplikacji:
- sterowanie postacią za pomocą klawiatury,
- obliczanie i zadawanie obrażeń na podstawie statystyk podstawowych i statystyk
przedmiotów,
- dostępność kilku postaci oraz przeciwników o rożnych mechanikach (np. wrogowie skaczący
na gracza, wrogowie strzelający, itp.),
- losowa generacja poziomów z rozmaitymi pokojami (w każdym pokoju znajduje się co
najmniej jedno przejście oraz jeden przedmiot; na całym poziomie znajduje się dokładnie
jeden przeciwnik główny),
- dodatkowy tryb gry, polegający na pokonywaniu jak największej ilości przeciwników
pojawiających się w falach (plansza bez pomieszczeń, losowy przedmiot znajduje się
na końcu fali),
- zróżnicowana mechanika ataków, zależna od typu postaci (ataki zasięgowe i broń biała).
- przedmioty użytkowe, czyli przedmioty niezwiększające statystyk; użycie tych przedmiotów
wiąże się z pewnymi korzyściami, np. użycie klepsydry może zagwarantować chwilowe
spowolnienie czasu.
