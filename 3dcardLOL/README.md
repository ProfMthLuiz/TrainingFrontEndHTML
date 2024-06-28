# MENU

&nbsp; &nbsp; &nbsp; &nbsp; ➡️ &nbsp; [Conteúdo](#conteúdo-do-repositório) <br>
&nbsp; &nbsp; &nbsp; &nbsp; ➡️ &nbsp; [Como utilizar](#como-utilizar) <br>
&nbsp; &nbsp; &nbsp; &nbsp; ➡️ &nbsp; [NOTAS](#notas) <br>
&nbsp; &nbsp; &nbsp; &nbsp; ➡️ &nbsp; [EXPLICAÇÕES](#explicações) <br>

<h2>3D Card LOL</h2>

&nbsp; &nbsp; &nbsp; &nbsp; 🃏 Este projeto apresenta uma carta 3D inspirada no jogo League of Legends (LoL), utilizando HTML e CSS para criar efeitos visuais dinâmicos.

<h2>Conteúdo do Repositório</h2>
&nbsp; &nbsp; &nbsp; &nbsp; 📑 index.html: Arquivo HTML principal que define a estrutura da página. <br>
&nbsp; &nbsp; &nbsp; &nbsp; 📁 styles/: Pasta que contém o arquivo CSS (styles.css) responsável pelo estilo da página. <br>
&nbsp; &nbsp; &nbsp; &nbsp; 📁 images/: Pasta que contém as imagens utilizadas no projeto. <br>

<h2>Como Utilizar</h2>
&nbsp; &nbsp; &nbsp; &nbsp; ✒️ Clone este repositório: <br><br>

```
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

&nbsp; &nbsp; &nbsp; &nbsp; 📁 Abra o arquivo index.html em seu navegador web.

<h2>Notas</h2>
&nbsp; &nbsp; &nbsp; &nbsp; 📌 Ajuste as propriedades e caminhos das imagens conforme necessário para explorar diferentes efeitos visuais e técnicas de CSS. <br> <br>

<h2>Explicações</h2>

&nbsp; &nbsp; &nbsp; &nbsp; 📌 <strong>translate3d</strong> <br>
&nbsp; &nbsp; &nbsp; &nbsp; - A função translate3d é uma das funções de transformação 3D no CSS. Ela permite que você mova um elemento no espaço 3D ao longo dos eixos X, Y e Z. <br> <br>

&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Sintaxe:

```
translate3d(x, y, z)
```

&nbsp; &nbsp; &nbsp; &nbsp; - x: A quantidade de movimento ao longo do eixo X. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - y: A quantidade de movimento ao longo do eixo Y. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - z: A quantidade de movimento ao longo do eixo Z. <br><br>
&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Exemplo:

```
transform: translate3d(10px, 20px, 30px);
```

&nbsp; &nbsp; &nbsp; &nbsp; - Isso move o elemento 10 pixels para a direita, 20 pixels para baixo e 30 pixels para frente. <br> <br> <br>



&nbsp; &nbsp; &nbsp; &nbsp; 📌 <strong>drop-shadow</strong> <br>
&nbsp; &nbsp; &nbsp; &nbsp; - A propriedade filter com a função drop-shadow aplica uma sombra projetada a um elemento, similar a box-shadow, mas funciona com imagens e outros elementos que possuem transparências. <br>

&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Sintaxe:

```
filter: drop-shadow(offset-x offset-y blur-radius color);
```

&nbsp; &nbsp; &nbsp; &nbsp; - offset-x: Deslocamento da sombra no eixo X. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - offset-y: Deslocamento da sombra no eixo Y. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - blur-radius: Raio de desfoque da sombra. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - color: Cor da sombra. <br><br>
&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Exemplo:

```
filter: drop-shadow(2px 2px 2px #000);
```

&nbsp; &nbsp; &nbsp; &nbsp; - Isso aplica uma sombra preta com 2 pixels de deslocamento em X e Y, e um desfoque de 2 pixels. <br> <br> <br>



&nbsp; &nbsp; &nbsp; &nbsp; 📌 <strong> filter </strong> <br>
&nbsp; &nbsp; &nbsp; &nbsp; - A propriedade filter permite aplicar efeitos gráficos como desfoque, brilho, contraste, entre outros, a um elemento.

&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Sintaxe:

```
filter: none | blur() | brightness() | contrast() | drop-shadow() | grayscale() | hue-rotate() | invert() | opacity() | saturate() | sepia() | url();
```

&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Exemplo:

```
filter: blur(5px) brightness(0.5);
```

&nbsp; &nbsp; &nbsp; &nbsp; - Isso aplica um desfoque de 5 pixels e reduz o brilho do elemento pela metade.  <br> <br> <br>



&nbsp; &nbsp; &nbsp; &nbsp; 📌 <strong>transform</strong> <br>
&nbsp; &nbsp; &nbsp; &nbsp; -A propriedade transform aplica uma transformação 2D ou 3D a um elemento. Isso inclui traduções, rotações, escalas, e outras transformações. <br>

&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Sintaxe:

```
transform: none | transform-functions;
```

&nbsp; &nbsp; &nbsp; &nbsp; - Funções Comuns: <br>
&nbsp; &nbsp; &nbsp; &nbsp; - translate(x, y): Move o elemento. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - rotate(angle): Rotaciona o elemento. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - scale(x, y): Redimensiona o elemento. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - skew(x-angle, y-angle): Inclina o elemento. <br> <br>
&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Exemplo:

```
transform: translate(10px, 20px) rotate(45deg);
```

&nbsp; &nbsp; &nbsp; &nbsp; - Isso move o elemento 10 pixels à direita e 20 pixels para baixo, e então o rotaciona 45 graus.  <br> <br> <br>



&nbsp; &nbsp; &nbsp; &nbsp; 📌  <strong> transform: perspective(900px) translateY(-5%) rotateX(25deg) translateZ(0) </strong> <br>
&nbsp; &nbsp; &nbsp; &nbsp; - Esta é uma combinação de várias transformações 3D: <br>

&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Exemplo:

```
transform: perspective(900px) translateY(-5%) rotateX(25deg) translateZ(0);
```

&nbsp; &nbsp; &nbsp; &nbsp; - perspective(900px): Define uma perspectiva de 900 pixels, dando um efeito de profundidade 3D. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - translateY(-5%): Move o elemento 5% para cima no eixo Y. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - rotateX(25deg): Rotaciona o elemento 25 graus ao redor do eixo X. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - translateZ(0): Move o elemento no eixo Z, neste caso, 0 pixels, mas é útil para combinar com outras transformações 3D. <br> <br> <br>



&nbsp; &nbsp; &nbsp; &nbsp; 📌  <strong> box-shadow </strong> <br>
&nbsp; &nbsp; &nbsp; &nbsp; - A propriedade box-shadow aplica uma ou mais sombras a um elemento. <br>

&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Sintaxe:

```
box-shadow: offset-x offset-y blur-radius spread-radius color;
```

&nbsp; &nbsp; &nbsp; &nbsp; - offset-x: Deslocamento da sombra no eixo X. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - offset-y: Deslocamento da sombra no eixo Y. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - blur-radius: Raio de desfoque da sombra. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - spread-radius: Raio de expansão da sombra. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - color: Cor da sombra. <br> <br>
&nbsp; &nbsp; &nbsp; &nbsp; ✏️ Exemplo:

```
box-shadow: rgba(0, 0, 0, 0.25) 0px 14px 28px rgba(0, 0, 0, 0.22) 0px 10px 10px;
```

&nbsp; &nbsp; &nbsp; &nbsp; - Isso aplica duas sombras: <br>
&nbsp; &nbsp; &nbsp; &nbsp; - rgba(0, 0, 0, 0.25) 0px 14px 28px: Uma sombra preta sem deslocamento no eixo X, 14 pixels de deslocamento no eixo Y, 28 pixels de desfoque, e sem expansão. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - rgba(0, 0, 0, 0.22) 0px 10px 10px: Outra sombra preta sem deslocamento no eixo X, 10 pixels de deslocamento no eixo Y, 10 pixels de desfoque, e sem expansão. <br>
&nbsp; &nbsp; &nbsp; &nbsp; - Estas sombras adicionam profundidade e dimensão ao elemento, fazendo com que pareça elevado ou flutuante acima do fundo. <br><br>

&nbsp; &nbsp; &nbsp; &nbsp; ⬆️ &nbsp; [Início](#menu) <br>
