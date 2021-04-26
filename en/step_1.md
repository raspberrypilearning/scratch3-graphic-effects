Use graphic effects to `change`{:class="block3looks"} and `set`{:class="block3looks"} `color`{:class="block3looks"}, `ghost`{:class="block3looks"}, `brightness`{:class="block3looks"}, and other effects for sprites and the Stage.

**Rooster effects**: [See inside](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

The `set color effect to`{:class="block3looks"} and `change color effect by`{:class="block3looks"} blocks both have drop-down menus in which you can choose from a range of different graphic effects that can be used to change your sprite's appearance.

+ `color`{:class="block3looks"}: from `0` to `199` (bigger numbers will wrap around, so `200` is the same as `0`)
+ `fisheye`{:class="block3looks"}: `0` means no effect, big numbers cause a bigger 'fisheye' effect, and big negative numbers cause a reverse 'fisheye' effect
+ `whirl`{:class="block3looks"}: `0` means no effect, big numbers make a big whirl to the left, and big negative numbers make a big whirl to the right
+ `pixelate`{:class="block3looks"}: `0` means no effect, and bigger numbers create more pixels
+ `mosaic`{:class="block3looks"}: `0` means no effect, and bigger or negative numbers create more copies
+ `brightness`{:class="block3looks"}: `0` means no effect, numbers up to `100` make the sprite lighter, and negative numbers down to `-100` make the sprite darker 
+ `ghost`{:class="block3looks"}: `0` means no effect, and numbers up to `100` make the sprite more transparent 

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

Use `clear graphic effects`{:class="block3looks"} to start again. Clicking on the green flag also clears all graphic effects.

To set the graphic effect of a sprite when the project is started, place a `set graphic effect to`{:class="block3looks"} block under a `when green flag clicked`{:class="block3events"} block:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```
