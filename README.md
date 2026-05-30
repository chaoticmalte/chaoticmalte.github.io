<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ChaoticMalte | Portfolio</title>
<style>
:root{
--bg:#0d1117;--card:#161b22;--border:#30363d;
--text:#f0f6fc;--accent:#00d4ff;--accent2:#7b61ff;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
font-family:Segoe UI,Arial,sans-serif;
background:var(--bg);
color:var(--text);
line-height:1.6;
overflow-x:hidden;
}
.container{max-width:1200px;margin:auto;padding:0 20px}
nav{
position:sticky;top:0;z-index:1000;
background:rgba(13,17,23,.9);
backdrop-filter:blur(10px);
border-bottom:1px solid var(--border);
}
.nav-inner{
display:flex;justify-content:space-between;align-items:center;
padding:16px 0;flex-wrap:wrap;gap:10px;
}
.nav-links{display:flex;gap:18px;flex-wrap:wrap}
.nav-links a{color:white;text-decoration:none}
.hero{
min-height:90vh;
display:flex;align-items:center;justify-content:center;
text-align:center;padding:80px 20px;
}
h1{
font-size:clamp(3rem,8vw,6rem);
background:linear-gradient(90deg,var(--accent),var(--accent2));
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}
.subtitle{font-size:clamp(1rem,2vw,1.3rem);color:#c9d1d9;margin:15px 0}
.badge{
display:inline-block;padding:10px 16px;border-radius:30px;
border:1px solid #2f6;background:#0f2a1c;color:#7dffb0;
}
.btn{
display:inline-block;margin-top:20px;padding:14px 24px;
background:var(--accent);color:black;text-decoration:none;
border-radius:10px;font-weight:bold;
}
section{padding:90px 0}
.section-title{
text-align:center;font-size:clamp(2rem,5vw,3rem);
color:var(--accent);margin-bottom:40px;
}
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;
}
.card{
background:var(--card);
border:1px solid var(--border);
border-radius:18px;
padding:24px;
}
.stats{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
}
.stat{text-align:center}
.stat h3{font-size:2rem;color:var(--accent)}
.progress{height:12px;background:#222;border-radius:999px;overflow:hidden;margin:8px 0 18px}
.fill{height:100%;background:linear-gradient(90deg,var(--accent),var(--accent2))}
footer{
border-top:1px solid var(--border);
padding:40px 20px;text-align:center;color:#9aa4af
}
</style>
</head>
<body>

<nav>
<div class="container nav-inner">
<div><strong>ChaoticMalte</strong></div>
<div class="nav-links">
<a href="#about">Über mich</a>
<a href="#projects">Projekte</a>
<a href="#skills">Skills</a>
<a href="#contact">Kontakt</a>
</div>
</div>
</nav>

<header class="hero">
<div>
<h1>ChaoticMalte</h1>
<p class="subtitle">Minecraft Entwickler • Server Administrator • Webentwickler</p>
<div class="badge">🟢 Verfügbar für neue Projekte</div><br>
<a href="#contact" class="btn">Kontakt</a>
</div>
</header>

<section id="about">
<div class="container">
<h2 class="section-title">Über mich</h2>
<div class="card">
Entwicklung von Minecraft Plugins, Server-Infrastrukturen, Webseiten sowie MySQL- und MariaDB-Lösungen.
Erfahrung mit Linux, Pterodactyl und individuellen Server-Systemen.
</div>
</div>
</section>

<section>
<div class="container">
<h2 class="section-title">Statistiken</h2>
<div class="stats">
<div class="card stat"><h3>5+</h3><p>Eigene Systeme</p></div>
<div class="card stat"><h3>20+</h3><p>Server Setups</p></div>
<div class="card stat"><h3>1000+</h3><p>Stunden Erfahrung</p></div>
<div class="card stat"><h3>&lt;24h</h3><p>Antwortzeit</p></div>
</div>
</div>
</section>

<section>
<div class="container">
<h2 class="section-title">Referenz</h2>
<div class="card">
<h3>ChunkBuild (bis 2024)</h3>
<p>Ehemaliger Minecraft-Server mit 20–50 täglichen Spielern.</p>
</div>
</div>
</section>

<section id="projects">
<div class="container">
<h2 class="section-title">Projekte</h2>
<div class="grid">
<div class="card"><h3>CaseOpening</h3></div>
<div class="card"><h3>Casino System</h3></div>
<div class="card"><h3>MOTD System</h3></div>
<div class="card"><h3>SMP Addon System</h3></div>
<div class="card"><h3>BanSystem</h3></div>
</div>
</div>
</section>

<section id="skills">
<div class="container">
<h2 class="section-title">Skills</h2>
<div class="card">
Java 95%
<div class="progress"><div class="fill" style="width:95%"></div></div>
Minecraft Entwicklung 95%
<div class="progress"><div class="fill" style="width:95%"></div></div>
MySQL / MariaDB 90%
<div class="progress"><div class="fill" style="width:90%"></div></div>
Pterodactyl 85%
<div class="progress"><div class="fill" style="width:85%"></div></div>
HTML / CSS 80%
<div class="progress"><div class="fill" style="width:80%"></div></div>
</div>
</div>
</section>

<section>
<div class="container">
<h2 class="section-title">Bewertungen</h2>
<div class="grid">
<div class="card">⭐⭐⭐⭐⭐<br><br>Sehr schnelle Umsetzung.<br><br>- Lukas</div>
<div class="card">⭐⭐⭐⭐⭐<br><br>Professionelle Zusammenarbeit.<br><br>- Max</div>
<div class="card">⭐⭐⭐⭐⭐<br><br>Sauberer Code und gute Kommunikation.<br><br>- Tom</div>
</div>
</div>
</section>

<section id="contact">
<div class="container">
<h2 class="section-title">Kontakt</h2>
<div class="card" style="text-align:center">
<h3>Discord</h3>
<p style="font-size:1.3rem;color:#00d4ff">hakubaa_</p>
<p>Antwortzeit normalerweise unter 24 Stunden.</p>
</div>
</div>
</section>

<footer>
ChaoticMalte • Minecraft Entwickler • Discord: hakubaa_
</footer>

</body>
</html>
