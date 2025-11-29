DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AHMUX – Perfumes & Watches</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #222;
    }
    header {
      background: black;
      color: white;
      padding: 30px;
      text-align: center;
      font-size: 32px;
      letter-spacing: 3px;
    }
    nav {
      background: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-size: 18px;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1523292562811-6899bca127d9?auto=format&fit=crop&w=1500&q=80') center/cover;
      height: 350px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 40px;
      text-shadow: 2px 2px 10px #000;
    }
    .section {
      padding: 40px;
      text-align: center;
      background: white;
      margin: 20px;
      border-radius: 10px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.1);
    }
    footer {
      background: black;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>AHMUX</header>
  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero" id="home">Premium Perfumes & Luxury Watches</div>

  <div class="section" id="products">
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">
        <h3>Luxury Perfumes</h3>
        <p>Long-lasting premium fragrances.</p>
      </div>
      <div class="product">
        <h3>Stylish Watches</h3>
        <p>Modern timepieces with elegant designs.</p>
      </div>
    </div>
  </div>

  <div class="section" id="contact">
    <h2>Contact Us</h2>
    <p>WhatsApp: <strong>03412189262</strong></p>
  </div>

  <footer>
    © 2025 AHMUX – All Rights Reserved
  </footer>
</body>
</html>
# ahmux-website
