# Spock-Rock Game (Spock-Rock)

Projekt rozszerzonej gry "kamień - papier - nożyce", z pięcioma opcjami do wyboru, napisany w Javascript z użyciem modułów.

## Opis

Pomysł zaczerpnięty z **The Big Bang Theory: Rock, Paper, Scissors, Lizard, Spock**. Szczegółowa mapa ruchów została przedstawiona na grafice poniżej.

![Instrukcja](./instruction.png "Instrukcja")

Gracz wybiera jedną spośród pięciu dostępnych opcji klikając na odpowiednią ikonę (`Font Awesome`). Następnie ruch wykonuje komputer (w sposób `pseudolosowy`). Skrypt zestawia ruchy wykonane przez gracza i komputer z zawartością tablicy **choices**, po czym informuje o wyniku. Zwycięstwo gracza jest dodatkowo wyróżnione efektem wizualnym zapewnionym przez skrypt `confetti.js`, zaimplementowany `modułowo`.

Projekt jest responsywny (`@media`), korzysta z `Google Fonts` czy `Flexboxa`.

## Zastosowanie i plany rozwoju

Możliwe jest usprawnienie warstwy wizualnej projektu poprzez m. in. wprowadzenie customizacji kolorystyki aplikacji. Generalnie ta prosta gra może zostać wykorzystana jako dodatek do większego serwisu internetowego poświęconego rozrywce.

Preview dostępne [na serwerze własnym (eGildia Graczy)](https://egildia.pl/projects/spock-rock-game/)
