<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>উদ্যম - UDDAM Admission & Academic Care</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background: #eef2f4;
      color: #333;
      max-width: 700px;
      margin: auto;
    }
    .logo {
      display: flex;
      align-items: center;
      gap: 15px;
      margin-bottom: 20px;
    }
    .logo img {
      height: 60px;
    }
    .caption {
      font-weight: bold;
      font-size: 18px;
      margin-bottom: 20px;
    }
    .quote {
      font-style: italic;
      color: #666;
      margin-bottom: 25px;
    }
    ul {
      list-style-type: none;
      padding-left: 0;
    }
    li {
      margin: 10px 0;
    }
    a {
      text-decoration: none;
      color: #007acc;
      font-weight: bold;
    }
    a:hover {
      text-decoration: underline;
    }
    .pdf-container {
      margin-top: 30px;
      border: 1px solid #ccc;
      background: #fff;
      padding: 10px;
    }
    iframe {
      width: 100%;
      height: 600px;
      border: none;
    }
  </style>
</head>
<body>

  <div class="logo">
    <img src="logo.png" alt="Fusion Logo" />
    <div class="caption">📚 <b>Fusion PDF Library by Imran (SSC-27)</b></div>
  </div>

  <div class="quote">"Never Let Your Mind Dominate Your Conscience" — Imran</div>

  <ul>
    <li><a href="#ch1" onclick="loadPDF('SSC%20Phys%20BQ%20Ch-1.pdf')">SSC Phys BQ Ch-1</a></li> 
    <li><a href="#ch2" onclick="loadPDF('SSC_Physics_motion_Sheet-01.pdf')">SSC Phys BQ Ch-2 Motion (গতি)</a></li>
    <li><a href="#ch3" onclick="loadPDF('Work_p_E.pdf')">SSC Phys BQ Ch-4 Work, Energy & Power</a></li>
    <li><a href="#ch4" onclick="loadPDF('phys_ch7_wave_sound.pdf')">SSC Phys BQ Ch-7 Waves & Sound</a></li>
  </ul>

  <div class="pdf-container">
    <iframe id="pdf-viewer" src="" title="PDF Viewer"></iframe>
  </div>

  <script>
    function loadPDF(file) {
      document.getElementById('pdf-viewer').src = file;
    }
  </script>

</body>
</html>
