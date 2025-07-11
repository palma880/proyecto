<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Semana Santa</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff8f0;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #4B0082;
      color: white;
      text-align: center;
      padding: 20px;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
      cursor: pointer;
    }

    main {
      padding: 20px;
    }

    section {
      display: none;
    }

    section.active {
      display: block;
    }

    footer {
      background-color: #2E004E;
      color: white;
      text-align: center;
      padding: 10px 20px;
    }

    footer .social-icons {
      margin-top: 10px;
    }

    footer .social-icons a {
      display: inline-block;
      margin: 0 10px;
      color: white;
      text-decoration: none;
      transition: color 0.3s ease;
      vertical-align: middle;
    }

    footer .social-icons a:hover {
      color: #ffcc00;
    }

    footer .social-icons svg {
      width: 24px;
      height: 24px;
      fill: currentColor;
      vertical-align: middle;
    }

    img {
      margin: 10px;
      max-width: 100%;
      height: auto;
    }

    iframe {
      width: 100%;
      max-width: 100%;
      height: auto;
      aspect-ratio: 16 / 9;
    }

    @media (max-width: 768px) {
      nav a {
        display: inline-block;
        margin: 5px 8px;
        font-size: 14px;
      }
      main {
        padding: 15px 10px;
      }
    }

    @media (max-width: 480px) {
      header h1 {
        font-size: 24px;
      }
      nav a {
        font-size: 12px;
        margin: 5px 6px;
      }
      main {
        padding: 10px 5px;
      }
      footer {
        padding: 10px 5px;
      }
      footer .social-icons a {
        margin: 0 6px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Semana Santa</h1>
    <nav>
      <a onclick="mostrarSeccion('inicio')">Inicio</a>
      <a onclick="mostrarSeccion('historia')">Historia</a>
      <a onclick="mostrarSeccion('tradiciones')">Tradiciones</a>
      <a onclick="mostrarSeccion('galeria')">Galería</a>
    </nav>
  </header>

  <main>
    <section id="inicio" class="active">
      <h2>Bienvenidos</h2>
      <p>Descubre el significado y la celebración de la Semana Santa en Guatemala.</p>
    </section>

    <section id="historia">
      <h2>Origen de la Semana Santa en Guatemala</h2>
      <p>Festividad religiosa arraigada, con raíces que se remontan al siglo XVI, cuando los misioneros españoles introdujeron las celebraciones litúrgicas católicas. La Semana Santa en Guatemala es uno de los acontecimientos más notables del país, con procesiones, vigilias, marchas fúnebres, gastronomía de temporada y creación de tapices de flores y altares.</p>
    </section>

    <section id="tradiciones">
      <h2>Iglesias en Cuidad Capital de Guatemala y Antigua Guatemala</h2>
      <ul>
        <li>Parroquia Nuestra Señora De Candelaria Zona 1 Capital</li>
        <li>Rectoría Santuario Arquidiocesano del Señor San José Zona 1 Capital</li>
        <li>Parroquia Santísimo Nombre De Jesús, Templo De La Recolección Zona 1 Capital</li>
        <li>Templo de San Bartolomé Becerra Antigua Guatemala</li>
        <li>Parroquia Virgen de la Medalla Milagrosa Zona 7 Capital</li>
      </ul>
    </section>

    <section id="galeria">
      <h2>Imágenes de cortejos procesiones y videos de resumen de la Semana Santa 2025</h2>
      <img src="imagenes/candelaria_oficial.jpg" alt="Candelaria" />
      <img src="imagenes/recoleccion_2025.jpg" alt="Recolección 2025" />
      <img src="imagenes/jesus_caida.jpg" alt="Jesús Caído" />
      <img src="imagenes/de_los_milagros.jpg" alt="Procesión Jesús de los Milagros" />
      <br /><br />
      <iframe 
        src="https://www.youtube.com/embed/gUiVQkSbVkc" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
      </iframe>
    </section>
  </main>

   </section>
  </main>

  <footer>
    <p>&copy; 2025 Semana Santa</p>
    <div class="social-icons">
      <a href="https://www.facebook.com/share/19Wx238Ged//tuPagina" target="_blank" aria-label="Facebook">
        <svg viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.595 0 0 .594 0 1.326v21.348C0 23.406.595 24 1.325 24h11.495v-9.294H9.69v-3.622h3.13V8.413c0-3.1 1.894-4.788 4.659-4.788 1.325 0 2.466.099 2.797.143v3.24l-1.92.001c-1.505 0-1.797.715-1.797 1.763v2.31h3.587l-.467 3.622h-3.12V24h6.116C23.406 24 24 23.406 24 22.674V1.326C24 .594 23.406 0 22.675 0z"/></svg>
      </a>
      <a href="https://www.instagram.com/semanasantaenlinea?igsh=MXAydmJjZ3cwb2l2MA==/tuPerfil" target="_blank" aria-label="Instagram">
        <svg viewBox="0 0 24 24"><path d="M7.75 2h8.5A5.75 5.75 0 0122 7.75v8.5A5.75 5.75 0 0116.25 22h-8.5A5.75 5.75 0 012 16.25v-8.5A5.75 5.75 0 017.75 2zm0 1.5A4.25 4.25 0 003.5 7.75v8.5A4.25 4.25 0 007.75 20.5h8.5a4.25 4.25 0 004.25-4.25v-8.5A4.25 4.25 0 0016.25 3.5h-8.5zM12 7a5 5 0 110 10 5 5 0 010-10zm0 1.5a3.5 3.5 0 100 7 3.5 3.5 0 000-7zm4.75-.88a1.12 1.12 0 110 2.24 1.12 1.12 0 010-2.24z"/></svg>
      </a>
      <a href="https://www.tiktok.com/@semanasantaenlinea?_t=ZM-8wf8Q4SxlQL&_r=1/@tuUsuario" target="_blank" aria-label="TikTok">
        <svg viewBox="0 0 24 24"><path d="M9 3v12.75a3.75 3.75 0 103.75-3.75v-6h3v5.25A6.75 6.75 0 119 21a6.713 6.713 0 01-3.196-.77v-3.07A3.75 3.75 0 009 18V3h3z"/></svg>
      </a>
    </div>
  </footer>

  <script>
    function mostrarSeccion(id) {
      const secciones = document.querySelectorAll('main section');
      secciones.forEach(sec => sec.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
  </script>


</body>
</html>

