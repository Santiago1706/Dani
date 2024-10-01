# Dani

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Síndrome de Down</title>
    <link rel="icon" type="image/png" href="https://example.com/favicon.png">
    <style>
        body {
            font-family: 'Times New Roman', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #85e3ff, #ff96b2);
            color: #8F00FF;
            overflow-x: hidden;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .logo {
            font-size: 1.8em;
            font-weight: bold;
            color: #8F00FF;
        }
        nav {
            position: absolute;
            top: 70px;
            left: -300px;
            background-color: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            z-index: 10;
            transition: left 0.5s ease;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 10px 20px;
        }
        nav ul li {
            margin: 5px 0;
        }
        nav ul li a {
            text-decoration: none;
            color: #8F00FF;
            font-weight: bold;
            padding: 10px 15px;
            display: block;
            transition: color 0.3s, background 0.3s;
        }
        nav ul li a:hover {
            color: #FFFFFF;
            background-color: #87CEEB;
            border-radius: 5px;
        }
        .menu-toggle {
            cursor: pointer;
            font-size: 2em;
            color: #87CEEB;
        }
        .menu-toggle div {
            width: 30px;
            height: 4px;
            background-color: #8F00FF;
            margin: 5px 0;
            transition: all 0.3s ease;
        }
        .hero {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            background-image: url('https://pauloliberalesso.wordpress.com/wp-content/uploads/2011/10/titulo.jpg');
            background-size: cover;
            background-position: center;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.4);
            z-index: 1;
        }
        .hero h1 {
            font-size: 4em;
            margin: 0;
            z-index: 2;
            position: relative;
        }
        .hero p {
            font-size: 1.5em;
            margin-top: 10px;
            z-index: 2;
            position: relative;
        }
        .section {
            padding: 60px 20px;
            background-color: white;
            color: #333;
            text-align: center;
        }
        .section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #8F00FF;
        }
        .section p {
            font-size: 1.2em;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
        }
        .toggle-container {
            display: flex;
            align-items: center;
            justify-content: space-around;
            margin: 20px 0;
        }
        .toggle-container img {
            max-width: 300px; /* Ajusta el tamaño de la imagen */
            border-radius: 10px;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: #87CEEB;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        .contact-form h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #87CEEB;
        }
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }
        .contact-form button {
            padding: 10px 20px;
            border: none;
            background-color: #87CEEB;
            color: white;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .contact-form button:hover {
            background-color: #87CEEB;
        }
        footer {
            background-color: #87CEEB;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Síndrome de Down</div>
        <div class="menu-toggle" onclick="toggleMenu()">
            <div></div>
            <div></div>
            <div></div>
        </div> <!-- Tres rayas -->
        <nav id="nav-menu">
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#Resumen">Resumen</a></li>
                <li><a href="#Problematica">Problematica</a></li>
                <li><a href="#Introducción">Introducción</a></li>
                <li><a href="#Resultados">Resultados</a></li>
                <li><a href="#Limitaciones-Problematica">Conclusión</a></li>
                <li><a href="#Referencias">Referencias</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="inicio">
        <div>
            <h1>Síndrome de Down</h1>
            <p>Daniela Tatiana Figueroa Pasos</p>
        </div>
    </section>

    <section class="section" id="Resumen">
        <div class="toggle-container" id="toggle-container">
            <div class="text-content">
                <h2>Resumen</h2>
                <p>En Salud y Bienestar, nos dedicamos a promover un estilo de vida saludable a través de programas educativos.</p>
            </div>
            <img src="https://previews.123rf.com/images/hafakot/hafakot1605/hafakot160500343/59133149-ilustraci%C3%B3n-3d-del-t%C3%ADtulo-de-s%C3%ADndrome-de-down-de-documentos-m%C3%A9dicos-medicial-concepto.jpg">
        </div>
    </section>
    <section class="section" id="Problematica">
        <div class="toggle-container" id="toggle-container">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBBzwQyg-pth6lzTo5tsblYvTeNiWrjTSrDw&s" alt="Descripción de la imagen">
            <div class="text-content">
                <h2>Problematica</h2>
                <p>Nuestro objetivo es empoderar a las personas con el conocimiento y los recursos necesarios.</p>
            </div>
        </div>
    </section>

    <section class="section" id="Introducción">
        <div class="toggle-container" id="toggle-container">
            <div class="text-content">
                <h2>Introducción</h2>
                <p>Nuestro objetivo es empoderar a las personas con el conocimiento y los recursos necesarios.</p>
            </div>
            <img src="https://img.freepik.com/fotos-premium/dia-mundial-sindrome-down-inscripcion-letras-madera-sobre-fondo-azul-palmas-bebe-amarillas-concepto-concienciacion-sobre-sindrome-down-banner-ilustracion-cartel_259471-219.jpg" alt="Descripción de la imagen">
        </div>
    </section>
      
      <section class="section" id="Resultados">
        <div class="toggle-container" id="toggle-container">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJrtj9E1i5jSxKW3Cjz7cx5csLNU_EhGIs2xzHxW6K8Yat8nc1Qmnu0XaaJeV4MUsJb_0&usqp=CAU">
            <div class="text-content">
                <h2>Resultados</h2>
                <p>Nuestro objetivo es empoderar a las personas con el conocimiento y los recursos necesarios.</p>
            </div>
        </div>
    </section>

 <section class="section" id="Conclusión">
        <div class="toggle-container" id="toggle-container">
            <div class="text-content">
                <h2>Conclusión</h2>
                <p>Nuestro objetivo es empoderar a las personas con el conocimiento y los recursos necesarios.</p>
            </div>
            <img src="https://static.vecteezy.com/system/resources/previews/011/610/321/non_2x/world-down-syndrome-day-multicolored-socks-two-color-ribbon-and-themed-lettering-for-banner-or-postcard-design-vector.jpg">
        </div>
    </section>

     <section class="section" id="Referencias">
        <div class="toggle-container" id="toggle-container">
            <img src="https://i0.wp.com/www.julianmarquina.es/wp-content/uploads/Buscador-de-documentos-a-traves-de-Internet.jpg?fit=1200%2C912&ssl=1">
            <div class="text-content">
                <h2>Referencias</h2>
                <p>CITA. Obtenido de <a href="LINK" target="_blank">LINK</a></p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Daniela Figueroa. - Síndrome de Down. Todos los derechos reservados.</p>
    </footer>

    <script>
        function toggleMenu() {
            const navMenu = document.getElementById('nav-menu');
            if (navMenu.style.left === '0px') {
                navMenu.style.left = '-300px';
            } else {
                navMenu.style.left = '0px';
            }
        }
    </script>
</body>
</html>
