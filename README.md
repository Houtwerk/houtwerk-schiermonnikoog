
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Houtwerk Schiermonnikoog - Specialist in gebintenbouw en houtskeletbouw op Schiermonnikoog.">
  <title> </title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
  position: relative;
  height: 320px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: center;
    }
    .logo {
  background-color: transparent;
  position: absolute;
  top: -20px;
  margin: 20px auto;
  width: 350px;
  height: auto;
  z-index: 10;
}
    .banner {
  width: 100%;
  height: 100%;
  position: absolute;
  top: 150px;
    }
    .banner img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      opacity: 0;
      transition: opacity 1s ease-in-out;
    }
    .banner img.active {
      opacity: 10;
    }
    nav {
      position: absolute;
      bottom: 10px;
      width: 100%;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .section {
      padding: 20px;
      text-align: center;
    }
    .cards {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .card {
      background-color: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      width: 250px;
      text-align: center;
    }
    .card img {
      width: 100%;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <img src="images/logo_transparant.png" alt="Houtwerk Schiermonnikoog Logo" class="logo">
    <div class="banner">
      <img src="images/sfeer.JPG" class="active" alt="Banner 1">
      <img src="images/detail_nok1.1.jpeg" alt="Banner 2">
      <img src="images/detail_sneeuw_NW1.1.JPG" alt="Banner 3">
      <img src="images/detail_schoor1.1.jpg" alt="Banner 4">
    </div>
    <nav>
      <a href="index.html">Home</a>
      <a href="projecten.html">Projecten</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  
  <section class="section">
    <h2>Traditioneel gebintenbouw op Schiermonnikoog</h2>
    <p>Gespecialiseerd in gebintenbouw voor grote en kleine projecten.</p>
  </section>
  
  <section class="section">
    <h2>Onze diensten</h2>
    <div class="cards">
      <div class="card">
        <h3>Gebintenbouw</h3>
        <p>Duurzaam en authentiek handwerk.</p>
      </div>
      <div class="card">
        <h3>Houtskeletbouw</h3>
        <p>Duurzaam en op maat gemaakte constructies.</p>
      </div>
      <div class="card">
        <h3>Schuren & Overkappingen</h3>
        <p>Voor tuin, werkplaats of tuinhuis.</p>
      </div>
    </div>
  </section>
  
  <section class="section">
    <h2>Onze Projecten</h2>
    <p>Bekijk hier een selectie van afgeronde projecten.</p>
    <div class="cards">
      <div class="card">
        <img src="images/project1.jpg" alt="Gebintconstructie met houtskeletbouw">
        <h3>Project 1</h3>
        <p>Gebintconstructie met houtskeletbouw.</p>
      </div>
      <div class="card">
        <img src="images/project2.jpg" alt="Traditionele gebinten schuur">
        <h3>Project 2</h3>
        <p>Traditionele gebinten schuur.</p>
      </div>
      <div class="card">
        <img src="images/project3.jpg" alt="Overkapping voor de tuin">
        <h3>Project 3</h3>
        <p>Overkapping voor de tuin.</p>
      </div>
    </div>
  </section>
  
  <section class="section">
    <h2>Contact</h2>
    <p>Neem contact op voor een vrijblijvende offerte.</p>
    <form>
      <input type="text" placeholder="Naam" required><br>
      <input type="email" placeholder="E-mail" required><br>
      <textarea placeholder="Bericht" rows="4"></textarea><br>
      <button type="submit">Verstuur</button>
    </form>
  </section>
  
  <footer>
    <p>&copy; 2025 Houtwerk Schiermonnikoog</p>
  </footer>

  <script>
    let currentIndex = 0;
    const images = document.querySelectorAll('.banner img');
    
    function switchImage() {
      images[currentIndex].classList.remove('active');
      currentIndex = (currentIndex + 1) % images.length;
      images[currentIndex].classList.add('active');
    }
    setInterval(switchImage, 3000);
  </script>
</body>
</html>
