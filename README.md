<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>La Pasta Bella</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">La Pasta Bella</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#gallery">maithali</a></li>
        <li class="nav-item"><a class="nav-link" href="#menu">Meun : veg-non-veg</a></li>
        <li class="nav-item"><a class="nav-link" href="#reservation">Reservation : LA PASTA BELLA</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<header class="bg-light text-center p-5">
  <h1>Welcome to La Pasta Bella</h1>
  <p>Authentic Italian dining experience</p>
  <a href="#reservation" class="btn btn-primary">Book a Table</a>
</header>

<!-- Gallery -->
<section id="gallery" class="container my-5">
  <h2 class="text-center mb-4">Our Ambiance</h2>
  <div class="row g-3">
    <div class="col-md-4"><img src="img1.jpg" class="img-fluid rounded" alt="Restaurant interior"></div>
    <div class="col-md-4"><img src="img2.jpg" class="img-fluid rounded" alt="Dining area"></div>
    <div class="col-md-4"><img src="img3.jpg" class="img-fluid rounded" alt="Italian food"></div>
  </div>
</section>

<!-- Menu -->
<section id="menu" class="container my-5">
  <h2 class="text-center mb-4">Our Menu</h2>
  <div class="d-flex justify-content-center mb-3">
    <button class="btn btn-outline-secondary me-2" onclick="filterMenu('all')">All</button>
    <button class="btn btn-outline-success me-2" onclick="filterMenu('veg')">Veg</button>
    <button class="btn btn-outline-danger" onclick="filterMenu('nonveg')">Non-Veg</button>
  </div>
  <div class="row" id="menuItems">
    <div class="col-md-4 menu-item veg">
      <div class="card"><div class="card-body">
        <h5 class="card-title">Margherita Pizza <span class="badge bg-success">Veg</span></h5>
        <p>Classic vegetarian pizza with fresh basil</p>
      </div></div>
    </div>
    <div class="col-md-4 menu-item nonveg">
      <div class="card"><div class="card-body">
        <h5 class="card-title">Chicken Alfredo Pasta <span class="badge bg-danger">Non-Veg</span></h5>
        <p>Creamy pasta with grilled chicken</p>
      </div></div>
    </div>
    <!-- Add more dishes here -->
  </div>
</section>

<!-- Reservation Form -->
<section id="reservation" class="container my-5">
  <h2 class="text-center mb-4">Reserve a Table</h2>
  <form class="row g-3">
    <div class="col-md-6">
      <label for="name" class="form-label">Name</label>
      <input type="text" class="form-control" id="name" required>
    </div>
    <div class="col-md-6">
      <label for="email" class="form-label">Email</label>
      <input type="email" class="form-control" id="email" required>
    </div>
    <div class="col-md-6">
      <label for="date" class="form-label">Date</label>
      <input type="date" class="form-control" id="date" value="2026-06-19" required>
    </div>
    <div class="col-md-6">
      <label for="time" class="form-label">Time</label>
      <input type="time" class="form-control" id="time" min="08:30" max="12:30" required>
    </div>
    <div class="col-md-6">
      <label for="guests" class="form-label">Guests</label>
      <input type="number" class="form-control" id="guests" min="1" required>
    </div>
    <div class="col-12">
      <label for="requests" class="form-label">Special Requests</label>
      <textarea class="form-control" id="requests" rows="3"></textarea>
    </div>
    <div class="col-12">
      <button type="submit" class="btn btn-success">Reserve Now</button>
    </div>
  </form>
</section>

<!-- Footer -->
<footer class="bg-dark text-light text-center p-4 mt-5">
  <div class="container">
    <p class="mb-1">📍 Address: Nagpur</p>
    <p class="mb-1">📞 Phone: +91 111122225555</p>
    <p class="mb-1">✉️ Email: info@lapastabella.com</p>
    <p class="mb-1">👩‍🍳 Owner: Maithali</p>
    <p class="mb-1">👨‍💼 Manager: Masum</p>
    <div class="mt-2">
      <a href="#" class="text-light me-3">Facebook</a>
      <a href="#" class="text-light me-3">Instagram</a>
      <a href="#" class="text-light">Twitter</a>
    </div>
    <p class="mt-3 mb-0">&copy; 2026 La Pasta Bella. All rights reserved.</p>
  </div>
</footer>

<script>
function filterMenu(type) {
  const items = document.querySelectorAll('.menu-item');
  items.forEach(item => {
    if (type === 'all') {
      item.classList.remove('d-none');
    } else {
      item.classList.toggle('d-none', !item.classList.contains(type));
    }
  });
}
</script>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>



