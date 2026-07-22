# Maplix.ai
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Maplix.ai</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #ffffff;
      color: #333;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 8%;
      background: white;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }

    .logo {
      font-size: 26px;
      font-weight: bold;
      color: #333;
    }

    .logo span {
      color: #8bc34a;
    }

    nav a {
      margin-left: 25px;
      text-decoration: none;
      color: #555;
      font-weight: 500;
    }

    .hero {
      min-height: 80vh;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 60px 8%;
    }

    .hero-text {
      max-width: 550px;
    }

    /* ===== MAPLIX LOGO ===== */

    .hero-logo {
      width: 140px;
      height: auto;
      display: block;
      margin-bottom: 25px;
    }

    .hero-text h1 {
      font-size: 56px;
      margin-bottom: 20px;
      color: #2f2f2f;
    }

    .hero-text h1 span {
      color: #8bc34a;
    }

    .hero-text p {
      font-size: 20px;
      line-height: 1.6;
      color: #666;
    }

    .buttons {
      margin-top: 30px;
    }

    .btn {
      padding: 14px 26px;
      border-radius: 8px;
      text-decoration: none;
      margin-right: 15px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      transform: translateY(-2px);
    }

    .btn-primary {
      background: #8bc34a;
      color: white;
    }

    .btn-secondary {
      border: 2px solid #8bc34a;
      color: #8bc34a;
    }

    .hero-card {
      background: white;
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 15px 40px rgba(0,0,0,0.08);
      text-align: center;
      max-width: 350px;
    }

    .cube {
      font-size: 70px;
      color: #8bc34a;
      margin-bottom: 20px;
    }

    .section {
      padding: 70px 8%;
      text-align: center;
      background: white;
    }

    .section h2 {
      font-size: 36px;
      margin-bottom: 15px;
    }

    .cards {
      display: flex;
      gap: 25px;
      margin-top: 40px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .card {
      background: #f7f9f6;
      padding: 30px;
      border-radius: 16px;
      width: 280px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.04);
    }

    .card h3 {
      color: #8bc34a;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #2f2f2f;
      color: white;
    }

    @media (max-width: 800px) {

      .hero {
        flex-direction: column;
        text-align: center;
      }

      nav {
        display: none;
      }

      .hero-logo {
        width: 110px;
        margin: 0 auto 25px;
      }

      .hero-text h1 {
        font-size: 40px;
      }

      .hero-card {
        margin-top: 40px;
      }
    }

  </style>
</head>

<body>

<header>

  <div class="logo">
    maplix<span>.ai</span>
  </div>

  <nav>
    <a href="Maplixtest.html">Home</a>
    <a href="features.html">Features</a>
    <a href="pricing.html">Pricing</a>
    <a href="contact.html">Contact</a>
  </nav>

</header>

<section class="hero">

  <div class="hero-text">

    <!-- MAPLIX LOGO -->
    <img src="m-logo.png" alt="Maplix Logo" class="hero-logo">

    <h1>
      Welcome to <span>Maplix.ai</span>
    </h1>

    <p>
      Where space tech and engineering will take you to the next level! 🚀
    </p>

    <div class="buttons">
      <a href="#" class="btn btn-primary">Get Started</a>
      <a href="#" class="btn btn-secondary">Learn More</a>
    </div>

  </div>

  <div class="hero-card">

    <div class="cube">⬢</div>

    <h2>AI-Powered Space Exploration and Engineering Platform</h2>

    <p>
      Use the power of artificial intelligence to create space crafts, satellites, and more. Maplix.ai is your gateway to the future of space exploration.
    </p>

  </div>

</section>

<section class="section" id="features">

  <h2>What Maplix.ai Does</h2>

  <p>Powerful AI tools for space exploration and engineering.</p>

  <div class="cards">

    <div class="card">
      <h3>Smart Mapping</h3>
      <p>Create Efficient and accurate blueprints and designs for your space projects.</p>
    </div>

    <div class="card">
      <h3>AI-Powered Engineers</h3>
      <p>Use artificial intelligence powered Robots to Engineer and build spaceships,satelites and more.</p>
    </div>

    <div class="card">
      <h3>Accuracy</h3>
      <p>Ensure precise and reliable results for your space projects.</p>
    </div>

  </div>

</section>

<section class="section" id="about">

  <h2>Built for the Future</h2>

  <p>
    Maplix.ai combines clean design, artificial intelligence,
    and smart visualization to help make with the future of space exploration and engeneering.
  </p>

</section>

<footer id="contact">
  © 2026 Maplix.ai. All rights reserved.
</footer>

</body>
</html>
