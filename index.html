<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vishal Gupta — Full Stack Developer</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=JetBrains+Mono:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #050810;
    --surface: #0b1120;
    --border: #1a2540;
    --accent: #00d4ff;
    --accent2: #7c3aed;
    --accent3: #f59e0b;
    --text: #e2e8f0;
    --muted: #64748b;
    --glow: rgba(0,212,255,0.15);
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Syne', sans-serif;
    overflow-x: hidden;
    cursor: none;
  }

  /* Custom cursor */
  .cursor {
    position: fixed;
    width: 12px; height: 12px;
    background: var(--accent);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9999;
    transition: transform 0.15s ease, opacity 0.3s;
    mix-blend-mode: screen;
  }
  .cursor-trail {
    position: fixed;
    width: 36px; height: 36px;
    border: 1px solid rgba(0,212,255,0.4);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9998;
    transition: transform 0.4s ease, opacity 0.3s;
  }

  /* Starfield */
  canvas#stars {
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    z-index: 0;
    pointer-events: none;
  }

  /* Grid overlay */
  .grid-overlay {
    position: fixed;
    inset: 0;
    background-image:
      linear-gradient(rgba(0,212,255,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,212,255,0.03) 1px, transparent 1px);
    background-size: 60px 60px;
    z-index: 0;
    pointer-events: none;
  }

  main {
    position: relative;
    z-index: 1;
    max-width: 900px;
    margin: 0 auto;
    padding: 40px 24px 100px;
  }

  /* ── HERO ── */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-top: 60px;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: rgba(0,212,255,0.08);
    border: 1px solid rgba(0,212,255,0.25);
    border-radius: 100px;
    padding: 6px 16px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    color: var(--accent);
    margin-bottom: 28px;
    opacity: 0;
    animation: fadeUp 0.8s 0.2s forwards;
  }
  .badge-dot {
    width: 7px; height: 7px;
    background: var(--accent);
    border-radius: 50%;
    animation: pulse 2s infinite;
  }

  .hero-name {
    font-size: clamp(52px, 10vw, 96px);
    font-weight: 800;
    line-height: 0.95;
    letter-spacing: -3px;
    opacity: 0;
    animation: fadeUp 0.9s 0.3s forwards;
  }
  .hero-name .line1 { display: block; color: var(--text); }
  .hero-name .line2 {
    display: block;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .hero-title {
    margin-top: 20px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 16px;
    color: var(--muted);
    opacity: 0;
    animation: fadeUp 0.9s 0.45s forwards;
  }
  .hero-title span { color: var(--accent3); }

  .hero-desc {
    margin-top: 20px;
    max-width: 560px;
    font-size: 17px;
    color: #94a3b8;
    line-height: 1.7;
    font-weight: 400;
    opacity: 0;
    animation: fadeUp 0.9s 0.55s forwards;
  }

  .hero-links {
    margin-top: 36px;
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    opacity: 0;
    animation: fadeUp 0.9s 0.7s forwards;
  }
  .btn {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 12px 24px;
    border-radius: 8px;
    font-family: 'Syne', sans-serif;
    font-size: 14px;
    font-weight: 600;
    text-decoration: none;
    transition: all 0.25s;
    cursor: none;
  }
  .btn-primary {
    background: var(--accent);
    color: #000;
    border: 1px solid transparent;
  }
  .btn-primary:hover {
    background: transparent;
    color: var(--accent);
    border-color: var(--accent);
    box-shadow: 0 0 30px rgba(0,212,255,0.25);
  }
  .btn-ghost {
    background: transparent;
    color: var(--text);
    border: 1px solid var(--border);
  }
  .btn-ghost:hover {
    border-color: var(--accent);
    color: var(--accent);
  }

  /* scroll indicator */
  .scroll-hint {
    margin-top: 60px;
    display: flex;
    align-items: center;
    gap: 12px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--muted);
    opacity: 0;
    animation: fadeUp 0.9s 1s forwards;
  }
  .scroll-line {
    width: 40px; height: 1px;
    background: var(--muted);
    position: relative;
    overflow: hidden;
  }
  .scroll-line::after {
    content: '';
    position: absolute;
    top: 0; left: -100%;
    width: 100%; height: 100%;
    background: var(--accent);
    animation: scanLine 2s 1.5s infinite;
  }

  /* ── SECTION ── */
  .section {
    padding: 80px 0 0;
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .section.visible { opacity: 1; transform: none; }

  .section-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--accent);
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-bottom: 12px;
  }
  .section-title {
    font-size: 38px;
    font-weight: 800;
    letter-spacing: -1.5px;
    line-height: 1;
    margin-bottom: 40px;
  }

  /* ── STATS ── */
  .stats-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 16px;
    margin-bottom: 0;
  }
  .stat-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 24px;
    position: relative;
    overflow: hidden;
    transition: border-color 0.3s, transform 0.3s;
  }
  .stat-card:hover { border-color: var(--accent); transform: translateY(-4px); }
  .stat-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--accent), transparent);
    opacity: 0;
    transition: opacity 0.3s;
  }
  .stat-card:hover::before { opacity: 1; }
  .stat-num {
    font-size: 40px;
    font-weight: 800;
    color: var(--accent);
    line-height: 1;
    font-family: 'JetBrains Mono', monospace;
  }
  .stat-label { font-size: 13px; color: var(--muted); margin-top: 6px; }

  /* ── SKILLS ── */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
    gap: 12px;
  }
  .skill-chip {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 14px 12px;
    text-align: center;
    font-size: 13px;
    font-weight: 600;
    color: var(--text);
    transition: all 0.25s;
    cursor: default;
    position: relative;
    overflow: hidden;
  }
  .skill-chip::after {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    opacity: 0;
    transition: opacity 0.25s;
  }
  .skill-chip:hover { border-color: var(--accent); transform: scale(1.05); }
  .skill-chip:hover::after { opacity: 0.08; }
  .skill-chip .skill-icon { font-size: 24px; display: block; margin-bottom: 6px; }

  /* ── LEARNING ── */
  .learning-bar-wrap { margin-bottom: 20px; }
  .learning-bar-header {
    display: flex;
    justify-content: space-between;
    font-size: 14px;
    margin-bottom: 8px;
    font-weight: 600;
  }
  .learning-bar-track {
    height: 6px;
    background: var(--surface);
    border-radius: 100px;
    overflow: hidden;
    border: 1px solid var(--border);
  }
  .learning-bar-fill {
    height: 100%;
    border-radius: 100px;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    width: 0%;
    transition: width 1.4s cubic-bezier(0.4,0,0.2,1) 0.3s;
    box-shadow: 0 0 12px rgba(0,212,255,0.5);
  }

  /* ── ABOUT CARD ── */
  .about-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 16px;
    padding: 36px;
    position: relative;
    overflow: hidden;
  }
  .about-card::before {
    content: '';
    position: absolute;
    top: -60px; right: -60px;
    width: 200px; height: 200px;
    background: radial-gradient(circle, rgba(0,212,255,0.08) 0%, transparent 70%);
    pointer-events: none;
  }
  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 24px;
  }
  .about-item {
    display: flex;
    align-items: flex-start;
    gap: 14px;
  }
  .about-icon {
    width: 40px; height: 40px;
    background: rgba(0,212,255,0.1);
    border: 1px solid rgba(0,212,255,0.2);
    border-radius: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
    flex-shrink: 0;
  }
  .about-label { font-size: 12px; color: var(--muted); margin-bottom: 4px; }
  .about-value { font-size: 15px; font-weight: 600; }

  /* ── SOCIAL ── */
  .social-row {
    display: flex;
    flex-wrap: wrap;
    gap: 14px;
  }
  .social-link {
    display: flex;
    align-items: center;
    gap: 10px;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 14px 20px;
    text-decoration: none;
    color: var(--text);
    font-size: 14px;
    font-weight: 600;
    transition: all 0.25s;
    cursor: none;
  }
  .social-link:hover {
    border-color: var(--accent);
    color: var(--accent);
    transform: translateY(-3px);
    box-shadow: 0 8px 30px rgba(0,212,255,0.12);
  }
  .social-link svg { width: 20px; height: 20px; }

  /* ── FOOTER ── */
  .footer {
    margin-top: 100px;
    padding-top: 40px;
    border-top: 1px solid var(--border);
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: gap;
    gap: 16px;
  }
  .footer-left {
    font-family: 'JetBrains Mono', monospace;
    font-size: 13px;
    color: var(--muted);
  }
  .footer-left span { color: var(--accent); }

  /* ── TERMINAL BLOCK ── */
  .terminal {
    background: #080d1a;
    border: 1px solid var(--border);
    border-radius: 14px;
    overflow: hidden;
    font-family: 'JetBrains Mono', monospace;
  }
  .terminal-bar {
    background: #0f1625;
    padding: 12px 16px;
    display: flex;
    align-items: center;
    gap: 8px;
    border-bottom: 1px solid var(--border);
  }
  .dot { width: 10px; height: 10px; border-radius: 50%; }
  .dot-r { background: #ff5f57; }
  .dot-y { background: #febc2e; }
  .dot-g { background: #28c840; }
  .terminal-title { font-size: 12px; color: var(--muted); margin-left: 8px; }
  .terminal-body { padding: 24px; font-size: 14px; line-height: 2; }
  .t-prompt { color: var(--accent2); }
  .t-cmd { color: var(--accent); }
  .t-string { color: #34d399; }
  .t-key { color: var(--accent3); }
  .t-comment { color: #475569; }
  .t-cursor {
    display: inline-block;
    width: 9px; height: 16px;
    background: var(--accent);
    vertical-align: text-bottom;
    animation: blink 1s step-end infinite;
    margin-left: 2px;
  }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(20px); }
    to   { opacity: 1; transform: none; }
  }
  @keyframes pulse {
    0%,100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.4; transform: scale(0.7); }
  }
  @keyframes blink {
    0%,100% { opacity: 1; }
    50% { opacity: 0; }
  }
  @keyframes scanLine {
    0% { left: -100%; }
    100% { left: 200%; }
  }
  @keyframes float {
    0%,100% { transform: translateY(0px); }
    50% { transform: translateY(-8px); }
  }

  @media (max-width: 600px) {
    .about-grid { grid-template-columns: 1fr; }
    .hero-name { letter-spacing: -2px; }
  }
</style>
</head>
<body>

<div class="cursor" id="cursor"></div>
<div class="cursor-trail" id="cursorTrail"></div>
<canvas id="stars"></canvas>
<div class="grid-overlay"></div>

<main>

  <!-- HERO -->
  <section class="hero">
    <div class="badge">
      <span class="badge-dot"></span>
      Available for opportunities
    </div>

    <h1 class="hero-name">
      <span class="line1">Vishal</span>
      <span class="line2">Gupta</span>
    </h1>

    <p class="hero-title">
      &lt; <span>FullStack Developer</span> /&gt; &nbsp;·&nbsp; India 🇮🇳
    </p>

    <p class="hero-desc">
      I build end-to-end digital experiences — from pixel-perfect frontends to
      robust backend systems. Currently leveling up in Node.js & Docker. 
      Passionate about clean code and scalable architecture.
    </p>

    <div class="hero-links">
      <a href="https://vsite.tech/" target="_blank" class="btn btn-primary">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
        vsite.tech
      </a>
      <a href="https://github.com/vishal4719" target="_blank" class="btn btn-ghost">
        <svg viewBox="0 0 24 24" width="16" height="16" fill="currentColor"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0 0 24 12c0-6.63-5.37-12-12-12z"/></svg>
        GitHub
      </a>
      <a href="mailto:vg2556519@gmail.com" class="btn btn-ghost">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
        Email
      </a>
    </div>

    <div class="scroll-hint">
      <div class="scroll-line"></div>
      scroll to explore
    </div>
  </section>

  <!-- TERMINAL -->
  <section class="section" id="s1">
    <div class="section-label">// whoami</div>
    <div class="terminal">
      <div class="terminal-bar">
        <div class="dot dot-r"></div>
        <div class="dot dot-y"></div>
        <div class="dot dot-g"></div>
        <span class="terminal-title">vishal@dev ~ profile.json</span>
      </div>
      <div class="terminal-body">
        <div><span class="t-prompt">❯</span> <span class="t-cmd">cat</span> profile.json</div>
        <div>{</div>
        <div>&nbsp;&nbsp;<span class="t-key">"name"</span>: <span class="t-string">"Vishal Gupta"</span>,</div>
        <div>&nbsp;&nbsp;<span class="t-key">"role"</span>: <span class="t-string">"FullStack Developer"</span>,</div>
        <div>&nbsp;&nbsp;<span class="t-key">"location"</span>: <span class="t-string">"India 🇮🇳"</span>,</div>
        <div>&nbsp;&nbsp;<span class="t-key">"currently_learning"</span>: [<span class="t-string">"NodeJs"</span>, <span class="t-string">"Docker"</span>],</div>
        <div>&nbsp;&nbsp;<span class="t-key">"contact"</span>: <span class="t-string">"vg2556519@gmail.com"</span>,</div>
        <div>&nbsp;&nbsp;<span class="t-key">"portfolio"</span>: <span class="t-string">"https://vsite.tech"</span>,</div>
        <div>&nbsp;&nbsp;<span class="t-key">"open_to_work"</span>: <span style="color:#f87171">true</span> <span class="t-comment">// hire me!</span></div>
        <div>}<span class="t-cursor"></span></div>
      </div>
    </div>
  </section>

  <!-- STATS -->
  <section class="section" id="s2">
    <div class="section-label">// metrics</div>
    <h2 class="section-title">By the numbers</h2>
    <div class="stats-grid">
      <div class="stat-card">
        <div class="stat-num" data-count="15">0</div>
        <div class="stat-label">Projects Built</div>
      </div>
      <div class="stat-card">
        <div class="stat-num" data-count="8">0</div>
        <div class="stat-label">Technologies Mastered</div>
      </div>
      <div class="stat-card">
        <div class="stat-num" data-count="2">0</div>
        <div class="stat-label">Cloud Platforms</div>
      </div>
      <div class="stat-card">
        <div class="stat-num" data-count="100">0</div>
        <div class="stat-label">% Passion for Code</div>
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section class="section" id="s3">
    <div class="section-label">// stack</div>
    <h2 class="section-title">Tech Arsenal</h2>
    <div class="skills-grid">
      <div class="skill-chip"><span class="skill-icon">⚛️</span>React</div>
      <div class="skill-chip"><span class="skill-icon">🟩</span>Node.js</div>
      <div class="skill-chip"><span class="skill-icon">🐍</span>Python</div>
      <div class="skill-chip"><span class="skill-icon">☕</span>Java</div>
      <div class="skill-chip"><span class="skill-icon">🟨</span>JavaScript</div>
      <div class="skill-chip"><span class="skill-icon">🐘</span>PHP</div>
      <div class="skill-chip"><span class="skill-icon">🍃</span>MongoDB</div>
      <div class="skill-chip"><span class="skill-icon">🐬</span>MySQL</div>
      <div class="skill-chip"><span class="skill-icon">🐘</span>PostgreSQL</div>
      <div class="skill-chip"><span class="skill-icon">🐳</span>Docker</div>
      <div class="skill-chip"><span class="skill-icon">☁️</span>AWS</div>
      <div class="skill-chip"><span class="skill-icon">🔷</span>Azure</div>
      <div class="skill-chip"><span class="skill-icon">🔥</span>Firebase</div>
      <div class="skill-chip"><span class="skill-icon">⚡</span>Express</div>
      <div class="skill-chip"><span class="skill-icon">🎨</span>Tailwind</div>
      <div class="skill-chip"><span class="skill-icon">🔴</span>Redux</div>
      <div class="skill-chip"><span class="skill-icon">🎭</span>Figma</div>
      <div class="skill-chip"><span class="skill-icon">🌿</span>Git</div>
    </div>
  </section>

  <!-- LEARNING -->
  <section class="section" id="s4">
    <div class="section-label">// growth</div>
    <h2 class="section-title">Currently Learning</h2>
    <div class="learning-bar-wrap">
      <div class="learning-bar-header"><span>Node.js — Backend Mastery</span><span style="color:var(--accent)">75%</span></div>
      <div class="learning-bar-track"><div class="learning-bar-fill" data-width="75"></div></div>
    </div>
    <div class="learning-bar-wrap">
      <div class="learning-bar-header"><span>Docker — Containerization</span><span style="color:var(--accent)">60%</span></div>
      <div class="learning-bar-track"><div class="learning-bar-fill" data-width="60"></div></div>
    </div>
    <div class="learning-bar-wrap">
      <div class="learning-bar-header"><span>Cloud Architecture</span><span style="color:var(--accent)">50%</span></div>
      <div class="learning-bar-track"><div class="learning-bar-fill" data-width="50"></div></div>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="section" id="s5">
    <div class="section-label">// info</div>
    <h2 class="section-title">Quick Facts</h2>
    <div class="about-card">
      <div class="about-grid">
        <div class="about-item">
          <div class="about-icon">📍</div>
          <div>
            <div class="about-label">Location</div>
            <div class="about-value">India 🇮🇳</div>
          </div>
        </div>
        <div class="about-item">
          <div class="about-icon">💼</div>
          <div>
            <div class="about-label">Role</div>
            <div class="about-value">FullStack Developer</div>
          </div>
        </div>
        <div class="about-item">
          <div class="about-icon">📚</div>
          <div>
            <div class="about-label">Currently Learning</div>
            <div class="about-value">NodeJs & Docker</div>
          </div>
        </div>
        <div class="about-item">
          <div class="about-icon">📧</div>
          <div>
            <div class="about-label">Email</div>
            <div class="about-value">vg2556519@gmail.com</div>
          </div>
        </div>
        <div class="about-item">
          <div class="about-icon">🧩</div>
          <div>
            <div class="about-label">LeetCode</div>
            <div class="about-value">vishal_4719</div>
          </div>
        </div>
        <div class="about-item">
          <div class="about-icon">🚀</div>
          <div>
            <div class="about-label">Status</div>
            <div class="about-value" style="color:var(--accent)">Open to Work</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CONNECT -->
  <section class="section" id="s6">
    <div class="section-label">// connect</div>
    <h2 class="section-title">Let's Build Together</h2>
    <div class="social-row">
      <a class="social-link" href="https://vsite.tech/" target="_blank">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
        vsite.tech
      </a>
      <a class="social-link" href="https://github.com/vishal4719" target="_blank">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0 0 24 12c0-6.63-5.37-12-12-12z"/></svg>
        GitHub
      </a>
      <a class="social-link" href="https://www.linkedin.com/in/vishal-gupta-b99797260" target="_blank">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
        LinkedIn
      </a>
      <a class="social-link" href="https://instagram.com/vishal_4719" target="_blank">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"/><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"/><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"/></svg>
        Instagram
      </a>
      <a class="social-link" href="https://www.leetcode.com/vishal_4719" target="_blank">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M13.483 0a1.374 1.374 0 0 0-.961.438L7.116 6.226l-3.854 4.126a5.266 5.266 0 0 0-1.209 2.104 5.35 5.35 0 0 0-.125.513 5.527 5.527 0 0 0 .062 2.362 5.83 5.83 0 0 0 .349 1.017 5.938 5.938 0 0 0 1.271 1.818l4.277 4.193.039.038c2.248 2.165 5.852 2.133 8.063-.074l2.396-2.392c.54-.54.54-1.414.003-1.955a1.378 1.378 0 0 0-1.951-.003l-2.396 2.392a3.021 3.021 0 0 1-4.205.038l-.02-.019-4.276-4.193c-.652-.64-.972-1.469-.948-2.263a2.68 2.68 0 0 1 .066-.523 2.545 2.545 0 0 1 .619-1.164L9.13 8.114c1.058-1.134 3.204-1.27 4.43-.278l3.501 2.831c.593.48 1.461.387 1.94-.207a1.384 1.384 0 0 0-.207-1.943l-3.5-2.831c-.8-.647-1.766-1.045-2.774-1.202l2.015-2.158A1.384 1.384 0 0 0 13.483 0zm-2.866 12.815a1.38 1.38 0 0 0-1.38 1.382 1.38 1.38 0 0 0 1.38 1.382H20.79a1.38 1.38 0 0 0 1.38-1.382 1.38 1.38 0 0 0-1.38-1.382z"/></svg>
        LeetCode
      </a>
      <a class="social-link" href="mailto:vg2556519@gmail.com">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
        Email Me
      </a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer">
    <div class="footer-left">
      built with <span>♥</span> by Vishal Gupta &nbsp;·&nbsp; <span>2025</span>
    </div>
    <div class="footer-left">
      <span>vsite.tech</span>
    </div>
  </footer>

</main>

<script>
// ── Cursor ──
const cursor = document.getElementById('cursor');
const trail = document.getElementById('cursorTrail');
let mx = 0, my = 0, tx = 0, ty = 0;
document.addEventListener('mousemove', e => {
  mx = e.clientX; my = e.clientY;
  cursor.style.transform = `translate(${mx-6}px,${my-6}px)`;
});
function animTrail() {
  tx += (mx - tx) * 0.12;
  ty += (my - ty) * 0.12;
  trail.style.transform = `translate(${tx-18}px,${ty-18}px)`;
  requestAnimationFrame(animTrail);
}
animTrail();

// ── Stars ──
const canvas = document.getElementById('stars');
const ctx = canvas.getContext('2d');
let stars = [];
function resize() {
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
}
function initStars() {
  stars = [];
  for (let i = 0; i < 160; i++) {
    stars.push({
      x: Math.random() * canvas.width,
      y: Math.random() * canvas.height,
      r: Math.random() * 1.2 + 0.2,
      o: Math.random() * 0.7 + 0.1,
      speed: Math.random() * 0.15 + 0.05
    });
  }
}
function drawStars() {
  ctx.clearRect(0, 0, canvas.width, canvas.height);
  stars.forEach(s => {
    s.y -= s.speed;
    if (s.y < 0) s.y = canvas.height;
    ctx.beginPath();
    ctx.arc(s.x, s.y, s.r, 0, Math.PI * 2);
    ctx.fillStyle = `rgba(180,220,255,${s.o})`;
    ctx.fill();
  });
  requestAnimationFrame(drawStars);
}
window.addEventListener('resize', () => { resize(); initStars(); });
resize(); initStars(); drawStars();

// ── Scroll reveal ──
const obs = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      e.target.classList.add('visible');
      // Trigger counters
      e.target.querySelectorAll('[data-count]').forEach(el => animCount(el));
      // Trigger bars
      e.target.querySelectorAll('[data-width]').forEach(el => {
        setTimeout(() => el.style.width = el.dataset.width + '%', 100);
      });
    }
  });
}, { threshold: 0.15 });
document.querySelectorAll('.section').forEach(s => obs.observe(s));

// ── Count animation ──
function animCount(el) {
  const target = parseInt(el.dataset.count);
  let current = 0;
  const step = Math.ceil(target / 40);
  const timer = setInterval(() => {
    current = Math.min(current + step, target);
    el.textContent = current + (el.dataset.count === '100' ? '%' : '+');
    if (current >= target) clearInterval(timer);
  }, 35);
}

// ── Skill chip hover glow ──
document.querySelectorAll('.skill-chip').forEach(chip => {
  chip.addEventListener('mousemove', e => {
    const rect = chip.getBoundingClientRect();
    const x = ((e.clientX - rect.left) / rect.width * 100).toFixed(1);
    const y = ((e.clientY - rect.top) / rect.height * 100).toFixed(1);
    chip.style.background = `radial-gradient(circle at ${x}% ${y}%, rgba(0,212,255,0.12), var(--surface) 70%)`;
  });
  chip.addEventListener('mouseleave', () => {
    chip.style.background = '';
  });
});
</script>
</body>
</html>
