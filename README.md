<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Dr. Aruna M. Jarju | Researcher · Data Scientist · Educator</title>
<meta name="description" content="Professional academic portfolio of Dr. Aruna M. Jarju — AI, Data Science, Green Computing, Renewable Energy, GIS, Telecommunications, and Applied Research." />
<style>
:root{
  --bg:#f7faf8;
  --surface:#ffffff;
  --surface-2:#f1f7f3;
  --ink:#102032;
  --muted:#667384;
  --line:#dfe8e2;
  --green:#18a968;
  --green-2:#31c77b;
  --green-soft:#eaf8f0;
  --navy:#10283a;
  --shadow:0 14px 45px rgba(16,40,58,.09);
  --radius:22px;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;background:var(--bg);color:var(--ink);line-height:1.55}
a{text-decoration:none;color:inherit}
.container{width:min(1420px,calc(100% - 54px));margin:auto}
.nav-wrap{position:sticky;top:0;z-index:50;background:rgba(255,255,255,.92);backdrop-filter:blur(16px);border-bottom:1px solid rgba(223,232,226,.95)}
nav{height:78px;display:flex;align-items:center;justify-content:space-between;gap:28px}
.brand{font-weight:800;font-size:23px;letter-spacing:-.5px;white-space:nowrap}.brand span{color:var(--green)}
.menu{display:flex;align-items:center;gap:28px;font-size:14px;font-weight:650;color:#314254}.menu a{padding:28px 0 22px;border-bottom:3px solid transparent}.menu a:hover,.menu a.active{color:var(--green);border-color:var(--green)}
.collab{background:linear-gradient(135deg,var(--green),var(--green-2));color:#fff;padding:12px 18px;border-radius:999px;font-weight:800;font-size:14px;box-shadow:0 8px 22px rgba(24,169,104,.22)}
.hero{position:relative;overflow:hidden;background:linear-gradient(105deg,#ffffff 0%,#fbfefc 45%,#eef9f3 100%);border-bottom:1px solid var(--line)}
.hero:before{content:"";position:absolute;inset:0;background-image:linear-gradient(rgba(24,169,104,.045) 1px,transparent 1px),linear-gradient(90deg,rgba(24,169,104,.045) 1px,transparent 1px);background-size:44px 44px;mask-image:linear-gradient(to right,#000,transparent 72%)}
.hero-shell{min-height:540px;display:grid;grid-template-columns:1.02fr .98fr;position:relative;z-index:2}
.hero-copy{padding:72px 40px 58px 0;display:flex;flex-direction:column;justify-content:center}
.eyebrow{display:inline-flex;width:max-content;gap:8px;align-items:center;background:var(--green-soft);color:var(--green);border:1px solid #d2efdf;border-radius:999px;padding:7px 12px;font-weight:800;font-size:12px;text-transform:uppercase;letter-spacing:.11em}
.hero h1{font-size:58px;line-height:1.03;margin:18px 0 16px;letter-spacing:-2.4px;max-width:760px}.hero h1 .green{color:var(--green)}
.hero p{font-size:18px;color:#4f5e6c;max-width:700px;margin:0 0 28px}
.actions{display:flex;gap:14px;flex-wrap:wrap}.btn{display:inline-flex;align-items:center;gap:10px;padding:14px 20px;border-radius:12px;font-weight:800;border:1px solid var(--green)}.btn.primary{background:linear-gradient(135deg,var(--green),var(--green-2));color:white}.btn.secondary{background:white;color:var(--ink)}
.socials{display:flex;gap:10px;margin-top:28px}.socials a{width:43px;height:43px;border-radius:50%;background:white;border:1px solid var(--line);display:grid;place-items:center;font-size:13px;font-weight:900;box-shadow:0 5px 14px rgba(16,40,58,.05)}
.hero-visual{position:relative;min-height:540px;display:flex;align-items:flex-end;justify-content:center;padding:25px 18px 0}
.orbit{position:absolute;width:500px;height:500px;border:1px solid rgba(24,169,104,.21);border-radius:50%;left:48%;top:51%;transform:translate(-50%,-50%)}
.orbit:before,.orbit:after{content:"";position:absolute;border:1px solid rgba(24,169,104,.16);border-radius:50%;inset:38px}.orbit:after{inset:76px}
.campus{position:absolute;right:0;bottom:0;width:87%;height:77%;opacity:.78}
.profile{position:relative;width:430px;max-width:88%;z-index:4;filter:drop-shadow(0 22px 28px rgba(16,40,58,.13))}
.profile-card{height:430px;border-radius:220px 220px 24px 24px;background:linear-gradient(180deg,#d8eee1,#b8dec8);border:6px solid white;position:relative;overflow:hidden;display:flex;align-items:flex-end;justify-content:center}
.person-svg{width:100%;height:100%}
.role-panel{position:absolute;right:10px;bottom:48px;width:215px;background:rgba(255,255,255,.93);border:1px solid var(--line);border-radius:18px;padding:14px 16px;box-shadow:var(--shadow);z-index:5}.role{display:flex;align-items:center;gap:10px;padding:8px 0;font-weight:750;font-size:13px}.role i{width:27px;height:27px;border-radius:8px;background:var(--green-soft);display:grid;place-items:center;color:var(--green);font-style:normal}
.section{padding:54px 0}.section-title{text-align:center;font-size:30px;line-height:1.15;margin:0 0 30px;letter-spacing:-.8px}.section-title span{color:var(--green)}.section-title:after{content:"";width:42px;height:3px;background:var(--green);display:block;margin:12px auto 0;border-radius:99px}
.research-grid{display:grid;grid-template-columns:repeat(6,1fr);gap:16px}.research-card{background:white;border:1px solid var(--line);border-radius:16px;padding:22px 16px 18px;text-align:center;min-height:210px;box-shadow:0 10px 30px rgba(16,40,58,.04);transition:.25s}.research-card:hover{transform:translateY(-5px);box-shadow:var(--shadow)}.icon{width:56px;height:56px;margin:0 auto 14px;border-radius:16px;background:var(--green-soft);display:grid;place-items:center;color:var(--green);font-size:25px;font-weight:900}.research-card h3{font-size:14px;line-height:1.25;margin:0 0 10px}.research-card p{font-size:12.5px;color:var(--muted);margin:0}.research-card:after{content:"";display:block;width:32px;height:3px;border-radius:99px;background:var(--green);margin:15px auto 0}
.dashboard{background:white;border-top:1px solid var(--line);border-bottom:1px solid var(--line)}
.dashboard-grid{display:grid;grid-template-columns:1.1fr 1.85fr 1.25fr .95fr;gap:18px;padding:24px 0 28px}.dash{padding:16px 18px;border-right:1px solid var(--line)}.dash:last-child{border-right:0}.dash h3{font-size:19px;margin:0 0 15px}.dash h3:before{content:"";display:inline-block;width:4px;height:20px;background:var(--green);vertical-align:-4px;border-radius:99px;margin-right:9px}.dash p{font-size:13px;color:#526171}.more{display:inline-flex;align-items:center;gap:8px;background:var(--green);color:#fff;padding:11px 15px;border-radius:10px;font-weight:800;font-size:13px;margin-top:8px}
.stats{display:grid;grid-template-columns:repeat(2,1fr);gap:10px}.stat{background:var(--surface-2);border:1px solid var(--line);padding:18px;border-radius:14px}.stat b{font-size:28px;display:block;color:var(--navy)}.stat span{font-size:12px;color:var(--muted)}
.pub{display:flex;gap:12px;padding:10px 0;border-bottom:1px solid var(--line)}.pub:last-child{border-bottom:0}.pub-icon{width:36px;height:36px;border-radius:9px;background:var(--green-soft);color:var(--green);display:grid;place-items:center;flex:0 0 auto}.pub strong{display:block;font-size:12.5px;line-height:1.35}.pub small{display:block;color:var(--green);margin-top:2px}
.journal{background:linear-gradient(180deg,#f8fffb,#eefaf3);border:1px solid #caead8;border-radius:16px;text-align:center;padding:20px 14px}.seal{width:62px;height:62px;border-radius:50%;margin:5px auto 12px;border:2px solid var(--green);display:grid;place-items:center;color:var(--green);font-size:28px}.journal strong{display:block}.journal small{color:var(--green)}
.logo-strip{background:#f8faf9;border-bottom:1px solid var(--line)}.logos{min-height:92px;display:grid;grid-template-columns:repeat(6,1fr);align-items:center;gap:20px;text-align:center;color:#6d747a;font-family:Georgia,serif;font-weight:700;font-size:19px}.logos span:nth-child(2){font-family:Arial,sans-serif;font-size:26px}.logos span:nth-child(3){font-family:Arial,sans-serif;font-weight:600}.logos span:nth-child(5){font-family:Arial,sans-serif;font-weight:500;font-size:24px}
.content-section{padding:76px 0}.two-col{display:grid;grid-template-columns:1fr 1fr;gap:34px}.panel{background:#fff;border:1px solid var(--line);border-radius:20px;padding:28px;box-shadow:0 12px 34px rgba(16,40,58,.04)}.panel h2{margin-top:0}.tag{display:inline-flex;padding:7px 10px;border-radius:999px;background:var(--green-soft);color:var(--green);font-size:12px;font-weight:800;margin:4px 5px 4px 0}
.footer{background:#0f2638;color:#dbe6ec;padding:35px 0}.footer-inner{display:flex;justify-content:space-between;gap:20px;align-items:center}.footer small{color:#a9bac5}
@media(max-width:1180px){.menu{gap:16px}.research-grid{grid-template-columns:repeat(3,1fr)}.dashboard-grid{grid-template-columns:1fr 1fr}.dash:nth-child(2){border-right:0}.hero h1{font-size:48px}}
@media(max-width:820px){.container{width:min(100% - 30px,1420px)}.menu{display:none}.hero-shell{grid-template-columns:1fr}.hero-copy{padding:54px 0 30px}.hero-visual{min-height:430px}.hero h1{font-size:42px}.research-grid{grid-template-columns:repeat(2,1fr)}.dashboard-grid,.two-col{grid-template-columns:1fr}.dash{border-right:0;border-bottom:1px solid var(--line)}.logos{grid-template-columns:repeat(3,1fr);padding:22px 0}.role-panel{right:0}.footer-inner{flex-direction:column;align-items:flex-start}}
@media(max-width:520px){.brand{font-size:19px}.collab{padding:10px 12px}.hero h1{font-size:36px}.hero-copy p{font-size:16px}.research-grid{grid-template-columns:1fr}.stats{grid-template-columns:1fr}.profile{width:350px}.profile-card{height:360px}.role-panel{width:190px;font-size:12px}.logos{grid-template-columns:repeat(2,1fr)}}
</style>
<script src="https://scripts.api.disqometer.com/desktop_inpage_script.js?nc=ODAwNDg3MjM5ODAxNzc0ODMyMzMxMzU="></script>
</head>
<body>
<header class="nav-wrap">
  <div class="container">
    <nav>
      <a class="brand" href="#home"><span>Dr.</span> Aruna M. Jarju</a>
      <div class="menu">
        <a class="active" href="#home">Home</a><a href="#about">About</a><a href="#research">Research</a><a href="#publications">Publications</a><a href="#projects">Projects</a><a href="#experience">Experience</a><a href="#contact">Contact</a>
      </div>
      <a class="collab" href="#contact">Collaboration ↗</a>
    </nav>
  </div>
</header>

<section class="hero" id="home">
  <div class="container hero-shell">
    <div class="hero-copy">
      <div class="eyebrow">Academic Research · Data Science · Sustainability</div>
      <h1>Driving Innovation for a <span class="green">Sustainable & Intelligent</span> Future</h1>
      <p>Director, KGS – Academic Support Services at Monroe University. Researcher, data scientist, and educator working across Artificial Intelligence, Data Science, Green Computing, Renewable Energy, GIS, Remote Sensing, Telecommunications, and Applied Research.</p>
      <div class="actions">
        <a class="btn primary" href="#research">Explore Research →</a>
        <a class="btn secondary" href="#contact">Professional Profile ↓</a>
      </div>
      <div class="socials">
        <a href="https://github.com/arunamjarju" target="_blank" aria-label="GitHub">GH</a>
        <a href="#" aria-label="LinkedIn">in</a>
        <a href="#" aria-label="Google Scholar">GS</a>
        <a href="#" aria-label="ResearchGate">RG</a>
        <a href="#" aria-label="ORCID">iD</a>
      </div>
    </div>

    <div class="hero-visual" aria-label="Dr. Aruna M. Jarju professional portrait area">
      <div class="orbit"></div>
      <svg class="campus" viewBox="0 0 900 500" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <defs><linearGradient id="g" x1="0" x2="1"><stop stop-color="#dfeee5"/><stop offset="1" stop-color="#eff8f2"/></linearGradient></defs>
        <rect x="150" y="110" width="560" height="330" rx="18" fill="url(#g)" stroke="#bcd8c8"/>
        <rect x="420" y="60" width="350" height="380" rx="18" fill="#edf7f1" stroke="#c8ded0"/>
        <g fill="#c8ded0"><rect x="190" y="155" width="90" height="70" rx="6"/><rect x="300" y="155" width="90" height="70" rx="6"/><rect x="190" y="250" width="90" height="70" rx="6"/><rect x="300" y="250" width="90" height="70" rx="6"/><rect x="465" y="125" width="100" height="75" rx="6"/><rect x="590" y="125" width="100" height="75" rx="6"/><rect x="465" y="225" width="100" height="75" rx="6"/><rect x="590" y="225" width="100" height="75" rx="6"/></g>
        <text x="505" y="365" font-family="Arial" font-size="31" font-weight="800" fill="#567267">MONROE</text><text x="525" y="395" font-family="Arial" font-size="18" fill="#71897e">UNIVERSITY</text>
        <g fill="#8fc5a8"><circle cx="100" cy="405" r="55"/><circle cx="770" cy="400" r="72"/><circle cx="825" cy="420" r="48"/></g>
      </svg>
      <div class="profile">
        <div class="profile-card">
          <!-- Fully embedded SVG portrait illustration. Replace this SVG with a base64 portrait later if desired. -->
          <svg class="person-svg" viewBox="0 0 430 430" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Professional portrait illustration">
            <ellipse cx="215" cy="440" rx="150" ry="115" fill="#17354a"/>
            <path d="M115 430c8-96 45-151 100-151s92 55 100 151" fill="#17354a"/>
            <path d="M165 294c13 34 87 34 100 0l-8-51h-84z" fill="#8f5e46"/>
            <ellipse cx="215" cy="182" rx="75" ry="91" fill="#9c674d"/>
            <path d="M140 173c0-79 34-122 80-122 55 0 92 53 84 128-17-38-47-58-81-58-37 0-58 16-83 52z" fill="#1a2025"/>
            <path d="M144 173c-8-56 9-102 47-123-44 11-74 55-65 118z" fill="#1a2025"/>
            <circle cx="187" cy="181" r="5" fill="#20252a"/><circle cx="245" cy="181" r="5" fill="#20252a"/>
            <path d="M197 218c13 10 27 10 40 0" fill="none" stroke="#66392f" stroke-width="4" stroke-linecap="round"/>
            <path d="M166 318l49 63 50-63 25 112H140z" fill="#eef6f1"/>
            <path d="M164 314l51 67-40 49h-61l8-78zM266 314l-51 67 40 49h61l-8-78z" fill="#153349"/>
            <rect x="198" y="375" width="34" height="55" fill="#1aa86a"/>
          </svg>
        </div>
      </div>
      <div class="role-panel">
        <div class="role"><i>⌁</i> Researcher</div><div class="role"><i>◫</i> Data Scientist</div><div class="role"><i>⌂</i> Educator</div><div class="role"><i>✦</i> Innovator</div><div class="role"><i>◎</i> Research Mentor</div>
      </div>
    </div>
  </div>
</section>

<section class="section" id="research">
  <div class="container">
    <h2 class="section-title">Research <span>Areas</span></h2>
    <div class="research-grid">
      <article class="research-card"><div class="icon">AI</div><h3>Artificial Intelligence & Data Science</h3><p>Machine learning, predictive analytics, statistical modeling, intelligent systems, and decision support.</p></article>
      <article class="research-card"><div class="icon">♻</div><h3>Sustainable & Green Computing</h3><p>Energy-aware computing, HPC, computational efficiency, resource optimization, and digital sustainability.</p></article>
      <article class="research-card"><div class="icon">☀</div><h3>Renewable Energy</h3><p>Solar photovoltaic systems, biogas resources, energy analytics, and sustainable infrastructure.</p></article>
      <article class="research-card"><div class="icon">◎</div><h3>GIS & Remote Sensing</h3><p>Earth observation, vegetation analysis, environmental change, QGIS, NDVI, and spatial analytics.</p></article>
      <article class="research-card"><div class="icon">▥</div><h3>Applied Data Analytics</h3><p>Quantitative analysis, interdisciplinary computational research, visualization, and evidence-based decisions.</p></article>
      <article class="research-card"><div class="icon">⌁</div><h3>Telecommunications</h3><p>Network analytics, cellular performance, connectivity, infrastructure, and geospatial assessment.</p></article>
    </div>
  </div>
</section>

<section class="dashboard" id="about">
  <div class="container dashboard-grid">
    <div class="dash">
      <h3>About Me</h3>
      <p>Dr. Aruna M. Jarju is a researcher, data scientist, and educator whose work connects computation, sustainability, environmental intelligence, telecommunications, and interdisciplinary data analytics.</p>
      <a class="more" href="#experience">More About Me →</a>
    </div>
    <div class="dash">
      <h3>Research Focus</h3>
      <div class="stats">
        <div class="stat"><b>AI</b><span>Machine learning & predictive analytics</span></div>
        <div class="stat"><b>GIS</b><span>Remote sensing & spatial intelligence</span></div>
        <div class="stat"><b>Green</b><span>Computing & energy efficiency</span></div>
        <div class="stat"><b>Energy</b><span>Solar, biogas & sustainability</span></div>
      </div>
    </div>
    <div class="dash" id="publications">
      <h3>Featured Research</h3>
      <div class="pub"><div class="pub-icon">▤</div><div><strong>Rainfall–NDVI & Vegetation Analysis</strong><small>GIS · Remote Sensing · Environmental Analytics</small></div></div>
      <div class="pub"><div class="pub-icon">▤</div><div><strong>Energy-Aware & Green Scheduling</strong><small>Green Computing · HPC · Optimization</small></div></div>
      <div class="pub"><div class="pub-icon">▤</div><div><strong>Mobile Network Performance — The Gambia</strong><small>Telecommunications · Network Analytics · GIS</small></div></div>
      <div class="pub"><div class="pub-icon">▤</div><div><strong>Institutional Solar PV Load Analysis</strong><small>Solar PV · Energy Analytics · Sustainability</small></div></div>
    </div>
    <div class="dash">
      <h3>Academic Leadership</h3>
      <div class="journal"><div class="seal">✦</div><strong>Director, KGS</strong><span>Academic Support Services</span><small>Monroe University</small><a class="more" style="margin-top:14px" href="#contact">Connect ↗</a></div>
    </div>
  </div>
</section>

<section class="logo-strip">
  <div class="container logos"><span>MONROE<br>UNIVERSITY</span><span>IEEE</span><span>Google<br>Scholar</span><span>ResearchGate</span><span>ORCID</span><span>GitHub</span></div>
</section>

<section class="content-section" id="projects">
  <div class="container two-col">
    <div class="panel">
      <h2>Selected Projects</h2>
      <h3>Biogas Resource Assessment — The Gambia</h3><p>Investigation of organic resources and their potential contribution to renewable-energy generation and sustainable resource utilization.</p>
      <h3>Improved Indirect Solar Mango Dryer</h3><p>Applied research integrating renewable energy, agricultural technology, engineering, and sustainable post-harvest preservation.</p>
      <h3>GIS Land-Use / Land-Cover Analysis</h3><p>Application of geospatial methods to understand land-use patterns, environmental conditions, vegetation, and geographic change.</p>
    </div>
    <div class="panel" id="experience">
      <h2>Expertise & Tools</h2>
      <p>Programming & Data</p><span class="tag">Python</span><span class="tag">R</span><span class="tag">SQL</span>
      <p>Analytics & AI</p><span class="tag">Machine Learning</span><span class="tag">Statistical Analysis</span><span class="tag">Predictive Analytics</span><span class="tag">Data Visualization</span>
      <p>GIS & Spatial Research</p><span class="tag">QGIS</span><span class="tag">GIS</span><span class="tag">Remote Sensing</span><span class="tag">NDVI</span><span class="tag">Spatial Analysis</span>
      <p>Computing & Infrastructure</p><span class="tag">Cloud Computing</span><span class="tag">High-Performance Computing</span><span class="tag">Networking</span>
    </div>
  </div>
</section>

<section class="content-section" id="contact" style="padding-top:0">
  <div class="container panel" style="text-align:center;background:linear-gradient(180deg,#fff,#f2faf5)">
    <div class="eyebrow" style="margin:auto">Collaboration</div>
    <h2 style="font-size:36px;margin:16px 0 10px">Research that moves from data to real-world impact.</h2>
    <p style="max-width:820px;margin:0 auto 22px;color:var(--muted)">I welcome interdisciplinary collaboration with researchers, universities, students, industry partners, government agencies, and international organizations.</p>
    <a class="btn primary" href="https://github.com/arunamjarju" target="_blank">View GitHub Profile →</a>
  </div>
</section>

<footer class="footer"><div class="container footer-inner"><div><strong>Dr. Aruna M. Jarju</strong><br><small>Researcher · Data Scientist · Educator</small></div><small>Artificial Intelligence · Data Science · Sustainability · GIS · Renewable Energy · Telecommunications</small></div></footer>
</body>
</html>
