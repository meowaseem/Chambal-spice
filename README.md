# Chambal-spice
<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chambal Spice</title>
<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #fff;
  color: #333;
}

header {
background: #8B0000;
color: white;
padding: 20px;
text-align: center;
}

nav {
display: flex;
justify-content: center;
background: #222;
}

nav a {
color: white;
padding: 14px 20px;
text-decoration: none;
}

nav a:hover {
background: #8B0000;
}

.hero {
background: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092') no-repeat center/cover;
height: 60vh;
display: flex;
align-items: center;
justify-content: center;
color: white;
font-size: 40px;
font-weight: bold;
}

.section {
padding: 40px;
text-align: center;
}

.menu-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
gap: 20px;
}

.card {
border: 1px solid #ddd;
padding: 20px;
border-radius: 10px;
}

footer {
background: #222;
color: white;
text-align: center;
padding: 20px;
}

button {
background: #8B0000;
color: white;
padding: 10px 20px;
border: none;
cursor: pointer;
}

button:hover {
background: black;
} </style>

</head>

<body>

<header>
  <h1>Chambal Spice</h1>
  <p>Family-Friendly Restaurant | ₹200–400</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#menu">Menu</a>
  <a href="#reviews">Reviews</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero">
  Taste the Authentic Flavors 🍛
</div>

<section id="about" class="section">
  <h2>About Us</h2>
  <p>
    Chambal Spice is a highly rated (4.7⭐) family-friendly restaurant in Dholpur, Rajasthan.
    Known for delicious food, fast service, and warm hospitality.
  </p>
  <p>Outdoor seating • Vegan options • Clean & comfortable ambiance</p>
</section>

<section id="menu" class="section">
  <h2>Popular Menu</h2>
  <div class="menu-grid">
    <div class="card">Chole Bhature</div>
    <div class="card">Paneer Lababdar</div>
    <div class="card">Butter Paneer Masala</div>
    <div class="card">Malai Kofta</div>
    <div class="card">Hakka Noodles</div>
    <div class="card">Dal Tadka</div>
    <div class="card">Naan & Roti</div>
    <div class="card">Masala Tea</div>
  </div>
</section>

<section id="reviews" class="section">
  <h2>Customer Reviews ⭐</h2>
  <p><strong>4.7 / 5 (1500+ Reviews)</strong></p>
  <p>"Very tasty food and great ambiance!"</p>
  <p>"Fast service and reasonable prices."</p>
  <p>"Clean place with friendly staff."</p>
</section>

<section id="contact" class="section">
  <h2>Contact Us</h2>
  <p>📍 Near Royal Enfield Showroom, Dholpur, Rajasthan</p>
  <p>📞 080005 14885</p>
  <p>⏰ Open till 12 AM</p>
  <button onclick="callNow()">Call Now</button>
</section>

<footer>
  <p>© 2026 Chambal Spice | All Rights Reserved</p>
</footer>

<script>
function callNow() {
  window.location.href = "tel:08000514885";
}
</script>

</body>
</html>
