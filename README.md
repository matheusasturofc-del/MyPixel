# MyPixel

Editor de texturas em pixel art para resource packs do Minecraft, feito para o
pack **Majestic Diamond** (1.8). Roda direto no navegador: não precisa instalar nada.

## Como usar

1. Abra o `index.html` no navegador (Chrome, Edge ou Firefox). Também funciona
   publicado no GitHub Pages.
2. Clique em **Abrir pack (.zip)** e escolha o zip do seu pack (ou arraste o
   zip para a página). No computador também dá para usar **Abrir pasta**.
3. Clique numa textura da lista para abrir, ou use **Abrir conjunto** para
   abrir várias lado a lado: todas as lãs, espadas, arco, poções, armaduras...
4. Pinte e depois baixe:
   - **Baixar pack**: o pack inteiro, com as suas edições, pronto para a pasta
     `resourcepacks`.
   - **Só as editadas**: um pack pequeno só com o que você mudou (funciona
     sozinho no jogo, o resto fica com a textura original).
   - **Baixar PNG**: só a textura selecionada.

As edições ficam salvas no navegador enquanto você trabalha: se a página
fechar, abra o mesmo pack de novo e elas voltam.

## Mira

O conjunto **Mira** abre só o canto do `gui/icons.png` onde fica a mira
(16x16 num pack 16x), com zoom grande e fundo escuro. O que você pinta ali vai
direto para o lugar certo do `icons.png`, e o resto da imagem (corações, fome,
armadura) não é tocado. No jogo a mira aparece com as cores invertidas contra
o fundo, então desenhe em branco e mude o formato.

## Ferramentas

| Tecla | Ferramenta | O que faz |
|---|---|---|
| B | Lápis | Pinta pixels. Arraste para desenhar. |
| E | Apagar | Deixa o pixel transparente. |
| G | Balde | Pinta a área de mesma cor encostada no pixel. |
| I | Pegar | Pega a cor de um pixel. |
| V | Mão | Arraste para selecionar; arraste dentro da seleção para mover os pixels. Com **Alt**, duplica em vez de mover. |
| R | Trocar | Troca uma cor pela cor atual em **todas** as texturas abertas. |

Com uma seleção ativa: **setas** movem 1 pixel, **Enter** fixa, **Esc** cancela
o movimento (os pixels voltam para onde estavam), **Delete** apaga e **Ctrl+A**
seleciona a textura inteira. No celular, use os botões do painel **Seleção**.
Pixels arrastados para fora da textura são cortados quando você fixa.

Outros atalhos: **Ctrl+Z** desfaz, **Ctrl+Y** (ou Ctrl+Shift+Z) refaz, **+ / -**
ou **Ctrl + rodinha do mouse** mudam o zoom (até 64x), **H** liga/desliga a grade.
Texturas grandes, como o `icons.png` (256x256), vão até 16x.

A paleta **Cores das texturas abertas** mostra as cores mais usadas nas
texturas da folha, para você manter o mesmo estilo em todas.
