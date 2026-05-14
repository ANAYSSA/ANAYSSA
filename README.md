ANAYSSA — GitHub README Preview  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; } :root { --bg: #0a0c10; --surface: #111318; --surface2: #181c23; --border: rgba(255,255,255,0.07); --accent: #7ee787; --accent2: #58a6ff; --accent3: #f78166; --accent4: #d2a8ff; --text: #e6edf3; --muted: #7d8590; --font-display: 'Syne', sans-serif; --font-mono: 'JetBrains Mono', monospace; } body { background: var(--bg); color: var(--text); font-family: var(--font-mono); min-height: 100vh; padding: 2rem 1rem; } .readme-wrap { max-width: 860px; margin: 0 auto; } /* ── HEADER ── */ .header { position: relative; padding: 3rem 0 2rem; border-bottom: 1px solid var(--border); margin-bottom: 3rem; overflow: hidden; } .header-grid { display: grid; grid-template-columns: 1fr auto; gap: 2rem; align-items: start; position: relative; z-index: 2; } .grid-bg { position: absolute; inset: 0; opacity: 0.04; background-image: linear-gradient(var(--accent2) 1px, transparent 1px), linear-gradient(90deg, var(--accent2) 1px, transparent 1px); background-size: 40px 40px; z-index: 1; } .name-block h1 { font-family: var(--font-display); font-size: clamp(2.4rem, 6vw, 4rem); font-weight: 800; letter-spacing: -0.03em; line-height: 1; margin-bottom: 0.6rem; } .name-block h1 span { color: var(--accent); } .subtitle { font-size: 0.85rem; color: var(--muted); letter-spacing: 0.12em; text-transform: uppercase; margin-bottom: 1.4rem; } .tags { display: flex; flex-wrap: wrap; gap: 0.5rem; margin-bottom: 1.6rem; } .tag { font-size: 0.7rem; padding: 3px 10px; border-radius: 20px; border: 1px solid; letter-spacing: 0.05em; font-weight: 500; } .tag-green { color: var(--accent); border-color: rgba(126,231,135,0.3); background: rgba(126,231,135,0.07); } .tag-blue { color: var(--accent2); border-color: rgba(88,166,255,0.3); background: rgba(88,166,255,0.07); } .tag-red { color: var(--accent3); border-color: rgba(247,129,102,0.3); background: rgba(247,129,102,0.07); } .tag-purple{ color: var(--accent4); border-color: rgba(210,168,255,0.3); background: rgba(210,168,255,0.07); } .typing-line { font-size: 0.85rem; color: var(--muted); } .cursor { display: inline-block; width: 8px; height: 14px; background: var(--accent); vertical-align: middle; margin-left: 2px; animation: blink 1s step-end infinite; } @keyframes blink { 50% { opacity: 0; } } /* avatar SVG */ .avatar-wrap { flex-shrink: 0; } /* ── STATS ROW ── */ .stats-row { display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; margin-bottom: 3rem; } .stat-card { background: var(--surface); border: 1px solid var(--border); border-radius: 12px; padding: 1.2rem 1.4rem; position: relative; overflow: hidden; transition: border-color .2s, transform .2s; } .stat-card::before { content: ''; position: absolute; top: 0; left: 0; right: 0; height: 2px; } .stat-card.green::before { background: var(--accent); } .stat-card.blue::before { background: var(--accent2); } .stat-card.purple::before{ background: var(--accent4); } .stat-card:hover { transform: translateY(-2px); border-color: rgba(255,255,255,0.14); } .stat-num { font-family: var(--font-display); font-size: 2rem; font-weight: 800; line-height: 1; margin-bottom: 0.3rem; } .stat-card.green .stat-num { color: var(--accent); } .stat-card.blue .stat-num { color: var(--accent2); } .stat-card.purple .stat-num{ color: var(--accent4); } .stat-label { font-size: 0.72rem; color: var(--muted); letter-spacing: 0.08em; text-transform: uppercase; } /* ── SECTION TITLE ── */ .section-title { font-size: 0.72rem; color: var(--muted); letter-spacing: 0.15em; text-transform: uppercase; margin-bottom: 1rem; display: flex; align-items: center; gap: 0.75rem; } .section-title::after { content: ''; flex: 1; height: 1px; background: var(--border); } /* ── ABOUT ── */ .about-block { background: var(--surface); border: 1px solid var(--border); border-radius: 12px; padding: 1.8rem 2rem; margin-bottom: 3rem; position: relative; } .about-block .prompt { font-size: 0.75rem; color: var(--accent); margin-bottom: 1rem; } .about-block p { font-size: 0.88rem; line-height: 1.9; color: #b0bac6; margin-bottom: 0.9rem; } .about-block p:last-child { margin-bottom: 0; } .about-block .highlight { color: var(--accent2); } .about-block .highlight2 { color: var(--accent); } .about-block .highlight3 { color: var(--accent4); } /* ── STACK SVG ── */ .stack-section { margin-bottom: 3rem; } .stack-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(120px, 1fr)); gap: 0.75rem; } .stack-item { background: var(--surface); border: 1px solid var(--border); border-radius: 10px; padding: 1rem 0.8rem; text-align: center; transition: border-color .2s, transform .2s; cursor: default; } .stack-item:hover { border-color: rgba(255,255,255,0.18); transform: translateY(-3px); } .stack-item svg { width: 32px; height: 32px; margin-bottom: 0.5rem; } .stack-name { font-size: 0.72rem; color: var(--muted); letter-spacing: 0.05em; } /* ── PROJECTS ── */ .projects-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; margin-bottom: 3rem; } .project-card { background: var(--surface); border: 1px solid var(--border); border-radius: 12px; padding: 1.4rem 1.5rem; transition: border-color .2s, transform .2s; position: relative; overflow: hidden; } .project-card::after { content: ''; position: absolute; bottom: 0; right: 0; width: 80px; height: 80px; border-radius: 50%; opacity: 0.04; } .project-card.p1::after { background: var(--accent); } .project-card.p2::after { background: var(--accent2); } .project-card.p3::after { background: var(--accent4); } .project-card.p4::after { background: var(--accent3); } .project-card:hover { border-color: rgba(255,255,255,0.14); transform: translateY(-2px); } .project-header { display: flex; align-items: center; gap: 0.6rem; margin-bottom: 0.7rem; } .project-icon { width: 20px; height: 20px; flex-shrink: 0; } .project-name { font-size: 0.9rem; font-weight: 700; color: var(--text); } .project-desc { font-size: 0.78rem; color: var(--muted); line-height: 1.6; margin-bottom: 1rem; } .project-lang { display: flex; align-items: center; gap: 0.4rem; font-size: 0.7rem; color: var(--muted); } .lang-dot { width: 10px; height: 10px; border-radius: 50%; flex-shrink: 0; } /* ── ACTIVITY BAR ── */ .activity-section { margin-bottom: 3rem; } .activity-bar-wrap { background: var(--surface); border: 1px solid var(--border); border-radius: 12px; padding: 1.4rem 1.6rem; } .activity-row { display: flex; align-items: center; gap: 1rem; margin-bottom: 1rem; } .activity-row:last-child { margin-bottom: 0; } .activity-lang { font-size: 0.75rem; color: var(--muted); width: 70px; flex-shrink: 0; } .bar-bg { flex: 1; height: 6px; background: rgba(255,255,255,0.05); border-radius: 3px; overflow: hidden; } .bar-fill { height: 100%; border-radius: 3px; animation: grow 1.2s cubic-bezier(.4,0,.2,1) both; animation-delay: var(--d, 0s); } @keyframes grow { from { width: 0 !important; } } .bar-pct { font-size: 0.72rem; color: var(--muted); width: 32px; text-align: right; flex-shrink: 0; } /* ── FOOTER ── */ .footer-block { border-top: 1px solid var(--border); padding-top: 2rem; display: flex; align-items: center; justify-content: space-between; flex-wrap: gap; } .footer-left { font-size: 0.75rem; color: var(--muted); line-height: 1.8; } .footer-left span { color: var(--accent2); } .social-links { display: flex; gap: 0.75rem; } .social-btn { display: flex; align-items: center; gap: 0.5rem; font-size: 0.72rem; color: var(--muted); border: 1px solid var(--border); border-radius: 8px; padding: 0.4rem 0.8rem; text-decoration: none; transition: border-color .2s, color .2s; font-family: var(--font-mono); } .social-btn:hover { border-color: rgba(255,255,255,0.25); color: var(--text); } /* scrollbar */ ::-webkit-scrollbar { width: 6px; } ::-webkit-scrollbar-track { background: var(--bg); } ::-webkit-scrollbar-thumb { background: var(--border); border-radius: 3px; }
// fullstack developer
ANAYSSA
🐍 Python ⚡ Fullstack 📍 Astana, KZ 🎓 AITU
FULLSTACK ANAYSSA
7
repositories
4+
languages
∞
bugs fixed
about me
> cat about.txt
Привет, я Anuar — студент Astana IT University, пишу код потому что мне это реально нравится, а не просто потому что надо. Начинал с Java на парах по ООП, потом попробовал Python — и не смог остановиться.
Занимаюсь fullstack разработкой: с одной стороны пишу логику на Python, с другой — верстаю фронт. Один из моих проектов — AituSchedule, сайт который показывает свободные аудитории в универе. Увидел проблему → решил её кодом. Вот так и работаю.
Сейчас развиваюсь в вебе и автоматизации. Люблю когда код делает жизнь проще — хотя бы на чуть-чуть.
tech stack
Python
HTML/CSS
Java
C++
C++
Git
Web
projects
AituSchedule
Сайт для просмотра свободных аудиторий в AITU. Сделал потому что было нужно — теперь пользуются однокурсники.
HTML / JavaScript
JPEG → PNG Converter
Python скрипт для конвертации изображений. Просто и работает — batch обработка папок.
Python
Cinema Reservation
OOP-проект на Java — система бронирования кино. Полный цикл: залы, места, билеты.
Java
ADS Algorithms
Алгоритмы и структуры данных на C++. Лабы по ADS — сортировки, деревья, графы.
C++
languages used
Python
55%
HTML
25%
Java
12%
C++
8%
github.com/ANAYSSA  
Astana, Kazakhstan · AITU · building in public
github
const phrases = [ "student @ AITU, Astana", "python fullstack developer", "turning problems into code", "if it annoyed me — i automated it", ]; let pi = 0, ci = 0, deleting = false, pause = 0; const el = document.getElementById('typing'); function tick() { const phrase = phrases[pi]; if (pause > 0) { pause--; setTimeout(tick, 80); return; } if (!deleting) { el.textContent = phrase.slice(0, ++ci); if (ci === phrase.length) { deleting = true; pause = 20; } } else { el.textContent = phrase.slice(0, --ci); if (ci === 0) { deleting = false; pi = (pi + 1) % phrases.length; pause = 5; } } setTimeout(tick, deleting ? 40 : 80); } tick();
