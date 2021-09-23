**Haan effecten**: [Klik hier](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

De `zet kleur effect op`{:class="block3looks"} en `verander kleur effect met`{:class="block3looks"} blokken hebben beiden dropdown-menu's waarin je kunt kiezen uit een reeks verschillende grafische effecten waarmee je het uiterlijk van je sprite kunt veranderen:

+ `kleur`{:class="block3looks"}: van `0` tot `199` (grotere getallen lopen rond, dus `200` is hetzelfde als `0`)
+ `vissenoog`{:class="block3looks"}: `0` betekent geen effect, grote getallen geven een groter 'vissenoog'-effect en negatieve getallen veroorzaken een omgekeerd 'vissenoog'-effect
+ `draaikolk`{:class="block3looks"}: `0` betekent geen effect, grote getallen maken een grote draaikolk naar links en grote negatieve getallen maken een grote draaikolk naar rechts
+ `pixeleren`{:class="block3looks"}: `0` betekent geen effect, en grotere getallen zorgen voor meer pixels
+ `mozaïek`{:class="block3looks"}: `0` betekent geen effect, en grotere of negatieve getallen zorgen voor meer of minder kopieën
+ `helderheid`{:class="block3looks"}: `0` betekent geen effect, getallen tot aan `100` maken de sprite lichter en negatieve getallen tot aan `-100` maken de sprite donkerder
+ `transparant`{:class="block3looks"}: `0` betekent geen effect, en getallen tot `100` maken de sprite transparanter

Probeer met het `zet`{:class="block3looks"} codeblok de verschillende effectwaarden uit om te zien wat ze doen. Ontdek hoe de verschillende effecten jouw sprite veranderen.

```blocks3
set [draaikolk v] effect to (100)

set [pixeleren v] effect to (50)
```

**Tip:** Een `kleureffect`{:class="block3looks"} van `225` is gelijk aan een `kleureffect`{:class="block3looks"} van `25`, zodat je de kleur kunt blijven veranderen. Voor andere grafische effecten worden er geen andere wijzigingen aangebracht nadat je het maximale of minimale getal voor het effect hebt bereikt.

```blocks3
forever
change [kleur v] effect by [25]
wait [0.5] seconds
```

Gebruik `zet alle effecten uit`{:class="block3looks"} om opnieuw te beginnen. Door op de groene vlag te klikken, worden ook alle grafische effecten gewist.

Om het grafische effect van een sprite in te stellen wanneer het project wordt gestart, plaats je een `zet grafisch effect op`{:class="block3looks"} blok onder een `wanneer op de groene vlag wordt geklikt`{:class="block3events"} blok:

```blocks3
when green flag clicked
set [transparant v] effect to (25)
```

**Tip:** Je kunt ook `zet`{:class="block3looks"} en `verander`{:class="block3looks"} grafische effecten instellen voor het **Speelveld**.
