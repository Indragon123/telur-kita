<template>
  <section class="history container">
    <div class="history-images">
      <img src="@/assets/images/history-1.png" alt="History 1" class="img-left" />
      <div class="img-right-container">
        <img src="@/assets/images/history-2.png" alt="History 2" class="img-right" />
        <div class="badge-mitra">Mitra More Than 850+</div>
      </div>
    </div>
    
    <div class="history-text">
      <h2><span class="red-text">HISTORY</span> of Our Journey</h2>
      <p class="bold-text">TelurKita adalah Brand Peternakan Ayam Petelur dengan lebih dari 100 Peternak Binaan di Seluruh Indonesia. Selain ternak sendiri, TelurKita juga membuka Peluang Kemitraan Titip Ternak Ayam Petelur yang semuanya dikelola oleh TelurKita sehingga Pemilik Ternak cukup Terima Bagi Hasil Panennya Saja.</p>
      <p class="bold-text mt-4">Sejak 2015, TelurKita selalu hadir dalam Enthusiasm Peternakan Ayam Petelur di Indonesia.</p>
      
      <div class="checklists">
        <ul>
          <li><i class="fa-solid fa-check"></i> Staf Profesional</li>
          <li><i class="fa-solid fa-check"></i> Dukungan Penuh</li>
        </ul>
        <ul>
          <li><i class="fa-solid fa-check"></i> Harga Murah</li>
          <li><i class="fa-solid fa-check"></i> Terpercaya</li>
        </ul>
      </div>
    </div>
  </section>
</template>

<style scoped>
.history {
  display: flex;
  gap: 50px;
  padding: 80px 20px;
  align-items: center;
}
.history-images {
  display: flex;
  gap: 15px;
  flex: 1;
}
.img-left, .img-right {
  width: 200px;
  height: auto;
  border-radius: 10px;
  object-fit: cover;
}
.img-right-container { position: relative; }
.badge-mitra {
  background-color: #c62828;
  color: white;
  text-align: center;
  padding: 10px;
  font-weight: bold;
  border-radius: 0 0 10px 10px;
}
.history-text { flex: 1; }
.history-text h2 {
  font-size: 32px;
  margin-bottom: 20px;
  font-weight: normal;
}
.red-text { color: #c62828; font-weight: bold; }
.bold-text { font-weight: 600; line-height: 1.6; }
.mt-4 { margin-top: 15px; }
.checklists {
  display: flex;
  gap: 40px;
  margin-top: 20px;
  color: #c62828;
  font-weight: bold;
}
.checklists ul { list-style: none; }
.checklists li { margin-bottom: 10px; }
.checklists i { margin-right: 10px; }

/* --- KODE RESPONSIF UNTUK HP --- */
@media (max-width: 768px) {
  .history {
    flex-direction: column;
    padding: 40px 20px;
  }
  .history-images {
    flex-direction: column;
    align-items: center;
  }
  .img-left, .img-right { width: 100%; max-width: 300px; }
  .history-text h2 { font-size: 24px; text-align: center; }
  .checklists {
    flex-direction: column;
    gap: 10px;
  }
}
</style>