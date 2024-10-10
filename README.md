# mi-sitio-barbie

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barbie World</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo-barbie.png" alt="Logo Barbie">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#about">Sobre Barbie</a></li>
                <li><a href="#collection">Colección</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Bienvenidos al Mundo de Barbie</h1>
        <p>Descubre lo último sobre Barbie, su colección y mucho más.</p>
    </section>

    <section id="about">
        <h2>Sobre Barbie</h2>
        <p>Barbie es mucho más que una muñeca, es un ícono cultural que inspira a niñas de todo el mundo a soñar en grande. Desde su creación en 1959, Barbie ha seguido evolucionando y ofreciendo modelos de roles diversos y empoderados.</p>
        <img src="barbie-historia.jpg" alt="Historia de Barbie">
    </section>

    <section id="collection">
        <h2>Colección</h2>
        <div class="gallery">
            <img src="barbie1.jpg" alt="Barbie 1">
            <img src="barbie2.jpg" alt="Barbie 2">
            <img src="barbie3.jpg" alt="Barbie 3">
        </div>
        <p>Descubre la amplia variedad de muñecas Barbie disponibles en nuestra colección exclusiva.</p>
    </section>

    <footer id="contact">
        <h3>Contacto</h3>
        <p>¿Tienes alguna pregunta o quieres saber más sobre Barbie? ¡Escríbenos!</p>
        <form action="#">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message"></textarea>
            <button type="submit">Enviar</button>
        </form>
        <p>&copy; 2024 Barbie World. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #fce4ec;
    color: #333;
}

header {
    background-color: #ff69b4;
    color: white;
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo img {
    height: 50px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 2rem;
    text-align: center;
}

section#home {
    background-color: #ffe4e1;
    padding: 3rem 2rem;
}

section#about img {
    max-width: 100%;
    height: auto;
    margin-top: 1rem;
}

section#collection .gallery {
    display: flex;
    justify-content: space-around;
    margin-top: 2rem;
}

section#collection .gallery img {
    width: 30%;
    border-radius: 10px;
}

footer {
    background-color: #ff69b4;
    color: white;
    padding: 2rem;
    text-align: center;
}

footer form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    max-width: 400px;
    margin: 0 auto;
}

footer input, footer textarea {
    padding: 0.5rem;
    border: 1px solid #ff69b4;
    border-radius: 5px;
}

footer button {
    padding: 0.7rem;
    background-color: white;
    color: #ff69b4;
    border: none;
    border-radius: 5px;
    font-weight: bold;
    cursor: pointer;
}
