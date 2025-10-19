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


- **Exemplo 1:** Texto dentro da seção **\<body\>** com as formatações acima.

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

- **Exemplo 2:** Lista ordenada e lista não ordena com itens e subitens.

    ```html
    <body>
        <h2>Minha primeira lista ordenada!</h2>
        <ol>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
            <li> Item 4
                <ol>
                    <li>Item 3.1</li>
                    <li>Item 3.2</li>
                    <li>Item 3.3</li>
                </ol>
            </li>
        </ol>

        <h2>Minha primeira lista não ordenada!</h2>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
            <li>Item4
                <ol>
                    <li>Item 3.1</li>
                    <li>Item 3.2</li>
                    <li>Item 3.3</li>
                </ol>
            </li>
        </ul>        
    </body>
    ```

## Tag para incluir figuras
    
- **\<img /\>:** Usada para incorporar uma imagem em uma página wen. Utilize os atributos de **img** para definir o diretório da imagem. sua largura, entre outros.
    - **src:** Este é um atributo obrigatório que especifica a URL (Uniform Resource Locator) ou caminho para o arquivo de imagem.
    - **width:** Define a largura da imagem. Poder ser um valor fixo em pixels (**px**) ou um valor percentual referente à largura do conteiner pai desta imagem.    

- **Exemplo:** Incluindo uma imagem dendo da seção **\<body\>**.

    ```html
    <body>
        <img width="250px" src="./images/image1.png"/>

        <img width="50%" src="./images/image1.png"/>    
    </body>
    ```

## Tag para incluir dados 

