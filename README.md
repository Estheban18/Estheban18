<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #0a0f14;
      color: #e0e0e0;
      margin: 0;
      padding: 20px;
      line-height: 1.6;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      background: #1a1f28;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 255, 255, 0.2);
    }
    .banner {
      text-align: center;
      padding: 20px 0;
    }
    .banner img {
      width: 100%;
      max-width: 600px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);
    }
    h1 {
      color: #00ffff;
      text-align: center;
      margin: 10px 0;
      font-size: 2.5em;
    }
    p {
      text-align: center;
      margin: 5px 0;
    }
    .bio {
      margin: 20px 0;
      padding: 15px;
      background: #222831;
      border-radius: 5px;
    }
    .tech-stack {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
      gap: 10px;
      margin: 20px 0;
    }
    .tech-stack img {
      width: 100%;
      height: auto;
      transition: transform 0.3s ease;
    }
    .tech-stack img:hover {
      transform: scale(1.1);
    }
    .social-links {
      text-align: center;
      margin: 20px 0;
    }
    .social-links a {
      margin: 0 10px;
      text-decoration: none;
      color: #00ffff;
    }
    .social-links a:hover {
      color: #ff00ff;
    }
    .snake-section {
      text-align: center;
      margin-top: 30px;
    }
    .snake-section img {
      width: 150px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(255, 0, 255, 0.5);
      transition: transform 0.3s ease;
    }
    .snake-section img:hover {
      transform: scale(1.1);
    }
    .snake-section p {
      font-style: italic;
      color: #ff00ff;
      text-shadow: 0 0 5px #ff00ff;
    }
    @media (max-width: 600px) {
      h1 { font-size: 1.8em; }
      .banner img { max-width: 100%; }
      .tech-stack { grid-template-columns: repeat(auto-fill, minmax(100px, 1fr)); }
      .snake-section img { width: 120px; }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="banner">
      <img src="your-photo-url-here" alt="Estheban's Photo Banner"/>
    </div>
    <h1>¡Hola! Soy Estheban, Desarrollador del Futuro 🚀</h1>
    <p>Estudiante en SENATI | 💻 Programador Full Stack en formación | 🔮 Futuro Ingeniero de Software</p>
    <div class="bio">
      <p>Actualmente aprendiendo desarrollo web y móvil en SENATI, trabajando en proyectos personales y explorando tecnologías como Python, MySQL, y Android Studio. Apasionado por resolver problemas con código y amante de la tecnología futurista. ¡Conéctate conmigo!</p>
    </div>
    <h2>Tech Stack:</h2>
    <div class="tech-stack">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
      <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white" alt="Android Studio"/>
      <img src="https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=xampp&logoColor=white" alt="XAMPP"/>
    </div>
    <div class="social-links">
      <a href="tu-enlace-facebook">Facebook</a> |
      <a href="tu-enlace-instagram">Instagram</a> |
      <a href="tu-enlace-linkedin">LinkedIn</a> |
      <a href="tu-enlace-twitter">Twitter</a> |
      <a href="mailto:tu-email@gmail.com">Email</a>
    </div>
    <div class="snake-section">
      <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZ3Z0a3F5eWVod3A3YXFmczM4a3U2cXF5c2x4d2M5aTBzM3NheWV6ZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l0Iyl55kTeh71nTWw/giphy.gif" alt="Cyber Snake"/>
      <p>🐍 Culebra Cibernética - Guardián del Código</p>
    </div>
  </div>
</body>
</html>
