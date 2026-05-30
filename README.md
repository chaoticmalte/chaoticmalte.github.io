<!DOCTYPE html>
<html lang="de">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="description" content="ChaoticMalte — Minecraft Entwickler, Server Administrator und Webentwickler. Verfügbar für Projekte.">
	<meta name="author" content="ChaoticMalte">
	<title>ChaoticMalte | Portfolio</title>
	<style>
		*{margin:0;padding:0;box-sizing:border-box;font-family:Segoe UI,sans-serif;scroll-behavior:smooth}
		:root{--bg:#0d1117;--muted:#8b949e;--card:#161b22}
		.sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);white-space:nowrap;border:0}
		body{background:var(--bg);color:#fff;overflow-x:hidden}
		body:before{content:"";position:fixed;inset:0;background:
			linear-gradient(rgba(255,255,255,.03) 1px,transparent 1px),
			linear-gradient(90deg,rgba(255,255,255,.03) 1px,transparent 1px);
			background-size:40px 40px;z-index:-2}
		.glow{position:fixed;width:500px;height:500px;border-radius:50%;
			background:radial-gradient(circle,rgba(0,212,255,.15),transparent 70%);
			top:-150px;right:-150px;z-index:-1}
		nav{position:fixed;top:0;width:100%;background:rgba(13,17,23,.85);backdrop-filter:blur(12px);border-bottom:1px solid #30363d;z-index:1000}
		nav .wrap{max-width:1200px;margin:auto;padding:18px;display:flex;justify-content:space-between;align-items:center}
		nav a{color:#fff;text-decoration:none;margin-left:18px}
		header{min-height:100vh;display:flex;align-items:center;justify-content:center;text-align:center;padding:20px}
		h1{font-size:5rem;background:linear-gradient(90deg,#00d4ff,#7b61ff);-webkit-background-clip:text;-webkit-text-fill-color:transparent}
		.subtitle{font-size:1.2rem;color:#c9d1d9;margin:15px 0}
		.badge{display:inline-block;padding:10px 18px;border-radius:30px;background:#123;border:1px solid #2f6;color:#8f8}
		.btn{display:inline-block;margin-top:20px;padding:14px 24px;background:#00d4ff;color:#000;text-decoration:none;border-radius:10px;font-weight:bold}
		main{padding-top:84px}
		section{padding:90px 10%}
		.title{text-align:center;color:#00d4ff;font-size:2.4rem;margin-bottom:40px}
		.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:20px}
		.card{background:rgba(22,27,34,.85);border:1px solid #30363d;border-radius:18px;padding:24px;backdrop-filter:blur(8px);transition:transform .3s}
		.card:hover{transform:translateY(-5px)}
		.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:20px}
		.stat{text-align:center;background:var(--card);padding:25px;border-radius:15px;border:1px solid #30363d}
		.stat h2{color:#00d4ff;font-size:2.2rem}
		.progress{height:14px;background:#222;border-radius:20px;overflow:hidden;margin:8px 0 20px}
		.fill{height:100%;background:linear-gradient(90deg,#00d4ff,#7b61ff)}
		footer{text-align:center;padding:40px;border-top:1px solid #30363d;color:var(--muted)}
		.list-reset{list-style:none;padding-left:0;margin:0}
		@media(max-width:768px){h1{font-size:3rem} nav .links{display:none}}
	</style>
</head>
<body>
	<a class="sr-only" href="#main">Zum Inhalt springen</a>
	<div class="glow" aria-hidden="true"></div>

	<nav role="navigation" aria-label="Hauptnavigation">
		<div class="wrap">
			<div><b>ChaoticMalte</b></div>
			<div class="links">
				<a href="#about">Über mich</a>
				<a href="#stats">Statistiken</a>
				<a href="#projects">Projekte</a>
				<a href="#contact">Kontakt</a>
			</div>
		</div>
	</nav>

	<main id="main">
		<header>
			<div>
				<h1>ChaoticMalte</h1>
				<p class="subtitle">Minecraft Entwickler • Server Administrator • Webentwickler</p>
				<p class="badge" aria-hidden="true">🟢 Verfügbar für neue Projekte</p>
				<br>
				<a class="btn" href="#contact" aria-label="Zum Kontaktbereich springen">Kontakt aufnehmen</a>
			</div>
		</header>

		<section id="about" aria-labelledby="about-heading">
			<h2 id="about-heading" class="title">Über mich</h2>
			<article class="card">
				<p>Ich entwickle Minecraft Plugins, Server‑Systeme, Webseiten und Datenbanklösungen.</p>
				<p>Erfahrung mit Java, MySQL, MariaDB, Linux, Pterodactyl und individueller Server‑Infrastruktur.</p>
			</article>
		</section>

		<section id="stats" aria-labelledby="stats-heading">
			<h2 id="stats-heading" class="title">Statistiken</h2>
			<div class="stats">
				<div class="stat"><h2>5+</h2><p>Eigene Systeme</p></div>
				<div class="stat"><h2>20+</h2><p>Server Setups</p></div>
				<div class="stat"><h2>1000+</h2><p>Stunden Erfahrung</p></div>
				<div class="stat"><h2>&lt;24h</h2><p>Antwortzeit</p></div>
			</div>
		</section>

		<section aria-labelledby="ref-heading">
			<h2 id="ref-heading" class="title">Referenzprojekt</h2>
			<article class="card">
				<h3>🌍 ChunkBuild (bis 2024)</h3>
				<p>Ehemaliger eigener Minecraft‑Server mit 20–50 täglichen Spielern.</p>
				<ul class="list-reset" style="margin-top:10px">
					<li>Eigene Plugins</li>
					<li>Eigene Infrastruktur</li>
					<li>MySQL/MariaDB</li>
					<li>Serververwaltung &amp; Entwicklung</li>
				</ul>
			</article>
		</section>

		<section id="projects" aria-labelledby="projects-heading">
			<h2 id="projects-heading" class="title">Entwickelte Systeme</h2>
			<div class="grid">
				<div class="card"><h3>🎁 CaseOpening</h3><p>Kisten‑ und Belohnungssystem.</p></div>
				<div class="card"><h3>🎰 Casino</h3><p>Casino mit Wirtschaftssystem.</p></div>
				<div class="card"><h3>📢 MOTD System</h3><p>Dynamische MOTD Verwaltung.</p></div>
				<div class="card"><h3>🌍 SMP Addon</h3><p>Erweiterungen für SMP‑Server.</p></div>
				<div class="card"><h3>🔨 BanSystem</h3><p>Moderation mit Bans &amp; Mutes.</p></div>
			</div>
		</section>

		<section aria-labelledby="skills-heading">
			<h2 id="skills-heading" class="title">Skills</h2>
			<div class="card">
				<p>Java <strong>95%</strong></p>
				<div class="progress" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="95" aria-label="Java 95 Prozent"><div class="fill" style="width:95%"></div></div>

				<p>Minecraft Entwicklung <strong>95%</strong></p>
				<div class="progress" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="95" aria-label="Minecraft Entwicklung 95 Prozent"><div class="fill" style="width:95%"></div></div>

				<p>MySQL / MariaDB <strong>90%</strong></p>
				<div class="progress" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="90" aria-label="MySQL MariaDB 90 Prozent"><div class="fill" style="width:90%"></div></div>

				<p>Pterodactyl <strong>85%</strong></p>
				<div class="progress" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="85" aria-label="Pterodactyl 85 Prozent"><div class="fill" style="width:85%"></div></div>

				<p>HTML / CSS <strong>80%</strong></p>
				<div class="progress" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="80" aria-label="HTML CSS 80 Prozent"><div class="fill" style="width:80%"></div></div>
			</div>
		</section>

		<section aria-labelledby="reviews-heading">
			<h2 id="reviews-heading" class="title">Bewertungen</h2>
			<div class="grid">
				<div class="card">⭐⭐⭐⭐⭐<br><br>„Sehr schnelle Umsetzung und saubere Arbeit.“<br><br><small>– Lukas</small></div>
				<div class="card">⭐⭐⭐⭐⭐<br><br>„Professionelle Kommunikation und gutes Ergebnis.“<br><br><small>– Max</small></div>
				<div class="card">⭐⭐⭐⭐⭐<br><br>„Server lief direkt problemlos.“<br><br><small>– Tom</small></div>
			</div>
		</section>

		<section id="contact" aria-labelledby="contact-heading">
			<h2 id="contact-heading" class="title">Kontakt</h2>
			<div class="card" style="text-align:center">
				<h3>Discord</h3>
				<p style="margin-top:10px;font-size:1.2rem;color:#00d4ff">hakubaa_</p>
				<p style="margin-top:15px">Antwortzeit normalerweise unter 24 Stunden.</p>
			</div>
		</section>
	</main>

	<footer>
		<b>ChaoticMalte</b><br><br>
		Minecraft Entwickler • Server Administrator • Webentwickler<br><br>
		Discord: hakubaa_
	</footer>
</body>
</html>
