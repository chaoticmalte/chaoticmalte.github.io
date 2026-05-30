<html lang="de">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="description" content="ChaoticMalte — Minecraft Entwickler, Server Administrator und Webentwickler. Verfügbar für Projekte.">
	<meta name="author" content="ChaoticMalte">
	<title>ChaoticMalte | Premium Portfolio</title>
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
				<a id="nav-about" href="#about">Über mich</a>
				<a id="nav-stats" href="#stats">Statistiken</a>
				<a id="nav-projects" href="#projects">Projekte</a>
				<a id="nav-contact" href="#contact">Kontakt</a>
			</div>
			<div aria-label="Sprache wählen">
				<button id="lang-de" aria-pressed="true">DE</button>
				<button id="lang-en" aria-pressed="false">EN</button>
			</div>
		</div>
	</nav>

	<main id="main">
		<header>
			<div>
				<h1 id="hero-name">ChaoticMalte</h1>
				<p id="hero-sub" class="subtitle">Minecraft Entwickler • Server Administrator • Webentwickler</p>
				<p id="hero-badge" class="badge" aria-hidden="true">🟢 Verfügbar für neue Projekte</p>
				<br>
				<a id="hero-contact-btn" class="btn" href="#contact" aria-label="Zum Kontaktbereich springen">Kontakt aufnehmen</a>
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
			<div class="grid">
				<div class="card" style="text-align:center">
					<h3 id="contact-primary-title">Direkt kontaktieren</h3>
					<p style="margin-top:10px;font-size:1.1rem;color:#00d4ff" id="contact-discord">Discord: hakubaa_</p>
					<p style="margin-top:10px" id="contact-email">E-Mail: <a href="mailto:hakubaa@example.com" id="mailto-link">hakubaa@example.com</a></p>
					<p style="margin-top:10px">Antwortzeit normalerweise unter 24 Stunden.</p>
					<p style="margin-top:12px">
						<a id="link-telegram" href="https://t.me/hakubaa" target="_blank" rel="noopener">Telegram</a> ·
						<a id="link-whatsapp" href="https://wa.me/4915112345678" target="_blank" rel="noopener">WhatsApp</a> ·
						<a id="link-linkedin" href="https://www.linkedin.com/" target="_blank" rel="noopener">LinkedIn</a>
					</p>
				</div>

				<div class="card">
					<h3 id="contact-form-title">Kontaktformular</h3>
					<form id="contact-form" aria-label="Kontaktformular">
						<label for="c-name" id="lbl-name">Name</label>
						<input id="c-name" name="name" type="text" required placeholder="Dein Name" style="width:100%;margin-top:6px;padding:10px;border-radius:8px;border:1px solid #30363d;background:#0b0f13;color:#fff">

						<label for="c-email" id="lbl-email" style="margin-top:12px;display:block">E-Mail</label>
						<input id="c-email" name="email" type="email" required placeholder="dein@email.de" style="width:100%;margin-top:6px;padding:10px;border-radius:8px;border:1px solid #30363d;background:#0b0f13;color:#fff">

						<label for="c-country" id="lbl-country" style="margin-top:12px;display:block">Land</label>
						<select id="c-country" name="country" style="width:100%;margin-top:6px;padding:10px;border-radius:8px;border:1px solid #30363d;background:#0b0f13;color:#fff">
							<option value="DE">Germany</option>
							<option value="AT">Austria</option>
							<option value="CH">Switzerland</option>
							<option value="US">United States</option>
							<option value="GB">United Kingdom</option>
							<option value="OTHER">Other</option>
						</select>

						<label for="c-phone" id="lbl-phone" style="margin-top:12px;display:block">Telefon (optional)</label>
						<input id="c-phone" name="phone" type="tel" placeholder="+49 151 12345678" style="width:100%;margin-top:6px;padding:10px;border-radius:8px;border:1px solid #30363d;background:#0b0f13;color:#fff">

						<label for="c-msg" id="lbl-message" style="margin-top:12px;display:block">Nachricht</label>
						<textarea id="c-msg" name="message" rows="5" required placeholder="Schreibe mir..." style="width:100%;margin-top:6px;padding:10px;border-radius:8px;border:1px solid #30363d;background:#0b0f13;color:#fff"></textarea>

						<div style="margin-top:12px;display:flex;gap:8px;align-items:center">
							<button type="submit" id="contact-submit" class="btn">Senden</button>
							<button type="button" id="contact-reset" style="background:#222;color:#fff;padding:10px 14px;border-radius:8px;border:1px solid #30363d">Zurücksetzen</button>
						</div>
						<p id="contact-feedback" class="sr-only" role="status"></p>
					</form>
				</div>
			</div>
		</section>
	</main>

	<footer>
		<b>ChaoticMalte</b><br><br>
		Minecraft Entwickler • Server Administrator • Webentwickler<br><br>
		Discord: hakubaa_
	</footer>
	<script>
		(function(){
			const translations = {
				de: {
					'nav-about':'Über mich',
					'nav-stats':'Statistiken',
					'nav-projects':'Projekte',
					'nav-contact':'Kontakt',
					'hero-sub':'Minecraft Entwickler • Server Administrator • Webentwickler',
					'hero-badge':'🟢 Verfügbar für neue Projekte',
					'hero-contact-btn':'Kontakt aufnehmen',
					'about-heading':'Über mich',
					'stats-heading':'Statistiken',
					'ref-heading':'Referenzprojekt',
					'projects-heading':'Entwickelte Systeme',
					'skills-heading':'Skills',
					'reviews-heading':'Bewertungen',
					'contact-heading':'Kontakt',
					'contact-primary-title':'Direkt kontaktieren',
					'contact-discord':'Discord: hakubaa_',
					'contact-email':'E-Mail: ',
					'contact-form-title':'Kontaktformular',
					'lbl-name':'Name',
					'lbl-email':'E-Mail',
					'lbl-country':'Land',
					'lbl-phone':'Telefon (optional)',
					'lbl-message':'Nachricht',
					'contact-submit':'Senden',
				},
				en: {
					'nav-about':'About',
					'nav-stats':'Stats',
					'nav-projects':'Projects',
					'nav-contact':'Contact',
					'hero-sub':'Minecraft Developer • Server Admin • Web Developer',
					'hero-badge':'🟢 Available for new projects',
					'hero-contact-btn':'Contact',
					'about-heading':'About',
					'stats-heading':'Statistics',
					'ref-heading':'Reference Project',
					'projects-heading':'Built Systems',
					'skills-heading':'Skills',
					'reviews-heading':'Reviews',
					'contact-heading':'Contact',
					'contact-primary-title':'Contact directly',
					'contact-discord':'Discord: hakubaa_',
					'contact-email':'Email: ',
					'contact-form-title':'Contact form',
					'lbl-name':'Name',
					'lbl-email':'Email',
					'lbl-country':'Country',
					'lbl-phone':'Phone (optional)',
					'lbl-message':'Message',
					'contact-submit':'Send',
				}
			};

			const setLang = (lang) => {
				const map = translations[lang] || translations.de;
				document.documentElement.lang = lang;
				['nav-about','nav-stats','nav-projects','nav-contact','hero-sub','hero-badge','hero-contact-btn','contact-primary-title','contact-discord','contact-email','contact-form-title','lbl-name','lbl-email','lbl-country','lbl-phone','lbl-message'].forEach(id=>{
					const el = document.getElementById(id);
					if(!el) return;
					if(id === 'contact-email'){
						const mail = document.getElementById('mailto-link');
						el.innerHTML = map[id] + '<a href="mailto:hakubaa@example.com' + '">' + 'hakubaa@example.com' + '</a>';
						return;
					}
					if(el.tagName === 'INPUT' || el.tagName === 'TEXTAREA' || el.tagName === 'SELECT'){
						if(map[id]) el.placeholder = map[id];
						return;
					}
					el.textContent = map[id] || el.textContent;
				});
				// update buttons aria-pressed
				document.getElementById('lang-de').setAttribute('aria-pressed', String(lang==='de'));
				document.getElementById('lang-en').setAttribute('aria-pressed', String(lang==='en'));
			};

			document.getElementById('lang-de').addEventListener('click',()=>setLang('de'));
			document.getElementById('lang-en').addEventListener('click',()=>setLang('en'));

			// contact form handling: open mailto as fallback
			const form = document.getElementById('contact-form');
			const feedback = document.getElementById('contact-feedback');
			form.addEventListener('submit', (e)=>{
				e.preventDefault();
				const name = document.getElementById('c-name').value.trim();
				const email = document.getElementById('c-email').value.trim();
				const country = document.getElementById('c-country').value;
				const phone = document.getElementById('c-phone').value.trim();
				const msg = document.getElementById('c-msg').value.trim();
				if(!name || !email || !msg){
					feedback.textContent = 'Bitte alle Pflichtfelder ausfüllen.';
					feedback.classList.remove('sr-only');
					return;
				}
				const subject = encodeURIComponent('Kontaktanfrage von ' + name);
				const body = encodeURIComponent('Name: ' + name + '\nEmail: ' + email + '\nLand: ' + country + '\nTelefon: ' + phone + '\n\nNachricht:\n' + msg);
				const mailto = 'mailto:hakubaa@example.com?subject=' + subject + '&body=' + body;
				// try opening mail client
				window.location.href = mailto;
				feedback.textContent = 'E-Mail-Client geöffnet. Falls nicht, kopiere die E-Mail-Adresse und schreibe manuell.';
				feedback.classList.remove('sr-only');
			});

			document.getElementById('contact-reset').addEventListener('click', ()=>{
				form.reset();
				feedback.textContent = '';
				feedback.classList.add('sr-only');
			});

			// initialize default language
			setLang('de');
		})();
	</script>
</body>
</html>
