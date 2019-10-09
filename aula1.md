# Front-End I - Fundamentos de HTML, CSS e Js - Aula 1

> Editor de código (VS Code)

<img src="https://content-static.upwork.com/blog/uploads/sites/3/2015/05/05110037/Front-end-dev1.png" alt="Front-End Checklist" width="100%">

## Sumário

1. **[Noções básicas de desenvolvimento Web](#Noções-básicas-de-desenvolvimento-Web)**
1. **[Marcação x Programação](#Fornecendo-informações-x-fornecendo-instruções:)**
1. **[HTML](#HTML)**
2. **[Títulos](#Títulos)**
3. **[Parágrafos](#Parágrafos)**
4. **[Comentários](#Comentários)**
5. **[Atributos](#Atributos)**
6. **[Links](#Links)**
7. **[Links para elementos internos](#Links-para-elementos-internos)**
8. **[ID e classes](#ID-e-classes)**
9. **[Listas](#Listas)**
10. **[Aninhanhando muitos elementos](#Aninhanhando-muitos-elementos)**
11. **[HTML 5](#HTML-5)**
12. **[Declarando um documento HTML](#Declarando-um-documento-HTML)**
13. **[Mais Tags](#Mais-Tags)**
14. **[Exercícios](#Exercícios)**
-----

## Definição 

### Noções básicas de desenvolvimento Web
As linguagens de marcação são a base da Web - onde tudo começou, quando sites eram apenas páginas estáticas com texto e alguma formatação. Originários dos processos de composição usados ​​nas primeiras impressoras, esses idiomas há muito tempo são usados ​​para anotar o texto de um site, determinando a arquitetura de um site e a exibição do texto. Embora as linguagens de marcação façam parte do passado, isso não as tornou obsoletas. Na verdade, eles continuaram sendo um núcleo de desenvolvimento e seu futuro.

Tudo o que você vê na Web é uma combinação de marcação (texto), CSS (design) e scripts de front-end (interatividade), e essa marcação é o que cria a base de um site. HTML é a marcação principal para páginas da Web, ou praticamente qualquer coisa exibida em um navegador, o que explica por que ainda é incrivelmente relevante e por que muitos desenvolvedores o conhecem.

### Fornecendo informações x fornecendo instruções: 
#### Como as linguagens de marcação diferem das linguagens de programação
A moeda das linguagens de marcação é texto, ela controla como o texto é exibido, estruturado e organizado. Enquanto as linguagens de programação informam aos dados e aos bancos de dados como se comportar, o HTML estrutura esses dados.

Funciona através de anotações.

Na sua forma mais básica, a marcação é salpicada em todo o texto na forma de anotações, que informam ao software ou a um navegador como exibir esse texto. Se você já viu HTML no formato bruto, provavelmente já viu "tags" - comandos descritivos incorporados no texto, definidos entre colchetes de abertura e fechamento. Essas tags indicam que o que estiver dentro desses colchetes não é texto, mas algo para o navegador processar - deixando o texto em negrito ou com hiperlink ou quebrando um parágrafo.

### HTML 
HTML, linguagem de marcação de hipertexto, foi a primeira linguagem baseada na Internet. Essa linguagem de marcação descritiva é a marcação principal para todas as páginas da Web ou quase tudo exibido em um navegador, e é por isso que continua sendo uma habilidade essencial para todos os desenvolvedores. O HTML evoluiu para a versão mais recente, o HTML5, que adiciona mais recursos do que as versões anteriores e agora pode definir a aparência dos vídeos, imagens e texto.
Depois que o documento HTML de um site é criado, outros aspectos podem ser incorporados a essa marcação - por exemplo, um programa JavaScript pode ser incorporado ao HTML para adicionar interatividade ao site, e as folhas de estilo em cascata (CSS) podem ser vinculadas ao arquivo HTML para controlar todos os aspectos do design. Dessa forma, é a espinha dorsal do site.

## Semântica - Introdução ao HTML básico

### Títulos

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

### Parágrafos

```html
<p>O desenvolvimento da web de front-end é a prática de converter dados em uma interface gráfica</p>
```

### Comentários

É uma maneira de deixar comentários para outros desenvolvedores no seu código sem afetar a saída resultante exibida ao usuário final.

Comentar também é uma maneira conveniente de tornar o código inativo sem precisar excluí-lo completamente.

Os comentários em HTML começam com <! - e terminam com um ->

```html
<!-- <p>O desenvolvimento da web de front-end é a prática de converter dados em uma interface gráfica</p> -->
```

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

### Atributos

Todos os elementos HTML podem ter atributos, eles fornecem informações adicionais sobre um elemento.

Geralmente vêm em pares `name="value"`.Os valores dos atributos devem sempre estar entre aspas.

Além disso, alguns atributos são necessários para certos elementos. Por exemplo, uma tag `<img>` deve conter os atributos `src` e `alt`.

> Mais informações em: [HTML Attributes](https://www.w3schools.com/html/html_attributes.asp)

### Links

Você pode usar elementos âncora para vincular ao conteúdo fora da sua página da web.

elementos âncora precisam de um endereço da web de destino chamado atributo href. Eles também precisam de texto âncora. Aqui está um exemplo:

```html
<a href="https://freecodecamp.org">this links to freecodecamp.org</a>
```

Você pode transformar elementos em links aninhando-os em um elemento.

```html
<a href="#"><img src="https://bit.ly/fcc-running-cats" alt="Three kittens running towards the camera."></a>
```

### Links para elementos internos

Os elementos âncora também podem ser usados para criar links internos para ir para diferentes seções em uma página da web.

Para criar um link interno, atribua o atributo hrefattribute a um símbolo de hash #plus o valor do atributo id para o elemento ao qual você deseja vincular internamente, geralmente mais abaixo na página. Você precisará adicionar o mesmo atributo de atributo ao elemento ao qual está vinculando. Um id é um atributo que descreve exclusivamente um elemento.

Abaixo está um exemplo de um link de âncora interno e seu elemento de destino:

```html
<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>
```

### ID e classes
O atributo id especifica um ID exclusivo para um elemento HTML (o valor deve ser exclusivo no documento HTML).

O atributo id é mais usado para apontar para um estilo em uma folha de estilos e por JavaScript (via HTML DOM) para manipular o elemento com o ID específico.

```html
<h1 id="myHeader">Hello World!</h1>
```

O atributo class especifica um ou mais nomes de classe para um elemento.

O atributo de classe é usado principalmente para apontar para uma classe em uma folha de estilos. No entanto, também pode ser usado por um JavaScript (via HTML DOM) para fazer alterações nos elementos HTML com uma classe especificada.

```html
<h1 class="intro">Header 1</h1>
<p>A paragraph.</p>
<p class="important">Note that this is an important paragraph. :)</p>
```

### Listas
#### Lista não ordenada
O HTML possui um elemento especial para criar listas não ordenadas ou listas de estilos de marcadores.

As listas não ordenadas começam com um elemento `<ul>` de abertura, seguido por qualquer número de elementos `<li>`. Por fim, listas não ordenadas fecham com um `</ul>`

```html
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```

#### Lista ordenada
O HTML possui outro elemento especial para criar listas ordenadas ou listas numeradas.

As listas ordenadas começam com um elemento <ol> de abertura, seguido por qualquer número de elementos <li>. Por fim, as listas ordenadas fecham com um </ol>

```html
<ol>
  <li>Garfield</li>
  <li>Sylvester</li>
</ol>
```

### Aninhanhando muitos elementos
O elemento div, também conhecido como elemento de divisão, é um contêiner de uso geral para outros elementos.

O elemento div é provavelmente o elemento HTML mais usado de todos.

Assim como qualquer outro elemento que não se fecha automaticamente, você pode abrir um elemento div com `<div>` e fechá-lo em outra linha com `</div>`.
```html
<div>
 <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
</div>
```

### HTML 5

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



### Declarando um documento HTML
Os desafios até agora cobriram elementos HTML específicos e seus usos. No entanto, existem alguns elementos que dão estrutura geral à sua página e devem ser incluídos em todos os documentos HTML.

Na parte superior do documento, você precisa informar ao navegador qual versão do HTML sua página está usando. HTML é uma linguagem em evolução e é atualizado regularmente. A maioria dos principais navegadores suporta a especificação mais recente, que é HTML5. No entanto, páginas da Web mais antigas podem usar versões anteriores do idioma.

Você informa essas informações ao navegador adicionando a tag <! DOCTYPE ...> na primeira linha, onde a parte "..." é a versão do HTML. Para HTML5, você usa <! DOCTYPE html>.

O DOCTYPE! E maiúsculo é importante, especialmente para navegadores mais antigos. O html não diferencia maiúsculas de minúsculas.

Em seguida, o restante do seu código HTML precisa ser envolvido em htmltags. A abertura `<html>` fica diretamente abaixo da linha <! DOCTYPE html>, e o fechamento `</html>`fica no final da página.

```html
<!DOCTYPE html>
<html>
  <!-- Your HTML code goes here -->
</html>
```

Você pode adicionar outro nível de organização em seu documento HTML nas tags htm com os elementos de cabeçalho e corpo. Qualquer marcação com informações sobre sua página entraria no cabeçalho. Em seguida, qualquer marcação com o conteúdo da página (o que é exibido para um usuário) será inserida na etiqueta do corpo.

Os elementos de metadados, como link, meta, título e estilo, geralmente ficam dentro do headelement.

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- metadata elements -->
  </head>
  <body>
    <!-- page contents -->
  </body>
</html>
```

### Mais Tags
> https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element

## Exercícios

* Crie uma página da Web na qual esteja seu nome na tela.
* Crie uma página da web e defina seu título como "Esta é uma página da web".
* Crie uma página da Web na qual esteja qualquer texto de sua escolha na tela.
* Crie alguns links para vários mecanismos de pesquisa (google, yahoo, duckduckgo, bing, etc).
* Crie links para cinco páginas diferentes em cinco sites diferentes, que deverão abrir em uma nova janela.
* Crie uma página com um link na parte superior que, quando clicado, saltará até o final da página.
* Crie uma página com um link na parte inferior que, quando clicada, saltará até o topo da página.
* Crie uma página com um link na parte superior que, quando clicado, saltará até o final da página. Na parte inferior da página, deve haver um link para voltar ao topo da página.
* Exiba cinco imagens diferentes. Pule duas linhas entre cada imagem. Cada imagem deve ter um título.
* Exiba uma imagem que, quando clicada, vinculará a um mecanismo de pesquisa de sua escolha (deve ser aberto em uma nova janela).
* Exiba uma imagem que, quando clicada, vinculará a si mesma e exibirá a imagem no navegador por si só.

* **Reproduzir essa pagina com html**