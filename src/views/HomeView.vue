<script setup>
import Navbar from '@/components/landing-page/Navbar.vue'
import HeroSlider from '@/components/landing-page/HeroSlider.vue'
import HistorySection from '@/components/landing-page/HistorySection.vue'
import WhyChooseSection from '@/components/landing-page/WhyChooseSection.vue'
import LatestNewsSection from '@/components/landing-page/LatestNewsSection.vue'
import PartnershipSlider from '@/components/landing-page/PartnershipSlider.vue'
import Footer from '@/components/landing-page/Footer.vue'
</script>

<template>
  <div class="landing-page">
    <Navbar />
    <HeroSlider />
    <HistorySection />
    <WhyChooseSection />
    <LatestNewsSection />
    <PartnershipSlider />
    <Footer />
  </div>
</template>

<style scoped>
/* Tambahkan reset CSS atau framework CSS di main.js */
</style>