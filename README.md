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
  background-color: #f4f4f4;
}
    header {
  background-color: white;
  padding: 15px 0;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  z-index: 100;
}
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.logo img {
  width: 150px;
}

nav a {
  color: #333;
  margin-left: 20px;
  text-decoration: none;
  font-size: 18px;
}

nav a:hover {
  text-decoration: underline;
}

/* Banner met doorlopende afbeeldingen */
.banner {
  width: 100%;
  height: 500px; /* Hoogte van de banner */
  position: relative;
  overflow: hidden;
  margin-top: 80px; /* Voorkomt overlap met de vaste header */
}

.carousel img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
  opacity: 0;
  transition: opacity 1s ease-in-out;
}

.carousel img.active {
  opacity: 1;
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

<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Houtwerk Schiermonnikoog</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="container">
      <div class="logo">
        img src="images/logo_transparant.png" alt="Houtwerk Schiermonnikoog Logo" class="logo">
      </div>
      <nav>
    <a href="#productcategorieen">Productcategorieën</a>
    <a href="#projecten">Uitgelichte Projecten</a>
    <a href="#werkwijze">Werkwijze</a>
    <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

<section class="banner">
  <div class="carousel">
      <img src="images/sfeer.JPG" class="active" alt="Banner 1">
      <img src="images/detail_nok1.1.jpeg" alt="Banner 2">
      <img src="images/detail_sneeuw_NW1.1.JPG" alt="Banner 3">
      <img src="images/detail_schoor1.1.jpg" alt="Banner 4"> 
  </div>
</section>
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
