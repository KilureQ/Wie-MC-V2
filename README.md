<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WieśMC v2 - Minecraft RP</title>
    <style>
        /* Reset stylów */
        body, h1, h2, p, ul, li, a, input, textarea, button {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #e4e4e4;
            color: #333;
        }

        header {
            background: #2b9348;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 10px 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
            text-align: center;
        }

        #about, #features, #contact {
            margin-bottom: 20px;
            background: white;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        #features ul {
            list-style: none;
            padding: 0;
        }

        #features ul li {
            margin-bottom: 10px;
        }

        form {
            max-width: 400px;
            margin: 0 auto;
        }

        form label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        form input, form textarea, form button {
            width: 100%;
            margin-bottom: 15px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        form button {
            background: #2b9348;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 1rem;
        }

        form button:hover {
            background: #238636;
        }

        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>WieśMC v2</h1>
        <p>Najlepszy Minecraft RP!</p>
        <nav>
            <ul>
                <li><a href="#about">O serwerze</a></li>
                <li><a href="#features">Możliwości</a></li>
                <li><a href="#contact">Kontakt</a></li>
                <li><a href="#owners">Własciciele</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>O serwerze</h2>
        <p>WieśMC v2 to serwer roleplay,jest to odnowiona wersja 1 edycji WieśMC.Serwer upadł jakieś 2lata temu a my chcemy go teraz odnowić. </p>
    </section>

    <section id="features">
        <h2>Możliwości serwera</h2>
        <ul>
            <li>👤Ogromny poziom roleplay</li>
            <li>🏠 Budowa własnego domu/sklepu/restauracji/itd</li>
            <li>💬 Rozbudowany system roleplay</li>
            <li>🛒 Fajne dopracowane Skrypty</li>
            <li>🩷 Rozbudowany system serc </li>
        </ul>
    </section>

    <section id="owners">
        <h2>Własciciele Serwera!</h2>
        <ul>
            <li>Włascicielami Serwera są:</li>
            <li>KilureQ: https://www.youtube.com/@KilureQ </li>
            <li>Kubus: https://www.youtube.com/@KubusGamesYT</li>
        </ul>
    </section>
   
    <section id="contact">
        <h2>Skontaktuj się z nami</h2>
        <form>
            <label for="name">Twoje imię:</label>
            <input type="text" id="name" name="name" placeholder="Wpisz swoje imię" required>

            <label for="email">Twój e-mail:</label>
            <input type="email" id="email" name="email" placeholder="Wpisz swój adres e-mail" required>

            <label for="message">Twoja wiadomość:</label>
            <textarea id="message" name="message" rows="5" placeholder="Napisz wiadomość..." required></textarea>

            <button type="submit">Wyślij wiadomość</button>
        </form>
    </section>
      
    <footer>
        <p>&copy; 2024 WieśMC v2. Wszelkie prawa zastrzeżone.</p>
    
</footer>
</body>
</html>

