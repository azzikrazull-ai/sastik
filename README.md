
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>SASTIK - Sanggar Seni Tiga Kendari</title>
  <meta name="description" content="Website resmi Sanggar Seni Tiga Kendari (SASTIK) – Sanggar seni tari tradisional dan modern dari Kendari." />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --merah-tua:#8B0000;
      --merah-cerah:#e63946;
      --emas:#FFD700;
      --putih:#fff;
      --hitam:#1a1a1a;
    }
    *{box-sizing:border-box;margin:0;padding:0;scroll-behavior:smooth;}
    body{font-family:Poppins,sans-serif;background:linear-gradient(180deg,var(--hitam),#330000);color:var(--putih);}
    header{position:sticky;top:0;background:rgba(139,0,0,0.9);backdrop-filter:blur(6px);padding:1rem 2rem;display:flex;align-items:center;justify-content:space-between;z-index:10;box-shadow:0 2px 10px rgba(0,0,0,0.4)}
    header h1{color:var(--emas);font-size:1.5rem;font-weight:700;}
    nav ul{display:flex;list-style:none;gap:1.5rem;}
    nav a{color:var(--putih);text-decoration:none;font-weight:500;transition:0.3s;}
    nav a:hover{color:var(--emas);}
    .hero{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;padding:4rem 2rem;animation:fadeIn 2s ease-in;}
    .hero-text{flex:1;min-width:300px;}
    .hero-text h2{font-size:2.2rem;color:var(--emas);margin-bottom:1rem;}
    .hero-text p{max-width:550px;line-height:1.7;color:#fce8e8;}
    .hero-img{flex:1;min-width:300px;text-align:center;}
    .hero-img img{width:100%;max-width:400px;border-radius:12px;box-shadow:0 0 20px rgba(255,215,0,0.5);animation:float 4s ease-in-out infinite;}

    section{padding:3rem 2rem;}
    h2.section-title{text-align:center;color:var(--emas);margin-bottom:1rem;font-size:1.8rem;}
    p.section-sub{text-align:center;margin-bottom:2rem;color:#f8dcdc;}

    .profil,.tarian,.galeri,.kontak{max-width:1100px;margin:auto;}

    .profil-content{display:flex;flex-wrap:wrap;align-items:center;gap:2rem;}
    .profil-content img{width:100%;max-width:400px;border-radius:12px;box-shadow:0 0 15px rgba(255,255,255,0.2)}
    .profil-content div{flex:1;}

    .tarian-list{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1.5rem;}
    .tarian-card{background:rgba(255,255,255,0.05);border-radius:12px;padding:1rem;text-align:center;transition:transform 0.3s;}
    .tarian-card:hover{transform:scale(1.05);}
    .tarian-card img{width:100%;border-radius:10px;margin-bottom:.5rem;}

    .galeri-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:1rem;}
    .galeri-grid img{width:100%;border-radius:10px;transition:transform 0.3s,box-shadow 0.3s;}
    .galeri-grid img:hover{transform:scale(1.05);box-shadow:0 0 15px var(--emas);}

    .kontak-form{display:flex;flex-direction:column;gap:1rem;max-width:600px;margin:auto;}
    input,textarea{padding:.8rem;border:none;border-radius:8px;background:rgba(255,255,255,0.1);color:var(--putih);}
    button{padding:.8rem 1.5rem;background:var(--emas);color:var(--hitam);border:none;border-radius:8px;font-weight:600;cursor:pointer;transition:0.3s;}
    button:hover{background:var(--merah-cerah);color:var(--putih);}

    footer{text-align:center;padding:1.5rem;background:rgba(0,0,0,0.8);color:#ddd;margin-top:2rem;font-size:.9rem;}

    @keyframes fadeIn{from{opacity:0;transform:translateY(20px);}to{opacity:1;transform:translateY(0);}}
    @keyframes float{0%{transform:translateY(0);}50%{transform:translateY(-10px);}100%{transform:translateY(0);}}

    /* 🎭 ANIMASI TAMBAHAN UNTUK GAMBAR */
    @keyframes fadeInUp {
      from {opacity: 0; transform: translateY(30px);}
      to {opacity: 1; transform: translateY(0);}
    }
    img.animate {
      opacity: 0;
      transform: translateY(30px);
      transition: all 1s ease;
    }
    img.animate.show {
      opacity: 1;
      transform: translateY(0);
      animation: fadeInUp 1.2s ease forwards;
    }
    img:hover {
      transform: scale(1.07);
      box-shadow: 0 0 20px gold;
    }
  </style>
</head>
<body>
  <header>
    <h1>SASTIK</h1>
    <nav>
      <ul>
        <li><a href="#beranda">Beranda</a></li>
        <li><a href="#profil">Profil</a></li>
        <li><a href="#tarian">Tarian</a></li>
        <li><a href="#galeri">Galeri</a></li>
        <li><a href="#kontak">Kontak</a></li>
      </ul>
    </nav>
  </header>

  <section id="beranda" class="hero">
    <div class="hero-text">
      <h2>Sanggar Seni Tiga Kendari (SASTIK)</h2>
      <p>Tempat kami menyalurkan cinta terhadap budaya dan tarian tradisional. Di SASTIK, menari bukan sekadar gerak, tetapi juga wujud rasa, makna, dan kebersamaan keluarga seni.</p>
    </div>
    <div class="hero-img">
      <img src="IMG-satu.jpg" alt="Penari tradisional SASTIK" class="animate">
    </div>
  </section>

  <section id="profil" class="profil">
    <h2 class="section-title">Profil Sanggar</h2>
    <p class="section-sub">Menjaga dan melestarikan seni tari tradisional Kendari</p>
    <div class="profil-content">
      <img src="IMG-tiga.jpg" alt="Latihan tari di sanggar" class="animate">
      <div>
        <p>SASTIK (Sanggar Seni Tiga Kendari) didirikan dengan semangat untuk melestarikan budaya lokal melalui tari. Kami adalah keluarga besar penari muda yang berlatih, tampil, dan berbagi kebahagiaan lewat gerak dan irama.</p>
        <p>Dengan pelatih berpengalaman dan anggota yang solid, kami telah tampil di berbagai acara budaya dan festival daerah. Kami percaya bahwa setiap gerakan memiliki cerita dan setiap tarian adalah warisan.</p>
      </div>
    </div>
  </section>

  <section id="tarian" class="tarian">
    <h2 class="section-title">Tarian Kami</h2>
    <p class="section-sub">Karya tari yang pernah kami tampilkan</p>
    <div class="tarian-list">
      <div class="tarian-card">
        <img src="IMG-parang.jpg" alt="Tari Haluoleo" class="animate">
        <h3>Tari Haluoleo</h3>
        <p>Tari penyambutan khas Sulawesi Tenggara yang menggambarkan kehangatan dan persaudaraan.</p>
      </div>
      <div class="tarian-card">
        <img src="IMG-tameng.jpg" alt="Tari Amoara" class="animate">
        <h3>Tari Amoara</h3>
        <p>Tarian kebanggaan SASTIK yang memadukan energi muda dan tradisi daerah dengan gaya elegan.</p>
      </div>
      <div class="tarian-card">
        <img src="IMG-toraja.jpg" alt="Tari 4 etnis" class="animate">
        <h3>Tari 4 etnis</h3>
        <p>Tari 4 Etnis adalah tarian kreasi yang berasal dari Sulawesi Selatan yang memadukan unsur-unsur dari empat etnis terbesar di wilayah tersebut: Bugis, Makassar, Mandar, dan Toraja..</p>
      </div>
    </div>
  </section>

  <section id="galeri" class="galeri">
    <h2 class="section-title">Galeri</h2>
    <p class="section-sub">Potret kebersamaan dan penampilan kami</p>
    <div class="galeri-grid">
      <img src="IMG-ulta.jpg" alt="Penampilan tari" class="animate">
      <img src="IMG-toraja.jpg" alt="Latihan tari" class="animate">
      <img src="IMG-satu.jpg" alt="Kostum tari" class="animate">
      <img src="IMG-tiga.jpg" alt="Pertunjukan panggung" class="animate">
    </div>
  </section>

  <footer>
    <p>© 2025 SASTIK - Sanggar Seni Tiga Kendari. Semua Hak Dilindungi.</p>
  </footer>

  <script>
    function kirimPesan(e){
      e.preventDefault();
      const nama=document.getElementById('nama').value;
      alert('Terima kasih '+nama+'! Pesan kamu sudah terkirim ke SASTIK.');
      e.target.reset();
    }

    // 🔸 Efek animasi saat discroll
    const animElements = document.querySelectorAll('img.animate');
    function animOnScroll(){
      animElements.forEach(el=>{
        const rect = el.getBoundingClientRect();
        if(rect.top < window.innerHeight - 100){
          el.classList.add('show');
        }
      });
    }
    window.addEventListener('scroll', animOnScroll);
    animOnScroll();
  </script>
  
  <canvas id="bintang"></canvas>
<script>
const canvas=document.getElementById('bintang');
const ctx=canvas.getContext('2d');
canvas.width=innerWidth;canvas.height=innerHeight;
const stars=[];
for(let i=0;i<100;i++){stars.push({x:Math.random()*innerWidth,y:Math.random()*innerHeight,r:Math.random()*1.5});}
function draw(){
  ctx.clearRect(0,0,canvas.width,canvas.height);
  ctx.fillStyle='white';
  stars.forEach(s=>{
    ctx.beginPath();
    ctx.arc(s.x,s.y,s.r,0,Math.PI*2);
    ctx.fill();
  });
}
function update(){
  stars.forEach(s=>{
    s.y+=0.2;
    if(s.y>innerHeight){s.y=0;s.x=Math.random()*innerWidth;}
  });
}
function animate(){draw();update();requestAnimationFrame(animate);}
animate();
</script>
  
  <script>
const imgs=document.querySelectorAll('.galeri-grid img');
imgs.forEach(img=>{
  img.addEventListener('click',()=>{
    const popup=document.createElement('div');
    popup.style.position='fixed';
    popup.style.top='0';popup.style.left='0';
    popup.style.width='100%';popup.style.height='100%';
    popup.style.background='rgba(0,0,0,0.9)';
    popup.style.display='flex';popup.style.alignItems='center';popup.style.justifyContent='center';
    popup.innerHTML=`<img src="${img.src}" style="max-width:90%;max-height:90%;border-radius:10px;">`;
    popup.onclick=()=>popup.remove();
    document.body.appendChild(popup);
  });
});
</script>
  
</body>
</html>
