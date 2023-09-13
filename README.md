# Michael
Projeto de Jogadores
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="assets/css/template.css">
    <title>Página de Apresentação</title>
</head>
<header>
</header>
<body>
    <header></header>
        <div class="Jogadores">
            <h1>Conheça Os melhores 5 jogadores</h1>
        </div>
    </header>

<section id="Link">
    <div class="blusas">
        <a href="https://pt.wikipedia.org/wiki/Lionel_Messi">
            <img src="download.jpg" alt="">
            <h3>Lionel Messi/Idade 35 anos 24 de junho de 1987</h3>
        </a>
    </div>
    <div class="Link">
        <a href="https://pt.wikipedia.org/wiki/Cristiano_Ronaldo">
            <img src="download (2).jpg" alt="">
            <h3>Cristiano Ronaldo/Idade
                37 anos
                5 de fevereiro de 1985</h3>
        </a>
    </div>
    <div class="Link">
        <a href="https://pt.wikipedia.org/wiki/Neymar">
            <img src="download (3).jpg" alt="">
            <h3>Neymar/Idade
                30 anos
                5 de fevereiro de 1992</h3>
        </a>
    </div>
    <div class="Link">
        <a href="https://pt.wikipedia.org/wiki/Karim_Benzema">
            <img src="download (4).jpg" alt="">
            <h3>Karim Benzema/Idade
                34 anos
                19 de dezembro de 1987</h3>
        </a>
    </div>
    <div class="Link">
        <a href="https://pt.wikipedia.org/wiki/Robert_Lewandowski">
            <img src="download (5).jpg" alt="">
            <h3>Robert Lewandowski/Idade
                34 anos
                21 de agosto de 1988</h3>
        </a>
    </div>
</section>
<section id="button">
    <div class="buttonum">
        <button>
            <a href="">Quem é o melhor ?</a>
        </button>
        </div>
</section>

</body>
</html

CSS3 

body{
    margin: 0px;
    padding: 0px;

}
header{
    display: flex;
    justify-content:space-between ;
    width: 100%;
    height: 70px;
    margin: 0px;
    padding: 0px;
}
.jogadores {
    width: 100px;
    height: 60px;
    background-image: none;
   margin-left: 20px;
   margin-top: 10px;
}
.button{
    display: flex;
    width: auto;
    height: 40px;
    margin-left: 500px;
    margin-top: 50px;
    margin-bottom: 50px;
}
button{
    background-color: #000;
    border-radius: 15px;

}
button a{
    color: #fff;
    font-size: 25px;
    text-decoration: none;
}
#colecao{
    display: flex;
    justify-content: center;
    margin: 50px;
    margin-left: 100px;
}
.blusas{
    display: flex;
    justify-content: space-between;
}
#colecao,
.blusas,
a{
    text-decoration: none;
    color: #000;
    font-size: 25px;
}
#colecao,
.blusas,
img{
    width: 500px;
}
#colecao,
.blusasdois{
    display: flex;
    justify-content: space-between;
    margin-left: 100px;
}
#button{
    display: flex;
    width: auto;
    height: 40px;
}
.buttonum{
  margin-left: 200px;
}
