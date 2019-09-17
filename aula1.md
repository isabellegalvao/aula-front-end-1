# Front-End I - Fundamentos de HTML, CSS e Js - Aula 1

* Editor de código (VS Code)

## Sumário

1. **[HTML](#Introdução-ao-HTML-básico)**
2. **[Títulos](#Títulos)**
3. **[Parágrafos](#Parágrafos)**
4. **[Comentários](#Comentários)**
5. **[HTML 5](#HTML-5)**
6. **[Atributos](#Atributos)**
7. **[Links](#Links)**
8. **[Links para elementos internos](#Links-para-elementos-internos)**
9. **[ID e classes](#ID-e-classes)**
10. **[Listas](#Listas)**
-----

##  Introdução ao HTML básico

### Tags HTML

#### Títulos

```html
<h1>Olá</h1>
```
Esse é um elemento HTML.

A maioria dos elementos HTML possui uma tag de abertura e uma tag de fechamento.

A única diferença entre as tags de abertura e fechamento é a barra após o suporte de abertura de uma tag de fechamento.

Os elementos HTML `<h1>` - `<h6>` representam seis níveis de títulos de seção. `<h1>` é o nível mais alto da seção e `<h6>` é o mais baixo.

> Evite usar tags de cabeçalho para redimensionar o texto. Em vez disso, use a propriedade de tamanho da fonte CSS. Os títulos usam tamanho para indicar sua importância relativa, mas o CSS é preferido para o redimensionamento de uso geral.
Evite pular os níveis de título: sempre comece a partir de `<h1>,` use em seguida `<h2>` e assim por diante.
Você deve evitar o uso de `<h1>` mais de uma vez em uma página.

#### Parágrafos

```html
<p>O desenvolvimento da web de front-end é a prática de converter dados em uma interface gráfica</p>
```

#### Comentários

É uma maneira de deixar comentários para outros desenvolvedores no seu código sem afetar a saída resultante exibida ao usuário final.

Comentar também é uma maneira conveniente de tornar o código inativo sem precisar excluí-lo completamente.

Os comentários em HTML começam com <! - e terminam com um ->

```html
<!-- <p>O desenvolvimento da web de front-end é a prática de converter dados em uma interface gráfica</p> -->
```

#### HTML 5

O HTML5 apresenta tags HTML mais descritivas. Isso inclui cabeçalho, rodapé, navegação, vídeo, artigo, seção e outros.

Essas tags facilitam a leitura do HTML e também ajudam na otimização e otimização de mecanismos de busca (SEO).

A tag main HTML5 ajuda os mecanismos de pesquisa e outros desenvolvedores a encontrar o conteúdo principal da sua página.

```html
<nav>
  <ul>
    <li><a href="#">link</a></li>
    <li><a href="#">link</a></li>
  </ul>
</nav>
```

```html
<article>
  <h1>How to Become an MDN Contributor</h1>
  <p>
    Do you want to help protect the web?....
  </p>
</article>
```

```html
<section>
  <h1>Amazing MDN Contributors</h1>
    <ul>
      <li><img src="link" alt="descriptive text"></li>
      <li><img src="link" alt="descriptive text"></li>
      <li><img src="link" alt="descriptive text"></li>
    </ul>
    <aside>
     <p>To get involved contact</p>
    </aside>
</section>
```
> Mais informações em: [Using HTML sections and outlines
](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Using_HTML_sections_and_outlines#Defining_sections)

### Imagens

Você pode adicionar imagens ao seu site usando o elemento img e apontar para o URL de uma imagem específica usando o atributo src.

Um exemplo disso seria:

```html
<img src="https://www.your-image-source.com/your-image.jpg">
```

Observe que os elementos img são de fechamento automático.

Todos os elementos img devem ter um atributo alt. O texto dentro de um atributo alt é usado para os leitores de tela para melhorar a acessibilidade e é exibido se a imagem não carregar.

Nota: Se a imagem for puramente decorativa, usar um atributo de alta vazio vazio é uma prática recomendada.

Idealmente, o atributo alt não deve conter caracteres especiais, a menos que seja necessário.

Vamos adicionar um atributo alt ao nosso exemplo img acima:

```html
<img src="https://www.your-image-source.com/your-image.jpg" alt="Autor de pé em uma praia com dois polegares para cima.">
```

#### Atributos

Todos os elementos HTML podem ter atributos, eles fornecem informações adicionais sobre um elemento.

Geralmente vêm em pares `name="value"`

> Mais informações em: [HTML Attributes](https://www.w3schools.com/html/html_attributes.asp)

#### Links

Você pode usar elementos âncora para vincular ao conteúdo fora da sua página da web.

elementos âncora precisam de um endereço da web de destino chamado atributo href. Eles também precisam de texto âncora. Aqui está um exemplo:

```html
<a href="https://freecodecamp.org">this links to freecodecamp.org</a>
```

Você pode transformar elementos em links aninhando-os em um elemento.

```html
<a href="#"><img src="https://bit.ly/fcc-running-cats" alt="Three kittens running towards the camera."></a>
```


#### Links para elementos internos

Os elementos âncora também podem ser usados para criar links internos para ir para diferentes seções em uma página da web.

Para criar um link interno, atribua o atributo hrefattribute a um símbolo de hash #plus o valor do atributo id para o elemento ao qual você deseja vincular internamente, geralmente mais abaixo na página. Você precisará adicionar o mesmo atributo de atributo ao elemento ao qual está vinculando. Um id é um atributo que descreve exclusivamente um elemento.

Abaixo está um exemplo de um link de âncora interno e seu elemento de destino:

```html
<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>
```

#### ID e classes
texto

```html
<!--  -->
```

#### Listas
texto

```html
<!--  -->
```

#### Lista ordenada
texto

```html
<!--  -->
```

#### Criar um campo de texto
texto

```html
<!--  -->
```

#### Adicionar texto de espaço reservado a um campo de texto
texto

```html
<!--  -->
```

#### Criar um elemento de formulário
texto

```html
<!--  -->
```

#### Adicionar um botão Enviar a um formulário
texto

```html
<!--  -->
```

#### Use HTML5 para exigir um campo
texto

```html
<!--  -->
```

#### Criar um conjunto de botões de opção
texto

```html
<!--  -->
```

#### Criar um conjunto de caixas de seleção
texto

```html
<!--  -->
```

#### Verificar botões de opção e caixas de seleção por padrão
texto

```html
<!--  -->
```

#### Aninhar muitos elementos em um único elemento div
texto

```html
<!--  -->
```

#### Declare o Doctype de um documento HTML
texto

```html
<!--  -->
```

#### Definir a cabeça e o corpo de um documento HTML
texto

```html
<!--  -->
```
