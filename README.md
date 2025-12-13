# 55club-analysis
UI based analysis helper for educational purpose only
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>55 CLUB | Analysis Helper</title>
<meta name="description" content="Analysis helper UI. No guaranteed results.">
<style>
*{box-sizing:border-box}
body{margin:0;font-family:'Segoe UI',Arial,sans-serif;background:radial-gradient(circle at top,#0b1f4b,#02050c 70%);color:#fff;overflow-x:hidden}
.container{max-width:420px;margin:auto;padding:20px}
.hero{background:linear-gradient(135deg,#ffd36a,#ff4ecd);border-radius:22px;padding:26px;color:#111;box-shadow:0 0 40px rgba(0,170,255,.8)}
.badge{display:inline-block;padding:6px 12px;border-radius:20px;background:#000;color:#ffd36a;font-size:12px;font-weight:800}
h1{margin:10px 0;font-size:26px;font-weight:900}
.tagline{font-size:14px;line-height:1.6}
.cta{display:block;margin-top:18px;padding:16px;text-align:center;font-weight:900;text-decoration:none;border-radius:16px;background:linear-gradient(135deg,#000,#222);color:#fff}
.telegram{margin-top:14px;padding:14px;border-radius:16px;text-align:center;font-weight:900;background:linear-gradient(135deg,#0099ff,#00eaff)}
.telegram a{color:#fff;text-decoration:none}
.steps{margin-top:22px}
.step{background:#0d152e;margin-bottom:10px;padding:14px;border-radius:14px}
.footer{margin-top:20px;font-size:11px;opacity:.85;text-align:center}
/* GATE */
.overlay{position:fixed;inset:0;background:rgba(0,0,0,.88);z-index:1000;display:flex;align-items:center;justify-content:center}
.modal{background:#0f1630;border-radius:20px;max-width:360px;padding:24px;box-shadow:0 0 35px rgba(0,170,255,.9);text-align:center}
.actions{display:flex;gap:10px;margin-top:16px}
.actions a,.actions button{flex:1;padding:14px;border-radius:14px;border:0;font-weight:900;text-decoration:none}
.primary{background:linear-gradient(135deg,#ffd36a,#00eaff);color:#001}
.secondary{background:#333;color:#fff}
.hidden{display:none}
/* ANALYSIS */
.card{background:#0f1730;border-radius:16px;padding:16px;box-shadow:0 0 18px rgba(0,153,255,.35);margin-top:16px}
.bar{height:10px;border-radius:10px;background:#1b2a55;overflow:hidden;margin-top:6px}
.fill{height:100%}
.red{background:#ff4d4d}
.green{background:#2ecc71}
.violet{background:#9b59b6}
</style>
</head>
<body>
<div class="container">
  <div class="hero">
    <span class="badge">PREMIUM UI</span>
    <h1>55 CLUB ANALYSIS HELPER</h1>
    <p class="tagline">UI-based analysis helper. No guaranteed results. Educational use only.</p>
    <a class="cta" href="https://55clublive.site/#/register?invitationCode=838761740800" target="_blank">REGISTER VIA OFFICIAL LINK</a>
    <div class="telegram"><a href="https://t.me/+Q9-gc6xRyxwyYzBl" target="_blank">JOIN OFFICIAL TELEGRAM</a></div>
  </div>

  <div id="analysis" class="hidden">
    <div class="card">
      <b>Probability (UI Demo)</b>
      <div>Red <span id="r">--%</span><div class="bar"><div id="rb" class="fill red" style="width:0%"></div></div></div>
      <div>Green <span id="g">--%</span><div class="bar"><div id="gb" class="fill green" style="width:0%"></div></div></div>
      <div>Violet <span id="v">--%</span><div class="bar"><div id="vb" class="fill violet" style="width:0%"></div></div></div>
    </div>
  </div>

  <div class="steps">
    <div class="step">1️⃣ Register using our link</div>
    <div class="step">2️⃣ Join Telegram</div>
    <div class="step">3️⃣ Unlock analysis UI</div>
  </div>

  <div class="footer">⚠️ No guaranteed profit. Results depend on user decisions.</div>
</div>

<!-- GATE -->
<div id="gate" class="overlay">
  <div class="modal">
    <h2>Unlock Analysis</h2>
    <p>Register and join Telegram to continue.</p>
    <div class="actions">
      <a class="primary" href="https://55clublive.site/#/register?invitationCode=838761740800" target="_blank">Register</a>
      <a class="secondary" href="https://t.me/+Q9-gc6xRyxwyYzBl" target="_blank">Telegram</a>
    </div>
    <button class="primary" style="margin-top:12px;width:100%" onclick="unlock()">I have completed</button>
  </div>
</div>

<script>
function unlock(){
  document.getElementById('gate').classList.add('hidden');
  document.getElementById('analysis').classList.remove('hidden');
  demo();
}
function demo(){
  const r=Math.floor(Math.random()*60)+20;
  const g=Math.floor(Math.random()*(100-r));
  const v=100-r-g;
  document.getElementById('r').innerText=r+'%';
  document.getElementById('g').innerText=g+'%';
  document.getElementById('v').innerText=v+'%';
  document.getElementById('rb').style.width=r+'%';
  document.getElementById('gb').style.width=g+'%';
  document.getElementById('vb').style.width=v+'%';
}
</script>
</body>
</html>
