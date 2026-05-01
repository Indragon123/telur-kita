<template>
  <section class="why-choose container">
    <h2 class="section-title">Why Choose <span class="bg-red-light">TelurKita ?</span></h2>
    
    <div class="features-grid">
      <div class="feature-card">
        <i class="fa-regular fa-calendar-days icon-red"></i>
        <h3>Pengalaman 10+ Tahun</h3>
        <p>Dengan pengalaman lebih dari 10 tahun, kami memahami industri dari pemeliharaan hingga pemasaran.</p>
      </div>
      <div class="feature-card">
        <i class="fa-solid fa-users icon-red"></i>
        <h3>Kemitraan Transparan</h3>
        <p>Sistem kemitraan jelas, legal, dan saling menguntungkan dengan pendampingan berkelanjutan.</p>
      </div>
      <div class="feature-card">
        <i class="fa-solid fa-hand-holding-dollar icon-red"></i>
        <h3>Harga Kompetitif</h3>
        <p>Menawarkan kualitas terbaik dengan harga yang tetap terjangkau bagi semua kalangan.</p>
      </div>
      <div class="feature-card">
        <i class="fa-solid fa-check-to-slot icon-red"></i>
        <h3>Produk Berkualitas</h3>
        <p>Telur Omega-3 sehat, higienis, dan memenuhi standar mutu untuk konsumen dan mitra.</p>
      </div>
      <div class="feature-card">
        <i class="fa-solid fa-headset icon-red"></i>
        <h3>Dukungan Teknis Lengkap</h3>
        <p>Kami menyediakan edukasi dan pembinaan tentang cara beternak, perawatan kandang.</p>
      </div>
      <div class="feature-card">
        <i class="fa-solid fa-gears icon-red"></i>
        <h3>Inovasi Berkelanjutan</h3>
        <p>Selalu menghadirkan solusi baru dalam peternakan untuk meningkatkan produktivitas.</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.why-choose {
  text-align: center;
  padding: 60px 20px;
}
.bg-red-light {
  background-color: #ffebee;
  color: #c62828;
  padding: 5px 15px;
  border-radius: 5px;
}
.features-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 40px;
}
.feature-card { text-align: center; padding: 20px; }
.icon-red {
  font-size: 45px;
  color: #c62828;
  margin-bottom: 20px;
}
.feature-card h3 {
  font-size: 18px;
  margin-bottom: 10px;
  color: #333;
}
.feature-card p {
  font-size: 12px;
  color: #666;
  line-height: 1.5;
}
/* --- KODE RESPONSIF UNTUK HP --- */
@media (max-width: 768px) {
  .section-title { font-size: 24px; margin-bottom: 30px; }
  .features-grid {
    grid-template-columns: 1fr; /* Mengubah 3 kolom menjadi 1 baris vertikal */
    gap: 30px;
  }
}
</style>