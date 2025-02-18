<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>Edgar Ortiz-Brizuela</title>
  <style>
    /* Global Styles */
    body {
      background-color: rgba(0, 0, 0, 1); /* Black background */
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
    }

    /* Floating Sidebar */
    .sidebar {
      width: 300px;
      background: rgba(17, 17, 17, 0.8); /* Semi-transparent dark background */
      color: white;
      position: fixed;
      top: 50%;
      left: 20px; /* Slight offset from the left */
      transform: translateY(-50%); /* Center vertically */
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
      text-align: center;
      border-radius: 15px; /* Rounded corners */
      box-shadow: 0px 4px 8px rgba(255, 255, 255, 0.2); /* Soft glow effect */
      transition: 0.3s ease-in-out;
    }

    /* Sidebar Image */
    .sidebar img {
      width: 120px;
      height: auto;
      border-radius: 50%;
      border: 3px solid white;
      margin-bottom: 15px;
    }

    /* Sidebar Hover Effect */
    .sidebar:hover {
      background: rgba(17, 17, 17, 1); /* Fully opaque on hover */
    }

    /* Main Content */
    .main-content {
      margin-left: 200px; /* More space to accommodate floating sidebar */
      padding: 20px;
      width: calc(100% - 320px);
    }

    .content {
      background: white;
      padding: 20px;
      max-width: 1000px;
      margin: auto;
      border-radius: 10px;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    }

    /* Language Toggle Buttons */
    .language-toggle {
      text-align: center;
      margin-bottom: 20px;
    }

    .language-toggle button {
      background-color: #0073e6;
      color: white;
      border: none;
      padding: 10px 15px;
      font-size: 14px;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s ease-in-out;
      margin-left: 10px;
    }

    .language-toggle button:hover {
      background-color: #005bb5;
    }

    /* Hide one language version by default */
    .hidden {
      display: none;
    }

    /* Responsive Design */
    @media (max-width: 800px) {
      .sidebar {
        width: 80px;
        left: 10px;
        padding: 10px;
      }

      .sidebar img {
        width: 60px;
      }

      .sidebar h2, .sidebar p {
        display: none; /* Hide text on smaller screens */
      }

      .main-content {
        margin-left: 100px;
        width: calc(100% - 120px);
      }
    }
  </style>
</head>
<body>

  <!-- Floating Sidebar -->
  <div class="sidebar">
    <img src="profile.jpg" alt="Edgar Ortiz-Brizuela">
    <h2>Edgar Ortiz-Brizuela</h2>
  </div>

  <!-- Main Content -->
  <div class="main-content">

    <!-- Language Toggle Buttons -->
    <div class="language-toggle">
      <button id="button-en">English</button>
      <button id="button-es">Español</button>
    </div>

    <!-- English Version -->
    <div class="content" id="content-en">
      <img src="title.jpg" width="1000" alt="Title Image"/>

      <h1>Welcome to my personal info website!</h1>

      <p>My name is <strong>Edgar Ortiz-Brizuela</strong>, and I am a Ph.D. candidate in Epidemiology at McGill University. Here, you'll find a brief overview of my background 📚, links to my work ✏️, and ways to connect with me ✉️. I am always open to collaboration!</p>

      <h2>📚 Background</h2>
      <p>I am a medical doctor, having graduated from the <a href="https://www.medicina.uaslp.mx/">Facultad de Medicina UASLP</a>. I specialized in Internal Medicine and Infectious Diseases, both at the <a href="http://www.incmnsz.mx/">Instituto Nacional de Ciencias Médicas y Nutrición Salvador Zubirán</a> in Mexico City. My passion for research led me to pursue a Master of Science in Epidemiology from the <a href="https://www.mcgill.ca/epi-biostat-occh/">Department of Epidemiology, Biostatistics, and Occupational Health at McGill University</a>, and a Master of Science in Clinical Sciences from <a href="http://www.facmed.unam.mx">UNAM</a>, Mexico. I am currently completing my Ph.D. in Epidemiology at McGill. You can have a look at a more complete resume <a href="https://github.com/ortizbrizuela/info/blob/main/docs/CV_EOB_2024.pdf">here</a>.</p>

      <h2>✏️ Links to My Work</h2>
      <ul>
        <li><a href="https://scholar.google.com/citations?hl=es&user=rYaloZcAAAAJ">Google Scholar</a></li>
        <li><a href="https://github.com/ortizbrizuela">GitHub</a></li>
        <li><a href="https://orcid.org/0000-0001-7169-8459">ORCID profile</a></li>
      </ul>
    </div>

    <!-- Spanish Version -->
    <div class="content hidden" id="content-es">
      <img src="title.jpg" width="1000" alt="Imagen de Título"/>

    <h1>¡Bienvenido a mi sitio personal de información!</h1>

    <p>Mi nombre es <strong>Edgar Ortiz-Brizuela</strong>, y soy candidato a doctorado (Ph.D.) en Epidemiología en la Universidad McGill. Aquí encontrarás una breve descripción de mi formación 📚, enlaces a mi trabajo ✏️ y formas de contactarme ✉️. ¡Siempre estoy abierto a colaborar!</p>

    <h2>📚 Formación</h2>
    <p>Soy médico, graduado de la <a href="https://www.medicina.uaslp.mx/">Facultad de Medicina UASLP</a>. Me especialicé en Medicina Interna y Enfermedades Infecciosas, ambas en el <a href="http://www.incmnsz.mx/">Instituto Nacional de Ciencias Médicas y Nutrición Salvador Zubirán</a> en Ciudad de México. Mi pasión por la investigación me llevó a cursar la Maestría en Epidemiología en el <a href="https://www.mcgill.ca/epi-biostat-occh/">Departamento de Epidemiología, Bioestadística y Salud Ocupacional de la Universidad McGill</a>, y una Maestría en Ciencias Médicas en la <a href="http://www.facmed.unam.mx">UNAM</a>, México. Actualmente, estoy cursando mi doctorado en Epidemiología en McGill. Puedes ver un CV más completo <a href="https://github.com/ortizbrizuela/info/blob/main/docs/CV_EOB_2024.pdf">aquí</a>.</p>

    <h2>🖥️ Áreas de Investigación</h2>
    <ul>
      <li><strong>Enfermedades infecciosas:</strong>
        <ul>
          <li>Vacunología.</li>
          <li>Resistencia antimicrobiana.</li>
          <li>Tuberculosis.</li>
        </ul>
      </li>
      <li><strong>Epidemiología:</strong>
        <ul>
          <li>Inferencia causal.</li>
          <li>Epidemiología descriptiva.</li>
          <li>Big data e Inteligencia Artificial.</li>
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
    <p>No dudes en <a href="mailto:edgar.ortiz-brizuela@mail.mcgill.ca">ponerte en contacto</a> para colaboraciones.</p>

    <hr>
  </div>

  <script>
    const buttonEn = document.getElementById('button-en');
    const buttonEs = document.getElementById('button-es');
    const contentEn = document.getElementById('content-en');
    const contentEs = document.getElementById('content-es');

    buttonEn.addEventListener('click', () => {
      contentEn.classList.remove('hidden');
      contentEs.classList.add('hidden');
    });

    buttonEs.addEventListener('click', () => {
      contentEs.classList.remove('hidden');
      contentEn.classList.add('hidden');
    });
  </script>

</body>
</html>
