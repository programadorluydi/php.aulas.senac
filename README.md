# php.aulas.senac
Aulas Senac Php
<?php
echo("Esse é o meu primeiro programa em PHP<br>");
$n1=1;
$n2=2;
echo("O resultado é: ". $n1+$n2 . "<br/>"); // Irá mostrar 3
// Soma
$n3="1";
$n4="2";
echo("O resultado é: ". $n3.$n4 . "<br/>");
// Concatenação
$nome="Marcos";
$sobrenome="Silva";
echo("Bem vindo, " . $nome . " " . $sobrenome . "<br/>");
$salario=1450.56;
echo("R$" . $salario . "<br/>");
$brasileiro=true;
echo($brasileiro);
?>



O que é o HTML?
// HTML, significa Hyper Text Markup Linguage- Linguage de Marcação de super texto.
// Os comandos HTML são chamados de TAGs. As Tags são palavras chave, que ficam cercadas pelos simbolos < >
Ex: <hr>..<body> e </body>. 
// As Tags são divididas em duas, TAG simples e composta: A TAG simples nao precisa ser encerrada 
Ex: <hr>....<br>..........<img>........<meta>
//Ja as Tag compostas precisam ser encerradas. Ex: <body>....</body>....<titlle>....</titlle>
//As Tags tanto simples como composta, possuem atributos(propriedades). Ex: <img src= "foto.jpg" alt ="Foto do cliente">
<body background ="red">..............</body>
// Para transformar codigo em objetos, imagens, cores, o navegador usa uma ferramenta chamada motor web 
Ele realiza o processo de reinderização, que é transformar codigo em objetos.
//Todo arquivo html deve ser salvo com a extensão HTML.
Para testas um arquivo HTML , nos o abrimos em um navegador web(Chorme, Opera, Edge, Firefox, Safari,Brave, Tor......)

// CSS, o que é ?

CSS  - Cascade Style Sheet- (Folha de estilo em cascata);
// É um linguagem de programação que serve para dar estilo ao HTML.
// É usado para definir a cor, tamanho, fonte, layout, entre outros estilos
O CSS é utilizado para fazer formataçao em paginas HTML.
Ex: <style>body{background-color: red;}</style>
//O CSS pode ser aplicado de 3 maneiras :
// 1- Inline: é aplicado diretamente no elemento HTML.
Ex: <body style="background-color: red;"></body>
// 2- Interno: é aplicado dentro do arquivo HTML.
Ex: <style>body{background-color: red;}</style>
// 3- Externo: é aplicado em um arquivo separado. ideal fazer arquivo externo 
Ex: <link rel="stylesheet" type="text/css" href="estilo.css"/>
//O CSS tem uma estrutura de seletores e propriedades.
Ex: body{background-color: red;}
//O seletor é o elemento HTML que você deseja aplicar o estilo.
//A propriedade é o estilo que você deseja aplicar.
//O valor é o valor que você deseja aplicar a propriedade.
Ex: body{background-color: red;}
//O seletor é o body.
//A propriedade é o background-color.


Tres maneiras 
- Arquivo externo css
- Embutir o css na tag head da pagina html 
- Aplicar diretamente na tag html desejada
//O CSS tem uma hierarquia de estilização.
//A hierarquia é a seguinte :
// 1- Estilo inline.
// 2- Estilo interno.
// 3- Estilo externo.
//O CSS tem uma propriedade chamada !important.
//Essa propriedade é usada para dar prioridade a um estilo.
Ex: body{background-color: red !important;}
//O CSS tem uma propriedade chamada cascade.
//Essa propriedade é usada para aplicar estilos em elementos filhos.
Ex: body{background-color: red;}
p{background-color: blue;}
//O paragrafo herdará o estilo do body e aplicará o seu proprio estilo.

Ha tres elementos de aplicaçao:
-ID- identificador, usamos hashtag #
-CLASS- classe, usamos ponto .
-TAG- tag, usamos o nome da tag
Ex: #id{background-color: red;}
.class{background-color: blue;}
tag{background-color: green;}

//O CSS tem uma propriedade chamada pseudo-classe.
//Essa propriedade é usada para aplicar estilos em elementos em um estado específ
Ex: a:hover{background-color: red;}
//O CSS tem uma propriedade chamada pseudo-elemento.
//Essa propriedade é usada para aplicar estilos em elementos que não existem
Ex: p::first-line{background-color: red;}
//O CSS tem uma propriedade chamada media query.
//Essa propriedade é usada para aplicar estilos em diferentes tamanhos de
tela
Ex: @media (max-width: 800px)
    body{background-color: red;}
    //O CSS tem uma propriedade chamada flexbox.
    //Essa propriedade é usada para aplicar estilos em elementos que precisam
    ser flexíveis
    Ex: .container{display: flex;}
    //O CSS tem uma propriedade chamada grid.
    //Essa propriedade é usada para aplicar estilos em elementos que precisam
    ser grid
    Ex: .container{display: grid;}
    //O CSS tem uma propriedade chamada position.
    //Essa propriedade é usada para aplicar estilos em elementos que precisam
    ser posicionados
    Ex: .container{position: absolute;}
    //O CSS tem uma propriedade chamada float.
    //Essa propriedade é usada para aplicar estilos em elementos que precisam
    flutuar
    Ex: .container{float: left;}





