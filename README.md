
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>World Wonders</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fafafa;
      margin: 0;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 1rem 0;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    nav ul {
      list-style: none;
      padding: 0.5rem 0 1rem;
      margin: 0;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1rem;
    }

    nav ul li a {
      color: #ecf0f1;
      text-decoration: none;
      font-weight: bold;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      transition: background-color 0.3s ease;
    }

    nav ul li a:hover {
      background-color: #34495e;
    }

    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    .wonder {
      background-color: white;
      margin-bottom: 2rem;
      padding: 1rem 1.5rem;
      border-radius: 6px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .wonder h2 {
      margin-top: 0;
      color: #2c3e50;
    }

    .wonder img {
      max-width: 100%;
      height: auto;
      border-radius: 4px;
      margin: 0.5rem 0 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    }

    footer {
      text-align: center;
      padding: 1rem 0;
      background-color: #2c3e50;
      color: white;
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>The Seven Wonders of the World</h1>
    <nav>
      <ul>
        <li><a href="#great-wall">Great Wall of China</a></li>
        <li><a href="#petra">Petra</a></li>
        <li><a href="#christ-redeemer">Christ the Redeemer</a></li>
        <li><a href="#machu-picchu">Machu Picchu</a></li>
        <li><a href="#chichen-itza">Chichen Itza</a></li>
        <li><a href="#roman-colosseum">Roman Colosseum</a></li>
        <li><a href="#taj-mahal">Taj Mahal</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="great-wall" class="wonder">
      <h2>Great Wall of China</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/GreatWall_2004_Summer_4.JPG/640px-GreatWall_2004_Summer_4.JPG" alt="Great Wall of China" />
      <p>The Great Wall of China is a series of fortifications built across the historical northern borders of China to protect against invasions.</p>
    </section>

    <section id="petra" class="wonder">
      <h2>Petra</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Petra_Jordan_BW_21-09-2007_img3.jpg/640px-Petra_Jordan_BW_21-09-2007_img3.jpg" alt="Petra" />
      <p>Petra is a historical and archaeological city famous for its rock-cut architecture and water conduit system, located in southern Jordan.</p>
    </section>

    <section id="christ-redeemer" class="wonder">
      <h2>Christ the Redeemer</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/Cristo_Redentor_-_Rio_de_Janeiro%2C_Brasil.jpg/640px-Cristo_Redentor_-_Rio_de_Janeiro%2C_Brasil.jpg" alt="Christ the Redeemer" />
      <p>Christ the Redeemer is an iconic statue of Jesus Christ in Rio de Janeiro, Brazil, symbolizing peace and welcoming visitors with open arms.</p>
    </section>

    <section id="machu-picchu" class="wonder">
      <h2>Machu Picchu</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Machu_Picchu%2C_Peru.jpg/640px-Machu_Picchu%2C_Peru.jpg" alt="Machu Picchu" />
      <p>Machu Picchu is an ancient Incan city set high in the Andes Mountains of Peru, known for its sophisticated dry-stone construction.</p>
    </section>

    <section id="chichen-itza" class="wonder">
      <h2>Chichen Itza</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Chichen_Itza_3.jpg/640px-Chichen_Itza_3.jpg" alt="Chichen Itza" />
      <p>Chichen Itza is a large pre-Columbian archaeological site built by the Maya civilization in Mexico's Yucatán Peninsula.</p>
    </section>

    <section id="roman-colosseum" class="wonder">
      <h2>Roman Colosseum</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Colosseo_2020.jpg/640px-Colosseo_2020.jpg" alt="Roman Colosseum" />
      <p>The Roman Colosseum is an ancient amphitheater in Rome, Italy, famous for gladiatorial contests and public spectacles.</p>
    </section>

    <section id="taj-mahal" class="wonder">
      <h2>Taj Mahal</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Taj-Mahal.jpg/640px-Taj-Mahal.jpg" alt="Taj Mahal" />
      <p>The Taj Mahal is a white marble mausoleum in India, built by Emperor Shah Jahan in memory of his wife Mumtaz Mahal.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 World Wonders</p>
  </footer>
</body>
</html>
