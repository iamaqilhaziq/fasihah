<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Isteri - Ya</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        * { box-sizing: border-box; }
        
        body{
            margin:0;
            font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
            min-height: 100vh;
            display:flex;
            align-items:center;
            justify-content:center;
            padding: 24px;

            background: radial-gradient(circle at top, #ffe7ee, #f7dbe3 60%, #f2cfdc);
        }

        /* floating hearts layer */
        .hearts {
            position: fixed;
            inset: 0;
            pointer-events: none;
            overflow: hidden;
            z-index: 0;
        }
        .heart {
            position: absolute;
            bottom: -40px;
            font-size: 18px;
            opacity: 0.85;
            animation: floatUp linear forwards;
            filter: drop-shadow(0 6px 10px rgba(0,0,0,0.12));
        }
        @keyframes floatUp {
            from { transform: translateY(0) translateX(0) scale(1); opacity: 0.9; }
            to   { transform: translateY(-110vh) translateX(var(--drift)) scale(var(--scale)); opacity: 0; }
        }

        .wrap{
            width: min(820px, 95vw);
            text-align:center;
            position: relative;
            z-index: 1;
        }

        .panel{
            background: linear-gradient(180deg, rgba(255,255,255,0.35), rgba(255,255,255,0.18));
            border: 1px solid rgba(255,255,255,0.35);
            backdrop-filter: blur(8px);
            border-radius: 26px;
            padding: clamp(22px, 4vw, 44px);
            box-shadow: 0 18px 40px rgba(0,0,0,0.12);

            display:flex;
            flex-direction:column;
            align-items:center;
            gap: 14px;
        }

        .thumb{
            width: 40%;
            border-radius: 18px;
            overflow:hidden;
            background: rgba(255,255,255,0.6);
            box-shadow: 0 10px 25px rgba(0,0,0,0.12);
        }
        .thumb img{
            width:100%;
            height:100%;
            object-fit: cover;
            display:block;
        }

        .title{
            margin: 8px 0 0;
            font-size: clamp(26px, 4vw, 44px);
            font-weight: 900;
            letter-spacing: -0.02em;
            color: #7c2e35;
        }
        .subtitle{
            margin: 0;
            font-size: clamp(14px, 1.8vw, 18px);
            color: rgba(30,30,30,0.65);
            font-weight: 600;
        }

        /* music button */
        .music {
            margin-top: 14px;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            padding: 10px 14px;
            border-radius: 999px;
            background: rgba(255,255,255,0.55);
            border: 1px solid rgba(255,255,255,0.5);
            color: rgba(30,30,30,0.75);
            font-weight: 700;
            cursor: pointer;
            backdrop-filter: blur(8px);
        }
        
        .music small{ font-weight:600; opacity:.75; }
    </style>
</head>
<body>
  <!-- floating hearts -->
  <div class="hearts" id="hearts"></div>

  <div class="wrap">
    <div class="panel">
      <div class="thumb">
        <!-- tukar gambar sendiri -->
        <img src="image2.jpg" alt="Isteri">
      </div>

      <h1 class="title">Saya tahu awak akan kata ya!</h1>

      <!-- audio: letak fail mp3 sendiri -->
      <audio id="bgm" loop preload="auto">
        <source src="Wedding Nasheed - Muhammad Al Muqit _ Lyrics Arabic + Terjemahan  𝘈𝘳𝘢𝘣𝘪𝘤 𝘕𝘢𝘴𝘩𝘦𝘦𝘥 _ محمد المقيط.mp3" type="audio/mpeg">
      </audio>

      <button class="music" id="musicBtn" type="button">
        🎵 Mainkan Muzik (tekan jika tiada bunyi)
      </button>
    </div>
  </div>

  <script>
    /* ===== Floating hearts ===== */
    const heartsLayer = document.getElementById("hearts");

    function spawnHeart(){
      const el = document.createElement("div");
      el.className = "heart";
      el.textContent = Math.random() > 0.5 ? "💗" : "💖";

      const left = Math.random() * 100;                 // vw
      const duration = 4 + Math.random() * 4;           // 4-8s
      const drift = (Math.random() * 120 - 60) + "px";  // -60..60 px
      const scale = (0.7 + Math.random() * 1.2).toFixed(2);

      el.style.left = left + "vw";
      el.style.animationDuration = duration + "s";
      el.style.setProperty("--drift", drift);
      el.style.setProperty("--scale", scale);

      heartsLayer.appendChild(el);
      setTimeout(() => el.remove(), duration * 1000);
    }

    // spawn hearts continuously
    setInterval(spawnHeart, 350);

    /* ===== Background music ===== */
    const bgm = document.getElementById("bgm");
    const musicBtn = document.getElementById("musicBtn");

    async function tryPlay(){
      try {
        await bgm.play();
        musicBtn.textContent = "🔊 Muzik Dimainkan";
      } catch (e) {
        // autoplay blocked, user needs to tap
        musicBtn.textContent = "🎵 Mainkan Muzik (tekan jika tiada bunyi)";
      }
    }

    // Try autoplay (some browsers will block)
    tryPlay();

    musicBtn.addEventListener("click", async () => {
      if (bgm.paused) {
        await tryPlay();
      } else {
        bgm.pause();
        musicBtn.textContent = "🎵 Mainkan Muzik (tekan jika tiada bunyi)";
      }
    });
  </script>
</body>
</html>