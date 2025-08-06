<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>OurVerse</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      background-color: #fff7f3;
      color: #5a3e36;
      margin: 0;
      padding: 0 1em;
      line-height: 1.6;
    }
    header, footer {
      text-align: center;
      padding: 1em 0;
    }
    h1, h2 {
      font-family: 'Palatino Linotype', 'Book Antiqua', Palatino, serif;
    }
    section {
      margin: 2em 0;
    }
    .poem-toggle {
      background-color: #fff0eb;
      padding: 1em;
      border-radius: 10px;
      margin-bottom: 1em;
      cursor: pointer;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .poem-content {
      display: none;
      margin-top: 0.5em;
    }
    iframe {
      width: 100%;
      max-width: 560px;
      height: 315px;
      margin: 1em auto;
      display: block;
    }
    video {
      width: 100%;
      max-width: 600px;
      margin: 2em auto;
      display: block;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.2);
    }
    .love-message {
      font-size: 1.5em;
      text-align: center;
      margin: 3em 0 1em;
      font-weight: bold;
    }
  </style>
</head>
<body>

<header>
  <h1>OurVerse 💌</h1>
  <p>Bienvenid@ a este rinconcito creado para nosotros.</p>
</header>

<section>
  <h2>Dedicatoria ✨</h2>
  <p>
    Este espacio guarda palabras, recuerdos y momentos que nacieron de algo hermoso.  
    Porque desde que llegaste, entendí que el amor bonito sí existe.  
    Y aunque no lo buscaba, tu cariño me curó el alma sin quererlo.
  </p>
</section>

<section>
  <h2>Poemas Privados 📖</h2>

  <div class="poem-toggle" onclick="togglePoem(this)">
    Poema 1: Amor Silencioso
    <div class="poem-content">
      <p>
        Éramos solo amigos, o eso creíamos...<br>
        Pero mi alma ya te hablaba bajito,<br>
        con miedo, pero esperanza,<br>
        de ser algo más que un suspiro compartido.
      </p>
    </div>
  </div>

  <div class="poem-toggle" onclick="togglePoem(this)">
    Poema 2: Curaste mi Alma
    <div class="poem-content">
      <p>
        Llegaste sin prometer, sin exigir,<br>
        y con tu forma suave de mirar<br>
        hiciste que mi alma dejara de doler.<br>
        Amar ya no asusta... si es contigo.
      </p>
    </div>
  </div>

  <div class="poem-toggle" onclick="togglePoem(this)">
    Poema 3: Nuestro Tiempo
    <div class="poem-content">
      <p>
        Desde aquel 13 de marzo, algo cambió.<br>
        Cada momento, cada apodo, cada mirada<br>
        fue construyendo un nosotros que no sabía que quería...<br>
        hasta que no pude imaginar sin ti.
      </p>
    </div>
  </div>

  <div class="poem-toggle" onclick="togglePoem(this)">
    Poema 4: Y te amé
    <div class="poem-content">
      <p>
        El 28 de junio no fue solo un día más.<br>
        Fue el día que sin miedo, sin reservas<br>
        mi corazón te dijo “te amo”...<br>
        Y lo sigue gritando, sin parar.
      </p>
    </div>
  </div>
</section>

<section>
  <h2>Nuestras Canciones 🎶</h2>
  <p>Estas canciones me hicieron pensarte, soñarte y amarte... desde el inicio.</p>

  <ul>
    <li><a href="https://youtu.be/7h2ryr_uUEs?si=ICmjanI4Bx-yafb_" target="_blank">Canción 1</a></li>
    <li><a href="https://youtu.be/e1mOmdykmwI?si=UzzTqc0RCqvH20j8" target="_blank">Canción 2</a></li>
    <li><a href="https://youtu.be/Mcj75l2gJcY?si=yuC9-3wxWLRLQnM8" target="_blank">Canción 3</a></li>
    <li><a href="https://youtu.be/h0p8yTqj8i4?si=uzRrULSh-YbBcAl2" target="_blank">Canción 4</a></li>
    <li><a href="https://youtu.be/ntdwWKaGaPQ?si=v-nlZEfH3XW8sd0P" target="_blank">Canción 5</a></li>
  </ul>
</section>

<section>
  <h2>Nuestro viaje en fotos... porque cada instante contigo es un tesoro 🎥</h2>
  <video controls>
    <source Video Feliz Cumpleaños Collage Moderno Pastel_20250806_125609_000" />
    Tu navegador no puede reproducir este video.
  </video>
</section>

<div class="love-message">
  TE AMO CON TODA MI ALMA ❤️
</div>

<footer>
  <p>Creado con amor por Keith 💕</p>
</footer>

<script>
  function togglePoem(element) {
    const content = element.querySelector('.poem-content');
    content.style.display = content.style.display === 'block' ? 'none' : 'block';
  }
</script>

</body>
</html>
