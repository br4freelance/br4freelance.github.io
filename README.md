<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Abhishek Ranaut | Portfolio</title>
  <meta name="description" content="Portfolio of Abhishek Ranaut — Web Designer, Python Developer, SEO Specialist, and AI Chatbot Developer.">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Navigation -->
  <nav class="navbar">
    <div class="container nav-container">
      <h1 class="logo">Abhishek Ranaut</h1>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="hero">
    <div class="container">
      <h2>Hi 👋, I'm <span>Abhishek</span></h2>
      <p class="tagline">Web Designer | Python Developer | SEO Specialist | AI Chatbot Developer</p>
      <a href="#projects" class="btn">View My Work</a>
    </div>
  </header>

  <!-- About -->
  <section id="about" class="section">
    <div class="container">
      <h2>About Me</h2>
      <p>
        I am passionate about creating user-friendly, responsive websites and building 
        intelligent digital solutions. With experience in web design, full-stack development, 
        SEO, and AI-powered chatbots, I help businesses grow their online presence and 
        improve customer engagement.
      </p>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="section bg-light">
    <div class="container">
      <h2>My Skills</h2>
      <div class="grid">
        <div class="card">
          <h3>Web Design</h3>
          <p>WordPress, Webflow, Shopify, Wix, BigCommerce</p>
        </div>
        <div class="card">
          <h3>Development</h3>
          <p>Python, Django, React, Node.js, Laravel</p>
        </div>
        <div class="card">
          <h3>SEO</h3>
          <p>On-page, Off-page, Technical SEO, Local SEO</p>
        </div>
        <div class="card">
          <h3>AI Solutions</h3>
          <p>Chatbots, Automation, Business AI Tools</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="section">
    <div class="container">
      <h2>Projects</h2>
      <div class="grid">
        <div class="card">
          <h3>Portfolio Website</h3>
          <p>A responsive personal portfolio built with HTML, CSS, and JavaScript.</p>
          <a href="https://github.com/yourusername/portfolio" target="_blank">View Code</a>
        </div>
        <div class="card">
          <h3>SEO Dashboard</h3>
          <p>An analytics tool for monitoring SEO performance and ranking.</p>
          <a href="https://github.com/yourusername/seo-dashboard" target="_blank">View Code</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="section bg-light">
    <div class="container">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></p>
      <p>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© <span id="year"></span> Abhishek Ranaut | All Rights Reserved</p>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
