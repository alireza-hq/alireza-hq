<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Alireza — README</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;600&family=Syne:wght@400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: #0d1117;
    color: #e6edf3;
    font-family: 'Syne', sans-serif;
    padding: 2rem;
    min-height: 100vh;
  }

  .readme {
    max-width: 620px;
    margin: 0 auto;
  }

  /* Terminal */
  .term-bar {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 10px 10px 0 0;
    padding: 10px 16px;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .dot { width: 12px; height: 12px; border-radius: 50%; }
  .dot-r { background: #ff5f57; }
  .dot-y { background: #febc2e; }
  .dot-g { background: #28c840; }
  .term-title {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: #8b949e;
    margin-left: 6px;
  }

  .term-body {
    background: #111318;
    border: 1px solid #30363d;
    border-top: none;
    border-radius: 0 0 10px 10px;
    padding: 1.5rem 1.5rem 2rem;
    font-family: 'JetBrains Mono', monospace;
    font-size: 13px;
    line-height: 2;
    margin-bottom: 2rem;
  }
  .p { color: #8b949e; }
  .g { color: #5DCAA5; }
  .y { color: #FAC775; }
  .b { color: #85B7EB; }
  .w { color: #e6edf3; }
  .d { color: #3d444d; }

  /* Section label */
  .section-label {
    font-size: 10px;
    letter-spacing: .14em;
    text-transform: uppercase;
    color: #8b949e;
    margin-bottom: .75rem;
    font-family: 'JetBrains Mono', monospace;
  }

  /* Stack grid */
  .stack-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    margin-bottom: 2rem;
  }
  .stack-card {
    border: 1px solid #30363d;
    border-radius: 8px;
    padding: .75rem 1rem;
    background: #161b22;
  }
  .stack-card h4 {
    font-size: 10px;
    letter-spacing: .1em;
    text-transform: uppercase;
    color: #8b949e;
    margin-bottom: .5rem;
    font-family: 'JetBrains Mono', monospace;
  }
  .tag {
    display: inline-block;
    font-size: 11px;
    font-family: 'JetBrains Mono', monospace;
    padding: 3px 8px;
    border-radius: 4px;
    margin: 2px 2px 2px 0;
    background: #21262d;
    color: #8b949e;
    border: 1px solid #30363d;
  }

  /* Projects */
  .projects { margin-bottom: 2rem; }
  .proj {
    border: 1px solid #30363d;
    border-radius: 10px;
    padding: 1rem 1.25rem;
    margin-bottom: 10px;
    background: #161b22;
    display: flex;
    gap: 1rem;
    align-items: flex-start;
  }
  .proj-icon {
    width: 38px;
    height: 38px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    font-size: 18px;
  }
  .proj h3 { font-size: 14px; font-weight: 600; margin-bottom: 3px; color: #e6edf3; }
  .proj p { font-size: 12px; color: #8b949e; line-height: 1.5; }
  .proj-tags { margin-top: 7px; }

  /* Links */
  .links-row { display: flex; gap: 10px; flex-wrap: wrap; }
  .link-btn {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    padding: 7px 14px;
    border-radius: 8px;
    border: 1px solid #30363d;
    color: #8b949e;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: #161b22;
    transition: background .15s, color .15s;
  }
  .link-btn:hover { background: #21262d; color: #e6edf3; }
  .link-btn i { font-size: 14px; }
</style>
</head>
<body>
<div class="readme">

  <!-- Terminal -->
  <div class="term-bar">
    <div class="dot dot-r"></div>
    <div class="dot dot-y"></div>
    <div class="dot dot-g"></div>
    <span class="term-title">alireza-h-dev ~ README.md</span>
  </div>
  <div class="term-body">
    <div><span class="d">$ </span><span class="g">whoami</span></div>
    <div><span class="w">Alireza</span> <span class="d">—</span> <span class="p">Software Developer</span></div>
    <br>
    <div><span class="d">$ </span><span class="g">cat</span> <span class="b">about.txt</span></div>
    <div><span class="p">Building practical web applications with</span></div>
    <div><span class="y">React</span><span class="p">, </span><span class="y">Next.js</span><span class="p">, and </span><span class="y">TypeScript</span><span class="p">.</span></div>
    <div><span class="p">I enjoy building things, improving systems,</span></div>
    <div><span class="p">and writing software that stays maintainable.</span></div>
    <br>
    <div><span class="d">$ </span><span class="g">echo</span> <span class="b">$STATUS</span></div>
    <div><span class="g">▶</span> <span class="w">open to new opportunities</span> <span class="d">|</span> <span class="p">always shipping</span></div>
  </div>

  <!-- Stack -->
  <div class="section-label">tech stack</div>
  <div class="stack-grid">
    <div class="stack-card">
      <h4>Frontend</h4>
      <span class="tag">React</span><span class="tag">Next.js</span><span class="tag">TypeScript</span><span class="tag">Tailwind</span>
    </div>
    <div class="stack-card">
      <h4>Backend</h4>
      <span class="tag">Node.js</span><span class="tag">Express</span><span class="tag">PostgreSQL</span>
    </div>
    <div class="stack-card">
      <h4>Tooling</h4>
      <span class="tag">Git</span><span class="tag">Docker</span><span class="tag">Vercel</span><span class="tag">GitHub</span>
    </div>
  </div>

  <!-- Projects -->
  <div class="section-label">featured projects</div>
  <div class="projects">
    <div class="proj">
      <div class="proj-icon" style="background:#0d2818"><i class="ti ti-terminal-2" style="color:#5DCAA5"></i></div>
      <div>
        <h3>Interactive Portfolio</h3>
        <p>Developer workspace featuring a custom terminal, resume inspector, and project explorer.</p>
        <div class="proj-tags"><span class="tag">Next.js</span><span class="tag">TypeScript</span><span class="tag">Tailwind</span></div>
      </div>
    </div>
    <div class="proj">
      <div class="proj-icon" style="background:#0d1a2e"><i class="ti ti-layout-dashboard" style="color:#85B7EB"></i></div>
      <div>
        <h3>Internal Operations Dashboard</h3>
        <p>Company platform for authentication, tickets, forms, monitoring, and admin workflows.</p>
        <div class="proj-tags"><span class="tag">React</span><span class="tag">Node.js</span><span class="tag">PostgreSQL</span></div>
      </div>
    </div>
    <div class="proj">
      <div class="proj-icon" style="background:#2a1a0d"><i class="ti ti-shopping-cart" style="color:#FAC775"></i></div>
      <div>
        <h3>E-Commerce Platform</h3>
        <p>Full-stack store with auth, product management, checkout, and order workflows.</p>
        <div class="proj-tags"><span class="tag">Next.js</span><span class="tag">Express</span><span class="tag">PostgreSQL</span></div>
      </div>
    </div>
  </div>

  <!-- Links -->
  <div class="section-label">find me</div>
  <div class="links-row">
    <a class="link-btn" href="https://alireza-h-dev.vercel.app"><i class="ti ti-world"></i> portfolio</a>
    <a class="link-btn" href="https://linkedin.com/in/alireza-hq-dev"><i class="ti ti-brand-linkedin"></i> linkedin</a>
    <a class="link-btn" href="https://github.com/alireza-h-dev"><i class="ti ti-brand-github"></i> github</a>
  </div>

</div>
</body>
</html>
