# modmate-site
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ModMate for Xbox</title>
<style>
  @import url('[fonts.googleapis.com](https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Inter:wght@300;600&display=swap)');

  body {
    margin: 0;
    font-family: Inter, sans-serif;
    background: #0a0a0e;
    color: #fff;
  }

  header {
    padding: 25px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .logo {
    font-family: Orbitron, sans-serif;
    font-size: 32px;
    font-weight: 700;
    color: #00ff9d;
    letter-spacing: 2px;
  }

  nav a {
    color: #ccc;
    margin-left: 25px;
    text-decoration: none;
    transition: 0.2s;
  }
  nav a:hover { color: #00ff9d; }

  .hero {
    padding: 120px 20px;
    text-align: center;
    background: radial-gradient(circle at center, #1d1f2b, #0a0a0e 70%);
  }

  .hero h1 {
    font-family: Orbitron, sans-serif;
    font-size: 60px;
    margin-bottom: 10px;
    color: #00ffcb;
    text-shadow: 0 0 20px #00ffcb66;
  }

  .hero p {
    font-size: 22px;
    color: #aaa;
    max-width: 600px;
    margin: 0 auto 40px;
  }

  .cta-btn {
    display: inline-block;
    padding: 16px 35px;
    font-size: 20px;
    border-radius: 8px;
    text-decoration: none;
    background: #00ff9d;
    color: #0a0a0e;
    font-weight: 700;
    transition: 0.2s;
  }
  .cta-btn:hover { background: #00ffcb; }

  .section {
    padding: 80px 20px;
    max-width: 900px;
    margin: auto;
  }

  .features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 25px;
    margin-top: 40px;
  }

  .feature-card {
    background: #14141b;
    border: 1px solid #1f2330;
    border-radius: 12px;
    padding: 25px;
    transition: 0.25s;
  }
  .feature-card:hover {
    border-color: #00ff9d;
    transform: translateY(-4px);
  }

  footer {
    text-align: center;
    padding: 30px;
    color: #666;
    margin-top: 40px;
    font-size: 14px;
  }
</style>
</head>
<body>

<header>
  <div class="logo">ModMate</div>
  <nav>
    <a href="#features">Features</a>
    <a href="#download">Download</a>
    <a href="#about">About</a>
  </nav>
</header>

<section class="hero">
  <h1>ModMate for Xbox</h1>
  <p>The ultimate companion for modding, tweaking, and optimizing your Xbox experience with style.</p>
  <a class="cta-btn" href="#download">Get Started</a>
</section>

<section id="features" class="section">
  <h2>Features</h2>
  <div class="features">
    <div class="feature-card">
      <h3>Instant Mod Switching</h3>
      <p>Swap configurations on the fly without restarting games or apps.</p>
    </div>

    <div class="feature-card">
      <h3>Performance Boosts</h3>
      <p>Smart tweaks that push your system while keeping things stable.</p>
    </div>

    <div class="feature-card">
      <h3>Clean UI</h3>
      <p>Slick cyber‑themed interface made for fast, intuitive use.</p>
    </div>

    <div class="feature-card">
      <h3>Cloud Sync</h3>
      <p>Carry your mod profiles across any Xbox you sign in on.</p>
    </div>
  </div>
</section>

<section id="download" class="section">
  <h2>Download ModMate</h2>
  <p>Available soon on the Microsoft Store for Xbox.</p>
  <a class="cta-btn" href="#">Notify Me</a>
</section>

<section id="about" class="section">
  <h2>About ModMate</h2>
  <p>ModMate is designed to give power users and casual players the cleanest, fastest way to manage enhancements on Xbox—no clutter, no bullshit, just power and control.</p>
</section>

<footer>© 2026 ModMate. All rights reserved.</footer>

</body>
</html>
