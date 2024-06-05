<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cambio Climático</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em;
            text-align: center;
        }
        nav {
            margin: 0;
            padding: 0;
            background-color: #333;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        nav ul li {
            float: left;
        }
        nav ul li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav ul li a:hover {
            background-color: #111;
        }
        main {
            padding: 1em;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .image-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 1em;
        }
        .image-section img {
            max-width: 100%;
            height: auto;
            margin: 0.5em;
            border: 2px solid #ddd;
            border-radius: 5px;
        }
        .image-section div {
            flex: 1;
            max-width: 300px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>El Cambio Climático</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Inicio</a></li>
            <li><a href="#impact">Impacto</a></li>
            <li><a href="#solutions">Soluciones</a></li>
            <li><a href="#contact">Contacto</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Inicio</h2>
            <p>El cambio climático es uno de los mayores desafíos de nuestro tiempo. Afecta a todos los países y comunidades del mundo.</p>
        </section>
        <section id="impact">
            <h2>Impacto del Cambio Climático</h2>
            <p>El cambio climático está provocando fenómenos meteorológicos extremos, elevación del nivel del mar y pérdida de biodiversidad.</p>
            <div class="image-section">
                <div>
                    <a href="https://upload.wikimedia.org/wikipedia/commons/b/bb/Beach_erosion_4.jpg" target="_blank">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/b/bb/Beach_erosion_4.jpg" alt="Erosión costera">
                    </a>
                    <p>Erosión costera</p>
                </div>
                <div>
                    <a href="https://upload.wikimedia.org/wikipedia/commons/c/c6/Flooding_in_Venice_after_2019_meteorological_event.jpg" target="_blank">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/c/c6/Flooding_in_Venice_after_2019_meteorological_event.jpg" alt="Inundaciones">
                    </a>
                    <p>Inundaciones</p>
                </div>
                <div>
                    <a href="https://upload.wikimedia.org/wikipedia/commons/5/54/Drought_California_2014.jpg" target="_blank">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/5/54/Drought_California_2014.jpg" alt="Sequías">
                    </a>
                    <p>Sequías</p>
                </div>
            </div>
        </section>
        <section id="solutions">
            <h2>Soluciones para el Cambio Climático</h2>
            <p>Es crucial tomar medidas para reducir las emisiones de gases de efecto invernadero y adoptar prácticas sostenibles.</p>
            <div class="image-section">
                <div>
                    <a href="https://upload.wikimedia.org/wikipedia/commons/5/59/Solar_panels_on_Toyota_Corolla.jpg" target="_blank">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/5/59/Solar_panels_on_Toyota_Corolla.jpg" alt="Energía solar">
                    </a>
                    <p>Energía solar</p>
                </div>
                <div>
                    <a href="https://upload.wikimedia.org/wikipedia/commons/7/7e/Wind_Farm_%284%29.jpg" target="_blank">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Wind_Farm_%284%29.jpg" alt="Energía eólica">
                    </a>
                    <p>Energía eólica</p>
                </div>
                <div>
                    <a href="https://upload.wikimedia.org/wikipedia/commons/0/09/Tree-planting-team-Mexico-4005.jpg" target="_blank">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/0/09/Tree-planting-team-Mexico-4005.jpg" alt="Reforestación">
                    </a>
                    <p>Reforestación</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>Autor: Daniel Eliezer Pérez Martínez | Grupo 210 Cobaev 42 &copy; 2024 Cambio Climático. Todos los derechos reservados.</p>
    </footer>
</body>
</html>