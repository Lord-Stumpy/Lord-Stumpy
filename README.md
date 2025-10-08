<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lord-Stumpy | Digital Chaos Engineer</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Roboto:wght@400;700&display=swap');

    body {
      margin: 0;
      font-family: 'JetBrains Mono', monospace;
      background: #0a0a0a;
      color: #f5f5f5;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 5rem 1rem 2rem;
      background: linear-gradient(180deg, #0a0a0a, #111);
      border-bottom: 1px solid #222;
      position: relative;
    }

    h1 {
      font-size: 2.8rem;
      color: #ff2e63;
      text-shadow: 0 0 8px #ff2e63aa;
      letter-spacing: 1px;
    }

    h2 {
      color: #08f7fe;
      margin-top: 3rem;
      text-align: center;
      text-shadow: 0 0 6px #08f7feaa;
    }

    p, li {
      font-family: 'Roboto', sans-serif;
      color: #ccc;
      line-height: 1.7;
    }

    .section {
      max-width: 900px;
      margin: 0 auto;
      padding: 2rem;
    }

    .tech-table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1rem;
      font-family: 'JetBrains Mono', monospace;
    }

    .tech-table th, .tech-table td {
      border-bottom: 1px solid #222;
      padding: 0.6rem;
      text-align: left;
    }

    .tech-table th {
      color: #ff2e63;
    }

    .stat-cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      margin-top: 2rem;
    }

    .stat-cards img {
      width: 420px;
      border-radius: 10px;
      box-shadow: 0 0 15px #111;
      transition: transform 0.3s ease;
    }

    .stat-cards img:hover {
      transform: scale(1.03);
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      border-top: 1px solid #222;
      color: #666;
      font-size: 0.9rem;
      margin-top: 4rem;
    }

    a {
      color: #ff2e63;
      text-decoration: none;
      transition: 0.3s;
    }

    a:hover {
      color: #08f7fe;
    }

    blockquote {
      font-style: italic;
      color: #999;
      text-align: center;
      margin: 3rem auto;
      border-left: 3px solid #ff2e63;
      padding-left: 1rem;
      max-width: 700px;
    }

    @keyframes glow {
      0% { text-shadow: 0 0 8px #ff2e63; }
      50% { text-shadow: 0 0 16px #08f7fe; }
      100% { text-shadow: 0 0 8px #ff2e63; }
    }

    h1:hover {
      animation: glow 2s infinite alternate;
    }
  </style>
</head>
<body>
  <header>
    <h1>👑 Lord-Stumpy</h1>
    <p>Making weird things that somehow work.</p>
  </header>

  <section class="section">
    <h2>🧠 About Me</h2>
    <ul>
      <li>💻 Mostly messing around with <strong>tools, games, and creative tech</strong></li>
      <li>🧩 Big fan of learning how things <em>actually</em> work under the hood</li>
      <li>🕶️ Sometimes I make nice things — sometimes I make cursed ones</li>
      <li>🎧 Music, visuals, and chaos fuel everything I do</li>
    </ul>
  </section>

  <section class="section">
    <h2>⚔️ Tech & Tools</h2>
    <table class="tech-table">
      <tr>
        <th>Type</th>
        <th>Stuff I Use</th>
      </tr>
      <tr>
        <td>Main</td>
        <td>Python, JavaScript, HTML/CSS</td>
      </tr>
      <tr>
        <td>Side</td>
        <td>C#, Godot, Unity, Bash</td>
      </tr>
      <tr>
        <td>Design</td>
        <td>Photoshop, Clip Studio, Blender</td>
      </tr>
      <tr>
        <td>Experiments</td>
        <td>AI, shaders, automation</td>
      </tr>
    </table>
  </section>

  <section class="section">
    <h2>📊 GitHub Stats</h2>
    <div class="stat-cards">
      <img src="https://github-readme-stats.vercel.app/api?username=Lord-Stumpy&show_icons=true&theme=radical" alt="GitHub stats" />
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lord-Stumpy&layout=compact&theme=radical" alt="Top languages" />
    </div>
  </section>

  <section class="section">
    <h2>🚀 Projects</h2>
    <p>Right now I’m building and breaking small ideas until something cool sticks.</p>
    <ul>
      <li>🔮 Experimental game concepts</li>
      <li>🖼️ Visual tools or scripts</li>
      <li>💀 Random cursed utilities</li>
    </ul>
  </section>

  <section class="section">
    <h2>☕ Connect</h2>
    <p>If you’re into creative chaos, weird art, or coding side quests — say hey.</p>
    <ul>
      <li>🐦 Twitter: <a href="#">(your handle)</a></li>
      <li>🌐 Portfolio: <a href="#">(your site)</a></li>
      <li>📬 Email: <a href="mailto:you@example.com">you@example.com</a></li>
    </ul>
  </section>

  <blockquote>“Keep building weird stuff. The world’s got enough normal.”</blockquote>

  <footer>
    &copy; 2025 Lord-Stumpy. Built with chaos and caffeine.
  </footer>
</body>
</html>
