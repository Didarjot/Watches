<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ChronoClassics Watches</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      background: #f9f9f9;
      margin: 0;
      color: #333;
    }
    header {
      background: #111;
      color: white;
      text-align: center;
      padding: 40px 20px;
    }
    header img.logo {
      max-width: 200px;
      margin-top: 20px;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #222;
      padding: 15px;
      position: sticky;
      top: 0;
      z-index: 999;
    }
    nav a {
      color: white;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #f0c330;
    }
    .page {
      display: none;
      padding: 30px;
      max-width: 1100px;
      margin: auto;
    }
    .active {
      display: block;
    }
    .product {
      display: flex;
      background: white;
      margin: 20px 0;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .product img {
      max-width: 250px;
      margin-right: 20px;
      border-radius: 5px;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>ChronoClassics</h1>
    <p>Timeless Elegance & Sporty Performance</p>
    <img src="logo.png" alt="ChronoClassics Logo" class="logo">
  </header>

  <nav>
    <a href="#" onclick="showPage('home')">Home</a>
    <a href="#" onclick="showPage('formal')">Formal</a>
    <a href="#" onclick="showPage('sporty')">Sporty</a>
    <a href="#" onclick="showPage('contact')">Contact</a>
  </nav>

  <div id="home" class="page active">
    <h2>Welcome to ChronoClassics</h2>
    <p>Explore premium watches for the refined and the bold.</p>
  </div>

  <div id="formal" class="page">
    <h2>Formal Watches</h2>
    <div class="product">
      <img src="formal1.jpg" alt="Formal Watch 1">
      <div><h3>Regal Black</h3><p>Elegant black leather. ₹15,000</p></div>
    </div>
    <div class="product">
      <img src="formal2.jpg" alt="Formal Watch 2">
      <div><h3>Classic Silver</h3><p>Sleek silver stainless steel. ₹13,500</p></div>
    </div>
  </div>

  <div id="sporty" class="page">
    <h2>Sporty Watches</h2>
    <div class="product">
      <img src="sport1.jpg" alt="Sporty Watch 1">
      <div><h3>Trailblazer X</h3><p>Rugged adventure-ready. ₹9,999</p></div>
    </div>
    <div class="product">
      <img src="sport2.jpg" alt="Sporty Watch 2">
      <div><h3>Speed Runner</h3><p>Lightweight digital sports watch. ₹11,500</p></div>
    </div>
  </div>

  <div id="contact" class="page">
    <h2>Contact Us</h2>
    <p>Email: support@chronoclassics.com</p>
    <p>Phone: +91-9876543210</p>
  </div>

  <footer>&copy; 2025 ChronoClassics. All rights reserved.</footer>

  <script>
    function showPage(pageId) {
      const pages = document.querySelectorAll('.page');
      pages.forEach(p => p.classList.remove('active'));
      document.getElementById(pageId).classList.add('active');
    }
  </script>
</body>
</html>