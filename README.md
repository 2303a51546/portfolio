<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Srinithya Polneni | Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Poppins:wght@400;600&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      font-family: 'Poppins', sans-serif;
      background: radial-gradient(circle, #ffdde1, #ee9ca7);
      overflow-x: hidden;
    }

    body::before {
      content: "";
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: url('https://www.transparenttextures.com/patterns/bubbles.png');
      opacity: 0.15;
      z-index: -1;
      animation: float 20s linear infinite;
    }

    @keyframes float {
      0% { background-position: 0 0; }
      100% { background-position: 100% 100%; }
    }

    header {
      background: linear-gradient(135deg, #c94f7c, #7e3f8f);
      color: white;
      text-align: center;
      padding: 5rem 1rem 3rem;
      box-shadow: 0 0 40px #ffccff;
    }

    header h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3.1rem;
      color: #fff;
      text-shadow: 0 0 15px #fff, 0 0 30px #ff6ec7;
      animation: glowText 1.5s ease-in-out infinite alternate;
    }

    @keyframes glowText {
      from {
        text-shadow: 0 0 10px #ffccff;
      }
      to {
        text-shadow: 0 0 20px #fff, 0 0 35px #ff6ec7;
      }
    }

   .typewriter {
  font-size: 1.3rem;
  margin-top: 1rem;
  white-space: nowrap;
  overflow: hidden;
  width: 0;
  margin-inline: auto;
  animation: typing 4s steps(40, end) 1s infinite alternate;
  border-right: none; /* Cursor removed */
}

@keyframes typing {
  0% {
    width: 0;
  }
  100% {
    width: 40ch;
  }
}


    nav {
      margin-top: 2rem;
    }

    nav a {
      color: white;
      font-weight: bold;
      text-decoration: none;
      margin: 0 1rem;
      padding: 0.5rem 1rem;
      border-radius: 20px;
      transition: 0.3s;
      background: rgba(255,255,255,0.1);
    }

    nav a:hover {
      background: #fff;
      color: #c94f7c;
      box-shadow: 0 0 10px #fff;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 2rem 1rem;
    }

    .photo-box {
      text-align: center;
      margin-bottom: 2rem;
      perspective: 1000px;
    }

    .photo-box img {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      border: 5px solid white;
      box-shadow: 0 0 25px rgba(255, 0, 170, 0.325);
      object-fit: cover;
      transition: transform 0.5s ease-in-out;
    }

    .photo-box img:hover {
      transform: rotateY(10deg) scale(1.1);
    }

    section {
      margin-bottom: 2.5rem;
      animation: fadeInUp 1.5s ease;
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h2 {
      font-size: 2rem;
      color: #7e3f8f;
      margin-bottom: 1rem;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .card, .skill-list, .achievement-list {
      background-color: white;
      padding: 1.2rem;
      border-radius: 12px;
      border-left: 6px solid #ff6ec7;
      box-shadow: 0 0 20px rgba(0,0,0,0.1);
      margin-bottom: 1rem;
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.03);
      box-shadow: 0 0 25px rgba(255, 0, 170, 0.3);
    }

    ul {
      padding-left: 1.5rem;
    }

    footer {
      background-color: #7e3f8f;
      color: white;
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
    }

    a {
      color: #7e3f8f;
    }

    .btn-glow {
      display: inline-block;
      background: white;
      color: #7e3f8f;
      font-weight: bold;
      padding: 0.7rem 2rem;
      margin-top: 1rem;
      border-radius: 25px;
      box-shadow: 0 0 15px #fff;
      transition: all 0.3s ease-in-out;
      text-decoration: none;
    }

    .btn-glow:hover {
      background-color: #ff6ec7;
      color: white;
      box-shadow: 0 0 25px #ff6ec7;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.3rem;
      }

      nav a {
        display: block;
        margin: 0.4rem auto;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Srinithya Polneni</h1>
    <div class="typewriter">Web Developer | Learner | Dreamer</div>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#achievements">Achievements</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container">

    <div class="photo-box">
      <img src="Srinithya.jpg" alt="Srinithya.jpg" width="200">

    </div>

    <section id="about">
      <h2><i class="fas fa-user"></i> About Me</h2>
      <div class="card">
        <p>I am a passionate BTech student exploring Web Development and developing skills . I aim to build impactful applications and keep learning every day. My journey includes working on fun web projects, solving problems, and gaining certifications from top tech platforms.</p>
      </div>
    </section>

    <section id="skills">
      <h2><i class="fas fa-code"></i> Skills</h2>
      <div class="skill-list">
        <ul>
          <li>HTML, CSS, JavaScript</li>
          <li>Responsive Web Design</li>
          <li>C++, Python (Basics), DSA(Basics)</li>
          <li>SQL, PL/SQL</li>
          <li>GitHub</li>
        </ul>
      </div>
    </section>

    <section id="achievements">
      <h2><i class="fas fa-trophy"></i> Achievements</h2>
      <div class="achievement-list">
        <ul>
          <li><strong>CISCO:</strong> Data Analytics Essentials – Nov 2024</li>
          <li><strong>AWS Academy:</strong> Data Engineering – Mar 2025</li>
          <li><strong>AWS Academy:</strong> Cloud Foundations – Mar 2025</li>
          <li><strong>Marketing Club:</strong> Movie Buzz – Sep 2023</li>
          <li><strong>Flipkart:</strong> Runway Session 5 – Mar 2025</li>
        </ul>
      </div>
    </section>

    <section id="projects">
      <h2><i class="fas fa-diagram-project"></i> Projects</h2>
      <div class="card">
        <h3>Portfolio Website</h3>
        <p>A responsive personal site showcasing my work and contact details. Fully built with HTML and CSS.</p>
      </div>
      <div class="card">
        <h3>Quiz Platform</h3>
        <p>An educational quiz system with difficulty levels, navigation, and result analysis. Built for practice and learning.</p>
      </div>
      <div class="card">
  <h3>Heart Disease Prediction</h3>
  <p>A machine learning-based system that predicts the risk of heart disease using health-related features. Built to assist early diagnosis and improve healthcare decisions.</p>
</div>

    </section>

    <section id="contact">
      <h2><i class="fas fa-envelope"></i> Contact</h2>
      <div class="card">
        <p><strong><i class="fas fa-envelope"></i> Email:</strong> <a href="mailto:madhurimandala11@gmail.com">madhurimandala11@gmail.com</a></p>
        <p><strong><i class="fab fa-linkedin"></i> LinkedIn:</strong> 
  <a href="https://www.linkedin.com/in/madhuri-mandala-4238822ba" target="_blank" rel="noopener noreferrer">
    linkedin.com/in/madhuri-mandala-4238822ba
  </a>
</p>

       <p><strong><i class="fab fa-github"></i> GitHub:</strong> 
  <a href="https://github.com/2303a51546/srinithya polneni.git" target="_blank" rel="noopener noreferrer">
    github.com/2303a515465srinithya
  </a>
</p>

        <p><strong><i class="fas fa-file-pdf"></i> Resume:</strong> 
  <a href="https://github.com/2303a51546/portfolio/edit/main/README.md" 
     target="_blank" rel="noopener noreferrer">
    View My Resume
  </a>
</p>

      </div>
    </section>

  </div>

  <footer>
  <p>&copy; 2025 Sri nithya| Designed with passion 🎨 and creativity ✨</p>
</footer>


</body>
</html>
