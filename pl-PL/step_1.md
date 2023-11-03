**Efekty koguta**: [Zajrzyj do środka](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Bloki `zmień efekt kolor na`{:class="block3looks"} i `zmień efekt kolor o`{:class="block3looks"} mają rozwijane menu, przy pomocy którego możesz wybierać spośród szeregu różnych efektów graficznych, których można użyć do zmiany wyglądu duszka:

+ `kolor`{:class="block3looks"}: od `0` do `199` (większe liczby spowodują powrót do początku zakresu wartości, więc `200` będzie odpowiadało `0`)
+ `rybie oko`{:class="block3looks"}: `0` oznacza brak efektu, większe liczby powodują większy efekt „rybiego oka”, a liczby ujemne powodują odwrotny efekt „rybiego oka”
+ `wir`{:class="block3looks"}: `0` oznacza brak efektu, duże liczby tworzą duży wir w lewo, a duże liczby ujemne tworzą duży wir w prawo
+ `zniekształć`{:class="block3looks"}: `0` oznacza brak efektu, a większe liczby tworzą więcej pikseli
+ `mozaika`{:class="block3looks"}: `0` oznacza brak efektu, a większe lub ujemne liczby wpływają na liczbę kopii
+ `jasność`{:class="block3looks"}: `0` oznacza brak efektu, liczby do `100` sprawiają, że duszek jest jaśniejszy, a liczby ujemne do `-100` powodują, że duszek jest ciemniejszy
+ `duch`{:class="block3looks"}: `0` oznacza brak efektu, a liczby do `100` sprawiają, że duszek jest bardziej przezroczysty

Spróbuj `ustawić`{:class="block3looks"} różne wartości efektów, aby zobaczyć, co robi każdy z nich. Sprawdź, jak różne zmiany efektów wpływają na wygląd duszka.

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**Wskazówka:** `efekt kolor`{:class="block3looks"} z wartością `225` jest taki sam jak `efekt kolor`{:class="block3looks"} z wartością `25`, więc możesz ciągle zmieniać kolor. W przypadku innych efektów graficznych żadne inne zmiany nie zostaną wprowadzone po osiągnięciu maksymalnej lub minimalnej wartości dla danego efektu.

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

Użyj bloku `wyczyść efekty graficzne`{:class="block3looks"}, aby zacząć od nowa. Kliknięcie zielonej flagi również usuwa wszystkie efekty graficzne.

Aby ustawić efekt graficzny dla duszka, gdy projekt jest uruchamiany, umieść blok `ustaw efekt graficzny na`{:class="block3looks"} pod blokiem `kiedy kliknięto zieloną flagę`{:class="block3events"}:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Wskazówka:** Możesz także `ustawić`{:class="block3looks"} i `zmienić`{:class="block3looks"} efekty graficzne dla **sceny**.
