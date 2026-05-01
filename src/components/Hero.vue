<template>
  <section class="hero">
    <div class="container hero-content">
      <button class="nav-btn prev"><i class="fa-solid fa-chevron-left"></i></button>
      
      <div class="hero-text-area">
        <div class="badge-container">
          <img src="@/assets/images/maskot.png" alt="Mascot" class="mascot" />
          <h1 class="title">KANDANG <br> CAGEFREE</h1>
          <span class="highlight">DI TELURKITA</span>
        </div>
        <p class="description">
          Kami dengan senang hati memperkenalkan Kandang Ayam Bebas Sangkar terbaru kami. Ini adalah fasilitas terbaru kami yang inovatif yang dirancang untuk memaksimalkan kesehatan ayam.
        </p>
        <button class="btn-wa">
          <i class="fa-brands fa-whatsapp"></i> HUBUNGI KAMI
        </button>
      </div>

      <button class="nav-btn next"><i class="fa-solid fa-chevron-right"></i></button>
    </div>
  </section>
</template>

<style scoped>
.hero {
  background-color: #c62828; 
  background-image: url('@/assets/images/Hero-bg.png'); 
  background-size: cover;
  background-position: center;
  padding: 60px 0;
  color: white;
  position: relative;
}
.hero-content {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  position: relative;
}
.hero-text-area {
  max-width: 600px;
  background-color: white;
  padding: 40px;
  border-radius: 40px; 
  color: #c62828;
}
.mascot { height: 80px; margin-bottom: 10px; }
.title { font-size: 36px; font-weight: 900; line-height: 1.2; }
.highlight {
  display: inline-block;
  background-color: #ffeb3b;
  color: #d32f2f;
  padding: 5px 15px;
  font-weight: bold;
  border-radius: 5px;
  margin: 10px 0 20px;
  font-size: 24px;
}
.description { font-size: 16px; margin-bottom: 20px; color: #333; }
.btn-wa {
  background-color: #25d366;
  color: white;
  border: none;
  padding: 10px 25px;
  font-size: 16px;
  font-weight: bold;
  border-radius: 25px;
  display: inline-flex;
  align-items: center;
  gap: 10px;
  cursor: pointer;
}
.btn-wa i { font-size: 24px; }
.nav-btn {
  background: transparent;
  border: none;
  color: white;
  font-size: 40px;
  cursor: pointer;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
}
.prev { left: 0; }
.next { right: 0; }

/* --- KODE RESPONSIF UNTUK HP --- */
@media (max-width: 768px) {
  .hero-content {
    flex-direction: column;
  }
  .hero-text-area {
    padding: 20px;
    border-radius: 20px;
  }
  .title { font-size: 24px; }
  .highlight { font-size: 18px; margin: 10px 0; }
  .description { font-size: 14px; }
  .nav-btn { display: none; } /* Sembunyikan tombol panah di HP */
}
</style>