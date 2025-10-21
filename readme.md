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

- **Exemplo 1:** Estrutura básica da linguagem HTML.

    ```html
    <html>
        <head>
        </head>
        <body>
        </body>
    </html>
    ```

- **Exemplo 2:** Tags e atributos mínimos para iniciar um documento escrito em HTML.

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

## Tags e atributos para adição e formatação de textos

- **Tags para separação e estilos**
    - **\<hr\>:** Inclui uma linha horizontal que separa tematicamente o conteúdo. É uma tag vazia (autcontida).
    - **\<br/\>:** Inclui uma quebra linha, forçando o texto seguinte a aparecer na linha de baixo.
    - **CSS (Cascading Style Sheets):** A forma mais flexível e recomendada para estilizar. Você pode aplicar estilos aos elementos `<div>`, `<span>` e outros, e definir o visual sem alterar a estrutura do HTML.

- **Tags de estrutura e organização**
    - **\<h1\> a \<h6\>:** Definem títulos, do mais importante (`<h1>`) ao menos importante (`<h6>`).
        - **\<h1\> e \</h1\>:** Deve ser utilizado apenas uma vez por página. Identifica o assunto principal do conteúdo.
        - **\<h2\> e \</h2\>:** Usado para subtítulos que dividem o conteúdo em secções principais. Pode haver múltiplos **\<h2\>** em uma página.
        - **\<h3\> e \</h3\>:** Usado para subseções dentro de uma seção **\<h2\>**.
        - **\<h4\> e \</h4\>:** Usado para subdivisões ainda menores dentro de uma seção **\<h3\>**.
        - **\<h5\> e \</h5\>:** Usado para subdivisões dentro de uma seção **\<h4\>**.
        - **\<h6\> e \</h6\>:** Usado para o nivel mais baixo de cabeçalho, subdividindo secções **\<h5\>**.
    - **\<p\> e \</p\>:** Inclui um parágrafo de texto.    
    - **\<ul\> e \</ul\>:** Usada para criar listas não ordenadas.
    - **\<ol\> e \</ol\>:** Usada para criar listas ordenadas.
    - **\<li\> e \</li\>:**  Usada para criar itens nas listas ordenadas e não ordenadas.
    - **\<div\> e \</div\> :** Cria uma seção de nível de bloco para agrupar outros elementos. É útil para aplicar estilos em um grupo de conteúdo. É um elemento não semântico.
    - **\<span\>:** Usada para agrupar elementos inline, como palavras ou frases específicas dentro de um parágrafo, para aplicar estilos pontuais.   

- **Tags de estilo de texto e aparência**
    - **\<b\> e \</b\>:** Torna o texto em **negrito** sem dar significado semântico adicional (estílo físico).
    - **\<strong\> e \</strong\>:** Indica que  texto tem forte importância ou ênfase, e é exibido em **negrito** por padrão (estilo semântico).
    - **\<i\> e \</i\>:** Torna o texto em *itálico* (estilo físico).
    - **\<em\> e \</em\>:** Enfatiza o texto, que geralmente é exibido em itálico (estilo semântico).
    - **\<u\> e \</u\>:** Torna o texto **sublinhado** ou **underline**.
    - **\<sup\> e \</sup\>:** Torna o texto **sobreescrito** ou **superscript**.
    - **\<sub\> e \</sub\>:** Torna o texto **subscrito** ou **subscript**.
    - **\<small\> e \</small\>:** Apresenta o texto em uma fonte menor que o padrão, usado para coisas como direitos autorais.
    - **\<mark\> e \</mark\>:** Destaca o texto, com se ele estivesse marcado com um marca-texto.
    - **\<font\> e \</font\>:** *(obsoleto)* Define cor, tamanho e tipo de fonte diretamente no HTML.

- **Tags de correções e revisões**
    - **\<del\> e \</del\>:** Indica texto removido (aparece riscado).
    - **\<ins\> e \</ins\>:** Indica texto inserido (aparece sublinhado).

