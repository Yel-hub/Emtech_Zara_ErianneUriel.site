<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#769656">
<title>Erianne Uriel Legaspi | Academic Portfolio</title>
<style>
:root{--green:#769656;--green-dark:#365b35;--green-deep:#243d29;--green-pale:#eef3e8;--cream:#f8faf5;--ink:#20291f;--muted:#687467;--white:#fff;--line:#dce5d5;--shadow:0 14px 38px rgba(35,61,41,.10)}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:var(--cream);color:var(--ink);font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
a{color:inherit;text-decoration:none}.wrap{width:min(1120px,92%);margin:auto}
header{position:sticky;top:0;z-index:10;background:rgba(255,255,255,.94);backdrop-filter:blur(14px);border-bottom:1px solid var(--line)}
.nav{height:72px;display:flex;align-items:center;justify-content:space-between;gap:20px}.brand{display:flex;align-items:center;gap:11px;font-weight:850;letter-spacing:-.03em}.knight{height:42px;width:42px;display:grid;place-items:center;background:var(--green);color:white;border-radius:13px;font-size:25px;box-shadow:0 5px 12px #76965655}.brand small{display:block;color:var(--muted);font-size:10px;letter-spacing:.13em;text-transform:uppercase;font-weight:750}
nav{display:flex;gap:22px;align-items:center}nav a{font-size:13px;font-weight:750;color:#52604f}nav a:hover{color:var(--green-dark)}.nav-cta,.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;background:var(--green-dark);color:white;padding:11px 17px;border-radius:11px;font-weight:800;font-size:13px;border:0;cursor:pointer}.nav-cta:hover,.btn:hover{background:#29472d}
.hero{padding:82px 0 64px;background:radial-gradient(circle at 85% 20%,#dce9d0 0,transparent 28%),linear-gradient(135deg,#f8faf5,#edf3e7);overflow:hidden}
.hero-grid{display:block;max-width:780px}.eyebrow{display:inline-flex;gap:8px;align-items:center;color:var(--green-dark);background:#e2ecd9;border:1px solid #d0dfc4;border-radius:99px;padding:7px 12px;font-size:11px;font-weight:850;letter-spacing:.11em;text-transform:uppercase}
h1{font-size:clamp(42px,6vw,68px);line-height:1.04;letter-spacing:-.06em;margin:20px 0 18px;max-width:680px}h1 span{color:var(--green)}.lead{font-size:17px;color:#5d6959;max-width:590px;margin:0 0 26px}.hero-actions{display:flex;gap:12px;flex-wrap:wrap}.btn.secondary{background:white;color:var(--green-dark);border:1px solid var(--line)}

section{padding:76px 0}.section-head{display:flex;justify-content:space-between;align-items:end;gap:20px;margin-bottom:28px}.kicker{color:var(--green);font-size:11px;font-weight:900;letter-spacing:.15em;text-transform:uppercase}.section-head h2{font-size:clamp(28px,4vw,40px);letter-spacing:-.045em;line-height:1.1;margin:7px 0 0}.section-head p{color:var(--muted);max-width:450px;margin:0;font-size:14px}
.about-grid{display:grid;grid-template-columns:.8fr 1.2fr;gap:22px}.profile-card,.about-copy,.file-card,.gallery-card,.compliance-card{background:white;border:1px solid var(--line);border-radius:18px;box-shadow:var(--shadow)}.profile-card{padding:26px;background:var(--green-dark);color:white;display:flex;flex-direction:column;justify-content:space-between;min-height:250px}.avatar{width:58px;height:58px;border-radius:18px;background:#ffffff22;display:grid;place-items:center;font-size:29px}.profile-card h3{font-size:24px;margin:22px 0 2px}.profile-card p{margin:0;color:#dce8d6;font-size:13px}.profile-meta{font-size:11px;color:#dce8d6;margin-top:24px;letter-spacing:.08em;text-transform:uppercase}.about-copy{padding:28px}.about-copy h3{margin:0 0 9px;font-size:22px}.about-copy p{color:var(--muted);font-size:14px;margin:0 0 14px}.chips{display:flex;gap:8px;flex-wrap:wrap;margin-top:18px}.chip{background:var(--green-pale);color:var(--green-dark);padding:7px 11px;border-radius:99px;font-size:11px;font-weight:800}
.portfolio{background:#f0f4eb}.portfolio-note{font-size:13px;color:var(--muted);margin:-10px 0 24px}.file-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}.file-card{padding:20px;display:flex;flex-direction:column;min-height:220px;transition:.2s}.file-card:hover{transform:translateY(-4px);box-shadow:0 18px 38px #243d2918}.file-icon{height:45px;width:45px;display:grid;place-items:center;background:var(--green-pale);color:var(--green-dark);border-radius:13px;font-size:22px}.file-card h3{font-size:16px;line-height:1.3;margin:16px 0 6px}.file-card p{font-size:12px;color:var(--muted);margin:0 0 18px}.file-link{margin-top:auto;color:var(--green-dark);font-size:12px;font-weight:900}
.gallery-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:18px}.poster{background:white;border:1px solid var(--line);border-radius:18px;padding:12px;box-shadow:var(--shadow)}.poster img{display:block;width:100%;height:auto;border-radius:11px}.gallery-info{padding:25px;background:var(--green-pale);border-radius:18px;display:flex;flex-direction:column;justify-content:center}.gallery-info h3{font-size:25px;line-height:1.15;margin:0 0 10px}.gallery-info p{font-size:13px;color:var(--muted);margin:0 0 18px}
footer{background:var(--green-deep);color:white;padding:32px 0}.foot{display:flex;justify-content:space-between;gap:18px;align-items:center}.foot p{margin:0;color:#cbd9c5;font-size:12px}.foot strong{font-size:14px}
@media(max-width:780px){nav{gap:12px}nav a{font-size:11px}.nav-cta{display:none}.hero-grid,.about-grid,.gallery-grid{grid-template-columns:1fr}.file-grid{grid-template-columns:repeat(2,1fr)}.section-head{display:block}.section-head p{margin-top:12px}}
@media(max-width:480px){.nav{height:64px}.brand{font-size:13px}.brand small{font-size:8px}nav{gap:10px}nav a:nth-child(2){display:none}.hero{padding:58px 0 48px}section{padding:58px 0}.file-grid{grid-template-columns:1fr}.foot{display:block}.foot p{margin-top:8px}}
</style>
</head>
<body>
<header><div class="wrap nav">
  <a class="brand" href="#home"><span class="knight">♞</span><span>ERIANNE'S PORTFOLIO<small>ACADEMIC • PERFORMANCE TASK</small></span></a>
  <nav><a href="#home">Home</a><a href="#about">About</a><a href="#portfolio">Portfolio</a></nav>
  <a class="nav-cta" href="#portfolio">Explore work ↗</a>
</div></header>
<main>
<section class="hero" id="home"><div class="wrap hero-grid">
  <div><span class="eyebrow">♟ Strategy • Creativity • Learning</span>
    <h1>Every move is a step toward <span>progress.</span></h1>
    <p class="lead">Welcome to my academic portfolio — a collection of learning outputs, projects, and performance tasks presented in one place.</p>
    <div class="hero-actions"><a class="btn" href="#portfolio">View my portfolio ↗</a><a class="btn secondary" href="#about">Get to know me</a></div>
  </div>
</div></section>
<section id="about"><div class="wrap"><div class="section-head"><div><div class="kicker">01 / Introduction</div><h2>About the student</h2></div><p>A little introduction to the student behind the work and the purpose of this portfolio.</p></div>
  <div class="about-grid"><div class="profile-card"><div><div class="avatar">♞</div><h3>Erianne Uriel Legaspi</h3><p>Student • Learner • Creator</p></div><div class="profile-meta">Academic Portfolio · 2026</div></div>
  <div class="about-copy"><h3>Learning one step at a time.</h3><p>This website serves as my digital portfolio for my teacher's performance task. It gathers my submitted activities and project outputs so they can be viewed and reviewed conveniently.</p><p>Like chess, learning takes patience, focus, planning, and the courage to make the next move. Each output represents an opportunity to develop new skills and improve.</p><div class="chips"><span class="chip">Creativity</span><span class="chip">Critical thinking</span><span class="chip">Digital skills</span><span class="chip">Continuous learning</span></div></div></div>
</div></section>
<section class="portfolio" id="portfolio"><div class="wrap"><div class="section-head"><div><div class="kicker">02 / Submitted work</div><h2>My portfolio</h2></div><p>Browse the three shared WPS documents and the cyberbullying infographic included in my performance task.</p></div>
  <p class="portfolio-note">My submitted performance task outputs.</p>
  <div class="file-grid">
    <article class="file-card"><div class="file-icon">▤</div><h3>PowerPoint Presentation</h3><p>Powerpoint_ErianneUrielLegaspi.pptx</p><a class="file-link" target="_blank" rel="noopener" href="https://ap.wps.com/cms/docs/d/cbRaqoan26XjIOyV?sa=601.1074&amp;refer=copylink">Open presentation ↗</a></article>
    <article class="file-card"><div class="file-icon">▦</div><h3>Infographics Spreadsheet</h3><p>Infographics_ErianneUrielLegaspi.xlsx</p><a class="file-link" target="_blank" rel="noopener" href="https://ap.wps.com/cms/docs/d/cbRaqeJUDw8uMcGK?sa=601.1074&amp;refer=copylink">Open file ↗</a></article>
    <article class="file-card"><div class="file-icon">▥</div><h3>Financial Dashboard</h3><p>FinancialDashboard_ErianneUrielLegaspi.xlsx</p><a class="file-link" target="_blank" rel="noopener" href="https://ap.wps.com/cms/docs/d/cbRaquK5Ay7VVSUt?sa=601.1074&amp;refer=copylink">Open dashboard ↗</a></article>
    <article class="file-card"><div class="file-icon">▧</div><h3>Cyberbullying Infographic</h3><p>Awareness infographic showing the definition, common forms, examples, and effects of cyberbullying.</p><a class="file-link" target="_blank" rel="noopener" href="assets/cyberbullying-infographic.jpeg">View infographic ↗</a></article>
  </div>
</div></section>

</main>
<footer><div class="wrap foot"><div><strong>♞ Erianne Uriel Legaspi</strong><p>Academic Portfolio · Performance Task</p></div><p>Designed with a chess-inspired green &amp; white theme.</p></div></footer>

</body></html>
