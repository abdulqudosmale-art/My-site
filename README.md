# My-site
For my beautiful and prettiest girl 
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #0f172a;
      color: white;
      line-height: 1.6;
    }

    header {
      position: fixed;
      width: 100%;
      top: 0;
      left: 0;
      padding: 18px 10%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(15, 23, 42, 0.9);
      backdrop-filter: blur(10px);
      z-index: 1000;
    }

    .logo {
      font-size: 1.5rem;
      font-weight: 700;
      color: #38bdf8;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 25px;
      transition: 0.3s ease;
      font-weight: 500;
    }

    nav a:hover {
      color: #38bdf8;
    }

    section {
      min-height: 100vh;
      padding: 120px 10% 60px;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 50px;
      flex-wrap: wrap;
    }

    .hero-text {
      flex: 1;
    }

    .hero-text h1 {
      font-size: 3.5rem;
      margin-bottom: 10px;
    }

    .hero-text h1 span {
      color: #38bdf8;
    }

    .hero-text h2 {
      font-size: 1.5rem;
      font-weight: 400;
      margin-bottom: 20px;
      color: #cbd5e1;
    }

    .hero-text p {
      max-width: 600px;
      margin-bottom: 30px;
      color: #94a3b8;
    }

    .btn {
      display: inline-block;
      padding: 12px 28px;
      background: #38bdf8;
      color: #0f172a;
      border-radius: 10px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s ease;
    }

    .btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 20px rgba(56, 189, 248, 0.3);
    }

    .hero-image {
      flex: 1;
      display: flex;
      justify-content: center;
    }

    .hero-image img {
      width: 320px;
      height: 320px;
      object-fit: cover;
      border-radius: 50%;
      border: 5px solid #38bdf8;
      box-shadow: 0 0 40px rgba(56, 189, 248, 0.4);
    }

    .section-title {
      font-size: 2.3rem;
      margin-bottom: 40px;
      text-align: center;
      color: #38bdf8;
    }

    .about-content {
      text-align: center;
      max-width: 800px;
      margin: auto;
      color: #cbd5e1;
    }

    .skills-grid,
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }

    .skill-card,
    .project-card {
      background: #1e293b;
      padding: 25px;
      border-radius: 18px;
      transition: 0.3s ease;
      border: 1px solid transparent;
    }

    .skill-card:hover,
    .project-card:hover {
      transform: translateY(-5px);
      border-color: #38bdf8;
    }

    .skill-card h3,
    .project-card h3 {
      margin-bottom: 10px;
      color: #38bdf8;
    }

    .project-card p,
    .skill-card p {
      color: #cbd5e1;
      font-size: 0.95rem;
    }

    .contact {
      text-align: center;
    }

    .contact p {
      margin-bottom: 20px;
      color: #cbd5e1;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #020617;
      color: #94a3b8;
    }

    @media (max-width: 768px) {
      .hero {
        flex-direction: column-reverse;
        text-align: center;
      }

      .hero-text h1 {
        font-size: 2.5rem;
      }

      nav {
        display: none;
      }
    }
  </style></head>
<body>  <header>
    <div class="logo">MyPortfolio</div><nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>

  </header>  <section id="home" class="hero">
    <div class="hero-text">
      <h1>Hi, I'm <span>Abdul Qudoos</span></h1>
      <h2>Creative Developer & Designer</h2><p>
    I create modern, responsive, and visually appealing websites. Passionate about aesthetics, smooth experiences, and bringing creative ideas to life through code and design.
  </p>

  <a href="#contact" class="btn">Hire Me</a>
</div>

<div class="hero-image">
  <!-- Put your profile picture named "2352.jpg" in the same folder as this HTML file -->
  <img src="2352.jpg" alt="Abdul Qudoos Profile Picture">
</div>

  </section>  <section id="about">
    <h2 class="section-title">About Me</h2><div class="about-content">
  <p>
    I'm Abdul Qudoos, a passionate creator who enjoys building stylish and functional websites. I love designing modern user experiences and turning imagination into reality with creativity and code.
  </p>
</div>

  </section>  <section id="skills">
    <h2 class="section-title">Skills</h2><div class="skills-grid">
  <div class="skill-card">
    <h3>HTML5</h3>
    <p>Semantic and accessible website structure.</p>
  </div>

  <div class="skill-card">
    <h3>CSS3</h3>
    <p>Responsive layouts, animations, and modern styling.</p>
  </div>

  <div class="skill-card">
    <h3>JavaScript</h3>
    <p>Interactive and dynamic user experiences.</p>
  </div>

  <div class="skill-card">
    <h3>UI/UX Design</h3>
    <p>Clean and user-friendly interfaces.</p>
  </div>
</div>

  </section>  <section id="projects">
    <h2 class="section-title">Projects</h2><div class="projects-grid">
  <div class="project-card">
    <h3>Yashfeen's Birthday</h3>
    <p>A beautifully designed birthday project made with creativity, emotions, and modern web styling.</p>
  </div>

  <div class="project-card">
    <h3>E-Commerce UI</h3>
    <p>A responsive shopping website interface with sleek design.</p>
  </div>

  <div class="project-card">
    <h3>Weather App</h3>
    <p>A simple weather app using API integration and modern UI.</p>
  </div>
</div>

  </section>  <section id="contact" class="contact">
    <h2 class="section-title">Contact Me</h2><p>Email: qudosmale@gmail.com</p>
<p>Instagram: @qudoos_1136 → @caffeen__</p>

<a href="mailto:qudosmale@gmail.com" class="btn">Send Email</a>

  </section>  <footer>
    <p>© 2026 Abdul Qudoos | All Rights Reserved</p>
  </footer></body>
</html>
