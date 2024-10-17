**Hahn mit Effekte**: [Schaue hinein](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Die Blöcke „ `Setze Effekt Farbe auf`{:class="block3looks"}“ und „ `Ändere Effekt Farbe um`{:class="block3looks"}“ verfügen beide über Dropdown-Menüs, in denen du aus einer Reihe verschiedener Grafikeffekte auswählen kannst, mit denen das Erscheinungsbild der Figur geändert werden kann:

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

**Tip:** A `color effect`{:class="block3looks"} of `225` is the same as a `color effect`{:class="block3looks"} of `25`, so you can keep changing the colour. For other graphic effects, no other changes will be made after you reach the maximum or minimum number for the effect.

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

Use the `clear graphic effects`{:class="block3looks"} block to start again. Clicking on the green flag also clears all graphic effects.

To set a graphic effect for a sprite when the project is started, place a `set graphic effect to`{:class="block3looks"} block under a `when green flag clicked`{:class="block3events"} block:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Tip:** You can also `set`{:class="block3looks"} and `change`{:class="block3looks"} graphic effects for the **Stage**.
