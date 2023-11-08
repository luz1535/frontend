index.html

<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>MyPet</title>
    <meta charset="utf-8">

  </head>
  <body>

    <!--inicio dos links-->
    <header>
        <h2>MyPet</h2>
        <div class="links">
            <a href="index.html">Casa</a>
            <a href="Racasdepet.html">Raças de pet</a>
            <a href="cuidados.html">Cuidados</a>
            <a href="vacinas.html">Vacinas</a>
        </div>
    </header>
    <!--final dos links-->

    <!--inicio noticias-->
    <h1 class="sub-header">
        O site que cuida<br/>
        do bem estar do seu pet
    </h1>
    
    <div class="body-content">
        <h2 class="body-content-title">Notícias sobre pets</h2>
        <ul class="blog-posts">
            <li class="card">
                <img src="assets/card-image.svg"/>
                <div class="card-content">
                    <span class="card-date">não adicionada</span>
                    <h3>não adicionada<br/>não adicionada</h3>
                </div>
            </li>
            <li class="card">
                <img src="assets/card-image.svg"/>
                <div class="card-content">
                    <span class="card-date">não adicionada</span>
                    <h3>não adicionada<br/> não adicionada</h3>
                </div>
            </li>
            <li class="card">
                <img src="assets/card-image.svg"/>
                <div class="card-content">
                    <span class="card-date">não adicionada</span>
                    <h3>não adicionada<br/> não adicionada</h3>
                </div>
            </li>
        </ul>
    </div>
    <!--final noticias-->
    
    <!--inicio rodapé-->
    <footer>
        <h6>2023 | MYPET</h4>
        <a href="#" class="footer-link">ajuda</a>
    </footer>
    <!--final rodapé-->

  </body>
</html>

<!--inicio style-->
<style>
 html, body {
    height: 100%;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    margin: 0;
}

header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 50px;
    background: #48617a;
    opacity: .85;
    padding: 10px 50px;
    color: #FFFFFF;
}

a {
    margin: 5px;
    text-decoration: none;
    color: #FFFFFF;
}
.sub-header {
    display: flex;
    align-items: center;
    background: #48617a;
    margin: 0;
    padding: 0 50px;
    color: #FFFFFF;
    height: 250px;
}

.body-content {
    padding: 0 50px;
    color: #495057;
}

.body-content-title {
    margin: 60px 0;   
}

.blog-posts {
    display: flex;
    list-style-type: none;
    margin-bottom: 80px; 
    padding: initial;
}

.card {
    display: flex;
    align-items: end;
    margin-right: 20px;
}

img {
    width: 420px;
    height: 350px;
}

.card-content {
    position: absolute;
    color: #FFFFFF;
    margin: 20px;
}

.card-date {
    font-size: small;
    opacity: .8;
}

footer {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 50px;
    background: #48617a;
    padding: 10px 50px;
    color: #FFFFFF;
}

.footer-link {
    font-size: small;
    font-weight: 100;
}
</style>
<!--final style-->



cuidados.html

vacinas.html

racasdepet.html

pasta SRC
