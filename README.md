<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>55 Club • Sure Shot VIP</title>
<meta name="description" content="55 Club VIP community landing page. Promotional UI. Play responsibly." />
<style>
*{box-sizing:border-box}
:root{
  --bg1:#020a06;--bg2:#071a12;--g1:#00ff9c;--g2:#9cffd2;--gold1:#ffd36a;--gold2:#ff9f0a;--cyan:#00c6ff;
}
html,body{height:100%}
body{
  margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;
  background:radial-gradient(1200px 600px at 50% -10%,#0b1f16 0%,var(--bg1) 60%);
  color:#eafff3;overflow-x:hidden
}
.wrap{max-width:420px;margin:0 auto;padding:28px 18px 18px}
.card{
  position:relative;overflow:hidden;border-radius:26px;padding:20px;
  background:linear-gradient(135deg,#071a12,#071327);
  box-shadow:0 20px 60px rgba(0,255,140,.25)
}
/* ambient glow ring */
.ambient{position:absolute;inset:-35%;pointer-events:none;
  background:conic-gradient(from 180deg at 50% 50%,rgba(0,255,156,.18),transparent 30%,rgba(255,191,0,.18),transparent 60%);
  animation:spin 14s linear infinite}
@keyframes spin{to{transform:rotate(360deg)}}
/* header */
.header{display:grid;place-items:center;gap:10px;animation:fadeUp .7s ease both}
@keyframes fadeUp{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}
.logo-wrap{position:relative;display:grid;place-items:center}
.logo-ring{position:absolute;width:140px;height:140px;border-radius:50%;background:conic-gradient(from 0deg,#ffd36a,#ff9f0a,#00ff9c,#ffd36a);filter:blur(2px);animation:ringSpin 6s linear infinite;opacity:.9}
@keyframes ringSpin{to{transform:rotate(360deg)}}
.logo-img{position:relative;z-index:2;width:110px;height:110px;border-radius:50%;object-fit:cover;
  box-shadow:0 0 25px rgba(255,191,0,.6),0 0 35px rgba(0,255,156,.45)}
.title{font-size:26px;font-weight:900;text-align:center;margin:6px 0}
.title .g{background:linear-gradient(135deg,var(--g1),var(--g2));-webkit-background-clip:text;background-clip:text;color:transparent}
.subtitle{font-size:20px;font-weight:900;text-align:center;margin:4px 0 10px;
  background:linear-gradient(90deg,#ffd36a,#ff9f0a,#fff1a8,#ff9f0a,#ffd36a);
  background-size:300% 300%;
  -webkit-background-clip:text;background-clip:text;color:transparent;
  animation:goldMove 3s linear infinite;
  filter:drop-shadow(0 0 16px rgba(255,191,0,.6))}
@keyframes goldMove{0%{background-position:0%}100%{background-position:100%}}
.badge{font-size:12px;font-weight:800;padding:6px 10px;border-radius:999px;
  background:linear-gradient(135deg,#0b2a1e,#0b1430);color:#bfffe3;box-shadow:inset 0 0 0 1px rgba(0,255,156,.25)}
/* list */
.list{margin:14px 0;display:grid;gap:10px;animation:fadeUp .9s .1s both}
.item{display:flex;gap:10px;align-items:flex-start;background:linear-gradient(135deg,#0b2a1e,#0b1430);border-radius:16px;padding:12px}
.item b{color:var(--g1)}
.item span{font-size:14px}
/* CTA */
.cta{position:relative;overflow:hidden;display:flex;align-items:center;justify-content:center;gap:10px;margin-top:16px;padding:16px;border-radius:20px;
  background:linear-gradient(135deg,var(--cyan),var(--g1));color:#002417;text-decoration:none;font-weight:900;font-size:18px;
  box-shadow:0 0 30px rgba(0,255,156,.7);animation:pulse 2.2s ease-in-out infinite}
.cta::after{content:"";position:absolute;inset:-40%;background:linear-gradient(120deg,transparent 40%,rgba(255,255,255,.6),transparent 60%);
  transform:translateX(-100%);animation:shine 2.5s infinite}
@keyframes shine{to{transform:translateX(100%)}}
@keyframes pulse{0%,100%{transform:translateZ(0) scale(1)}50%{transform:scale(1.03)}}
.note{font-size:11px;opacity:.75;text-align:center;margin-top:10px}
</style>
</head>
<body>
<div class="wrap">
  <div class="card">
    <div class="ambient"></div>
    <div class="header">
      <!-- Replace src with your uploaded image filename -->
      <div class="logo-wrap">
        <div class="logo-ring"></div>
        <img class="logo-img" src="55club.png" alt="55 Club" />
      </div>
      <div class="badge">Premium Community</div>
      <div style="height:4px"></div>
      <div class="title"><span class="g">55 CLUB SURE SHOT</span></div>
      <div class="subtitle">Join Free VIP Channel</div>
    </div><div class="list">
  <div class="item"><b>✔</b><span><b>Join Now for Making Money</b> with community insights & updates</span></div>
  <div class="item"><b>✔</b><span>Daily earning range: <b>₹2K – ₹25K</b> (varies)</span></div>
  <div class="item"><b>✔</b><span>Exclusive tips, bonuses & announcements</span></div>
  <div class="item"><b>✔</b><span>Fast updates • Mobile friendly • Secure access</span></div>
</div>

<a class="cta" href="https://t.me/+Am1tjEfej-MzZDVl" target="_blank" rel="noopener">🚀 Join Telegram Now</a>
<div class="note">Important: After clicking, open Telegram app and tap “Join”. Promotional UI • Play responsibly • 18+</div>

  </div>
</div>
</body>
</html>
