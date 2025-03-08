# aula3-4

<!DOCTYPE html>
<html lang="pt">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="sty.css">
</head>


<body>
    <div class="title">


        <img width="180px" height="180px" src="c++.png" alt="c">
        <h1>C++ e Java</h1> 
        <img width="180px" height="180px" src="java.png" alt="j">
    </div>
   

    <div class="frame1">
        <p>home livros videos contatos</p>

    </div>

    <div class="tex">
<h2>introdução</h2>
<p>
    C++ (em português: lê-se "cê mais mais", em inglês lê-se see plus plus) é uma linguagem de programação compilada multi-paradigma (seu suporte inclui linguagem imperativa, orientada a objetos e genérica) e de uso geral. Desde os anos 1990 é uma das linguagens comerciais mais populares, sendo bastante usada também na academia por seu grande desempenho e base de utilizadores.
    </p>
 <p>Java é uma linguagem de programação orientada a objetos desenvolvida na década de 90 por uma equipe de programadores chefiada por James Gosling, na empresa Sun Microsystems. Em 2008 o Java foi adquirido pela empresa Oracle Corporation. 
</p>

<p>Java foi desenvolvida por um grupo de pesquisadores da SUN Microsystems por volta de 1990, pouco antes da explosão da Internet. Essa linguagem possui estrutura muito semelhante à da linguagem C, da qual descende imediatamente. Java tem em comum com a linguagem C++ o fato de ser orientada a objetos e mantém com esta uma alto grau de semelhança. 
</p>

    </div>

    <div class="fotos">
<h2>Livros</h2>  

</div>

       





 <div class="fote">
    <img width="300" height="450" src="book1 (1).jpg" alt="">
    <img width="300" height="450" src="book2.jpg" alt="">
     <img width="300" height="450" src="book3.jpg" alt="">
    
    </div>

<div class="tl">
    <h2>Aprenda a programar com Java e C++ na FEI.</h2>

</div>

<div class="links">
<iframe width="400" height="400" src="https://www.youtube.com/embed/4MHAOPxcnsQ
" frameborder="0"></iframe>
<iframe width="400" height="400" src="
https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3652.648556785657!2d-46.581586585019195!3d-23.724241184602274!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce4158ef9c7c05%3A0x776b798985695f52!2sCentro%20Universit%C3%A1rio%20FEI%20-%20Campus%20S%C3%A3o%20Bernardo%20do%20Campo!5e0!3m2!1spt-BR!2sbr!4v1630280666216!5m2!1spt-BR!2sbr" frameborder="0"></iframe>
</div>

<div class="tl3">
<h2>Contatos</h2>
</div>

<div class="tabela">
    <table border=2>
        <tr>
          <th>Nome</th>
          <th>email</th>
        </tr>
        <tr>
          <td>Prof. Dr. Fagner Pimentel</td>
          <td>fpimentel@fei.edu.br</td>
        </tr>
        <tr>
          <td>Prof. Dr. Issac Jesus da Silva</td>
          <td>issacjesus@fei.edu.br</td>
        </tr>
      </table>

</div>

</body>

</html>






body{background-color: #d3d3d3;}

.title
    {display: flex;
    background-color:#FEE4C3;
    justify-content: space-between;
    padding: 20px;
    width: 1800px;
    border: solid 5px #000a7a;
    color: #006705;
    font-size: 25px; 
    text-align: center;
    }  
   

    .frame1{
        position: relative;
        top:0px;
        left: 0px;
        display: flex;
        padding: 20px;
        width: 1810px;
        background-color: #87CEFA;
        justify-content: center;
        text-align: justify;
        word-spacing: 180px;
       color: #632D47;
       font-size: 15px ;
    }

    .tex{
        text-align: center;
        font-size: 20pt;
        font-family: sans-serif;
    }

    .fotos{text-align: center;
        font-size: 20pt;
    }

    .fote{
        display: flex;
        justify-content: space-around;
       }

     .tl
        {
        text-align: center;
        font-size: 20pt;
        }

     .links
        {
        display: flex;
        justify-content: space-evenly;
        }

        .tl3{
            text-align: center;
            font-size: 20pt;
        }

        .tabela{
            display: flex;
            justify-content: center;
            border-color: red;
            border-style: dashed;
            text-align: center;
            color:black;
            font-size: 15px;
           width: 300px;
            
        }
