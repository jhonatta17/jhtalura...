# jhtalura...

!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>AluraBooks</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <header class="cabeçalho">
            <div class="container"> 
                <span class="cabeçalho__menu-hamburguer container__imagem"></span>
                <img src="img/Logo.svg" alt="Logo da AluraBooks" class="container__imagem">
            </div>
            <div class="container">
                <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos" class="container__imagem"></a>
                <a href="#"><img src="img/Compras.svg" alt="Carrinho de compras" class="container__imagem"></a>
                <a href="#"><img src="img/Usuario.svg" alt="Meu perfil" class="container__imagem"></a>
            </div>
        </header>
    </label>
    <ul class="lista-menu">
      <li class="lista-menu_titulo">Categorias</li>
      <li class="lista-menu_item">
        <a href="#" class="lista-menu_link">Programação</a>
      </li>
      <li class="lista-menu_item">
        <a href="#" class="lista-menu_link">Front-end</a>
      </li>
      <li class="lista-menu_item">
        <a href="#" class="lista-menu_link">Infraestrutura</a>
      </li>
      <li class="lista-menu_item">
        <a href="#" class="lista-menu_link">Business</a>
      </li>
      <li class="lista-menu_item">
        <a href="#" class="lista-menu_link">Design & UX</a>
      </li>
    </ul>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>AluraBooks</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="styles.css">
    
    </head>
    <div class="swiper-wrapper">
        <!-- Slides -->
        <div class="swiper-slide"><img src="img/Apachekafka.svg" alt="Livro sobre apache kafka e spring boot da alura books"></div>
        <div class="swiper-slide"><img src="img/Liderança.svg" alt="Livro sobre liderança em design design da alura books"></div>
        <div class="swiper-slide"><img src="img/Javascript.svg" alt="Livro sobre javascript assertivo da alura books"></div>
        <div class="swiper-slide"><img src="Guia Front-end.svg" alt="Livro Guia front end"></div>
        <div class="swiper-slide"><img src="Portugol.svg" alt="Livro sobre portugol"></div>
        <div class="swiper-slide"><img src="Acessibilidade.svg" alt="livro sobre acessibilidade"></di>
    </div>
    <script>
        const swiper = new Swiper('.swiper', {
            spaceBetween: 10,
            slidesPerView: 3,
            pagination: {
                el: '.swiper-pagination',
                type: 'bullets',
            },
        });
    </script>
    </body>
</html>
