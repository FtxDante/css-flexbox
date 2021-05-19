# Site feito com FlexBoox

## Ferramentas Usadas
1. **HTML5**
2. **CSS3**
3. **FlexBox**

*Aprendi o que é uma imagem HERO* (Que é uma imagem de fundo com o contéudo centralizado) e também coloquei em prática muito dos conhecimentos de flexbox.

![Principal, área com a navegação e uma imagem HERO](https://github.com/FtxDante/css-flexbox/blob/main/node-curso/img/Principal.png)

![Conheça, fotos das praias e do hotel](https://github.com/FtxDante/css-flexbox/blob/main/node-curso/img/Conhe%C3%A7a.png)

![NewsLetter, como para escrever o email](https://github.com/FtxDante/css-flexbox/blob/main/node-curso/img/NewsLetter.png)

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Paraiso</title>
    <link rel="stylesheet" href="/node-curso/css/reset.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap" rel="stylesheet">
    <link href="/node-curso/css/fontawesome-free-5.15.2-web/css/all.css" rel="stylesheet">

    <link rel="stylesheet" href="/node-curso/css/style.css">
</head>
<body>
    <header>

        <a href="#"><img src="/node-curso/img/logo.png" alt="Logo Hotel Paraiso"></a>

        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Reservas</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Conheça esse paraiso chamado Itacaré</h1>
        <h3>"Aconchego, conforto, simpatia e alto astral"</h3>
        <a href="#" class="btn">Saiba mais</a>
    </section>

    <section class="conheca-o-hotel">
        <h2>Conheça o Hotel Paraíso</h2>
        <p>Feche os olhos e imagine o paraíso. Um lugar tranquilo no meio da Mata Atlântica e banhado pelo oceano, onde voz encontra paz, comodidade, conforto e tranquilidade.</p>
        <hr>
        <ul class="grid">
            <li class="small" style="background-image: url(/node-curso/img/itacare-01.jpg);"></li>
            <li class="large" style="background-image: url(/node-curso/img/itacare-02.jpg);"></li>
            <li class="large" style="background-image: url(/node-curso/img/itacare-03.jpg);"></li>
            <li class="small" style="background-image: url(/node-curso/img/itacace-04.jpg);"></li>
        </ul>
    </section>

    <section class="caracteristicas">
        <h2>Uníco hotel de itacaré</h2>
        <p>Já que você não tem muitas opções mesmo, veja abaixo o que oferecemos.</p>
        <hr>

        <ul class="grid">
            <li>
                <i class="fas fa-location-arrow"></i>
                <h3>Localização</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aspernatur laborum totam asperiores aliquam maiores fugiat, dolorum, quisquam deserunt tempore perferendis consequatur eveniet dolorem autem similique aperiam pariatur ab illum cum.</p>
            </li>

            <li>
                <i class="fas fa-gift"></i>
                <h3>Pacotes de Oferta</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aspernatur laborum totam asperiores aliquam maiores fugiat, dolorum, quisquam deserunt tempore perferendis consequatur eveniet dolorem autem similique aperiam pariatur ab illum cum.</p>
            </li>

            <li>
                <i class="fas fa-home"></i>
                <h3>Acomodações</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aspernatur laborum totam asperiores aliquam maiores fugiat, dolorum, quisquam deserunt tempore perferendis consequatur eveniet dolorem autem similique aperiam pariatur ab illum cum.</p>
            </li>
        </ul>


    </section>

    <section class="newsletter">
        <h2>NewsLetter</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor asperiores tempore porro odio voluptate sapiente dolorum perferendis.</p>
        <hr>

        <form action="">
            <input type="text" placeholder="Email">
            <button> Cadastrar </button>
        </form>
    </section>

    <footer>
        <ul>
            <li><a href="#"><i class="fab fa-facebook"></i></a></li>
            <li><a href="#"><i class="fab fa-twitter"></i></a></li>
            <li><a href="#"><i class="fab fa-snapchat"></i></a></li>
            <li><a href="#"><i class="fab fa-pinterest"></i></a></li>
        </ul>
        <p>&copy; Todos os direitos reservados - Hotel Paraíso - 2023</p>
    </footer>

    <script>
        
    </script>
</body>
</html>
 
 
