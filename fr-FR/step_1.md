**Rooster effects**: [See inside](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

The `set color effect to`{:class="block3looks"} and `change color effect by`{:class="block3looks"} blocks both have drop-down menus in which you can choose from a range of different graphic effects that can be used to change your sprite's appearance:

+ `couleur`{:class="block3looks"} : de `0` à `199` (les nombres plus grands seront enveloppés, donc `200` équivaut à `0`)
+ `fisheye`{:class="block3looks"}: `0` means no effect, bigger numbers cause a bigger 'fisheye' effect, and negative numbers cause a reverse 'fisheye' effect
+ `tourbillon`{:class="block3looks"}: `0` signifie aucun effet, les grands nombres font un grand tourbillon vers la gauche et les grands nombres négatifs font un grand tourbillon vers la droite
+ `pixeliser`{:class="block3looks"} : `0` signifie aucun effet, et des nombres plus grands créent plus de pixels
+ `mosaic`{:class="block3looks"}: `0` means no effect, and bigger or negative numbers affect the number of copies
+ `luminosité`{:class="block3looks"} : `0` signifie aucun effet, les nombres jusqu'à `100` éclaircissent le sprite et les nombres négatifs jusqu'à `-100` l'assombrissent
+ `fantôme`{:class="block3looks"} : `0` signifie aucun effet, et des nombres jusqu'à `100` rendent le sprite plus transparent

Try to `set`{:class="block3looks"} the different effect values to see what each one does. Explore how different effect changes make your sprite look.

```blocks3
mettre l'effet [tourbillon v] à (100)

mettre l'effet [pixeliser v] à (50)
```

**Tip:** A `color effect`{:class="block3looks"} of `225` is the same as a `color effect`{:class="block3looks"} of `25`, so you can keep changing the colour. For other graphic effects, no other changes will be made after you reach the maximum or minimum number for the effect.

```blocks3
répéter indéfiniment
ajouter [25] à l'effet [couleur v]
attendre [0.5] secondes
```

Use the `clear graphic effects`{:class="block3looks"} block to start again. Clicking on the green flag also clears all graphic effects.

To set a graphic effect for a sprite when the project is started, place a `set graphic effect to`{:class="block3looks"} block under a `when green flag clicked`{:class="block3events"} block:

```blocks3
quand le drapeau vert est cliqué
mettre l'effet [fantôme v] à (25)
```

**Tip:** You can also `set`{:class="block3looks"} and `change`{:class="block3looks"} graphic effects for the **Stage**.
