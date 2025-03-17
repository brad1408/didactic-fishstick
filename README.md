<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Menú del Restaurante</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <header>
      <h1>Restaurante Delicioso</h1>
      <nav>
        <ul>
          <li><a href="#menu">Menú</a></li>
          <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <section id="menu">
      <h2>Menú de Platillos</h2>
      <div class="menu-item">
        <img
          src="https://cdn0.recetasgratis.net/es/posts/8/6/2/causa_limena_31268_orig.jpg"
          alt="Platillo 1"
        />
        <h3>Plato 1</h3>
        <p>Descripción del platillo delicioso.</p>
        <p class="price">$15.00</p>
      </div>
      <div class="menu-item">
        <img
          src="https://buenazo.cronosmedia.glr.pe/original/2020/10/01/5f76ad2b7663ac3db70632da.jpg"
          alt="Platillo 2"
        />
        <h3>Plato 2</h3>
        <p>Descripción del platillo delicioso.</p>
        <p class="price">$12.00</p>
      </div>
      <!-- Puedes agregar más elementos del menú aquí -->
    </section>

    <section id="sobre-nosotros">
      <h2>Sobre Nosotros</h2>
      <p>
        Somos un restaurante dedicado a ofrecer lo mejor de la comida gourmet.
        ¡Ven y disfruta de nuestros sabores únicos!
      </p>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <form>
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required />

        <label for="email">Correo electrónico:</label>
        <input type="email" id="email" name="email" required />

        <label for="mensaje">Mensaje:</label>
        <textarea id="mensaje" name="mensaje" required></textarea>

        <button type="submit">Enviar</button>
      </form>
    </section>

    <footer>
      <p>&copy; 2025 Restaurante Delicioso. Todos los derechos reservados.</p>
    </footer>

    <script src="scripts.js"></script>
  </body>
</html>
