<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>Edgar Ortiz-Brizuela</title>

  <!-- Google Fonts: Inter -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  
  <!-- Font Awesome for Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

  <style>
    /* ---- Global Styles ---- */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
      background-color: rgba(211, 211, 211, 0.8);
      line-height: 1.6;
    }

    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 0 auto;
    }

    /* ---- Header & Language Toggle ---- */
    .header {
      position: fixed;
      top: 0;
      width: 100%;
      background: #fff;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      z-index: 999;
      display: flex;
      justify-content: flex-end;
      align-items: center;
      padding: 10px 20px;
    }

    .language-toggle button {
      background-color: #0073e6;
      color: white;
      border: none;
      padding: 10px 15px;
      font-size: 14px;
      cursor: pointer;
      border-radius: 5px;
      margin-left: 10px;
      transition: background 0.3s ease-in-out;
    }

    .language-toggle button:hover {
      background-color: #005bb5;
    }

    /* ---- Main Container ---- */
    .content {
      background: #fff;
      max-width: 1000px;
      margin: 80px auto 40px auto; /* 80px top margin to avoid overlap with fixed header */
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    }

    /* ---- Fade-in / Fade-out Animation ---- */
    .hidden {
      display: block;   /* For fade effect, keep block but use opacity 0 */
      opacity: 0;
      pointer-events: none; /* So it's not clickable */
      transition: opacity 0.5s ease-in-out;
    }

    .visible {
      display: block;
      opacity: 1;
      transition: opacity 0.5s ease-in-out;
    }

    h1, h2 {
      text-align: center;
    }
    hr {
      margin-top: 30px;
    }

    /* ---- Links / Contact Icons ---- */
    .contact-links a {
      display: inline-block;
      margin: 5px 10px;
      text-decoration: none;
      color: #0073e6;
      font-weight: 600;
    }
    .contact-links i {
      margin-right: 5px;
    }

    /* Example styling for sub-lists */
    ul ul {
      margin-left: 20px;
      list-style: square;
    }
  </style>
