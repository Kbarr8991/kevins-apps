<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Apps Hub - Kevin</title>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #0f172a;
      color: white;
      text-align: center;
      padding: 80px 20px;
      margin: 0;
    }
    h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }
    p.subtitle {
      font-size: 1.3rem;
      opacity: 0.8;
      margin-bottom: 60px;
    }
    .apps {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
      max-width: 1100px;
      margin: 0 auto;
    }
    .app-card {
      background: #1e2937;
      padding: 40px 25px;
      border-radius: 16px;
      text-decoration: none;
      color: white;
      transition: all 0.3s ease;
    }
    .app-card:hover {
      background: #334155;
      transform: translateY(-10px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    }
    .app-card h2 {
      margin: 0 0 15px 0;
      font-size: 1.7rem;
    }
    .app-card p {
      margin: 0;
      opacity: 0.75;
      font-size: 1.1rem;
    }
  </style>
</head>
<body>
  <h1>🚀 My Apps Hub</h1>
  <p class="subtitle">All my apps in one place</p>

  <div class="apps">
    <a href="https://YOUR-APP-1.vercel.app" class="app-card" target="_blank">
      <h2>App Name 1</h2>
      <p>Short description of what this app does</p>
    </a>

    <a href="https://YOUR-APP-2.vercel.app" class="app-card" target="_blank">
      <h2>App Name 2</h2>
      <p>Short description of what this app does</p>
    </a>

    <!-- Add more cards here if you have more apps -->
    <!-- Example:
    <a href="https://third-app.vercel.app" class="app-card" target="_blank">
      <h2>App Name 3</h2>
      <p>Description here</p>
    </a>
    -->
  </div>
</body>
</html>
