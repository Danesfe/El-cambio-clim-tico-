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
            pointer-events: none; /* Hace que la imagen sea estática */
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
                    <img src="https://upload.wikimedia.org/wikipedia/commons/b/bb/Beach_erosion_4.jpg" alt="Erosión costera">
                    <p>Erosión costera<br>(Fuente: Wikimedia Commons)</p>
                </div>
                <div>
                    <a href="https://www.google.com/imgres?q=animado%20inundaciones&imgurl=https%3A%2F%2Fpreviews.123rf.com%2Fimages%2Fgreenpencil%2Fgreenpencil2108%2Fgreenpencil210800026%2F173953487-casa-de-caricaturas-inundada-de-agua-inundaciones-e-inundaciones-y-naturaleza-ilustraci%25C3%25B3n.jpg&imgrefurl=https%3A%2F%2Fes.123rf.com%2Fphoto_173953487_casa-de-caricaturas-inundada-de-agua-inundaciones-e-inundaciones-y-naturaleza-ilustraci%25C3%25B3n.html&docid=Zja2MBrOtSd-7M&tbnid=hqWZdWr82f-t0M&vet=12ahUKEwjG3_OP-sSGAxVU4skDHXtEKG8QM3oECCwQAA..i&w=1300&h=1300&hcb=2&ved=2ahUKEwjG3_OP-sSGAxVU4skDHXtEKG8QM3oECCwQAA" target="_blank">
                        <img src="https://previews.123rf.com/images/greenpencil/greenpencil2108/greenpencil210800026/173953487-casa-de-caricaturas-inundada-de-agua-inundaciones-e-inundaciones-y-naturaleza-ilustraci%C3%B3n.jpg" alt="Inundaciones">
                    </a>
                    <p>Inundaciones<br>(Fuente: 123RF)</p>
                </div>
                <div>
                    <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.freepik.es%2Fvectores%2Fsequia&psig=AOvVaw0AlZoxn2mShczOEStX6E0H&ust=1717697875553000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCKCHjfCJxYYDFQAAAAAdAAAAABAE" alt="Sequías">
                    <p>Sequías<br>Por causa del cambio climático, la temperatura terrestre ha aumentado, lo que ocasiona sequías.</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Cambio Climático - Todos los derechos reservados - Autor: Daniel Eliezer Pérez Martínez - Grupo 210 COBAEV 42</p>
    </footer>
</body>
</html>