🃏 <strong>3D Card LOL</strong>

&nbsp; &nbsp; &nbsp; &nbsp; Este projeto apresenta uma carta 3D inspirada no jogo League of Legends (LoL), utilizando HTML e CSS para criar efeitos visuais dinâmicos.

<h2>Conteúdo do Repositório</h2>
&nbsp; &nbsp; &nbsp; &nbsp; 📑 index.html: Arquivo HTML principal que define a estrutura da página. <br>
&nbsp; &nbsp; &nbsp; &nbsp; 📁 styles/: Pasta que contém o arquivo CSS (styles.css) responsável pelo estilo da página. <br>
&nbsp; &nbsp; &nbsp; &nbsp; 📁 images/: Pasta que contém as imagens utilizadas no projeto. <br>

<h2>Como Usar</h2>
&nbsp; &nbsp; &nbsp; &nbsp; ✒️ Clone este repositório: <br><br>

```
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

&nbsp; &nbsp; &nbsp; &nbsp; 📁 Abra o arquivo index.html em seu navegador web.

<h2>Notas</h2>
&nbsp; &nbsp; &nbsp; &nbsp; 📌 Ajuste as propriedades e caminhos das imagens conforme necessário para explorar diferentes efeitos visuais e técnicas de CSS.


















<br>
<br>
<br>
<br>
<br>

1. translate3d
A função translate3d é uma das funções de transformação 3D no CSS. Ela permite que você mova um elemento no espaço 3D ao longo dos eixos X, Y e Z.

Sintaxe:

css
Copiar código
translate3d(x, y, z)
x: A quantidade de movimento ao longo do eixo X.
y: A quantidade de movimento ao longo do eixo Y.
z: A quantidade de movimento ao longo do eixo Z.
Exemplo:

css
Copiar código
transform: translate3d(10px, 20px, 30px);
Isso move o elemento 10 pixels para a direita, 20 pixels para baixo e 30 pixels para frente.

2. drop-shadow
A propriedade filter com a função drop-shadow aplica uma sombra projetada a um elemento, similar a box-shadow, mas funciona com imagens e outros elementos que possuem transparências.

Sintaxe:

css
Copiar código
filter: drop-shadow(offset-x offset-y blur-radius color);
offset-x: Deslocamento da sombra no eixo X.
offset-y: Deslocamento da sombra no eixo Y.
blur-radius: Raio de desfoque da sombra.
color: Cor da sombra.
Exemplo:

css
Copiar código
filter: drop-shadow(2px 2px 2px #000);
Isso aplica uma sombra preta com 2 pixels de deslocamento em X e Y, e um desfoque de 2 pixels.

3. filter
A propriedade filter permite aplicar efeitos gráficos como desfoque, brilho, contraste, entre outros, a um elemento.

Sintaxe:

css
Copiar código
filter: none | blur() | brightness() | contrast() | drop-shadow() | grayscale() | hue-rotate() | invert() | opacity() | saturate() | sepia() | url();
Exemplo:

css
Copiar código
filter: blur(5px) brightness(0.5);
Isso aplica um desfoque de 5 pixels e reduz o brilho do elemento pela metade.

4. transform
A propriedade transform aplica uma transformação 2D ou 3D a um elemento. Isso inclui traduções, rotações, escalas, e outras transformações.

Sintaxe:

css
Copiar código
transform: none | transform-functions;
Funções Comuns:

translate(x, y): Move o elemento.
rotate(angle): Rotaciona o elemento.
scale(x, y): Redimensiona o elemento.
skew(x-angle, y-angle): Inclina o elemento.
Exemplo:

css
Copiar código
transform: translate(10px, 20px) rotate(45deg);
Isso move o elemento 10 pixels à direita e 20 pixels para baixo, e então o rotaciona 45 graus.

5. transform: perspective(900px) translateY(-5%) rotateX(25deg) translateZ(0)
Esta é uma combinação de várias transformações 3D:

Exemplo:

css
Copiar código
transform: perspective(900px) translateY(-5%) rotateX(25deg) translateZ(0);
perspective(900px): Define uma perspectiva de 900 pixels, dando um efeito de profundidade 3D.
translateY(-5%): Move o elemento 5% para cima no eixo Y.
rotateX(25deg): Rotaciona o elemento 25 graus ao redor do eixo X.
translateZ(0): Move o elemento no eixo Z, neste caso, 0 pixels, mas é útil para combinar com outras transformações 3D.
6. box-shadow
A propriedade box-shadow aplica uma ou mais sombras a um elemento.

Sintaxe:

css
Copiar código
box-shadow: offset-x offset-y blur-radius spread-radius color;
offset-x: Deslocamento da sombra no eixo X.
offset-y: Deslocamento da sombra no eixo Y.
blur-radius: Raio de desfoque da sombra.
spread-radius: Raio de expansão da sombra.
color: Cor da sombra.
Exemplo:

css
Copiar código
box-shadow: rgba(0, 0, 0, 0.25) 0px 14px 28px rgba(0, 0, 0, 0.22) 0px 10px 10px;
Isso aplica duas sombras:

rgba(0, 0, 0, 0.25) 0px 14px 28px: Uma sombra preta sem deslocamento no eixo X, 14 pixels de deslocamento no eixo Y, 28 pixels de desfoque, e sem expansão.
rgba(0, 0, 0, 0.22) 0px 10px 10px: Outra sombra preta sem deslocamento no eixo X, 10 pixels de deslocamento no eixo Y, 10 pixels de desfoque, e sem expansão.
Estas sombras adicionam profundidade e dimensão ao elemento, fazendo com que pareça elevado ou flutuante acima do fundo.
