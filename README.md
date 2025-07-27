## Hi there 👋

<!--
**EddyScentz/EddyScentz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>EDDYS SCENTZ</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #000;
      color: #fff;
    }

    header {
      background: url('https://images.unsplash.com/photo-1556228453-bcd0b2118a02?auto=format&fit=crop&w=1600&q=80') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    header h1 {
      font-size: 48px;
      font-weight: 800;
      letter-spacing: 3px;
      margin: 0;
    }

    header p {
      font-size: 18px;
      margin: 20px 0;
    }

    .shop-btn {
      background: #fff;
      color: #000;
      padding: 12px 30px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 4px;
    }

    section {
      padding: 60px 20px;
      background-color: #111;
    }

    .products {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
    }

    .card {
      background: #1a1a1a;
      border-radius: 8px;
      padding: 20px;
      width: 280px;
    }

    .card img {
      width: 100%;
      border-radius: 6px;
    }

    .card h3 {
      margin: 15px 0 5px;
    }

    .card p {
      color: #ccc;
      font-size: 14px;
    }

    select, button {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: none;
      border-radius: 4px;
      font-weight: bold;
    }

    button {
      background-color: #fff;
      color: #000;
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 40px 20px;
      background-color: #000;
      color: #888;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>EDDYS SCENTZ</h1>
    <p>Luxury Cologne Samples — 1, 3, 5, 10, 30 mL</p>
    <a href="#shop" class="shop-btn">SHOP NOW</a>
  </header>

  <section id="shop">
    <h2 style="text-align:center; margin-bottom: 40px;">Featured Fragrance</h2>
    <div class="products">

      <div class="card">
        <img src="https://via.placeholder.com/280x180?text=Imagination+by+LV" alt="Imagination by Louis Vuitton">
        <h3>Imagination</h3>
        <p>by Louis Vuitton</p>
        <select>
          <option>1ml - $4.99</option>
          <option>3ml - $14.50</option>
          <option disabled>5ml - Coming Soon</option>
          <option disabled>10ml - Coming Soon</option>
          <option disabled>30ml - Coming Soon</option>
        </select>
        <button>Add to Cart</button>
      </div>

    </div>
  </section>

  <footer>
    &copy; 2025 EDDYS SCENTZ. All rights reserved.
  </footer>

</body>
</html>
