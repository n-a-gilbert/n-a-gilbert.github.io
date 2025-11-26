# More coming soon!

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>My GitHub Pages Site</title>
  <meta name="description" content="A simple static site hosted with GitHub Pages" />

  <!-- Fav icon (optional) -->
  <link rel="icon" href="data:;base64,iVBORw0KGgo=">

  <!-- Styles -->
  <link rel="stylesheet" href="styles.css" />

  <!-- Social preview (optional) -->
  <meta property="og:title" content="My GitHub Pages Site">
  <meta property="og:description" content="A simple static site hosted with GitHub Pages">
</head>
<body>
  <header class="site-header">
    <div class="container">
      <a class="brand" href="/">MySite</a>
      <button id="navToggle" class="nav-toggle" aria-expanded="false" aria-controls="mainNav">
        ☰
      </button>
      <nav id="mainNav" class="site-nav" aria-label="Main navigation">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main id="home" class="container hero">
    <h1>Hello — welcome to my GitHub Pages site</h1>
    <p class="lead">This is a minimal, responsive static site. Edit <code>index.html</code>, <code>styles.css</code>, and push to GitHub.</p>
    <p><a class="btn" href="#projects">See projects</a></p>
  </main>

  <section id="about" class="container card">
    <h2>About</h2>
    <p>Short description about you or the project. Add more sections or pages as you like.</p>
  </section>

  <section id="projects" class="container grid">
    <article class="card">
      <h3>Project A</h3>
      <p>Summary of a project. Link to repo or demo.</p>
      <p><a href="https://github.com/" target="_blank" rel="noopener">View on GitHub →</a></p>
    </article>

    <article class="card">
      <h3>Project B</h3>
      <p>Another project or showcase item.</p>
      <p><a href="#" rel="noopener">Details →</a></p>
    </article>
  </section>

  <footer id="contact" class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Your Name · <a href="mailto:you@example.com">you@example.com</a></p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
