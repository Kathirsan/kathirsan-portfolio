# kathirsan-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vivekanantharaja Kathirsan - Portfolio</title>
  <link rel="stylesheet" href="styles.css"/>
  <script defer src="main.js"></script>
</head>
<body>
  <!-- Navigation -->
  <header class="navbar">
    <div class="container nav-inner">
      <div class="brand">VK Portfolio</div>
      <nav class="nav-links">
        <a href="#home">Home</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#experience">Experience</a>
        <a href="#achievements">Achievements</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="hero container">
    <div class="hero-text">
      <h1>Hello, I'm <span>Kathirsan</span></h1>
      <p>B.Sc. Software Engineering Undergraduate at Sabaragamuwa University of Sri Lanka</p>
      <p class="career">Career Objective: To utilize my free time productively by engaging in part-time work, while developing my skills and gaining professional experience.</p>
    </div>
    <div class="hero-img">
      <img src="assets/profile.jpg" alt="Profile Photo"/>
    </div>
  </section>

  <!-- Education -->
  <section id="education" class="section container">
    <h2>Education</h2>
    <ul>
      <li><strong>B.Sc. Software Engineering</strong>, Sabaragamuwa University (2nd Year)</li>
      <li><strong>A/L (2022/23)</strong> - Combined Maths A, Chemistry A, Physics C</li>
      <li><strong>O/L (2019)</strong> - 9 Subjects including Mathematics A, Science B, Commerce A</li>
    </ul>
  </section>

  <!-- Skills -->
  <section id="skills" class="section container">
    <h2>Skills</h2>
    <div class="grid">
      <span class="tag">Java</span>
      <span class="tag">HTML</span>
      <span class="tag">CSS</span>
      <span class="tag">JavaScript</span>
      <span class="tag">MySQL</span>
      <span class="tag">Problem Solving</span>
      <span class="tag">Logical Thinking</span>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="section container">
    <h2>Projects</h2>
    <div class="card">
      <h3>Event Webpage</h3>
      <p>Created an HTML webpage for displaying event details, images, and contact information.</p>
      <p><em>GitHub link</em>: <span class="meta">Add later</span></p>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience" class="section container">
    <h2>Experience</h2>
    <div class="card">
      <h3>Airtel Company</h3>
      <p>Customer Service / Sales Support</p>
    </div>
    <div class="card">
      <h3>Chess Team Player</h3>
      <p>Represented University & School in competitions.</p>
    </div>
  </section>

  <!-- Achievements -->
  <section id="achievements" class="section container">
    <h2>Achievements & Activities</h2>
    <ul>
      <li>Represented chess team in competitions.</li>
      <li>Successfully developed HTML event pages.</li>
    </ul>
  </section>

  <!-- Contact -->
  <section id="contact" class="section container">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:vivekanantharajakathirsan2003@gmail.com">vivekanantharajakathirsan2003@gmail.com</a></p>
    <p>Phone: <a href="tel:+94702493178">+94 70 249 3178</a></p>
    <p>Location: Hospital Road, Kondavil East, Kondavil, Sri Lanka</p>
  </section>

  <footer class="footer">
    © 2025 Vivekanantharaja Kathirsan · Built with HTML, CSS & JS
  </footer>
  body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #0b1220;
  color: #e5e7eb;
  line-height: 1.6;
}

.container { max-width: 1000px; margin: auto; padding: 20px; }

.navbar { position: sticky; top:0; background: #0f172a; padding: 10px; }
.nav-inner { display: flex; justify-content: space-between; align-items: center; }
.nav-links a { color: #e5e7eb; margin: 0 10px; text-decoration: none; }
.nav-links a:hover { color: #38bdf8; }

.hero { display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; padding: 50px 20px; }
.hero-text h1 { font-size: 2.5rem; }
.hero-text span { color: #38bdf8; }
.hero-img img { width: 220px; border-radius: 15px; border: 3px solid #2563eb; }

.section { margin: 50px 0; }
.section h2 { color: #38bdf8; }

.grid { display: flex; flex-wrap: wrap; gap: 10px; }
.tag { background: #1e40af; padding: 6px 12px; border-radius: 15px; }

.card { background: #1e293b; padding: 15px; border-radius: 10px; margin: 10px 0; }
.card h3 { margin-top: 0; }

.footer { text-align: center; padding: 20px; background: #0f172a; margin-top: 40px; }
// Smooth scrolling for nav links
document.querySelectorAll('a[href^="#"]').forEach(link => {
  link.addEventListener('click', e => {
    e.preventDefault();
    document.querySelector(link.getAttribute('href')).scrollIntoView({
      behavior: 'smooth'
    });
  });
});

</body>
</html>
