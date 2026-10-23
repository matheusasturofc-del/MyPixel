# MyPixel

Editor de texturas em pixel art para resource packs do Minecraft, feito para o
pack **Majestic Diamond** (1.8). Roda direto no navegador: não precisa instalar nada.

## Como usar

1. Abra o `index.html` no navegador (Chrome, Edge ou Firefox). Também funciona
   publicado no GitHub Pages.
2. Clique em **Abrir pack (.zip)** e escolha o zip do seu pack (ou arraste o
   zip para a página). No computador também dá para usar **Abrir pasta**.
3. Clique numa textura da lista para abrir, ou use **Abrir conjunto** para
   abrir várias lado a lado: mira, lãs, espadas, arco, poções, armaduras...
4. Pinte e depois baixe:
   - **Baixar pack**: o pack inteiro, com as suas edições, pronto para a pasta
     `resourcepacks`.
   - **Só as editadas**: um pack pequeno só com o que você mudou (funciona
     sozinho no jogo, o resto fica com a textura original).
   - **Baixar PNG**: só a textura selecionada.

As edições ficam salvas no navegador enquanto você trabalha: se a página
fechar, abra o mesmo pack de novo e elas voltam.

## Ferramentas

| Tecla | Ferramenta | O que faz |
|---|---|---|
| B | Lápis | Pinta pixels. **Shift + clique** faz uma linha reta desde o último ponto. |
| E | Apagar | Deixa os pixels transparentes. |
| G | Balde | Pinta a área da mesma cor. Sem "Só a área encostada", pinta essa cor na textura inteira. |
| I | Pegar | Pega a cor de um pixel e volta para a ferramenta de antes. |
| L | Linha | Linha reta. Com **Shift**, trava em 0°, 45° ou 90°. |
| U | Retângulo | Contorno ou preenchido. Com **Shift**, vira quadrado. |
| O | Círculo | Círculo ou elipse, contorno ou preenchido. Com **Shift**, fica redondo. |
| D | Luz | Clareia ou escurece os pixels por onde passa (bom para luz e sombra). |
| K | Xadrez | Pinta um pixel sim, um não (pontilhado, para degradês). |
| V | Mão | Seleciona um retângulo e move os pixels. Com **Alt**, duplica. |
| W | Varinha | Seleciona a área da mesma cor. **Shift + clique** soma à seleção. |
| R | Trocar | Troca uma cor pela cor atual em **todas** as texturas abertas. |

**Alt + clique** com o lápis, o balde, as formas ou o xadrez pega a cor sem
trocar de ferramenta.

### Opções do pincel

Aparecem embaixo das ferramentas, conforme a ferramenta escolhida:

- **Pincel**: tamanho de 1 a 8 pixels (teclas **[** e **]**).
- **Espelho**: pinta espelhado na horizontal (↔), na vertical (↕) ou nos dois,
  ótimo para espadas, armaduras e itens simétricos. Uma linha tracejada mostra o eixo.
- **Preenchido** (retângulo e círculo) e **Só a área encostada** (balde e varinha).

### Seleção, copiar e colar

| Atalho | Botão | O que faz |
|---|---|---|
| Ctrl+C | Copiar | Copia a seleção (sem seleção, copia a textura inteira). |
| Ctrl+X | Recortar | Copia e apaga a seleção. |
| Ctrl+V | Colar | Cola na textura ativa. Também cola imagens copiadas de outros programas. |
| Ctrl+D | Duplicar | Cria uma cópia da seleção para você arrastar (funciona no celular). |
| Enter | Fixar | Termina de mover e cola os pixels no lugar. |
| Esc | Cancelar | Desiste do movimento (ou da colagem). |
| Delete | Apagar | Apaga o que está selecionado. |
| Ctrl+A | Selecionar tudo | Seleciona a textura inteira. |

Com uma seleção, as **setas** movem 1 pixel. Para colar em outra textura,
clique no **nome** dela (em cima da imagem) para deixá-la ativa sem pintar, e
depois em **Colar**. Pixels arrastados para fora da textura são cortados.

### Girar, espelhar e ajustar cores

- **Espelhar ↔ / ↕** e **Girar 90°** (Shift+H, Shift+V, Shift+R) agem na
  seleção, ou na textura ativa inteira se não houver seleção. Girar a textura
  inteira só funciona em texturas quadradas.
- **Ajustar cores** muda matiz, saturação e brilho da seleção ou da textura
  ativa, com prévia ao vivo. **Aplicar** confirma, **Descartar** volta.

### Prévia

Mostra a textura ativa no tamanho real e repetida 3×3, para ver como ela fica
num bloco no jogo.

## Mira

O conjunto **Mira** abre só o canto do `gui/icons.png` onde fica a mira
(16x16 num pack 16x), com zoom grande e fundo escuro. O que você pinta ali vai
direto para o lugar certo do `icons.png`, e o resto da imagem (corações, fome,
armadura) não é tocado. No jogo a mira aparece com as cores invertidas contra
o fundo, então desenhe em branco e mude o formato.

## Outros atalhos

**Ctrl+Z** desfaz, **Ctrl+Y** (ou Ctrl+Shift+Z) refaz, **H** liga/desliga a grade.

Zoom e navegação na folha:

- **Rodinha do mouse**: zoom (até 64x) no ponto onde está o mouse. **+ / -** e
  o controle de zoom também funcionam. Texturas grandes, como o `icons.png`
  (256x256), vão até 16x.
- **Shift + rodinha**: rola a folha.
- **Espaço + arrastar**, ou arrastar com o **botão do meio**: move a folha.
