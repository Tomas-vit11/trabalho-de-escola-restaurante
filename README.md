<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Laitaliaestilo.css">
    <title>La Itália</title>
</head>
<body>
    <header>
        <div class="menu"> 
            <div class="logo">
            <img src="logo.png" alt="logo" class="logo">
            </div>
        <h1>La Italia Ristorante</h1>
            <div class="menu-links">
            <a href="cardapio.html">Cardapio</a>
            <a href="#contato">Contato</a>
            <a href="https://www.google.com/maps/place/Cidade+Deus,+Taubaté+-+SP/@-23.0388472,-45.5656249,3a,75y,187.67h,83.89t/data=!3m7!1e1!3m5!1shDMnrDyNuUMP3Dj59pNcvg!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D6.110512438514235%26panoid%3DhDMnrDyNuUMP3Dj59pNcvg%26yaw%3D187.67351713589233!7i16384!8i8192!4m15!1m8!3m7!1s0x94ccf8e10e95755f:0xc97888942aa49e86!2sCidade+Deus,+Taubaté+-+SP!3b1!8m2!3d-23.0387177!4d-45.5655942!16s%2Fg%2F1ymsdzcvz!3m5!1s0x94ccf8e10e95755f:0xc97888942aa49e86!8m2!3d-23.0387177!4d-45.5655942!16s%2Fg%2F1ymsdzcvz?entry=ttu&g_ep=EgoyMDI1MDYwOS4xIKXMDSoASAFQAw%3D%3D">Localização</a>
            </div>
        </div>
    </header>
    
    <h1 class="Promoção">Oferta do dia</h1>
    <!-- Slider de pratos em oferta -->
    <section class="slider-container" id="slider-container">
    <div class="slider">
        <div class="slide active">
        <a href="lasanha.html">
            <img src="prato1.png" alt="Lasanha Especial">
            <div class="slide-content">
                <h3>Spaghetti alla Carbonara</h3>
                <p>Massa ao molho de ovos, queijo pecorino, pancetta e pimenta preta.</p>
                <span class="preco" style="text-decoration: line-through; opacity: 0.7;">R$ 48,90</span>
                <span class="preco">R$ 41,55</span>
            </div>
        </a>
        </div>
        <a href="Pizza-margarita.html">
        <div class="slide">
            <img src="prato2.png" alt="Pizza Margherita">
            <div class="slide-content">
                <h3>Pollo al Marsala</h3>
                <p>Peito de frango ao molho de vinho Marsala e cogumelos.</p>
                <span class="preco" style="text-decoration: line-through; opacity: 0.7;">R$ 47,90</span>
                <span class="preco">R$ 42,90</span>
            </div>
        </div>
        </a>

        <a href="Risoto-d-camarão">
        <div class="slide">
            <img src="prato3.png" alt="Risoto de Camarão">
            <div class="slide-content">
                <h3>Salada verde com vinagrete balsâmico</h3>
                <p>Mix de folhas com molho balsâmico artesanal.</p>
                <span class="preco" style="text-decoration: line-through; opacity: 0.7;">R$ 23,00</span>
                <span class="preco">R$ 18,99</span>
            </div>
        </div>
        </a>

        <a href="Tiramisu.html">
        <div class="slide">
            <img src="prato4.png" alt="Tiramisu">
            <div class="slide-content">
                <h3>Tiramisù Classico</h3>
                <p>Sobremesa de camadas com café, mascarpone e cacau.</p>
                <span class="preco" style="text-decoration: line-through; opacity: 0.7;">R$ 28,90</span>
                <span class="preco">R$ 24,40</span>
            </div>
        </div>
        </a>
    </div>

    <!-- Botões de navegação -->
    <button class="nav-btn prev-btn" onclick="changeSlide(-1)">&#10094;</button>
    <button class="nav-btn next-btn" onclick="changeSlide(1)">&#10095;</button>
    
        <!-- Indicadores -->
    <div class="indicators">
        <span class="indicator active" onclick="currentSlide(1)"></span>
        <span class="indicator" onclick="currentSlide(2)"></span>
        <span class="indicator" onclick="currentSlide(3)"></span>
        <span class="indicator" onclick="currentSlide(4)"></span>
    </div>
    </section>
           
    
    <section class="explicação">
        <div class="texto">
            <div class="corpotext">
                <h1 class="titulo">Sobre nós</h1>
                <p>O restaurante Sabor & Alma nasceu da paixão de três grandes amigos pela gastronomia e pelo desejo de criar um espaço onde o sabor e a amizade se encontram. Fundado em 2022, cada integrante traz sua personalidade e talento para tornar nossa cozinha única e acolhedora.</p>
                <div class="subtitulo"><p>Leonardo Brito - Chefe executivo</p></div>
                <p>Nosso chefe Leonardo(Léo) é o mestre da cozinha, com formação sólida e uma criatividade sem limites. Ele combina ingredientes frescos e técnicas apuradas para criar pratos que são verdadeiras obras de arte, sempre buscando surpreender o paladar dos nossos clientes.</p>
                <div class="subtitulo"><p>Tomas Vitor – Sommelier e Gerente de Atendimento</p></div>
                <p>Com um conhecimento profundo sobre vinhos e bebidas, Tomas é quem cuida da experiência na sala, garantindo que cada cliente seja bem recebido e que a harmonização entre prato e bebida seja perfeita.</p>
                <div class="subtitulo"><p>Samuel Queiroz - Padeiro e confeiteiro</p></div>
                <p>Responsável por adoçar nossas refeições, Samuel traz o aroma irresistível do pão caseiro e das sobremesas feitas com receitas artesanais. Seu talento deixa qualquer visita ao Sabor & Alma ainda mais especial.</p>
                <p>Juntos, somos mais que um time - Somos uma familia que busca entregar o melhor sabor para você</p>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="contato">
            <p id="contato">Tel: (12) 98892-5710</p>
            <p>Localização: Rua Araraquara, nº 98</p>
        </div>
        <div class="creditos">
            &copy; 2025 - Página desenvolvida por TDAdevs
        </div>
    </footer>

        <script>
            let currentSlideIndex = 0;
            const slides = document.querySelectorAll('.slide');
            const indicators = document.querySelectorAll('.indicator');
            const totalSlides = slides.length;

            function showSlide(index) {
                slides.forEach(slide => slide.classList.remove('active'));
                indicators.forEach(indicator => indicator.classList.remove('active'));
                slides[index].classList.add('active');
                indicators[index].classList.add('active');
            }

            function changeSlide(direction) {
                currentSlideIndex += direction;
                if (currentSlideIndex >= totalSlides) currentSlideIndex = 0;
                if (currentSlideIndex < 0) currentSlideIndex = totalSlides - 1;
                showSlide(currentSlideIndex);
            }  

            function currentSlide(index) {
                currentSlideIndex = index - 1;
                showSlide(currentSlideIndex);
            }

            let sliderInterval = setInterval(() => {
                changeSlide(1);
            }, 5000);

            const sliderContainer = document.querySelector('.slider-container');

            sliderContainer.addEventListener('mouseover', () => {
                clearInterval(sliderInterval); // Pausa o autoplay
            });

            sliderContainer.addEventListener('mouseout', () => {
                sliderInterval = setInterval(() => {
                changeSlide(1);
                }, 5000); // Retoma o autoplay
            }); 
        </script>
    </body>
</html>
