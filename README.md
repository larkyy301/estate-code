
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DreamNest Realty</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <div class="container">
      <h1 class="logo">DreamNest Realty</h1>
      <nav>
        <ul class="nav-links">
          <li><a href="#">Home</a></li>
          <li><a href="#">Listings</a></li>
          <li><a href="#">Agents</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h2>Find Your Dream Home</h2>
      <p>Discover the best properties in the city with expert guidance.</p>
      <a href="#" class="btn">View Listings</a>
    </div>
  </section>

  <section class="listings">
    <div class="container">
      <h2>Featured Listings</h2>
      <div class="cards">
        <div class="card">
          <img src="https://source.unsplash.com/400x250/?house,modern" alt="House 1" />
          <div class="card-content">
            <h3>Modern Family Home</h3>
            <p>3 Bed · 2 Bath · $450,000</p>
          </div>
        </div>
        <div class="card">
          <img src="https://source.unsplash.com/400x250/?house,luxury" alt="House 2" />
          <div class="card-content">
            <h3>Luxury Villa</h3>
            <p>5 Bed · 4 Bath · $1,200,000</p>
          </div>
        </div>
        <div class="card">
          <img src="https://source.unsplash.com/400x250/?apartment,city" alt="House 3" />
          <div class="card-content">
            <h3>Downtown Apartment</h3>
            <p>2 Bed · 1 Bath · $320,000</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="about">
    <div class="container">
      <h2>Why Choose Us?</h2>
      <p>
        At DreamNest Realty, we specialize in connecting people with their perfect property. Whether you're looking to buy, sell, or rent — our expert agents are here to guide you every step of the way.
      </p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 DreamNest Realty. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
}

body {
  background: #f9f9f9;
  color: #333;
  line-height: 1.6;
}

.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
}

header {
  background: #0d1b2a;
  padding: 20px 0;
  color: #fff;
}

.logo {
  font-size: 24px;
  font-weight: 600;
}

.nav-links {
  list-style: none;
  display: flex;
  justify-content: flex-end;
  gap: 20px;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #ffc300;
}

header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.hero {
  background: url('https://source.unsplash.com/1600x600/?realestate') no-repeat center center/cover;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

.hero h2 {
  font-size: 48px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 20px;
}

.btn {
  background: #ffc300;
  color: #000;
  padding: 12px 24px;
  text-decoration: none;
  border-radius: 30px;
  font-weight: bold;
  transition: background 0.3s ease;
}

.btn:hover {
  background: #e0a800;
}

.listings {
  padding: 60px 20px;
  background: #fff;
}

.listings h2 {
  text-align: center;
  margin-bottom: 40px;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
}

.card {
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: transform 0.2s ease;
}

.card:hover {
  transform: translateY(-5px);
}

.card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.card-content {
  padding: 15px;
}

.card-content h3 {
  font-size: 20px;
  margin-bottom: 5px;
}

.about {
  padding: 60px 20px;
  background: #f1f1f1;
  text-align: center;
}

.about h2 {
  margin-bottom: 20px;
}

.about p {
  max-width: 700px;
  margin: auto;
  font-size: 18px;
}

footer {
  background: #0d1b2a;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}

