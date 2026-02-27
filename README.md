<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=250&section=header&text=Azure%20DevOps%20Engineer&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Terraform%20|%20AKS%20|%20CI/CD%20|%20Cloud%20Automation&descAlignY=55&descAlign=50"/>
</p>
<p align="center">
  <img src="https://miro.medium.com/max/1400/1*9s9s9s9s9s9s9s.gif" width="700"/>
</p>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Suman Kamarthapu – Azure DevOps Engineer</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=JetBrains+Mono:wght@300;400;600&display=swap" rel="stylesheet">
<style>
  :root {
    --azure: #0078D4;
    --azure-light: #50e6ff;
    --azure-dark: #003f8c;
    --steel: #1a2235;
    --steel-mid: #243047;
    --steel-light: #2d3d5a;
    --text: #e8f4fd;
    --muted: #8aaccc;
    --accent: #00d4aa;
    --warn: #ffd700;
    --glow: rgba(0,120,212,0.3);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: var(--steel);
    color: var(--text);
    font-family: 'JetBrains Mono', monospace;
    overflow-x: hidden;
  }

  /* === ANIMATED BACKGROUND === */
  .bg-canvas {
    position: fixed;
    inset: 0;
    z-index: 0;
    background:
      radial-gradient(ellipse at 20% 20%, rgba(0,120,212,0.18) 0%, transparent 50%),
      radial-gradient(ellipse at 80% 80%, rgba(0,212,170,0.12) 0%, transparent 50%),
      radial-gradient(ellipse at 50% 0%, rgba(80,230,255,0.08) 0%, transparent 40%);
  }

  .grid-lines {
    position: fixed;
    inset: 0;
    z-index: 0;
    background-image:
      linear-gradient(rgba(0,120,212,0.05) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,120,212,0.05) 1px, transparent 1px);
    background-size: 50px 50px;
    animation: gridMove 20s linear infinite;
  }

  @keyframes gridMove {
    0% { transform: translateY(0); }
    100% { transform: translateY(50px); }
  }

  /* Floating particles */
  .particles { position: fixed; inset: 0; z-index: 0; pointer-events: none; }
  .particle {
    position: absolute;
    width: 2px; height: 2px;
    background: var(--azure-light);
    border-radius: 50%;
    animation: float linear infinite;
    opacity: 0;
  }
  @keyframes float {
    0% { transform: translateY(100vh) translateX(0); opacity: 0; }
    10% { opacity: 0.6; }
    90% { opacity: 0.3; }
    100% { transform: translateY(-10px) translateX(var(--drift)); opacity: 0; }
  }

  /* === LAYOUT === */
  .wrapper {
    position: relative;
    z-index: 1;
    max-width: 900px;
    margin: 0 auto;
    padding: 40px 24px 80px;
  }

  /* === HERO === */
  .hero {
    text-align: center;
    padding: 60px 0 50px;
    animation: fadeUp 0.8s ease both;
  }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .avatar-ring {
    width: 110px; height: 110px;
    margin: 0 auto 24px;
    border-radius: 50%;
    background: linear-gradient(135deg, var(--azure), var(--accent));
    display: flex; align-items: center; justify-content: center;
    font-size: 48px;
    box-shadow: 0 0 40px var(--glow), 0 0 80px rgba(0,212,170,0.1);
    animation: pulse 3s ease-in-out infinite;
    position: relative;
  }

  .avatar-ring::after {
    content: '';
    position: absolute;
    inset: -4px;
    border-radius: 50%;
    border: 2px solid transparent;
    background: linear-gradient(135deg, var(--azure-light), var(--accent)) border-box;
    -webkit-mask: linear-gradient(#fff 0 0) padding-box, linear-gradient(#fff 0 0);
    -webkit-mask-composite: destination-out;
    mask-composite: exclude;
    animation: spin 8s linear infinite;
  }

  @keyframes spin { to { transform: rotate(360deg); } }
  @keyframes pulse {
    0%,100% { box-shadow: 0 0 40px var(--glow), 0 0 80px rgba(0,212,170,0.1); }
    50% { box-shadow: 0 0 60px var(--glow), 0 0 120px rgba(0,212,170,0.2); }
  }

  .cert-badge {
    position: absolute;
    top: -8px; right: -8px;
    background: linear-gradient(135deg, #0078d4, #00b4d8);
    color: white;
    font-size: 9px;
    font-weight: 700;
    padding: 3px 7px;
    border-radius: 20px;
    letter-spacing: 0.5px;
    border: 2px solid var(--steel);
    white-space: nowrap;
  }

  .hero h1 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(2rem, 6vw, 3.5rem);
    font-weight: 800;
    background: linear-gradient(135deg, #fff 30%, var(--azure-light) 70%, var(--accent));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    letter-spacing: -1px;
    margin-bottom: 8px;
  }

  .hero .role {
    font-size: 1.05rem;
    color: var(--azure-light);
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-bottom: 16px;
    font-weight: 600;
  }

  .hero .location {
    color: var(--muted);
    font-size: 0.85rem;
    margin-bottom: 28px;
  }

  .hero .tagline {
    font-family: 'Syne', sans-serif;
    font-size: 1.1rem;
    color: var(--text);
    max-width: 560px;
    margin: 0 auto 32px;
    line-height: 1.7;
    opacity: 0.85;
  }

  /* === CONTACT BADGES === */
  .contact-strip {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    justify-content: center;
    margin-bottom: 16px;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    gap: 7px;
    padding: 8px 16px;
    border-radius: 40px;
    font-size: 0.78rem;
    font-weight: 600;
    letter-spacing: 0.5px;
    border: 1px solid rgba(0,120,212,0.3);
    background: rgba(0,120,212,0.08);
    color: var(--azure-light);
    text-decoration: none;
    transition: all 0.25s ease;
    cursor: pointer;
  }

  .badge:hover {
    background: rgba(0,120,212,0.2);
    border-color: var(--azure-light);
    transform: translateY(-2px);
    box-shadow: 0 8px 20px rgba(0,120,212,0.2);
  }

  .badge .icon { font-size: 1rem; }

  /* === SECTION === */
  .section {
    margin: 48px 0;
    animation: fadeUp 0.8s ease both;
  }

  .section-header {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 24px;
  }

  .section-icon {
    width: 36px; height: 36px;
    border-radius: 8px;
    background: linear-gradient(135deg, var(--azure), var(--azure-dark));
    display: flex; align-items: center; justify-content: center;
    font-size: 18px;
    box-shadow: 0 4px 15px var(--glow);
    flex-shrink: 0;
  }

  .section-title {
    font-family: 'Syne', sans-serif;
    font-size: 1.3rem;
    font-weight: 700;
    color: white;
    letter-spacing: 1px;
    text-transform: uppercase;
  }

  .divider {
    flex: 1;
    height: 1px;
    background: linear-gradient(90deg, rgba(0,120,212,0.4), transparent);
  }

  /* === YAML PROFILE BLOCK === */
  .yaml-block {
    background: rgba(13,20,35,0.8);
    border: 1px solid rgba(0,120,212,0.25);
    border-radius: 16px;
    padding: 28px 32px;
    backdrop-filter: blur(10px);
    position: relative;
    overflow: hidden;
  }

  .yaml-block::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, var(--azure), var(--accent), var(--azure-light));
  }

  .yaml-block .file-tab {
    position: absolute;
    top: 0; left: 24px;
    background: linear-gradient(135deg, var(--azure), var(--azure-dark));
    color: white;
    font-size: 0.7rem;
    padding: 2px 12px 5px;
    border-radius: 0 0 8px 8px;
    letter-spacing: 0.5px;
  }

  .yaml-block pre {
    font-size: 0.85rem;
    line-height: 1.8;
    white-space: pre-wrap;
    margin-top: 16px;
  }

  .y-key { color: var(--azure-light); }
  .y-val { color: var(--accent); }
  .y-str { color: #ffd8a0; }
  .y-comment { color: var(--muted); }
  .y-list { color: #c3e6ff; }

  /* === EXPERIENCE CARDS === */
  .exp-card {
    background: rgba(13,20,35,0.7);
    border: 1px solid rgba(0,120,212,0.2);
    border-radius: 16px;
    padding: 24px 28px;
    margin-bottom: 20px;
    backdrop-filter: blur(8px);
    position: relative;
    transition: all 0.3s ease;
    overflow: hidden;
  }

  .exp-card::before {
    content: '';
    position: absolute;
    left: 0; top: 0; bottom: 0;
    width: 3px;
    background: linear-gradient(180deg, var(--azure), var(--accent));
    border-radius: 3px;
  }

  .exp-card:hover {
    border-color: rgba(0,120,212,0.4);
    transform: translateX(4px);
    box-shadow: 0 8px 30px rgba(0,0,0,0.3), -4px 0 20px rgba(0,120,212,0.15);
  }

  .exp-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 12px;
  }

  .exp-title {
    font-family: 'Syne', sans-serif;
    font-size: 1.05rem;
    font-weight: 700;
    color: white;
  }

  .exp-company {
    color: var(--azure-light);
    font-size: 0.85rem;
    margin-top: 2px;
  }

  .exp-date {
    font-size: 0.75rem;
    color: var(--muted);
    background: rgba(0,120,212,0.1);
    padding: 4px 10px;
    border-radius: 20px;
    border: 1px solid rgba(0,120,212,0.2);
    white-space: nowrap;
  }

  .exp-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    margin-top: 14px;
  }

  .tag {
    font-size: 0.7rem;
    padding: 3px 10px;
    border-radius: 20px;
    background: rgba(0,120,212,0.12);
    border: 1px solid rgba(0,120,212,0.25);
    color: var(--azure-light);
    font-weight: 600;
    letter-spacing: 0.3px;
  }

  .tag.green {
    background: rgba(0,212,170,0.1);
    border-color: rgba(0,212,170,0.3);
    color: var(--accent);
  }

  .exp-bullets {
    list-style: none;
    margin-top: 12px;
  }

  .exp-bullets li {
    font-size: 0.82rem;
    color: var(--muted);
    line-height: 1.7;
    padding-left: 18px;
    position: relative;
    margin-bottom: 6px;
  }

  .exp-bullets li::before {
    content: '▸';
    position: absolute;
    left: 0;
    color: var(--accent);
  }

  /* === SKILLS GRID === */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 16px;
  }

  .skill-card {
    background: rgba(13,20,35,0.8);
    border: 1px solid rgba(0,120,212,0.2);
    border-radius: 14px;
    padding: 20px;
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
  }

  .skill-card:hover {
    border-color: rgba(0,120,212,0.5);
    transform: translateY(-4px);
    box-shadow: 0 12px 30px rgba(0,0,0,0.3), 0 0 20px rgba(0,120,212,0.1);
  }

  .skill-card .sk-icon { font-size: 28px; margin-bottom: 10px; }
  .skill-card .sk-title {
    font-family: 'Syne', sans-serif;
    font-size: 0.9rem;
    font-weight: 700;
    color: white;
    margin-bottom: 8px;
  }

  .skill-card .sk-items {
    display: flex;
    flex-wrap: wrap;
    gap: 4px;
  }

  .sk-item {
    font-size: 0.65rem;
    padding: 2px 8px;
    border-radius: 10px;
    background: rgba(80,230,255,0.08);
    border: 1px solid rgba(80,230,255,0.15);
    color: var(--azure-light);
  }

  /* === STATS ROW === */
  .stats-row {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
    gap: 16px;
  }

  .stat-card {
    background: rgba(13,20,35,0.8);
    border: 1px solid rgba(0,120,212,0.2);
    border-radius: 14px;
    padding: 24px 20px;
    text-align: center;
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
  }

  .stat-card::after {
    content: '';
    position: absolute;
    bottom: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, var(--azure), var(--accent));
    transform: scaleX(0);
    transition: transform 0.3s ease;
  }

  .stat-card:hover::after { transform: scaleX(1); }
  .stat-card:hover { transform: translateY(-4px); box-shadow: 0 12px 30px rgba(0,0,0,0.3); }

  .stat-num {
    font-family: 'Syne', sans-serif;
    font-size: 2rem;
    font-weight: 800;
    background: linear-gradient(135deg, var(--azure-light), var(--accent));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .stat-label {
    font-size: 0.72rem;
    color: var(--muted);
    margin-top: 4px;
    letter-spacing: 0.5px;
  }

  /* === CERT === */
  .cert-card {
    background: linear-gradient(135deg, rgba(0,63,140,0.4), rgba(0,120,212,0.2));
    border: 1px solid rgba(0,120,212,0.4);
    border-radius: 16px;
    padding: 24px 28px;
    display: flex;
    align-items: center;
    gap: 20px;
    backdrop-filter: blur(8px);
  }

  .cert-logo {
    width: 64px; height: 64px;
    border-radius: 12px;
    background: linear-gradient(135deg, #0078d4, #00b4d8);
    display: flex; align-items: center; justify-content: center;
    font-size: 30px;
    flex-shrink: 0;
    box-shadow: 0 8px 20px rgba(0,120,212,0.3);
  }

  .cert-info h3 {
    font-family: 'Syne', sans-serif;
    font-size: 1rem;
    font-weight: 700;
    color: white;
    margin-bottom: 4px;
  }

  .cert-info p { color: var(--muted); font-size: 0.82rem; }
  .cert-info .cert-issuer { color: var(--azure-light); font-weight: 600; font-size: 0.85rem; margin-top: 2px; }

  /* === FOOTER === */
  .footer {
    text-align: center;
    padding: 40px 0 20px;
    color: var(--muted);
    font-size: 0.78rem;
  }

  .footer .quote {
    font-family: 'Syne', sans-serif;
    font-size: 1rem;
    color: var(--azure-light);
    margin-bottom: 8px;
    font-style: italic;
  }

  /* === ANIMATIONS DELAY === */
  .section:nth-child(2) { animation-delay: 0.1s; }
  .section:nth-child(3) { animation-delay: 0.2s; }
  .section:nth-child(4) { animation-delay: 0.3s; }
  .section:nth-child(5) { animation-delay: 0.4s; }

  /* === EDU === */
  .edu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 16px;
  }

  .edu-card {
    background: rgba(13,20,35,0.7);
    border: 1px solid rgba(0,212,170,0.2);
    border-radius: 14px;
    padding: 20px 24px;
    transition: all 0.3s ease;
  }

  .edu-card:hover {
    border-color: rgba(0,212,170,0.4);
    transform: translateY(-3px);
  }

  .edu-card .edu-degree {
    font-family: 'Syne', sans-serif;
    font-size: 0.95rem;
    font-weight: 700;
    color: white;
    margin-bottom: 4px;
  }

  .edu-card .edu-uni { color: var(--accent); font-size: 0.82rem; }
  .edu-card .edu-year { color: var(--muted); font-size: 0.75rem; margin-top: 4px; }

  @media (max-width: 600px) {
    .wrapper { padding: 20px 16px 60px; }
    .hero h1 { font-size: 2rem; }
    .yaml-block { padding: 20px; }
    .exp-card { padding: 18px; }
  }
</style>
</head>
<body>

<!-- Animated background -->
<div class="bg-canvas"></div>
<div class="grid-lines"></div>
<div class="particles" id="particles"></div>

<div class="wrapper">

  <!-- ===== HERO ===== -->
  <div class="hero">
    <div class="avatar-ring" style="position:relative;display:inline-flex;">
      ☁️
      <span class="cert-badge">⭐ MS Azure Certified</span>
    </div>

    <h1>Suman Kamarthapu</h1>
    <div class="role">☁️ Azure DevOps Engineer</div>
    <div class="location">📍 Coventry, London, UK &nbsp;|&nbsp; 7+ Years Experience</div>

    <p class="tagline">
      Building secure, scalable delivery platforms on Microsoft Azure —<br>
      where infrastructure meets intelligence.
    </p>

    <div class="contact-strip">
      <a class="badge" href="mailto:sumancloudtech@gmail.com">
        <span class="icon">✉️</span> sumancloudtech@gmail.com
      </a>
      <a class="badge" href="tel:07350000959">
        <span class="icon">📞</span> 07350 000959
      </a>
      <a class="badge" href="https://linkedin.com/in/suman-kamarthapu-9539ab236">
        <span class="icon">🔗</span> LinkedIn
      </a>
    </div>
  </div>

  <!-- ===== YAML PROFILE ===== -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">👤</div>
      <span class="section-title">Profile</span>
      <div class="divider"></div>
    </div>
    <div class="yaml-block">
      <div class="file-tab">profile.yaml</div>
      <pre>
<span class="y-comment"># ─── Engineer Profile ─────────────────────────────────</span>

<span class="y-key">👨‍💻 identity:</span>
  <span class="y-key">name:</span>     <span class="y-str">"Suman Kamarthapu"</span>
  <span class="y-key">role:</span>     <span class="y-str">"Azure DevOps Engineer"</span>
  <span class="y-key">location:</span> <span class="y-str">"🇬🇧 Coventry, London, UK"</span>
  <span class="y-key">exp:</span>      <span class="y-str">"7+ years"</span>

<span class="y-key">🎯 mission:</span>
  <span class="y-key">primary:</span>  <span class="y-str">"Build secure, scalable Azure delivery platforms"</span>
  <span class="y-key">vision:</span>   <span class="y-str">"Automate everything. Monitor everything."</span>
  <span class="y-key">motto:</span>    <span class="y-str">"Reliable pipelines. Zero surprises."</span>

<span class="y-key">💡 focus_areas:</span>
  <span class="y-list">- ☁️  Azure IaaS / PaaS / AKS</span>
  <span class="y-list">- 🔄  Multi-stage YAML CI/CD Pipelines</span>
  <span class="y-list">- 🏗️  Terraform & ARM Infrastructure as Code</span>
  <span class="y-list">- 🐳  Docker / Kubernetes Orchestration</span>
  <span class="y-list">- 📊  Azure Monitor / Log Analytics / App Insights</span>
  <span class="y-list">- 🔐  Key Vault & RBAC Security</span>
  <span class="y-list">- 🤝  Agile / Scrum Delivery</span></pre>
    </div>
  </div>

  <!-- ===== STATS ===== -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">📈</div>
      <span class="section-title">By the Numbers</span>
      <div class="divider"></div>
    </div>
    <div class="stats-row">
      <div class="stat-card">
        <div class="stat-num">7+</div>
        <div class="stat-label">Years in Azure DevOps</div>
      </div>
      <div class="stat-card">
        <div class="stat-num">3</div>
        <div class="stat-label">Cloud Providers</div>
      </div>
      <div class="stat-card">
        <div class="stat-num">∞</div>
        <div class="stat-label">Pipelines Delivered</div>
      </div>
      <div class="stat-card">
        <div class="stat-num">0</div>
        <div class="stat-label">Manual Deploys Preferred</div>
      </div>
    </div>
  </div>

  <!-- ===== TECH ARSENAL ===== -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">⚙️</div>
      <span class="section-title">Technology Arsenal</span>
      <div class="divider"></div>
    </div>
    <div class="skills-grid">
      <div class="skill-card">
        <div class="sk-icon">☁️</div>
        <div class="sk-title">Azure Cloud</div>
        <div class="sk-items">
          <span class="sk-item">AKS</span>
          <span class="sk-item">VMs</span>
          <span class="sk-item">VNets</span>
          <span class="sk-item">NSGs</span>
          <span class="sk-item">App Services</span>
          <span class="sk-item">Storage</span>
          <span class="sk-item">Load Balancers</span>
          <span class="sk-item">Key Vault</span>
        </div>
      </div>
      <div class="skill-card">
        <div class="sk-icon">🔄</div>
        <div class="sk-title">CI/CD & DevOps</div>
        <div class="sk-items">
          <span class="sk-item">Azure Pipelines</span>
          <span class="sk-item">Azure Boards</span>
          <span class="sk-item">Azure Repos</span>
          <span class="sk-item">Azure Artifacts</span>
          <span class="sk-item">GitHub</span>
          <span class="sk-item">GitLab</span>
          <span class="sk-item">Jenkins</span>
        </div>
      </div>
      <div class="skill-card">
        <div class="sk-icon">🏗️</div>
        <div class="sk-title">Infrastructure as Code</div>
        <div class="sk-items">
          <span class="sk-item">Terraform</span>
          <span class="sk-item">azurerm</span>
          <span class="sk-item">ARM Templates</span>
          <span class="sk-item">RBAC</span>
        </div>
      </div>
      <div class="skill-card">
        <div class="sk-icon">🐳</div>
        <div class="sk-title">Containers & K8s</div>
        <div class="sk-items">
          <span class="sk-item">Docker</span>
          <span class="sk-item">Kubernetes</span>
          <span class="sk-item">Deployments</span>
          <span class="sk-item">StatefulSets</span>
          <span class="sk-item">Ingress</span>
          <span class="sk-item">ConfigMaps</span>
          <span class="sk-item">Secrets</span>
        </div>
      </div>
      <div class="skill-card">
        <div class="sk-icon">📊</div>
        <div class="sk-title">Observability</div>
        <div class="sk-items">
          <span class="sk-item">Azure Monitor</span>
          <span class="sk-item">Log Analytics</span>
          <span class="sk-item">App Insights</span>
          <span class="sk-item">SLO Dashboards</span>
          <span class="sk-item">Alerting</span>
        </div>
      </div>
      <div class="skill-card">
        <div class="sk-icon">⌨️</div>
        <div class="sk-title">Scripting & DB</div>
        <div class="sk-items">
          <span class="sk-item">Bash</span>
          <span class="sk-item">PowerShell</span>
          <span class="sk-item">Azure CLI</span>
          <span class="sk-item">MySQL</span>
          <span class="sk-item">MongoDB</span>
          <span class="sk-item">Cosmos DB</span>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== EXPERIENCE ===== -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">💼</div>
      <span class="section-title">Professional Journey</span>
      <div class="divider"></div>
    </div>

    <!-- Job 1 -->
    <div class="exp-card">
      <div class="exp-header">
        <div>
          <div class="exp-title">🚀 Azure DevOps Engineer</div>
          <div class="exp-company">MOKSHA'S SOLUTIONS PVT LTD · Coventry/London</div>
        </div>
        <div class="exp-date">📅 Sep 2022 – Present</div>
      </div>
      <ul class="exp-bullets">
        <li>Led Azure DevOps delivery across multiple apps with reusable multi-stage YAML pipelines, environments, approvals, and gates for Dev/Test/Prod.</li>
        <li>Provisioned & governed Azure infra with Terraform (azurerm) and ARM — VNets, NSGs, AKS, VM Scale Sets, App Service, Storage, Key Vault — following IaC & RBAC best practices.</li>
        <li>Deployed and operated AKS workloads using Kubernetes manifests (Deployments, StatefulSets, Services, Ingress, ConfigMaps, Secrets).</li>
        <li>Standardized container build, scan & publish flows using Docker and Azure Artifacts; enforced semantic versioning and traceable releases.</li>
        <li>Integrated secrets management via Azure Key Vault; tightened branch policies and PR reviews in GitHub/Azure Repos.</li>
        <li>Implemented observability with Azure Monitor, Log Analytics & Application Insights; built SLO dashboards and actionable alerting.</li>
        <li>Automated routine operations with Bash, PowerShell & Azure CLI to reduce manual toil; active Agile ceremony participant.</li>
      </ul>
      <div class="exp-tags">
        <span class="tag">Azure DevOps</span>
        <span class="tag">Terraform</span>
        <span class="tag">AKS</span>
        <span class="tag">Docker</span>
        <span class="tag green">Key Vault</span>
        <span class="tag green">Azure Monitor</span>
        <span class="tag">YAML Pipelines</span>
        <span class="tag">Kubernetes</span>
      </div>
    </div>

    <!-- Job 2 -->
    <div class="exp-card">
      <div class="exp-header">
        <div>
          <div class="exp-title">⚡ Azure DevOps Engineer</div>
          <div class="exp-company">BlueTech Prism · Coventry/London</div>
        </div>
        <div class="exp-date">📅 Sep 2021 – Aug 2022</div>
      </div>
      <ul class="exp-bullets">
        <li>Supported multiple application teams delivering reliable CI/CD across Dev, Test & Production environments.</li>
        <li>Designed and maintained Azure DevOps YAML pipelines for build and release automation, increasing deployment consistency and speed.</li>
        <li>Provisioned Azure infrastructure with Terraform & ARM; managed VMs, App Services, Storage, Load Balancers, VNets, NSGs & Azure Monitor.</li>
        <li>Managed AKS clusters and authored Kubernetes manifests; containerized applications with Docker.</li>
        <li>Implemented branch strategies and PR workflows in GitHub/Azure Repos; automated tasks with Azure CLI, Bash & PowerShell.</li>
        <li>Ensured secure secret management using Azure Key Vault; collaborated cross-functionally in Agile/Scrum ceremonies.</li>
      </ul>
      <div class="exp-tags">
        <span class="tag">Azure DevOps</span>
        <span class="tag">Terraform</span>
        <span class="tag">ARM</span>
        <span class="tag">AKS</span>
        <span class="tag">Docker</span>
        <span class="tag green">Log Analytics</span>
        <span class="tag green">App Insights</span>
      </div>
    </div>

    <!-- Job 3 -->
    <div class="exp-card">
      <div class="exp-header">
        <div>
          <div class="exp-title">🔧 DevOps Engineer</div>
          <div class="exp-company">FOCO IT Consulting · Hyderabad, India</div>
        </div>
        <div class="exp-date">📅 Mar 2018 – Feb 2021</div>
      </div>
      <ul class="exp-bullets">
        <li>Built and maintained CI/CD pipelines using Jenkins, Maven & Git applying DevOps best practices alongside Azure DevOps.</li>
        <li>Delivered solutions on Azure compute services: VMs, VM Scale Sets, Functions, App Service & Batch.</li>
        <li>Containerized applications with Docker and deployed to Azure and AWS environments.</li>
        <li>Administered Git with branching/tagging strategies, pull requests & merges to enable collaborative delivery.</li>
        <li>Built and operated highly available workloads on Kubernetes; managed Azure AD user provisioning via portal & PowerShell.</li>
        <li>Worked with MySQL, MongoDB & Cosmos DB; participated actively in Agile ceremonies.</li>
      </ul>
      <div class="exp-tags">
        <span class="tag">Jenkins</span>
        <span class="tag">Maven</span>
        <span class="tag">Git</span>
        <span class="tag">Docker</span>
        <span class="tag">Kubernetes</span>
        <span class="tag green">AWS</span>
        <span class="tag green">Azure</span>
        <span class="tag">CosmosDB</span>
      </div>
    </div>
  </div>

  <!-- ===== CERTIFICATION ===== -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">🏅</div>
      <span class="section-title">Certification</span>
      <div class="divider"></div>
    </div>
    <div class="cert-card">
      <div class="cert-logo">⭐</div>
      <div class="cert-info">
        <h3>Microsoft Azure Fundamentals</h3>
        <div class="cert-issuer">🔵 Microsoft Certified</div>
        <p>Validates foundational knowledge of cloud concepts and Azure services, security, privacy, compliance, and trust.</p>
      </div>
    </div>
  </div>

  <!-- ===== EDUCATION ===== -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">🎓</div>
      <span class="section-title">Education</span>
      <div class="divider"></div>
    </div>
    <div class="edu-grid">
      <div class="edu-card">
        <div class="edu-degree">🎓 Master of Information Technology</div>
        <div class="edu-uni">University of Ballarat, Melbourne, Australia</div>
        <div class="edu-year">📅 2008 – 2010</div>
      </div>
      <div class="edu-card">
        <div class="edu-degree">🎓 Master of Computer Applications</div>
        <div class="edu-uni">Osmania University, Hyderabad, India</div>
        <div class="edu-year">📅 2004 – 2007</div>
      </div>
    </div>
  </div>

  <!-- ===== FOOTER ===== -->
  <div class="footer">
    <div class="quote">"Infrastructure should be invisible when it works perfectly."</div>
    <p>✨ Open to new Azure DevOps & Cloud Engineering opportunities · 🇬🇧 Based in Coventry, UK</p>
    <p style="margin-top:8px; color:#4a6a8a; font-size:0.7rem;">sumancloudtech@gmail.com · 07350 000959</p>
  </div>

</div>

<script>
  // Generate floating particles
  const container = document.getElementById('particles');
  for (let i = 0; i < 40; i++) {
    const p = document.createElement('div');
    p.className = 'particle';
    p.style.left = Math.random() * 100 + 'vw';
    p.style.animationDuration = (8 + Math.random() * 15) + 's';
    p.style.animationDelay = (Math.random() * 20) + 's';
    p.style.setProperty('--drift', (Math.random() * 100 - 50) + 'px');
    p.style.width = p.style.height = (1 + Math.random() * 3) + 'px';
    if (Math.random() > 0.5) p.style.background = 'var(--accent)';
    container.appendChild(p);
  }
</script>
</body>
</html>
