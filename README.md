<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Portfolio - Fito Venegas</title>
    <style>
        /* Estilos básicos */
        body {
            font-family: 'Helvetica', sans-serif;
            background-color: #f0f4f8;
            color: #2c3e50;
            margin: 0;
            padding: 0;
        }

        /* Navbar */
        .navbar {
            background-color: #34495e;
            color: white;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .navbar ul {
            list-style: none;
            display: flex;
            margin: 0;
        }

        .navbar li {
            margin: 0 15px;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            font-weight: 500;
        }

        .navbar a:hover {
            color: #f39c12;
        }

        /* Sección: Sobre mí */
        .about-section {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 50px 20px;
            background-color: #ffffff;
        }

        .about-content {
            max-width: 50%;
        }

        .about-content h2 {
            color: #2980b9;
            font-size: 28px;
            margin-bottom: 20px;
        }

        .about-content p {
            color: #7f8c8d;
            font-size: 18px;
            line-height: 1.6;
        }

        .profile-pic {
            border-radius: 50%;
            width: 150px;
            border: 3px solid #34495e;
        }

        /* Sección: Habilidades */
        .skills-section {
            background-color: #ecf0f1;
            padding: 50px 20px;
            text-align: center;
        }

        .skills-section h2 {
            font-size: 26px;
            color: #34495e;
            margin-bottom: 30px;
        }

        .skills-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .skill-card {
            background-color: #ffffff;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 300px;
            transition: transform 0.3s;
        }

        .skill-card:hover {
            transform: translateY(-5px);
        }

        .skill-card h3 {
            color: #2980b9;
            margin-bottom: 15px;
            font-size: 22px;
        }

        .skill-card p {
            color: #7f8c8d;
            font-size: 16px;
        }

        /* Sección: Proyectos */
        .projects-section {
            padding: 50px 20px;
            background-color: #f0f4f8;
        }

        .projects-section h2 {
            font-size: 26px;
            color: #34495e;
            text-align: center;
            margin-bottom: 30px;
        }

        .projects-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .project-card {
            background-color: #ffffff;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 300px;
            text-align: center;
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-card h3 {
            color: #2980b9;
            margin-bottom: 15px;
            font-size: 22px;
        }

        .project-card p {
            color: #7f8c8d;
            font-size: 16px;
            margin-bottom: 15px;
        }

        .btn {
            background-color: #2980b9;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #f39c12;
        }

        /* Sección: Contacto */
        .contact-section {
            background-color: #34495e;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }

        .contact-section h2 {
            font-size: 26px;
            margin-bottom: 20px;
        }

        .contact-section p {
            color: #bdc3c7;
            font-size: 18px;
            margin-bottom: 20px;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <!-- Contenedor Principal -->
    <header>
        <nav class="navbar">
            <div class="logo">
                <h1>Fito Venegas</h1>
            </div>
            <ul>
                <li><a href="#about">Sobre mí</a></li>
                <li><a href="#skills">Habilidades</a></li>
                <li><a href="#projects">Proyectos</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <!-- Sección: Sobre mí -->
    <section id="about" class="about-section">
        <div class="about-content">
            <h2>Licenciado en Periodismo y Comunicación</h2>
            <p>Hola, soy <strong>Fito Venegas</strong>, licenciado en periodismo y comunicación. Actualmente soy freelance y estoy en busca de mi primer trabajo como desarrollador front-end. Además, tengo más de 3 años de experiencia como trader de criptomonedas, lo que me ha enseñado análisis crítico, gestión de riesgos y toma de decisiones rápidas.</p>
        </div>
        <img src="FitoVenegas.jpg" alt="Imagen de perfil" class="profile-pic">
    </section>

    <!-- Sección: Habilidades -->
    <section id="skills" class="skills-section">
        <h2>Habilidades</h2>
        <div class="skills-container">
            <div class="skill-card">
                <h3>Front-End Developer</h3>
                <p>HTML, CSS, JavaScript</p>
            </div>
            <div class="skill-card">
                <h3>Cripto Trader</h3>
                <p>Más de 3 años de experiencia en trading de criptomonedas, análisis técnico y estrategias de inversión.</p>
            </div>
            <div class="skill-card">
                <h3>Periodismo y Comunicación</h3>
                <p>Experiencia en medios digitales, redacción, y producción de contenido.</p>
            </div>
        </div>
    </section>

    <!-- Sección: Proyectos -->
    <section id="projects" class="projects-section">
        <h2>Proyectos</h2>
        <div class="projects-container">
            <div class="project-card">
                <h3>Portfolio Personal</h3>
                <p>Mi primer proyecto como desarrollador front-end: un sitio web personal para mostrar mis habilidades y proyectos.</p>
                <a href="#" class="btn">Ver Proyecto</a>
            </div>
            <!-- Puedes agregar más proyectos aquí -->
        </div>
    </section>

    <!-- Sección: Contacto -->
    <section id="contact" class="contact-section">
        <h2>Contacto</h2>
        <p>Si estás interesado en contactarme, no dudes en enviarme un correo electrónico.</p>
        <a href="fitoovenegas@hotmail.com" class="btn">Enviarme un Email</a>
    </section>

    <footer>
        <p>&copy; 2024 Fito Venegas. Todos los derechos reservados.</p>
    </footer>

    <script>
        // Aquí puedes añadir código JavaScript en el futuro
    </script>
</body>
</html>
