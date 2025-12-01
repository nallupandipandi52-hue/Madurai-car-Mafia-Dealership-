# Madurai-car-Mafia-Dealership-
Madurai Car Mafia – Tamil Nadu Only Online Car Dealership • WhatsApp: 7806842824
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Madurai Car Mafia - Online Dealership</title>
  <meta name="description" content="Madurai Car Mafia - Tamil Nadu only online car dealership. WhatsApp: 7806842824" />
  <style>
    :root{
      --accent:#ffcc00;
      --cta:#ff4d4d;
      --bg:#f5f5f5;
      --card:#ffffff;
      --muted:#666;
      --maxwidth:1100px;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter, Arial, sans-serif;background:var(--bg);color:#111}
    header{
      background:#000;color:white;padding:18px 16px;display:flex;align-items:center;gap:12px;justify-content:space-between;
    }
    .brand{font-weight:800;font-size:20px;letter-spacing:0.6px}
    .sub{font-size:13px;color:#ddd}
    .container{max-width:var(--maxwidth);margin:18px auto;padding:0 16px}
    .hero{
      display:grid;grid-template-columns:1fr 360px;gap:18px;align-items:center;
      margin-bottom:18px;
    }
    .hero .left{
      background:linear-gradient(180deg,#0b0b0b00 0%, #00000010 100%);
      padding:18px;border-radius:12px;
    }
    .title{font-size:28px;color:#111;margin:0 0 6px;font-weight:800}
    .lead{color:var(--muted);margin:0 0 12px}
    .price{font-size:26px;color:green;font-weight:800;margin:6px 0}
    .tags{display:flex;gap:8px;flex-wrap:wrap;margin:12px 0}
    .tag{background:var(--accent);color:#000;padding:8px 10px;border-radius:999px;font-weight:700}
    .ctas{display:flex;gap:10px;margin-top:10px;flex-wrap:wrap}
    .btn{display:inline-block;padding:12px 16px;border-radius:10px;text-decoration:none;color:#fff;font-weight:700}
    .btn.call{background:#111}
    .btn.wa{background:#25D366}
    .card{background:var(--card);border-radius:12px;padding:12px;box-shadow:0 6px 20px rgba(0,0,0,0.08)}
    .gallery{display:grid;grid-template-columns:repeat(2,1fr);gap:8px}
    .gallery img{width:100%;height:170px;object-fit:cover;border-radius:8px;cursor:pointer}
    .details{margin-top:12px;line-height:1.6;color:#333}
    .list{padding:10px 0;margin:0;display:grid;grid-template-columns:repeat(2,1fr);gap:8px}
    .list div{background:#f8f8f8;padding:10px;border-radius:8px;font-weight:600}
    footer{margin-top:18px;padding:14px;text-align:center;background:#111;color:#fff;border-radius:8px}
    /* responsive */
    @media(max-width:880px){
      .hero{grid-template-columns:1fr;gap:12px}
      .gallery img{height:140px}
    }

    /* Image modal */
    .modal{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(0,0,0,0.75);z-index:999}
    .modal img{max-width:95%;max-height:90%;border-radius:6px}
    .badge{display:inline-block;padding:6px 10px;background:#000;color:#fff;border-radius:8px;font-size:13px}
    .note{font-size:13px;color:var(--muted);margin-top:8px}
  </style>
</head>
<body>

<header>
  <div>
    <div class="brand">Madurai Car Mafia</div>
    <div class="sub">Online Dealership • Tamil Nadu Only</div>
  </div>
  <div style="text-align:right">
    <div class="badge">WhatsApp: 7806842824</div>
    <div class="sub" style="margin-top:6px">No Advance • Direct Meeting Only</div>
  </div>
</header>

<main class="container">
  <!-- HERO -->
  <section class="hero">
    <div class="left card">
      <h1 class="title">Maruti Suzuki Baleno — For Sale</h1>
      <p class="lead">Good condition • Black roof • Diesel • Reliable city hatch</p>

      <div class="price">₹5,20,000</div>

      <div class="tags">
        <div class="tag">Tamil Nadu Only</div>
        <div class="tag">No Advance</div>
        <div class="tag">Direct Meeting</div>
      </div>

      <div class="ctas">
        <a class="btn call" href="tel:7806842824">Call Now</a>
        <a class="btn wa" href="https://wa.me/917806842824" target="_blank">WhatsApp Seller</a>
      </div>

      <div class="details">
        <p><strong>Car:</strong> Maruti Suzuki Baleno (Diesel)</p>
        <p><strong>Price:</strong> ₹5,20,000</p>
        <p><strong>Location:</strong> Tamil Nadu (Madurai area)</p>
        <p class="note">Share this link to buyers. All meetings will be done in-person. No advance payment requested.</p>
      </div>
    </div>

    <!-- Gallery column -->
    <aside style="display:flex;flex-direction:column;gap:10px">
      <div class="card" style="padding:8px;">
        <div style="font-weight:800;margin-bottom:8px">Photos</div>
        <div class="gallery">
          <img src="car1.jpg" alt="Car photo 1" data-full="car1.jpg">
          <img src="car2.jpg" alt="Car photo 2" data-full="car2.jpg">
          <img src="car3.jpg" alt="Car photo 3" data-full="car3.jpg">
          <img src="car4.jpg" alt="Car photo 4" data-full="car4.jpg">
        </div>
      </div>

      <div class="card">
        <div style="font-weight:800;margin-bottom:8px">Quick Info</div>
        <div class="list">
          <div>Fuel: Diesel</div>
          <div>Owner: Single / 1st</div>
          <div>KMs: Provide KM</div>
          <div>Year: Provide Model Year</div>
        </div>
      </div>
    </aside>
  </section>

  <!-- More cars (optional) -->
  <section style="display:grid;gap:12px">
    <!-- Example other card -->
    <!-- You can duplicate this block to add more car listings -->
    <div class="card" style="display:flex;gap:12px;align-items:center;">
      <img src="car1.jpg" alt="thumb" style="width:140px;height:90px;object-fit:cover;border-radius:8px">
      <div>
        <div style="font-weight:800">Maruti Suzuki Baleno</div>
        <div style="color:var(--muted);margin-top:6px">Price: ₹5,20,000 • WhatsApp: 7806842824</div>
      </div>
    </div>
  </section>

  <footer>
    © 2025 Madurai Car Mafia • WhatsApp: 7806842824 • Tamil Nadu Only
  </footer>
</main>

<!-- Image modal -->
<div class="modal" id="modal">
  <img src="" alt="full" id="modalImg">
</div>

<script>
  // Simple gallery modal
  const imgs = document.querySelectorAll('.gallery img');
  const modal = document.getElementById('modal');
  const modalImg = document.getElementById('modalImg');

  imgs.forEach(img=>{
    img.addEventListener('click', ()=>{
      const src = img.dataset.full || img.src;
      modalImg.src = src;
      modal.style.display = 'flex';
    });
  });

  modal.addEventListener('click', ()=> modal.style.display = 'none');
</script>

</body>
</html>
