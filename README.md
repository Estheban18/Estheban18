<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portafolio profesional de Estheban, desarrollador Full Stack en formación">
  <title>Estheban | Desarrollador en Formación</title>
  <style>
    :root {
      --primary-color: #2563eb;
      --secondary-color: #1e40af;
      --text-color: #333333;
      --light-text: #6b7280;
      --bg-color: #f9fafb;
      --card-bg: #ffffff;
      --border-radius: 8px;
      --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    
    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    
    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 2rem;
    }
    
    header {
      text-align: center;
      margin-bottom: 3rem;
    }
    
    .profile-picture {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin: 0 auto 1.5rem;
      border: 4px solid var(--primary-color);
      box-shadow: var(--box-shadow);
    }
    
    h1 {
      color: var(--primary-color);
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
      font-weight: 700;
    }
    
    .title {
      font-size: 1.25rem;
      color: var(--light-text);
      margin-bottom: 1.5rem;
      font-weight: 400;
    }
    
    .bio {
      max-width: 700px;
      margin: 0 auto 2rem;
      text-align: center;
      font-size: 1.1rem;
      line-height: 1.8;
    }
    
    .section {
      background-color: var(--card-bg);
      border-radius: var(--border-radius);
      padding: 2rem;
      margin-bottom: 2rem;
      box-shadow: var(--box-shadow);
    }
    
    .section-title {
      color: var(--primary-color);
      font-size: 1.5rem;
      margin-top: 0;
      margin-bottom: 1.5rem;
      font-weight: 600;
    }
    
    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    
    .tech-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      width: 100px;
    }
    
    .tech-icon {
      width: 50px;
      height: 50px;
      margin-bottom: 0.5rem;
    }
    
    .tech-name {
      font-size: 0.9rem;
      color: var(--light-text);
      text-align: center;
    }
    
    .social-links {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-top: 2rem;
    }
    
    .social-link {
      color: var(--primary-color);
      text-decoration: none;
      font-weight: 500;
      transition: color 0.2s;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }
    
    .social-link:hover {
      color: var(--secondary-color);
      text-decoration: underline;
    }
    
    .social-icon {
      width: 20px;
      height: 20px;
    }
    
    footer {
      text-align: center;
      margin-top: 3rem;
      color: var(--light-text);
      font-size: 0.9rem;
    }
    
    @media (max-width: 768px) {
      .container {
        padding: 1.5rem;
      }
      
      h1 {
        font-size: 2rem;
      }
      
      .title {
        font-size: 1.1rem;
      }
      
      .bio {
        font-size: 1rem;
      }
      
      .section {
        padding: 1.5rem;
      }
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
  <div class="container">
    <header>
      <img src="https://via.placeholder.com/150" alt="Foto de perfil de Estheban" class="profile-picture">
      <h1>Estheban Pérez</h1>
      <p class="title">Estudiante de Desarrollo de Software | Full Stack en formación</p>
      <div class="bio">
        <p>Actualmente cursando estudios en SENATI con especialización en desarrollo de software. Apasionado por crear soluciones tecnológicas innovadoras y eficientes. Mi objetivo es convertirme en un ingeniero de software altamente capacitado, combinando conocimientos técnicos con creatividad para resolver problemas complejos.</p>
      </div>
    </header>
    
    <div class="section">
      <h2 class="section-title">Habilidades Técnicas</h2>
      <div class="tech-stack">
        <div class="tech-item">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" class="tech-icon">
          <span class="tech-name">Python</span>
        </div>
        <div class="tech-item">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" class="tech-icon">
          <span class="tech-name">MySQL</span>
        </div>
        <div class="tech-item">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" class="tech-icon">
          <span class="tech-name">HTML5</span>
        </div>
        <div class="tech-item">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" class="tech-icon">
          <span class="tech-name">CSS3</span>
        </div>
        <div class="tech-item">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/androidstudio/androidstudio-original.svg" alt="Android Studio" class="tech-icon">
          <span class="tech-name">Android</span>
        </div>
        <div class="tech-item">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" class="tech-icon">
          <span class="tech-name">Git</span>
        </div>
      </div>
    </div>
    
    <div class="section">
      <h2 class="section-title">Formación Académica</h2>
      <div style="margin-bottom: 1.5rem;">
        <h3 style="margin-bottom: 0.5rem; font-size: 1.2rem;">SENATI</h3>
        <p style="margin-top: 0; color: var(--light-text);">Técnico en Desarrollo de Software (En curso)</p>
        <p style="margin-top: 0.5rem;">Formación en desarrollo de aplicaciones web y móviles, bases de datos, y fundamentos de ingeniería de software.</p>
      </div>
    </div>
    
    <div class="social-links">
      <a href="https://linkedin.com/in/tu-perfil" class="social-link" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-linkedin social-icon"></i> LinkedIn
      </a>
      <a href="https://github.com/tu-usuario" class="social-link" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-github social-icon"></i> GitHub
      </a>
      <a href="mailto:tu-email@ejemplo.com" class="social-link">
        <i class="fas fa-envelope social-icon"></i> Email
      </a>
    </div>
    
    <footer>
      <p>© 2023 Estheban Pérez. Todos los derechos reservados.</p>
    </footer>
  </div>
</body>
</html>
