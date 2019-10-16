# Front-End I - Fundamentos de HTML, CSS e Js - Aula 2

> Editor de código (VS Code)

## Sumário

##  Metatags

https://htmlhead.dev/

## Definição 

### CSS
CSS é a sigla para o termo em inglês Cascading Style Sheets que, traduzido para o português, significa Folha de Estilo em Cascatas. É uma linguagem que trabalha com documentos HTML para definir a maneira como os documentos da Web são apresentados. Ele é usado para controlar a aparência e a posição dos elementos HTML.

## Anatomia

```css
seletor{
  propriedade: valor;
}
```

## Propridades

### Fundo
| Propridades | Definição|
|----------|:-------------:|
| background | Define uma variedade de propriedades de segundo plano em uma declaração. |
| background-attachment | Especifique se a imagem de plano de fundo é fixa na janela de exibição ou se rola. |
| background-color | Define a cor de fundo de um elemento. |
| background-image | Define a imagem de plano de fundo de um elemento. |
| background-position | Define a origem de uma imagem de plano de fundo. |
| background-repeat | Especifique se / como a imagem de fundo é lado a lado. |
| background-size  | Especifica o tamanho das imagens de fundo. |

### Borda
| Propridades | Definição|
|----------|:-------------:|
| border | Define a largura, estilo e cor dos quatro lados da borda de um elemento. |
| border-radius | Define a forma dos cantos da borda de um elemento. |

### Cor
| Propridades | Definição|
|----------|:-------------:|
| color | Especifique a cor do texto de um elemento. |
| opacity  | Especifica a transparência de um elemento. |

### Dimensão
| Propridades | Definição|
|----------|:-------------:|
| height | Especifique a altura de um elemento. |
| max-height | Especifique a altura máxima de um elemento. |
| max-width | Especifique a largura máxima de um elemento. |
| min-height | Especifique a altura mínima de um elemento. |
| min-width | Especifique a largura mínima de um elemento. |
| width | Especifique a largura de um elemento. |

### Font
| Propridades | Definição|
|----------|:-------------:|
| font | Define uma variedade de propriedades de fonte em uma declaração. |
| font-family | Define uma lista de fontes para o elemento. |
| font-size | Define o tamanho da fonte do texto. |
| font-style | Define o estilo da fonte para o texto. |
| font-weight | Especifique o peso da fonte do texto. |

### Lista
| Propridades | Definição|
|----------|:-------------:|
| list-style | Define o estilo de exibição para uma lista e elementos da lista. |

### Espaçamento
| Propridades | Definição|
|----------|:-------------:|
| margin | Define a margem nos quatro lados do elemento. |
| margin-bottom | Define a margem inferior do elemento. |
| margin-left | Define a margem esquerda do elemento. |
| margin-right | Define a margem direita do elemento. |
| margin-top | Define a margem superior do elemento. |

| Propridades | Definição|
|----------|:-------------:|
| padding | Define o preenchimento nos quatro lados do elemento. |
| padding-bottom | Define o preenchimento inferior do elemento. |
| padding-left | Define o preenchimento esquerda do elemento. |
| padding-right | Define o preenchimento direita do elemento. |
| padding-top | Define o preenchimento superior do elemento. |

### Texto
| Propridades | Definição|
|----------|:-------------:|
| direction| Defina a direção do texto / direção da escrita. |
| text-align| Define o alinhamento horizontal do conteúdo embutido. |
| text-align-last | Especifica como a última linha de um bloco ou uma linha logo antes de uma quebra de linha forçada é alinhada quando o alinhamento de texto é justificado. |
| text-decoration| Especifica a decoração adicionada ao texto. |
| text-indent| Recue a primeira linha do texto. |
| text-justify | Especifica o método de justificação a ser usado quando a propriedade de alinhamento de texto estiver configurada para justificar. |
| text-shadow | Aplica uma ou mais sombras ao conteúdo do texto de um elemento. |
| text-transform| Transforma o caso do texto. |
| line-height| Define a altura entre as linhas do texto. |
| letter-spacing| Define o espaçamento extra entre as letras. |
| word-spacing| Define o espaçamento entre as palavras. |

