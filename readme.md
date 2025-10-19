# Materiais de Apoio 

Nossos materiais complementares têm como objetivo apresentar informações para facilitar e enriquecer a sua jornada de aprendizado. Para isso, links úteis (como slides, repositórios e páginas oficiais) serão disponibilizados, além de dicas sobre como se destacar na DIO e no mercado de trabalho. 


# Linguagem HTML
#### Autor: Fabio Toledo Bonemer De Salvi
A linguagem HTML é uma linguagem de marcação de texto, sendo formada por tags e seus atributos.\
Abaixo estão listadas a maioria das tags e atributos utilizados em progetos web.

## Tags básicas

A estrutura básica de um documento escrito em **HTML** contém as **tags** delimitadoras do conteúdo que será tratado pela linguagem **HTML**, uma seção de cabeçalho (**head**) e uma seção de corpo (**body**):

- **\<html\> e \</html\>:** Delimita o conteúdo do documento que será tratado como HTML.

- **\<head\> e \</head\>:** Seção de cabeçalho do documento responsável pelas informações de configuração do documento.

- **\<body\> e \</body>:** Seção do documento responsável pela parte visual do documento.

- **Exemplo:** Estrutura básica de um documento escrito em HTML.

    ```html
    <html>
        <head>
        </head>
        <body>
        </body>
    </html>
    ```

## Tags e atributos para adição e formatação de textos

- **Tags para separação e estilos**
    - **\<hr\>:** Inclui uma linha horizontal que separa tematicamente o conteúdo. É uma tag vazia (autcontida).
    - **\<br/\>:** Inclui uma quebra linha, forçando o texto seguinte a aparecer na linha de baixo.
    - **CSS (Cascading Style Sheets):** A forma mais flexível e recomendada para estilizar. Você pode aplicar estilos aos elementos `<div>`, `<span>` e outros, e definir o visual sem alterar a estrutura do HTML.

- **Tags de estrutura e organização**
    - **\<h1\> a \<h6\>:** Definem títulos, do mais importante (`\<h1\>`) ao menos importante (`\<h6\>`).
        - **\<h1\> \</h1\>:** Deve ser utilizado apenas uma vez por página. Identifica o assunto principal do conteúdo.
        - **\<h2\> \</h2\>:** Usado para subtítulos que dividem o conteúdo em secções principais. Pode haver múltiplos **\<h2\>** em uma página.
        - **\<h3\> \</h3\>:** Usado para subseções dentro de uma seção **\<h2\>**.
        - **\<h4\> \</h4\>:** Usado para subdivisões ainda menores dentro de uma seção **\<h3\>**.
        - **\<h5\> \</h5\>:** Usado para subdivisões dentro de uma seção **\<h4\>**.
        - **\<h6\> \</h6\>:** Usado para o nivel mais baixo de cabeçalho, subdividindo secções **\<h5\>**.
    - **\<p\> \</p\>:** Inclui um parágrafo de texto.    
    - **\<ul\> \</ul\>:** Usada para criar listas não ordenadas.
    - **\<ol\> \</ol\>:** Usada para criar listas ordenadas.
    - **\<li\> \</li\>:**  Usada para criar itens nas listas ordenadas e não ordenadas.
    - **\<div\> \</div\> :** Cria uma seção de nível de bloco para agrupar utros elementos. É útil para aplicar estilos em um grupo de conteúdo.
    - **\<span\>:** Usada para agrupar elementos inline, como palavras ou frases específicas dentro de um parágrafo, para aplicar estilos pontuais.   

- **Tags de formatação de texto**
    - **\<b\> \</b\>:** Torna o texto em **negrito** sem dar significado semântico adicional (estílo físico).
    - **\<strong\> \</strong\>:** Indica que  texto tem forte importância ou ênfase, e é exibido em **negrito** por padrão (estilo semântico).
    - **\<i\> \</i\>:** Torna o texto em *itálico* (estilo físico).
    - **\<em\> \</em\>:** Enfatiza o texto, que geralemente é exibido em itálico (estilo semãntico).
    - **\<u\> \</u\>:** Torna o texto **sublinhado** ou **underline**.
    - **\<sup\> \</sup\>:** Torna o texto **sobreescrito** ou **superscript**.
    - **\<sub\> \</sup\>:** Torna o texto **subscrito** ou **subscript**.
    - **\<small\> \</small\>:** Apresenta o texto em uma fonte menor que o padrão, usado para coisas como direitos autorais.
    - **\<mark\> \</mark\>:** Destaca o texto, com se ele estivesse marcado com um marca-texto.

- **Atributos para serem utilizados com as tags:** Os atributos são palavras especiais dentro das tags de abertura que fornecem informação a um elemento e modificam o seu comportamento. Alguns atributos aplicáveis às tags de formatação de texto.
    - **id:** Define um identificador único para um elemento específico. Auxilia na identificação de um elemento quando se utiliza Javascript.
    - **style:** Define um estilo ão texto, podendo ser uma cor, uma determinada fonte, um determinada tamanho, entre outros, aplicado diretemente a um elemento.
    - **class:** Define a classe a que esta tag pertence. A classe representa um conjunto de estilos pré-determinado que pode ser aplicado a mais de um elemento.


