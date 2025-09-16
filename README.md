<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BR4freelance | Business-Driven Freelance Services</title>
  <meta name="description" content="BR4freelance - A group of freelancers providing cost-effective and business-driven services in Web Design, Development, SEO, and AI solutions.">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar">
    <div class="container nav-container">
      <h1 class="logo">BR4freelance</h1>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero -->
  <header class="hero">
    <div class="container">
      <h2>We are <span>BR4freelance</span></h2>
      <p class="tagline">Providing cost-effective, business-driven freelance services</p>
      <a href="#services" class="btn">Explore Our Services</a>
    </div>
  </header>

  <!-- About -->
  <section id="about" class="section">
    <div class="container">
      <h2>About Us</h2>
      <p>
        BR4freelance is a group of passionate freelancers offering innovative 
        and reliable solutions to help businesses grow online. We specialize in 
        creating effective websites, scalable applications, and smart digital 
        marketing strategies that drive results.
      </p>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="section bg-light">
    <div class="container">
      <h2>Our Services</h2>
      <div class="grid">
        <div class="card">
          <h3>Web Design</h3>
          <p>Creative, responsive, and user-friendly designs for WordPress, Webflow, Shopify, and more.</p>
        </div>
        <div class="card">
          <h3>Development</h3>
          <p>Custom development with Python, React, Node.js, and Laravel for business applications.</p>
        </div>
        <div class="card">
          <h3>SEO</h3>
          <p>Result-driven SEO including On-page, Off-page, Technical SEO, and Local SEO strategies.</p>
        </div>
        <div class="card">
          <h3>AI Solutions</h3>
          <p>Intelligent AI chatbots, automation tools, and business AI integrations to enhance efficiency.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="section">
    <div class="container">
      <h2>Recent Projects</h2>
      <div class="grid">
        <div class="card">
          <h3>E-commerce Redesign</h3>
          <p>Revamped a Shopify store with modern UI, boosting sales by 40%.</p>
        </div>
        <div class="card">
          <h3>SEO Campaign</h3>
          <p>Executed a local SEO strategy for a business, increasing organic traffic by 65%.</p>
        </div>
        <div class="card">
          <h3>AI Chatbot</h3>
          <p>Developed a customer-support chatbot that reduced response time by 70%.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="section bg-light">
    <div class="container">
      <h2>Contact Us</h2>
      <p>Email: <a href="mailto:br4freelance@gmail.com">br4freelance@gamil.com</a></p>
      <p>GitHub: <a href="https://github.com/br4freelance" target="_blank">github.com/br4freelance</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© <span id="year"></span> BR4freelance | Cost-effective, business-driven freelance services</p>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>

/* Global */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: system-ui, Arial, sans-serif;
  line-height: 1.6;
  color: #222;
  background: #f9f9f9;
}

.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
}

h1, h2, h3 {
  margin-bottom: 1rem;
  font-weight: 600;
}

a {
  color: #0077cc;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* Navbar */
.navbar {
  background: #111;
  color: #fff;
  padding: 1rem 0;
}

.nav-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1rem;
}

.nav-links a {
  color: #fff;
  font-weight: 500;
}

.nav-links a:hover {
  color: #00c2ff;
}

/* Hero */
.hero {
  background: linear-gradient(to right, #0077cc, #00c2ff);
  color: #fff;
  text-align: center;
  padding: 4rem 1rem;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.hero span {
  color: #ffeb3b;
}

.tagline {
  font-size: 1.2rem;
  margin-bottom: 2rem;
}

.btn {
  display: inline-block;
  padding: 0.75rem 1.5rem;
  background: #fff;
  color: #0077cc;
  border-radius: 5px;
  font-weight: bold;
}

.btn:hover {
  background: #f0f0f0;
}

/* Sections */
.section {
  padding: 3rem 1rem;
}

.section h2 {
  text-align: center;
  margin-bottom: 2rem;
}

.bg-light {
  background: #f1f1f1;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
}

.card {
  background: #fff;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
}

.card h3 {
  margin-bottom: 1rem;
  color: #0077cc;
}

/* Footer */
footer {
  text-align: center;
  background: #111;
  color: #fff;
  padding: 1rem 0;
}
