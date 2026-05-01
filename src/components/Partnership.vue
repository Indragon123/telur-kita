<template>
  <section class="partnership container">
    <div class="partnership-wrapper">
      <button class="slide-btn"><i class="fa-solid fa-chevron-left"></i></button>
      
      <div class="partnership-content">
        <div class="image-box">
          <div class="bg-red-box"></div>
          <img src="@/assets/images/partnership-pic.jpg" alt="Bang Ardi" class="partner-img" />
        </div>
        <div class="text-box">
          <h3>KEMITRAAN YANG TRANSPARAN</h3>
          <p>Jangan khawatir untuk bergabung dengan TelurKita karena semua sistem kemitraan jelas, legal, dan transparan. Tidak usah khawatir soal kepastian hasil karena semuanya sudah terstruktur dengan baik.</p>
          <span class="author">~ Bang Ardi</span>
        </div>
      </div>

      <button class="slide-btn"><i class="fa-solid fa-chevron-right"></i></button>
    </div>
  </section>
</template>

<style scoped>
.partnership { padding: 60px 20px; }
.partnership-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 40px;
}
.partnership-content {
  display: flex;
  align-items: center;
  gap: 40px;
  max-width: 700px;
}
.image-box { position: relative; }
.bg-red-box {
  background-color: #c62828;
  width: 180px;
  height: 180px;
  position: absolute;
  top: -10px;
  left: -10px;
  z-index: 1;
}
.partner-img {
  width: 180px;
  height: 180px;
  object-fit: cover;
  position: relative;
  z-index: 2;
  border: 4px solid white;
}
.text-box h3 {
  font-size: 20px;
  margin-bottom: 10px;
}
.text-box p {
  font-size: 14px;
  line-height: 1.6;
  margin-bottom: 10px;
  color: #444;
}
.author {
  font-weight: bold;
  font-style: italic;
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
  .partnership-content {
    flex-direction: column;
    text-align: center;
    gap: 20px;
  }
  .bg-red-box { display: none; } /* Matikan kotak merah belakang agar rapi di HP */
  .partner-img { border: 4px solid #c62828; margin: 0 auto; }
  .slide-btn { display: none; }
}
</style>