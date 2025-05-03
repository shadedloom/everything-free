# <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Everything Free</title>
  <style>
    /* Base Styling */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Arial", sans-serif;
    }

    body {
      background-color: #f4f4f9;
      color: #333;
    }

    header {
      background-color: #008080;
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 2rem;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }

    nav a {
      text-decoration: none;
      color: #fff;
      font-size: 1rem;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 80vh;
      background: url('https://via.placeholder.com/1200x800') no-repeat center center/cover;
      color: #fff;
      text-align: center;
    }

    .hero h2 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }

    .section {
      padding: 4rem 2rem;
      text-align: center;
    }

    .section h3 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .section p {
      max-width: 600px;
      margin: 0 auto;
      line-height: 1.6;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }

    .features div {
      background-color: #fff;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 1rem 0;
    }

    footer p {
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Everything Free</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div>
      <h2>All for Free</h2>
      <p>Discover amazing resources, services, and opportunities—completely free of charge.</p>
    </div>
  </section>

  <section id="about" class="section">
    <h3>About Us</h3>
    <p>At Everything Free, we believe in the power of generosity. Explore a world of free resources that empower, inspire, and support communities globally.</p>
  </section>

  <section id="features" class="section">
    <h3>Our Features</h3>
    <div class="features">
      <div>
        <h4>Free Education</h4>
        <p>Access courses and materials without any cost.</p>
      </div>
      <div>
        <h4>Free Tools</h4>
        <p>Discover apps and software to enhance your productivity.</p>
      </div>
      <div>
        <h4>Free Support</h4>
        <p>Get help and guidance from our community.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <h3>Contact Us</h3>
    <p>Email: support@everythingfree.com | Phone: +1 800 FREE 123</p>
  </section>

  <footer>
    <p>&copy; 2025 Everything Free. All rights reserved.</p>
  </footer>
</body>
</html>
