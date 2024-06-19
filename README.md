<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">
    <title>Curiosidades de Tecnologia</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
        <main id="cabecalho">
        
                <h1 class="titulo">Curiosidades de Tecnologia</h1>
                <p class="assunto">Tudo aquilo que você sempre quis saber sobre o mundo Tech, em um único lugar</p>
                <div><p>Home</p></div>
                <div><p>Notícias</p></div>
                <div></p> <p>Curiosidades</p></div>
                <div><p>Fale Conosco</p></div>
        </main>
    <main> 
        <section>
            <h1>História do Mascote do Android</h1>
            <p>Provavelmente você sabe que o sistema operacional Android, mantido pelo Google é um dos mais utilizados para dispositivos móveis em todo o mundo. Mas tavez você não saiba que o seu simpático mascote tem um nome e uma história muito curiosa? Pois acompanhe esse artigo para aprender muita coisa sobre esse robozinho.</p>
            <h2>A primeira versão</h2>
            <p>A primeira tentativa de criar um mascote surgiu em 2007 e veio de um desenvolvedor chamado Dan Morrill. Ele conta que abriu o Inkscape (software livre para vetorização de imagens) e criou sua própria versão de robô. O objetivo era apenas personificar o sistema apenas para a a sua equipe, não existia nenhuma solicitação da empresa para a criação de um mascote.</p>
            <img src="imagens/dan-droids.png" alt="foto da primeira tentativa de criar um mascote">
            <p>Essa primeira versão bizarra até foi batizada em homenagem ao seu criador: seriam os Dandroids.</p>
            <h2>Surge um novo mascote</h2>
            <p>A ideia de ter um mascote foi amadurecendo e a missão foi passada para uma profissional da área. A ilustradora Russa Irina Blok, também funcionária do Google, ficou com a missão de representar o pequeno robô de uma maneira mais agradável.</p>
            <img src="imagens/irina-blok.jpg" alt="foto da ilustradora Russa Irina Blok" >
            <p>A ideia principal da Irina era representar tudo graficamente com poucos traços e de forma mais chapada. O desenho também deveria gerar identificação rápida com quem o olha. Surgiu então o Bugdroid, o novo mascote do Android.</p>
            <img src="imagens/bugdroid.png" alt="foto de um robo é um humano" >
            <p>A principal inspiração para os traços do novo Bugdroid veio daqueles bonequinhos que ilustram portas de banheiro para indicar o gênero de cada porta. Conta a lenda que a artista estava criando em sua mesa no escritório do Google e olhou para o lado dos banheiros e a identificação foi imediata: simples, limpo, objetivo.</p>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/cKEA0-MOhOs?si=d8rDYiTJe7on9oiX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            <main>
                <section>
                    <article>
                        <h3>Quer aprender mais?</h3>
                        <p>Outro assunto curioso em relação ao Android é que cada versão sempre foi nomeada em homenagem a um doce, em ordem alfabética a partir da versão 1.5 até a 9.0.</p>
                        <ul>
                            <li>1.5 - Cupcake</li>
                            <li>1.6 - Donut</li>
                            <li>3.0 - Eclair</li>
                            <li>2.2 - Froyo</li>
                            <li>2.3 - Gingerbread</li>
                            <li>3.0 - Honeycomb</li>
                            <li>4.0 - Ice Cream Sandwich</li>
                            <li>4.1 - Jelly Bean</li>
                            <li>4.4 - KitKat</li>
                            <li>5.0 - Lolipop</li>
                            <li>6.0 - Marshmallow</li>
                            <li>7.0 - Nougat</li>
                            <li>8.0 - Oreo</li>
                            <li>9.0 - Pie</li>
                        </ul>
                        <p>Infelizmente, o Android Q não existiu, pois o Google resolveu pôr fim a essa divertida prática e começou a usar numerações, o que deu origem ao Android 10.</p>
                        <p>Acesse aqui o site Android History para conhecer a sequência das versões "adocicadas" e o que cada uma trouxe para o sistema Android.<p>
                    </article>
                </section>
            </main>
            
                <p>Então é isso! Espero que você tenha gostado do nosso artigo com essa curiosidade sobre o sistema Android e seu simpático mascote.</p>
        </section>
    
</main>
    <footer>
        <p>Site criado por Gustavo Guanabara para o CursoemVideo</p>
    </footer>
</body>
</html>




CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS CSS 

@charset "UTF-8";

body{
    background-color: rgba(71, 177, 71, 0.842);
}
main#cabecalho{
    background-image: linear-gradient(#058905bb,#146114c0,#174417c4);
    margin: 0px;
}
main{
    background-color: #fff;
    margin-left: 110px;
    margin-right: 110px;
    padding: 10px;
}
div{
    text-align: center;
    display: inline-table;
    margin-right: 20px;
    color: #fff;
}
div:hover{
    background-color: rgba(169, 169, 169, 0.699);
    height: 13px;
    width: auto;
}
footer{
    text-align: center;
    background-color: #174417c4;
    color: #fff;
    padding: 1px;
    height: 46px;
}
section#aprender{
    background-color: #1b6b1bcb;
    color: #fff;
}
article{
    background-color: #8fe28fe7;
}
h1{
    font-family: Arial, Helvetica, sans-serif;
    color: #197919;
}
h2{
    font-family: Arial, Helvetica, sans-serif;
    color: #115211;
    background-color: #19791962;
}
h3{
    background-color: #114911;
    color: #fff;
}
p{
    font-family: serif;
    text-align: justify;
}

h1.titulo{
    text-align: center;
    color: #fff;
}
p.assunto{
    text-align: center;
    color: #fff; 
}
