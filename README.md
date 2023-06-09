<!DOCTYPE html>
<html>
<head>
  <title>MiPágina - Compra y venta de productos</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <!-- Barra de navegación -->
    <nav>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Productos</a></li>
        <li><a href="#">Vender</a></li>
        <li><a href="#">Mi perfil</a></li>
        <li><a href="#">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <section id="hero">
    <!-- Contenido de la página de inicio -->
    <h1>Bienvenido a MiPágina</h1>
    <p>Encuentra los mejores productos de segunda mano cerca de ti.</p>
    <a href="#" class="btn">Explorar</a>
  </section>

  <section id="product-list">
    <!-- Lista de productos -->
    <h2>Productos destacados</h2>
    <div class="product">
      <img src="producto1.jpg" alt="Producto 1">
      <h3>Nombre del producto</h3>
      <p>Descripción del producto</p>
      <span class="price">$99.99</span>
      <a href="#" class="btn">Ver detalles</a>
    </div>
    <div class="product">
      <img src="producto2.jpg" alt="Producto 2">
      <h3>Nombre del producto</h3>
      <p>Descripción del producto</p>
      <span class="price">$49.99</span>
      <a href="#" class="btn">Ver detalles</a>
    </div>
    <!-- Agregar más productos aquí -->
  </section>

  <section id="sell">
    <!-- Página para vender productos -->
    <h2>Vende tus productos</h2>
    <p>¡Gana dinero vendiendo tus productos usados!</p>
    <a href="#" class="btn">Vender ahora</a>
  </section>

  <section id="contact">
    <!-- Página de contacto -->
    <h2>Contacto</h2>
    <p>¿Tienes alguna pregunta o sugerencia? ¡Contáctanos!</p>
    <form>
      <label for="name">Nombre:</label>
      <input type="text" id="name" name="name">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email">
      <label for="message">Mensaje:</label>
      <textarea id="message" name="message"></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <!-- Pie de página -->
    <p>&copy; 2023 MiPágina. Todos los derechos reservados.</p>
  </footer
