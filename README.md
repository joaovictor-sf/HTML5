# Html5

## Table of Contents
+ [About](#about)
+ [Getting Started](#getting_started)
+ [Usage](#usage)
+ [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>
<b>HTML5</b> (HyperText Markup Language 5) é a quinta versão da linguagem de marcação utilizada para estruturar e apresentar conteúdo na web. Foi lançado pela primeira vez em 2014 e desde então se tornou a base fundamental para a construção de páginas web modernas.

O html funciona na base de <b>tags</b>, as tags são tudo no html

## Tags básicas
<a name = "tags_basicas"></a>
```
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

### &lt;!DOCTYPE html&gt;

Diz o tipo do Documento, nesse caso documento html.

### &lt;html lang="?"&gt;

É onde estará todo o código html, tudo estará dentro da tag <b>&lt;html&gt;</b>.

O lang=”” é onde será colocado a linguagem padrão do projeto, <b>en</b> é inglês, <b>pt-br</b> é portugues.

### &lt;head&gt;
 <a name = "usage"></a>
 O <b>head</b> é onde ficam as informações que não aparecem diretamente para o usuário.

### &lt;meta charset="UTF-8"&gt;
 <a name = "usage"></a>
<meta charset="UTF-8">
A tag <meta> representa diversos tipos de metadados que não podem ser expressos utilizando as tags &lt;title>, &lt;base>, &lt;link>, &lt;style>, e &lt;script>.

 ### &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
 <a name = "usage"></a>
 A <b>viewport</b> é a área visível da página web para o usuário. Isso fornece instruções para o navegador sobre como controlar as dimensões e a escala da página. 

<b>width=device-width</b> define a largura da página para seguir a largura da tela do dispositivo (que pode variar de acordo com o dispositivo). 

<b>initial-scale=1.0</b> define o nível inicial de zoom quando a página é carregada pelo navegador.


 ### &lt;title&gt;
 <a name = "usage"></a>
O Título da página

 ### &lt;body&gt;
 <a name = "usage"></a>
É onde ficam as informações que aparecem diretamente para o usuário.

 ## Tags mais simples do body
 <a name = "usage"></a>

 ```
        <h1>Título h1</h1><!--h1 a h6 são tags de cabeçalho-->
        <h2>Título h2</h2><!--Quanto maior o número menor a fonte-->
        <h3>Título h3</h3>
       
        A tag br serve para quebrar linhas.<br><!--TAG <br> significa break,
            serve para fazer uma quebra de linha-->
        Etiam hendrerit tincidunt diam, vitae iaculis urna porttitor sed.
        Nam vel purus aliquet, tempus nulla id, faucibus dolor.


        <p>A tag p serve para criar parágrafos</p><!--A tag <p> serve para criar paragrafos-->
        <hr><!--Cria uma linha horizontal-->
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>


        <p>Tem duas maneiras de deixar o texto em negrito, que é utilizando a <b>tag
            b</b> ou <strong>strong</strong>. Strong é o aconselhavel<!--O aconselhável é strong-->
        </p>
       
        <p>Para deixar em itálico tem duas opções: <i>i</i> e <em>em</em>, o indicado é o <em>em</em></p>
        <!--Para deixar em Itálico utilize a tag <em>-->
        <p>para criar uma <u>underline se utiliza a tag u</u> e quando vc quer criar um
            <strike>traço de errado se utiliza strike</strike></p>
            <!--Para deixar o texto em underline use <u>-->
            <!--Para deixar o texto com um risco de erro use <strike>-->
       
        <h1>Caracteres especiais:</h1>


        No html tem alguns Caracteres que possuem deveres específicos e
        por isso não podem ser digitados normalmente em um texto, esses caracteres são:
        <br>
        &lt;, &gt;, &amp;, &quot;, &apos;, &cent;, &pound;, &yen;, &euro;, &copy;, &reg;, e o espaço em branco(&nbsp;)
        <br>
        Para maís informações <a href="https://www.w3schools.com/html/html_entities.asp">Clique aqui</a>
 ```

 ### &lt;h1&gt; a &lt;h6&gt;
<a name = "usage"></a>

São tags de cabeçalho, quando maior o número menor a fonte

 ### &lt;br&gt;
 <a name = "usage"></a>

Faz uma quebra de linha

 ### &lt;p&gt;
 <a name = "usage"></a>
Cria parágrafos.

 ### &lt;a href=""&gt;
 <a name = "usage"></a>
Criar um link, que pode ser externo(colocando um link completo) ou interno(pagina.html). A sigla href significa: hyperlink reference.

 ## Modificadores de Texto

 ### Negrito
 <a name = "usage"></a>

Pode ser utilizado as tags &lt;b> ou &lt;strong>. A recomendada é  &lt;strong>.

 ### Itálico
 <a name = "usage"></a>
As tags são &lt;i> ou &lt;em>, o indicado é o &lt;em>.

 ### Underline
 <a name = "usage"></a>
A tag &lt;u>.

### Risco na palavra
 <a name = "usage"></a>
A tag &lt;strike>.

 ### Caracteres sem valor
 <a name = "usage"></a>
<, >, &, ", ', ¢, £, ¥, €, ©, ® e o espaço em branco( )

São caracteres que não podem ser escritos normalmente em html por terem alguma função para podermos utilizá-los temos que ultilizar troca-los respectivamente por: &lt - &gt - &amp - &quot - &apos - &cent - &pound - &yen - &euro - &copy - &reg - e o espaço em branco(&nbsp)

Adicione ";" no final.

## Imagem
 <a name = "usage"></a>

Para colocar uma imagem no site utilizando unicamente o html utiliza-se a tag &lt;img>

Exemplo:

Ex1: &lt;img src="Aqui vc coloca o endereço/link da imagem" height="altura" width="largura" alt="descrição">

Ex2: &lt;img src="" alt="" style="Podemos colocar o comprimento e largura desejado dentro de style (width: 287px;height: 625px)">

 ## Listas
 <a name = "usage"></a>
Para criar uma lista utilizam-se diversas tags simultaneamente.

Primeiro é decidido o tipo de lista, existem 3 tipos: ordenada, não ordenada e com descrição.

### Ordenadas e não ordenadas
 <a name = "usage"></a>

Para criar uma lista ordenada ou não ordenada usa-se, respectivamente, as tags &lt;ol> e &lt;ul>.

Para adicionar um item a lista, utiliza-se a tag &lt;li>.

 ### Com descrição
 <a name = "usage"></a>
Para criar uma lista com descrição usa-se a tag &lt;dl>.

Para adicionar um item à lista, utiliza-se a tag &lt;dt>.

Para adicionar uma descrição ao item, usa-se a tag &lt;dd>.

## Tabela
 <a name = "usage"></a>
 
&lt;table style=""> É onde ficará a tabela, o style pode ser utilizado para definir o tamanho da tabela

&lt;tr> Linha da tabela

&lt;th> são títulos de itens da tabela, ele centraliza e deixar em negrito o que estiver escrito

&lt;td> coluna da tabela

&lt;td rowspan=""> rowspan dz quantas linhas o item vai ocupar

&lt;td colspan=""> colspan dz quantas colunas o item vai ocupar

## Formulário
 <a name = "usage"></a>
Existem diversos tipos de formulários na internet, de telas de login à atividades. Assim como as listas, há diversas tags utilizadas na criação de formulários.

### Tags
 <a name = "usage"></a>

&lt;form action="processa.php"> é onde ficará o formulário action serviria para mandar as informações do formulário para por exemplo um código php.

&lt;input type=""> É onde começa a festa do formulário, possuindo diversos atributos e variações de type.

&lt;input type="text" name="login"> Uma área para colocar um pequeno texto, costuma ser utilizado para login.

&lt;input type="password" name="senha"> Uma área para colocar a senha que visualmente troca as letras por '*'.

&lt;input type="submit" value="Logar"> Uma botão para enviar os valores ao sistemas, value é o que estará escrito no botão.

&lt;input type="radio" name="sexo" value="M"> Ultilizado para escolher uma opção entre algumas escolhidas &lt;input type="radio" name="sexo" value="F"> Como sexo

&lt;input type="checkbox" name="linguagem" value="P"> Utilizado quando é possível escolher mais que uma opção &lt;input type="checkbox" name="linguagem" value="J">

&lt;select name="estado" id=""> Cria uma lista com opções rotativas.

&lt;option value="">BA</option> Opções da lista.

&lt;textarea name="" id="" cols="30" rows="10"> Uma área de texto a qual o tamanho pode ser ajustado pelo usuário cols serve para modificar a largura padrão e rows a altura padrão.