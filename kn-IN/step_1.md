**Rooster effects**: [See inside](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

The `set color effect to`{:class="block3looks"} and `change color effect by`{:class="block3looks"} blocks both have drop-down menus in which you can choose from a range of different graphic effects that can be used to change your sprite's appearance:

+ `color`{:class="block3looks"}: `0` ರಿಂದ `199` (ದೊಡ್ಡ ಸಂಖ್ಯೆಗಳು ಸುತ್ತುತ್ತವೆ, ಆದ್ದರಿಂದ `200` `0`ನಂತೆಯೇ ಇರುತ್ತದೆ)
+ `fisheye`{: class = "block3looks"}: `0` ಎಂದರೆ ಯಾವುದೇ ಪರಿಣಾಮವಿಲ್ಲ, ದೊಡ್ಡ ಸಂಖ್ಯೆಗಳು ದೊಡ್ಡ 'fisheye' ಪರಿಣಾಮವನ್ನು ಉಂಟುಮಾಡುತ್ತವೆ, ಮತ್ತು ನಕಾರಾತ್ಮಕ ಸಂಖ್ಯೆಗಳು ರಿವರ್ಸ್ 'fisheye' ಪರಿಣಾಮವನ್ನು ಉಂಟುಮಾಡುತ್ತವೆ
+ `whirl`{:class="block3looks"}: `0` means no effect, big numbers make a big whirl to the left, and big negative numbers make a big whirl to the right
+ `pixelate`{:class="block3looks"}: `0` means no effect, and bigger numbers create more pixels
+ `mosaic`{:class="block3looks"}: `0` means no effect, and bigger or negative numbers affect the number of copies
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

Use the `clear graphic effects`{:class="block3looks"} block to start again. Clicking on the green flag also clears all graphic effects.

To set a graphic effect for a sprite when the project is started, place a `set graphic effect to`{:class="block3looks"} block under a `when green flag clicked`{:class="block3events"} block:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Tip:** You can also `set`{:class="block3looks"} and `change`{:class="block3looks"} graphic effects for the **Stage**.
