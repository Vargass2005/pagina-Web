<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mi página web</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #e6f0ff;
      color: #333333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #4a90e2;
      color: white;
      padding: 30px 40px;
      text-align: center;
      border-bottom: 5px solid #357ABD;
    }
    section {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    .info {
      background-color: white;
      border: 2px solid #4a90e2;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 3px 3px 8px rgba(0,0,0,0.1);
    }
    .info h2 {
      color: #4a90e2;
      border-bottom: 1px solid #ccc;
      padding-bottom: 5px;
    }
    .social a, .info a {
      color: #4a90e2;
      text-decoration: none;
      font-weight: bold;
      margin-right: 10px;
    }
    .social a i, .info a i {
      margin-right: 5px;
    }
    a:hover {
      text-decoration: underline;
    }
    footer {
      background-color: #4a90e2;
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 14px;
      border-top: 5px solid #357ABD;
    }
    .icon {
      margin-right: 5px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Mi página web</h1>
    <p>Jesús Enrique Vargas Herrera</p>
  </header>

  <section>
    <div class="info">
      <h2>Sobre mí</h2>
      <p>
        <i class="fas fa-laptop-code icon"></i>
        <i class="fas fa-desktop icon"></i>
        <i class="fas fa-laptop icon"></i>
        Soy estudiante de Ingeniería Industrial en la 
        <a href="https://ucsp.edu.pe/" target="_blank">Universidad Católica San Pablo</a>. 
        Me llama la atención la optimización de procesos y me da mucha curiosidad la inteligencia artificial.
      </p>
      <p>
        <i class="fas fa-computer icon"></i>
        Actualmente estoy llevando el curso de <strong>Fundamentos de Informática</strong> con el profesor 
        <a href="https://www.linkedin.com/in/ecuadrosv/" target="_blank">Ernesto Cuadros</a>.
      </p>
    </div>

    <div class="info">
      <h2>Educación</h2>
      <p><a href="https://ucsp.edu.pe/" target="_blank">Universidad Católica San Pablo</a></p>
      <p>La carrera de Ingeniería Industrial se enfoca en diseñar, mejorar y optimizar sistemas productivos y de servicios.<br>
      Aquí se puede consultar la <a href="https://ucsp.edu.pe/vive-san-pablo/universidad/transparencia/malla-curricular-ingenieria-industrial/" target="_blank">malla curricular</a>.</p>
    </div>

    <div class="info social">
      <h2>Redes sociales</h2>
      <a href="https://www.linkedin.com/in/jesús-enrique-vargas-herrera-a87659371" target="_blank">
        <i class="fab fa-linkedin"></i>LinkedIn
      </a>
      <a href="https://www.instagram.com/varguitas___ss/" target="_blank">
        <i class="fab fa-instagram"></i>Instagram
      </a>
    </div>

    <div class="info">
      <h2>Contacto</h2>
      <p>
        <i class="fas fa-envelope icon"></i>
        <a href="mailto:jesus.vargas.herrera@ucsp.edu.pe">jesus.vargas.herrera@ucsp.edu.pe</a>
      </p>
    </div>
  </section>

  <footer>
    &copy; 2025 Jesús Enrique Vargas Herrera
  </footer>

</body>
</html>
