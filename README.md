<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gold Aura Jewellery</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #fffaf3;
      color: #333;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 50px;
      background-color: #fff;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #b8860b;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #b8860b;
    }
    .hero {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1600185365483-26d7a4e66c7a') center/cover no-repeat;
      color: #fff;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 18px;
      margin-bottom: 30px;
    }
    .btn {
      background-color: #b8860b;
      color: #fff;
      padding: 12px 25px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.3s;
    }
    .btn:hover {
      background-color: #cfa24b;
    }
    .section {
      padding: 60px 50px;
      text-align: center;
    }
    .section h2 {
      font-size: 32px;
      color: #b8860b;
      margin-bottom: 30px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }
    .product {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }
    .product:hover {
      transform: translateY(-5px);
    }
    .product img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }
    .product h3 {
      font-size: 20px;
      margin: 15px 0 5px;
    }
    .product p {
      color: #555;
    }
    .price {
      color: #b8860b;
      font-weight: bold;
      margin-bottom: 15px;
    }
    .about {
      max-width: 800px;
      margin: auto;
      font-size: 18px;
      color: #555;
      line-height: 1.8;
    }
    form {
      max-width: 600px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, textarea {
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Gold Aura</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#shop">Shop</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Elegance in Every Piece</h1>
    <p>Discover handcrafted jewellery that defines your beauty.</p>
    <a href="#shop" class="btn">Shop Now</a>
  </section>

  <section id="shop" class="section">
    <h2>Our Collection</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1522312346375-d1a52e2b99b3" alt="Necklace">
        <h3>Golden Pearl Necklace</h3>
        <p class="price">$120</p>
        <p>Elegant pearls crafted with perfection.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1576395107442-5a6b4d9e6c42" alt="Ring">
        <h3>Diamond Eternity Ring</h3>
        <p class="price">$250</p>
        <p>Shine that lasts forever.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1627338488360-0d1b0e7f8b9c" alt="Earrings">
        <h3>Royal Hoop Earrings</h3>
        <p class="price">$90</p>
        <p>Crafted to make you sparkle.</p>
      </div>
    </div>
  </section>

  <section id="about" class="section">
    <h2>About Gold Aura</h2>
    <div class="about">
      <p>Gold Aura is a fine jewellery brand known for its timeless designs and elegant craftsmanship. Each piece is a story of tradition, luxury, and artistry. We combine modern aesthetics with classic detailing to create jewellery that complements every personality.</p>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button class="btn" type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Gold Aura Jewellery. All Rights Reserved.</p>
  </footer>
</body>
</html>
