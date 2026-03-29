<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maithali's res</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Maithali - Mankapur</a>
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
    <div class="col-md-4"><img src="img1.data:image/jpeg;base64,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" class="img-fluid rounded" alt="Restaurant"></div>
    <div class="col-md-4"><img src="img2.jpg" class="img-fluid rounded" alt="Dining"></div>
    <div class="col-md-4"><img src="img3.jpg" class="img-fluid rounded" alt="Food"></div>
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
    <div class="col-md-4 menu-item veg">
      <div class="card"><div class="card-body"><h5 class="card-title">Margherita Pizza</h5><p>Classic veg pizza</p></div></div>
    </div>
    <div class="col-md-4 menu-item nonveg">
      <div class="card"><div class="card-body"><h5 class="card-title">Chicken Alfredo Pasta</h5><p>Creamy non-veg pasta</p></div></div>
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
  <p>© 2026 Maithali | Located in Mankapur</p>
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



     

       
