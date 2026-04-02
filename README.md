<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>La Pasta Bella</title>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f5f5f5;
}

header {
  text-align: center;
  padding: 30px;
  background: #8b0000;
  color: white;
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
  background: white;
  margin: 10px;
  padding: 15px;
  border-radius: 10px;
  width: 220px;
  text-align: center;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

form input, form select, form button {
  width: 260px;
  padding: 10px;
  margin: 10px;
  border-radius: 5px;
  border: none;
}

button {
  background: #8b0000;
  color: white;
  cursor: pointer;
}

button:hover {
  background: #a00000;
}

footer {
  background: #000;
  color: white;
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
  <a href="#reservation">Book Table</a>
  <a href="#contact">Contact</a>
</nav>

<section id="menu">
  <h2>Our Menu</h2>
  <div class="menu-items">

    <div class="card"><h3>Palak Paneer</h3><p>₹100</p></div>
    <div class="card"><h3>Lentil Dal</h3><p>₹200</p></div>
    <div class="card"><h3>Ratatouille</h3><p>₹300</p></div>
    <div class="card"><h3>Shiro Wat</h3><p>₹400</p></div>

    <div class="card"><h3>Butter Chicken</h3><p>₹200</p></div>
    <div class="card"><h3>Hyderabadi Biryani</h3><p>₹300</p></div>
    <div class="card"><h3>Tandoori Chicken</h3><p>₹400</p></div>
    <div class="card"><h3>Mutton Rogan Josh</h3><p>₹500</p></div>
    <div class="card"><h3>Fish Curry</h3><p>₹300</p></div>

  </div>
</section>

<section id="reservation">
  <h2>Book a Table</h2>

  <form onsubmit="submitForm(event)">
    <input type="text" placeholder="Your Name" required><br>
    <input type="date" required><br>
    <input type="time" required><br>

    <select required>
      <option value="">Select Food Type</option>
      <option>Veg</option>
      <option>Non-Veg</option>
    </select><br>

    <input type="number" placeholder="Number of Guests" required><br>

    <button type="submit">Submit</button>
  </form>

  <p id="message"></p>

  <h2>Pay Online (UPI)</h2>

  <a href="upi://pay?pa=9512345615@upi&pn=La Pasta Bella&am=200&cu=INR" onclick="showPaymentMsg()">
    <button>Pay ₹200 via UPI</button>
  </a>

  <p id="payMsg" style="font-weight:bold; color:green;"></p>

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

<script>
function submitForm(event) {
  event.preventDefault();
  document.getElementById("message").innerText = "✅ Table booked successfully!";
}

function showPaymentMsg() {
  document.getElementById("payMsg").innerText = "🙏 Thank you for your payment!";
}
</script>

</body>
</html>
    