- **\<input\>:** Define um campo de formulário interativo que permite ao usuário inserir dados.\
A forma como ela é exibida e seu comportamento é determinada pelo atributo `type` e modificada por vários outros atributos:

    - **Atributo principal - `type`:**  Este atributo é o mais importante e define o tipo de controle que o `<input>` irá renderizar (o tipo de entrada) e, consequentemente, o comportamento e os atributos aplicáveis.   

        - **Entrada de texto e variações específicas**
            - **text:** Campo de texto de liha única.
            - **password:** Campo de texto que oculta o valor digitado com asteriscos.
            - **email:** Campo para entrada de endereços de e-mail.
            - **number:** Campo para inserir números.
            - **tel:** Um campo para números de telefone.
            - **url:** Campo para selecionar
            - **search:** 

        - **Seleção booleana ou exclusiva**      
            - **checkbox:** Uma caixa de seleção que pode ser marcada com asteriscos.
            - **radio:** Um botão de opção, permitindo a seleçã de apenas um item em um grupo.

        - **Upload e envio de imagens**
            - **file:** Permite ao usuário selecionar um arquivo para upload.

        - **Entrada de datas e horários**
            - **date:** Cria um campo de seleção de data.
            - **time:** Permite ao usuário selecionar um horário (horas e minutos).
            - **datetime-local:** Permite ao usuário selecionar data e hora local (sem fuso horário).
            - **month:** Permite selecionar um mês e ano.
            - **week:** Permite selecionar uma semana específica do ano.

        - **Seleção de intervalo numérico**
            - **range:** Um controle delizante para inserir um número de um intervalo.

        - **Seleção de cor**
            - **color:** Campo para selecinar uma cor.

        - **Valor oculto, enviado com o formulário**
            - **hidden:** Cria um campo invisível que envia dados ocultos junto com o formulário.

        - **Botões de ação**
            - **button:** Um botão clicável genérico.
            - **submit:** Um botão que envia os dados do formulário.
            - **reset:** Cria um botão que redefine tds os caps do formulário para seus valres iniciais (os definidos no HTML), sem enviar os dados ao servidor.
            - **image:** Atua como um botão de envio (igual a `submit`), mas exibindo uma imagem clicável. Envia as cordenadas do clique (x, y).           
    
    - **Atributos de controle de envio (`form*`)**
        - **`name`:** Identifica o nome do campo, usado para enviar dados ao servidor (chave usada no envio dos dados).
        - **`form`:** Associa o campo a um `<form>` específico, mesm fora dele.
        - **`formaction`:** URL de destino ao enviar (`submit`específico).
        - **`formactype`:** Define o tipo de codificação dos dados enviados (`multipart/form-data`, etc).
        - **`formmethod`:** Método HTTP (`get`, `post`).
        - **`formtarget`:** Alvo do envi (`_blank`, `_self`, etc).
        - **`formnovalidate`:** Ignora validação ao enviar este campo.
        - **`value`:** Define o valor inicial (padrão) do campo e tambném o valor enviado (se aplicável).
        - **`dirname`:** Envia a direção do texto (`ltr`, `rtl`) junto com o valor.

    - **Atributos de validação e restrição de dados**
        - **`required`:** Um atributo booleano para especifícar preenchido brigatório antes do envio do formulário.
        - **`pattern`:** Especifica uma expressão regular que o valor do campo deve corresponder para ser considerado válido.          
        - **`min`:** Define o valor mínimo permitido para campos numéricos ou de data.
        - **`max`:** Define o valor máximo permitido para campos numéricos ou de data.
        - **`minlength`:** Define o número mínimo de caracteres necessários.
        - **`maxlength`:** Limita o número máximo de caracteres que podem ser digitados.
        - **`step`:** Define o incremento permitido entre valores numéricos.
        - **`readonly`:** Impede o usuário de modificar o valor do campo, mas permite que o valor seja enviado com o formulário.
        - **`disabled`:** Desabilita o campo, tornando-o inativo, impedindo que o seu valor seja enviado.        
        - **`accept`:** Define os tipos de aqrquivos aceitos (`.jpg`, `image/*`, etc).
        - **`multiple`:** Permite a seleção de múltiplos arquivos ou valores (dependendo do tipo do campo).        

    - **Atributos de comportamento e acessibilidade:**
        - **`autofocus`:** Foca automaticamente no campo ao carregar a página.
        - **`autocomplete`:** Ativa/desativa autocompletar (`on`, `off`, `email`, `name`, etc) baseado em dados que o usuário inseriu anteriormente.
        - **`inputmode`:** Sugere tipo de teclado em dispositivo móveis (`numeric`, `email`, etc).
        - **`capture`:** Solicita entrada da câmera/microfone (em `file`).
        - **`placeholder`:** Exibe um texto de exemplo dentro do campo (desaparece quando o usuário digitar algo).
        - **`tabindex`:** Define rdem de navegação via tecla TAB.        
        - **`list`:** Permite vincular o campo a um elemento `<datalist>`, oferecendo opções de preenchimento automático.  
        - **`aria-*`:** Atributos de acessibilidade (ARIA).
        - **`enterkeyhint`:** Sugere o rótul do botão "Enter" no teclado virtual.
        - **`tittle`:** Texto exibido como dica ao passar o mouse.

    - **Atributos de aparência e layout`**
        - **`id`:** Identifica o elemento de forma única no campo, útil para associar com uma `<label>` ou para manipulação com JavaScript.
        - **`class`:** Define classes CSS para estilização.
        - **`style`:** Define estilos inline.
        - **`size`:** Largura do campo em caracteres.
        - **`width`:** Largura de um campo (para `type="image"`).
        - **`height`:** Altura de um campo (para `type="image"`).
        - **`alt`:** Texto alternativo (para `image`).
        - **`src`:** URL da imagem (para `image`).

    - **Atributos de estado e seleção**
    (Específicos para botões de opção e caixas de seleção).
        - **`checked`:** Define se  campo inicia marcado (`checked`, `radio`).
        - **`value`:** Valor ennviado quando marcado.

    - **Atributos de events (interatividade)
        - **`oninput`:** Executa código conforme o usuário digita.
        - **`onchange`:** Executa código quando o valor muda.
        - **`onclick`:** Ao clicar no campo.
        - **`onfocus`:** Ao ganhar foco.
        - **`onblur`:** Ao perder foco.

    - **Observação importante**
    O comportamento e a relevância de muitos atributos dependem diretamente do valor de `type`.\
    Por exemplo, `min`e `max` não se aplicam a `text`, mas são excenciais em `number` e `date`.


    




## Tag âncora (hyperlink)

- **\<a\> e \</a\>:** Define um link que pode nacegar para outra página, seção, arquivo ou ação.\
É um dos principais elementos de navegação em HTML.
Seus principais atributos são:

    - **`href`:** Define  destino d link (URL, âncora, e-mail, etc).
    - **`target`:** Especifica onde abrir  link (`_blank`, `_self`, etc).
    - **`title`:** Exibe uma dica ao passar o mouse.
    - **`download`:** Faz o link baixar  arquivo em vez de abri-lo.
    - **`rel`:** Define a relação entre o document e o link (`noopener`, `nofollow`, etc).
    - **`type`:** Indica o tipo MIME do recurso (ex: `application/pdf`).
    - **`hreflang`:** Define o idioma do destino.

- **Exemplo**

    ```html
    <body>
        <h1>Sobre meu site</h1>
        <a href="index.html" title="Página inicial" target="_self">< Voltar</a>
    </body>
    ```

# Comandos de produtividade em Visual Studio Code

## Recursos Úteis 

Alguns recursos de produtividade estão disponíveis em **IDEs** como **VS Code** e visão  auxilizar na inserção e modificação de algumas estrutras da linguagem:

### Emmet abbreviation (Abreviações Emmet)
Digite a abreviação desejada e, na sequencia, pressione a tecla `TAB`.

- `HTML:5`: Insere uma estrutura padrão:

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

- `ol>li*3`: Insere uma lista ordenada com três itens.
    ```html
    <ol>
        <li></li>
        <li></li>
        <li></li>
    </ol>
    ```    

- `ol>li{Item $}*3`: Insere uma lista ordenada com três itens, incluindo texto e uma numeração.
    ```html
    <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ol>
    ```

- `ul>li*3`: Insere uma lista não-ordenada com três itens.
    ```html
    <ul>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    ```    
- `ul>li{Item $}*3`: Insere uma lista não-ordenada com três itens, incluindo texto e numeração crescente.
    ```html
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    ```

- `li{Item 4}>ol>li{Item 3.$}*3`: Insere um item com texto definido e uma sub-lista ordenada com text definido e com numeração crescente.
    ```html
    <li>Item4
        <ol>
            <li>Item 3.1</li>
            <li>Item 3.2</li>
            <li>Item 3.3</li>
        </ol>
    </li>
    ```

- `ul>li*2>a`: Insere um lista não-ordenada com dois itens com link a definir.
    ```html
    <ul>
        <li><a href=""></a></li>
        <li><a href=""></a></li>
    </ul>
    ```

## Slide 
 - [**Introdução ao HTML na Prática.pptx**](https://hermes.dio.me/files/assets/e7860ad4-810b-4ca6-ac00-398ce51f3fad.pptx) - Apresentação utilizada no curso.

## Dicas

- **Artigos/Fórum:** você pode compartilhar conteúdos técnicos através de Artigos (visíveis globalmente na plataforma da DIO). Por outro lado, você também pode compartilhar suas conquistas e dúvidas usando os Fóruns (que são específicos para cada experiência educacional na DIO, como um Bootcamp por exemplo); 

 - **Pesquise na Web:** pode parecer óbvio, mas é importante frisar a importância das engines de busca no dia-a-dia de um profissional de TI. Caso não encontre o que procura dentro da DIO, pesquise sobre o assunto (conceito, dúvida, erro etc) na Internet. 

Bons estudos! 