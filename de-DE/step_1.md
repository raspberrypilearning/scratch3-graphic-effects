**Hahn mit Effekte**: [Schaue hinein](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Die Blöcke „`Setze Effekt Farbe auf`{:class="block3looks"}“ und „`Ändere Effekt Farbe um`{:class="block3looks"}“ verfügen beide über Dropdown-Menüs, in denen du aus einer Reihe verschiedener Grafikeffekte auswählen kannst, mit denen das Erscheinungsbild der Figur geändert werden kann:

+ `Farbe`{:class="block3looks"}: von `0` bis `199` (größere Zahlen werden umgebrochen, also ist `200` dasselbe wie `0`)
+ `Fischauge`{:class="block3looks"}: `0` bedeutet keinen Effekt, größere Zahlen verursachen einen größeren Fischaugeneffekt und negative Zahlen verursachen einen umgekehrten Fischaugeneffekt
+ `Wirbel`{:class="block3looks"}: `0` bedeutet keinen Effekt, große Zahlen machen einen großen Wirbel nach links und große negative Zahlen machen einen großen Wirbel nach rechts
+ `verpixeln`{:class="block3looks"}: `0` bedeutet keinen Effekt, und größere Zahlen erzeugen mehr Pixel
+ `Mosaik`{:class="block3looks"}: `0` bedeutet keinen Effekt, und größere oder negative Zahlen beeinflussen die Anzahl der Kopien
+ `Helligkeit`{:class="block3looks"}: `0` bedeutet keinen Effekt, Zahlen bis `100` machen die Figur heller und negative Zahlen bis `-100` machen die Figur dunkler
+ `Geist`{:class="block3looks"}: `0` bedeutet keinen Effekt, und Zahlen bis `100` machen die Figur transparenter

Versuche, die verschiedenen Effektwerte zu `setzen`{:class="block3looks"} um zu sehen, was jeder einzelne bewirkt. Finde heraus, wie die unterschiedlichen Effekte das Aussehen deiner Figur beeinflussen.

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**Tipp:** Ein `Ändere Effekt Farbe`{:class="block3looks"} von `225` ist identisch zu einem `Farbeffekt`{:class="block3looks"} von `25`, du kannst die Farbe also immer wieder ändern. Bei anderen Effekten werden keine weiteren Änderungen mehr vorgenommen, nachdem die Maximal- oder Minimalzahl für den Effekt erreicht wurde.

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

Verwende den Block `schalte Grafikeffekte aus`{:class="block3looks"}, um erneut zu beginnen. Durch Klicken auf die grüne Flagge werden die Grafikeffekte ebenfalls gelöscht.

Um beim Starten des Projekts einen Grafikeffekt für eine Figur festzulegen, platziere einen Block `setze Effekt ... auf` {:class="block3looks"} unter einem Block `Wenn auf grüne Flagge geklickt wird`{:class="block3events"}:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Tipp:**Du kannst die Blöcke `setze`{:class="block3looks"} und `ändere`{:class="block3looks"} Grafikeffekte für die **Bühne** ändern.