- **Exemplo:** Texto dentro da seção **\<body\>** com as formatações acima.

    ```html
    <body>
        <h1><strong id="titulo" style="color:blue;" class="titulo-principal">Meu primeiro <i>HTML!</i></strong></body></h1>

        <h2><strong><u>tecnologia<sup>*</sup></h2>

        <blockquote>
            <i>O jeito DIO._ para você ganhar destaque mais rápido no mercado.</i>
        </blockquote>  

        <p>Os nossos cursos e programas de formação são criados em conjunto come specialistas das empresas <mark>inovadoras do mundo</mark>.</p>

    </body>
    ```

## Tag para incluir figuras
    
- **\<img /\>:** Usada para incorporar uma imagem em uma página wen. Utilize os atributos de **img** para definir o diretório da imagem. sua largura, entre outros.
    - **src:** Este é um atributo obrigatório que especifica a URL (Uniform Resource Locator) ou caminho para o arquivo de imagem.
    - **width:** Define a largura da imagem. Poder ser um valor fixo em pixels (**px**) ou um valor percentual referente à largura do conteiner pai desta imagem.    

- **Exemplo:** Incuindo uma imagem dendo da seção **\<body\>**.

```html
<body>
    <img width="250px" src="./images/image1.png"/>

    <img width="50%" src="./images/image1.png"/>    
</body>
```

## Tags para incluir dados 

- **\<input /\>:** Define um campo de formulário interativo que permite ao usuário inserir dados.\
Os atributos mais importantes são:

    - **type:** Específica o tipo de controle.\
    Podendo ser:
        - **text:** Campo de texto de liha única.
        - **password:** Campo de texto que oculta o valor digitado com asteriscos.
        - **checkbox:** Uma caixa de seleção que pode ser marcada com asteriscos.
        - **radio:** Um botão de opção, permitindo a seleçã de apenas um item em um grupo.
        - **submit:** Um botão que enia os dados do formulário.
        - **button:** Um botão clicável genérico.
        - **file:** Permite ao usuário selecionar um arquivo para upload.
        - **date:** Cria um campo de seleção de data.
        - **email:** Campo para entrada de endereços de e-mail.
        - **number:** Campo para inserir números.
        - **url:** Campo para selecionar
        - **color:** Campo para selecinar uma cor.
        - **range:** Um controle delizante para inserir um número de um intervalo.
        - **month:** Permite selecionar um mês e ano.
       
    - **name:** Identifica o nome do campo, usado para enviar dados ao servidor.
    - **id:** Identifica o elemento de forma única na página.
    - **value:** Define o valor inicial do campo.
    - **placeholder:** Exibe um texto de exemplo dentro do campo (desaparece quando  usuário digita).
    - **required:** Indica que o campo deve ser preenchido antes do envio do formulário.
    - **readonly:** Impede o usuário de modificar o valor do campo.
    - **disabled:** Desabilita o campo, tornando-o inativo.
    - **maxlength:** Limita o número máximo de caracteres que podem ser digitados.
    - **minlength:** Define o número mínimo de caracteres necessários.
    - **min:** Define o valor mínimo permitido para campos numéricos ou de data.
    - **max:** Define o valor máximo permitido para campos numéricos ou de data.
    - **multiple:** Permite a seleção de múltiplos arquivos ou valores (dependendo do tipo do campo).
    - **autofocus:** Foca automaticamente no campo quando a página carrega.
    - **pattern:** Define um padrão de expressão regular para validação do valor.


    
# Comandos de produtividade em Visual Studio Code

## Recursos Úteis 

Alguns recursos de produtividade estão disponíveis em **IDEs** como **VS Code** e visão  auxilizar na inserção e modificação de algumas estrutras da linguagem:

### Emmet abbreviation (Abreviações Emmet)

- `HTML:5`: Digite este comando seguido da tecla `TAB` para inserir uma estrutura padrão:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```


## Slide 
 - [**Introdução ao HTML na Prática.pptx**](https://hermes.dio.me/files/assets/e7860ad4-810b-4ca6-ac00-398ce51f3fad.pptx) - Apresentação utilizada no curso.

## Dicas

- **Artigos/Fórum:** você pode compartilhar conteúdos técnicos através de Artigos (visíveis globalmente na plataforma da DIO). Por outro lado, você também pode compartilhar suas conquistas e dúvidas usando os Fóruns (que são específicos para cada experiência educacional na DIO, como um Bootcamp por exemplo); 

 - **Pesquise na Web:** pode parecer óbvio, mas é importante frisar a importância das engines de busca no dia-a-dia de um profissional de TI. Caso não encontre o que procura dentro da DIO, pesquise sobre o assunto (conceito, dúvida, erro etc) na Internet. 

Bons estudos! 