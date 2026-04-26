<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
    }

    header {
      padding: 20px;
      text-align: center;
      background: #020617;
    }

    h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    .hero {
      text-align: center;
      padding: 60px 20px;
    }

    .hero h2 {
      font-size: 2rem;
      color: #38bdf8;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }

    .card {
      background: #1e293b;
      padding: 20px;
      border-radius: 10px;
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
      background: #334155;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #020617;
    }
  </style>
</head>

<body>

<header>
  <h1>Your Name</h1>
  <p>Web Developer 🚀</p>
</header>

<section class="hero">
  <h2>Hi, I'm Your Name 👋</h2>
  <p>I build websites and cool projects.</p>
</section>

<section class="projects">
  <div class="card">
    <h3>Project 1</h3>
    <p>Describe your project here.</p>
  </div>

  <div class="card">
    <h3>Project 2</h3>
    <p>Describe your project here.</p>
  </div>

  <div class="card">
    <h3>Project 3</h3>
    <p>Describe your project here.</p>
  </div>
</section>

<footer>
  <p>© 2026 Your Name</p>
</footer>

</body>
</html>
