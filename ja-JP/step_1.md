**ニワトリの画像効果**： [Scratchの内部を見る](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

`色の効果を`{:class="block3looks"}に設定する、そして `色の効果を`{:class="block3looks"}ブロック毎に変える。どちらにもドロップダウンメニューがあり、さまざまな画像効果を選択でき、スプライトの外観を変えることができます。

+ `色`{:class="block3looks"}: `0` から `199` までの間で選べます。(それより大きい数字は最初の数字に戻ります。 `200` は `0` と同じです。)
+ `魚眼レンズ`{:class="block3looks"}: `0` は画像効果なしです。数値が大きいほど「魚眼レンズ」効果が大きくなり、負の数は逆向きの「魚眼レンズ」効果になります。
+ `渦巻き`{:class="block3looks"}: `0` は画像効果なしです。大きな数字は大きな渦巻きを左回りに作り、大きな負の数は右回りの渦巻きを作ります。
+ `ピクセル化`{:class="block3looks"}: `0` は画像効果なしです。数が大きいほど多くのピクセルに分けられます。
+ `モザイク`{:class="block3looks"}: `0` は画像効果がなしです。大きい数または負の数によってコピー数が決まります。
+ `明るさ`{:class="block3looks"}: `0` は画像効果なしです。 数を`100` まで上げていくとでスプライトはより明るくなり、負の数を`-100`まで下げていくと スプライトはより暗くなります。
+ `幽霊`{:class="block3looks"}: `0` は画像効果なしです。数を`100` まで上げていくとスプライトはより透明になります。

画像効果の値をいろいろ `設定`{:class="block3looks"}してみて、それぞれがどんな効果になるかを確認してください。 さまざまな画像効果によってスプライトがどのように違って見えるかを調べましょう。

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**ヒント:** A `色の効果`{:class="block3looks"}を `225`にすることは `色の効果`{:clsss="block3looks"} を`25`にすることと同じです。これにより、色を変え続けることができます 。 他の画像効果の場合、数値が最大または最小に達した後は、それ以上の変化はありません。

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

`画像効果をなくす`{:class="block3looks"}ブロックを使用すると最初に戻ります。 緑の旗をクリックしても、すべての画像効果がクリアされます。

プロジェクトが開始されたときにスプライトの画像効果を設定するには、 `色の効果を設定する`{:class="block3looks"}ブロックを `緑色のフラグが押されたとき`{:class="block3events"}ブロックの下に置きます。

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**ヒント:** **ステージ**に対しても、画像効果を `設定`{:class="block3looks"}したり、 `変更`{:class="block3looks"}したりできます。
