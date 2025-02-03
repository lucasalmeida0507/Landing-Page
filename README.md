# Landing-Page
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Inicial</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
</head>

<body style="background-color: black;">
    <header class="header" style="background-color: black;">
        <div class="logo" style="color: #f1bd2f;">Investigador Vasconcelos <img src="eagle.png" alt="" width="40px"></div>
        <nav class="nav">
        </nav>
        <div class="dropdown">
            <button class="btn btn-secondary" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" style="background-color: #f1bd2f; color: black; border-color: black;">
                <strong>☰</strong>
            </button>
            <div class="dropdown-menu" aria-labelledby="dropdownMenu2" style="background-color:#f1bd2f;">
              <a href="servicos.html" class="dropdown-item" type="button" style="color: #000000;"><strong>Serviços</strong></a>
              <a href="sobre.html" class="dropdown-item" type="button" style="color: #000000;"><strong>Sobre</strong></a>
              <a href="contato.html" class="dropdown-item" type="button" style="color:#000000 ;"><strong>Contato</strong></a>
            </div>
          </div>
    </header>

    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
        </ol>
        <div class="carousel-inner" style="align-items: center;">
            <div class="carousel-item active">
                <img class="d-block w-100" src="cadu24.png" alt="Primeiro Slide" style="size: 20px;">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="cadu23.png" alt="Segundo Slide" style="size: 20px;">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="cadu22.png" alt="Terceiro Slide" style="size: 20px;">         
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="cadu21.png" alt="Terceiro Slide" style="size: 20px;">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Anterior</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Próximo</span>
        </a>

        
    <div class="carousel-item">
        <img src="..." alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>...</h5>
          <p>...</p>
        </div>
      </div>

    </div>

    <section class="hero" style="background-color: black;">
        <div class="hero-content">
            <h1 style="color: #f1bd2f;">Agente de inteligência e investigação particular</h1>
            <p style="color: aliceblue;">Metódo seguro e sigiloso para extração de informações sobre empresas, instituições e pessoas.</p>
            <a href="sobre.html" class="cta-btn" style="background-color: #f1bd2f; color: black;"><strong>Saiba Mais</strong></a>
        </div>
    </section>

    <section class="features" style="background: radial-gradient(circle, #1d1d1d, #000000); /* Gradiente radial */
    height: 100vh;
    margin: 0;">
        <div class="feature">
            <h2 style="color: #f1bd2f;">Qualidade</h2>
            <p style="color: aliceblue;">Oferecemos serviços de qualidade para nossos clientes.</p>
        </div>
        <div class="feature">
            <h2 style="color: #f1bd2f;">Confiança</h2>
            <p style="color: aliceblue;">Nosso trabalho é baseado em confiança e transparência.</p>
        </div>
        <div class="feature">
            <h2 style="color: #f1bd2f;">Suporte</h2>
            <p style="color: aliceblue;">Estamos sempre prontos para ajudar você a alcançar seus objetivos.</p>
        </div>
    </section>

    <section id="contato" class="contact" style="background-color: #f1bd2f;">
        <h2>Depoimentos</h2>
        <form action="#">
            <input type="text" placeholder="Seu nome" required>
            <input type="email" placeholder="Seu e-mail" required>
            <textarea placeholder="Mensagem" required></textarea>
            <button type="submit" style="background-color: black;">Enviar</button>
        </form>
    </section>

    <footer class="footer" style="background-color: black;">
        <p>&copy; 2025 Investigador Vasconcelos. Todos os direitos reservados.</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"
        integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"
        integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy"
        crossorigin="anonymous"></script>
</body>

</html>
