<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ChronoClassics Watches</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Montserrat', sans-serif;
      background: #f2f2f2;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(to right, #0f0f0f, #1a1a1a);
      color: #fff;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.3);
    }
    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.1rem;
      color: #ccc;
    }
    nav {
      background: #1c1c1c;
      display: flex;
      justify-content: center;
      padding: 15px 0;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 20px;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #f0c330;
    }
    .page {
      display: none;
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .active {
      display: block;
    }
    .product {
      background: #fff;
      padding: 20px;
      margin: 20px 0;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      display: flex;
      gap: 20px;
      align-items: center;
      flex-wrap: wrap;
    }
    .product img {
      width: 100%;
      max-width: 300px;
      border-radius: 4px;
    }
    .product-details {
      flex: 1;
    }
    .product h3 {
      margin-bottom: 10px;
    }
    .buy-button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #111;
      color: #fff;
      text-decoration: none;
      border-radius: 4px;
      transition: background 0.3s;
    }
    .buy-button:hover {
      background-color: #444;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 60px;
    }
    form input, form textarea, form button {
      width: 100%;
      padding: 10px;
      margin: 8px 0 20px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-family: inherit;
    }
    form button {
      background: #111;
      color: white;
      border: none;
      cursor: pointer;
      transition: background 0.3s;
    }
    form button:hover {
      background: #333;
    }
    h2 {
      margin-bottom: 20px;
      font-size: 2rem;
      border-bottom: 2px solid #ccc;
      padding-bottom: 10px;
    }
    img.logo {
      max-width: 280px;
      display: block;
      margin: 20px auto;
    }
  </style>
</head>
<body>
  <header>
    <h1>ChronoClassics</h1>
    <p>Timeless Elegance & Sporty Performance</p>
  </header>  <nav>
    <a href="#" onclick="showPage('home')">Home</a>
    <a href="#" onclick="showPage('formal')">Formal</a>
    <a href="#" onclick="showPage('sporty')">Sporty</a>
    <a href="#" onclick="showPage('contact')">Contact</a>
    <a href="#" onclick="showPage('feedback')">Feedback</a>
  </nav>  <div id="home" class="page active">
    <h2>Welcome to ChronoClassics</h2>
    <p>Where craftsmanship meets innovation. Explore a wide range of premium watches for every lifestyle.</p>
    <img class="logo" src="https://images.unsplash.com/photo-1617048669648-0b3c0f9e54fb?auto=format&fit=crop&w=512&q=80" alt="ChronoClassics Logo">
  </div>  <div id="formal" class="page">
    <h2>Formal Watches</h2>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&w=400&q=80" alt="Regal Black">
      <div class="product-details">
        <h3>Regal Black</h3>
        <p>Elegant black dial with leather strap. Perfect for executive style. ₹15,000</p>
        <a href="#" class="buy-button">Buy Now</a>
      </div>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1534422298391-e4f8c172dddb?auto=format&fit=crop&w=400&q=80" alt="Classic Silver">
      <div class="product-details">
        <h3>Classic Silver</h3>
        <p>Minimalist silver-tone timepiece with timeless appeal. ₹13,500</p>
        <a href="#" class="buy-button">Buy Now</a>
      </div>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1585386959984-a4155223f7e1?auto=format&fit=crop&w=400&q=80" alt="Executive Gold">
      <div class="product-details">
        <h3>Executive Gold</h3>
        <p>Premium gold-plated design for formal occasions. ₹22,000</p>
        <a href="#" class="buy-button">Buy Now</a>
      </div>
    </div>
  </div>  <div id="sporty" class="page">
    <h2>Sporty Watches</h2>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1622675363311-59b14ff5507e?auto=format&fit=crop&w=400&q=80" alt="Trailblazer X">
      <div class="product-details">
        <h3>Trailblazer X</h3>
        <p>Durable, waterproof, and made for adventure. ₹9,999</p>
        <a href="#" class="buy-button">Buy Now</a>
      </div>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1585776245991-8ec20903f65a?auto=format&fit=crop&w=400&q=80" alt="Speed Runner">
      <div class="product-details">
        <h3>Speed Runner</h3>
        <p>Digital-analog hybrid with chronograph features. ₹11,500</p>
        <a href="#" class="buy-button">Buy Now</a>
      </div>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1599940824395-322c6b021f46?auto=format&fit=crop&w=400&q=80" alt="Adventura Pro">
      <div class="product-details">
        <h3>Adventura Pro</h3>
        <p>Built-in GPS, shockproof, and rugged. ₹13,800</p>
        <a href="#" class="buy-button">Buy Now</a>
      </div>
    </div>
  </div>  <div id="contact" class="page">
    <h2>Contact Us</h2>
    <p>Email: <strong>support@chronoclassics.com</strong></p>
    <p>Phone 1: <strong>+91-9876543210</strong></p>
    <p>Phone 2: <strong>+91-8765432198</strong></p>
    <p>Address: <strong>5th Floor, Watch Tower Plaza, Delhi, India</strong></p>
    <p>Instagram: <strong>@ChronoClassics</strong></p>
  </div>  <div id="feedback" class="page">
    <h2>Leave Feedback</h2>
    <form>
      <label for="name">Your Name:</label>
      <input type="text" id="name" name="name" required /><label for="email">Email:</label>
  <input type="email" id="email" name="email" required />

  <label for="message">Message:</label>
  <textarea id="message" name="message" rows="5" required></textarea>

  <button type="submit">Submit</button>
</form>

  </div>  <footer>
    &copy; 2025 ChronoClassics. All rights reserved.
  </footer>  <script>
    function showPage(pageId) {
      const pages = document.querySelectorAll('.page');
      pages.forEach(page => page.classList.remove('active'));
      document.getElementById(pageId).classList.add('active');
    }
  </script></body>
</html>