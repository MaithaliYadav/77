<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maithali</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Maithali</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
        <li class="nav-item"><a class="nav-link" href="#menu">Menu</a></li>
        <li class="nav-item"><a class="nav-link" href="#reservation">Reservation</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<header class="bg-light text-center p-5">
  <h1>Welcome to Maithali</h1>
  <p>Authentic Italian dining experience in Mankapur</p>
  <a href="#reservation" class="btn btn-primary">Book a Table</a>
</header>

<!-- Gallery -->
<section id="gallery" class="container my-5">
  <h2 class="text-center mb-4">Our Ambiance</h2>
  <div class="row g-3">
    <div class="col-md-4"><img src="img1.<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/b37d4988-3feb-47c4-97fa-2ef38c3616e0" />
jpg" class="img-fluid rounded" alt="Restaurant"></div>
    <div class="col-md-4"><img src="img2.<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/f976fdf7-ddfb-41f3-b7ca-950950bb20bb" />
jpg" class="img-fluid rounded" alt="Dining"></div>
    <div class="col-md-4"><img src="img3.<img width="241" height="148" alt="image" src="https://github.com/user-attachments/assets/e5278da9-8d3d-40a9-9ba2-e41191cb2d98" />
jpg" class="img-fluid rounded" alt="Food"></div>
  </div>
</section>

<!-- Menu -->
<section id="menu" class="container my-5">
  <h2 class="text-center mb-4">Our Menu</h2>
  <div class="d-flex justify-content-center mb-3">
    <button class="btn btn-outline-primary me-2" onclick="filterMenu('veg')">Veg</button>
    <button class="btn btn-outline-danger" onclick="filterMenu('nonveg')">Non-Veg</button>
  </div>
  <div class="row" id="menuItems">
    <!-- Veg Item -->
    <div class="col-md-4 menu-item veg">
      <div class="card"><div class="card-body"><h5 class="card-title">Margherita Pizza</h5><p>Classic veg pizza</p></div></div>
    </div>
    <!-- Non-Veg Item -->
    <div class="col-md-4 menu-item nonveg">
      <div class="card"><div class="card-body"><h5 class="card-title">Chicken Alfredo Pasta</h5><p>Creamy non-veg pasta</p></div></div>
    </div>
    <!-- Cheese Burger -->
    <div class="col-md-4 menu-item nonveg">
      <div class="card"><div class="card-body"><h5 class="card-title">Cheese Burger</h5><p>Juicy burger with melted cheese</p></div></div>
    </div>
    <!-- Cheese Sandwich -->
    <div class="col-md-4 menu-item veg">
      <div class="card"><div class="card-body"><h5 class="card-title">Cheese Sandwich</h5><p>Grilled sandwich with melted cheese</p></div></div>
    </div>
    <!-- Hot Dog -->
    <div class="col-md-4 menu-item nonveg">
      <div class="card"><div class="card-body"><h5 class="card-title">Hot Dog</h5><p>Classic grilled sausage in a bun with toppings</p></div></div>
    </div>
    <!-- French Fries -->
    <div class="col-md-4 menu-item veg">
      <div class="card"><div class="card-body"><h5 class="card-title">French Fries</h5><p>Crispy golden fries served hot</p></div></div>
    </div>
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
      <input type="date" class="form-control" id="date" required value="2027-06-19">
    </div>
    <div class="col-md-6">
      <label for="time" class="form-label">Time</label>
      <input type="time" class="form-control" id="time" required min="08:30" max="12:30">
    </div>
    <div class="col-12">
      <button type="submit" class="btn btn-success">Reserve Now</button>
    </div>
  </form>
  <p class="text-muted mt-2">Reservations available between 8:30 AM and 12:30 PM</p>
</section>

<!-- Footer -->
<footer class="bg-dark text-light text-center p-3">
  <p>© 2026 Maithali | Address: Mankapur</p>
</footer>

<script>
function filterMenu(type) {
  const items = document.querySelectorAll('.menu-item');
  items.forEach(item => {
    item.style.display = item.classList.contains(type) ? 'block' : 'none';
  });
}
</script>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

