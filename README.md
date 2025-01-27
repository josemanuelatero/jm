<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primera Página Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }
        nav a:hover {
            color: #3d8b40;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            margin-top: 20px;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a Mi Página Web</h1>
    </header>

    <nav>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <main>
        <section id="sobre-mi">
            <h2>Sobre mí</h2>
            <p>Hola, soy un apasionado del desarrollo web. ¡Gracias por visitar mi sitio!</p>
        </section>

        <section id="proyectos">
            <h2>Proyectos</h2>
            <p>Aquí puedes encontrar algunos de mis proyectos destacados.</p>
            <img src="https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=1080" 
                 alt="Edificio moderno">
        </section>

        <section id="contacto">
            <h2>Contacto</h2>
            <p>Puedes escribirme a: <a href="mailto:miemail@example.com">miemail@example.com</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Mi Nombre. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
