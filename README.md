<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IEM Iot Projects SAS</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
            scroll-behavior: smooth;
        }
        header {
            background-color: #2c2c2c;
            padding: 20px;
            text-align: center;
            color: white;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffa500;
        }
        section {
            padding: 60px 20px;
            background-color: #fff;
        }
        section:nth-child(even) {
            background-color: #f9f9f9;
        }
        .hero {
            height: 100vh;
            background-image: url('https://cdn.pixabay.com/photo/2017/09/27/10/30/robot-2791671_1280.jpg');
            background-size: cover;
            background-position: center;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }
        .hero h1 {
            font-size: 4em;
            margin-bottom: 0.5em;
        }
        .hero p {
            font-size: 1.5em;
        }
        .content {
            max-width: 1200px;
            margin: auto;
        }
        .btn-primary {
            background-color: #ffa500;
            color: white;
            padding: 15px 30px;
            border: none;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s;
            border-radius: 5px;
        }
        .btn-primary:hover {
            background-color: #cc8400;
        }
        .services, .about, .projects, .team {
            display: flex;
            flex-wrap: wrap;
            gap: 40px;
        }
        .services div, .about div, .projects div, .team div {
            flex: 1;
            min-width: 280px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .services div:hover, .about div:hover, .projects div:hover, .team div:hover {
            transform: translateY(-10px);
        }
        .about img, .projects img, .team img {
            max-width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #2c2c2c;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
        }
        footer a {
            color: #ffa500;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
        .back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #ffa500;
            color: white;
            padding: 10px 15px;
            font-size: 1.2em;
            border-radius: 50%;
            display: none;
            cursor: pointer;
            transition: opacity 0.3s;
        }
        .back-to-top.visible {
            display: block;
            opacity: 1;
        }
        .counters {
            display: flex;
            justify-content: space-around;
            background-color: #fff;
            padding: 60px 0;
        }
        .counter {
            text-align: center;
        }
        .counter h2 {
            font-size: 3em;
            color: #ffa500;
        }
        .counter p {
            font-size: 1.2em;
        }
    </style>
</head>
<body>

<header>
    <h1>IEM Iot Projects SAS</h1>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#servicios">Servicios</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#nosotros">Nosotros</a>
        <a href="#contacto">Contacto</a>
    </nav>
</header>

<div class="hero" id="inicio">
    <div class="content">
        <h1>Transformamos tu Mundo con Tecnología</h1>
        <p>Expertos en monitoreo inalambrico</p>
        <button class="btn-primary" onclick="document.querySelector('#contacto').scrollIntoView({behavior: 'smooth'});">Contáctanos</button>
    </div>
</div>

<section id="servicios">
    <div class="content">
        <h2>Nuestros Servicios</h2>
        <div class="services">
            <div>
                <h3>Automatización y Control</h3>
                <p>Implementamos sistemas avanzados de automatización para optimizar la producción industrial.</p>
            </div>
            <div>
                <h3>Monitoreo de Variables</h3>
                <p>Instalamos y mantenemos sensores para CO2, temperatura, humedad y más, permitiendo un monitoreo ambiental en tiempo real.</p>
            </div>
            <div>
                <h3>Iluminación Inteligente</h3>
                <p>Proyectos de iluminación automatizada para industrias, oficinas y espacios comerciales.</p>
            </div>
            <div>
                <h3>Mecatrónica</h3>
                <p>Sistemas avanzados de mecatrónica, incluyendo máquinas de juegos y sistemas personalizados.</p>
            </div>
            <div>
                <h3>Mantenimiento Preventivo y Correctivo</h3>
                <p>Diagnóstico, mantenimiento y reparación de equipos de automatización y control industrial.</p>
            </div>
            <div>
                <h3>Instalación de Variadores de Frecuencia</h3>
                <p>Control de velocidad y eficiencia energética en motores industriales a través de variadores de frecuencia.</p>
            </div>
        </div>
    </div>
</section>

<section class="counters">
    <div class="counter">
        <h2>+900</h2>
        <p>Sensores LoRa instalados</p>
    </div>
    <div class="counter">
        <h2>+2000</h2>
        <p>Proyectos Completados</p>
    </div>
    <div class="counter">
        <h2>+10</h2>
        <p>Años de Experiencia</p>
    </div>
</section>

<section id="proyectos">
    <div class="content">
        <h2>Proyectos Destacados</h2>
        <div class="projects">
            <div>
                <h3>Automatización en Compensar</h3>
                <img src="https://cdn.pixabay.com/photo/2020/12/16/21/08/mosquitoes-5837702_960_720.jpg" alt="Proyecto Compensar">
                <p>Instalación de más de 900 sensores LoRa para monitoreo ambiental en Compensar, optimizando la gestión energética y el confort de los usuarios.</p>
            </div>
            <div>
                <h3>Proyecto de Iluminación Industrial</h3>
                <img src="https://cdn.pixabay.com/photo/2016/05/03/00/53/electrician-1368309_960_720.jpg" alt="Proyecto Iluminación">
                <p>Diseño y ejecución de un sistema de iluminación inteligente para una planta industrial, mejorando la eficiencia energética y productividad.</p>
            </div>
            <div>
                <h3>Integración de Sistemas de Mecatrónica</h3>
                <img src="https://cdn.pixabay.com/photo/2024/01/25/00/25/robot-8530783_1280.jpg" alt="Proyecto Mecatrónica">
                <p>Desarrollo de sistemas mecatrónicos personalizados para entretenimiento y soluciones industriales.</p>
            </div>
        </div>
    </div>
</section>

<section id="nosotros">
    <div class="content about">
        <div>
            <h2>Sobre Nosotros</h2>
            <p>En IEM Iot Projects SAS, combinamos innovación, tecnología y experiencia para ofrecer soluciones que optimizan los procesos industriales. Con más de una década de experiencia, somos líderes en automatización y control, con una vasta trayectoria en proyectos de sensores, iluminación, mecatrónica y proyectados a ser los mejores en monitoreo inalambrico.</p>
        </div>
        <div>
            <img src="https://cdn.pixabay.com/photo/2024/06/18/04/12/modern-farming-8836926_960_720.png" alt="Sobre Nosotros">
        </div>
    </div>
</section>

<section id="contacto">
    <div class="content">
        <h2>Contáctanos</h2>
        <p>¿Tienes un proyecto en mente? Contáctanos al número: <strong>+57 304 2915535</strong></p>
    </div>
</section>

<footer>
    <p>IEM Iot Projects SAS © 2024 - Todos los derechos reservados</p>
    <p>Visítanos: <a href="#">www.iem-iot.com</a></p>
</footer>

<div class="back-to-top" id="backToTop" onclick="window.scrollTo({ top: 0, behavior: 'smooth' });">↑</div>

<script>
    window.onscroll = function() {
        const backToTop = document.getElementById('backToTop');
        if (window.pageYOffset > 300) {
            backToTop.classList.add('visible');
        } else {
            backToTop.classList.remove('visible');
        }
    };
</script>

</body>
</html>
