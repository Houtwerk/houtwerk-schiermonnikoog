
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Houtwerk Schiermonnikoog - Traditioneel gebintenbouw">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    header {
      position: relative;
      height: 300px;
      background: rgba(0, 0, 0, 0.5);
      background-image: url('images/banner.jpg');
      background-size: cover;
      background-position: center;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .logo {
      position: absolute;
      top: 20px;
      left: 20px;
      width: 150px;
    }

    nav a {
      color: white;
      margin: 0 20px;
      text-decoration: none;
      font-size: 18px;
    }

    .foto-collage {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
    }

    .image-gallery img {
      width: 300px;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }

    #houtwerk {
      text-align: center;
      padding: 50px;
      background-color: #fff;
    }

    #houtwerk h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    .text-blok {
      background-color: #f9f9f9;
      padding: 20px;
      border-radius: 8px;
      max-width: 800px;
      margin: 0 auto;
    }

    footer {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }

    footer form {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    footer input, footer textarea, footer button {
      margin: 10px;
      padding: 10px;
      width: 80%;
      max-width: 400px;
      font-size: 16px;
    }

    footer button {
      background-color: #444;
      color: white;
      border: none;
      cursor: pointer;
    }

    footer button:hover {
      background-color: #666;
    }
  </style>
</head>
<body>
  <!-- Header met semi-transparante banner -->
  <header>
    <div class="banner">
      <img src="images/logo_transparant.png" alt="Houtwerk Schiermonnikoog Logo" class="logo">
      <nav>
        <a href="#productcategorieen">Productcategorieën</a>
        <a href="#projecten">Uitgelichte Projecten</a>
        <a href="#werkwijze">Werkwijze</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Foto Collage -->
  <section class="foto-collage">
    <div class="image-gallery">
      <img src="images/sfeer.JPG.jpg" alt="Project 1">
      <img src="images/nok_detail1.1.jpg" alt="Project 2">
      <img src="images/detail_sneeuw_NW1.1.JPG" alt="Project 3">
      <img src="images/detail_schoor1.1.jpg" alt="Project 4">
    </div>
  </section>

  <!-- Sectie over Houtwerk -->
  <section id="houtwerk">
    <h2>Traditioneel Gebintenbouw</h2>
    <div class="text-blok">
      <p>Welkom bij Houtwerk Schiermonnikoog, gespecialiseerd in traditioneel gebintenbouw. Wij bieden duurzame, ambachtelijke constructies.</p>
    </div>
  </section>

  <!-- Footer met Contact en Offerte aanvraag -->
  <footer>
    <div id="contact">
      <h3>Contact</h3>
      <p>Wil je een vrijblijvende offerte aanvragen? Neem contact met ons op:</p>
      <form action="mailto:info@houtwerkschiermonnikoog.nl" method="post" enctype="text/plain">
        <input type="text" name="naam" placeholder="Naam" required><br>
        <input type="email" name="email" placeholder="E-mail" required><br>
        <textarea name="bericht" rows="4" placeholder="Bericht" required></textarea><br>
        <button type="submit">Offerte Aanvragen</button>
      </form>
    </div>
    <p>&copy; 2025 Houtwerk Schiermonnikoog</p>
  </footer>
</body>
</html>

