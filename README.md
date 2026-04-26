<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #0f172a;
  color: white;
}

/* Navbar */
nav {
  display: flex;
  justify-content: space-between;
  padding: 20px 40px;
  background: #020617;
}

nav a {
  color: #38bdf8;
  text-decoration: none;
  margin-left: 20px;
}

/* Hero */
.hero {
  text-align: center;
  padding: 80px 20px;
}

.hero h1 {
  font-size: 3rem;
}

.hero span {
  color: #38bdf8;
}

/* Section */
.section {
  padding: 50px 20px;
  max-width: 1000px;
  margin: auto;
}

h2 {
  color: #38bdf8;
}

/* Projects */
.projects {
  display: grid;
  gap: 20px;
}

.card {
  background: #1e293b;
  padding: 20px;
  border-radius: 10px;
}

/* Skills */
.skills span {
  display: inline-block;
  background: #334155;
  padding: 8px 12px;
  margin: 5px;
  border-radius: 5px;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background: #020617;
}
</style>
</head>

<body>

<nav>
  <div><b>Your Name</b></div>
  <div>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<section class="hero">
  <h1>Hi, I'm <span>Your Name</span> 👋</h1>
  <p>Aspiring Web Developer building real-world projects</p>
</section>

<section id="about" class="section">
  <h2>About Me</h2>
  <p>I am learning web development and building projects using HTML, CSS, and JavaScript.</p>

  <div class="skills">
    <span>HTML</span>
    <span>CSS</span>
    <span>JavaScript</span>
  </div>
</section>

<section id="projects" class="section">
  <h2>Projects</h2>

  <div class="projects">
    <div class="card">
      <h3>Portfolio Website</h3>
      <p>This personal portfolio built using HTML and CSS.</p>
    </div>

    <div class="card">
      <h3>Weather App</h3>
      <p>Fetches real-time weather using API.</p>
    </div>

  </div>
</section>

<section id="contact" class="section">
  <h2>Contact</h2>
  <p>Email: your@email.com</p>
  <p>GitHub: github.com/your-username</p>
</section>

<footer>
  <p>© 2026 Your Name</p>
</footer>

</body>
</html>
