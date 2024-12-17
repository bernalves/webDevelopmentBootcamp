# CSS Box Model

![pt-BR](https://img.shields.io/badge/lang-pt--BR-green)

## Relevância dos Tópicos

1. Cruciais
    - Width & Height
    - Border
    - Padding
    - Margin
    - Display Property
    - Unidades: percentage, EMS & REMS

2. Nice to Have
    - Border Radius

## Notas

### The Box Model

> Traduz a ideia de que tudo em CSS faz parte de uma "caixa" (um container).
> Cada uma destas partes representa diferentes partes de uma página e contém diferentes propriedades.

**Width**: define a largura, **Heigth** define a altura. Estas propriedades dizem respeito ao **conteúdo interno** e estão condicionadas à estilização em CSS, e caso mais propriedades sejam adicionadas, serão limitadas ao valores definidos. Por exemplo, a propriedade *background-color* se extenderá até o limite definido, ao invés de preencher todo o espaço da *div*.

**Border** diz respeito ao contorno dos elementos da página, simples assim. As propriedades básicas da borda são *border-width*, *border-color* e *border-style*, para estilizarmos a espessura, cores e aparência, respectivamente. Vale lembrar que a propriedade ***border-sizing*** muda a abordagem utilizada, o que faz com que os valores se limitem à *largura* e *altura* definidas previamente nas *divs*.

**Padding** representa o espaço interno entre o elemento e a borda, enquanto **Margin** representa o espaço externo à borda, entre um elemento e outro. No entanto, a propriedade **Display** consegue que as propriedades *margin* e *padding* sejam respeitadas por elemntos *block* ou *inline*, com novas possbilidades de exibição nas páginas.
