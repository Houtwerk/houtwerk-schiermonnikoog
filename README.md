<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Houtwerk Schiermonnikoog - Specialist in gebintenbouw en houtskeletbouw op Schiermonnikoog.">
  <title>Houtwerk Schiermonnikoog</title>
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
  background-image: url('images/houtwerk simpel v2 klaar.pdf');
  background-size: cover; 
  background-position: center; 
  background-repeat: no-repeat; 
  height: 250px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
}

header h1 {
  background: rgba(0, 0, 0, 0.5); 
  padding: 10px;
  border-radius: 5px;
}
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      text-align: center;
      padding: 50px 20px;
      background-color: #eee;
    }
    .diensten {
      padding: 20px;
      text-align: center;
    }
    .cards {
      display: flex;
      justify-content: center;
      gap: 20px;
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
    .projecten {
      padding: 20px;
      text-align: center;
    }
    .contact {
      padding: 20px;
      text-align: center;
    }
    input, textarea {
      width: 80%;
      margin-bottom: 10px;
      padding: 10px;
    }
    button {
      padding: 10px 20px;
      background-color: #333;
      color: white;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
  <h1>Houtwerk Schiermonnikoog</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="projecten.html">Projecten</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

  <section class="hero">
    <h2>Ambachtelijke Houtbouw op Schiermonnikoog</h2>
    <p>Gespecialiseerd in gebintenbouw en houtskeletbouw.</p>
  </section>

  <section class="diensten">
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

  <section class="projecten">
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
        <img src="detail_nok1.1.jpeg" alt="Overkapping voor de tuin">
        <h3>Project 3</h3>
        <p>Overkapping voor de tuin.</p>
      </div>
    </div>
  </section>

  <section class="contact">
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
</body>
</html>