### Posicionamento
| Propridades | Definição|
|----------|:-------------:|
| display | Especifica como um elemento é exibido na tela. |
| position | Especifica como um elemento é posicionado. |
| top | Especifique a localização da aresta superior do elemento posicionado. |
| right | Especifique a localização da borda direita do elemento posicionado. |
| bottom | Especifique a localização da aresta inferior do elemento posicionado. |
| left | Especifique a localização da borda esquerda do elemento posicionado. |
| z-index | Especifica uma ordem de camadas ou empilhamento para elementos posicionados. |
| overflow | Especifica o tratamento do conteúdo que excede a caixa do elemento. |
overflow-x  | Especifica como gerenciar o conteúdo quando ele exceder a largura da largura do | elemento. |content area.
| overflow-y  | Especifica como gerenciar o conteúdo quando ele ultrapassa a altura do elemento |content area.
| box-shadow  | Aplica uma ou mais sombras à caixa do elemento. |
| box-sizing  | Altere o modelo de caixa CSS padrão. |

## Pseudo-classes

Uma pseudo-classe CSS é uma palavra-chave adicionada a seletores que especifica um estado especial do elemento selecionado. Por exemplo, `:hover` pode ser usado para alterar a cor de um botão quando o usuário passar o cursor sobre ele.

```css

div:hover {
  background-color: #F89B4D;
}

```

Pseudo-classes permitem que você aplique um estilo a um elemento não apenas em relação ao conteúdo da árvore do documento, mas também em relação a fatores externos como o histórico de navegação (:visited, por exemplo), o estado do seu conteúdo (como :checked em certos elementos de um formulário), ou a posição do mouse (como :hover, que permite saber se o mouse está sobre um elemento ou não).

Observação: Diferentemente das pseudo-classes, pseudo-elementos podem ser usados para estilizar uma parte específica de um elemento.


```css

seletor:pseudo-classe {
  propriedade: valor;
} 

```

Pseudo-classes padrão
* :active
* :checked
* :disabled
* :first
* :first-child
* :first-of-type
* :focus
* :hover
* :last-child
* :last-of-type
* :link
* :not()
* :nth-child()
* :nth-last-child()
* :nth-last-of-type()
* :nth-of-type()
* :only-child
* :only-of-type
* :read-only
* :read-write
* :required
* :root
* :visited

## Pseudo-elementos 

Diferentemente das pseudo-classes, pseudo-elementos podem ser usados para estilizar uma parte específica de um elemento.

```css

seletor::pseudo-elemento {
  propriedade: valor;
} 

```
> Como regra, os dois pontos devem ser usados duas vezes  ( :: )  ao invés de uma única vez  ( : ). Isso distingue pseudo-classes de pseudo-elementos. Apesar disso, devido a essa distinção não estar presente em versões mais antigas da especificação da W3C, a maioria dos navegadores suportam ambas as sintaxes para os pseudo-elementos originais.

Pseudo-elementos padrão
* ::after
* ::before
* ::first-letter
* ::first-line
* ::selection
* ::placeholder 


### Posicionamento

https://www.origamid.com/projetos/css-grid-layout-guia-completo/

https://origamid.com/projetos/flexbox-guia-completo/


## Recursos

> [HTML e CSS - Common terms](https://russmaxdesign.github.io/maxdesign-slides/02-css/202-common-terms.html#/) Revisão

> [CSS Templates](https://www.w3schools.com/css/css_templates.asp)

> [CSS3 Properties](https://www.tutorialrepublic.com/css-reference/css3-properties.php)

> [BEM em 5 min](https://medium.com/trainingcenter/bem-em-5min-f5c80fd23439)

> [Layout](https://calltoidea.com/application/images/call/Pages/layouts/n0cl1qtyaN-layout-cti.jpg)

> [Layout](https://calltoidea.com/layouts/)

## Coisas maneiras com CSS

[Jogo da velha](https://codepen.io/kalabasa/pen/oVMOZK)
[Totoro](https://codepen.io/jsmit-s/pen/yrBKEe)
[Imagem de caixa de leite](https://codepen.io/twelve13/pen/ewKEXp)
[Lava Lamp](https://codepen.io/jsmit-s/pen/mgbxXz)
[Botões](https://codepen.io/chengarda/pen/KbRaEL)