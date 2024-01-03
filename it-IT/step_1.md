**Gallo con effetti**: [Guarda dentro](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

I blocchi `porta effetto colore a`{:class="block3looks"} e `cambia effetto colore di`{:class="block3looks"} hanno entrambi menu a discesa che propongono una vasta gamma di effetti grafici, da usare per cambiare l'aspetto del tuo sprite:

+ `colore`{:class="block3looks"}: da `0` a `199` (i numeri più grandi ricominceranno da capo, quindi `200` è uguale a `0`)
+ `fish-eye`{:class="block3looks"}: `0` significa nessun effetto, i numeri più grandi causano un effetto 'fisheye' maggiore e i numeri negativi causano un effetto 'fisheye' inverso
+ `mulinello`{:class="block3looks"}: `0` significa nessun effetto, i numeri grandi fanno un grande vortice a sinistra, e i grandi numeri negativi fanno un grande vortice a destra
+ `effetto pixel`{:class="block3looks"}: `0` significa nessun effetto e numeri più grandi creano pixel più grandi
+ `mosaico`{:class="block3looks"}: `0` significa nessun effetto e numeri più grandi o negativi influiscono sul numero di copie
+ `luminosità`{:class="block3looks"}: `0` significa nessun effetto, i numeri fino a `100` rendono lo sprite più chiaro e i numeri negativi fino a `-100` rendono lo sprite più scuro
+ `fantasma`{:class="block3looks"}: `0` significa nessun effetto e i numeri fino a `100` rendono lo sprite più trasparente

Prova a `portare effetti a`{:class="block3looks"} i diversi valori degli effetti per vedere cosa fa ciascuno. Scopri come le diverse modifiche agli effetti cambiano l'aspetto al tuo sprite.

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**Suggerimento:** Un effetto `colore`{:class="block3looks"} di `225` è uguale a un effetto `colore`{:class="block3looks"} di `25`, quindi puoi continuare a cambiare il colore. Per gli altri effetti grafici, non verranno apportate altre modifiche dopo aver raggiunto il numero massimo o minimo per l'effetto.

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

Usa il blocco `rimuovi effetti grafici`{:class="block3looks"} per ricominciare. Facendo clic sulla bandierina verde si cancellano tutti gli effetti grafici.

Per impostare un effetto grafico per uno sprite all'avvio del progetto, posiziona un blocco `porta effetto grafico a`{:class="block3looks"} sotto un blocco `quando si clicca sulla bandierina verde`{:class="block3events"}:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Suggerimento:** Puoi anche `impostare`{:class="block3looks"} e `cambiare`{:class="block3looks"} effetti grafici per lo **Stage**.
