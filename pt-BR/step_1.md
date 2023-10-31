**Efeitos de galo**: [Ver interior](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

Ambos os blocos `defina o efeito cor como`{:class="block3looks"} e `mude ao efeito cor`{:class="block3looks"} têm menus suspensos nos quais você pode escolher entre uma variedade de efeitos gráficos que podem ser usados para alterar a aparência do seu ator:

+ `cor`{:class="block3looks"}: de `0` até `199` (números maiores serão continuações, então `200` é o mesmo que `0`)
+ `olho de peixe`{:class="block3looks"}: `0` é sem efeito, números maiores causam um efeito 'olho de peixe' maior, e números negativos causam um efeito 'olho de peixe' invertido
+ `turbilhão`{:class="block3looks"}: `0` é sem efeito, números grandes fazem um grande turbilhão para esquerda e números grandes negativos fazem um grande turbilhão para a direita
+ `pixelado`{:class="block3looks"}: `0` é sem efeito e números maiores criam mais pixels
+ `mosaico`{:class="block3looks"}: `0` é sem efeito, números maiores ou negativos afetam o número de cópias
+ `brilho`{:class="block3looks"}: `0` é sem efeito, números até `100` deixam o ator mais claro e números negativos até `-100` deixam o ator mais escuro
+ `fantasma`{:class="block3looks"}: `0` é sem efeito, números até `100` tornam o ator mais transparente

Tente `definir`{:class="block3looks"} os diferentes valores de efeito para ver o que cada um faz. Explore como diferentes efeitos alteram a aparência de seu ator.

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**Dica:** Um `efeito de cor`{:class="block3looks"} de `225` é o mesmo que um `efeito de cor`{:class="block3looks"} de `25`, então você pode continuar alterando a cor. Para outros efeitos gráficos, nenhuma alteração será feita depois que você atingir o número máximo ou mínimo para o efeito.

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

Use o bloco `efeitos gráficos claros`{:class="block3looks"} para começar de novo. Clicar na bandeira verde também limpa todos os efeitos gráficos.

Para definir um efeito gráfico para um ator assim que o projeto for iniciado, coloque um bloco `defina o efeito gráfico como`{:class="block3looks"} sob um bloco `quando a bandeira verde for clicada`{:class="block3events"}:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Dica:** Você também pode `definir`{:class="block3looks"} e `alterar`{:class="block3looks"} efeitos gráficos para o **Palco**.
