<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mishras Housing | Your Dream Home in Vasai-Nalasopara</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700;900&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --gold: #C9A84C;
    --gold-light: #E8C96A;
    --dark: #0D0D0D;
    --dark2: #161616;
    --dark3: #1E1E1E;
    --cream: #F5F0E8;
    --cream2: #EDE6D6;
    --text-muted: #888;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--dark);
    color: var(--cream);
    font-family: 'DM Sans', sans-serif;
    overflow-x: hidden;
  }

  /* HERO */
  .hero {
    min-height: 100vh;
    background: linear-gradient(135deg, #0D0D0D 0%, #1a1208 50%, #0D0D0D 100%);
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 2rem;
    overflow: hidden;
  }

  .hero::before {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse 80% 60% at 50% 40%, rgba(201,168,76,0.12) 0%, transparent 70%);
  }

  .hero-grid {
    position: absolute;
    inset: 0;
    background-image: 
      linear-gradient(rgba(201,168,76,0.05) 1px, transparent 1px),
      linear-gradient(90deg, rgba(201,168,76,0.05) 1px, transparent 1px);
    background-size: 60px 60px;
    mask-image: radial-gradient(ellipse at center, black 30%, transparent 75%);
  }

  .hero-content {
    position: relative;
    z-index: 2;
    max-width: 860px;
  }

  .hero-badge {
    display: inline-block;
    border: 1px solid rgba(201,168,76,0.4);
    color: var(--gold);
    font-size: 0.7rem;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    padding: 0.45rem 1.2rem;
    border-radius: 100px;
    margin-bottom: 2rem;
    animation: fadeUp 0.8s ease both;
  }

  .hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2.8rem, 7vw, 5.5rem);
    font-weight: 900;
    line-height: 1.08;
    margin-bottom: 1.5rem;
    animation: fadeUp 0.8s 0.15s ease both;
  }

  .hero h1 span {
    color: var(--gold);
    display: block;
  }

  .hero p {
    font-size: clamp(1rem, 2vw, 1.2rem);
    color: #aaa;
    max-width: 560px;
    margin: 0 auto 2.5rem;
    line-height: 1.7;
    animation: fadeUp 0.8s 0.3s ease both;
  }

  .hero-cta {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
    animation: fadeUp 0.8s 0.45s ease both;
  }

  .btn-primary {
    background: var(--gold);
    color: var(--dark);
    padding: 0.9rem 2.2rem;
    border-radius: 6px;
    font-weight: 600;
    font-size: 0.95rem;
    text-decoration: none;
    letter-spacing: 0.02em;
    transition: all 0.3s;
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
  }

  .btn-primary:hover {
    background: var(--gold-light);
    transform: translateY(-2px);
    box-shadow: 0 12px 40px rgba(201,168,76,0.3);
  }

  .btn-outline {
    border: 1px solid rgba(201,168,76,0.5);
    color: var(--gold);
    padding: 0.9rem 2.2rem;
    border-radius: 6px;
    font-weight: 500;
    font-size: 0.95rem;
    text-decoration: none;
    transition: all 0.3s;
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
  }

  .btn-outline:hover {
    background: rgba(201,168,76,0.08);
    border-color: var(--gold);
    transform: translateY(-2px);
  }

  /* STATS */
  .stats {
    background: var(--dark2);
    border-top: 1px solid rgba(201,168,76,0.15);
    border-bottom: 1px solid rgba(201,168,76,0.15);
    padding: 3rem 2rem;
  }

  .stats-grid {
    max-width: 900px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 2rem;
    text-align: center;
  }

  .stat-num {
    font-family: 'Playfair Display', serif;
    font-size: 2.8rem;
    font-weight: 700;
    color: var(--gold);
    line-height: 1;
  }

  .stat-label {
    font-size: 0.82rem;
    color: var(--text-muted);
    text-transform: uppercase;
    letter-spacing: 0.1em;
    margin-top: 0.4rem;
  }

  /* SECTION BASE */
  section { padding: 5rem 2rem; }

  .container { max-width: 1000px; margin: 0 auto; }

  .section-label {
    font-size: 0.7rem;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 0.8rem;
  }

  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2rem, 4vw, 3rem);
    font-weight: 700;
    line-height: 1.2;
    margin-bottom: 1rem;
  }

  .section-sub {
    color: #999;
    font-size: 1rem;
    line-height: 1.7;
    max-width: 560px;
    margin-bottom: 3rem;
  }

  /* SERVICES */
  .services { background: var(--dark); }

  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1.5rem;
    margin-top: 3rem;
  }

  .service-card {
    background: var(--dark2);
    border: 1px solid rgba(255,255,255,0.06);
    border-radius: 12px;
    padding: 2rem;
    transition: all 0.3s;
    position: relative;
    overflow: hidden;
  }

  .service-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, transparent, var(--gold), transparent);
    opacity: 0;
    transition: opacity 0.3s;
  }

  .service-card:hover {
    border-color: rgba(201,168,76,0.25);
    transform: translateY(-4px);
    box-shadow: 0 20px 60px rgba(0,0,0,0.4);
  }

  .service-card:hover::before { opacity: 1; }

  .service-icon {
    font-size: 2rem;
    margin-bottom: 1rem;
  }

  .service-card h3 {
    font-family: 'Playfair Display', serif;
    font-size: 1.2rem;
    margin-bottom: 0.6rem;
    color: var(--cream);
  }

  .service-card p {
    font-size: 0.9rem;
    color: #888;
    line-height: 1.6;
  }

  /* WHY US */
  .why { background: var(--dark2); }

  .why-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.5rem;
    margin-top: 3rem;
  }

  .why-item {
    display: flex;
    gap: 1rem;
    align-items: flex-start;
  }

  .why-dot {
    width: 36px;
    height: 36px;
    background: rgba(201,168,76,0.12);
    border: 1px solid rgba(201,168,76,0.3);
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1rem;
    flex-shrink: 0;
  }

  .why-item h4 {
    font-size: 0.95rem;
    font-weight: 600;
    margin-bottom: 0.3rem;
    color: var(--cream);
  }

  .why-item p {
    font-size: 0.82rem;
    color: #777;
    line-height: 1.5;
  }

  /* AREAS */
  .areas { background: var(--dark); }

  .areas-list {
    display: flex;
    flex-wrap: wrap;
    gap: 0.8rem;
    margin-top: 2rem;
  }

  .area-tag {
    background: var(--dark2);
    border: 1px solid rgba(201,168,76,0.2);
    color: var(--cream2);
    padding: 0.5rem 1.2rem;
    border-radius: 100px;
    font-size: 0.88rem;
    transition: all 0.3s;
  }

  .area-tag:hover {
    background: rgba(201,168,76,0.1);
    border-color: var(--gold);
    color: var(--gold);
  }

  /* CTA SECTION */
  .cta-section {
    background: linear-gradient(135deg, #1a1208, #0d0d0d);
    border-top: 1px solid rgba(201,168,76,0.2);
    text-align: center;
    padding: 5rem 2rem;
  }

  .cta-section h2 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2rem, 4vw, 3.2rem);
    margin-bottom: 1rem;
  }

  .cta-section h2 span { color: var(--gold); }

  .cta-section p {
    color: #999;
    margin-bottom: 2.5rem;
    font-size: 1rem;
  }

  /* CONTACT */
  .contact-cards {
    display: flex;
    justify-content: center;
    gap: 1.2rem;
    flex-wrap: wrap;
    margin-top: 1rem;
  }

  .contact-card {
    background: var(--dark2);
    border: 1px solid rgba(201,168,76,0.2);
    border-radius: 10px;
    padding: 1.2rem 1.8rem;
    text-decoration: none;
    color: var(--cream);
    display: flex;
    align-items: center;
    gap: 0.8rem;
    transition: all 0.3s;
    font-size: 0.9rem;
  }

  .contact-card:hover {
    border-color: var(--gold);
    background: rgba(201,168,76,0.08);
    transform: translateY(-3px);
    box-shadow: 0 12px 40px rgba(201,168,76,0.15);
  }

  .contact-icon { font-size: 1.3rem; }

  /* FOOTER */
  footer {
    background: #080808;
    border-top: 1px solid rgba(255,255,255,0.05);
    padding: 2rem;
    text-align: center;
  }

  .footer-logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.4rem;
    color: var(--gold);
    margin-bottom: 0.5rem;
    letter-spacing: 0.05em;
  }

  footer p {
    font-size: 0.8rem;
    color: #555;
  }

  /* UDYAM BADGE */
  .udyam-badge {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    background: rgba(201,168,76,0.08);
    border: 1px solid rgba(201,168,76,0.25);
    border-radius: 6px;
    padding: 0.4rem 1rem;
    font-size: 0.75rem;
    color: var(--gold);
    letter-spacing: 0.05em;
    margin-top: 1.5rem;
  }

  /* ANIMATIONS */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .fade-in {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s ease, transform 0.6s ease;
  }

  .fade-in.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* NAV */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    padding: 1.2rem 2rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: rgba(13,13,13,0.85);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid rgba(201,168,76,0.1);
  }

  .nav-logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.3rem;
    color: var(--gold);
    text-decoration: none;
    letter-spacing: 0.05em;
  }

  .nav-cta {
    background: var(--gold);
    color: var(--dark);
    padding: 0.55rem 1.4rem;
    border-radius: 6px;
    font-weight: 600;
    font-size: 0.85rem;
    text-decoration: none;
    transition: all 0.3s;
  }

  .nav-cta:hover { background: var(--gold-light); }

  .hero { padding-top: 5rem; }

  /* RESPONSIVE */
  @media (max-width: 600px) {
    .hero-cta { flex-direction: column; align-items: center; }
    .btn-primary, .btn-outline { width: 100%; max-width: 280px; justify-content: center; }
    .contact-card { width: 100%; max-width: 320px; justify-content: center; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <a href="#" class="nav-logo">Mishras Housing</a>
  <a href="https://wa.me/919529060919" class="nav-cta">📞 Contact Us</a>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-grid"></div>
  <div class="hero-content">
    <div class="hero-badge">✦ Vasai · Nalasopara · Virar ✦</div>
    <h1>
      Apna Pehla Ghar
      <span>Humare Saath</span>
    </h1>
    <p>Trusted real estate partner for first-time home buyers in the Vasai-Virar corridor. Flats from ₹50L–₹1Cr in prime locations.</p>
    <div class="hero-cta">
      <a href="https://wa.me/91XXXXXXXXXX?text=Namaste!%20Ghar%20dekhna%20hai" class="btn-primary">
        💬 WhatsApp Now
      </a>
      <a href="#services" class="btn-outline">
        🏠 Our Services
      </a>
    </div>
    <div class="udyam-badge">
      🏛️ MSME Registered · UDYAM-MH-17-0238360
    </div>
  </div>
</section>

<!-- STATS -->
<div class="stats">
  <div class="stats-grid">
    <div class="fade-in">
      <div class="stat-num">500+</div>
      <div class="stat-label">Happy Families</div>
    </div>
    <div class="fade-in">
      <div class="stat-num">₹50L</div>
      <div class="stat-label">Starting Price</div>
    </div>
    <div class="fade-in">
      <div class="stat-num">3</div>
      <div class="stat-label">Prime Locations</div>
    </div>
    <div class="fade-in">
      <div class="stat-num">5★</div>
      <div class="stat-label">Client Rating</div>
    </div>
  </div>
</div>

<!-- SERVICES -->
<section class="services" id="services">
  <div class="container">
    <div class="section-label fade-in">What We Offer</div>
    <h2 class="section-title fade-in">Ghar Dhundna Ab<br>Aasaan Ho Gaya</h2>
    <p class="section-sub fade-in">End-to-end support — from property search to registration — sab kuch ek jagah.</p>
    <div class="services-grid">
      <div class="service-card fade-in">
        <div class="service-icon">🏢</div>
        <h3>Flat Buying</h3>
        <p>1BHK se 3BHK tak — builder deals, site visits, aur loan assistance sab included.</p>
      </div>
      <div class="service-card fade-in">
        <div class="service-icon">🔑</div>
        <h3>Resale Properties</h3>
        <p>Ready-to-move flats at best prices. Legal verification aur negotiation mein puri help.</p>
      </div>
      <div class="service-card fade-in">
        <div class="service-icon">💰</div>
        <h3>Home Loan Help</h3>
        <p>SBI, HDFC, LIC — sabse best rate pe loan dilaate hain. Zero processing stress.</p>
      </div>
      <div class="service-card fade-in">
        <div class="service-icon">📋</div>
        <h3>Documentation</h3>
        <p>Agreement, registration, stamp duty — poori paperwork hum handle karte hain.</p>
      </div>
      <div class="service-card fade-in">
        <div class="service-icon">🏗️</div>
        <h3>New Projects</h3>
        <p>Vasai East ka premium project — Deep Sky G+23. Pre-launch pricing available.</p>
      </div>
      <div class="service-card fade-in">
        <div class="service-icon">🤝</div>
        <h3>Free Consultation</h3>
        <p>Pehli meeting bilkul free. Budget, location, requirements — sab baat karein.</p>
      </div>
    </div>
  </div>
</section>

<!-- WHY US -->
<section class="why">
  <div class="container">
    <div class="section-label fade-in">Why Mishras Housing</div>
    <h2 class="section-title fade-in">Hum Alag Kyun Hain</h2>
    <div class="why-grid">
      <div class="why-item fade-in">
        <div class="why-dot">🏡</div>
        <div>
          <h4>Local Experts</h4>
          <p>Vasai-Nalasopara ki har gali ka pata hai humein</p>
        </div>
      </div>
      <div class="why-item fade-in">
        <div class="why-dot">💎</div>
        <div>
          <h4>No Hidden Charges</h4>
          <p>Zero surprises — poori clarity pehle din se</p>
        </div>
      </div>
      <div class="why-item fade-in">
        <div class="why-dot">⚡</div>
        <div>
          <h4>Fast Process</h4>
          <p>Site visit to booking — 48 ghante mein</p>
        </div>
      </div>
      <div class="why-item fade-in">
        <div class="why-dot">🛡️</div>
        <div>
          <h4>MSME Registered</h4>
          <p>Government verified business — 100% trustworthy</p>
        </div>
      </div>
      <div class="why-item fade-in">
        <div class="why-dot">📱</div>
        <div>
          <h4>WhatsApp Support</h4>
          <p>Koi bhi sawaal — seedha WhatsApp karo</p>
        </div>
      </div>
      <div class="why-item fade-in">
        <div class="why-dot">❤️</div>
        <div>
          <h4>First-Time Buyer Focus</h4>
          <p>Pehla ghar kharidna — humari speciality</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- AREAS -->
<section class="areas">
  <div class="container">
    <div class="section-label fade-in">Coverage</div>
    <h2 class="section-title fade-in">Hamari Service Areas</h2>
    <p class="section-sub fade-in">Vasai-Virar Municipal Corporation ke in prime areas mein properties available hain:</p>
    <div class="areas-list fade-in">
      <span class="area-tag">Vasai East</span>
      <span class="area-tag">Vasai West</span>
      <span class="area-tag">Nalasopara East</span>
      <span class="area-tag">Nalasopara West</span>
      <span class="area-tag">Virar East</span>
      <span class="area-tag">Virar West</span>
      <span class="area-tag">Nala Sopara Station Area</span>
      <span class="area-tag">Achole Road</span>
      <span class="area-tag">Tulinj</span>
      <span class="area-tag">Pelhar</span>
      <span class="area-tag">Navghar</span>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section">
  <div class="section-label">Ready to Buy?</div>
  <h2>Apna <span>Sapna Ghar</span><br>Aaj Hi Dekho</h2>
  <p>Free site visit book karo — zero commitment, zero charges</p>
  <div class="contact-cards">
    <a href="https://wa.me/91XXXXXXXXXX?text=Namaste!%20Mujhe%20property%20dekhni%20hai" class="contact-card">
      <span class="contact-icon">💬</span>
      <div>
        <div style="font-weight:600">WhatsApp</div>
        <div style="font-size:0.78rem;color:#888">+91 XXXXX XXXXX</div>
      </div>
    </a>
    <a href="tel:+91XXXXXXXXXX" class="contact-card">
      <span class="contact-icon">📞</span>
      <div>
        <div style="font-weight:600">Call Us</div>
        <div style="font-size:0.78rem;color:#888">Mon–Sat, 9AM–8PM</div>
      </div>
    </a>
    <a href="https://maps.google.com/?q=Nalasopara,Vasai,Maharashtra" class="contact-card">
      <span class="contact-icon">📍</span>
      <div>
        <div style="font-weight:600">Office</div>
        <div style="font-size:0.78rem;color:#888">Nalasopara, Vasai</div>
      </div>
    </a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-logo">Mishras Housing</div>
  <p style="margin-bottom:0.4rem">Vasai · Nalasopara · Virar — Maharashtra</p>
  <p>MSME Reg: UDYAM-MH-17-0238360 · © 2025 Mishras Housing. All rights reserved.</p>
</footer>

<script>
  // Scroll animations
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
</script>
</body>
</html>
