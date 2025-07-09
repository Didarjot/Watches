<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ChronoClassics Watches</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f5f5f5; }
    header { background: #000; color: white; padding: 20px; text-align: center; }
    nav { background: #333; padding: 10px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    .page { display: none; padding: 20px; }
    .active { display: block; }
    .product { background: white; padding: 15px; margin: 10px; border-radius: 5px; }
    footer { background: #000; color: white; text-align: center; padding: 10px; position: fixed; bottom: 0; width: 100%; }
    img { width: 100%; max-width: 300px; height: auto; }
  </style>
</head>
<body>
  <header>
    <h1>ChronoClassics</h1>
    <p>Timeless Elegance & Sporty Performance</p>
  </header>  <nav>
    <a href="#" onclick="showPage('home')">Home</a>
    <a href="#" onclick="showPage('formal')">Formal Watches</a>
    <a href="#" onclick="showPage('sporty')">Sporty Watches</a>
    <a href="#" onclick="showPage('contact')">Contact</a>
    <a href="#" onclick="showPage('feedback')">Feedback</a>
  </nav>  <div id="home" class="page active">
    <h2>Welcome to ChronoClassics</h2>
    <p>Discover our exclusive range of formal and sporty watches crafted with precision and style.</p>
    <img src="https://via.placeholder.com/300x200?text=ChronoClassics+Logo" alt="ChronoClassics Logo">
  </div>  <div id="formal" class="page">
    <h2>Formal Watches Collection</h2>
    <div class="product">
      <h3>Regal Black</h3>
      <img src="https://via.placeholder.com/300x200?text=Regal+Black" alt="Regal Black">
      <p>Elegant black dial with leather strap. ₹15,000</p>
    </div>
    <div class="product">
      <h3>Classic Silver</h3>
      <img src="https://via.placeholder.com/300x200?text=Classic+Silver" alt="Classic Silver">
      <p>Minimalist silver-tone timepiece. ₹13,500</p>
    </div>
    <div class="product">
      <h3>Executive Gold</h3>
      <img src="https://via.placeholder.com/300x200?text=Executive+Gold" alt="Executive Gold">
      <p>Gold-plated finish with premium detailing. ₹22,000</p>
    </div>
  </div>  <div id="sporty" class="page">
    <h2>Sporty Watches Collection</h2>
    <div class="product">
      <h3>Trailblazer X</h3>
      <img src="https://via.placeholder.com/300x200?text=Trailblazer+X" alt="Trailblazer X">
      <p>Durable, waterproof with shock resistance. ₹9,999</p>
    </div>
    <div class="product">
      <h3>Speed Runner</h3>
      <img src="https://via.placeholder.com/300x200?text=Speed+Runner" alt="Speed Runner">
      <p>Chronograph with digital features. ₹11,500</p>
    </div>
    <div class="product">
      <h3>Adventura Pro</h3>
      <img src="https://via.placeholder.com/300x200?text=Adventura+Pro" alt="Adventura Pro">
      <p>GPS enabled with rugged build. ₹13,800</p>
    </div>
  </div>  <div id="contact" class="page">
    <h2>Contact Us</h2>
    <p>Email: support@chronoclassics.com</p>
    <p>Phone 1: +91-9876543210</p>
    <p>Phone 2: +91-8765432198</p>
    <p>Address: 5th Floor, Watch Tower Plaza, Delhi, India</p>
  </div>  <div id="feedback" class="page">
    <h2>Leave Feedback</h2>
    <form>
      <label for="name">Your Name:</label><br>
      <input type="text" id="name" name="name" /><br><br>
      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email" /><br><br>
      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5" cols="30"></textarea><br><br>
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