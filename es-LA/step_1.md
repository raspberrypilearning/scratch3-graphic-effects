**Efectos de gallo**: [Ver interior](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Los bloques `fijar efecto color a`{:class="block3looks"} y `cambiar el efecto color en`{:class="block3looks"} tienen menús desplegables en los que puedes elegir entre una variedad de diferentes efectos gráficos que se puede utilizar para cambiar la apariencia de tu objeto:

+ `color`{:class="block3looks"}: de `0` a `199` (los números más grandes vuelven a comenzar, por lo que `200` es lo mismo que `0`)
+ `ojo de pez`{:class="block3looks"}: `0` significa que no hay efecto, los números más grandes causan un efecto 'ojo de pez' mayor y los números negativos causan un efecto 'ojo de pez' inverso
+ `remolino`{:class="block3looks"}: `0` significa que no hay efecto, los números grandes hacen un gran giro hacia la izquierda y los números grandes negativos hacen un gran giro hacia la derecha
+ `pixelar`{:class="block3looks"}: `0` significa que no hay efecto, y los números más grandes crean más píxeles
+ `mosaico`{:class="block3looks"}: `0` significa que no hay efecto, y los números más grandes o negativos afectan el número de copias
+ `brillo`{:class="block3looks"}: `0` significa que no hay efecto, los números hasta `100` hacen que el objeto sea más claro y los números negativos hasta `-100` hacen que el objeto sea más oscuro
+ `desvanecer`{:class="block3looks"}: `0` significa que no hay efecto, y los números hasta `100` hacen que el objeto sea más transparente

Intenta `fijar`{:class="block3looks"} los diferentes valores de efecto para ver qué hace cada uno. Explora cómo hacen que tu objeto se vea los diferentes efectos.

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**Consejo:** Un `efecto color`{:class="block3looks"} de `225` es lo mismo que un `efecto color`{:class="block3looks"} de `25`, por lo que puedes seguir cambiando el color. Para otros efectos gráficos, no se realizarán otros cambios después de alcanzar el número máximo o mínimo del efecto.

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

Utiliza el bloque `quitar efectos gráficos`{:class="block3looks"} para empezar de nuevo. Al hacer clic en la bandera verde también se borran todos los efectos gráficos.

Para fijar el efecto gráfico de un objeto cuando se inicia el proyecto, coloca un bloque `fijar efecto a`{:class="block3looks"} debajo de un bloque `al presionar la bandera verde`{:class="block3events"}:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Consejo:** También puedes `fijar`{:class="block3looks"} y `cambiar`{:class="block3looks"} efectos gráficos para el **Escenario**.
