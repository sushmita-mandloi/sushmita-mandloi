<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Sushmita Mandloi | Data Analyst & Data Scientist</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@2.47.0/tabler-icons.min.css">
<style>
* { margin:0; padding:0; box-sizing:border-box; }
body { font-family: 'Segoe UI', sans-serif; }
.port { background: #0d0d1a; color: #e0e0f0; min-height: 100vh; padding-bottom: 3rem; }
.hero { background: linear-gradient(135deg, #0d0d1a 0%, #1a1040 50%, #0d0d1a 100%); padding: 2.5rem 2rem 2rem; text-align: center; border-bottom: 1px solid #2a1f5a; }
.hero h1 { font-size: 2.2rem; font-weight: 700; background: linear-gradient(90deg, #a78bfa, #38bdf8, #a78bfa); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; letter-spacing: -1px; }
.hero .subtitle { color: #94a3b8; font-size: 0.88rem; margin-top: 0.3rem; }
.hero-avatar { width: 100px; height: 100px; border-radius: 50%; border: 3px solid #7c3aed; margin: 0 auto 1rem; overflow: hidden; display: flex; align-items: center; justify-content: center; }
.hero-avatar img { width: 100%; height: 100%; object-fit: cover; object-position: center top; }
.badges { display: flex; flex-wrap: wrap; gap: 7px; justify-content: center; margin-top: 0.8rem; }
.badge { padding: 4px 11px; border-radius: 20px; font-size: 10px; font-weight: 700; letter-spacing: 0.4px; }
.b-purple { background: #2d1b69; color: #c4b5fd; border: 1px solid #5b21b6; }
.b-cyan { background: #0c2a3f; color: #67e8f9; border: 1px solid #0e7490; }
.b-green { background: #0f2a1e; color: #6ee7b7; border: 1px solid #059669; }
.b-orange { background: #2a1800; color: #fcd34d; border: 1px solid #b45309; }
.b-pink { background: #2a0f1e; color: #f9a8d4; border: 1px solid #9d174d; }
.social-links { display: flex; gap: 10px; justify-content: center; margin-top: 1rem; flex-wrap: wrap; }
.soc-btn { padding: 8px 14px; border-radius: 6px; font-size: 11px; font-weight: 600; text-decoration: none; border: 1px solid; display: flex; align-items: center; gap: 5px; cursor: pointer; }
.soc-linkedin { background: #0a2a4a; color: #60a5fa; border-color: #1d4ed8; }
.soc-github { background: #1a1a2e; color: #c4b5fd; border-color: #5b21b6; }
.soc-email { background: #2a0f0f; color: #fca5a5; border-color: #991b1b; }
.soc-phone { background: #0f2a1e; color: #34d399; border-color: #059669; }
.icon-only { padding: 8px 12px; }
.divider-accent { height: 2px; background: linear-gradient(90deg, transparent, #7c3aed, #38bdf8, transparent); }
.section { padding: 1.4rem 1.5rem 1rem; border-bottom: 1px solid #1e1b4b; }
.sec-title { font-size: 0.75rem; font-weight: 700; color: #a78bfa; display: flex; align-items: center; gap: 8px; margin-bottom: 1rem; text-transform: uppercase; letter-spacing: 1.2px; }
.sec-title::before { content: ''; display: inline-block; width: 3px; height: 14px; background: #7c3aed; border-radius: 2px; }
.about-text { font-size: 0.85rem; color: #cbd5e1; line-height: 1.75; }
.hl-purple { color: #a78bfa; font-weight: 600; }
.hl-cyan { color: #38bdf8; font-weight: 600; }
.hl-green { color: #34d399; font-weight: 600; }
.strength-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 9px; }
.strength-card { background: #12102a; border: 1px solid #2d1b69; border-radius: 10px; padding: 12px; }
.strength-card .icon { font-size: 1.2rem; margin-bottom: 5px; }
.strength-card h4 { font-size: 0.8rem; font-weight: 600; color: #c4b5fd; margin-bottom: 3px; }
.strength-card p { font-size: 0.72rem; color: #6b7280; line-height: 1.5; }
.timeline-item { display: flex; gap: 12px; margin-bottom: 1rem; }
.tl-dot-col { display: flex; flex-direction: column; align-items: center; padding-top: 4px; }
.tl-dot { width: 9px; height: 9px; border-radius: 50%; background: #7c3aed; flex-shrink: 0; }
.tl-line { width: 1px; background: #2d1b69; flex: 1; margin-top: 4px; }
.tl-content { padding-bottom: 4px; }
.tl-content h4 { font-size: 0.85rem; font-weight: 600; color: #e0e0f0; }
.tl-org { font-size: 0.75rem; color: #7c3aed; margin-bottom: 2px; }
.tl-date { font-size: 0.7rem; color: #4b5563; margin-bottom: 5px; }
.tl-content p { font-size: 0.75rem; color: #6b7280; line-height: 1.5; }
.tag-row { display: flex; flex-wrap: wrap; gap: 5px; margin-top: 6px; }
.tag { padding: 2px 8px; border-radius: 4px; font-size: 9px; font-weight: 700; }
.t-data { background: #0c2a3f; color: #38bdf8; }
.t-ai { background: #0f2a1e; color: #34d399; }
.t-dev { background: #2a1800; color: #fbbf24; }
.t-bi { background: #2a0f1e; color: #f9a8d4; }
.skills-section { display: flex; flex-direction: column; gap: 0.75rem; }
.skill-label { font-size: 0.7rem; color: #4b5563; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 6px; display: flex; align-items: center; gap: 5px; }
.skill-tags { display: flex; flex-wrap: wrap; gap: 6px; }
.sk { padding: 4px 11px; border-radius: 20px; font-size: 10px; font-weight: 600; }
.sk-py { background: #1c2a4a; color: #60a5fa; border: 1px solid #1d4ed8; }
.sk-sql { background: #0c2a3f; color: #38bdf8; border: 1px solid #0284c7; }
.sk-bi { background: #2a0f1e; color: #f9a8d4; border: 1px solid #9d174d; }
.sk-ml { background: #1a0c40; color: #c4b5fd; border: 1px solid #7c3aed; }
.sk-tool { background: #0f2a1e; color: #34d399; border: 1px solid #059669; }
.sk-misc { background: #1a1400; color: #fbbf24; border: 1px solid #b45309; }
.edu-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 9px; }
.edu-card { background: #12102a; border: 1px solid #2d1b69; border-radius: 10px; padding: 12px; }
.edu-card .edu-icon { font-size: 1.4rem; margin-bottom: 5px; }
.edu-card h4 { font-size: 0.8rem; font-weight: 600; color: #c4b5fd; }
.edu-card .edu-inst { font-size: 0.72rem; color: #38bdf8; margin-top: 2px; }
.edu-card .edu-yr { font-size: 0.68rem; color: #4b5563; margin-top: 2px; }
.cert-row { display: flex; gap: 8px; flex-wrap: wrap; margin-top: 9px; }
.cert-card { background: #12102a; border: 1px solid #2d1b69; border-radius: 10px; padding: 10px 12px; flex: 1; min-width: 130px; }
.cert-card .cert-ico { font-size: 1.1rem; margin-bottom: 3px; }
.cert-card h4 { font-size: 0.76rem; color: #c4b5fd; font-weight: 600; }
.cert-card .cert-sub { font-size: 0.67rem; color: #4b5563; margin-top: 2px; }
.github-stat-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; margin-bottom: 0.8rem; }
.gh-stat { background: #12102a; border: 1px solid #2d1b69; border-radius: 10px; padding: 10px; text-align: center; }
.gh-stat .num { font-size: 1.4rem; font-weight: 700; color: #a78bfa; }
.gh-stat .lbl { font-size: 0.65rem; color: #4b5563; margin-top: 2px; }
.lang-bar { display: flex; flex-direction: column; gap: 6px; }
.lang-item { display: flex; align-items: center; gap: 8px; }
.lang-dot { width: 9px; height: 9px; border-radius: 50%; flex-shrink: 0; }
.lang-name { font-size: 0.72rem; color: #cbd5e1; flex: 1; }
.lang-track { flex: 2; height: 4px; background: #1e1b4b; border-radius: 2px; overflow: hidden; }
.lang-fill { height: 100%; border-radius: 2px; }
.lang-pct { font-size: 0.68rem; color: #4b5563; min-width: 28px; text-align: right; }
.traits-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; }
.trait-card { background: #12102a; border: 1px solid #2d1b69; border-radius: 10px; padding: 10px; text-align: center; }
.trait-card .t-icon { font-size: 1.3rem; margin-bottom: 5px; }
.trait-card h4 { font-size: 0.72rem; font-weight: 600; color: #c4b5fd; margin-bottom: 3px; }
.trait-card p { font-size: 0.65rem; color: #6b7280; line-height: 1.4; }
.projects-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 9px; }
.proj-card { background: #12102a; border: 1px solid #2d1b69; border-radius: 10px; padding: 12px; }
.proj-card .proj-icon { font-size: 1.2rem; margin-bottom: 5px; }
.proj-card h4 { font-size: 0.8rem; font-weight: 600; color: #c4b5fd; margin-bottom: 4px; }
.proj-card p { font-size: 0.72rem; color: #6b7280; line-height: 1.5; }
.connect-section { text-align: center; padding: 1.5rem; }
.connect-section p { font-size: 0.8rem; color: #6b7280; margin-bottom: 1rem; }
.footer-note { font-size: 0.7rem; color: #374151; margin-top: 1rem; }
.pv-counter { display: flex; align-items: center; justify-content: center; gap: 10px; margin-top: 0.8rem; }
.pv-box { background: #12102a; border: 1px solid #2d1b69; border-radius: 20px; padding: 5px 16px; font-size: 10px; color: #a78bfa; font-weight: 700; display: flex; align-items: center; gap: 6px; }
.pv-box span { color: #38bdf8; font-size: 12px; font-weight: 800; }
@media (max-width: 600px) {
  .strength-grid, .edu-grid, .projects-grid, .traits-grid { grid-template-columns: 1fr 1fr; }
  .traits-grid { grid-template-columns: 1fr 1fr; }
}
</style>
</head>
<body>
<div class="port">

<div class="hero">
  <div class="hero-avatar">
    <img src="assets/profile.png" alt="Sushmita Mandloi" id="profileImg" />
  </div>
  <h1>Hi 👋, I'm Sushmita Mandloi</h1>
  <div class="subtitle">Integrated M.Tech · CSE (Computational &amp; Data Science) · VIT Bhopal University</div>
  <div class="subtitle" style="margin-top:3px;">📍 Ashta, Madhya Pradesh, India</div>
  <div class="badges">
    <span class="badge b-purple">DATA ANALYST</span>
    <span class="badge b-cyan">DATA SCIENTIST</span>
    <span class="badge b-green">SQL EXPERT</span>
    <span class="badge b-orange">POWER BI</span>
    <span class="badge b-pink">GSSOC 2026</span>
  </div>
  <div class="social-links">
    <a href="https://www.linkedin.com/in/sushmita-mandloi-6010112a8/" class="soc-btn soc-linkedin" target="_blank" rel="noopener"><i class="ti ti-brand-linkedin"></i> LinkedIn</a>
    <a href="https://github.com/sushmita-mandloi" class="soc-btn soc-github" target="_blank" rel="noopener"><i class="ti ti-brand-github"></i> GitHub</a>
    <a href="mailto:sushmitamandloi05@gmail.com" class="soc-btn soc-email icon-only" title="Email"><i class="ti ti-mail" style="font-size:16px;"></i></a>
    <a href="tel:9244168599" class="soc-btn soc-phone icon-only" title="Contact"><i class="ti ti-phone" style="font-size:16px;"></i></a>
  </div>
  <div class="pv-counter">
    <div class="pv-box"><i class="ti ti-eye" style="font-size:13px;"></i> Profile Views <span id="pv-num">—</span></div>
    <div class="pv-box"><i class="ti ti-star" style="font-size:13px;color:#fbbf24;"></i> ALS</div>
  </div>
</div>

<div class="divider-accent"></div>

<div class="section">
  <div class="sec-title"><i class="ti ti-user"></i> About Me</div>
  <p class="about-text">I'm a final-year <span class="hl-purple">Integrated M.Tech student</span> specializing in Computational and Data Science at VIT Bhopal University, actively targeting <span class="hl-cyan">Data Analyst and Data Science roles</span>. My technical toolkit spans Python, SQL, Power BI, and Excel — and I love turning raw data into meaningful stories.</p>
  <p class="about-text" style="margin-top:0.6rem;">I hold a <span class="hl-green">HackerRank 5-Star SQL badge</span> and Advanced SQL certification, completed a Data Science internship at CodeSoft, and am currently contributing to open-source projects as a <span class="hl-cyan">GSSoC 2026</span> contributor.</p>
  <p class="about-text" style="margin-top:0.6rem;">Beyond tech, I'm a creative soul — I enjoy <span class="hl-purple">painting, dance, and art &amp; craft</span>. I believe creativity and data thinking go hand in hand!</p>
</div>

<div class="section">
  <div class="sec-title"><i class="ti ti-bolt"></i> Core Strengths</div>
  <div class="strength-grid">
    <div class="strength-card"><div class="icon">🔍</div><h4>Data Storyteller</h4><p>Transforming raw datasets into clear, actionable insights using Python, SQL, and Power BI.</p></div>
    <div class="strength-card"><div class="icon">🧩</div><h4>Problem Solver</h4><p>Analytical thinker who tackles complex data problems with structured, creative solutions.</p></div>
    <div class="strength-card"><div class="icon">🤝</div><h4>Collaborative Worker</h4><p>Skilled at working in team environments and contributing to open-source projects globally.</p></div>
    <div class="strength-card"><div class="icon">📈</div><h4>Lifelong Learner</h4><p>Constantly upskilling — from SQL certifications to ML models and BI dashboards.</p></div>
  </div>
</div>

<div class="section">
  <div class="sec-title"><i class="ti ti-briefcase"></i> Professional Journey</div>
  <div class="timeline-item">
    <div class="tl-dot-col"><div class="tl-dot"></div><div class="tl-line"></div></div>
    <div class="tl-content">
      <h4>Data Science Intern</h4>
      <div class="tl-org">CodeSoft</div>
      <div class="tl-date">2024 · Internship</div>
      <p>Applied Python and ML techniques to real-world datasets, built predictive models, and performed end-to-end exploratory data analysis to derive business insights.</p>
      <div class="tag-row"><span class="tag t-data">PYTHON</span><span class="tag t-data">EDA</span><span class="tag t-ai">MACHINE LEARNING</span><span class="tag t-data">SQL</span></div>
    </div>
  </div>
  <div class="timeline-item">
    <div class="tl-dot-col"><div class="tl-dot"></div><div class="tl-line"></div></div>
    <div class="tl-content">
      <h4>GSSoC 2026 Contributor</h4>
      <div class="tl-org">GirlScript Summer of Code</div>
      <div class="tl-date">2026 · Open Source Contribution</div>
      <p>Contributing to real-world open source projects, enhancing coding skills, collaborating with developers worldwide, and building a portfolio of production-level code.</p>
      <div class="tag-row"><span class="tag t-dev">OPEN SOURCE</span><span class="tag t-dev">COLLABORATIVE DEVELOPMENT</span><span class="tag t-dev">CODE REVIEW</span></div>
    </div>
  </div>
  <div class="timeline-item">
    <div class="tl-dot-col"><div class="tl-dot"></div></div>
    <div class="tl-content">
      <h4>Data Analytics Portfolio Builder</h4>
      <div class="tl-org">Self-Initiated Project</div>
      <div class="tl-date">2024 – Present</div>
      <p>Building an end-to-end data analytics project using Python, SQL, and Power BI — covering data cleaning, EDA, SQL querying, and interactive dashboards.</p>
      <div class="tag-row"><span class="tag t-data">POWER BI</span><span class="tag t-data">PYTHON</span><span class="tag t-data">SQL</span><span class="tag t-bi">DASHBOARD</span></div>
    </div>
  </div>
</div>

<div class="section">
  <div class="sec-title"><i class="ti ti-folder"></i> Portfolio Projects</div>
  <div class="projects-grid">
    <div class="proj-card">
      <div class="proj-icon">🛍️</div>
      <h4>Customer Shopping Behavior Analysis</h4>
      <p>End-to-end analytics — data cleaning, SQL querying, EDA in Python, and Power BI dashboard for business insights.</p>
      <div class="tag-row"><span class="tag t-data">PYTHON</span><span class="tag t-data">SQL</span><span class="tag t-bi">POWER BI</span></div>
    </div>
    <div class="proj-card">
      <div class="proj-icon">🎬</div>
      <h4>Movie Rating Prediction</h4>
      <p>Random Forest Regression model to predict movie ratings from metadata, cast, and genre features.</p>
      <div class="tag-row"><span class="tag t-ai">RANDOM FOREST</span><span class="tag t-ai">SKLEARN</span><span class="tag t-data">PANDAS</span></div>
    </div>
  </div>
</div>

<div class="section">
  <div class="sec-title"><i class="ti ti-code"></i> Technical Skills</div>
  <div class="skills-section">
    <div class="skill-group">
      <div class="skill-label"><span>💻</span> Programming Languages</div>
      <div class="skill-tags"><span class="sk sk-py">Python</span><span class="sk sk-sql">SQL</span><span class="sk sk-misc">C++</span><span class="sk sk-misc">Java</span></div>
    </div>
    <div class="skill-group">
      <div class="skill-label"><span>📊</span> Data Analysis &amp; BI</div>
      <div class="skill-tags"><span class="sk sk-bi">Power BI</span><span class="sk sk-tool">Excel</span><span class="sk sk-py">Pandas</span><span class="sk sk-py">NumPy</span><span class="sk sk-py">Matplotlib</span><span class="sk sk-py">Seaborn</span></div>
    </div>
    <div class="skill-group">
      <div class="skill-label"><span>🤖</span> Machine Learning</div>
      <div class="skill-tags"><span class="sk sk-ml">Scikit-learn</span><span class="sk sk-ml">Random Forest</span><span class="sk sk-ml">TensorFlow</span><span class="sk sk-ml">Keras</span></div>
    </div>
    <div class="skill-group">
      <div class="skill-label"><span>🗄️</span> Databases</div>
      <div class="skill-tags"><span class="sk sk-sql">MySQL</span><span class="sk sk-sql">PostgreSQL</span><span class="sk sk-sql">Advanced SQL</span></div>
    </div>
    <div class="skill-group">
      <div class="skill-label"><span>🛠️</span> Tools &amp; Platforms</div>
      <div class="skill-tags"><span class="sk sk-tool">Jupyter Notebook</span><span class="sk sk-tool">Git &amp; GitHub</span><span class="sk sk-tool">VS Code</span><span class="sk sk-tool">Google Colab</span></div>
    </div>
  </div>
</div>

<div class="section">
  <div class="sec-title"><i class="ti ti-school"></i> Education &amp; Certifications</div>
  <div class="edu-grid">
    <div class="edu-card">
      <div class="edu-icon">🎓</div>
      <h4>Integrated M.Tech</h4>
      <div class="edu-inst">VIT Bhopal University</div>
      <div class="edu-yr">CSE – Computational &amp; Data Science</div>
      <div class="edu-yr">2020 – 2027 · Final Year</div>
    </div>
    <div class="edu-card">
      <div class="edu-icon">🏆</div>
      <h4>HackerRank 5-Star SQL</h4>
      <div class="edu-inst">HackerRank</div>
      <div class="edu-yr">Advanced SQL Badge · 2024</div>
      <div style="margin-top:6px;"><span class="badge b-cyan" style="font-size:9px;">5 ★ BADGE</span></div>
    </div>
  </div>
  <div class="cert-row">
    <div class="cert-card"><div class="cert-ico">📊</div><h4>Power BI Analytics</h4><div class="cert-sub">Microsoft · 2024</div></div>
    <div class="cert-card"><div class="cert-ico">🐍</div><h4>Python Programming</h4><div class="cert-sub">HackerRank · 2024</div></div>
    <div class="cert-card"><div class="cert-ico">🤖</div><h4>Data Science Intern</h4><div class="cert-sub">CodeSoft · 2024</div></div>
  </div>
</div>

<div class="section">
  <div class="sec-title"><i class="ti ti-chart-bar"></i> GitHub Stats</div>
  <div class="github-stat-grid">
    <div class="gh-stat"><div class="num">⭐</div><div class="lbl">Active Repos</div></div>
    <div class="gh-stat"><div class="num" style="color:#38bdf8;">GSSoC</div><div class="lbl">2026 Contributor</div></div>
    <div class="gh-stat"><div class="num" style="color:#34d399;">5★</div><div class="lbl">SQL Rating</div></div>
  </div>
  <div style="background:#12102a; border:1px solid #2d1b69; border-radius:10px; padding:12px;">
    <div style="font-size:0.68rem; color:#4b5563; font-weight:700; text-transform:uppercase; letter-spacing:1px; margin-bottom:8px;">Most Used Languages</div>
    <div class="lang-bar">
      <div class="lang-item"><div class="lang-dot" style="background:#3572A5;"></div><div class="lang-name">Python</div><div class="lang-track"><div class="lang-fill" style="width:50%;background:#3572A5;"></div></div><div class="lang-pct">50%</div></div>
      <div class="lang-item"><div class="lang-dot" style="background:#e38c00;"></div><div class="lang-name">SQL</div><div class="lang-track"><div class="lang-fill" style="width:30%;background:#e38c00;"></div></div><div class="lang-pct">30%</div></div>
      <div class="lang-item"><div class="lang-dot" style="background:#f1e05a;"></div><div class="lang-name">Jupyter Notebook</div><div class="lang-track"><div class="lang-fill" style="width:15%;background:#f1e05a;"></div></div><div class="lang-pct">15%</div></div>
      <div class="lang-item"><div class="lang-dot" style="background:#f34b7d;"></div><div class="lang-name">C++</div><div class="lang-track"><div class="lang-fill" style="width:5%;background:#f34b7d;"></div></div><div class="lang-pct">5%</div></div>
    </div>
  </div>
</div>

<div class="section">
  <div class="sec-title"><i class="ti ti-sparkles"></i> Personal Traits</div>
  <div class="traits-grid">
    <div class="trait-card"><div class="t-icon">🎨</div><h4>Creative Mind</h4><p>Love painting, dance &amp; art — creativity fuels my data thinking too!</p></div>
    <div class="trait-card"><div class="t-icon">🔄</div><h4>Adaptable</h4><p>Thriving in fast-changing environments and embracing new challenges.</p></div>
    <div class="trait-card"><div class="t-icon">🤝</div><h4>Team Player</h4><p>Collaborating effectively across diverse teams and open-source communities.</p></div>
    <div class="trait-card"><div class="t-icon">📚</div><h4>Lifelong Learner</h4><p>Always upskilling — SQL, ML, BI, or anything data-driven!</p></div>
    <div class="trait-card"><div class="t-icon">🎯</div><h4>Goal-Oriented</h4><p>Setting clear placement targets and working methodically to hit them.</p></div>
    <div class="trait-card"><div class="t-icon">💡</div><h4>Curious Analyst</h4><p>Always asking "why?" behind data patterns — the mark of a true analyst.</p></div>
  </div>
</div>

<div class="divider-accent"></div>

<div class="connect-section">
  <div class="sec-title" style="justify-content:center;"><i class="ti ti-antenna-bars-5"></i> Let's Connect and Collaborate!</div>
  <p>Open to Data Analyst &amp; Data Science roles, internships, and collaborations. Let's build something data-driven together! 🚀</p>
  <div class="social-links">
    <a href="https://www.linkedin.com/in/sushmita-mandloi-6010112a8/" class="soc-btn soc-linkedin" target="_blank" rel="noopener"><i class="ti ti-brand-linkedin"></i> LinkedIn</a>
    <a href="https://github.com/sushmita-mandloi" class="soc-btn soc-github" target="_blank" rel="noopener"><i class="ti ti-brand-github"></i> GitHub</a>
    <a href="mailto:sushmitamandloi05@gmail.com" class="soc-btn soc-email icon-only" title="Email"><i class="ti ti-mail" style="font-size:16px;"></i></a>
    <a href="tel:9244168599" class="soc-btn soc-phone icon-only" title="Contact"><i class="ti ti-phone" style="font-size:16px;"></i></a>
  </div>
  <div class="footer-note">😊 Thank you for visiting my portfolio!</div>
</div>

</div>
<script>
try {
  const k = 'sushmita_pv';
  let v = parseInt(localStorage.getItem(k) || '0') + 1;
  localStorage.setItem(k, v);
  const el = document.getElementById('pv-num');
  if(el) el.textContent = v.toLocaleString();
} catch(e) {}

const img = document.getElementById('profileImg');
if(img) {
  img.onerror = function() {
    this.parentElement.innerHTML = '<div style="width:100%;height:100%;background:#1e1b4b;display:flex;align-items:center;justify-content:center;font-size:2rem;font-weight:700;color:#a78bfa;">S</div>';
  };
}
</script>
</body>
</html>
