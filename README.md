<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DON CEZAR PRODUCTION</title>
  <style>
    body{margin:0;font-family:Arial,sans-serif;background:#f4f4f4;color:#222}
    header{background:#000;color:#d4af37;padding:30px 20px;text-align:center}
    header h1{margin:0;font-size:32px}
    header p{color:#fff;margin-top:10px}
    nav{background:#111;display:flex;justify-content:center;gap:12px;padding:12px;flex-wrap:wrap}
    nav button{background:#333;color:#fff;border:none;padding:8px 14px;border-radius:6px;cursor:pointer}
    nav button:hover{background:#555}
    section{padding:35px;margin:25px auto;max-width:1100px;background:#fff;border-radius:14px;box-shadow:0 4px 10px rgba(0,0,0,.08)}
    h2{text-align:center;color:#000}
    iframe{width:100%;height:550px;border:none;border-radius:12px}
    footer{background:#000;color:#fff;text-align:center;padding:20px}
    .lang{text-align:center;margin-top:15px}
    .lang button{margin:5px;padding:6px 12px;border:none;border-radius:6px;background:#d4af37;color:#000;cursor:pointer}
    .whatsapp{position:fixed;bottom:20px;right:20px;background:#25D366;color:#fff;padding:14px 18px;border-radius:50px;text-decoration:none;font-weight:bold;box-shadow:0 4px 8px rgba(0,0,0,.3)}
  </style>
</head>
<body>

<header>
  <h1>DON CEZAR PRODUCTION 🎨</h1>
  <p id="slogan">تصميم اللوجو • اللوحات الإعلانية • دمج الصور | Free Logo & Graphic Design</p>
  <div class="lang">
    <button onclick="setLang('ar')">AR</button>
    <button onclick="setLang('en')">EN</button>
    <button onclick="setLang('fr')">FR</button>
  </div>
</header>

<nav>
  <button onclick="document.getElementById('logo').scrollIntoView()">Logo</button>
  <button onclick="document.getElementById('ads').scrollIntoView()">Ads</button>
  <button onclick="document.getElementById('photos').scrollIntoView()">Photos</button>
  <button onclick="document.getElementById('about').scrollIntoView()">About</button>
  <button onclick="document.getElementById('contact').scrollIntoView()">Contact</button>
</nav>

<section id="logo">
  <h2>🖌️ Logo Design</h2>
  <iframe src="https://www.canva.com/create/logos/"></iframe>
</section>

<section id="ads">
  <h2>📢 Advertising Design</h2>
  <iframe src="https://www.canva.com/create/posters/"></iframe>
</section>

<section id="photos">
  <h2>🖼️ Photo Editing</h2>
  <iframe src="https://www.photopea.com"></iframe>
</section>

<section id="about">
  <h2>👤 About Us</h2>
  <p id="aboutText" style="text-align:center">
    DON CEZAR PRODUCTION منصة مجانية تساعدك على تصميم لوجو احترافي، لوحات إعلانية ودمج الصور بسهولة وبدون خبرة.
  </p>
</section>

<section id="contact">
  <h2>📩 Contact</h2>
  <p style="text-align:center">
    📞 Phone: 0668805634<br>
    💬 WhatsApp: 0668919744<br>
    ✉️ Email: zaidouarbia@me.com<br>
    📘 Facebook: DON CEZAR Production
  </p>
</section>

<footer>
  <p>© 2026 DON CEZAR PRODUCTION – Free Design Platform</p>
</footer>

<a class="whatsapp" href="https://wa.me/212668919744" target="_blank">WhatsApp 💬</a>

<script>
function setLang(lang){
  if(lang==='ar'){
    document.documentElement.lang='ar';document.documentElement.dir='rtl';
    document.getElementById('slogan').innerText='تصميم اللوجو • اللوحات الإعلانية • دمج الصور | منصة تصميم مجانية';
    document.getElementById('aboutText').innerText='DON CEZAR PRODUCTION منصة مجانية تساعدك على تصميم لوجو احترافي، لوحات إعلانية ودمج الصور بسهولة وبدون خبرة.';
  }
  if(lang==='en'){
    document.documentElement.lang='en';document.documentElement.dir='ltr';
    document.getElementById('slogan').innerText='Logo Design • Advertising • Photo Editing | Free Platform';
    document.getElementById('aboutText').innerText='DON CEZAR PRODUCTION is a free platform for logo design, advertising visuals and photo editing.';
  }
  if(lang==='fr'){
    document.documentElement.lang='fr';document.documentElement.dir='ltr';
    document.getElementById('slogan').innerText='Création de logos • Publicité • Retouche photo | Plateforme gratuite';
    document.getElementById('aboutText').innerText='DON CEZAR PRODUCTION est une plateforme gratuite pour le design graphique et la retouche photo.';
  }
}
</script>

</body>
</html>