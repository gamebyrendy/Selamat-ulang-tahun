
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Selamat Ulang Tahun, Fira! dari bestfriend mu andeh&Rendy🎂🎉</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap" rel="stylesheet">
<style>
  :root{
    --bg1:#ffe6f7; --bg2:#e6f7ff; --bg3:#fff7e6;
    --card:#ffffffee; --text:#222; --accent:#ff4d88; --accent2:#6c5ce7; --good:#00c896;
  }
  *{box-sizing:border-box}
  html,body{height:100%;margin:0}
  body{
    font-family:Poppins,system-ui,-apple-system,Segoe UI,Roboto,Arial,Helvetica,sans-serif;
    color:var(--text);
    /* candy gradient */
    background:
      radial-gradient(40% 60% at 10% 10%, var(--bg1), transparent 60%),
      radial-gradient(50% 70% at 90% 15%, var(--bg2), transparent 60%),
      radial-gradient(60% 80% at 30% 90%, var(--bg3), transparent 60%),
      linear-gradient(135deg,#ffd3ec,#d7f2ff,#fff0cc);
    background-attachment: fixed;
    overflow-x:hidden;
  }

  /* floating balloons */
  .balloon{
    position:absolute; bottom:-15vh; width:60px; height:80px; border-radius:40px 40px 45px 45px;
    box-shadow: inset -6px -12px 30px #0001;
    animation: float 12s linear infinite;
    filter: drop-shadow(0 10px 20px #0002);
  }
  .balloon:after{
    content:""; position:absolute; left:50%; top:78%; width:2px; height:120px; background:#0002; transform:translateX(-50%);
  }
  @keyframes float{
    0%{transform:translateY(0) translateX(0) rotate(0)}
    50%{transform:translateY(-120vh) translateX(25px) rotate(2deg)}
    100%{transform:translateY(-240vh) translateX(-25px) rotate(-2deg)}
  }

  .wrap{max-width:980px;margin:auto;padding:28px}
  .hero{
    margin-top:24px;
    background:var(--card);
    border-radius:24px;
    padding:28px 22px;
    backdrop-filter: blur(6px);
    box-shadow: 0 18px 40px #00000022;
    position:relative; overflow:hidden;
  }
  .tag{
    display:inline-block; padding:6px 12px; border-radius:999px; font-weight:600; font-size:12px;
    background:linear-gradient(90deg,#ff9ac4,#b69cff); color:#fff; letter-spacing:.5px;
    box-shadow:0 6px 14px #ff4d8866;
  }
  h1{margin:10px 0 6px; font-size:clamp(26px,5vw,44px); line-height:1.1}
  .sub{opacity:.8; margin:0 0 12px}
  .photo{
    width:110px; height:110px; border-radius:20px; object-fit:cover; border:6px solid #fff; box-shadow:0 10px 24px #0001;
  }
  .grid{display:grid; grid-template-columns:1fr; gap:16px; margin-top:18px}
  @media(min-width:760px){ .grid{grid-template-columns: 1.1fr .9fr} .right{text-align:right} }

  .card{
    background:#fff; border-radius:18px; padding:16px 18px; box-shadow:0 10px 26px #00000018;
  }
  .btns{display:flex; flex-wrap:wrap; gap:10px; margin-top:14px}
  .btn{
    border:0; padding:12px 16px; border-radius:14px; font-weight:700; cursor:pointer;
    transition:transform .08s ease, box-shadow .2s ease;
  }
  .btn.primary{background:linear-gradient(90deg,#ff5aa5,#a855f7); color:#fff; box-shadow:0 10px 20px #ff5aa544}
  .btn.ghost{background:#fff; color:#444; border:2px solid #eee}
  .btn.success{background:linear-gradient(90deg,#00c896,#00e1b0); color:#fff}
  .btn:active{transform:translateY(1px)}
  .mini{font-size:12px; opacity:.7}
  .list{padding-left:20px; margin:0}
  .quote{
    font-size:clamp(16px,2.5vw,18px);
    border-left:6px solid var(--accent);
    padding:10px 14px; background:#fff7fb; border-radius:12px; margin:10px 0;
  }
  footer{
    text-align:center; padding:24px 10px; color:#444; font-size:13px;
  }

  /* Confetti canvas over content */
  #confetti{position:fixed; inset:0; pointer-events:none; z-index:4}
  /* subtle glow stars */
  .twinkle{
    position:absolute; width:10px; height:10px; border-radius:50%;
    background: radial-gradient(circle at 30% 30%, #fff, #fff0 60%);
    opacity:.4; animation: twinkle 3s ease-in-out infinite;
  }
  @keyframes twinkle{
    0%,100%{transform:scale(.6); opacity:.2}
    50%{transform:scale(1.2); opacity:.7}
  }
</style>
</head>
<body>

<canvas id="confetti"></canvas>

<!-- Floating balloons (colors & random positions via style attr) -->
<div class="balloon" style="left:6%; background:#ff8fab"></div>
<div class="balloon" style="left:18%; width:50px;height:70px;background:#ffd166; animation-duration:14s"></div>
<div class="balloon" style="left:34%; background:#90e0ef; animation-duration:16s"></div>
<div class="balloon" style="left:58%; background:#bde0fe; animation-duration:13s"></div>
<div class="balloon" style="left:76%; background:#caffbf; animation-duration:15s"></div>

<div class="wrap">
  <div class="hero">
    <span class="tag">🎉 Happy Birthday Mode</span>
    <div class="grid">
      <div>
        <h1>Selamat Ulang Tahun, <span style="color:var(--accent)">Fira</span>! 🎂✨</h1>
        <p class="sub">Semoga harimu secerah pelangi dan semanis es krim kesukaanmu! 🎈</p>
        <div class="quote">
          <strong>Kata motivasi:</strong><br>
          “Tambah usia, tambah berani bermimpi. <em>Kecilkan takutmu, besarkan tekadmu.</em> Langkah kecil hari ini bisa jadi lompatan besar besok.”
        </div>
        <ul class="list">
          <li>Sehat selalu dan makin bahagia.</li>
          <li>Sukses sekolah/kerja, rezeki lancar.</li>
          <li>Lingkungan baik & teman yang suportif — termasuk aku, bestiemu. 😎🤝</li>
        </ul>
        <div class="btns">
          <button class="btn primary" id="btnPop">Tiup Lilin 🎂</button>
          <button class="btn success" id="btnWish">Buka Pesan Rahasia 💌</button>
          <button class="btn ghost" id="btnMusic">🎵 Putar Musik</button>
        </div>
        <p class="mini">Tip: klik/tap di mana saja buat munculin konfeti lagi.</p>
      </div>
      <div class="right">
        <!-- Ganti src dengan foto Fira kalau ada -->
        <img class="photo" src="https://images.unsplash.com/photo-1530026405186-ed1f139313f8?q=80&w=400&auto=format&fit=crop" alt="Fira">
        <div class="card" style="margin-top:12px">
          <b>Bestie Note 🗿🙏</b>
          <p style="margin:.4rem 0 0">
            Makasih udah jadi teman paling asik. Tetap jadi Fira yang baik hati,
            gokil, dan nggak gampang nyerah. Tahun ini pasti lebih epic! 🚀
          </p>
        </div>
      </div>
    </div>
  </div>

  <!-- 3 mini-cards -->
  <div class="grid" style="margin-top:18px">
    <div class="card">
      <b>🎯 Resolusi Seru</b>
      <p>Belajar hal baru 15 menit tiap hari. Kecil, konsisten, tapi berdampak besar.</p>
    </div>
    <div class="card">
      <b>💖 Self-Reminder</b>
      <p>Kamu cukup. Kamu berharga. Kamu mampu — dan kamu nggak sendirian.</p>
    </div>
    <div class="card">
      <b>🌟 Doa Terbaik</b>
      <p>Semoga langkahmu dipermudah, dilapangkan, dan dilimpahi keberkahan. Aamiin.</p>
    </div>
  </div>

  <footer>
    Dibuat dengan cinta oleh bestie-mu. &middot; Klik di mana saja untuk konfeti 🎊
  </footer>
</div>

<!-- Optional music: taruh file song.mp3 di folder yang sama -->
<audio id="bgm" src="song.mp3" preload="auto"></audio>

<script>
/* Tiny confetti engine */
(function(){
  const canvas = document.getElementById('confetti');
  const ctx = canvas.getContext('2d');
  let W, H, pieces = [];
  const COLORS = ['#ff4d88','#ffd166','#6c5ce7','#00c896','#6ee7ff','#ffc7ea','#b8ffce'];

  function resize(){
    W = canvas.width = innerWidth;
    H = canvas.height = innerHeight;
  }
  addEventListener('resize', resize); resize();

  function spawn(n=120, x=W/2, y=H/2){
    for(let i=0;i<n;i++){
      const angle = Math.random()*Math.PI*2;
      const speed = 2 + Math.random()*6;
      pieces.push({
        x, y,
        w: 6 + Math.random()*6,
        h: 8 + Math.random()*10,
        vx: Math.cos(angle)*speed,
        vy: Math.sin(angle)*speed - 4,
        rot: Math.random()*Math.PI,
        vr: (Math.random()-.5)*0.3,
        col: COLORS[(Math.random()*COLORS.length)|0],
        life: 90 + Math.random()*50
      });
    }
  }

  function tick(){
    ctx.clearRect(0,0,W,H);
    pieces = pieces.filter(p=>p.life>0);
    for(const p of pieces){
      p.vy += 0.12; // gravity
      p.x += p.vx; p.y += p.vy; p.rot += p.vr; p.life--;
      ctx.save();
      ctx.translate(p.x,p.y);
      ctx.rotate(p.rot);
      ctx.fillStyle = p.col;
      ctx.fillRect(-p.w/2,-p.h/2,p.w,p.h);
      ctx.restore();
    }
    requestAnimationFrame(tick);
  }
  tick();

  // First burst
  setTimeout(()=>spawn(200, W*.5, H*.55), 400);

  // Interactions
  addEventListener('pointerdown', e => spawn(140, e.clientX, e.clientY));
  document.getElementById('btnPop').addEventListener('click', () => spawn(260, W*.5, H*.65));

  // Secret wish
  document.getElementById('btnWish').addEventListener('click', () => {
    const lines = [
      "Fira, semoga tahun ini kamu ketemu banyak alasan buat tersenyum 😊",
      "Kalau capek, istirahat. Tapi jangan berhenti. Aku dukung terus! 💪",
      "You’ve got this. One step at a time. 🚶‍♀️✨"
    ];
    alert(lines[Math.floor(Math.random()*lines.length)]);
  });

  // Music toggle (needs song.mp3)
  const audio = document.getElementById('bgm');
  const btnMusic = document.getElementById('btnMusic');
  function toggleMusic(){
    if(!audio.src){ alert("Taruh file musik bernama 'song.mp3' di folder yang sama ya ✨"); return; }
    if(audio.paused){ audio.loop=true; audio.play().catch(()=>{}); btnMusic.textContent="⏸️ Hentikan Musik"; }
    else { audio.pause(); btnMusic.textContent="🎵 Putar Musik"; }
  }
  btnMusic.addEventListener('click', toggleMusic);

  // Twinkle stars randomly
  for(let i=0;i<18;i++){
    const s=document.createElement('div');
    s.className='twinkle';
    s.style.left = (Math.random()*100)+'%';
    s.style.top  = (Math.random()*100)+'%';
    s.style.animationDelay = (Math.random()*3)+'s';
    s.style.opacity = .15 + Math.random()*.6;
    s.style.transform = `scale(${.5+Math.random()})`;
    document.body.appendChild(s);
  }
})();
</script>
</body>
</html>
