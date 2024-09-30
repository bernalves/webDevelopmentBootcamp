# O Básico Sobre CSS

![pt-BR](https://img.shields.io/badge/lang-pt--BR-green)

## Relevância dos Tópicos

1. Cruciais
    - Conceptual Overview of CSS
    - Basic CSS Syntax
    - Including Styles Correctly
    - Color Systems: RGB, Hex, etc.
    - font-family properties

2. Importantes
    - Common Text Properties

## Notas

### Objetivos dessa seção

1. Introduzir os conceitos básicos sobre CSS (Cascading Style Sheets)

### O que é CSS

> É uma linguagem pra descever como os elementos são apresentados visualmente e estilizados. Segue um padrão simples de objetos: `{ property: value }`.

> Nem todas as propriedades tem de ser memorizadas (acredite, são muitas!), por isso pode sempre consultá-las online: [Referências CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Reference).

2. Includind Styles (Estilizando os elementos)

> **Boas práticas:** a melhor prática é estilizar seus elementos em um arquivo .css e incluir um `<link>` no cabeçalho de seu arquivo HTML. Não é recomendável estilizar os elementos diretamente após declará-los ou incluí-los em um elemento `<style>` em seu documento HTML, pois não serão reutilizáveis. Mesmo que pretenda usar a estilização apenas uma vez, mantenha-se no caminho das boas práticas que foram pensadas por outros antes de você.

Para estilizar os elementos utilizando um arquivo .css adicional, iremos utilizar o elemento `<link>` em nosso cabeçalho (elemento `<head>`), da seguinte forma:

``` html
<head>
    <title> Meu arquivo HTML</title>
    <link rel="stylesheet" href="{caminho/arquivo}.css">
</head>
```
