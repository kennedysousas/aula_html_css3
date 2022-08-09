<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="utf-8">
    <title>Minha página</title>
    <link rel="stylesheet" type="text/css" href="CSS/style.css" <!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/4c49692760.js" crossorigin="anonymous"></script>
</head>

<body>
    <!-- menu (# ancora a seção)-->
    <nav class="navbar navbar-expand-lg navbar-light">
        <a class="navbar-brand" href="#">
            <img src="img/google-logo-1.png" width="150px">
        </a>
        <div class="collapse navbar-collapse">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" href="#quem-somos">Quem somos</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#parceiros">Parceiros</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#servicos">serviços</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contato">contato</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- cabecalho -->
    <header class="minha-pagina text-center margin">
        <h1>Minha página</h1>
        <p>Oferecemos os melhores sites para sua empresa
            <br>e também temos o melhor código
        </p>
    </header>

    <!-- seções separam o blocos do site -->
    <section id="quem-somos">
        <div class="container-fluid quem-somos text-center margin">
            <div class="container margin">
                <h2>Quem somos</h2>
                <p>Oferecemos os melhores serviços de site e aplicativos</p>
                <div class="margin">
                    <img src="img/contato.jpeg" width="400" height="400" class="rounded-circle">
                    <img src="img/servicos.jpeg" width="400" height="400" class="rounded-circle">
                </div>
            </div>
        </div>
    </section>

    <section id="parceiros">
        <div class="container-fluid text-center margin parceiros">
            <h2>Parceiros</h2>
            <p>Temos o melhor time</p>
            <div class="container margin">
                <div class="row">
                    <div class="col-lg 4">
                        <img src="img/time.jpeg" width="100%" height="400px" class="rounded-circle">
                    </div>
                    <div class="col-lg 4">
                        <img src="img/parceiros.jpeg" width="100%" height="400px" class="rounded-circle">
                    </div>
                    <div class="col-lg 4">
                        <img src="/img/time.jpeg" width="100%" height="400px%" class="rounded-circle">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="servicos">
        <div class="container-fluid text-center margin servicos">
            <h2>serviços</h2>
            <p>Entre em contato conosco e faça um agendamento</p>
            <div class="container margin">
                <div class="row">
                    <div class="col-lg 4">
                        <p>Lorem ipsum sit dolor</p>
                        <img src="/img/servicos.jpeg" width="100%">
                    </div>
                    <div class="col-lg 4">
                        <p>Lorem ipsum sit dolor</p>
                        <img src="/img/contato2.jpg" width="100%">
                    </div>
                    <div class="col-lg 4">
                        <p>Lorem ipsum sit dolor</p>
                        <img src="/img/contato2.jpg" width="100%">
                    </div>
                    <div class="col-lg 4">
                        <p>Lorem ipsum sit dolor</p>
                        <img src="/img/contato2.jpg" width="100%">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contato">
        <div class="container-fluid text-center margin contato">
            <div class="container margin">
                <div class="row">
                    <div class="col-lg 4">
                        <img src="img/email.png" width="50px">
                        <h4 style="margin-top: 0.25em;">Mensagem</h4>
                        <p><a href="mailto:kennedy_sousa_df@hotmail.com">Enviar mensagem</a></p>
                    </div>
                    <div class="col-lg 4">
                        <img src="img/numero.png" width="50px">
                        <h4 style="margin-top: 0.25em;">Telefone</h4>
                        <p><a href="tel:99999999">Entre em contato</a></p>
                    </div>
                    <div class="col-lg 4">
                        <i class="fa-solid fa-address-card fa-3x"></i>
                        <h4 style="margin-top: 0.25em;">contato</h4>
                        <p><a href="tel:99999999">Credenciais</a></p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- footer é rodapé -->
    <footer class="container-fluid text-center bg-footer">Desenvolvido por <a
            href="https://www.instagram.com/kennedysousas/" target="_blank" rel="noreferrer noopener">@kennedysousas</a>
    </footer>

</body>

<!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
    crossorigin="anonymous"></script>

</html>
