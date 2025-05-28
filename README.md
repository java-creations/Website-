<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Temples & Attractions in Namakkal</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f2f2f2;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #0d1a26, #1a3d5d);
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }
    header h1 {
      font-size: 2.8rem;
      margin: 0;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 2rem;
    }
    .section-title {
      font-size: 2rem;
      margin-bottom: 1rem;
      border-left: 6px solid #4a90e2;
      padding-left: 10px;
      color: #2c3e50;
    }
    .card-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
    }
    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-6px);
    }
    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }
    .card-content {
      padding: 1rem;
    }
    .card-content h2 {
      margin: 0 0 0.5rem 0;
      font-size: 1.5rem;
      color: #2d2d2d;
    }
    .card-content p {
      margin: 0;
      font-size: 1rem;
      line-height: 1.6;
      color: #555;
    }
    .author-section {
      text-align: center;
      margin-top: 3rem;
    }
    .author-section img {
      width: 200px;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }
    .author-section p {
      font-size: 1.1rem;
      margin-top: 0.8rem;
      color: #333;
      font-weight: bold;
    }
    footer {
      background: #1a1a1a;
      color: #ccc;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Famous Temples & Attractions in Namakkal</h1>
</header>

<main class="container">

  <section>
    <h2 class="section-title">Popular Temples</h2>
    <div class="card-grid">

      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Narasimhaswamy_Temple%2C_Namakkal.jpg" alt="Narasimha Swamy Temple" />
        <div class="card-content">
          <h2>Narasimha Swamy Temple</h2>
          <p>This temple is carved into a hillside and dedicated to Lord Narasimha. Known for its ancient architecture and spiritual significance, it's a must-visit in Namakkal.</p>
        </div>
      </div>

      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Anjaneyar_Temple%2C_Namakkal.jpg" alt="Anjaneyar Temple" />
        <div class="card-content">
          <h2>Anjaneyar Temple</h2>
          <p>Home to one of the tallest statues of Lord Hanuman (18 ft), this temple is open to the sky and revered by devotees seeking courage and strength.</p>
        </div>
      </div>

      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a3/Namakkal_Fort.jpg" alt="Namakkal Fort Temple" />
        <div class="card-content">
          <h2>Namakkal Fort & Ranganatha Temple</h2>
          <p>The 17th-century Namakkal Fort houses the Ranganatha Temple, known for its peaceful atmosphere and panoramic views from atop the hill.</p>
        </div>
      </div>

    </div>
  </section>

  <section style="margin-top: 3rem;">
    <h2 class="section-title">Kolli Hills (Kolli Malai)</h2>
    <div class="card-grid">
      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f0/Kolli_Hills_Mountain_View.jpg" alt="Kolli Hills" />
        <div class="card-content">
          <h2>Kolli Hills</h2>
          <p>Kolli Hills, known as Kolli Malai, is a mountain range in the Eastern Ghats, famous for its 70 hairpin bends, scenic views, and the powerful Arapaleeswarar Temple. Visitors are enchanted by waterfalls like Agaya Gangai, vibrant flora, and a tranquil escape from city life.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="author-section">
    <img src="file-F6LsU8MtTB85qCprbVvwzS" alt="Created by Javagar">
    <p>Created by Javagar</p>
  </section>

</main>

<footer>
  &copy; 2025 Namakkal Temple & Tourism Board. All rights reserved.
</footer>

</body>
</html>
