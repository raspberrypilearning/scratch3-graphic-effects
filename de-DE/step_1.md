**Hahn-Effekte**: [Schaue hinein](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Die Blöcke `setze Effekt Farbe auf`{:class="block3looks"} und `ändere Effekt Farbe um`{:class="block3looks"} verfügen beide über Dropdown-Menüs, in denen du aus einer Reihe verschiedener Grafikeffekte auswählen kannst, mit denen das Aussehen deiner Figur geändert werden kann:

+ `Farbe`{:class="block3looks"}: von `0` bis `199` (größere Zahlen werden umgebrochen, also ist `200` dasselbe wie `0`)
+ `Fischauge`{:class="block3looks"}: `0` bedeutet keinen Effekt, größere Zahlen bewirken einen größeren Fischaugeneffekt und negative Zahlen bewirken einen umgekehrten Fischaugeneffekt
+ `Wirbel`{:class="block3looks"}: `0` bedeutet keinen Effekt, große Zahlen machen einen großen Wirbel nach links und große negative Zahlen machen einen großen Wirbel nach rechts
+ `Pixel`{:class="block3looks"}: `0` bedeutet keinen Effekt, und größere Zahlen erzeugen mehr Pixel
+ `Mosaik`{:class="block3looks"}: `0` bedeutet keinen Effekt, und größere oder negative Zahlen beeinflussen die Anzahl der Kopien
+ `Helligkeit`{:class="block3looks"}: `0` bedeutet keinen Effekt, Zahlen bis `100` machen die Figur heller und negative Zahlen bis `-100` machen die Figur dunkler
+ `Durchsichtigkeit`{:class="block3looks"}: `0` bedeutet keinen Effekt, und Zahlen bis `100` machen die Figur transparenter

Probiere die Effekte aus und `setze`{:class="block3looks"} verschiedene Werte ein, um zu sehen, was jeder einzelne Effekt bewirkt. Finde heraus, wie die unterschiedlichen Effekte das Aussehen deiner Figur beeinflussen.

```blocks3
set [Wirbel v] effect to (100)

set [Pixel v] effect to (50)
```

**Tipp:** Ein `Effekt Farbe`{:class="block3looks"} von `225` ist identisch zu einem `Effekt Farbe`{:class="block3looks"} von `25`, du kannst die Farbe also fortlaufend ändern. Bei anderen Effekten werden keine weiteren Änderungen mehr vorgenommen, nachdem die Maximal- oder Minimalzahl für den Effekt erreicht wurde.

```blocks3
forever
change [Farbe v] effect by [25]
wait [0.5] seconds
```

Verwende den Block `schalte Grafikeffekte aus`{:class="block3looks"}, um erneut zu beginnen. Durch Klicken auf die grüne Flagge werden die Grafikeffekte ebenfalls gelöscht.

Um beim Starten des Projekts einen Grafikeffekt für eine Figur festzulegen, platziere einen Block `setze Effekt ... auf`{:class="block3looks"} unter einem Block `Wenn grüne Flagge angeklickt wird`{:class="block3events"}:

```blocks3
when green flag clicked
set [Durchsichtigkeit v] effect to (25)
```

**Tipp:**Du kannst die Blöcke `setze`{:class="block3looks"} und `ändere`{:class="block3looks"} Effekt auch für die **Bühne** verwenden.
