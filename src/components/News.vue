<template>
  <section class="news container">
    <h2 class="section-title">LATEST NEWS</h2>
    
    <div class="news-slider">
      <button class="slide-btn"><i class="fa-solid fa-chevron-left"></i></button>
      
      <div class="news-grid">
        <div class="news-item">
          <img src="@/assets/images/news-1.png" alt="Peresmian Kandang" />
          <p>RESMIKAN KANDANG CAGEFREE, DORONG INOVASI PETERNAKAN AYAM BERKELANJUTAN UNTUK KETAHANAN PANGAN DI KEDIRI</p>
        </div>
        <div class="news-item">
          <img src="@/assets/images/news-2.png" alt="Koperasi Desa" />
          <p>KOPERASI DESA MERAH PUTIH METATU BENJENG KEMBANGKAN USAHA PETERNAKAN AYAM RAS PETELUR</p>
        </div>
        <div class="news-item">
          <img src="@/assets/images/news-3.png" alt="Gathering Mitra" />
          <p>GATHERING MITRA PT ASSASTA SAMPOERNA INDONESIA DAERAH SIDOARJO, SURABAYA DAN GRESIK</p>
        </div>
      </div>

      <button class="slide-btn"><i class="fa-solid fa-chevron-right"></i></button>
    </div>
  </section>
</template>

<style scoped>
.news { padding: 60px 20px; text-align: center; }
.news-slider {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
}
.news-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
.news-item img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 8px;
  margin-bottom: 15px;
}
.news-item p {
  font-size: 12px;
  font-weight: bold;
  line-height: 1.4;
  text-transform: uppercase;
}
.slide-btn {
  background: none;
  border: none;
  font-size: 30px;
  cursor: pointer;
  color: #333;
}

/* --- KODE RESPONSIF UNTUK HP --- */
@media (max-width: 768px) {
  .news-grid {
    grid-template-columns: 1fr; /* Menjadi 1 kolom ke bawah */
  }
  .slide-btn { display: none; } /* Sembunyikan panah di HP agar bisa di-scroll manual */
}
</style>