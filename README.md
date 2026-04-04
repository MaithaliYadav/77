<!DOCTYPE html>
<section id="menu" class="container my-5">
  <h2 class="text-center mb-4">Our Menu</h2>
  <div class="d-flex justify-content-center mb-4">
    <button class="btn btn-dark me-2" onclick="filterMenu('all')">All</button>
    <button class="btn btn-success me-2" onclick="filterMenu('veg')">Veg</button>
    <button class="btn btn-danger" onclick="filterMenu('nonveg')">Non-Veg</button>
  </div>
  <div class="row g-4" id="menuItems">

    <div class="col-md-6 col-lg-4 menu-item veg">
      <div class="card h-100"><div class="card-body">
        <h5 class="card-title">Margherita Pizza <span class="badge bg-success float-end">Veg</span></h5>
        <p class="text-muted">Fresh basil, mozzarella, and tomatoes.</p>
      </div></div>
    </div>

    <div class="col-md-6 col-lg-4 menu-item nonveg">
      <div class="card h-100"><div class="card-body">
        <h5 class="card-title">Chicken Alfredo <span class="badge bg-danger float-end">Non-Veg</span></h5>
        <p class="text-muted">Creamy pasta with grilled chicken.</p>
      </div></div>
    </div>

    <div class="col-md-6 col-lg-4 menu-item veg">
      <div class="card h-100"><div class="card-body">
        <h5 class="card-title">Penne Arrabbiata <span class="badge bg-success float-end">Veg</span></h5>
        <p class="text-muted">Spicy tomato sauce with garlic and chili.</p>
      </div></div>
    </div>

  </div>
</section>

<!-- Reservation -->
<section id="reservation" class="container my-5 py-5 bg-light rounded shadow-sm">
  <h2 class="text-center mb-4">Reserve a Table</h2>
  <form id="resForm" class="row g-3 px-lg-5">
    <div class="col-md-6"><input type="text" class="form-control" placeholder="Name" required></div>
    <div class="col-md-6"><input type="email" class="form-control" placeholder="Email" required></div>
    <div class="col-md-4"><input type="date" class="form-control" required></div>
    <div class="col-md-4"><input type="time" class="form-control" required></div>
    <div class="col-md-4"><input type="number" class="form-control" min="1" placeholder="Guests" required></div>
    <div class="col-12 text-center mt-4">
      <button type="submit" class="btn btn-dark btn-lg w-50">Confirm Booking</button>
    </div>
  </form>
</section>

<!-- Footer -->
<footer class="bg-dark text-light text-center p-5 mt-5">
  <p>📍 Nagpur, Maharashtra</p>
  <p>📞 +91 1111 2222 55</p>
  <p class="small opacity-50">© 2026 La Pasta Bella</p>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

<script>
function filterMenu(type) {
  const items = document.querySelectorAll('.menu-item');
  items.forEach(item => {
    if (type === 'all') item.classList.remove('d-none');
    else item.classList.toggle('d-none', !item.classList.contains(type));
  });
}

document.getElementById('resForm').addEventListener('submit', function(e) {
  e.preventDefault();
  alert('Grazie! Reservation submitted successfully.');
  this.reset();
});
</script>

</body>
</html>



