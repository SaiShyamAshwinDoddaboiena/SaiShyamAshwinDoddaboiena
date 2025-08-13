<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sai Shyam Ashwin Doddaboiena | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: { extend: {} },
      plugins: [],
    }
  </script>
</head>
<body class="bg-gray-50 text-gray-900 dark:bg-gray-900 dark:text-gray-100 font-sans transition-colors duration-300">

  <!-- Header -->
  <header class="bg-white dark:bg-gray-800 shadow-md sticky top-0 z-50">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Sai Shyam Ashwin Doddaboiena</h1>
      <div class="flex items-center gap-4">
        <a href="https://www.linkedin.com/in/saishyamashwin/" target="_blank" class="text-blue-600 dark:text-blue-400 hover:underline">LinkedIn</a>
        <button id="dark-toggle" class="bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-200 px-3 py-1 rounded-lg">Dark Mode</button>
      </div>
    </div>
  </header>

  <!-- About Me -->
  <section class="container mx-auto px-6 py-10">
    <h2 class="text-3xl font-semibold mb-4">About Me</h2>
    <p class="text-gray-700 dark:text-gray-300">
      I am a passionate developer and cloud enthusiast with expertise in AI-driven solutions, cloud platforms, and full-stack development. I have hands-on experience building scalable, intelligent applications and deploying them using modern DevOps practices.
    </p>
  </section>

  <!-- Certifications -->
  <section class="bg-white dark:bg-gray-800 py-10">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-semibold mb-4">Certifications</h2>
      <ul class="list-disc list-inside text-gray-700 dark:text-gray-300 space-y-2">
        <li>Microsoft Azure Fundamentals</li>
        <li>AWS Certified Developer – Associate</li>
        <li>SQL & Relational Database Design</li>
        <li>Smart India Hackathon 2019 Finalist – Competed at NIT Trichy</li>
      </ul>
    </div>
  </section>

  <!-- Skills -->
  <section class="container mx-auto px-6 py-10">
    <h2 class="text-3xl font-semibold mb-4">Skills</h2>
    <ul class="flex flex-wrap gap-4">
      <li class="bg-blue-100 dark:bg-blue-800 text-blue-800 dark:text-blue-100 px-4 py-2 rounded-full">AWS</li>
      <li class="bg-blue-100 dark:bg-blue-800 text-blue-800 dark:text-blue-100 px-4 py-2 rounded-full">Azure</li>
      <li class="bg-blue-100 dark:bg-blue-800 text-blue-800 dark:text-blue-100 px-4 py-2 rounded-full">Google Cloud</li>
      <li class="bg-blue-100 dark:bg-blue-800 text-blue-800 dark:text-blue-100 px-4 py-2 rounded-full">OpenAI / Claude / Amazon Bedrock</li>
      <li class="bg-blue-100 dark:bg-blue-800 text-blue-800 dark:text-blue-100 px-4 py-2 rounded-full">React.js / Next.js</li>
      <li class="bg-blue-100 dark:bg-blue-800 text-blue-800 dark:text-blue-100 px-4 py-2 rounded-full">Django / Flask / Node.js</li>
      <li class="bg-blue-100 dark:bg-blue-800 text-blue-800 dark:text-blue-100 px-4 py-2 rounded-full">Docker / Kubernetes / Terraform</li>
      <li class="bg-blue-100 dark:bg-blue-800 text-blue-800 dark:text-blue-100 px-4 py-2 rounded-full">SQL / BigQuery</li>
    </ul>
  </section>

  <!-- Projects -->
  <section class="bg-white dark:bg-gray-800 py-10">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-semibold mb-6">Projects</h2>

      <!-- Filter Buttons -->
      <div class="mb-6 flex flex-wrap gap-3">
        <button class="filter-btn px-3 py-1 rounded-lg bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-100" data-filter="all">All</button>
        <button class="filter-btn px-3 py-1 rounded-lg bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-100" data-filter="AI">AI</button>
        <button class="filter-btn px-3 py-1 rounded-lg bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-100" data-filter="Cloud">Cloud</button>
        <button class="filter-btn px-3 py-1 rounded-lg bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-100" data-filter="Web">Web</button>
      </div>

      <!-- Project Cards -->
      <div class="grid md:grid-cols-2 gap-6">
        <div class="project-card bg-gray-50 dark:bg-gray-900 p-6 rounded-lg shadow-md" data-category="AI Cloud Web">
          <h3 class="text-2xl font-bold mb-2">AI-Powered Smart E-Commerce Platform</h3>
          <p class="text-gray-700 dark:text-gray-300 mb-4">
            Enhances online shopping through AI-driven recommendations, a smart chatbot, and predictive inventory management.
          </p>
          <h4 class="font-semibold">Technologies & Tools:</h4>
          <p class="text-gray-700 dark:text-gray-300 mb-2">
            AI: OpenAI, Claude, Amazon Bedrock<br>
            Cloud: AWS, Google Cloud, Azure, Google BigQuery<br>
            DevOps: Docker, Kubernetes, Terraform<br>
            Frontend: React.js, Next.js<br>
            Backend: Django, Flask, Node.js
          </p>
          <h4 class="font-semibold">Key Features:</h4>
          <ul class="list-disc list-inside text-gray-700 dark:text-gray-300 space-y-1">
            <li>Personalized shopping experience with AI recommendations</li>
            <li>Real-time customer support via smart chatbot</li>
            <li>Optimized stock levels using predictive analytics</li>
            <li>Fully scalable and resilient architecture across multiple cloud providers</li>
          </ul>
        </div>

        <!-- You can duplicate the above card for more projects -->
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-100 dark:bg-gray-900 py-6 mt-10">
    <div class="container mx-auto px-6 text-center text-gray-600 dark:text-gray-400">
      &copy; 2025 Sai Shyam Ashwin Doddaboiena. All rights reserved.
    </div>
  </footer>

  <!-- JS -->
  <script>
    // Dark Mode Toggle
    const toggle = document.getElementById('dark-toggle');
    toggle.addEventListener('click', () => {
      document.documentElement.classList.toggle('dark');
      toggle.textContent = document.documentElement.classList.contains('dark') ? 'Light Mode' : 'Dark Mode';
    });

    // Project Filter
    const filterBtns = document.querySelectorAll('.filter-btn');
    const projects = document.querySelectorAll('.project-card');

    filterBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        const filter = btn.getAttribute('data-filter');

        projects.forEach(project => {
          if(filter === 'all' || project.dataset.category.includes(filter)) {
            project.style.display = 'block';
          } else {
            project.style.display = 'none';
          }
        });
      });
    });
  </script>

</body>
</html>
