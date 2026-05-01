<template>
  <nav class="navbar">
    <div class="container nav-content">
      <img src="@/assets/images/logo.png" alt="TelurKita Logo" class="logo" />
      <ul class="nav-links">
        <li><a href="#">BERANDA</a></li>
        <li><a href="#">KEMITRAAN AYAM</a></li>
        <li><a href="#">GERAI TELURKITA</a></li>
        <li><a href="#">KANTOR PELAYANAN</a></li>
        <li><a href="#">SALES AREA</a></li>
        <li><a href="#">TENTANG KAMI</a></li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
.navbar {
  background-color: #ef5350; /* Merah cerah */
  padding: 15px 0;
}
.nav-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo { height: 40px; }
.nav-links {
  display: flex;
  list-style: none;
  gap: 20px;
}
.nav-links a {
  color: white;
  text-decoration: none;
  font-size: 14px;
  font-weight: 600;
  text-transform: uppercase;
}
/* --- KODE RESPONSIF UNTUK HP --- */
@media (max-width: 768px) {
  .nav-content {
    flex-direction: column;
    gap: 15px;
  }
  .nav-links {
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
  }
  .nav-links a { font-size: 12px; }
}
</style>