<meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ModMate</title>
  <script src="[cdn.tailwindcss.com](https://cdn.tailwindcss.com)"></script>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Smooth fade-in animation */
    .fade-in {
@@ -31,7 +31,7 @@
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans"> <!-- Removed fade-in from body -->
<body class="bg-gray-900 text-white font-sans">

  <!-- Hero Section -->
  <section class="min-h-screen flex flex-col justify-center items-center text-center px-4 fade-in">
@@ -63,8 +63,8 @@
      <p>1. Open the installer and follow the on-screen instructions.</p>
      <p>2. Launch ModMate and select your downloader file.</p>
      <p>3. Browse and install mods directly from the app.</p>
      <p>4. Inject them into wormer <!-- Consider elaborating on "wormer" --></p>
    </div> <!-- Added missing closing div here -->
      <p>4. Inject them into your game files.</p>
    </div>
    <div class="max-w-2xl mx-auto text-gray-300 space-y-4">
      <p>5. Reinstall your game using the "reinstall method" and enjoy!</p>
      <p class="mt-4">For a full video guide, watch the tutorial below.</p>
@@ -73,19 +73,19 @@
      <a href="#" class="bg-green-500 hover:bg-green-600 px-8 py-3 rounded-2xl shadow glow transition">Download ModMate</a>
    </div>
    <div class="flex justify-center mt-10">
      <iframe class="rounded-2xl shadow-lg hover:scale-105 transition" width="560" height="315" src="[youtube.com](https://www.youtube.com/embed/YOUR_ACTUAL_VIDEO_ID)" title="YouTube video player" frameborder="0" allowfullscreen></iframe> <!-- Replaced VIDEO_ID -->
      <iframe class="rounded-2xl shadow-lg hover:scale-105 transition" width="560" height="315" src="https://www.youtube.com/embed/YOUR_ACTUAL_VIDEO_ID" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </section>

  <!-- Discord -->
  <section class="py-16 text-center fade-in">
    <h2 class="text-3xl font-bold mb-4">Join the Community</h2>
    <p class="text-gray-400 mb-6">Get help, share mods, and connect with others.</p>
    <a href="[discord.gg](https://discord.gg/vBjb9Fc8pA)" class="bg-indigo-500 hover:bg-indigo-600 px-8 py-3 rounded-2xl shadow glow transition">Join Discord</a> <!-- Corrected href -->
    <a href="https://discord.gg/vBjb9Fc8pA" class="bg-indigo-500 hover:bg-indigo-600 px-8 py-3 rounded-2xl shadow glow transition">Join Discord</a>
  </section>
  <!-- Footer -->
  <footer class="py-6 text-center text-gray-500 fade-in">
    <p> 2026 ModMate. All rights reserved.</p>
    <p>&copy; 2026 ModMate. All rights reserved.</p>
  </footer>

  <script>