- **Tags de código e entrada de dados**
    - **\<pre\> e \</pre/>:** Usada para preservar espaços, quebras de linha e formatação original do texto, o que é essencial para exibir códigos, saídas de programas, exemplos literais ou blocos de texto formatados - o mesmo contexto onde usamos `<code>`, `<samp>`, `<kbd>` e `<var>`.
    - **\<code\> e \</code\>:** Exibe um trecho de código.
    - **\<kbd\> e \</kdb\>:** Representa um tecla pressionada pelo usuário.
    - **\<var\> e \</var\>:** Indica uma variável.
    - **\<samp\> e \</samp\>:** Representa uma saída de programa.
    
- **Tags de citações e endereços**
    - **\<blockquote\> e \</blockquote\>:** Define uma citação longa em bloco.
    - **\<q\> e \</q\>:** Define uma sitação curta dentro de um parágrafo.
    - **\<address> e \</address\>:** Indica informações de contato.

- **Atributos para serem utilizados com as tags:** Os atributos são palavras especiais dentro das tags de abertura que fornecem informação a um elemento e modificam o seu comportamento. Alguns atributos aplicáveis às tags de formatação de texto.

    - **id:** Define um identificador único para um elemento específico. Auxilia na identificação de um elemento quando se utiliza Javascript.
    - **style:** Define um estilo ao texto, podendo ser uma cor, uma determinada fonte, um determinada tamanho, entre outros, aplicado diretemente a um elemento.
    - **class:** Define a classe a que esta tag pertence. A classe representa um conjunto de estilos pré-determinado que pode ser aplicado a mais de um elemento.


