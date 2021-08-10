**Effets coq** : [Voir à l'intérieur](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Les blocs `mettre l'effet couleur`{:class="block3looks"} et `ajouter à l'effet couleur`{:class="block3looks"} ont tous les deux des menus déroulants dans lesquels tu peux choisir parmi une gamme d'effets graphiques différents qui peuvent être utilisés pour changer l'apparence de ton sprite :

+ `couleur`{:class="block3looks"} : de `0` à `199` (les nombres plus grands seront enveloppés, donc `200` équivaut à `0`)
+ `fisheye`{:class="block3looks"} : `0` signifie qu'il n'y a pas d'effet, des nombres plus grands provoquent un effet « fisheye » plus grand, et des nombres négatifs provoquent un effet « fisheye » inverse
+ `tourbillon`{:class="block3looks"}: `0` signifie aucun effet, les grands nombres font un grand tourbillon vers la gauche et les grands nombres négatifs font un grand tourbillon vers la droite
+ `pixeliser`{:class="block3looks"} : `0` signifie aucun effet, et des nombres plus grands créent plus de pixels
+ `mosaïque`{:class="block3looks"} : `0` signifie aucun effet, et des nombres plus grands ou négatifs créent plus de copies
+ `luminosité`{:class="block3looks"} : `0` signifie aucun effet, les nombres jusqu'à `100` éclaircissent le sprite et les nombres négatifs jusqu'à `-100` l'assombrissent
+ `fantôme`{:class="block3looks"} : `0` signifie aucun effet, et des nombres jusqu'à `100` rendent le sprite plus transparent

Essaie de `définir`{:class="block3looks"} les différentes valeurs d'effet pour voir ce que chacun fait. Découvre comment les différents effets modifient l'apparence de ton sprite.

```blocks3
mettre l'effet [tourbillon v] à (100)

mettre l'effet [pixeliser v] à (50)
```

**Astuce :** Un `effet couleur`{:class="block3looks"} à `225` équivaut à un `effet couleur`{:class="block3looks"} à `25`, tu peux donc continuer à changer la couleur. Pour les autres effets graphiques, aucune autre modification ne sera apportée une fois que tu as atteint le nombre maximum ou minimum de l'effet.

```blocks3
répéter indéfiniment
ajouter [25] à l'effet [couleur v]
attendre [0.5] secondes
```

Utilise `annuler les effets graphiques`{:class="block3looks"} pour recommencer. Cliquer sur le drapeau vert annule également tous les effets graphiques.

Le `mettre l'effet couleur`{:class="block3looks"} et `ajouter à l'effet couleur`{:class="block3looks"} ont tous deux des menus déroulants dans lesquels tu peux choisir parmi une gamme d'effets graphiques différents qui peuvent être utilisés pour changer l'apparence de ton sprite :

```blocks3
when green flag clicked
mettre l'effet [fantôme v] à (25)
```

**Astuce :** Tu peux également `mettre`{:class="block3looks"} et `ajouter`{:class="block3looks"} les effets graphiques pour la **Scène**.
