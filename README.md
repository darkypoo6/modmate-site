<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ModMate</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Smooth fade-in animation */
    .fade-in {
      opacity: 0;
      transform: translateY(30px);
      transition: all 0.8s ease;
    }
    .fade-in.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* Button glow */
    .glow:hover {
      box-shadow: 0 0 20px rgba(59,130,246,0.7);
      transform: scale(1.05);
    }

    /* Floating animation */
    .float {
      animation: float 3s ease-in-out infinite;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans">

  <!-- Hero Section -->
  <section class="min-h-screen flex flex-col justify-center items-center text-center px-4 fade-in">
    <h1 class="text-6xl font-bold mb-4 float">ModMate</h1>
    <p class="text-xl text-gray-300 mb-6">The Ultimate Modding Companion</p>
    <a href="#download" class="bg-blue-500 hover:bg-blue-600 px-8 py-3 rounded-2xl shadow-lg glow transition">Get Started</a>
  </section>

  <!-- Features -->
  <section class="py-16 px-6 grid md:grid-cols-3 gap-8">
    <div class="bg-gray-800 p-6 rounded-2xl shadow fade-in hover:scale-105 transition">
      <h2 class="text-2xl font-semibold mb-2">Easy Setup</h2>
      <p class="text-gray-400">Install mods in minutes with our streamlined process.</p>
    </div>
    <div class="bg-gray-800 p-6 rounded-2xl shadow fade-in hover:scale-105 transition">
      <h2 class="text-2xl font-semibold mb-2">Safe & Secure</h2>
      <p class="text-gray-400">All files are verified and safe to use.</p>
    </div>
    <div class="bg-gray-800 p-6 rounded-2xl shadow fade-in hover:scale-105 transition">
      <h2 class="text-2xl font-semibold mb-2">Community Driven</h2>
      <p class="text-gray-400">Join our Discord to connect and share mods.</p>
    </div>
  </section>

  <!-- Instructions -->
  <section id="download" class="py-16 px-6 bg-gray-800 fade-in">
    <h2 class="text-3xl font-bold text-center mb-8">How to Install ModMate</h2>
    <div class="max-w-2xl mx-auto text-gray-300 space-y-4">
      <p>1. Download the ModMate installer using the button below.</p>
      <p>2. Open the installer and follow the on-screen instructions.</p>
      <p>3. Launch ModMate and select your game.</p>
      <p>4. Browse and install mods directly from the app.</p>
      <p>5. Restart your game and enjoy!</p>
      <p class="mt-4">For a full video guide, watch the tutorial below.</p>
    </div>

    <div class="flex justify-center mt-8">
      <a href="#" class="bg-green-500 hover:bg-green-600 px-8 py-3 rounded-2xl shadow glow transition">Download ModMate</a>
    </div>

    <div class="flex justify-center mt-10">
      <iframe class="rounded-2xl shadow-lg hover:scale-105 transition" width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
    </div>
  </section>

  <!-- Discord -->
  <section class="py-16 text-center fade-in">
    <h2 class="text-3xl font-bold mb-4">Join the Community</h2>
    <p class="text-gray-400 mb-6">Get help, share mods, and connect with others.</p>
    <a href="https://discord.gg/YOUR_LINK" class="bg-indigo-500 hover:bg-indigo-600 px-8 py-3 rounded-2xl shadow glow transition">Join Discord</a>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center text-gray-500 fade-in">
    <p> 2026 ModMate. All rights reserved.</p>
  </footer>

  <script>
    // Scroll animation trigger
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
        }
      });
    });

    document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
  </script>

</body>
</html>
