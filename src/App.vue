<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import History from './components/History.vue'
import WhyChoose from './components/WhyChoose.vue'
import News from './components/News.vue'
import Partnership from './components/Partnership.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div class="app-container">
    <Navbar />
    <Hero />
    <History />
    <WhyChoose />
    <News />
    <Partnership />
    <Footer />
  </div>
</template>

<style>
/* CSS Global / Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
body {
  background-color: #ffffff;
  color: #333;
}
.app-container {
  overflow-x: hidden;
}
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}
.section-title {
  font-size: 32px;
  text-align: center;
  margin-bottom: 50px;
}
</style>