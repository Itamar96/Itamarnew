<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Itamar Castillo — Home ◈ Personal Site</title>

  <style>
    :root{--max:960px;--ink:#1f2937;--muted:#6b7280;--card:#fff;--accent:#2563eb}
    *{box-sizing:border-box}
    body{margin:0;font:16px/1.55 system-ui,-apple-system,Segoe UI,Roboto,Arial;background:#f8fafc;color:var(--ink)}
    header,main,footer{display:block}
    .wrap{max-width:var(--max);margin:auto;padding:clamp(1rem,2vw,1.5rem)}
    header{background:var(--card);border-bottom:1px solid #e5e7eb}
    h1{margin:.2em 0 .4em;font-size:clamp(1.6rem,3vw,2.2rem)}
    h2{margin:.2em 0 .6em;color:var(--muted);font-size:clamp(1.2rem,2.2vw,1.4rem)}
    p{margin:.75rem 0}
    a{color:var(--accent)}
    .card{background:var(--card);border:1px solid #e5e7eb;border-radius:14px;padding:1rem}
    footer{border-top:1px solid #e5e7eb;color:var(--muted);font-size:.95rem}
    .links a{margin-right:.8rem}
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <h1>Itamar Castillo — Personal Site</h1>
    </div>
  </header>

  <main>
    <div class="wrap">
      <h2>Home</h2>
      <p>This is my personal homepage. It’s separate from my course work.</p>
      <div class="card">
        <p><strong>Course work:</strong> Visit my WEB115 site:</p>
        <p class="links"><a href="web115/">Go to my WEB115 course ↗</a></p>
      </div>
      <p>You can learn more about me by reading my introduction on the course site.</p>
    </div>
  </main>

  <footer>
    <div class="wrap">
      <p class="links">
        <a href="https://github.com/yourgithubloginid">GitHub</a>
        <a href="https://yourgithubloginid.github.io">GitHub Pages</a>
        <a href="https://yourgithubloginid.github.io/web115/">WEB115.io</a>
      </p>
      <p>© <span id="y"></span> Itamar Castillo</p>
    </div>
  </footer>

  <script>document.getElementById('y').textContent=new Date().getFullYear();</script>
</body>
</html>
