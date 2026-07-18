<!DOCTYPE html>
<html lang="ms">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Feedoz Enterprise menyediakan reka poster, reka logo dan penyediaan surat rasmi untuk syarikat, acara dan usahawan.">
  <meta name="theme-color" content="#080808">
  <title>Feedoz Enterprise | Creative Digital Services</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="loader" id="loader">
    <div class="loader-mark">FE</div>
  </div>

  <header class="header" id="header">
    <div class="container nav">
      <a href="#home" class="brand">
        <img src="assets/feedoz-logo.jpeg" alt="Logo Feedoz Enterprise">
        <div>
          <strong>FEEDOZ ENTERPRISE</strong>
          <span>Innovate • Empower • Grow</span>
        </div>
      </a>

      <button class="menu-toggle" id="menuToggle" aria-label="Buka menu">☰</button>

      <nav id="navMenu">
        <a href="#home">Utama</a>
        <a href="#services">Servis</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#pricing">Pakej</a>
        <a href="#contact">Hubungi</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="hero-grid-overlay"></div>
      <div class="glow glow-one"></div>
      <div class="glow glow-two"></div>

      <div class="container hero-layout">
        <div class="hero-copy reveal">
          <p class="eyebrow">CREATIVE • CORPORATE • DIGITAL</p>
          <h1>Naikkan imej bisnes anda dengan rekaan yang <span>lebih meyakinkan.</span></h1>
          <p class="lead">
            Feedoz Enterprise membantu usahawan, syarikat dan penganjur acara
            menghasilkan poster, logo serta dokumen rasmi yang kemas dan profesional.
          </p>

          <div class="hero-actions">
            <a class="btn btn-gold" href="https://wa.me/60193996980?text=Assalamualaikum%20Feedoz%20Enterprise%2C%20saya%20ingin%20bertanya%20tentang%20servis." target="_blank" rel="noopener">WhatsApp Sekarang</a>
            <a class="btn btn-dark" href="#portfolio">Lihat Portfolio</a>
          </div>

          <div class="stats">
            <div><strong>3</strong><span>Servis Utama</span></div>
            <div><strong>18</strong><span>Contoh Portfolio</span></div>
            <div><strong>100%</strong><span>Urusan Online</span></div>
          </div>
        </div>

        <div class="hero-card reveal">
          <div class="hero-card-ring"></div>
          <img src="assets/feedoz-logo.jpeg" alt="Feedoz Enterprise">
          <p>Professional creative solutions for modern businesses.</p>
        </div>
      </div>
    </section>

    <section class="section intro-section">
      <div class="container intro-grid">
        <div class="reveal">
          <p class="section-tag">TENTANG KAMI</p>
          <h2>Idea anda, kami susun menjadi sesuatu yang bernilai.</h2>
        </div>
        <div class="intro-copy reveal">
          <p>
            Kami menyediakan perkhidmatan kreatif dan dokumentasi yang sesuai
            untuk kegunaan syarikat, perniagaan kecil, program, acara dan promosi digital.
          </p>
          <p>
            Setiap tugasan disusun berdasarkan objektif pelanggan, identiti jenama
            dan gaya yang ingin ditampilkan.
          </p>
        </div>
      </div>
    </section>

    <section class="section services-section" id="services">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-tag">SERVIS KAMI</p>
          <h2>Penyelesaian utama Feedoz Enterprise</h2>
          <p>Servis yang mudah ditempah dan sesuai untuk pelbagai jenis perniagaan.</p>
        </div>

        <div class="service-grid">
          <article class="service-card reveal">
            <span class="service-no">01</span>
            <div class="service-icon">✦</div>
            <h3>Reka Poster</h3>
            <p>Poster promosi, syarikat, acara, pakej, menu, jualan dan media sosial.</p>
            <a href="https://wa.me/60193996980?text=Saya%20berminat%20dengan%20servis%20reka%20poster." target="_blank" rel="noopener">Tempah poster →</a>
          </article>

          <article class="service-card reveal">
            <span class="service-no">02</span>
            <div class="service-icon">A</div>
            <h3>Reka Logo</h3>
            <p>Logo moden untuk syarikat, produk, projek, program dan perniagaan baharu.</p>
            <a href="https://wa.me/60193996980?text=Saya%20berminat%20dengan%20servis%20reka%20logo." target="_blank" rel="noopener">Tempah logo →</a>
          </article>

          <article class="service-card reveal">
            <span class="service-no">03</span>
            <div class="service-icon">▤</div>
            <h3>Surat Rasmi</h3>
            <p>Surat permohonan, makluman, tawaran, notis, perjanjian dan dokumen korporat.</p>
            <a href="https://wa.me/60193996980?text=Saya%20berminat%20dengan%20servis%20surat%20rasmi." target="_blank" rel="noopener">Sediakan surat →</a>
          </article>
        </div>
      </div>
    </section>

    <section class="section portfolio-section" id="portfolio">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-tag">PORTFOLIO</p>
          <h2>Contoh hasil kerja Feedoz Enterprise</h2>
          <p>10 contoh poster, 5 konsep logo dan 3 contoh surat rasmi.</p>
        </div>

        <div class="portfolio-showcase reveal">
          <img src="assets/portfolio-board.png" alt="Portfolio Feedoz Enterprise">
        </div>

        <div class="portfolio-tabs reveal">
          <button class="tab active" data-filter="all">Semua</button>
          <button class="tab" data-filter="poster">Poster</button>
          <button class="tab" data-filter="logo">Logo</button>
          <button class="tab" data-filter="document">Surat Rasmi</button>
        </div>

        <div class="portfolio-grid">
          <article class="portfolio-card reveal" data-category="poster">
            <span>POSTER</span><h3>Corporate Event</h3><p>Rekaan profesional untuk syarikat dan acara rasmi.</p>
          </article>
          <article class="portfolio-card reveal" data-category="poster">
            <span>POSTER</span><h3>Umrah Promotion</h3><p>Poster pakej pelancongan dan promosi umrah.</p>
          </article>
          <article class="portfolio-card reveal" data-category="poster">
            <span>POSTER</span><h3>Restaurant Campaign</h3><p>Bahan promosi untuk menu dan kempen jualan.</p>
          </article>
          <article class="portfolio-card reveal" data-category="logo">
            <span>LOGO</span><h3>Modern Monogram</h3><p>Konsep minimalis dan mudah dikenali.</p>
          </article>
          <article class="portfolio-card reveal" data-category="logo">
            <span>LOGO</span><h3>Premium Identity</h3><p>Identiti eksklusif dengan gaya korporat.</p>
          </article>
          <article class="portfolio-card reveal" data-category="document">
            <span>SURAT RASMI</span><h3>Corporate Letter</h3><p>Susun atur kemas dengan gaya profesional.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section process-section">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-tag">CARA TEMPAHAN</p>
          <h2>Tiga langkah mudah</h2>
        </div>
        <div class="process-grid">
          <div class="process-card reveal"><span>1</span><h3>Hubungi</h3><p>Terangkan jenis servis yang diperlukan.</p></div>
          <div class="process-card reveal"><span>2</span><h3>Hantar bahan</h3><p>Berikan teks, gambar, warna atau rujukan.</p></div>
          <div class="process-card reveal"><span>3</span><h3>Semakan</h3><p>Hasil disediakan untuk semakan dan penambahbaikan.</p></div>
        </div>
      </div>
    </section>

    <section class="section pricing-section" id="pricing">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-tag">PAKEJ CADANGAN</p>
          <h2>Pilihan mudah untuk pelanggan</h2>
          <p>Harga akhir boleh disesuaikan mengikut tahap kesukaran dan keperluan projek.</p>
        </div>

        <div class="pricing-grid">
          <article class="price-card reveal">
            <p class="plan">STARTER</p>
            <h3>RM99</h3>
            <ul>
              <li>1 reka poster</li>
              <li>1 konsep utama</li>
              <li>Semakan asas</li>
            </ul>
            <a class="btn btn-dark full" href="https://wa.me/60193996980?text=Saya%20berminat%20dengan%20Pakej%20Starter." target="_blank" rel="noopener">Pilih Starter</a>
          </article>

          <article class="price-card featured reveal">
            <div class="popular">POPULAR</div>
            <p class="plan">BUSINESS</p>
            <h3>RM299</h3>
            <ul>
              <li>3 reka poster</li>
              <li>1 logo ringkas</li>
              <li>Semakan keutamaan</li>
            </ul>
            <a class="btn btn-gold full" href="https://wa.me/60193996980?text=Saya%20berminat%20dengan%20Pakej%20Business." target="_blank" rel="noopener">Pilih Business</a>
          </article>

          <article class="price-card reveal">
            <p class="plan">PREMIUM</p>
            <h3>Sebut Harga</h3>
            <ul>
              <li>Branding lengkap</li>
              <li>Poster, logo & dokumen</li>
              <li>Keperluan tersuai</li>
            </ul>
            <a class="btn btn-dark full" href="https://wa.me/60193996980?text=Saya%20ingin%20mendapatkan%20sebut%20harga%20Pakej%20Premium." target="_blank" rel="noopener">Minta Sebut Harga</a>
          </article>
        </div>
      </div>
    </section>

    <section class="contact-section" id="contact">
      <div class="container contact-panel reveal">
        <div>
          <p class="section-tag">HUBUNGI KAMI</p>
          <h2>Mulakan projek anda bersama Feedoz Enterprise.</h2>
          <p>Hubungi kami untuk pertanyaan, tempahan atau sebut harga.</p>
        </div>
        <div class="contact-list">
          <a href="tel:+60193996980"><small>Telefon / WhatsApp</small><strong>019-399 6980</strong></a>
          <a href="mailto:feedozenterprise@gmail.com"><small>E-mel</small><strong>feedozenterprise@gmail.com</strong></a>
          <a class="btn btn-gold full" href="https://wa.me/60193996980?text=Assalamualaikum%20Feedoz%20Enterprise%2C%20saya%20ingin%20membuat%20tempahan." target="_blank" rel="noopener">Dapatkan Sebut Harga</a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container footer-content">
      <div>
        <strong>FEEDOZ ENTERPRISE</strong>
        <p>Innovate • Empower • Grow</p>
      </div>
      <p>© <span id="year"></span> Feedoz Enterprise. Hak cipta terpelihara.</p>
    </div>
  </footer>

  <a class="whatsapp-float" href="https://wa.me/60193996980?text=Assalamualaikum%20Feedoz%20Enterprise%2C%20saya%20ingin%20bertanya%20tentang%20servis." target="_blank" rel="noopener">
    WhatsApp
  </a>

  <script src="script.js"></script>
</body>
</html>
