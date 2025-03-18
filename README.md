<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Houtwerk Schiermonnikoog - Traditioneel gebintenbouw Schiermonnikoog.">
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
      position: relative;
      height: 300px;
      overflow: hidden;
    }
    .logo {
      position: absolute;
      top: 10px;
      left: 10px;
      width: 120px;
      height: auto;
    }
    .banner {
      width: 100%;
      height: 100%;
      display: flex;
      position: absolute;
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
  </style>
</head>
<body>
  <header>
    <img src="images/logo.png" alt="Houtwerk Schiermonnikoog Logo" class="logo">
    <div class="banner">
      <img src="images/banner1.jpg" class="active" alt="Banner 1">
      <img src="images/banner2.jpg" alt="Banner 2">
      <img src="images/banner3.jpg" alt="Banner 3">
      <img src="images/banner4.jpg" alt="Banner 4">
    </div>
    <nav>
      <a href="index.html">Home</a>
      <a href="projecten.html">Projecten</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

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
