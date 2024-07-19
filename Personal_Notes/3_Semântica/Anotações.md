# Semântica

![pt-BR](https://img.shields.io/badge/lang-pt--BR-green)

## Relevância dos Tópicos

![Relevância](/Personal_Notes/3_Semântica/Relevância_dos_Tópicos.png)

## Notas

### Elementos

#### Blocos

> Elementos _Inline_ (em linha, em tradução literal) dividem o mesmo espaço na página (a mesma linha).

#### Inline

> Blocos, ao contrário, preenchem todo o espaço disponível.

#### Divs

> [_Divs_](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/div) (divisões) são elementos de bloco que tem como finalidade agrupar outros elementos da página.

_Divs_ forçam uma divisão de conteúdo antes e depois do agrupamento. Simples assim. Também permitem, por CSS, a estilização do bloco inteiro.

#### Spans

> [_Spans_](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/span) também tem a finalidade de agrupar elementos, porém em linha (_Inline_).

_Spans_ também são elementos genéricos, assim como as _Divs_, que possibilitam a alteração de vários elementos _Inline_ de uma só. Com CSS é possível estilizar todos os elementos _Span_ ao mesmo tempo.

#### Outros elementos

> `<hr>`: Linhas horizontais abaixo de um texto ou elemento.
> `<br>`: Adiciona uma quebra de linha ao seu texto.
> `<sup>`: Para textos acima do texto, como potências. 10 <sup>2</sup>.
> `<sub>`: Para textos abaixo do texto, como fórmulas quiímicas e frações. H<sub>2</sub>O.

### Entidades

> Sequências ou códigos HTML que se transformam em caracteres. Sempre começam com "&" e terminam com ";".
>> Exemplos: símbolos para copyright (&copy;), símbolos (&gt;, &lt; &micro;), objetos (&hearts;) e até algumas frações (&frac12;, &frac14;) e potências básicas (7&sup2;).

### O sentido da semântica nos elementos HTML

Usar os elementos corretos nos lugares apropriados se faz relevante não só para tornar o código mais "limpo" (como utilizar os princípios de [_Clean Architecture_](https://medium.com/luizalabs/descomplicando-a-clean-architecture-cf4dfc4a1ac6), por exemplo), mas também para facilitar a busca de mecanismos de pesquisa e a acessibilidade das aplicações, sites ou qualquer seja o projeto que esteja construindo. Por que não tornar a vida mais fácil de quem irá aproveitar o que você está construindo, ou de tornar mais acessível para outras pessoas que necessitam desses elementos para terem sua acessibilidade garantida durante sua navegação?

Não é difícil fazer o simples, basta ter vontade.

#### Elementos semânticos

Ao invés de "uma _div_ para governar a todos", use elementos mais apropriados e que dão mais sentido ao conteúdo que estão agrupando, como:

- `<article>`

- `<aside>`

- `<details>`

- `<footer>`

- `<header>`

- [`<main>`](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/main)

  - Representa o conteúdo principal da página que está contido no `<body>` e deve excluir qualquer conteúdo que seja repetitivo na página (exemplos: barras laterais (_sidebars_), menus (_nav links_), informações de copyright, logo, formulários, etc.)

- [`<nav>`](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/nav)

  - Representa todas referências de navegação dentro ou fora da página

- `<section>`

- `<summary>`
