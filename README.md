<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>React Admin UI - Project Overview</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f8f9fb;
      color: #333;
      margin: 0;
      padding: 2rem;
      line-height: 1.6;
    }

    h1, h2 {
      text-align: center;
      color: #2d2d2d;
    }

    h1 {
      margin-bottom: 0;
    }

    h2 {
      margin-top: 3rem;
      border-bottom: 2px solid #eee;
      padding-bottom: 0.3rem;
    }

    p.center {
      text-align: center;
      font-style: italic;
      color: #555;
    }

    ul {
      margin-left: 1.5rem;
    }

    pre {
      background: #e8f0fe;
      padding: 1rem;
      border-radius: 5px;
      overflow-x: auto;
    }

    table {
      border-collapse: collapse;
      width: 100%;
      margin-top: 1rem;
    }

    table, th, td {
      border: 1px solid #ccc;
    }

    th, td {
      padding: 0.75rem;
      text-align: left;
    }

    .tag {
      display: inline-block;
      background: #e0e0e0;
      padding: 0.2rem 0.6rem;
      border-radius: 4px;
      margin-right: 0.5rem;
      font-size: 0.85rem;
    }

    .btn {
      display: inline-block;
      background: #007bff;
      color: #fff;
      padding: 0.6rem 1.2rem;
      margin-top: 1rem;
      border-radius: 5px;
      text-decoration: none;
    }

    .btn:hover {
      background: #0056b3;
    }

    footer {
      text-align: center;
      margin-top: 4rem;
      font-size: 0.9rem;
      color: #999;
    }

    code {
      background: #f3f3f3;
      padding: 2px 5px;
      border-radius: 3px;
    }
  </style>
</head>
<body>

  <h1>🚀 React Admin UI</h1>
  <p class="center">Built for performance, designed for simplicity.</p>

  <p class="center">
    <span class="tag">React</span>
    <span class="tag">Tailwind CSS</span>
    <span class="tag">GitHub Pages</span>
    <span class="tag">HashRouter</span>
  </p>

  <h2>🔥 Features</h2>
  <ul>
    <li>⚛️ React 18 with functional components</li>
    <li>🎨 Tailwind CSS utility-first design</li>
    <li>🌗 Light & Dark UI layout</li>
    <li>📱 Fully responsive admin dashboard</li>
    <li>🔄 React Router v6 with <code>HashRouter</code> for GitHub Pages</li>
    <li>🚀 Live deployed using GitHub Pages</li>
  </ul>

  <h2>📦 Tech Stack</h2>
  <table>
    <tr><th>Category</th><th>Tool</th></tr>
    <tr><td>Frontend</td><td>React</td></tr>
    <tr><td>Routing</td><td>React Router v6 (<code>HashRouter</code>)</td></tr>
    <tr><td>Styling</td><td>Tailwind CSS</td></tr>
    <tr><td>Deployment</td><td>GitHub Pages</td></tr>
  </table>

  <h2>📁 Folder Structure</h2>
  <pre><code>src/
├── components/
├── layouts/
│   ├── admin/
│   ├── auth/
│   └── rtl/
├── App.jsx
└── index.js
</code></pre>

  <h2>🛠️ Setup Instructions</h2>
  <pre><code>git clone https://github.com/code-yeasin/react-admin-ui.git
cd react-admin-ui
npm install
npm start</code></pre>

  <h2>🚀 Deployment</h2>
  <p>The app is deployed using a manual <code>gh-pages</code> branch strategy with <code>HashRouter</code> to support sub-routing on GitHub Pages.</p>

  <pre><code>npm run build
xcopy /E /I /H /Y build\* ../admin-ui-deploy
cd ../admin-ui-deploy
git init
git checkout -b gh-pages
git remote add origin https://github.com/your-username/react-admin-ui.git
git add .
git commit -m "Deploy React build"
git push origin gh-pages --force</code></pre>

  <p><a href="https://code-yeasin.github.io/react-admin-ui" class="btn" target="_blank">🌐 View Live Demo</a></p>

  <h2>🙌 Author</h2>
  <p>Crafted by <a href="https://github.com/code-yeasin" target="_blank">Yeasin</a> — passionate about clean UI, optimized code, and real results.</p>

  <footer>
    © 2025 React Admin UI. All rights reserved.
  </footer>

</body>
</html>
