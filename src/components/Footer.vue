<template>
  <footer class="footer">
    <div class="container footer-content">
      <div class="footer-col">
        <h3>Kantor Pusat</h3>
        <ul>
          <li><i class="fa-solid fa-location-dot"></i> Jl. Jaya Katwang No. 227, Kec. Ngasem, Kab. Kediri, Jawa Timur, 64182</li>
          <li><i class="fa-brands fa-whatsapp"></i> +62-812-522-737-64</li>
          <li><i class="fa-regular fa-envelope"></i> cs@telurkita.com</li>
          <li><i class="fa-brands fa-tiktok"></i> telurkitaofficial</li>
          <li><i class="fa-brands fa-instagram"></i> telurkita.official</li>
        </ul>
      </div>
    </div>
    <div class="copyright">
      <p>© PT. Assasta Sampoerna Indonesia. All Rights Reserved.</p>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background-color: #b71c1c; 
  color: white;
  padding-top: 40px;
  margin-top: 60px;
}
.footer-content {
  display: flex;
  justify-content: center; /* Menengahkan konten karena sekarang hanya 1 kolom */
  padding-bottom: 40px;
}
.footer-col { 
  max-width: 600px; 
}
.footer-col h3 {
  font-size: 24px;
  font-style: italic;
  margin-bottom: 20px;
  border-bottom: 2px solid white;
  display: inline-block;
  padding-bottom: 5px;
}
.footer-col ul { list-style: none; }
.footer-col li {
  margin-bottom: 15px;
  display: flex;
  align-items: flex-start;
  gap: 15px;
  font-weight: 500;
  line-height: 1.4;
}
.footer-col i {
  font-size: 20px;
  width: 20px;
  text-align: center;
  margin-top: 2px;
}
.copyright {
  background-color: #9b111e;
  text-align: center;
  padding: 15px 20px;
  font-weight: bold;
  font-size: 14px;
}

/* --- KODE RESPONSIF UNTUK HP --- */
@media (max-width: 768px) {
  .footer-content {
    justify-content: flex-start; /* Kembali rata kiri di HP agar mudah dibaca */
    padding: 0 20px 30px;
  }
  .footer-col h3 { font-size: 20px; }
  .footer-col li { font-size: 14px; }
}
</style>