# TK-EMPEROR-COUTURE-A

<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>TK-EMPEROR COUTURE</title>

<style>

* {

  margin: 0;

  padding: 0;

  box-sizing: border-box;

}

body {

  font-family: Arial, sans-serif;

  color: #292323;

  background: #fffaf8;

}

header {

  background: #fff;

  padding: 20px 6%;

  display: flex;

  justify-content: space-between;

  align-items: center;

  flex-wrap: wrap;

  gap: 15px;

}

.logo {

  font-size: 22px;

  font-weight: bold;

  letter-spacing: 2px;

  color: #8d5368;

}

nav a {

  text-decoration: none;

  color: #292323;

  margin-left: 16px;

  font-size: 14px;

}

.hero {

  min-height: 530px;

  display: flex;

  align-items: center;

  padding: 60px 8%;

  background: linear-gradient(90deg, rgba(20,10,15,.65), rgba(20,10,15,.08)),

  url('https://images.unsplash.com/photo-1539109136881-3be0616acf4b?w=1400') center/cover;

  color: white;

}

.hero-content {

  max-width: 500px;

}

.hero h1 {

  font-size: clamp(38px, 7vw, 65px);

  line-height: 1.1;

  margin: 18px 0;

}

.hero p {

  font-size: 17px;

  line-height: 1.7;

  margin-bottom: 28px;

}

.eyebrow {

  letter-spacing: 4px;

  text-transform: uppercase;

  font-size: 12px;

}

.btn {

  display: inline-block;

  padding: 15px 28px;

  background: #a56b7e;

  color: white;

  text-decoration: none;

  letter-spacing: 1px;

  font-size: 13px;

}

section {

  padding: 75px 7%;

}

.section-title {

  text-align: center;

  margin-bottom: 40px;

}

.section-title h2 {

  font-size: 32px;

  margin-bottom: 12px;

}

.section-title p {

  color: #81767a;

  line-height: 1.6;

}

.products {

  display: grid;

  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));

  gap: 25px;

}

.product img {

  width: 100%;

  height: 330px;

  object-fit: cover;

  display: block;

}

.product h3 {

  margin-top: 15px;

  font-size: 18px;

}

.product p {

  margin-top: 8px;

  color: #8d5368;

  font-size: 14px;

}

.about {

  background: #f3e8e9;

  text-align: center;

}

.about p {

  max-width: 700px;

  margin: 20px auto 28px;

  line-height: 1.9;

  color: #62565b;

}

.contact {

  text-align: center;

}

footer {

  background: #292323;

  color: white;

  text-align: center;

  padding: 28px 15px;

  font-size: 13px;

  line-height: 1.8;

}

@media(max-width: 600px) {

  header {

    justify-content: center;

  }

  nav {

    text-align: center;

  }

  nav a {

    margin: 0 7px;

  }

  .hero {

    min-height: 460px;

  }

  section {

    padding: 55px 6%;

  }

}

</style>

</head>

<body>

<header>

  <div class="logo">TK-EMPEROR COUTURE</div>

  <nav>

    <a href="#home">Home</a>

    <a href="#collections">Collections</a>

    <a href="#about">About</a>

    <a href="#contact">Contact</a>

  </nav>

</header>

<div class="hero" id="home">

  <div class="hero-content">

    <div class="eyebrow">Elegance in every stitch</div>

    <h1>Style that defines you.</h1>

    <p>Discover elegant corporate dresses and beautiful ready-to-wear fashion designed for the modern woman.</p>

    <a href="#collections" class="btn">EXPLORE COLLECTION</a>

  </div>

</div>

<section id="collections">

  <div class="section-title">

    <h2>Our Collections</h2>

    <p>Discover elegance, confidence and timeless style.</p>

  </div>

  <div class="products">

    <div class="product">

      <img src="https://images.unsplash.com/photo-1595777457583-95e059d581b8?w=700" alt="Elegant dress">

      <h3>Corporate Elegance</h3>

      <p>Classy looks for every professional woman.</p>

    </div>

    <div class="product">

      <img src="https://images.unsplash.com/photo-1483985988355-763728e1935b?w=700" alt="Women's fashion">

      <h3>Ready to Wear</h3>

      <p>Beautiful styles for your everyday moments.</p>

    </div>

    <div class="product">

      <img src="https://images.unsplash.com/photo-1539109136881-3be0616acf4b?w=700" alt="Fashion outfit">

      <h3>Luxury Styles</h3>

      <p>Make every appearance unforgettable.</p>

    </div>

  </div>

</section>

<section class="about" id="about">

  <div class="section-title">

    <h2>About TK-EMPEROR COUTURE</h2>

  </div>

  <p>

    At TK-EMPEROR COUTURE, we believe every woman deserves to feel confident, beautiful and elegant. Our collections celebrate modern femininity through classy corporate dresses and stylish ready-to-wear outfits.

  </p>

  <a href="#contact" class="btn">GET IN TOUCH</a>

</section>

<section class="contact" id="contact">

  <div class="section-title">

    <h2>Contact Us</h2>

    <p>Ready to find your perfect style? We'd love to hear from you.</p>

  </div>

  <a href="mailto:info@tkemperorcouture.com" class="btn">EMAIL US</a>

</section>

<footer>

  <p>TK-EMPEROR COUTURE</p>

  <p>Elegance in every stitch. Style that defines you.</p>

  <p>© 2026 TK-EMPEROR COUTURE. All rights reserved.</p>

</footer>

</body>

</html>