</head>
<body>

  <!-- HEADER: Language Toggle -->
  <div class="header">
    <div class="language-toggle">
      <button id="button-en">English</button>
      <button id="button-es">Español</button>
    </div>
  </div>

  <!-- ENGLISH CONTENT -->
  <div class="content visible" id="content-en">
    <img src="title.jpg" alt="Title Image">

    <h1>Welcome to my personal info website!</h1>
    <p>
      My name is <strong>Edgar Ortiz-Brizuela</strong>, and I am a Ph.D. candidate in Epidemiology at McGill University. Here, you'll find a brief overview of my background 📚, links to my work ✏️, and ways to connect with me ✉️. I am always open to collaboration!
    </p>

    <h2>📚 Background</h2>
    <p>
      I am a medical doctor, having graduated from the
      <a href="https://www.medicina.uaslp.mx/">Facultad de Medicina UASLP</a>.
      I specialized in Internal Medicine and Infectious Diseases, both at the
      <a href="http://www.incmnsz.mx/">Instituto Nacional de Ciencias Médicas y Nutrición Salvador Zubirán</a>
      in Mexico City. My passion for research led me to pursue a Master of Science in Epidemiology from the
      <a href="https://www.mcgill.ca/epi-biostat-occh/">Department of Epidemiology, Biostatistics, and Occupational Health at McGill University</a>,
      and a Master of Science in Clinical Sciences from
      <a href="http://www.facmed.unam.mx">UNAM</a>, Mexico. I am currently completing my Ph.D. in Epidemiology at McGill.
      You can have a look at a more complete resume
      <a href="https://github.com/ortizbrizuela/info/blob/main/docs/CV_EOB_2024.pdf">here</a>.
    </p>

    <h2>🖥️ Research Interests</h2>
    <ul>
      <li><strong>Infectious diseases:</strong>
        <ul>
          <li>Vaccinology</li>
          <li>Antimicrobial resistance</li>
          <li>Tuberculosis</li>
        </ul>
      </li>
      <li><strong>Epidemiology:</strong>
        <ul>
          <li>Causal inference</li>
          <li>Descriptive epidemiology</li>
          <li>Big data and AI</li>
        </ul>
      </li>
    </ul>

    <h2>✏️ Links to My Work</h2>
    <ul>
      <li><a href="https://scholar.google.com/citations?hl=es&user=rYaloZcAAAAJ">Google Scholar</a></li>
      <li><a href="https://github.com/ortizbrizuela">GitHub</a></li>
      <li><a href="https://orcid.org/my-orcid?orcid=0000-0001-7169-8459">ORCID profile</a></li>
    </ul>

    <h2>✉️ Connect with Me</h2>
    <p class="contact-links">
      <a href="mailto:edgar.ortiz-brizuela@mail.mcgill.ca" title="Email"><i class="fas fa-envelope"></i>Email</a>
      <!-- Replace with your actual Twitter/LinkedIn if you wish -->
      <a href="https://twitter.com" target="_blank" title="Twitter"><i class="fab fa-twitter"></i>Twitter</a>
      <a href="https://linkedin.com" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i>LinkedIn</a>
    </p>

    <hr>
  </div>

  <!-- SPANISH CONTENT -->
  <div class="content hidden" id="content-es">
    <img src="title.jpg" alt="Imagen de Título">

    <h1>¡Bienvenido a mi sitio personal!</h1>
    <p>
      Mi nombre es <strong>Edgar Ortiz-Brizuela</strong>, y soy candidato a doctorado (Ph.D.) en Epidemiología en la Universidad McGill. Aquí encontrarás una breve descripción de mi formación 📚, enlaces a mi trabajo ✏️ y formas de contactarme ✉️. ¡Siempre estoy abierto a colaborar!
    </p>

    <h2>📚 Formación</h2>
    <p>
      Soy médico, graduado de la
      <a href="https://www.medicina.uaslp.mx/">Facultad de Medicina UASLP</a>.
      Me especialicé en Medicina Interna y Enfermedades Infecciosas, ambas en el
      <a href="http://www.incmnsz.mx/">Instituto Nacional de Ciencias Médicas y Nutrición Salvador Zubirán</a>
      en la Ciudad de México. Mi pasión por la investigación me llevó a cursar la Maestría en Epidemiología en el
      <a href="https://www.mcgill.ca/epi-biostat-occh/">Departamento de Epidemiología, Bioestadística y Salud Ocupacional de la Universidad McGill</a>,
      y una Maestría en Ciencias Médicas en la
      <a href="http://www.facmed.unam.mx">UNAM</a>, México. Actualmente, estoy cursando mi doctorado en Epidemiología en McGill.
      Puedes ver un CV más completo
      <a href="https://github.com/ortizbrizuela/info/blob/main/docs/CV_EOB_2024.pdf">aquí</a>.
    </p>

    <h2>🖥️ Áreas de Investigación</h2>
    <ul>
      <li><strong>Enfermedades infecciosas:</strong>
        <ul>
          <li>Vacunología</li>
          <li>Resistencia antimicrobiana</li>
          <li>Tuberculosis</li>
        </ul>
      </li>
      <li><strong>Epidemiología:</strong>
        <ul>
          <li>Inferencia causal</li>
          <li>Epidemiología descriptiva</li>
          <li>Big data e IA</li>
        </ul>
      </li>
    </ul>

    <h2>✏️ Enlaces a mi Trabajo</h2>
    <ul>
      <li><a href="https://scholar.google.com/citations?hl=es&user=rYaloZcAAAAJ">Google Scholar</a></li>
      <li><a href="https://github.com/ortizbrizuela">GitHub</a></li>
      <li><a href="https://orcid.org/my-orcid?orcid=0000-0001-7169-8459">Perfil ORCID</a></li>
    </ul>

    <h2>✉️ Contáctame</h2>
    <p class="contact-links">
      <a href="mailto:edgar.ortiz-brizuela@mail.mcgill.ca" title="Correo electrónico"><i class="fas fa-envelope"></i>Correo</a>
      <a href="https://twitter.com" target="_blank" title="Twitter"><i class="fab fa-twitter"></i>Twitter</a>
      <a href="https://linkedin.com" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i>LinkedIn</a>
    </p>

    <hr>
  </div>

  <!-- JavaScript para alternar idiomas con efecto fade -->
  <script>
    const buttonEn = document.getElementById('button-en');
    const buttonEs = document.getElementById('button-es');
    const contentEn = document.getElementById('content-en');
    const contentEs = document.getElementById('content-es');

    function toggleLanguage(lang) {
      if (lang === 'en') {
        contentEn.classList.add('visible');
        contentEn.classList.remove('hidden');
        
        contentEs.classList.add('hidden');
        contentEs.classList.remove('visible');
      } else {
        contentEs.classList.add('visible');
        contentEs.classList.remove('hidden');
        
        contentEn.classList.add('hidden');
        contentEn.classList.remove('visible');
      }
    }

    buttonEn.addEventListener('click', () => toggleLanguage('en'));
    buttonEs.addEventListener('click', () => toggleLanguage('es'));
  </script>
</body>
</html>
