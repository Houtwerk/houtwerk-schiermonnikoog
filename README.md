
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Houtwerk Schiermonnikoog</title>
    <style>
        /* Algemene instellingen */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        /* Header */
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header .logo img {
            width: 150px;
        }

        /* Navigatie */
        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        /* Hoofdcontent */
        main {
            padding: 20px;
        }

        /* Sectie Intro */
        #intro h1 {
            color: #333;
        }

        #intro p {
            font-size: 1.2em;
        }

        /* Diensten sectie */
        #diensten h2 {
            color: #444;
        }

        #diensten ul {
            list-style-type: square;
            margin-left: 20px;
        }

        #diensten ul li {
            margin-bottom: 10px;
        }

        /* Contact sectie */
        #contact form {
            display: flex;
            flex-direction: column;
        }

        #contact label {
            margin-top: 10px;
        }

        #contact input, #contact textarea {
            padding: 10px;
            margin: 5px 0 15px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        #contact button {
            padding: 10px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
        }

        #contact button:hover {
            background-color: #555;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">
            <img src="logo.png" alt="Houtwerk Schiermonnikoog Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Over ons</a></li>
                <li><a href="#">Diensten</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="intro">
            <h1>Welkom bij Houtwerk Schiermonnikoog</h1>
            <p>Wij bieden vakmanschap in houtbewerking en restauratie op Schiermonnikoog.</p>
        </section>

        <section id="diensten">
            <h2>Onze Diensten</h2>
            <ul>
                <li>Houtbewerking op maat</li>
                <li>Restauratie van houten gebouwen</li>
                <li>Meubelmakerij</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Neem contact met ons op via het onderstaande formulier of bel ons voor meer informatie.</p>
            <form>
                <label for="naam">Naam:</label>
                <input type="text" id="naam" name="naam" required>

                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>

                <label for="bericht">Bericht:</label>
                <textarea id="bericht" name="bericht" required></textarea>

                <button type="submit">Verstuur</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Houtwerk Schiermonnikoog | Alle rechten voorbehouden</p>
    </footer>

</body>
</html>
