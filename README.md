HTML
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ganni Motor Home Service</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #0b0b0b;
  color: white;
}

/* ANIMASI */
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeUp 1s ease forwards;
}

@keyframes fadeUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* HERO */
.hero {
  padding: 80px 20px;
  text-align: center;
  background: linear-gradient(rgba(0,0,0,0.85), rgba(0,0,0,0.9)),
              url('https://images.unsplash.com/photo-1605559424843-9e4c228bf1c2');
  background-size: cover;
  background-position: center;
}

/* LOGO */
.logo {
  width: 190px;
  margin-bottom: 15px;
  filter: drop-shadow(0 0 15px rgba(255,255,255,0.4));
  animation: glow 2s infinite alternate;
}

@keyframes glow {
  from { filter: drop-shadow(0 0 10px rgba(255,255,255,0.3)); }
  to { filter: drop-shadow(0 0 25px rgba(255,0,0,0.7)); }
}

.hero h1 {
  font-size: 30px;
}

.hero p {
  color: #ddd;
}

/* BUTTON */
.btn {
  display: inline-block;
  margin-top: 15px;
  padding: 14px 24px;
  border-radius: 10px;
  font-weight: bold;
  text-decoration: none;
  transition: 0.3s;
}

.btn-wa {
  background: #25D366;
  color: black;
}

.btn-wa:hover {
  transform: scale(1.1);
}

.btn-map {
  background: gold;
  color: black;
  margin-left: 10px;
}

/* SECTION */
section {
  padding: 30px 20px;
}

h2 {
  color: #ff3c3c;
}

/* CARD */
.card {
  background: #161616;
  padding: 15px;
  border-radius: 12px;
  margin-top: 10px;
  box-shadow: 0 0 15px rgba(255,0,0,0.1);
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

/* FLOATING WA */
.floating-wa {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25D366;
  color: black;
  padding: 15px 18px;
  border-radius: 50px;
  font-weight: bold;
  text-decoration: none;
  box-shadow: 0 0 15px rgba(0,255,100,0.5);
  z-index: 999;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 15px;
  background: #000;
  color: #aaa;
}
</style>

</head>

<body>

<!-- HERO -->
<div class="hero fade-in">
  <img src="logo.png" class="logo">
  <h1>GANNI MOTOR HOME SERVICE</h1>
  <p>Servis Motor Panggilan • 24 Jam • Maks 30 Menit Sampai</p>

  <a class="btn btn-wa" href="https://wa.me/6289637591994?text=Halo%20saya%20butuh%20servis%20motor" target="_blank">
    Chat Sekarang
  </a>

  <a class="btn btn-map" href="https://maps.app.goo.gl/7cpzYrABWeR8qn9Z6" target="_blank">
    Lokasi
  </a>
</div>

<section class="fade-in">
  <h2>Kenapa Pilih Kami?</h2>
  <div class="card">⚡ Datang Maksimal 30 Menit</div>
  <div class="card">🕒 Buka 24 Jam</div>
  <div class="card">🔧 Teknisi Profesional</div>
</section>

<section class="fade-in">
  <h2>Layanan</h2>
  <div class="card">
    Servis Mesin • Ganti Oli • Tune Up • Kelistrikan • Home Service
  </div>
</section>

<section class="fade-in">
  <h2>Area</h2>
  <div class="card">
    Jakarta Timur • Utara • Pusat • Selatan
  </div>
</section>

<section class="fade-in">
  <h2>Butuh Cepat?</h2>
  <div class="card" style="text-align:center;">
    <a class="btn btn-wa" href="https://wa.me/6289637591994" target="_blank">
      Pesan Sekarang
    </a>
  </div>
</section>

<!-- FLOATING BUTTON -->
<a class="floating-wa" href="https://wa.me/6289637591994" target="_blank">
  WA
</a>

<footer>
  © 2026 Ganni Motor Home Service
</footer>

</body>
</html>
