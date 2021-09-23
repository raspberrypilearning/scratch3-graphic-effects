**Efeitos de galo**: [Veja interior](https://scratch.mit.edu/projects/435730522/editor){: target = "_ blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

O `Configurar efeito de cor para`{: class = "block3looks"} e `altera o efeito de cor em`blocos {: class = "block3looks"}, ambos têm menus suspensos nos quais você pode escolher entre uma variedade de efeitos gráficos que podem ser usados para alterar a aparência do seu ator:

+ `cor`{:class="block3looks"}: de `0` para `199` (maiores números serão agrupados, então`200` é o mesmo que `0`)
+ `olho de peixe`{:class="block3looks"}: `0` não altera nada, números maiores dão um efeito maior, e números negativos têm o efeito contrário
+ `olho de peixe`{: class = "block3looks"}: `0` não altera nada, números maiores dão um efeito maior, e números negativos têm o efeito contrário
+ `pixelado`{: class = "block3looks"}: `0` nenhuma alteração, números maiores ou positivos criam mais pixels
+ `mosaico`{:class="block3looks"}: `0` nenhuma alteração, números maiores ou negativos afetam o número de cópias
+ `brilho`{: class = "block3looks"}: `0` nenhuma alteração, números até `100` deixam o ator mais claro e números negativos até `-100` deixam o ator mais escuro
+ `fantasma`{: class = "block3looks"}: `0` nenhuma alteração, números até `100` afetam a transparência do ator

Tente `alterar`{: class = "block3looks"} os valores do efeito para ver o que cada um faz. Veja como mudanças no efeito afetam a aparência de seu ator.

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**Dica:** Um `efeito de cor`{:class="block3looks"} de `225` é o mesmo que `efeito de cor`{:class="block3looks"} of `25`, então você pode continuar alterando a cor. Para outros efeitos gráficos, nenhuma alteração será feita depois que você atingir o número máximo ou mínimo para o efeito.

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

Use o bloco `efeitos gráficos claros`{:class="block3looks"} para começar de novo. Clicar na bandeira verde também limpa todos os efeitos gráficos.

Para definir o efeito gráfico de um ator assim que o projeto for iniciado, coloque um bloco `definir efeito gráfico para`{:class="block3looks"} sob um bloco `quando a bandeira verde é clicada`{:class="block3events"}:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**Dica:** Você também pode `definir`{: class = "block3looks"} e `alterar`{: class = "block3looks"} efeitos gráficos para o **Palco**.
