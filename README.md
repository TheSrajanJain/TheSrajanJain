<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Srajan's Portfolio 💼</title>
  <meta name="description" content="Srajan Jain's personal portfolio – Developer, coder, and UI enthusiast.">
  <meta name="keywords" content="Srajan Jain, developer, portfolio, coding, UI, frontend, backend">
  <meta name="author" content="Srajan Jain">
  <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/1055/1055646.png" />
  <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css"/>
  <style>
    :root {
      --primary: #00f5d4;
      --dark: #0f0f0f;
      --glass: rgba(255, 255, 255, 0.05);
    }

    * {
      margin: 0; padding: 0; box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #0f0f0f, #1c1c1c);
      color: #fff;
      line-height: 1.6;
      scroll-behavior: smooth;
    }

    header {
      position: fixed;
      top: 0;
      width: 100%;
      padding: 1rem 2rem;
      background: var(--glass);
      backdrop-filter: blur(10px);
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1000;
      border-bottom: 1px solid #222;
    }

    header h1 {
      color: var(--primary);
      font-size: 1.5rem;
    }

    nav a {
      margin-left: 20px;
      color: #fff;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--primary);
    }

    section {
      padding: 120px 20px 80px;
      max-width: 1000px;
      margin: auto;
      scroll-margin-top: 100px;
    }

    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      background: url('https://www.transparenttextures.com/patterns/stardust.png');
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    .hero span {
      color: var(--primary);
      animation: glow 2s infinite alternate;
    }

    .hero p {
      font-size: 1.3rem;
      margin-bottom: 25px;
    }

    .btn {
      background: var(--primary);
      color: black;
      padding: 12px 25px;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: transform 0.3s ease, background 0.3s ease;
    }

    .btn:hover {
      transform: scale(1.05);
      background: #00c9a7;
    }

    @keyframes glow {
      from { text-shadow: 0 0 10px var(--primary); }
      to { text-shadow: 0 0 20px var(--primary); }
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project {
      background: var(--glass);
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      border: 1px solid #222;
      transition: transform 0.3s ease;
    }

    .project:hover {
      transform: translateY(-10px);
      background: var(--primary);
      color: black;
    }

    .contact form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: auto;
    }

    .contact label {
      font-weight: 500;
      margin-bottom: -10px;
      font-size: 0.95rem;
    }

    .contact input, .contact textarea {
      padding: 10px;
      border-radius: 5px;
      border: none;
    }

    .contact button {
      background: var(--primary);
      color: black;
      padding: 10px;
      border: none;
      cursor: pointer;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      font-size: 0.9rem;
      color: #aaa;
    }

    /* Mobile responsive */
    @media (max-width: 600px) {
      header { flex-direction: column; align-items: flex-start; }
      .hero h1 { font-size: 2rem; }
      .hero p { font-size: 1rem; }
    }
  </style>
</head>
<body>

  <header>
    <h1><span aria-hidden="true">👨‍💻</span> Srajan Jain</h1>
    <nav>
      <a href="#home"><span aria-hidden="true">🏠</span> Home</a>
      <a href="#projects"><span aria-hidden="true">🛠</span> Projects</a>
      <a href="#about"><span aria-hidden="true">📘</span> About</a>
      <a href="#contact"><span aria-hidden="true">✉️</span> Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h1>Hey, I'm <span>Srajan Jain</span> <span aria-hidden="true">👋</span></h1>
    <p>I build awesome codes and frontend experiences. ✨</p>
    <a href="#projects" class="btn"><span aria-hidden="true">🚀</span> View My Work</a>
  </section>

  <section id="projects" data-aos="fade-up">
    <h2><span aria-hidden="true">🛠</span> My Projects</h2>
    <div class="project-grid">
      <div class="project">
        <h3>Java By Srajan Jain</h3>
        <p>A repository where beginners can take help to sort out their coding problems and understand basic programming concepts.</p>
        <a href="https://github.com/TheSrajanJain/Java-By-Srajan-Jain" target="_blank">View on GitHub</a>
      </div>
      <div class="project">
        <h3>C Programming By Srajan Jain</h3>
        <p>Comprehensive C programming examples and exercises for learners.</p>
        <a href="https://github.com/TheSrajanJain/C-Programming-By-Srajan-Jain" target="_blank">View on GitHub</a>
      </div>
      <div class="project">
        <h3>HTML and CSS by Srajan Jain</h3>
        <p>Projects and examples focusing on HTML and CSS for frontend development.</p>
        <a href="https://github.com/TheSrajanJain/HTML-and-CSS-by-Srajan-Jain" target="_blank">View on GitHub</a>
      </div>
      <div class="project">
        <h3>Cpp Programming by Srajan Jain</h3>
        <p>C++ programming resources and code samples for learners.</p>
        <a href="https://github.com/TheSrajanJain/Cpp-Programming-by-Srajan-Jain" target="_blank">View on GitHub</a>
      </div>
    </div>
  </section>

  <section id="about" data-aos="fade-right">
    <h2><span aria-hidden="true">📘</span> About Me</h2>
    <p>Hi! I'm Srajan Jain, a backend as well as frontend developer based in India 🇮🇳. I specialize in crafting responsive codes, commercial-level coding projects, and beautiful UIs that deliver great user experiences.</p>
  </section>

  <section id="contact" class="contact" data-aos="fade-left">
    <h2><span aria-hidden="true">✉️</span> Contact Me</h2>
    <form id="contactForm">
      <label for="name">Your Name</label>
      <input type="text" id="name" placeholder="Your Name" required />

      <label for="email">Your Email</label>
      <input type="email" id="email" placeholder="Your Email" required />

      <label for="message">Your Message</label>
      <textarea id="message" placeholder="Your Message" rows="4" required></textarea>

      <button type="submit">📨 Send Message</button>
    </form>
    <p id="responseMsg" style="text-align:center; margin-top:10px;"></p>
  </section>

  <footer>
    <p>© 2025 Srajan Jain. Built with 💙 and ☕</p>
  </footer>

  <!-- Animation Libraries -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({ duration: 1000 });

    document.getElementById("contactForm").addEventListener("submit", function (e) {
      e.preventDefault();
      document.getElementById('responseMsg').textContent = "✅ Message sent successfully!";
      this.reset();
    });
  </script>

</body>
</html>
