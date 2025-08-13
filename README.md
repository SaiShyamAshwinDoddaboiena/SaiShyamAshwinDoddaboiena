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

  <!-- Featured Projects -->
  <section class="bg-white dark:bg-gray-800 py-10">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-semibold mb-6">Featured Projects</h2>
      <div class="grid md:grid-cols-2 gap-6">

        <!-- Health Insurance Claims Analyzer -->
        <div class="project-card bg-gray-50 dark:bg-gray-900 p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-bold mb-2">🔎 Health Insurance Claims Analyzer</h3>
          <p class="text-gray-700 dark:text-gray-300">
            NLP-powered Streamlit app to categorize, prioritize, and extract sentiment from health insurance claim inquiries using Hugging Face models.
          </p>
        </div>

        <!-- Sentiment Analysis with BERT -->
        <div class="project-card bg-gray-50 dark:bg-gray-900 p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-bold mb-2">🗣️ Sentiment Analysis with BERT</h3>
          <p class="text-gray-700 dark:text-gray-300">
            Fine-tuned BERT model to classify customer reviews with real-time deployment for e-commerce insights.
          </p>
        </div>

        <!-- AI-Powered E-Commerce Chatbot -->
        <div class="project-card bg-gray-50 dark:bg-gray-900 p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-bold mb-2">🤖 AI-Powered E-Commerce Chatbot</h3>
          <p class="text-gray-700 dark:text-gray-300">
            GenAI chatbot using LangChain and OpenAI API to recommend products, resolve queries, and personalize user experiences.
          </p>
        </div>

        <!-- Streamlit + FastAPI AI Stack -->
        <div class="project-card bg-gray-50 dark:bg-gray-900 p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-bold mb-2">⚡ Streamlit + FastAPI AI Stack</h3>
          <p class="text-gray-700 dark:text-gray-300">
            Full-stack projects showcasing FastAPI for backend LLMs and Streamlit for interactive demos and dashboards.
          </p>
        </div>

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
  </script>

</body>
</html>
