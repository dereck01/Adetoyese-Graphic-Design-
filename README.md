# Adetoyese-Graphic-Design- <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adetoyese Graphic Design</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #111;
      color: #fff;
      padding: 1.5rem 2rem;
      text-align: center;
      animation: fadeIn 1.5s ease-in-out;
    }

    header h1 {
      font-size: 2.5rem;
    }

    nav {
      background: #222;
      display: flex;
      justify-content: center;
      padding: 1rem;
    }

    nav a {
      color: #fff;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00b894;
    }

    .hero {
      background: url('https://via.placeholder.com/1200x400') center/cover no-repeat;
      padding: 5rem 2rem;
      text-align: center;
      color: white;
      animation: fadeIn 2s ease-in-out;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .gallery {
      padding: 4rem 2rem;
      max-width: 1200px;
      margin: auto;
      animation: slideUp 1.5s ease-in-out;
    }

    .gallery h3 {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 2rem;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .gallery-grid img {
      width: 100%;
      height: auto;
      border-radius: 12px;
      transition: transform 0.4s;
    }

    .gallery-grid img:hover {
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 2rem;
      background: #111;
      color: #ccc;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Adetoyese Graphic Design</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Creative. Modern. Professional.</h2>
    <p>We bring your ideas to life through stunning graphic design.</p>
  </section>

  <section class="gallery" id="gallery">
    <h3>Our Work</h3>
    <div class="gallery-grid">
      <img src="https://via.placeholder.com/400x300" alt="Design 1" />
      <img src="https://via.placeholder.com/400x300" alt="Design 2" />
      <img src="https://via.placeholder.com/400x300" alt="Design 3" />
      <img src="https://via.placeholder.com/400x300" alt="Design 4" />
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Adetoyese Graphic Design. All rights reserved.</p>
  </footer>
</body>
</html>