- **Exemplo 1:** Formatação de texto.

    ```html
    <body>
        <h1><strong id="titulo" style="color:blue;" class="titulo-principal">Meu primeiro <i>HTML!</i></strong></h1>

        <h2><strong><u>tecnologia<sup>*</sup></u></strong></h2>

        <blockquote>
            <i>O jeito DIO._ para você ganhar destaque mais rápido no mercado.</i>
        </blockquote>  

        <p>Os nossos cursos e programas de formação são criados em conjunto come specialistas das empresas <mark>inovadoras do mundo</mark>.</p>

        <blockquote>O sucesso é a soma de pequenos esforços repetidos dia após dia.</blockquote>

        <p>Como disse o autor: <q>Aprender é evoluir</q>.</p>        

        <address>Autor: Fabio Toledo Bonemer De Salvi - engfabiodesalvi@exemplo.com</address>
        
        <!--Obsoleto! Utilizar CSS!-->
        <font color="blue" size="4" face="Arial">Texto com estilo antigo</font>

        <p>Preço antigo: <del>R$50,00</del></p>

        <p>Preço novo: <ins>R$39,90</ins></p>

        <abbr title="HyperText Markup Language">HTML</abbr>

        <p>Baseado em <cite>Dom Casmurro</cite>, de Machado de Assis.</p>

        <p><dfn>API</dfn> é um conjunto de rotinas que permite a comunicação entre sistemas.</p>

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

- **Exemplo 3:** Códigos e entradas de dados.

    ```html
    <!--HTML-->
    <pre><code>
    &lt;p&gt;Olá, mundo!&lt;/p&gt;
    </code></pre>
    
    <!--JavaScript-->
    <pre><code>
    console.log("Olá, mundo!");
    </code></pre>    

    <!--C-->
    <pre><code>
    printf("Olá, mundo!\n");
    </code></pre>
    ```

## Tag para incluir figuras
    
- **\<img /\>:** Usada para incorporar uma imagem em uma página web. Utilize os atributos de **img** para definir o diretório da imagem, a largura da imagem, entre outros.
    - **src:** Este é um atributo obrigatório que especifica a URL (Uniform Resource Locator) ou caminho para o arquivo de imagem.
    - **width:** Define a largura da imagem em **pixel** (px) ou em **porcentagem** (%). Não precisa incluir a unidade **px**.
    - **style:** Utilize a propriedade `width` deste atributo para definir a largura da imagem utilizando a unidade **pixel** (px) e outras unidades, podendo ser:
        - **Unidades aboslutas:** Essas unidades têm um tamanho fixo e não mudam com base em outros elementos ou no tamanho da tela. São ideais para layouts de impressão, mas podem causar problemas de acessibilidade na web, pois não se adaptam às configurações do usuário.
            - **px (pixels)** Essas unidades têm um tamanho fixo e não mudam com base em outros elementos ou no tamanho da tela. São ideais para layouts de impressão, mas podem causar problemas de acessibilidade na web, pois não se adaptam às configurações do usuário.
            - **cm (centímetros), mm (milímetros), in (polegadas):** Usadas principalmente para folhas de estilo de impressão.
    - **Unidades relativas:** Essas unidades se adaptam com base no elemento pai, no elemento raiz (root) ou na janela de visualização (viewport), sendo a melhor opção para criar designs responsivos.
        - **Relativas à fonte**
            - **em:** Relativa ao `font-size` do elemento pai. Se o `font-size` do pai mudar, o tamanho em em também mudará.
            - **rem:** Relativa ao `font-size` do elemento raiz (`<html>`). Usada para garantir que o escalonamento seja consistente em toda a página, sem o problema de herança aninhada do em.
            - **ch:** Relativa à largura do caractere "0" (zero) da fonte atual.

        - **Relativas à viewport:**
            - **% (porcentagem):** Relativa à largura do elemento que a contém (elemento pai).
                - **Exemplo:** `width: 50%;` ocupará metade da largura do elemento pai.
            - **vw (viewport width):** Relativa a 1% da largura da janela de visualização do navegador. Uma `width: 100vw;` ocupará 100% da largura da tela.
            - **vh (viewport height):** Relativa a 1% da altura da janela de visualização.
            - **vmin (viewport minimum):** Relativa a 1% da menor dimensão da janela de visualização (altura ou largura).
            - **vmax (viewport maximum):** Relativa a 1% da maior dimensão da janela de visualização (altura ou largura).

- **Exemplo:** Incluindo uma imagem dendro da seção **\<body\>**.

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
            - **text:** Campo de texto de linha única.
            - **password:** Campo de texto que oculta o valor digitado com asteriscos.
            - **email:** Campo para entrada de endereços de e-mail.
            - **number:** Campo para inserir números.
            - **tel:** Um campo para números de telefone.
            - **url:** Campo para inserir um endereço URL.
            - **search:** Campo de busca otimizado para a entrada de termos de pesquisa.

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
            - **image:** Atua como um botão de envio (igual a `submit`), mas exibindo uma imagem clicável. As cordenadas do clique (x, y) são enviadas.           
    
    - **Atributos de controle de envio (`form*`)**
        - **`name`:** Identifica o nome do campo, usado para enviar dados ao servidor (chave usada no envio dos dados).
            - **Exemplo**
                ```html
                <input type="radio" name="genero" value="masculino"> Masculino
                <input type="radio" name="genero" value="feminino"> Feminino
                ```
        - **`form`:** Associa um campo de entrada de dados `input` a um `<form>` específico, mesmo que este campo esteja localizado em qualquer outra parte do documento HTML e não dentro da tag.
            - **Exemplo**
                ```html
                <!-- O formulário com o ID "contato" -->
                <form id="contato" action="/enviar-dados" method="post">
                    <label for="nome">Nome:</label>
                    <input type="text" id="nome" name="nome">
                    <br>
                    <label for="email">E-mail:</label>
                    <input type="email" id="email" name="email">
                </form>

                <!-- O botão de envio fora da tag <form>, mas associado a ela pelo atributo 'form' -->
                <p>
                    Clique no botão para enviar o formulário.
                    <input type="submit" value="Enviar" form="contato">
                </p>                
                ```
        - **`formaction`:** URL de destino dos dados ao enviar (`submit`específico).\
        Ele substitui o atributo `action` da tag `<form>` para o botão `submit` (ou `image`) em que é usado.\
        Isso permite que um formulário tenha vários botões de envi, cada um enviando os dados para um destin diferente.
            - **Exemplo**
                ```html
                    <form action="/salvar-dados.php">
                        <label for="nome">Nome:</label>
                        <input type="text" id="nome" name="nome">
                        <br><br>

                        <input type="submit" value="Salvar no banco de dados">

                        <input type="submit" formaction="/enviar-por-email.php" value="Enviar por e-mail">
                    </form>                
                ```
        - **`formactype`:** Define o tipo de codificação dos dados enviados ao servidor.\
        Funciona apenas em elementos `<input>` com `type="submit"` ou `type="image"`e sobrescreve o atributo `enctype` definido na tag `<form>` principal.
            - **`application/x-www-form-urlencoded`:** É o valor padrão. Codifica todos os caracteres antes de enviá-los, convertendo espaços em `+` e caracteres especiais em seus valores hexadecimais.
            - **`multipart/form-data`:** Usado para enviar dados de formulários que contêm arquivos, como imagens e documentos. Ele não codifica os caracteres. É obrigatório para o envio de arquivos.
            - **`text/plain`:** Converte espaços em `+`, mas não codifica os caracteres especiais.
            - **Exemplo**
                ```html
                <form action="/destino.php" method="post">
                    <label for="fname">Primeiro nome:</label>
                    <input type="text" id="fname" name="fname"><br><br>
                    
                    <label for="arquivo">Anexar arquivo:</label>
                    <input type="file" id="arquivo" name="arquivo"><br><br>
                    
                    <!-- Botão de envio padrão -->
                    <input type="submit" value="Enviar Dados">
                    
                    <!-- Botão de envio que sobrescreve o enctype do formulário para upload -->
                    <input type="submit" formenctype="multipart/form-data" value="Enviar com arquivo">
                </form>             
                ```
        - **`formmethod`:** Usado para substituir o método HTTP especificado no atributo `method` da tag `<form>` à qual ele pertence.
            - **`get`:** Envia os dados do formulário como pares de nome/valor na URL.
                - Os dados ficam visíveis na barra de endereço do navegador.
                - É menos seguro e tem um limite de quantidade de dados a serem enviados.
                - É mais adequado para consultas de busca e dados não sensíveis.
            - **`post`:** Envia os dados do formulário dentro do corpo da solicitação HTTP.
                - Os dados não ficam visíveis na URL.
                - É mais seguro e não tem limitações de quantidade de dados.
                - É o método preferido para enviar dados sensíveis, como senhas.
            - **Exemplo**
                ```html
                <form action="/action_page.php" method="post">
                    Primeiro nome: <input type="text" name="fname"><br>
                    Último nome: <input type="text" name="lname"><br>
                    <button type="submit">Enviar com POST (método padrão)</button>
                    <button type="submit" formmethod="get">Pesquisar (com GET)</button>
                </form>            
                ```
        - **`formtarget`:** Usado para especificar onde a resposta do servidr, após a submissão de um formulário, deverá ser exibida.\
        Funciona com uma substituição local para o atributo `target` da tag `<form>` à qual o input pertence.\
        Aplicável apenas a inputs com o `type` igual a `submit` (botão de envio) ou `image` (botão de imagem).
            - **`_self` (valor padrão):** Abre a resposta na mesma janela ou na aba em que o formulário foi enviado.
            - **`_blank`:** Abre a resposta em uma nova janela ou aba do navegador.
            - **`_parent`:** Exibe a resposta no frame pai d frame atual.
            - **`_top`:** Abre a resposta no corp da janela do navegador, cancelando qualquer estrutura de frames que possa existir.
            - **`framename`:** Exibe a resposta em um `<iframe>` (ou frame) específico, nomeado com esse valor.
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

    - **Atributos de comportamento e acessibilidade**
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

    - **Atributos de aparência e layout**
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
    - **`target`:** Especifica onde abrir o link (`_blank`, `_self`, etc).
    - **`title`:** Exibe uma dica ao passar o mouse.
    - **`download`:** Faz o link baixar o arquivo em vez de abri-lo.
    - **`rel`:** Define a relação entre o document e o link (`noopener`, `nofollow`, etc).
    - **`type`:** Indica o tipo MIME do recurso (ex: `application/pdf`).
    - **`hreflang`:** Define o idioma do destino.

- **Exemplo**

    ```html
    <body>
        <h1>Sobre o meu site</h1>
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