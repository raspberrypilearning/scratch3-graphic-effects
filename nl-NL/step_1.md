**Rooster effects**: [See inside](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

The `set color effect to`{:class="block3looks"} and `change color effect by`{:class="block3looks"} blocks both have drop-down menus in which you can choose from a range of different graphic effects that can be used to change your sprite's appearance:

+ `kleur`{:class="block3looks"}: van `0` tot `199` (grotere getallen lopen rond, dus `200` is hetzelfde als `0`)
+ `fisheye`{:class="block3looks"}: `0` means no effect, bigger numbers cause a bigger 'fisheye' effect, and negative numbers cause a reverse 'fisheye' effect
+ `draaikolk`{:class="block3looks"}: `0` betekent geen effect, grote getallen maken een grote draaikolk naar links en grote negatieve getallen maken een grote draaikolk naar rechts
+ `pixeleren`{:class="block3looks"}: `0` betekent geen effect, en grotere getallen zorgen voor meer pixels
+ `mosaic`{:class="block3looks"}: `0` means no effect, and bigger or negative numbers affect the number of copies
+ `helderheid`{:class="block3looks"}: `0` betekent geen effect, getallen tot aan `100` maken de sprite lichter en negatieve getallen tot aan `-100` maken de sprite donkerder
+ `transparant`{:class="block3looks"}: `0` betekent geen effect, en getallen tot `100` maken de sprite transparanter

Try to `set`{:class="block3looks"} the different effect values to see what each one does. Explore how different effect changes make your sprite look.

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
