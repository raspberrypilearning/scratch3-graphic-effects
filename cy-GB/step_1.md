**Effeithiau Ceiliog**: [Gweld tu mewn](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Mae gan y blociau `gosod effaith lliw i`{:class="block3looks"} a `newid effaith lliw gan`{:class="block3looks"} ill dau gwymplenni lle y galli di ddewis o ystod o effeithiau graffeg y gellir eu defnyddio i newid sut mae corlun yn edrych:

+ `lliw`{:class="block3looks"}: o `0` i `199` (bydd niferoedd mwy yn lapio o gwmpas, felly mae `200` yr un peth ag `0`)
+ `llygad pysgodyn`{:class="block3looks"}: Mae `0` yn golygu dim effaith, mae rhifau mwy yn achosi effaith 'llygad pysgodyn' fwy, ac mae rhifau negyddol yn achosi effaith 'fisheye' wedi'i gwrthdroi
+ `chwyrliad`{:class="block3looks"}: mae `0` yn golygu dim effaith, mae rhifau mawr yn chwyrliad mawr i'r chwith, ac mae rhifau negyddol mawr yn gwneud chwyrliad mawr i'r dde
+ `picseleiddio`{:class="block3looks"}: mae `0` yn golygu dim effaith, ac mae rhifau mwy yn creu mwy o bicseli
+ `mosaig`{:class="block3looks"}: mae `0` yn golygu dim effaith, ac mae rhifau mwy neu negyddol yn effeithio ar nifer y copïau
+ `disgleirdeb`{:class="block3looks"}: Mae `0` yn golygu dim effaith, mae rhifau hyd at `100` yn gwneud y corlun yn ysgafnach, ac mae rhifau negyddol i lawr i `-100` yn gwneud y corlun yn dywyllach
+ `ysbryd`{:class="block3looks"}: mae `0` golygu dim effaith, ac mae rhifau hyd at `100` yn gwneud y corlun yn fwy tryloyw

Ceisia `osod`{:class="block3looks"} y gwahanol werthoedd effaith i weld beth mae pob un yn ei wneud. Arbrofa i weld sut mae gwahanol newid yr effeithiau yn gwneud i dy gorluniau edrych.

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**Awgrym:** Mae `effaith lliw`{:class="block3looks"} o `225` yr un peth ag `effaith lliw`{:class="block3looks"} o `25`, felly galli di barhau i newid y lliw. Ar gyfer effeithiau graffig eraill, ni wneir unrhyw newidiadau eraill ar ôl i ti gyrraedd y rhif uchaf neu isaf ar gyfer yr effaith.

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

Defnyddia'r bloc `clirio effeithiau graffeg`{:class="block3looks"} i gychwyn eto. Mae clicio ar y faner werdd hefyd yn clirio pob effaith graffeg.

I osod effaith graffeg ar gyfer corlun pan gaiff y prosiect ei gychwyn, rho floc `gosod effaith graffeg i`{:class="block3looks"} o dan bloc `pan fydd y fflag werdd wedi'i chlicio`{:class="block3events"}:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Awgrym:** Galli di hefyd `osod`{:class="block3looks"} a `newid`{:class="block3looks"} effeithiau graffeg ar gyfer y **Llwyfan**.
