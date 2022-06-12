<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cordel moderno</title>
    <style>
      @charset "UTF-8";

@import url('https://fonts.googleapis.com/css2?family=Passion+One&family=Roboto+Serif:opsz,wght@8..144,200&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Roboto+Serif:wght@200&family=Sriracha&display=swap');



:root {
    --fonte1: Verdana, Geneva, Thoma, sans-serif; 
    --fonte2: 'Passion One', cursive;
    --fonte3: 'Sriracha', cursive;
}

*{
    margin: 0px;
    padding: 0px;
    font-size: 1em;
}
html, body{
    min-height: 100vh;
    background-color: darkgray;
    font-family: var(--fonte1);

    
}
header {
    background-color: black;
    color: white;
    text-align: center;
}
header > h1 {
    font-size: 10vw;
    font-family: var(--fonte2);
    padding-top: 50px;
    font-variant: small-caps
      
    
    
}

header > p {
    padding-bottom: 50px;
}
header a, footer a {
    color: white;
    text-decoration: none;
    font-weight: bolder;
}
header a:hover, footer a:hover {
    text-decoration: underline;
}

section {
    padding-top: 10vh;
    padding-bottom: 10vh;
    line-height: 2em;
    padding-left: 30px;
    font-family: var(--fonte3);
    font-size: 3vw;
}

section > p{
    padding-bottom: 2em;
}

section.normal {
    background-color: white;
    color: black;

}

section.imagem{
    background-color: rgb(41, 40, 40);
    color: white;
    box-shadow: inset 6px 6px 13px rgba(0, 0, 0, 0.432);
    background-size: cover;
    background-attachment: fixed;

}
section.imagem > p {
    display: inline-block;
    padding: 5px;
    background-color: rgba(14, 13, 13, 0.507);
    text-shadow: 1px 1px 0px black ;
}
section#img01{
    background-image: url('../imagens/background001.jpg');
    background-position: right center;
   

}
section#img02{
    background-image: url('../imagens/background002.jpg');
    
    

}
footer {
    background-color: black;
    color: white;
    text-align: center;
    padding: 10px;

}
     </style>
    
    <link rel="stylesheet" href="estilo/style.css">
</head>
<body>
        <header>
            <h1>Cordel Moderno</h1>

                <p>Por <a href=" https://www.recantodasletras.com.br/poesias/3186743" target="_blank">Milton Duarte</a>
                </p>             
        </header>

    <section class="normal">
        <p>
            Estou ficando cansado <br>
            Da tal tecnologia <br>
            Só se fala por e-mail <br>
            Mensagem curta e fria <br>
            Twitter e Facebook <br>
            Antes que eu caduque <br>
            Vou dizer tudo em poesia.
        </p>
    </section>

    

    <section class="imagem" id="img01">
        <p>
            Não é mais como era antes <br>
            É tudo abreviado <br>
            "Você" só tem duas letras <br>
            O "O" e o "E" foi riscado <br>
            Para declarar o amor <br>
            Basta botar uma flor <br>
            E um coração desenhado.
        </p>
    </section>

    

    <section class="normal">
        <p>
            Arroba agora não pesa <br>
            É parte de um endereço<br>
            Ponto final nem se usa<br>
            Ou vai até no começo<br>
            Agora é .com<br>
            Se o saite é muito bom<br>
            Ele vale um alto preço.<br>
        </p>
        <p>
                Pra piorar a liguagem<br>
                O emoticom é um risco<br>
                Tem símbolo para tudo<br>
                Ponto e vírgula e um asterisco<br>
                Um beijo significa<br>
                Pra entender como fica<br>
                Decifre esse rabisco.
        </p>
        
    </section>

    

    <section class="imagem" id="img02">
        <p>
            Tenho saudade das cartas<br>
            Escritas com a própria mão<br>
            Mandava no mês de Junho<br>
            Só chegava no Verão<br>
            Mas matava a saudade<br>
            Era texto de verdade<br>
            Nas linhas do coração.
        </p>

    </section>

    
    <section class="normal">
        <p>
            Agora, escrevo e envio <br>
            Chegando na mesma hora<br>
            Mas quando vou prosear<br>
            A pessoa foi embora<br>
            Abriu outro aplicativo<br>
            O mundo ficou cativo<br>
            Da tecnologia do agora.<br>
            Felizmente, pra orar<br>
            Não precisa de internet<br>
            Deus escuta todo mundo<br>
            Se quiser, faça esse teste<br>
            Dois pontos são dois joelhos<br>
            Seus lábios são aparelhos<br>
            Deixe que Deus interprete.
        </p>
    </section>
    <footer>
        <p><a href="https://github.com/Bluteco" target="_blank">Site Criando por Fabio no curso em video</a></p>
    </footer>
</body>
</html>
