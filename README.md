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

    <h2>🖥️ Res
