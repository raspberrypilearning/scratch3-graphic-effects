**Tuppeffekter**: [Se inuti](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

`Sätt färgeffekten till`{:class="block3looks"}- och `ändra färgeffekten med`{:class="block3looks"}-block har båda rullgardinsmenyer där du kan välja från ett antal olika effekter som kan användas för att ändra din sprajts utseende:

+ `färg`{:class="block3looks"}: från `0` till `199` (större tal går tillbaka till början, så `200` är detsamma som `0`)
+ `fisheye`{:class="block3looks"}: `0` betyder ingen effekt, större tal ger en större 'fisheye'-effekt och negativa siffror orsakar en omvänd 'fisheye'-effekt
+ `virvel`{:class="block3looks"}: `0` betyder ingen effekt, stora tal medför en stor virvel åt vänster och stora negativa tal innebär en stor virvel åt höger
+ `pixla`{:class="block3looks"}: `0` betyder ingen effekt, och större tal skapar fler pixlar
+ `mosaik`{:class="block3looks"}: `0` betyder ingen effekt, och större eller negativa tal påverkar antalet kopior
+ `ljusstyrka`{:class="block3looks"}: `0` betyder ingen effekt, tal upp till `100` gör sprajten ljusare och negativa siffror ner till `-100` gör sprajten mörkare
+ `spöke`{:class="block3looks"}: `0` betyder ingen effekt, och tal upp till `100` gör sprajten mer genomskinlig

Försök att `sätta`{:class="block3looks"} de olika effektvärdena för att se vad var och en gör. Utforska hur olika effektförändringar får din sprajt att se ut.

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**Tips:** En `färgeffekt`{:class="block3looks"} på `225` är samma som en `färgeffekt`{:class="block3looks"} på `25` så du kan fortsätta att ändra färgen. För andra bildeffekter kommer inget ändras efter att du har uppnått det högsta eller lägsta antalet för effekten.

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

Använd `"ta bort grafisk effekt"`{:class="block3looks"}-blocket för att börja om. Att klicka på den gröna flaggan rensar också alla bildeffekter.

För att ställa in en bildeffekt på en sprajt när projektet startas, placera ett `"sätt bildeffekt till"`{:class="block3looks"}-block under ett `"när den gröna flagga klickas på"`{:class="block3events"}-block:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Tips:** Du kan även `ställa in`{:class="block3looks"} och `ändra`{:class="block3looks"} bildeffekter för **scenen**.
