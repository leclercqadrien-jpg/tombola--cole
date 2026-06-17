
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tombola – École d'Hennuyères</title>
<link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;600;700;800;900&family=Patrick+Hand&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
<style>
:root { --mauve-dark:#5c5fa0; --yellow:#f9c74f; --green:#52b788; --red:#e63946; --dark:#1a1a2e; --radius:18px; }
* { box-sizing:border-box; margin:0; padding:0; }
body { font-family:'Nunito',sans-serif; background:linear-gradient(160deg,#6a5be2 0%,#9b59d0 30%,#d45cb3 60%,#e8625a 85%,#f4a444 100%); min-height:100vh; overflow-x:hidden; }
body::before { content:''; position:fixed; inset:0; background-image:radial-gradient(circle at 8% 12%,rgba(255,255,255,.18) 0%,transparent 28%),radial-gradient(circle at 92% 8%,rgba(255,255,255,.14) 0%,transparent 22%),radial-gradient(circle at 55% 88%,rgba(255,255,255,.12) 0%,transparent 30%); pointer-events:none; z-index:0; }
.bunting { width:100%; height:60px; flex-shrink:0; }
.page { display:none; position:relative; z-index:1; }
.page.active { display:flex; flex-direction:column; min-height:100vh; align-items:center; }
header { width:100%; padding:0 20px; display:flex; justify-content:space-between; align-items:center; }
.nav-btn { background:rgba(255,255,255,.2); border:2px solid rgba(255,255,255,.35); color:white; padding:7px 16px; border-radius:50px; cursor:pointer; font-family:'Nunito',sans-serif; font-weight:800; font-size:.82rem; transition:all .2s; }
.nav-btn:hover { background:rgba(255,255,255,.35); }
.school-name { font-family:'Patrick Hand',cursive; color:white; font-size:.95rem; text-align:center; margin-top:4px; text-shadow:0 1px 6px rgba(0,0,0,.4); font-weight:700; }
.main-title { font-family:'Fredoka One',cursive; font-size:clamp(3rem,12vw,5.5rem); color:#fff200; text-align:center; line-height:1; letter-spacing:3px; text-shadow:3px 3px 0 #a020a0,6px 6px 0 rgba(0,0,0,.25); }
.subtitle-fancy { font-family:'Patrick Hand',cursive; color:white; text-align:center; font-size:clamp(1.05rem,3.8vw,1.45rem); line-height:1.45; margin-top:8px; text-shadow:1px 2px 8px rgba(0,0,0,.45); font-weight:700; }
.balloons { display:flex; gap:4px; justify-content:center; margin:12px 0 6px; }
.balloon { font-size:clamp(2rem,7vw,3rem); animation:float 3s ease-in-out infinite; filter:drop-shadow(0 3px 6px rgba(0,0,0,.2)); }
.balloon:nth-child(2){animation-delay:.6s}.balloon:nth-child(3){animation-delay:1.2s}
@keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-8px)}}
.card { background:rgba(255,255,255,.92); border-radius:var(--radius); padding:30px 28px; width:min(460px,calc(100vw - 28px)); margin:16px auto; box-shadow:0 16px 50px rgba(0,0,0,.25); position:relative; }
.card::before { content:''; position:absolute; top:-5px; left:14px; right:14px; height:6px; background:linear-gradient(90deg,#e63946,#f4845f,#f9c74f,#52b788,#74c0e8,#7b7fc4); border-radius:50px; }
.input-label { font-weight:900; color:var(--mauve-dark); font-size:.88rem; text-transform:uppercase; letter-spacing:.8px; margin-bottom:10px; display:block; }
.ticket-input { font-family:'Fredoka One',cursive; font-size:2.2rem; text-align:center; letter-spacing:8px; border:3px solid #d8d8f0; border-radius:14px; padding:14px 10px; color:var(--dark); outline:none; transition:border-color .2s; width:100%; background:#f7f7fd; }
.ticket-input:focus{border-color:var(--mauve-dark);background:white}
.ticket-input::placeholder{color:#ccc;letter-spacing:4px;font-size:1.6rem}
.btn-main { display:block; width:100%; padding:16px; background:linear-gradient(135deg,#e63946,#f4845f,#f9c74f); color:white; border:none; border-radius:14px; font-family:'Fredoka One',cursive; font-size:1.35rem; cursor:pointer; margin-top:20px; letter-spacing:1px; box-shadow:0 6px 20px rgba(0,0,0,.2); transition:transform .15s; text-shadow:0 1px 3px rgba(0,0,0,.2); }
.btn-main:hover{transform:translateY(-2px)}.btn-main:active{transform:translateY(0)}
.result-box { display:none; margin-top:22px; border-radius:14px; padding:26px 20px; text-align:center; animation:popIn .4s cubic-bezier(.34,1.56,.64,1); }
@keyframes popIn{from{transform:scale(.8);opacity:0}to{transform:scale(1);opacity:1}}
.result-box.win{background:linear-gradient(135deg,#d8f5ee,#b7ede0);border:3px solid var(--green)}
.result-box.lose{background:linear-gradient(135deg,#fde8ea,#fcc9cd);border:3px solid var(--red)}
.result-emoji{font-size:3.2rem;display:block;margin-bottom:10px}
.result-title{font-family:'Fredoka One',cursive;font-size:1.7rem;margin-bottom:7px}
.win .result-title{color:#0a7a5b}.lose .result-title{color:#b91c2c}
.result-msg{font-weight:700;font-size:.95rem;color:#444;line-height:1.5}
.prize-badge{display:inline-block;background:var(--dark);color:var(--yellow);font-family:'Fredoka One',cursive;font-size:1.05rem;padding:10px 22px;border-radius:50px;margin-top:12px;letter-spacing:1px}
.locked-box{display:block;text-align:center;padding:30px 24px;background:rgba(255,255,255,.92);border-radius:var(--radius);width:min(460px,calc(100vw - 28px));margin:14px auto;box-shadow:0 16px 50px rgba(0,0,0,.25);position:relative}
.locked-box::before{content:'';position:absolute;top:-5px;left:14px;right:14px;height:6px;background:linear-gradient(90deg,#e63946,#f4845f,#f9c74f,#52b788,#74c0e8,#7b7fc4);border-radius:50px}
.lock-icon{font-size:3.5rem;display:block;margin-bottom:10px}
.lock-title{font-family:'Fredoka One',cursive;font-size:1.6rem;color:var(--mauve-dark);margin-bottom:8px}
.lock-msg{font-family:'Patrick Hand',cursive;font-size:1.12rem;color:#444;line-height:1.55;margin-bottom:20px}
.lock-msg strong{color:var(--mauve-dark);font-size:1.05em}
.countdown-grid{display:flex;gap:10px;justify-content:center;flex-wrap:wrap}
.cd-block{background:linear-gradient(135deg,var(--mauve-dark),#484a8a);border-radius:14px;padding:14px 12px;min-width:72px;text-align:center;box-shadow:0 4px 14px rgba(92,95,160,.35)}
.cd-num{font-family:'Fredoka One',cursive;font-size:2rem;color:white;display:block;line-height:1}
.cd-lbl{font-size:.72rem;color:rgba(255,255,255,.75);text-transform:uppercase;letter-spacing:.8px;margin-top:4px;display:block;font-weight:700}
.qr-section{background:rgba(0,0,0,.2);border:2px dashed rgba(255,255,255,.45);border-radius:var(--radius);padding:26px;width:min(460px,calc(100vw - 28px));margin:0 auto 40px;text-align:center;backdrop-filter:blur(4px)}
.qr-section h3{font-family:'Fredoka One',cursive;color:white;font-size:1.3rem;margin-bottom:4px;text-shadow:0 2px 6px rgba(0,0,0,.3)}
.qr-section p{color:rgba(255,255,255,.9);font-size:.88rem;margin-bottom:16px;font-weight:700}
#qrcode{display:flex;justify-content:center}
#qrcode canvas,#qrcode img{border-radius:12px;border:5px solid white}
.btn-print{margin-top:14px;background:rgba(255,255,255,.18);border:2px solid rgba(255,255,255,.35);color:white;padding:10px 24px;border-radius:50px;cursor:pointer;font-family:'Nunito',sans-serif;font-weight:800;font-size:.88rem;transition:background .2s}
.btn-print:hover{background:rgba(255,255,255,.3)}
#page-admin .card{width:min(680px,calc(100vw - 28px))}
.admin-title{font-family:'Fredoka One',cursive;font-size:1.55rem;color:var(--dark);margin-bottom:4px}
.admin-subtitle{color:#666;font-size:.88rem;margin-bottom:8px}
.admin-info{background:#fef9e7;border:2px solid #f9c74f;border-radius:12px;padding:14px 16px;margin-bottom:20px;font-size:.88rem;color:#7d6608;font-weight:700;line-height:1.5}
.section-label{font-weight:900;font-size:.78rem;text-transform:uppercase;letter-spacing:1px;color:#999;margin-bottom:8px}
.prize-rows{display:flex;flex-direction:column;gap:12px;margin-bottom:10px}
.prize-row{display:grid;grid-template-columns:1fr auto;gap:8px}
.prize-row input,.prize-row textarea{border:2px solid #e0e0e0;border-radius:10px;padding:10px 12px;font-family:'Nunito',sans-serif;font-weight:700;font-size:.92rem;outline:none;transition:border-color .2s;width:100%}
.prize-row input:focus,.prize-row textarea:focus{border-color:var(--mauve-dark)}
.prize-row textarea{resize:none;font-family:'Fredoka One',cursive;font-size:.95rem;letter-spacing:2px}
.del-btn{background:#fee2e2;border:none;color:var(--red);width:36px;height:36px;border-radius:10px;cursor:pointer;font-size:1.1rem;display:flex;align-items:center;justify-content:center;flex-shrink:0;align-self:start;transition:background .2s}
.del-btn:hover{background:#fca5a5}
.btn-add{background:#f0f0fa;border:2px dashed #b0b0dd;color:var(--mauve-dark);padding:10px 18px;border-radius:10px;cursor:pointer;font-family:'Nunito',sans-serif;font-weight:800;font-size:.88rem}
.btn-add:hover{background:#e4e4f8}
.divider{border:none;border-top:2px solid #f0f0f0;margin:22px 0}
.stats-bar{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:22px}
.stat-pill{background:#f4f4fc;border:2px solid #e0e0f0;border-radius:50px;padding:7px 16px;font-weight:800;font-size:.82rem;color:var(--dark)}
.stat-pill span{color:var(--mauve-dark)}
.datetime-row{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.form-input{width:100%;border:2px solid #e0e0e0;border-radius:10px;padding:10px 12px;font-family:'Nunito',sans-serif;font-weight:700;font-size:.92rem;outline:none;transition:border-color .2s}
.form-input:focus{border-color:var(--mauve-dark)}
.code-output{background:#1e1e2e;border-radius:14px;padding:20px;margin-top:20px;display:none}
.code-output label{color:#a8aad8;font-size:.8rem;font-weight:800;text-transform:uppercase;letter-spacing:1px;display:block;margin-bottom:8px}
.code-box{background:#0d0d1a;border-radius:10px;padding:14px;font-family:monospace;font-size:.8rem;color:#f9c74f;word-break:break-all;max-height:120px;overflow-y:auto;line-height:1.5}
.btn-copy{margin-top:12px;background:var(--mauve-dark);border:none;color:white;padding:10px 20px;border-radius:10px;cursor:pointer;font-family:'Nunito',sans-serif;font-weight:800;font-size:.88rem;transition:background .2s}
.btn-copy:hover{background:#484a8a}
.btn-copy.copied{background:#52b788}
.overlay{position:fixed;inset:0;background:rgba(0,0,0,.65);backdrop-filter:blur(6px);display:flex;align-items:center;justify-content:center;z-index:100}
.login-box{background:white;border-radius:var(--radius);padding:38px 30px;width:min(360px,calc(100vw - 40px));text-align:center;box-shadow:0 30px 80px rgba(0,0,0,.45)}
.login-box h2{font-family:'Fredoka One',cursive;font-size:1.75rem;color:var(--dark);margin-bottom:6px}
.login-box p{color:#666;font-size:.88rem;margin-bottom:22px}
.pwd-input{width:100%;padding:13px 16px;border:2px solid #e0e0e0;border-radius:12px;font-family:'Nunito',sans-serif;font-weight:700;font-size:1rem;outline:none;text-align:center;letter-spacing:4px;transition:border-color .2s}
.pwd-input:focus{border-color:var(--mauve-dark)}
.pwd-error{color:var(--red);font-size:.83rem;margin-top:8px;font-weight:800;display:none}
@media print{body>*:not(#print-area){display:none!important}#print-area{display:block!important}}
#print-area{display:none;text-align:center;padding:40px;font-family:'Nunito',sans-serif}
#print-area h2{font-family:'Fredoka One',cursive;font-size:2.2rem;margin-bottom:6px;color:#5c5fa0}
#print-qr{margin:20px auto;width:fit-content}
</style>
</head>
<body>

<!-- PAGE ACCUEIL -->
<div id="page-home" class="page active">
<svg class="bunting" viewBox="0 0 800 60" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
<polygon points="50,5 65,40 35,40" fill="#e63946"/><polygon points="110,5 125,40 95,40" fill="#f9c74f"/>
<polygon points="170,5 185,40 155,40" fill="#52b788"/><polygon points="230,5 245,40 215,40" fill="#74c0e8"/>
<polygon points="290,5 305,40 275,40" fill="#f4845f"/><polygon points="350,5 365,40 335,40" fill="#e8b4d4"/>
<polygon points="410,5 425,40 395,40" fill="#e63946"/><polygon points="470,5 485,40 455,40" fill="#f9c74f"/>
<polygon points="530,5 545,40 515,40" fill="#52b788"/><polygon points="590,5 605,40 575,40" fill="#74c0e8"/>
<polygon points="650,5 665,40 635,40" fill="#f4845f"/><polygon points="710,5 725,40 695,40" fill="#e8b4d4"/>
<polygon points="760,5 775,40 745,40" fill="#e63946"/>
<polyline points="0,5 50,5 110,5 170,5 230,5 290,5 350,5 410,5 470,5 530,5 590,5 650,5 710,5 760,5 800,5" stroke="rgba(255,255,255,0.55)" stroke-width="1.5" fill="none"/>
</svg>
<header>
<div style="width:80px"></div>
<div style="text-align:center"><div class="school-name" id="schoolNameDisplay">École communale d'Hennuyères</div></div>
<button class="nav-btn" onclick="openAdmin()">⚙️ Admin</button>
</header>
<div class="main-title">TOMBOLA</div>
<div class="subtitle-fancy" id="subtitleDisplay">Pour financer le chapiteau de la Fancy-fair</div>
<div class="balloons">
<span class="balloon">🎈</span>
<span class="balloon" style="font-size:2.4rem">🟡</span>
<span class="balloon">🎈</span>
</div>

<div class="locked-box" id="lockedBox">
<span class="lock-icon">🔒</span>
<div class="lock-title">Pas encore !</div>
<div class="lock-msg">Le tirage au sort aura lieu le<br><strong id="drawDateDisplay">—</strong><br>Revenez à ce moment-là pour découvrir si vous avez gagné !</div>
<div class="countdown-grid">
<div class="cd-block"><span class="cd-num" id="cd-j">--</span><span class="cd-lbl">Jours</span></div>
<div class="cd-block"><span class="cd-num" id="cd-h">--</span><span class="cd-lbl">Heures</span></div>
<div class="cd-block"><span class="cd-num" id="cd-m">--</span><span class="cd-lbl">Min</span></div>
<div class="cd-block"><span class="cd-num" id="cd-s">--</span><span class="cd-lbl">Sec</span></div>
</div>
</div>

<div class="card" id="checkCard" style="display:none">
<label class="input-label">🎟 Ton numéro de ticket</label>
<input type="text" class="ticket-input" id="ticketInput" maxlength="6" placeholder="0000"
oninput="this.value=this.value.replace(/[^0-9]/g,'')"
onkeydown="if(event.key==='Enter') checkTicket()">
<button class="btn-main" onclick="checkTicket()">🔍 Vérifier mon ticket</button>
<div class="result-box win" id="resultWin">
<span class="result-emoji">🎉</span>
<div class="result-title">Félicitations !</div>
<div class="result-msg">Ton ticket est gagnant !<br>Rends-toi au stand de la tombola pour récupérer :</div>
<div class="prize-badge" id="prizeLabel">—</div>
</div>
<div class="result-box lose" id="resultLose">
<span class="result-emoji">😢</span>
<div class="result-title">Pas de chance…</div>
<div class="result-msg">Ce ticket n'est pas gagnant.<br>Merci d'avoir soutenu notre école ! 💙</div>
</div>
</div>
</div>

<!-- PAGE ADMIN -->
<div id="page-admin" class="page">
<svg class="bunting" viewBox="0 0 800 60" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
<polygon points="50,5 65,40 35,40" fill="#e63946"/><polygon points="110,5 125,40 95,40" fill="#f9c74f"/>
<polygon points="170,5 185,40 155,40" fill="#52b788"/><polygon points="230,5 245,40 215,40" fill="#74c0e8"/>
<polyline points="0,5 800,5" stroke="rgba(255,255,255,0.55)" stroke-width="1.5" fill="none"/>
</svg>
<header>
<div style="width:90px"></div>
<div class="school-name">Configuration</div>
<button class="nav-btn" onclick="goHome()">← Retour</button>
</header>
<div style="height:20px"></div>
<div class="card">
<div class="admin-title">⚙️ Configuration</div>
<div class="admin-subtitle">Modifie les paramètres puis clique "Générer le code"</div>
<div class="admin-info">
💡 <strong>Comment ça marche :</strong><br>
1. Modifie les paramètres ci-dessous<br>
2. Clique <strong>"Générer le code"</strong><br>
3. Copie le code et colle-le dans <strong>index.html</strong> sur GitHub<br>
→ La config est immédiatement visible sur tous les appareils !
</div>
<div class="stats-bar" id="statsBar"></div>
<div class="section-label">⏰ Date & heure du tirage</div>
<div class="datetime-row" style="margin-bottom:6px">
<div><div class="section-label">Date</div><input type="date" id="drawDate" class="form-input"></div>
<div><div class="section-label">Heure</div><input type="time" id="drawTime" class="form-input"></div>
</div>
<hr class="divider">
<div class="section-label">🏫 Nom de l'école</div>
<input type="text" id="schoolName" class="form-input" style="margin-bottom:12px">
<div class="section-label">📝 Sous-titre</div>
<input type="text" id="eventSubtitle" class="form-input">
<hr class="divider">
<div class="section-label">🎟 Plage de tickets</div>
<div class="datetime-row">
<div><div class="section-label">Du n°</div><input type="number" id="ticketFrom" class="form-input" min="1"></div>
<div><div class="section-label">Au n°</div><input type="number" id="ticketTo" class="form-input" min="1"></div>
</div>
<hr class="divider">
<div class="section-label">🎁 Lots & numéros gagnants</div>
<div class="prize-rows" id="prizeRows"></div>
<button class="btn-add" onclick="addPrize()">+ Ajouter un lot</button>
<hr class="divider">
<div class="section-label">🔑 Mot de passe admin</div>
<input type="password" id="adminPwd" class="form-input" placeholder="Mot de passe actuel affiché dans le code">
<button class="btn-main" onclick="generateCode()" style="margin-top:24px">⚡ Générer le code à copier</button>
<div class="code-output" id="codeOutput">
<label>📋 Copie ce bloc et remplace la ligne CONFIG dans index.html sur GitHub :</label>
<div class="code-box" id="codeBox"></div>
<button class="btn-copy" id="copyBtn" onclick="copyCode()">📋 Copier le code</button>
<div style="margin-top:12px;font-size:.82rem;color:#aaa;line-height:1.5">
Sur GitHub → clique <strong style="color:#f9c74f">index.html</strong> → ✏️ crayon → cherche <strong style="color:#f9c74f">// ===CONFIG===</strong> → remplace tout le bloc → Commit
</div>
</div>
</div>
<div style="height:40px"></div>
</div>

<!-- LOGIN -->
<div class="overlay" id="loginOverlay" style="display:none">
<div class="login-box">
<h2>🔒 Accès Admin</h2>
<p>Entrez le mot de passe pour accéder à la configuration</p>
<input type="password" class="pwd-input" id="pwdInput" placeholder="••••••" onkeydown="if(event.key==='Enter') tryLogin()">
<div class="pwd-error" id="pwdError">Mot de passe incorrect !</div>
<button class="btn-main" onclick="tryLogin()" style="margin-top:16px">Connexion</button>
</div>
</div>

<div id="print-area">
<h2 id="printSubtitle">Tombola</h2>
<p id="printSchool">École communale d'Hennuyères</p>
<p>Scannez ce QR Code pour vérifier votre ticket</p>
<div id="print-qr"></div>
</div>

<script>
// ===CONFIG===
const CONFIG = {
  "eventSubtitle": "Pour financer le chapiteau de la Fancy-fair",
  "schoolName": "École communale d'Hennuyères",
  "ticketFrom": 1,
  "ticketTo": 500,
  "drawDateTime": "2026-06-25T12:00",
  "password": "ecole2024",
  "prizes": [
    { "label": "Robot pâtissier", "tickets": "42,137" },
    { "label": "Enceinte JBL", "tickets": "205,318" },
    { "label": "Casque audio JBL", "tickets": "77,444,12,299" },
    { "label": "Plancha", "tickets": "18" },
    { "label": "Gaufrier", "tickets": "5000" },
    { "label": "Bon cinéma", "tickets": "2596" },
    { "label": "Appareil à raclette", "tickets": "1236" },
    { "label": "Airfryer", "tickets": "4963" },
    { "label": "Trottinette", "tickets": "1111" },
    { "label": "Uno", "tickets": "2525" },
    { "label": "Mini vidéo projecteur", "tickets": "2363" },
    { "label": "Pili pili", "tickets": "852" },
    { "label": "Set de couteaux", "tickets": "963" },
    { "label": "Jeu Flip 7", "tickets": "1899" },
    { "label": "Montre connectée", "tickets": "3444" }
  ]
};
// ===END CONFIG===

function buildWinnerMap(cfg) {
  const map = {};
  (cfg.prizes||[]).forEach(p => {
    p.tickets.split(',').map(s=>s.trim()).filter(Boolean).forEach(t => {
      const n=parseInt(t,10); if(!isNaN(n)) map[n]=p.label;
    });
  });
  return map;
}
function getDrawDate(cfg) { return cfg.drawDateTime ? new Date(cfg.drawDateTime) : null; }
function isDrawPassed(cfg) { const d=getDrawDate(cfg); return d ? Date.now()>=d.getTime() : true; }
function formatDrawDate(cfg) {
  const d=getDrawDate(cfg); if(!d) return '—';
  return d.toLocaleDateString('fr-BE',{weekday:'long',day:'numeric',month:'long',year:'numeric'})
    +' à '+d.toLocaleTimeString('fr-BE',{hour:'2-digit',minute:'2-digit'});
}
function escHtml(s){return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;')}

let cdInterval=null;
function startCountdown(cfg) {
  clearInterval(cdInterval);
  function tick() {
    const d=getDrawDate(cfg); if(!d) return;
    const diff=d.getTime()-Date.now();
    if(diff<=0){clearInterval(cdInterval);initHome();return;}
    document.getElementById('cd-j').textContent=String(Math.floor(diff/86400000)).padStart(2,'0');
    document.getElementById('cd-h').textContent=String(Math.floor((diff%86400000)/3600000)).padStart(2,'0');
    document.getElementById('cd-m').textContent=String(Math.floor((diff%3600000)/60000)).padStart(2,'0');
    document.getElementById('cd-s').textContent=String(Math.floor((diff%60000)/1000)).padStart(2,'0');
  }
  tick(); cdInterval=setInterval(tick,1000);
}

function initHome() {
  document.getElementById('schoolNameDisplay').textContent = CONFIG.schoolName||'';
  document.getElementById('subtitleDisplay').textContent = CONFIG.eventSubtitle||'';
  document.getElementById('drawDateDisplay').textContent = formatDrawDate(CONFIG);
  if(isDrawPassed(CONFIG)){
    document.getElementById('lockedBox').style.display='none';
    document.getElementById('checkCard').style.display='block';
  } else {
    document.getElementById('lockedBox').style.display='block';
    document.getElementById('checkCard').style.display='none';
    startCountdown(CONFIG);
  }
}

function checkTicket() {
  const raw=document.getElementById('ticketInput').value.trim();
  if(!raw){alert('Entrez un numéro de ticket !');return;}
  const num=parseInt(raw,10);
  document.getElementById('resultWin').style.display='none';
  document.getElementById('resultLose').style.display='none';
  const map=buildWinnerMap(CONFIG);
  if(num>=CONFIG.ticketFrom&&num<=CONFIG.ticketTo&&map[num]){
    document.getElementById('prizeLabel').textContent=map[num];
    document.getElementById('resultWin').style.display='block';
  } else {
    document.getElementById('resultLose').style.display='block';
  }
}

function generateQR() {
  const url=window.location.href.split('?')[0].split('#')[0];
  document.getElementById('qrcode') && (document.getElementById('qrcode').innerHTML='');
  if(document.getElementById('qrcode')) {
    new QRCode(document.getElementById('qrcode'),{text:url,width:200,height:200,colorDark:'#1a1a2e',colorLight:'#ffffff',correctLevel:QRCode.CorrectLevel.H});
  }
}

function showPage(id){document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));document.getElementById(id).classList.add('active');window.scrollTo(0,0);}
function openAdmin(){document.getElementById('loginOverlay').style.display='flex';document.getElementById('pwdInput').value='';document.getElementById('pwdError').style.display='none';setTimeout(()=>document.getElementById('pwdInput').focus(),100);}
function tryLogin(){
  if(document.getElementById('pwdInput').value===CONFIG.password){
    document.getElementById('loginOverlay').style.display='none';
    showPage('page-admin');renderAdmin();
  } else {
    document.getElementById('pwdError').style.display='block';
    document.getElementById('pwdInput').value='';
  }
}
function goHome(){showPage('page-home');initHome();}

function renderAdmin() {
  document.getElementById('eventSubtitle').value=CONFIG.eventSubtitle||'';
  document.getElementById('schoolName').value=CONFIG.schoolName||'';
  document.getElementById('ticketFrom').value=CONFIG.ticketFrom||1;
  document.getElementById('ticketTo').value=CONFIG.ticketTo||500;
  document.getElementById('adminPwd').value=CONFIG.password||'';
  if(CONFIG.drawDateTime){
    document.getElementById('drawDate').value=CONFIG.drawDateTime.split('T')[0];
    document.getElementById('drawTime').value=CONFIG.drawDateTime.split('T')[1]||'12:00';
  }
  const map=buildWinnerMap(CONFIG);
  const total=(CONFIG.ticketTo-CONFIG.ticketFrom+1)||0;
  document.getElementById('statsBar').innerHTML=`
    <div class="stat-pill">🎟 Tickets : <span>${total}</span></div>
    <div class="stat-pill">🏆 Gagnants : <span>${Object.keys(map).length}</span></div>
    <div class="stat-pill">📦 Lots : <span>${CONFIG.prizes.length}</span></div>
    <div class="stat-pill">⏰ <span>${isDrawPassed(CONFIG)?'✅ Tirage passé':'🔒 En attente'}</span></div>`;
  const container=document.getElementById('prizeRows');
  container.innerHTML='';
  (CONFIG.prizes||[]).forEach((p,i)=>{
    const row=document.createElement('div');
    row.className='prize-row';
    row.innerHTML=`
      <div style="grid-column:1/-1;font-weight:900;color:#777;font-size:.75rem;text-transform:uppercase">Lot ${i+1} – Label</div>
      <input type="text" placeholder="Ex: Robot pâtissier" value="${escHtml(p.label)}" id="pl_${i}">
      <button class="del-btn" onclick="removePrize(${i})">✕</button>
      <div style="font-weight:900;color:#777;font-size:.75rem;text-transform:uppercase;margin-top:6px;grid-column:1/-1">Numéros gagnants (séparés par virgules)</div>
      <textarea rows="2" placeholder="42, 137, 205" id="pt_${i}">${escHtml(p.tickets)}</textarea>
      <div></div>`;
    container.appendChild(row);
  });
  document.getElementById('codeOutput').style.display='none';
}

function addPrize(){CONFIG.prizes.push({tickets:'',label:''});renderAdmin();}
function removePrize(i){CONFIG.prizes.splice(i,1);renderAdmin();}

function generateCode() {
  const dv=document.getElementById('drawDate').value;
  const tv=document.getElementById('drawTime').value||'12:00';
  const prizes=[];
  let i=0;
  while(document.getElementById(`pl_${i}`)!==null){
    prizes.push({label:document.getElementById(`pl_${i}`).value.trim(),tickets:document.getElementById(`pt_${i}`).value.trim()});
    i++;
  }
  const newCfg={
    eventSubtitle:document.getElementById('eventSubtitle').value.trim(),
    schoolName:document.getElementById('schoolName').value.trim(),
    ticketFrom:parseInt(document.getElementById('ticketFrom').value,10)||1,
    ticketTo:parseInt(document.getElementById('ticketTo').value,10)||500,
    drawDateTime:dv?dv+'T'+tv:CONFIG.drawDateTime,
    password:document.getElementById('adminPwd').value||CONFIG.password,
    prizes
  };
  const code=`const CONFIG = ${JSON.stringify(newCfg,null,2)};`;
  document.getElementById('codeBox').textContent=code;
  document.getElementById('codeOutput').style.display='block';
  document.getElementById('copyBtn').textContent='📋 Copier le code';
  document.getElementById('copyBtn').className='btn-copy';
  document.getElementById('codeOutput').scrollIntoView({behavior:'smooth'});
}

function copyCode(){
  const code=document.getElementById('codeBox').textContent;
  navigator.clipboard.writeText(code).then(()=>{
    const btn=document.getElementById('copyBtn');
    btn.textContent='✅ Copié !';
    btn.className='btn-copy copied';
  });
}

function printQR(){
  document.getElementById('print-qr').innerHTML=document.getElementById('qrcode').innerHTML;
  document.getElementById('printSubtitle').textContent=CONFIG.eventSubtitle||'Tombola';
  document.getElementById('printSchool').textContent=CONFIG.schoolName||'';
  window.print();
}

window.addEventListener('load',()=>{
  try { generateQR(); } catch(e) { console.warn('QR error:', e); }
  initHome();
});
</script>
</body>
</html>
