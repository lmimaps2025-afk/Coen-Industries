<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Coen Industries</title>
<link href="https://fonts.googleapis.com/css2?family=Black+Han+Sans&family=Nunito:wght@400;600;700;900&display=swap" rel="stylesheet">
<style>
  :root { --black:#111111; --yellow:#FFD700; --yellow-dark:#FFC200; --white:#FFFFFF; --card-shadow:0 8px 32px rgba(0,0,0,0.18); }
  * { margin:0; padding:0; box-sizing:border-box; }
  body { font-family:'Nunito',sans-serif; background:var(--black); color:var(--white); min-height:100vh; }

  /* VISITOR BAR */
  .visitor-bar { background:rgba(255,215,0,0.07); border-bottom:1px solid rgba(255,215,0,0.15); text-align:center; padding:8px 16px; font-size:0.85rem; color:#888; letter-spacing:1px; }
  .visitor-bar span { color:var(--yellow); font-weight:900; }

  /* NAV */
  nav { position:sticky; top:0; z-index:100; background:var(--black); border-bottom:3px solid var(--yellow); display:flex; align-items:center; justify-content:space-between; padding:0 40px; height:70px; }
  .nav-logo { font-family:'Black Han Sans',sans-serif; font-size:1.5rem; color:var(--yellow); letter-spacing:2px; cursor:pointer; }
  .nav-links { display:flex; gap:8px; }
  .nav-btn { background:none; border:2px solid transparent; color:var(--white); font-family:'Nunito',sans-serif; font-size:1rem; font-weight:700; padding:8px 22px; border-radius:30px; cursor:pointer; transition:all 0.2s; letter-spacing:1px; }
  .nav-btn:hover,.nav-btn.active { background:var(--yellow); color:var(--black); border-color:var(--yellow); }
  .cart-btn { background:var(--yellow); color:var(--black); border:none; font-family:'Nunito',sans-serif; font-weight:900; font-size:0.95rem; padding:10px 22px; border-radius:30px; cursor:pointer; transition:all 0.2s; display:flex; align-items:center; gap:8px; }
  .cart-btn:hover { background:var(--yellow-dark); transform:scale(1.05); }
  .cart-count { background:var(--black); color:var(--yellow); border-radius:50%; width:22px; height:22px; display:flex; align-items:center; justify-content:center; font-size:0.8rem; font-weight:900; }

  /* PAGES */
  .page { display:none; animation:fadeIn 0.4s ease; }
  .page.active { display:block; }
  @keyframes fadeIn { from{opacity:0;transform:translateY(16px)} to{opacity:1;transform:translateY(0)} }

  /* HOME */
  .hero { min-height:calc(100vh - 100px); display:flex; flex-direction:column; align-items:center; justify-content:center; text-align:center; padding:60px 40px; position:relative; overflow:hidden; }
  .hero::before { content:''; position:absolute; inset:0; background:radial-gradient(ellipse at 50% 60%,rgba(255,215,0,0.10) 0%,transparent 70%); pointer-events:none; }
  .hero-gear { position:absolute; opacity:0.06; animation:spin 18s linear infinite; }
  .hero-gear.big { width:420px; top:-80px; right:-100px; }
  .hero-gear.small { width:220px; bottom:20px; left:-40px; animation-direction:reverse; animation-duration:12s; }
  @keyframes spin { from{transform:rotate(0deg)} to{transform:rotate(360deg)} }
  .hero-logo-svg { width:320px; max-width:90vw; margin-bottom:32px; animation:popIn 0.7s cubic-bezier(.34,1.56,.64,1) both; }
  @keyframes popIn { from{transform:scale(0.6);opacity:0} to{transform:scale(1);opacity:1} }
  .hero-message { background:var(--yellow); color:var(--black); border-radius:20px; padding:32px 48px; max-width:680px; margin:0 auto 40px; box-shadow:var(--card-shadow); animation:popIn 0.7s 0.2s cubic-bezier(.34,1.56,.64,1) both; }
  .hero-message h1 { font-family:'Black Han Sans',sans-serif; font-size:2.2rem; letter-spacing:1px; margin-bottom:14px; }
  .hero-message p { font-size:1.15rem; font-weight:600; line-height:1.6; color:#333; }
  .hero-badges { display:flex; gap:14px; flex-wrap:wrap; justify-content:center; animation:popIn 0.7s 0.4s cubic-bezier(.34,1.56,.64,1) both; }
  .badge { background:rgba(255,215,0,0.12); border:2px solid var(--yellow); color:var(--yellow); border-radius:30px; padding:10px 24px; font-weight:700; font-size:0.95rem; letter-spacing:1px; }
  .hero-cta { margin-top:36px; display:flex; gap:16px; flex-wrap:wrap; justify-content:center; animation:popIn 0.7s 0.5s cubic-bezier(.34,1.56,.64,1) both; }
  .btn-primary { background:var(--yellow); color:var(--black); border:none; font-family:'Nunito',sans-serif; font-weight:900; font-size:1.1rem; padding:16px 36px; border-radius:50px; cursor:pointer; transition:all 0.2s; letter-spacing:1px; }
  .btn-primary:hover { background:var(--yellow-dark); transform:translateY(-3px); box-shadow:0 8px 24px rgba(255,215,0,0.3); }
  .btn-outline { background:none; color:var(--yellow); border:2px solid var(--yellow); font-family:'Nunito',sans-serif; font-weight:900; font-size:1.1rem; padding:14px 36px; border-radius:50px; cursor:pointer; transition:all 0.2s; letter-spacing:1px; }
  .btn-outline:hover { background:var(--yellow); color:var(--black); transform:translateY(-3px); }

  /* PAGE HEADER */
  .page-header { background:var(--yellow); padding:48px 40px 32px; text-align:center; }
  .page-header h2 { font-family:'Black Han Sans',sans-serif; font-size:3rem; color:var(--black); letter-spacing:2px; }
  .page-header p { color:#444; font-size:1.1rem; font-weight:600; margin-top:8px; }

  /* SHOP */
  .shop-list { max-width:860px; margin:48px auto; padding:0 24px; display:flex; flex-direction:column; gap:24px; }
  .shop-item { background:#1c1c1c; border:2px solid #2a2a2a; border-radius:16px; display:flex; align-items:center; gap:28px; padding:24px; transition:all 0.25s; }
  .shop-item:hover { border-color:var(--yellow); transform:translateX(6px); box-shadow:-6px 0 0 var(--yellow); }
  .shop-item-img { width:110px; height:110px; border-radius:12px; background:var(--yellow); display:flex; align-items:center; justify-content:center; font-size:3rem; flex-shrink:0; }
  .shop-item-info { flex:1; }
  .shop-item-info h3 { font-family:'Black Han Sans',sans-serif; font-size:1.4rem; color:var(--yellow); letter-spacing:1px; margin-bottom:6px; }
  .shop-item-info p { color:#aaa; font-size:0.95rem; line-height:1.5; margin-bottom:10px; }
  .shop-item-tag { display:inline-block; background:rgba(255,215,0,0.1); border:1px solid rgba(255,215,0,0.3); color:var(--yellow); border-radius:20px; padding:3px 12px; font-size:0.78rem; font-weight:700; letter-spacing:1px; }
  .shop-item-right { display:flex; flex-direction:column; align-items:center; gap:12px; flex-shrink:0; }
  .price { font-family:'Black Han Sans',sans-serif; font-size:2rem; color:var(--yellow); }
  .add-to-cart { background:var(--yellow); color:var(--black); border:none; font-family:'Nunito',sans-serif; font-weight:900; font-size:0.9rem; padding:10px 20px; border-radius:30px; cursor:pointer; transition:all 0.2s; white-space:nowrap; }
  .add-to-cart:hover { background:var(--yellow-dark); transform:scale(1.06); }
  .add-to-cart.added { background:#22c55e; color:white; }

  /* CART */
  .cart-overlay { display:none; position:fixed; inset:0; background:rgba(0,0,0,0.7); z-index:200; align-items:flex-end; justify-content:center; }
  .cart-overlay.open { display:flex; }
  .cart-panel { background:#1c1c1c; border:2px solid var(--yellow); border-radius:24px 24px 0 0; padding:32px; width:100%; max-width:540px; max-height:80vh; overflow-y:auto; animation:slideUp 0.3s ease; }
  @keyframes slideUp { from{transform:translateY(100%)} to{transform:translateY(0)} }
  .cart-panel h3 { font-family:'Black Han Sans',sans-serif; font-size:1.8rem; color:var(--yellow); margin-bottom:20px; letter-spacing:2px; }
  .cart-empty { text-align:center; color:#666; padding:32px 0; font-size:1.1rem; }
  .cart-line { display:flex; justify-content:space-between; align-items:center; padding:12px 0; border-bottom:1px solid #2a2a2a; font-weight:600; }
  .cart-line .item-name { color:var(--white); }
  .cart-line .item-price { color:var(--yellow); font-weight:900; }
  .remove-item { background:none; border:none; color:#666; cursor:pointer; font-size:1.2rem; padding:0 8px; transition:color 0.2s; }
  .remove-item:hover { color:#ef4444; }
  .cart-total { display:flex; justify-content:space-between; padding:20px 0 0; font-family:'Black Han Sans',sans-serif; font-size:1.4rem; color:var(--yellow); letter-spacing:1px; }
  .checkout-note { background:rgba(255,215,0,0.1); border:1px solid rgba(255,215,0,0.3); border-radius:12px; padding:16px; margin-top:16px; color:#ccc; font-size:0.9rem; line-height:1.5; text-align:center; }
  .close-cart { float:right; background:none; border:none; color:#666; font-size:1.6rem; cursor:pointer; margin-top:-8px; transition:color 0.2s; }
  .close-cart:hover { color:var(--yellow); }

  /* GALLERY */
  .gallery-grid { max-width:1100px; margin:48px auto; padding:0 24px; display:grid; grid-template-columns:repeat(auto-fill,minmax(240px,1fr)); gap:24px; }
  .gallery-card { background:#1c1c1c; border:2px solid #2a2a2a; border-radius:16px; overflow:hidden; transition:all 0.25s; cursor:pointer; }
  .gallery-card:hover { border-color:var(--yellow); transform:translateY(-6px); box-shadow:0 16px 40px rgba(255,215,0,0.15); }
  .gallery-img { width:100%; height:200px; background:linear-gradient(135deg,#2a2a2a,#333); display:flex; align-items:center; justify-content:center; font-size:4rem; border-bottom:2px solid #2a2a2a; }
  .gallery-info { padding:16px 20px; }
  .gallery-info h3 { font-family:'Black Han Sans',sans-serif; font-size:1.1rem; color:var(--yellow); letter-spacing:1px; }
  .gallery-note { text-align:center; padding:0 24px 48px; color:#555; font-size:0.95rem; }
  .gallery-note span { color:var(--yellow); font-weight:700; }

  footer { background:#0a0a0a; border-top:2px solid var(--yellow); text-align:center; padding:28px; color:#555; font-size:0.9rem; margin-top:60px; }
  footer span { color:var(--yellow); font-weight:700; }

  @media(max-width:600px) {
    nav { padding:0 16px; }
    .hero-message { padding:24px 20px; }
    .hero-message h1 { font-size:1.6rem; }
    .shop-item { flex-direction:column; text-align:center; }
    .shop-item-right { flex-direction:row; }
    .page-header h2 { font-size:2rem; }
  }
</style>
</head>
<body>

<div class="visitor-bar">👀 VISITORS TO COEN INDUSTRIES: <span id="visitor-count">...</span></div>

<nav>
  <div class="nav-logo" onclick="showPage('home')">⚙️ COEN INDUSTRIES</div>
  <div class="nav-links">
    <button class="nav-btn active" onclick="showPage('home')" id="nav-home">HOME</button>
    <button class="nav-btn" onclick="showPage('shop')" id="nav-shop">SHOP</button>
    <button class="nav-btn" onclick="showPage('gallery')" id="nav-gallery">ART GALLERY</button>
  </div>
  <button class="cart-btn" onclick="toggleCart()">🛒 CART <span class="cart-count" id="cart-count">0</span></button>
</nav>

<div class="cart-overlay" id="cart-overlay" onclick="closeCartOutside(event)">
  <div class="cart-panel">
    <button class="close-cart" onclick="toggleCart()">✕</button>
    <h3>🛒 YOUR CART</h3>
    <div id="cart-items"><div class="cart-empty">Your cart is empty!<br>Go grab something cool 😄</div></div>
    <div class="cart-total" id="cart-total" style="display:none"><span>TOTAL</span><span id="total-price">$0</span></div>
    <div class="checkout-note" id="checkout-note" style="display:none">📬 To buy, ask a parent to contact <span style="color:var(--yellow);font-weight:700;">Coen Industries</span> and we'll arrange pickup or delivery at school!</div>
  </div>
</div>

<!-- HOME -->
<div class="page active" id="page-home">
  <div class="hero">
    <svg class="hero-gear big" viewBox="0 0 100 100" fill="white" xmlns="http://www.w3.org/2000/svg">
      <circle cx="50" cy="50" r="20" fill="none" stroke="white" stroke-width="4"/>
      <circle cx="50" cy="50" r="10"/>
      <rect x="46" y="20" width="8" height="14" rx="3"/><rect x="46" y="66" width="8" height="14" rx="3"/>
      <rect x="20" y="46" width="14" height="8" rx="3"/><rect x="66" y="46" width="14" height="8" rx="3"/>
    </svg>
    <svg class="hero-logo-svg" viewBox="0 0 500 320" xmlns="http://www.w3.org/2000/svg">
      <rect width="500" height="320" rx="20" fill="#111"/>
      <circle cx="40" cy="40" r="3" fill="#FFD700" opacity="0.4"/>
      <circle cx="460" cy="50" r="2" fill="#FFD700" opacity="0.3"/>
      <circle cx="80" cy="280" r="2" fill="#FFD700" opacity="0.3"/>
      <circle cx="430" cy="270" r="3" fill="#FFD700" opacity="0.4"/>
      <rect x="150" y="140" width="200" height="110" rx="4" fill="#FFD700"/>
      <rect x="140" y="132" width="220" height="14" rx="4" fill="#FFC200"/>
      <rect x="170" y="88" width="28" height="60" rx="5" fill="#FFD700"/>
      <rect x="214" y="103" width="22" height="45" rx="5" fill="#FFC200"/>
      <rect x="300" y="93" width="25" height="55" rx="5" fill="#FFD700"/>
      <rect x="166" y="82" width="36" height="10" rx="3" fill="#FFC200"/>
      <rect x="210" y="97" width="30" height="9" rx="3" fill="#FFD700"/>
      <rect x="296" y="87" width="33" height="10" rx="3" fill="#FFC200"/>
      <circle cx="184" cy="68" r="10" fill="white" opacity="0.13"/>
      <circle cx="195" cy="57" r="8" fill="white" opacity="0.09"/>
      <circle cx="225" cy="82" r="8" fill="white" opacity="0.11"/>
      <circle cx="314" cy="72" r="9" fill="white" opacity="0.12"/>
      <rect x="165" y="158" width="30" height="28" rx="4" fill="#111"/>
      <rect x="210" y="158" width="30" height="28" rx="4" fill="#111"/>
      <rect x="258" y="158" width="30" height="28" rx="4" fill="#111"/>
      <rect x="306" y="158" width="30" height="28" rx="4" fill="#111"/>
      <rect x="167" y="160" width="12" height="10" rx="2" fill="#FFD700" opacity="0.4"/>
      <rect x="212" y="160" width="12" height="10" rx="2" fill="#FFD700" opacity="0.4"/>
      <rect x="260" y="160" width="12" height="10" rx="2" fill="#FFD700" opacity="0.4"/>
      <rect x="308" y="160" width="12" height="10" rx="2" fill="#FFD700" opacity="0.4"/>
      <rect x="220" y="204" width="60" height="46" rx="5" fill="#111"/>
      <circle cx="272" cy="229" r="3" fill="#FFD700"/>
      <rect x="95" y="248" width="310" height="5" rx="2" fill="#FFD700" opacity="0.3"/>
      <g transform="translate(105,195)">
        <circle cx="0" cy="0" r="22" fill="none" stroke="#FFD700" stroke-width="5" opacity="0.7"/>
        <circle cx="0" cy="0" r="10" fill="#111" stroke="#FFD700" stroke-width="3" opacity="0.7"/>
        <rect x="-4" y="-28" width="8" height="10" rx="2" fill="#FFD700" opacity="0.7"/>
        <rect x="-4" y="18" width="8" height="10" rx="2" fill="#FFD700" opacity="0.7"/>
        <rect x="-28" y="-4" width="10" height="8" rx="2" fill="#FFD700" opacity="0.7"/>
        <rect x="18" y="-4" width="10" height="8" rx="2" fill="#FFD700" opacity="0.7"/>
      </g>
      <g transform="translate(395,188)">
        <circle cx="0" cy="0" r="18" fill="none" stroke="#FFD700" stroke-width="4" opacity="0.6"/>
        <circle cx="0" cy="0" r="8" fill="#111" stroke="#FFD700" stroke-width="2.5" opacity="0.6"/>
        <rect x="-3" y="-23" width="6" height="9" rx="2" fill="#FFD700" opacity="0.6"/>
        <rect x="-3" y="14" width="6" height="9" rx="2" fill="#FFD700" opacity="0.6"/>
        <rect x="-23" y="-3" width="9" height="6" rx="2" fill="#FFD700" opacity="0.6"/>
        <rect x="14" y="-3" width="9" height="6" rx="2" fill="#FFD700" opacity="0.6"/>
      </g>
      <text x="250" y="283" font-family="Arial Black, sans-serif" font-size="28" font-weight="900" fill="#FFD700" text-anchor="middle" letter-spacing="3">COEN INDUSTRIES</text>
      <text x="250" y="304" font-family="Arial, sans-serif" font-size="10" fill="#FFD700" text-anchor="middle" letter-spacing="2" opacity="0.7">CREATING • INSPIRING • MAKING THE WORLD BETTER</text>
    </svg>

    <div class="hero-message">
      <h1>👋 HEY, I'M COEN!</h1>
      <p>Welcome to <strong>Coen Industries</strong> — my very own business! I find amazing art supplies and bring them right to you at great prices. I believe creativity can make the world a better place, and my mission is to get great art tools into the hands of every kid who wants to create. When you shop here, you're helping spread more art, more imagination, and more good into the world. Let's make it better — together! 🌍🎨✨</p>
    </div>

    <div class="hero-badges">
      <div class="badge">🎨 ART SUPPLIES</div>
      <div class="badge">💛 KID-OWNED BUSINESS</div>
      <div class="badge">🌍 MAKING THE WORLD BETTER</div>
      <div class="badge">⭐ GREAT PRICES</div>
    </div>

    <div class="hero-cta">
      <button class="btn-primary" onclick="showPage('shop')">🛒 SHOP NOW</button>
      <button class="btn-outline" onclick="showPage('gallery')">🎨 SEE MY ART</button>
    </div>
  </div>
</div>

<!-- SHOP -->
<div class="page" id="page-shop">
  <div class="page-header">
    <h2>🏪 THE SHOP</h2>
    <p>Quality art supplies curated by Coen • Great prices • Ready to create!</p>
  </div>
  <div class="shop-list">

    <div class="shop-item">
      <div class="shop-item-img">🖌️</div>
      <div class="shop-item-info">
        <h3>PAINTBRUSH SET</h3>
        <p>A set of paintbrushes perfect for watercolors, acrylics, or anything you want to paint. Different sizes so you can do big bold strokes AND tiny details!</p>
        <span class="shop-item-tag">🎨 ART SUPPLY</span>
      </div>
      <div class="shop-item-right">
        <div class="price">$2</div>
        <button class="add-to-cart" onclick="addToCart(this,'Paintbrush Set',2)">+ ADD TO CART</button>
      </div>
    </div>

    <div class="shop-item">
      <div class="shop-item-img">✏️</div>
      <div class="shop-item-info">
        <h3>COLORED PENCILS</h3>
        <p>Bright, rich colored pencils great for drawing, shading, and coloring. A must-have for any artist. Super smooth on paper!</p>
        <span class="shop-item-tag">🎨 ART SUPPLY</span>
      </div>
      <div class="shop-item-right">
        <div class="price">$3</div>
        <button class="add-to-cart" onclick="addToCart(this,'Colored Pencils',3)">+ ADD TO CART</button>
      </div>
    </div>

    <div class="shop-item">
      <div class="shop-item-img">📓</div>
      <div class="shop-item-info">
        <h3>SKETCHBOOK</h3>
        <p>A fresh sketchbook ready for your next big idea. Thick pages that hold up to pencil, marker, and light paint. Fill it up with your imagination!</p>
        <span class="shop-item-tag">🎨 ART SUPPLY</span>
      </div>
      <div class="shop-item-right">
        <div class="price">$3</div>
        <button class="add-to-cart" onclick="addToCart(this,'Sketchbook',3)">+ ADD TO CART</button>
      </div>
    </div>

    <div class="shop-item">
      <div class="shop-item-img">🖍️</div>
      <div class="shop-item-info">
        <h3>MARKERS PACK</h3>
        <p>Bold, vibrant markers in a rainbow of colors. Perfect for posters, cards, comic books, or just doodling. The colors really pop!</p>
        <span class="shop-item-tag">🎨 ART SUPPLY</span>
      </div>
      <div class="shop-item-right">
        <div class="price">$2</div>
        <button class="add-to-cart" onclick="addToCart(this,'Markers Pack',2)">+ ADD TO CART</button>
      </div>
    </div>

    <div class="shop-item">
      <div class="shop-item-img">🎭</div>
      <div class="shop-item-info">
        <h3>WATERCOLOR SET</h3>
        <p>A classic watercolor paint set with a full spectrum of colors. Great for landscapes, portraits, or experimenting with blending and washes.</p>
        <span class="shop-item-tag">🎨 ART SUPPLY</span>
      </div>
      <div class="shop-item-right">
        <div class="price">$3</div>
        <button class="add-to-cart" onclick="addToCart(this,'Watercolor Set',3)">+ ADD TO CART</button>
      </div>
    </div>

  </div>
</div>

<!-- GALLERY -->
<div class="page" id="page-gallery">
  <div class="page-header">
    <h2>🎨 ART GALLERY</h2>
    <p>Original artwork created by Coen Cross</p>
  </div>
  <div class="gallery-grid">
    <div class="gallery-card"><div class="gallery-img">🖼️</div><div class="gallery-info"><h3>MY FIRST PAINTING</h3></div></div>
    <div class="gallery-card"><div class="gallery-img">🌈</div><div class="gallery-info"><h3>RAINBOW CITY</h3></div></div>
    <div class="gallery-card"><div class="gallery-img">🦁</div><div class="gallery-info"><h3>LION PORTRAIT</h3></div></div>
    <div class="gallery-card"><div class="gallery-img">🚀</div><div class="gallery-info"><h3>SPACE EXPLORER</h3></div></div>
    <div class="gallery-card"><div class="gallery-img">🏔️</div><div class="gallery-info"><h3>MOUNTAIN LANDSCAPE</h3></div></div>
    <div class="gallery-card"><div class="gallery-img">♻️</div><div class="gallery-info"><h3>RECYCLE ROBOT</h3></div></div>
  </div>
  <div class="gallery-note">🖼️ <span>Real photos of Coen's artwork coming soon!</span> Check back as the gallery grows.</div>
</div>

<footer>© 2026 <span>Coen Industries</span> • Founded by Coen Cross • Portland, Oregon • <span>Creating • Inspiring • Making the World Better</span></footer>

<script>
  // VISITOR COUNTER
  function updateVisitorCount() {
    const key = 'coen_industries_visitors';
    const sessionKey = 'coen_industries_visited';
    let count = parseInt(localStorage.getItem(key) || '1482', 10);
    if (!sessionStorage.getItem(sessionKey)) {
      count++;
      localStorage.setItem(key, count);
      sessionStorage.setItem(sessionKey, 'yes');
    }
    document.getElementById('visitor-count').textContent = count.toLocaleString();
  }
  updateVisitorCount();

  // NAVIGATION
  function showPage(name) {
    document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
    document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
    document.getElementById('page-' + name).classList.add('active');
    document.getElementById('nav-' + name).classList.add('active');
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  // CART
  let cart = [];
  function addToCart(btn, name, price) {
    cart.push({ name, price });
    updateCartUI();
    btn.textContent = '✓ ADDED!';
    btn.classList.add('added');
    setTimeout(() => { btn.textContent = '+ ADD TO CART'; btn.classList.remove('added'); }, 1500);
  }
  function removeFromCart(index) { cart.splice(index, 1); updateCartUI(); }
  function updateCartUI() {
    document.getElementById('cart-count').textContent = cart.length;
    const itemsEl = document.getElementById('cart-items');
    const totalEl = document.getElementById('cart-total');
    const noteEl  = document.getElementById('checkout-note');
    if (cart.length === 0) {
      itemsEl.innerHTML = '<div class="cart-empty">Your cart is empty!<br>Go grab something cool 😄</div>';
      totalEl.style.display = 'none'; noteEl.style.display = 'none';
    } else {
      let html = '', total = 0;
      cart.forEach((item, i) => {
        total += item.price;
        html += `<div class="cart-line"><span class="item-name">${item.name}</span><span class="item-price">$${item.price}</span><button class="remove-item" onclick="removeFromCart(${i})">✕</button></div>`;
      });
      itemsEl.innerHTML = html;
      document.getElementById('total-price').textContent = '$' + total;
      totalEl.style.display = 'flex'; noteEl.style.display = 'block';
    }
  }
  function toggleCart() { document.getElementById('cart-overlay').classList.toggle('open'); }
  function closeCartOutside(e) { if (e.target === document.getElementById('cart-overlay')) toggleCart(); }
</script>
</body>
</html>
