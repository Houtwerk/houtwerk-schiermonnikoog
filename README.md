<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
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

    .banner {
      width: 100%;
      height: 500px;
      position: relative;
      overflow: hidden;
      margin-top: 80px; 
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
  </style>
</head>
<body>

  <header>
    <div class="container">
      <div class="logo">
        <img src="images/logo_transparant.png" alt="Logo">
      </div>
      <nav>
        <a href="#home">Home</a>
        <a href="#services">Diensten</a>
        <a href="#projects">Projecten</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section class="banner">
    <div class="carousel">
      <img src="images/sfeer.JPG" class="active" alt="Banner 1">
      <img src="images/nok_detail1.1.jpg" alt="Banner 2">
      <img src="images/detail_sneeuw_NW1.1.JPG" alt="Banner 3">
      <img src="images/detail_schoor1.1.jpg" alt="Banner 4">
    </div>
  </section>

  <script>
    let currentIndex = 0;
    const images = document.querySelectorAll('.carousel img');

    function switchImage() {
      images[currentIndex].classList.remove('active');
      currentIndex = (currentIndex + 1) % images.length;
      images[currentIndex].classList.add('active');
    }

    setInterval(switchImage, 3000); // Wissel elke 3 seconden
  </script>

</body>
</html>
