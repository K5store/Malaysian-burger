# Malaysian-burger
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Daftar Menu Malaysian Burger</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

    body {
      margin: 0;
      background: #b71c1c; /* merah gelap seperti gambar */
      font-family: 'Poppins', sans-serif;
      color: #ffd54f; /* warna emas */
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
    }

    .container {
      max-width: 800px;
      margin: 2rem auto;
      background: #7b0000;
      border-radius: 20px;
      box-shadow: 0 8px 32px rgba(0,0,0,0.5);
      padding: 2rem 3rem;
      overflow: hidden;
    }

    header {
      text-align: center;
      margin-bottom: 2rem;
    }

    header .logo {
      font-weight: 700;
      font-size: 2.5rem;
      position: relative;
      display: inline-block;
      padding: 0.5rem 2rem;
      border: 4px solid #ffd54f;
      border-radius: 12px;
      background: radial-gradient(circle, #d43f3f 30%, #7b0000 90%);
      box-shadow: 0 0 8px #ffd54f;
    }
    header .logo::before {
      content: "🍔";
      position: absolute;
      left: -2rem;
      top: 50%;
      transform: translateY(-50%);
      font-size: 2.5rem;
    }

    h2 {
      font-weight: 700;
      font-size: 1.8rem;
      margin-top: 2rem;
      margin-bottom: 1rem;
      border-bottom: 2px solid #ffd54f;
      padding-bottom: 0.3rem;
      text-align: center;
      letter-spacing: 1.5px;
    }

    .menu-section {
      margin-bottom: 3rem;
    }

    ul.menu-list {
      list-style: none;
      padding: 0;
      margin: 0 auto;
      max-width: 480px;
    }

    ul.menu-list li {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 1rem;
      font-size: 1.2rem;
      font-weight: 600;
      text-shadow: 1px 1px 2px #c87f04;
      cursor: default;
    }

    ul.menu-list li .icon {
      margin-right: 0.6rem;
      font-size: 1.3rem;
    }

    ul.menu-list li .price {
      min-width: 50px;
      text-align: right;
    }

    .food-images {
      display: flex;
      justify-content: center;
      gap: 3rem;
      margin-top: 1rem;
      flex-wrap: wrap;
    }

    .food-images img {
      border-radius: 18px;
      width: 250px;
      height: auto;
      box-shadow: 0 8px 20px rgba(0,0,0,0.6);
      object-fit: contain;
      background: #3e0000;
      border: 3px solid #ffd54f;
    }

    .footer {
      text-align: center;
      font-style: italic;
      color: #f5deb3;
      font-size: 0.9rem;
      margin-top: 2rem;
      letter-spacing: 0.7px;
    }

    /* Responsive */
    @media (max-width: 700px) {
      .container {
        padding: 1.5rem 1.5rem;
      }
      .food-images {
        flex-direction: column;
        align-items: center;
      }
      .food-images img {
        width: 90%;
        max-width: 300px;
      }
    }
  </style>
</head>
<body>
  <div class="container" role="main">
    <header>
      <div class="logo">DAFTAR MENU<br> MALAYSIAN BURGER</div>
    </header>

    <section class="menu-section" aria-labelledby="burger-ayam">
      <h2 id="burger-ayam">BURGER AYAM</h2>
      <ul class="menu-list">
        <li><span><span class="icon">🍗</span> Ayam Biasa</span> <span class="price">18K</span></li>
        <li><span><span class="icon">🍗</span> Ayam Special</span> <span class="price">20K</span></li>
        <li><span><span class="icon">🧀</span> Ayam Special Cheese</span> <span class="price">25K</span></li>
        <li><span><span class="icon">🍔</span> Double Ayam</span> <span class="price">21K</span></li>
        <li><span><span class="icon">🍔</span> Double Ayam Cheese</span> <span class="price">26K</span></li>
        <li><span><span class="icon">🍔</span> Double Ayam Special Cheese</span> <span class="price">28K</span></li>
      </ul>

      <div class="food-images" aria-label="Gambar Burger Ayam dan kentang goreng">
        <img src="https://i.imgur.com/3n6fkEo.png" alt="Burger ayam dengan kentang goreng dan minuman" />
      </div>
    </section>

    <section class="menu-section" aria-labelledby="burger-daging">
      <h2 id="burger-daging">BURGER DAGING</h2>
      <ul class="menu-list">
        <li><span><span class="icon">🥩</span> Daging Biasa</span> <span class="price">19K</span></li>
        <li><span><span class="icon">🥩</span> Daging Special</span> <span class="price">21K</span></li>
        <li><span><span class="icon">🧀</span> Daging Special Cheese</span> <span class="price">26K</span></li>
        <li><span><span class="icon">🍔</span> Double Daging</span> <span class="price">22K</span></li>
        <li><span><span class="icon">🍔</span> Double Daging Cheese</span> <span class="price">27K</span></li>
        <li><span><span class="icon">🍔</span> Double Daging Special</span> <span class="price">29K</span></li>
      </ul>

      <div class="food-images" aria-label="Gambar Burger Daging dan kentang goreng">
        <img src="https://i.imgur.com/vxxSH1f.png" alt="Burger daging dengan kentang goreng dan minuman" />
      </div>
    </section>

    <div class="footer">
      Ukuran A4: 21 cm × 29,7 cm
    </div>
  </div>
</body>
</html>
