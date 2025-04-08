<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blue Power Support</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0d1117;
      color: #ffffff;
    }
    header {
      background-color: #1f2937;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      color: #3b82f6;
      font-size: 2.5rem;
      margin: 0;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin-top: 10px;
    }
    nav a {
      color: #ffffff;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(to right, #1e3a8a, #2563eb);
      color: white;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }
    .btn {
      background-color: #3b82f6;
      color: white;
      padding: 12px 25px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1rem;
    }
    .servicio {
      margin-bottom: 30px;
    }
    form input, form select, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: none;
      border-radius: 5px;
    }
    form button {
      background-color: #3b82f6;
      color: white;
      border: none;
      padding: 12px;
      width: 100%;
      border-radius: 5px;
      font-size: 1rem;
    }
    footer {
      text-align: center;
      background-color: #1f2937;
      padding: 20px;
      margin-top: 40px;
      color: #9ca3af;
    }
  </style>
</head>
<body>
  <header>
    <h1>Blue Power Support</h1>
    <nav>
      <a href="#quienes">¿Quiénes somos?</a>
      <a href="#servicios">Servicios</a>
      <a href="#cotizacion">Cotización</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Tecnología que protege. Conexiones que perduran.</h2>
    <p>Expertos en seguridad electrónica y telecomunicaciones a tu servicio.</p>
    <a href="#cotizacion"><button class="btn">Solicita tu cotización</button></a>
  </section>

  <section id="quienes">
    <h2>¿Quiénes somos?</h2>
    <p>En <strong>Blue Power Support</strong>, ofrecemos soluciones modernas e integradas en seguridad electrónica y telecomunicaciones. Nuestro compromiso es brindarte tecnología confiable y un servicio de calidad con atención personalizada.</p>
  </section>

  <section id="servicios">
    <h2>Servicios</h2>
    <div class="servicio">
      <h3>Seguridad Electrónica</h3>
      <ul>
        <li>Cámaras de videovigilancia (CCTV)</li>
        <li>Sistemas de alarma</li>
        <li>Control de acceso</li>
        <li>Videoporteros</li>
      </ul>
    </div>
    <div class="servicio">
      <h3>Telecomunicaciones</h3>
      <ul>
        <li>Instalación y fusión de fibra óptica</li>
        <li>Cableado estructurado</li>
        <li>Enlaces inalámbricos</li>
      </ul>
    </div>
    <div class="servicio">
      <h3>Servicios Especializados</h3>
      <ul>
        <li>Mantenimiento preventivo y correctivo</li>
        <li>Asesoría técnica</li>
        <li>Levantamientos técnicos</li>
      </ul>
    </div>
  </section>

  <section id="cotizacion">
    <h2>Solicita tu cotización</h2>
    <form>
      <input type="text" placeholder="Nombre completo" required>
      <input type="text" placeholder="Empresa (opcional)">
      <select required>
        <option value="">Selecciona un servicio</option>
        <option value="seguridad">Seguridad Electrónica</option>
        <option value="fibra">Fibra Óptica</option>
        <option value="otros">Otros</option>
      </select>
      <input type="text" placeholder="Ubicación del proyecto" required>
      <input type="tel" placeholder="Teléfono o WhatsApp" required>
      <input type="email" placeholder="Correo electrónico" required>
      <textarea rows="4" placeholder="Comentarios o requerimientos adicionales"></textarea>
      <button type="submit">Enviar cotización</button>
    </form>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p><strong>Teléfono:</strong> +52 XXX XXX XXXX</p>
    <p><strong>Correo:</strong> contacto@bluepowersupport.com</p>
    <p><strong>Horario de atención:</strong> Lunes a Viernes 9:00 a.m. - 6:00 p.m. | Sábados 9:00 a.m. - 1:00 p.m.</p>
  </section>

  <footer>
    <p>&copy; 2025 Blue Power Support. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
