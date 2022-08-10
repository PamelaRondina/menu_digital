Olá! 😊

Sou iniciante no mundo da programação e este é o meu primeiro projeto em Html e CSS. 🤩 Bora para mais uma aventura! 🚀 🌟

Veja o resultado deste projeto pelo QR Code abaixo, ou pelo [LINK](https://relaxed-haupia-b9e61f.netlify.app/)

![image](https://user-images.githubusercontent.com/108991648/183966304-814862f2-17fd-4145-8ac0-312d3cb3fb6c.png)



_______________

# Maratona Explorer 3.0 - Rocketseat

Este projeto visa realizar um menu digital com QR Code, utilizaremos da tecnologia de Front-End com Html e CSS.

**[Aula 01 - Iniciando nosso código](https://github.com/PamelaRondina/menu_digital#aula-01---iniciando-nosso-c%C3%B3digo-)**

- [x] O que é HTMl?
- [x] Conhecendo sobre tag, sintaxes, atributos
- [x] Iniciando o código

**[Aula 02 - Vamos estilizar o programa](https://github.com/PamelaRondina/menu_digital#aula-02---vamos-estilizar-o-programa)**

- [x] O que é CSS?
- [x] Conhecendo sobre declarações, comentários
- [x] Colorir o projeto
- [x] Adicionar e editando o box model

**[Aula 03 - Fontes e textos ](https://github.com/PamelaRondina/menu_digital#aula-03---fontes-e-textos)**

- [x] Editando as fontes
- [x] Utilizando o VS Code
- [x] Salvando o site no computador
- [x] Criando link de acesso ao site
- [x] Gerar o QR Code
- [x] Alterações no site   

**[Novas metas!](https://github.com/PamelaRondina/menu_digital#novas-metas)**

Nesta etapa, vou incluir os próximos passos deste projeto.

- [x] Adicionando imagem
- [x] Adicionando 
__________

## Instrutor
- Mayk Brito
__________

## Aula 01 - Iniciando nosso código 😁

### O que é HTML? 

> Hypertext Markup Language (Linguagem de Marcação de Texto)

Não é uma linguagem de programação, ela serve para estruturar textos, criar links, vídeos, imagens, etc;

Para compreender melhor,  [Comandos em HTML](https://github.com/PamelaRondina/step-by-step/blob/main/html/comandos_html.md)

### Iniciando o código...

Optei utilizar o editor VSCode, vamos abrir um `novo_arquivo.html` e `! + enter`, o próprio editor incluirá a estrutura básica de um html

- [x] Dentro do código estão alguns comentários
- [x] Vamos indentar para ter uma melhor visualização do código: selecionar de `<head>` até `</body>` e dar um TAB
- [x] Na parte `head` podemos incluir informações que não aparecerão na página

```html
<!DOCTYPE html>
<html lang="pt-br"> <!-- alterar para pt-br (portugês brasileiro) 
<meta http-equiv="X-UA-Compatible" content="IE=edge"> DELETAR-->
<head>
    <meta charset="UTF-8"> <!-- Serve para não ter erro em acentuações e caracteres especiais -->
      <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Viewport serve para melhorar a visualização em aparelhos móveis e no navegador  -->
    <title>Document</title> <!-- Nome do que aparecerá no Browser -->
</head>
<body>
    
</body>
</html>
```
Agora que entendemos alguns itens, vamos alterar os nomes:

- [x] title para "Menu Digital"
- [x] O título para "Cafeteria Sensações"

Vamos incluir novas tags entre o `<body>` e `</body>`
- [x] `<header>` abrir cabeçalho
- [x] `<h1>Título</h1>` título
- [x] `<p>Aberto todos os dias. 8h-21h</p>` parágrafo
- [x] `</header>` Fechar cabeçalho
 
```html
<body>
    <header>
        <h1>Cafeteria Sensações</h1>
        <p>Aberto todos os dias. 8h-21h</p>
    </header>
</body>
```
No VSCode para visualizar no navegador:

* Clique com o botão direito no nome do arquivo
* Clique em "Show in Browser"
* Em seguida, o arquivo será aberto diretamente no navegador

![image](https://user-images.githubusercontent.com/108991648/183738057-5121a0d4-2398-4b96-9d9d-737e18996603.png)


![image](https://user-images.githubusercontent.com/108991648/183737473-e5f7769b-614c-4524-b33e-cce24d49e729.png)



Abaixo de `</header>` vamos incluir:

- [x] `<section>` abrir seção
- [x] `<h2>Brunch</h2>` subtítulo
- [x] `<ul>` abrir lista não ordenada (com pontinhos)
- [x] `<li>` abrir item da lista
- [x] `<div>` abrir caixa genérica
- [x] `<h3>Waffle Doce</h3>` subtítulo do subtítulo
- [x] `<p>Lorem</p>` aqui, você deve escrever "lorem e apertar *enter*"
> É um texto apenas para referência, criará um texto qualquer. Podemos apagar parte deste texto

- [x] `</div>` fechar caixa genérica 
- [x] `<strong>` Abrir para incluir o valor R$00.00
- [x] `</strong>` Fechar
- [x] `</li>` fechar item da lista
- [x] `</ul>`fechar lista não ordenada
- [x] `</section>` fechar seção
 
 Incluir classes, para usarmos no CSS:
- [x] Após div `<div class="details">`
- [x] Após p `<p class="description">`
- [x] Após strong `<strong class="price">`

```html
<section>
    <h2>Brunch</h2>

    <ul>
        <li>
            <div class="details">
                <h3>Waffle Doce</h3>
                <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
            </div>

            <strong class="price">
            R$37.70
            </strong>
        </li>
    </ul>
</section>
```

![image](https://user-images.githubusercontent.com/108991648/183742944-be0dd4eb-2b07-4b14-b2e7-4ae669550e97.png)

Para incluir mais itens na lista
- [x] Copie de `<li>` até `</li>` 
- [x] Altere: o subtítulo do subtítulo, o parágrafo e o valor.

Para incluir mais seções
- [x] Copie de `<section>` até `</section>`
- [x] Altere o subtítulo e também os dados da lista

![image](https://user-images.githubusercontent.com/108991648/183744139-e12e38ef-9b7d-43c2-a4ea-d3a1e4224eca.png)

Nossa aula acaba por aqui, até a próxima! :)
___________

## Aula 02 - Vamos estilizar o programa

Neste momento, vamos melhorar o visual do nosso menu digital, dando cor e detalhes ao nosso programa. Iremos adicionar e ajustar espaçamentos, incluir o box model e muito mais...

Bora ver como esse projeto ficará!

### O que é CSS?

> Cascading Style Sheets (Folha de Estilo em Cascata)

Tecnologia que serve para apresentar o visual para o cliente, dando estilos para o Html

#### Princípios que nos ajudarão a codar em CSS!

**Declaration - Declaração**

Quais são as propriedades e valores que serão aplicadas no elemento:

- [x] `body` - (corpo) seletor
- [x] **{** - abre chaves
- [x] `background` - propriedade
- [x] `red`- valor (alterar os estilos dos elementos)
- [x] **}** - fecha chaves 

```css
body {
    background: red;
}
```
**Comentários**

Em CSS para inserir um comentário: `/*texto*/` 


**Cascata**

Tendo 2 declarações, a última será o de maior relevância.

```css
body {
    background: red;
}

body {
    background: blue;
}
```
> Neste exemplo, o body será de cor blue

Porém, a cascata perde essa prioridade devido à especificidade, cada seletor terá um peso e sua soma trará a relevância de prioridade.

```css
#id {
    /* peso 100*/
}

.class {
    /* peso 10*/
}

element {
    /* peso 1*/
}
```

![image](https://user-images.githubusercontent.com/108991648/183656135-7636b011-67da-4123-90c9-d3ae5f2f2cfe.png)


> Não inciar com numeral ou caracteres especiais os nomes de *id*, *class* e *element* ( _ é aceito)


## Bora colorir esse projeto! 🎨

Abra um novo arquivo em seu editor `nome_arquivo.css`

> Utilizo o VSC, para ter o preview: Extensão [Live Preview]( https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)

No arquivo principal em html inclua `<link rel="stylesheet" href="arquivo_em_css.css" />`, após, terá o preview no próprio VSC.

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estética</title>
    <link rel="stylesheet" href="conteudo_estilo.css" />

</head>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/183653303-34cf3db9-f9df-4282-98e5-668f73d2866d.png)

_____


#### Edições

**Editar o Body**

Será a cor do projeto, o que vai aparecer aos fundos:

![image](https://user-images.githubusercontent.com/108991648/183658216-57afdd9b-3727-44f7-aac1-4247d5555ee8.png)

```css
body {
    background-color:lightpink;
}
```

Para escolher a cor certa!
 [1. Homehost - Tabela de Cores](
https://www.homehost.com.br/blog/tutoriais/tabela-de-cores-html/)
[2. Erika Sarti - Tabela de Cores](https://erikasarti.com/html/tabela-cores/)

**Remover estilos**

Podemos remover ou alterar os estilos, basta mudar none para outro formato:

```css
ul {

    list-style: none;
}
```
![image](https://user-images.githubusercontent.com/108991648/183664916-1c72bbf1-93e4-47fe-84c3-4994aec47255.png)

**Remover espaços e preenchimentos**

* margin = espaços;
* padding = preenchimento.

```css
* {
    margin: 0;
    padding: 0;
}
```
![image](https://user-images.githubusercontent.com/108991648/183666072-e832e9cc-9c38-4deb-bbd0-c2967f701ee5.png)

___________

#### Box Model EMOJI CAIXA

Os elementos em Html serão em caixas

![image](https://user-images.githubusercontent.com/108991648/183666697-24e68149-7ece-49c6-9fa8-58e655f8749c.png)

Item | Descrição
-|-
margin | margem
border | borda
px | pixel (unidade de medida)
height | altura
padding | preenchimento da caixa
max-width | largura máxima da caixa
margin-bottom | espaço abaixo

Vamos estilizar por caixas. Em nosso código em html, minimizando as demais informações, temos. 

- [x] body
- [x] header
- [x] section

![image](https://user-images.githubusercontent.com/108991648/183681102-33a6a6fb-e9bf-4514-b35f-21e6ea22abe9.png)

Além disso, dentro de **section** temos:

- [x] h2
- [x] ul
- [x] li



![image](https://user-images.githubusercontent.com/108991648/183700044-bd51768d-907f-472c-a001-10fa7808e638.png)


Vamos iniciar nossa estilização em `header - html`

```html
<header>
        <h1>Cafeteria</h1>
        <p>Aberto todos os dias. 8h-21h</p>
    </header>
```
- [x] `max-widht` largura máxima da caixa
- [x] `border` borda, neste caso, apenas para visualizarmos onde estamos editando (vamos deletar)
- [x] `margin-left: auto`e `margin-right: auto` vai centralizar a caixa
    - Ou podemos utilizar `margin: 0 auto`
- [x] `padding` 32px cima/baixo e 0px laterais  
- [x] `text-align: center` texto alinhado ao centro

```css
header {
    max-width: 300px;
    border: 1px solid red;
    margin-left: auto;
    margin-right: auto;

    /* margin: 0 auto*/

    text-align: center;
    padding: 32px 0;
}
```
![image](https://user-images.githubusercontent.com/108991648/183691985-07e26996-18a4-419c-bcef-efe7f44d6754.png)

> Vamos deletar o `border`

No próximo item temos `section`. Podemos fazê-lo das seguintes formas:

Estilo 1.
```css
header {
    max-width: 300px;
    margin: 0 auto

    text-align: center;
    padding: 32px 0;
}

section
    max-width: 300px;
    border: 1px solid red;
    margin: 0 auto
```
Estilo 2.

- [x] Incluímos `header,`
- [x] As informações que se repetem em ambos passamos para abaixo de `section` (max-width,margin)

```css
header {
    padding: 32px 0;
    text-align: center;
}

header,
section {
    max-width: 300px;
    margin: 0 auto; 
  
}
```

![image](https://user-images.githubusercontent.com/108991648/183694420-c32c5634-7898-474f-82d6-a2c2002f0630.png)

**Editar Brunch / Bebidas**

Este item está dentro de `section e h2` e o nome do subítulo de cada seção.

![image](https://user-images.githubusercontent.com/108991648/183703799-a60e64ac-0d6a-400f-947c-64054cd4cda2.png)

- [X] `background-color` - altera o body deste item
- [x] `padding` 8px cima/baixo 16px laterais
- [x] `text-align:` central
- [x] `margin-bottom` espaço abaixo

```css   
section h2 {
   background-color: #FED7AA;
   padding: 8px 16px;
   text-align: center;

    margin-bottom: 24px;
}
```
![image](https://user-images.githubusercontent.com/108991648/183715299-e50c40a6-3009-485c-a227-db83acaaf557.png)


**Editar espaço entre ul / li**

Este item entre a palavra **Brunch** e **Waffle**:

![image](https://user-images.githubusercontent.com/108991648/183704015-63f05ef4-f70b-407d-8497-8ac469c7d8bc.png)

- [x] `margin-bottom` espaço abaixo

```css
ul li {
    margin-bottom: 16px;
}
```

**Editar R$ ao lado de Waffle Doce**

 Dentro de li temos duas caixas `div` e `strong`

![image](https://user-images.githubusercontent.com/108991648/183706492-eb3b97c9-c974-490a-b927-7d7fa28cfdf7.png)

- [x] `displey: flex` faz com que os elementos fiquem um ao lado do outro

```css
ul li {
    margin-bottom: 16px;
    display: flex;
}
```
![image](https://user-images.githubusercontent.com/108991648/183707237-39ad73f5-7424-493b-a901-87695f5817d5.png)

**Editar espaço da caixa Waffle + R$**  

Na linha `<div class="details">`

![image](https://user-images.githubusercontent.com/108991648/183708292-1a237bbf-df07-480f-b446-230ded20f107.png)

Estamos pedindo para o programa procurar dentro de li um elemento que possui a classe chamada "details"

- [x] `max-widht` largura máxima da caixa

```css
li .details {
    max-width: 240px;
}
```
**Tendo mais de 1 (uma) seção, alterar o espaço abaixo entre elas**


![image](https://user-images.githubusercontent.com/108991648/183709071-d8385ff6-8b33-4764-8357-2f4bdf40f367.png)

```css
section {
    margin-bottom: 24px;
}
```

**Editar Cor do título**

- [x] Adicionar tag `<span>` entre "Sensações" no arquivo html

![image](https://user-images.githubusercontent.com/108991648/183710451-210393c4-af71-4946-a6b7-414c0e2c0506.png)

No arquivo CSS adicionar:

```css
header h1 span {
    color: #995000;
}
```

![image](https://user-images.githubusercontent.com/108991648/183711437-9acc480e-a56c-4195-858a-45a88275797f.png)

**Adicionar espaçamento abaixo entre Waffle e o texto**

![image](https://user-images.githubusercontent.com/108991648/183712463-3b1aabcf-5ff3-4cac-b179-ca220bee04f6.png)

```css

.details h3 {
    margin-bottom: 8px;
}
```

E nossa aula 02, foi finalizada com grande estilo, ou melhor, com um menu totalmente cheio de estilos... 

😍😍

![image](https://user-images.githubusercontent.com/108991648/183715593-204dfe1b-d1b6-404b-8739-ffa94f1199eb.png)

_____________


## Aula 03 - Fontes e textos

Chegamos em nossa última aula, que projeto incrível!! 😍🥰

Vamos modificar as fontes e os textos, criar um link para acesso remoto e gerar o QRCOde

### Editando as Fontes

Em [Fontes Google](https://fonts.google.com/) vamos escolher nossa fonte favorita.

- [x] Clique na fonte que achar ideal
- [x] Escolha o tamanho
- [x] Adicione no +
- [x] O site vai gerar duas informações:
    1. Link para ser colado no arquivo em html
    2. Instruções para serem realizadas no arquivo CSS

![image](https://user-images.githubusercontent.com/108991648/183771647-0789b9b8-bf01-4bee-83ea-e7edddd65fcc.png)

Retonar para o arquivo em html
- [x] Colar o link 1. após `<head>`
- [x] E ajustar indentação

```html
<head>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Oleo+Script+Swash+Caps&display=swap" rel="stylesheet">
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Digital</title>
    <link rel="stylesheet" href="conteudo_estilo.css" />

</head>
```

Retornar para o arquivo em CSS
- [x] Colar o link 2. dentro de`body`, abaixo da cor

```css
body {
    background-color: #FEEDD5;
    font-family: 'Oswald', sans-serif; && font-family: 'Roboto Mono', monospace;
}
```

**Editar elementos**

- [x] Informar quais elementos vamos alterar a fonte `h1, h2, h3 .price`
- `text-transform: uppercase` letra MAIÚSCULA

```css
/*Fontes*/
h1, h2, h3, .price {
    fonte-family: Oswald, sans-serif;
    text-transform: uppercase;
}
```
**Editar tamanho da fonte**

- [x] `font-size: **px` incluir o tamanho da fonte em cada local que desejar

* Criar `header 1` e incluir o código abaixo:

```css
  header h1 {
    margin-bottom: 4px;
    font-size: 32px;
    line-height: 33px;
}
```
> lembrando que, a alteração do tamanho da fonte é apenas o `fonte-size: 00px`

* `section h2` incluir o tamanho da fonte

```css
section h2 {
    background-color: #FED7AA;
    padding: 8px 16px;
    text-align: center;

    margin-bottom: 24px;
    font-size: 18px;
}
```
* `.details h3` incluir o tamanho da fonte e altura da linha

```css
.details h3 {
    margin-bottom: 8px;
    font-size: 16px;
    line-height: 19px;
}
```
**Editar cor da fonte - Títulos, Subtítulos e Preço**

- [x] `color` Incluir no agrupamento das Fontes

```css
/*Global - Fonts*/
h1, h2, h3, .price {
    fonte-family: Oswald, sans-serif;
    text-transform: uppercase;
    color: #2d2c2a;
}
```

**Incluir e Editar o Parágrafo do header**

- [x] `header p` adicionar grupo
- [x] `color: rgba(0, 0, 0, 0.7);` cor 
- [x] `font-size: 14px;` tamanho fonte
- [x] `line-height: 21px;` altura da linha 

```css
header p {
    color: rgba(0, 0, 0, 0.7);
    font-size: 14px;
    line-height: 16px;
}
```

**Incluir e Editar o Parágrafo das listas**

- [x] `.details p` adicionar grupo
- [x] `color: rgba(0, 0, 0, 0.6);` cor 
- [x] `font-size: 14px;` tamanho fonte
- [x] `line-height: 21px;` altura da linha  

```css
.details p {
    color: rgba(0, 0, 0, 0.6);
    font-size: 14px;
    line-height: 21px;
}
```

### Utilizando o VSCode

> Esta etapa é para quem executou o código em um editor online. Se você realizou as tarefas em um editor em sua máquina local, desconsidere esta etapa.

No VSCode da máquina ou [VSCode online](https://vscode.dev/)

- [x] Clicar em **Open Folder**  
- [x] Criar uma nova pasta **New Folder** 
- [x] Clicar em Select
- [x] Liberar acesso a pasta 
- [x] Criar arquivo `index.html` 
- [x] Criar arquivo `style.css` 

![image](https://user-images.githubusercontent.com/108991648/183781306-e636655a-fb81-4958-ab09-d60fc2c59c02.png)

### Salvando o site no computador

> Esta etapa é para quem executou o código em um editor online. Se você realizou as tarefas em um editor em sua máquina local, desconsidere esta etapa.

* No arquivo html com o código já editado

- [x] **Ctrl+A** selecionar o código
- [x] **Ctrl+C** copiar o código 
- [x] **Ctrl+V** colar o código no arquivo `index.html`
- [x] Alterar o link dentro de head, para o nome do arquivo css que temos na pasta nova

> ./ == está no mesmo diretório

- [x] **Ctrl+S** salvar o arquivo

* No arquivo CSS com o código já editado

- [x] **Ctrl+A** selecionar o código
- [x] **Ctrl+C** copiar o código 
- [x] **Ctrl+V** colar o código no arquivo `style.css`
- [x] **Ctrl+S** salvar o arquivo

Pronto, agora seus arquivos estão no seu computador

### Criando link de acesso ao site

Acessar [Netlify](https://www.netlify.com/)
- [x] Realizar cadastro,  pode ser utilizado o GitHub
- [x] Responder o questionário do próprio site.
- [x] Import from Git e autorizar (importar o projeto do GitHub)
- [x] Autorizar acesso ao repositório

* O site vai gerar um link para o projeto.

### Gerar QRCode

Acessar [QRCode Generator](https://br.qr-code-generator.com/)

- [x] Realizar cadastro
- [x] Copiar o link criado no site do Netlify
- [x] Solicitará o tipo de uso: "uso pessoal"
- [x] Solicitará o tipo de QR Code: "Website"
- [x] Cole o link criado no Netlify
- [x] Faça o dowload 

Prontinho, etapa finalizada!

### Alterções no site

Pelo GitHub, dentro do repositório aperte o . (ponto), abrirá um editor. Aqui você pode editar o seu código.

- [x] Inclua ou exclua informações
- [x] Clieque onde aparece uma bolinha azul
- [x] Inclua uma mensagem informando qual o tipo de alteração
- [x] Clique na setinha para ajustar o seu código

![image](https://user-images.githubusercontent.com/108991648/183787004-cf4ac5fb-326e-4309-841b-00915e5c0873.png)

No Netlify será atualizado automaticamente!  


Prontinho, projeto finalizado com sucesso! 😁

______________

## Novas metas

Nesta etapa, vou incluir os próximos passos deste projeto.

**Adicionando imagem** 

Para este item, segui as dicas do [Prof: Guanabara](https://www.youtube.com/watch?v=1ZeettFfxys)

> Lembre-se dos direitos autorais de imagem, busque por imagens liberadas!

Recomendação|Sites
:-|:-
Pixabay | https://pixabay.com/pt/
Emojipedia|https://www.emojipedia.org/

Após analisar o seu projeto e identificar o local, tenha uma imagem salva em seu repositório do projeto, e vamos adicioná-la.

Optei por incluir uma imagem entre o nome e horário de funcionamento, localizado no `header`

- [x] `<span>` abrir tag genérica
- [x] `img` adicinar e apertar enter
- [x] `<img src="" alt="">` aparecerá automaticamente
- [x] Dentro das aspas do `src` aperte Ctrl+Espaço e procure pelo nome do arquivo
- [x] Dentro das aspas do `alt` inclua o nome do que se parece sua imagem
- [x] `</span>` fechar tag genérica


```html
  <header>
        <h1>Pizzaria <span>Sensações</span><span><img src="pizza_2.png" alt="imagem pizza"></span></h1>
        <p>Aberto de terça-feira a domingo. 18h-23h</p>
    </header>
```

![image](https://user-images.githubusercontent.com/108991648/183930061-f9b77339-85e4-4b29-8905-3e04e53d167b.png)

**Adicionar favicon**

Favicon é o ícone que aparece na guia do navegador

![image](https://user-images.githubusercontent.com/108991648/183938708-be7b8236-d0c0-40cb-aff5-97d1516bc356.png)

Podemos criar ícones nos sites abaixo:

Recomendação|Sites
:-|:-
Favicon|https://www.favicon.cc/
Favicon .io | https://favicon.io/

Após escolher o ícone, salve o arquivo em seu repositório.

Em `head`, acima de `title`, vamos incluir:

- [x] `link favicon` e apertar enter
- [x] Em `href=` deletar `favicon.ico` 
- [x] Nas aspas de `href=` clique Ctrl+espaço e selecione o arquivo

Prontinho!

![image](https://user-images.githubusercontent.com/108991648/183939648-1cab4002-0f7a-4caf-a523-39e6d008a407.png)








____________________





