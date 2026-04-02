<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>La Pasta Bella</title>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092') no-repeat center/cover;
  color: #fff;
}

body::before {
  content: "";
  position: fixed;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.6);
  top: 0;
  left: 0;
  z-index: -1;
}

header {
  text-align: center;
  padding: 30px;
  background: rgba(139,0,0,0.8);
}

nav {
  text-align: center;
  background: #333;
  padding: 10px;
}

nav a {
  color: white;
  margin: 10px;
  text-decoration: none;
}

section {
  padding: 20px;
}

.menu-items {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.card {
  background: rgba(255,255,255,0.9);
  color: black;
  margin: 10px;
  padding: 10px;
  border-radius: 10px;
  width: 220px;
  text-align: center;
}

.card img {
  width: 100%;
  border-radius: 10px;
}

footer {
  background: #000;
  padding: 20px;
  text-align: center;
}
</style>
</head>

<body>

<header>
  <h1>La Pasta Bella</h1>
  <p>Authentic Italian Dining Experience</p>
  <p><strong>Starting Price:</strong> ₹200 – ₹1000</p>
</header>

<nav>
  <a href="#menu">Menu</a>
  <a href="#contact">Contact</a>
</nav>

<section id="menu">
  <h2>Our Menu</h2>

  <div class="menu-items">

    <!-- Veg Items -->
    <div class="card">
      <h3>Palak Paneer</h3>
      <p>₹100</p>
    </div>

    <div class="card">
      <h3>Lentil Dal</h3>
      <p>₹200</p>
    </div>

    <div class="card">
      <h3>Ratatouille</h3>
      <p>₹300</p>
    </div>

    <div class="card">
      <h3>Shiro Wat</h3>
      <p>₹400</p>
    </div>

    <!-- Non-Veg Items -->
    <div class="card">
      <h3>Butter Chicken</h3>
      <p>₹200</p>
    </div>

    <div class="card">
      <h3>Hyderabadi Biryani</h3>
      <p>₹300</p>
    </div>

    <div class="card">
      <h3>Tandoori Chicken</h3>
      <p>₹400</p>
    </div>

    <div class="card">
      <h3>Mutton Rogan Josh</h3>
      <p>₹500</p>
    </div>

    <div class="card">
      <h3>Fish Curry</h3>
      <p>₹300</p>
    </div>

  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p><strong>Phone:</strong> <a href="tel:9512345615">9512345615</a></p>
  <p><strong>Email:</strong> <a href="mailto:lapastabella@gmail.com">lapastabella@gmail.com</a></p>
  <p><strong>Location:</strong> Mankapur</p>

  <p>
    <a href="https://facebook.com">Facebook</a> |
    <a href="https://instagram.com">Instagram</a> |
    <a href="https://wa.me/919512345615">WhatsApp</a> |
    <a href="https://t.me/">Telegram</a>
  </p>
</section>

<footer>
  <p>© 2026 La Pasta Bella</p>
  <p><strong>Owner:</strong> Maithali Yadav</p>
  <p><strong>Manager:</strong> Masum Yadav</p>
  <p><strong>Date:</strong> 19 April 2026</p>
  <p><strong>Opening Hours:</strong> 8:30 AM – 12:30 PM</p>
</footer>

    

