**Iziphumo zoMqhagi**: [Bona ngaphakathi](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Iibhloko `misela isiphumo sombala ku`{:class="block3looks"} kunye `tshintsha isiphumo sombala ngo`{:class="block3looks"} zombini zinemenyu ezilahlayo onokukhetha kuzo kuluhlu lweziphumo ezahlukeneyo zokuzoba ngekhompyutha ezinokusetyenziswa ukutshintsha inkangeleko yesprite sakho:

+ `umbala`{:class="block3looks"}: ukusuka `0` ukuya ku `199` (amanani amakhulu azakuzisongela, lonto ithetha ukuba `200` uyakufana no `0`)
+ `Iliso lentlanzi`{:class="block3looks"}: `0` uthetha ukuba akukho siphumo, amanani amakhulu abangela isiphumo esikhulu 'selihlo lentlanzi', kwaye amanani athabathayo abangela isiphumo 'selihlo lentlanzi' sibuyele umva
+ `Isivunguvungu`{:class="block3looks"}: `0` uthetha ukuba akukho siphumo, amanani amakhulu enza isivunguvungu esikhulu ukuya ekhohlo, kwaye amanani amakhulu athabathayo enza isivunguvungu esikhulu ekunene
+ `ubufiliba beskwere`{:class="block3looks"}: `0` uthetha ukuba akukho siphumo, kwaye amanani amakhulu enza ubufiliba beskwere obuniznzi/obukhulu
+ `umfanekiso wengceba`{:class="block3looks"}: `0` uthetha ukuba akukho siphumo, kwaye amanani amakhulu okanye athabathayo achaphazela inani leengceba
+ `ukuqaqamba`{:class="block3looks"}: `0`  uthetha ukuba akukho siphumo, abanani aphela `100` enza isprite siqaqambe kancinci, kwaye amanani athabathayo ukuya ku`100` enza isprite siqaqambe kakhulu
+ `Ubufiliba`{:class="block3looks"}: `0` uthetha ukuba akukho siphumo, kwaye amanani ukuya kuthi ga ku `100` yenza i-sprite icace ngakumbi

Zama uku `misela`{:class="block3looks"} amanani eziphumo ezahlukileyo ukubona ukuba singasinye isiphumo senza ntoni. Jonga ukuba utshintsho lwesiphumo esahlukeneyo ngasinye senza umohluko mni kwimbonakalo yesprite yakho.

```blocks3
set [Isivunguvungu v] effect to (100)

set [ubufiliba beskwere v] effect to (50)
```

Ingcebiso `Isiphumo sombala`{:class="block3looks"} u`225` sifana ne `Isiphumo sombala`{:class="block3looks"} u`25`, ungaqhubeka ukumana utshintsha umbala. Kwezinye iziphumo zokuzoba ngekhompyutha, alukho olunye utshintsho oluya kwenzeka emva kokuba ufikelele kwelona nani liphezulu okanye lisezantsi lesiphumo.

```blocks3
forever
change [umbala v] effect by [25]
wait [0.5] seconds
```

Sebenzisa ibhloko `cima iziphumo zokuzoba ngekhompyutha`{:class="block3looks"} ukuze uqalele. Ukucofa iflegi eluhlaza kuyakucima zonke iziphumo zokuzoba ngekhompyutha.

Ukumisela iziphumo zokuzoba ngekhompyutha kwisprite xa iprojekthi iqalwa, beka  `misela iziphumo zokuzoba ngekhompyutha ku`{:class="block3looks"} phantsi kwebhloko `xa iflegi eluhlaza icofiwe`{:class="block3events"}:

```blocks3
when green flag clicked
set [Ubufiliba v] effect to (25)
```

**Ingcebiso:** Uyakwazi noku `misela`{:class="block3looks"} uphinde u`Tshintshe`{:class="block3looks"} iziphumo zokuzoba ngekhompyutha ze**Qonga**.
