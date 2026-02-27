<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>AJ Fashion | Official Store</title>
  <meta name="description" content="AJ Fashion — Premium Panjabi, Stylish Shirts and Elegant Sarees. Shop via our Facebook store or message us on WhatsApp." />

  <style>
  *{margin:0;padding:0;box-sizing:border-box}
  body{font-family:'Poppins',sans-serif;background:#0f0f0f;color:#fff;scroll-behavior:smooth}
  a{text-decoration:none}
  /* NAVBAR */
  nav{position:fixed;top:0;width:100%;background:#111;padding:15px 30px;display:flex;justify-content:space-between;align-items:center;z-index:999}
  nav h2{color:#d4af37;font-weight:800;letter-spacing:1px}
  nav a{color:#fff;margin-left:20px;font-weight:500;transition:.3s}
  nav a:hover{color:#d4af37}
  /* HERO */
  header{height:100vh;background:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),linear-gradient(135deg,#1a1a1a,#333);background-size:cover;background-position:center;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;padding:20px}
  header h1{font-size:48px;font-weight:800;letter-spacing:2px}
  header p{margin-top:15px;font-size:20px;color:#ccc}
  .hero-buttons{margin-top:30px}
  .btn{padding:14px 35px;border-radius:40px;font-weight:700;margin:10px;display:inline-block;transition:.3s;border:none;cursor:pointer}
  .btn-gold{background:#d4af37;color:#000}
  .btn-gold:hover{box-shadow:0 0 25px #d4af37,0 0 50px #d4af37;transform:scale(1.05)}
  .btn-outline{border:2px solid #d4af37;color:#d4af37;background:transparent}
  .btn-outline:hover{background:#d4af37;color:#000}
  /* SECTIONS */
  .section{padding:100px 20px;max-width:1200px;margin:auto}
  .section h2{text-align:center;margin-bottom:50px;font-size:32px;color:#d4af37}
  /* PRODUCTS */
  .products{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:30px}
  .card{background:#1a1a1a;border-radius:20px;overflow:hidden;box-shadow:0 10px 30px rgba(0,0,0,.4);transition:.4s;cursor:pointer}
  .card:hover{transform:translateY(-10px)}
  .card img{width:100%;height:320px;object-fit:cover;transition:transform .5s,opacity .5s}
  .card img:hover{transform:scale(1.08)}
  .card-content{padding:20px;text-align:center}
  .price{color:#d4af37;font-weight:700;font-size:18px;margin-top:10px}
  /* FUNNEL CTA SECTION */
  .funnel{background:#111;text-align:center;padding:80px 20px;border-radius:20px}
  .funnel h3{font-size:28px;margin-bottom:20px}
  .funnel p{color:#ccc;margin-bottom:30px}
  /* REVIEWS */
  .reviews{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:25px}
  .review{background:#1a1a1a;padding:25px;border-radius:20px;box-shadow:0 10px 30px rgba(0,0,0,.4);transition:.3s}
  .review:hover{transform:translateY(-5px)}
  .stars{color:#f5b50a;margin:10px 0}
  /* FOOTER */
  footer{text-align:center;padding:40px;background:#000;color:#aaa}
  /* WHATSAPP FLOAT */
  .whatsapp{position:fixed;bottom:20px;right:20px;background:#25D366;color:#fff;width:65px;height:65px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:30px;box-shadow:0 5px 20px rgba(0,0,0,.6);transition:.3s;z-index:9999}
  .whatsapp:hover{transform:scale(1.1)}
  @media(max-width:768px){
  header h1{font-size:32px}
  header p{font-size:16px}
  .section{padding:70px 20px}
  }
  /* PRELOADER */
  #preloader{position:fixed;width:100%;height:100vh;background:#000;display:flex;align-items:center;justify-content:center;z-index:99999}
  .loader{border:6px solid #222;border-top:6px solid #d4af37;border-radius:50%;width:60px;height:60px;animation:spin 1s linear infinite}
  @keyframes spin{100%{transform:rotate(360deg)}}
  /* BOTTOM MOBILE BAR */
  .mobile-bar{display:none}
  @media(max-width:768px){
  .mobile-bar{display:flex;position:fixed;bottom:0;left:0;width:100%;background:#111;padding:10px;justify-content:space-around;z-index:9999}
  .mobile-bar a{color:#fff;font-weight:600}
  }
  /* ORDER MODAL */
  .modal{display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,.8);justify-content:center;align-items:center;z-index:99999}
  .modal[aria-hidden="true"]{display:none}
  .modal[aria-hidden="false"]{display:flex}
  .modal-content{background:#1a1a1a;padding:30px;border-radius:20px;width:90%;max-width:400px}
  .modal-content input, .modal-content textarea{width:100%;padding:12px;margin:10px 0;border:none;border-radius:10px}
  .close-btn{float:right;cursor:pointer;color:#d4af37;font-weight:700}
  /* LIVE ORDER POPUP */
  .live-popup{position:fixed;bottom:100px;left:20px;background:#1a1a1a;padding:15px 20px;border-radius:15px;box-shadow:0 5px 20px rgba(0,0,0,.5);display:none;z-index:9999;font-size:14px}
  </style>
</head>
<body>

  <div id="preloader" aria-hidden="false"><div class="loader" aria-hidden="true"></div></div>

  <nav>
    <h2>AJ Fashion</h2>
    <div>
      <a href="#products">Products</a>
      <a href="#reviews">Reviews</a>
      <a href="https://www.facebook.com/841560969043282" target="_blank" rel="noopener noreferrer">Shop Now</a>
    </div>
  </nav>

  <header>
    <h1>Premium Fashion Experience</h1>
    <p>Luxury Panjabi | Stylish Shirt | Elegant Saree</p>
    <div class="hero-buttons">
      <a href="https://www.facebook.com/841560969043282" target="_blank" rel="noopener noreferrer" class="btn btn-gold">Shop Now</a>
      <a href="https://m.me/841560969043282" target="_blank" rel="noopener noreferrer" class="btn btn-outline">Message Us</a>
    </div>
  </header>

  <main>
    <section class="section" id="products" aria-labelledby="products-heading">
      <h2 id="products-heading">Featured Collection</h2>
      <div class="products" id="products-grid">
        <article class="card" tabindex="0" role="button" data-product="Premium Panjabi" aria-pressed="false">
          <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='800' height='500'%3E%3Crect width='100%25' height='100%25' fill='%231a1a1a'/%3E%3Ctext x='50%25' y='50%25' fill='%23d4af37' font-size='40' text-anchor='middle' dominant-baseline='middle'%3EAJ Fashion Product%3C/text%3E%3C/svg%3E" alt="Premium Panjabi - AJ Fashion" loading="lazy">
          <div class="card-content">
            <h3>Premium Panjabi</h3>
            <div class="price">৳ 1150</div>
          </div>
        </article>

        <article class="card" tabindex="0" role="button" data-product="Stylish Shirt" aria-pressed="false">
          <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='800' height='500'%3E%3Crect width='100%25' height='100%25' fill='%231a1a1a'/%3E%3Ctext x='50%25' y='50%25' fill='%23d4af37' font-size='40' text-anchor='middle' dominant-baseline='middle'%3EAJ Fashion Product%3C/text%3E%3C/svg%3E" alt="Stylish Shirt - AJ Fashion" loading="lazy">
          <div class="card-content">
            <h3>Stylish Shirt</h3>
            <div class="price">৳ 950</div>
          </div>
        </article>

        <article class="card" tabindex="0" role="button" data-product="Elegant Saree" aria-pressed="false">
          <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='800' height='500'%3E%3Crect width='100%25' height='100%25' fill='%231a1a1a'/%3E%3Ctext x='50%25' y='50%25' fill='%23d4af37' font-size='40' text-anchor='middle' dominant-baseline='middle'%3EAJ Fashion Product%3C/text%3E%3C/svg%3E" alt="Elegant Saree - AJ Fashion" loading="lazy">
          <div class="card-content">
            <h3>Elegant Saree</h3>
            <div class="price">৳ 1650</div>
          </div>
        </article>
      </div>
    </section>

    <section class="section funnel" aria-labelledby="cta-heading">
      <h3 id="cta-heading">Ready to Upgrade Your Style?</h3>
      <p>Click below and explore our official Facebook store now.</p>
      <a href="https://www.facebook.com/841560969043282" target="_blank" rel="noopener noreferrer" class="btn btn-gold">Visit Facebook Shop</a>
      <a href="https://m.me/841560969043282" target="_blank" rel="noopener noreferrer" class="btn btn-outline">Chat on Messenger</a>
    </section>

    <section class="section" id="reviews" aria-labelledby="reviews-heading">
      <h2 id="reviews-heading">Customer Reviews</h2>
      <div class="reviews">
        <div class="review">
          <h4>Rasel</h4>
          <div class="stars" aria-hidden="true">★★★★★</div>
          <p>কাপড় ও ফিটিং অসাধারণ। AJ Fashion সত্যিই প্রিমিয়াম।</p>
        </div>
        <div class="review">
          <h4>Sakib</h4>
          <div class="stars" aria-hidden="true">★★★★★</div>
          <p>ডেলিভারি দ্রুত পেয়েছি। কোয়ালিটি একদম ছবির মতো।</p>
        </div>
        <div class="review">
          <h4>Mitu</h4>
          <div class="stars" aria-hidden="true">★★★★★</div>
          <p>ফেসবুক থেকে অর্ডার করেছি, সার্ভিস খুব ভালো।</p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    © 2026 AJ Fashion | WhatsApp: 01722123003
  </footer>

  <!-- WhatsApp / Order floating button -->
  <a href="#" class="whatsapp" id="open-order" role="button" aria-label="Open order modal">🛒</a>

  <!-- COUNTDOWN DISPLAY -->
  <div id="countdown-badge" style="position:fixed;top:70px;right:20px;background:#d4af37;color:#000;padding:10px 20px;border-radius:30px;font-weight:700;z-index:9999;box-shadow:0 5px 20px rgba(0,0,0,.4)">
    🔥 Offer Ends In: <span id="countdown">24:00:00</span>
  </div>

  <!-- PREPARED MODAL -->
  <div class="modal" id="orderModal" role="dialog" aria-modal="true" aria-hidden="true" aria-labelledby="orderTitle">
    <div class="modal-content">
      <button class="close-btn" id="closeModalBtn" aria-label="Close order form">X</button>
      <h3 id="orderTitle" style="color:#d4af37;text-align:center">Place Your Order</h3>
      <label class="visually-hidden" for="order-name">Your Name</label>
      <input id="order-name" type="text" placeholder="Your Name" />
      <label class="visually-hidden" for="order-phone">Phone Number</label>
      <input id="order-phone" type="text" inputmode="tel" placeholder="Phone Number" />
      <label class="visually-hidden" for="order-address">Address</label>
      <textarea id="order-address" placeholder="Address"></textarea>
      <button class="btn btn-gold" id="confirmOrderBtn" style="width:100%">Confirm Order</button>
    </div>
  </div>

  <!-- LIVE ORDER POPUP -->
  <div class="live-popup" id="livePopup" aria-hidden="true"></div>

  <script>
  (function(){
    // Constants
    const WHATSAPP_NUMBER = '8801722123003'; // international format for wa.me
    const localPhoneDisplay = '01722123003'; // for footer display

    // PRELOADER
    window.addEventListener('load', function () {
      const pre = document.getElementById('preloader');
      if (pre) pre.style.display = 'none';
    });

    // COUNTDOWN (start at 23:59:59)
    (function startCountdownOnce(){
      const el = document.getElementById('countdown');
      if(!el) return;
      // start from 86399 seconds = 23:59:59
      let timer = 86399;
      function tick() {
        const hours = String(Math.floor(timer / 3600)).padStart(2,'0');
        const minutes = String(Math.floor((timer % 3600) / 60)).padStart(2,'0');
        const seconds = String(timer % 60).padStart(2,'0');
        el.textContent = hours + ':' + minutes + ':' + seconds;
        timer = (timer - 1 + 86400) % 86400;
      }
      tick();
      setInterval(tick, 1000);
    })();

    // IMAGE SLIDER: cycles opacity smoothly
    document.addEventListener('DOMContentLoaded', function(){
      const images = Array.from(document.querySelectorAll('.card img'));
      if(images.length){
        let current = 0;
        images.forEach((img,i)=> img.style.opacity = (i===current)?'1':'0.7');
        setInterval(()=>{
          images.forEach((img,i)=> img.style.opacity = (i === current) ? '1' : '0.7');
          current = (current + 1) % images.length;
        }, 2000);
      }
    });

    // PRODUCT CLICK TRACKING (safely check fbq)
    document.addEventListener('DOMContentLoaded', function(){
      const productCards = document.querySelectorAll('.card');
      productCards.forEach(card=>{
        const productName = card.querySelector('h3') ? card.querySelector('h3').innerText : card.dataset.product || '';
        card.addEventListener('click', () => {
          if(typeof fbq !== 'undefined') fbq('track','AddToCart',{content_name: productName});
        });
        // allow keyboard activation
        card.addEventListener('keydown', (e) => {
          if(e.key === 'Enter' || e.key === ' ') {
            e.preventDefault();
            card.click();
          }
        });
      });
    });

    // LIVE ORDER POPUP
    (function livePopupLoop(){
      const names=["Rafi","Sakib","Mitu","Tanvir","Jannat","Imran"];
      const products=["Premium Panjabi","Stylish Shirt","Elegant Saree"];
      const popup = document.getElementById('livePopup');
      if(!popup) return;
      setInterval(()=>{
        const name = names[Math.floor(Math.random()*names.length)];
        const product = products[Math.floor(Math.random()*products.length)];
        popup.textContent = "🔥 " + name + " just ordered " + product;
        popup.style.display = "block";
        popup.setAttribute('aria-hidden','false');
        setTimeout(()=>{ popup.style.display = "none"; popup.setAttribute('aria-hidden','true'); }, 4000);
      },8000);
    })();

    // Modal behavior (no inline onclicks)
    (function modalBehavior(){
      const openBtn = document.getElementById('open-order');
      const modal = document.getElementById('orderModal');
      const closeBtn = document.getElementById('closeModalBtn');
      const confirmBtn = document.getElementById('confirmOrderBtn');
      const nameInput = document.getElementById('order-name');
      const phoneInput = document.getElementById('order-phone');
      const addressInput = document.getElementById('order-address');

      function openModal(e){
        if(e) e.preventDefault();
        modal.setAttribute('aria-hidden','false');
        // focus the first field
        nameInput.focus();
        // trap focus is out of scope for now but recommended
      }
      function closeModal(e){
        if(e) e && e.preventDefault();
        modal.setAttribute('aria-hidden','true');
        document.getElementById('open-order').focus();
      }

      openBtn.addEventListener('click', openModal);
      closeBtn.addEventListener('click', closeModal);
      // close on backdrop click
      modal.addEventListener('click', function(e){
        if(e.target === modal) closeModal();
      });
      // close on escape
      document.addEventListener('keydown', function(e){
        if(e.key === 'Escape' && modal.getAttribute('aria-hidden') === 'false') closeModal();
      });

      confirmBtn.addEventListener('click', function(){
        const name = nameInput.value.trim();
        const phone = phoneInput.value.trim();
        const address = addressInput.value.trim();
        if(!name || !phone || !address){
          alert('Please fill all fields');
          return;
        }
        if(typeof fbq !== 'undefined') fbq('track','Purchase');
        const message = `New Order%0AName: ${encodeURIComponent(name)}%0APhone: ${encodeURIComponent(phone)}%0AAddress: ${encodeURIComponent(address)}`;
        // open WhatsApp (international format)
        window.open(`https://wa.me/${WHATSAPP_NUMBER}?text=${message}`, '_blank', 'noopener');
        closeModal();
      });
    })();

    // Smooth scroll anchor prevention for href="#"
    document.addEventListener('DOMContentLoaded', function(){
      document.querySelectorAll('a[href^="#"]').forEach(anchor=>{
        anchor.addEventListener('click',function(e){
          const target = this.getAttribute('href');
          if(!target || target === '#'){ e.preventDefault(); return; }
          e.preventDefault();
          const el = document.querySelector(target);
          if(el) el.scrollIntoView({behavior:'smooth'});
        });
      });
    });

    // Replace footer phone display if needed (keeps visual consistency)
    (function updateFooterPhone(phoneNumber){
      // footer already contains the number; if you want to ensure format, you can modify here.
    })();

  })();
  </script>

</body>
</html>
