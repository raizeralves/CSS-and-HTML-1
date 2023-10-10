# CSS-and-HTML-1
Estilo de CSS e HTML para fazer botoes e uma tela legal

HTML:
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header></header>
    <main class="apresentacao">
        <section class="apresentacao__conteudo">
            <h1 class="apresentacao__conteudo__titulo">Que tal me dar uma chance de provar meu valor?<strong class="titulo-destaque"> Procuro emprego!</strong></h1>
            <p class="apresentacao__conteudo__texto">Olá! Sou Raí Alves, aprendendo a programar, formado em Redes de computadores e cursando Defesa Cibernética. Vamos conversar?</p>
            <div class="apresentacao__conteudo__links">
                <h2 class="apresentacao__links__subtitulo">Acesse minhas redes:</h2>
                <a class="apresentacao__links__link" href="https://www.instagram.com/1raialves/">Instagram</a>
                <a class="apresentacao__links__link" href="https://github.com/raizeralves">GitHub</a>
            </div>
        </section>
        <img src="imagem.jpg" alt="Raizera">
    </main>
    <footer></footer>
    
</body>
</html>



----------------------------------------------------------------XXXXXXXX------------------------------------------------------------------------




CSS:
@import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Montserrat:wght@400;600&display=swap');
* { 
    margin: 0;
    padding: 0;


}

body {
    height: 100vh ;
    box-sizing: border-box;
    background-color: black;
    color:aqua;
}

.titulo-destaque {
    color:white

}

.apresentacao{
    margin: 10% ;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.apresentacao__conteudo {
    width: 615px;
    display: flex;
    flex-direction: column;
    gap:40px;
}

.apresentacao__conteudo__titulo{
    font-size: 36px;
    font-family:'Krona One', sans-serif;
    color: deepskyblue;
}

.apresentacao__conteudo__texto {
    font-size: 24px;
    font-family: 'Montserrat', sans-serif;
}

.apresentacao__conteudo__links{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    gap: 32px;
}


.apresentacao__links__subtitulo{
    font-family: 'Krona one', sans-serif;
    font-weight:400;
    font-size: 24px;

    
}


.apresentacao__links__link{
    background-color: aqua;
    width: 280px;
    text-align: center;
    border-radius: 16px;
    font-size: 24px;
    font-weight: 600;
    padding: 21.5px 0;
    text-decoration: none;
    color: black;
    font-family:'Montserrat', sans-serif;
}



