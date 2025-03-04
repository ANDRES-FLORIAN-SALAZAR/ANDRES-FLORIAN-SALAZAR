<!DOCTYPE html>
<html>
<head>
  <style>
    /* Efecto en enlaces (hover con neón) */
    a:hover {
      color: #FF00FF;
      text-shadow: 0px 0px 5px #FF00FF, 0px 0px 15px #FF00FF;
      transition: text-shadow 0.3s ease, color 0.3s ease;
    }

    /* Efecto "zoom in" en imágenes */
    img:hover {
      transform: scale(1.1);
      transition: transform 0.3s ease-in-out;
      box-shadow: 0px 0px 10px #00FFFF, 0px 0px 20px #FF00FF;
      border-radius: 10px;
    }

    /* Animación en títulos (cambio de color lento) */
    h1, h2, h3 {
      animation: glow 2s infinite alternate;
    }

    @keyframes glow {
      0% {
        color: #39FF14;
        text-shadow: 0px 0px 5px #39FF14, 0px 0px 15px #39FF14;
      }
      100% {
        color: #FF00FF;
        text-shadow: 0px 0px 5px #FF00FF, 0px 0px 15px #FF00FF;
      }
    }

    /* Botones flotantes con animación */
    button {
      background: linear-gradient(135deg, #FF00FF, #39FF14);
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      font-family: 'Orbitron', sans-serif;
      color: #000;
      border-radius: 25px;
      cursor: pointer;
      box-shadow: 0px 4px 6px rgba(255, 255, 255, 0.3);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    button:hover {
      transform: translateY(-5px);
      box-shadow: 0px 8px 15px rgba(255, 255, 255, 0.5);
    }

    /* Efecto de luz en la tabla */
    table {
      box-shadow: 0px 0px 10px #FF00FF, 0px 0px 20px #39FF14;
      transition: box-shadow 0.3s ease-in-out;
    }

    table:hover {
      box-shadow: 0px 0px 20px #FF00FF, 0px 0px 40px #39FF14;
    }

    /* Efecto en las filas de tabla (hover) */
    table tr:hover {
      background: rgba(57, 255, 20, 0.1);
      transition: background 0.3s ease;
    }
  </style>
</head>

<body style="background-color: #000; color: #00FFFF; font-family: 'Orbitron', sans-serif;">

  <!-- Título -->
  <h1 align="center" style="color:#39ff14;"><b>🚀 Soy Duvan Andrés Florian Salazar 🌌</b></h1>

  <!-- Imagen -->
  <p align="center">
    <img src="imagenes/Fondo1.png" alt="GitHub" width="100%" height="150px" />
  </p>

  <!-- Navegación -->
  <h4 align="center" style="color:#FF00FF;">
    | <b><a href="#ciberseguridad" style="color:#FF00FF;">🛡️ Ciberseguridad</a></b> |
    <b><a href="#programacion" style="color:#FF00FF;">💻 Programación</a></b> |
    <b><a href="#contacto" style="color:#FF00FF;">✉️ Contacto</a></b> |
    <b><a href="#proyectos" style="color:#FF00FF;">📂 Proyectos</a></b> |
  </h4>

  <hr />

  <!-- Introducción -->
  <h2><b>🌠 Introducción</b></h2>
  <p style="color:#00FFFF; text-align:justify;">
    ¡Bienvenidos a mi mundo! Soy un apasionado explorador del vasto universo de la ciberseguridad y la programación. Mi enfoque principal está en proteger, construir y comprender cómo la tecnología puede transformar el mundo.
  </p>

  <hr />

  <!-- Áreas de Interés -->
  <h2><b>🔮 Áreas de Interés</b></h2>
  <ul style="color:#39FF14;">
    <li><b>🛡️ Ciberseguridad:</b> Encriptación, análisis de vulnerabilidades y protocolos de red.</li>
    <li><b>💻 Programación:</b> Desarrollo utilizando Python, CSS, HTML, Java, y Go.</li>
    <li><b>📚 Aprendizaje Continuo:</b> Exploración de nuevas tecnologías, metodologías y tendencias.</li>
  </ul>

  <hr />

  <!-- Herramientas y Tecnologías -->
  <h2><b>⚙️ Herramientas y Tecnologías</b></h2>
  <p align="center">
    <table align="center" style="width:90%; border-spacing: 0; box-shadow: 0 4px 8px rgba(255, 255, 255, 0.2); font-family: 'Orbitron', sans-serif; color:#39FF14; background: linear-gradient(135deg, #222222, #000000); border-radius: 10px; overflow: hidden;">
      <thead style="background: #FF00FF; color: #000; font-weight: bold;">
        <tr>
          <th style="padding: 15px;">🚀 Lenguajes</th>
          <th style="padding: 15px;">💾 Bases de Datos</th>
          <th style="padding: 15px;">🛠️ Entornos</th>
        </tr>
      </thead>
      <tbody>
        <tr style="text-align: center; border-bottom: 1px solid #FF00FF;">
          <td style="padding: 15px;">Python</td>
          <td style="padding: 15px;">MongoDB</td>
          <td style="padding: 15px;">Visual Studio Code</td>
        </tr>
        <tr style="text-align: center; border-bottom: 1px solid #FF00FF;">
          <td style="padding: 15px;">HTML/CSS/Java</td>
          <td style="padding: 15px;">SQL Server</td>
          <td style="padding: 15px;">Windows/Linux</td>
        </tr>
        <tr style="text-align: center; border-bottom: 1px solid #FF00FF;">
          <td style="padding: 15px;">Java</td>
          <td style="padding: 15px;">Django</td>
          <td style="padding: 15px;"></td>
        </tr>
        <tr style="text-align: center;">
          <td style="padding: 15px;">Go</td>
          <td style="padding: 15px;"></td>
          <td style="padding: 15px;"></td>
        </tr>
      </tbody>
    </table>
  </p>

  <hr />

  <!-- Proyectos Relevantes -->
  <h2><b>✨ Proyectos Relevantes</b></h2>
  <ul style="color:#00FFFF;">
    <li><b>ALPHA_WEB:</b> Creación de un codificador de contraseñas y un entorno de seguridad.</li>
    <li><b>PRUEBAS_SOFTWARE:</b> Pruebas de seguridad para aplicaciones y sistemas.</li>
    <li><b>TWITTER2:</b> Crear endpoints con respuesta de la aplicación utilizando MongoDB.</li>
    <li><b>nosql_taller5:</b> Uso y aprendizaje práctico de bases de datos NoSQL.</li>
    <li><b>TALLER-SQL:</b> Manejo avanzado de SQL Server para proyectos de análisis y desarrollo.</li>
    <li><b>AJEDREZ:</b> Creación básica de un juego de ajedrez con enfoque en lógica y diseño.</li>
  </ul>

  <hr />

  <!-- Contacto -->
  <h2><b>🌌 Encuéntrame en</b></h2>
  <p align="center">
    <a href="https://github.com/ANDRES-FLORIAN-SALAZAR" target="_blank">
      <img src="https://img.shields.io/badge/github-%2300acee.svg?color=181717&style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="https://www.linkedin.com/in/DUVAN-ANDRÉS-FLORIAN-SALAZAR/" target="_blank">
      <img src="https://img.shields.io/badge/linkedin-%2300ace>
