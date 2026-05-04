<template>
  <div class="bg-[#fffaf3] text-gray-800">
    <Navbar />
    <Hero />
    <Experience />
    <MenuPremium />
    <Gallery />
    <Location />
    <CTA />
    <Footer />
  </div>

  <a 
  href="https://wa.me/521XXXXXXXXXX"
  class="fixed bottom-5 right-5 bg-green-500 text-white px-5 py-3 rounded-full shadow-lg font-bold"
>
  Pedir 🌮
</a>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import Experience from './components/Experience.vue'
import MenuPremium from './components/MenuPremium.vue'
import Gallery from './components/Gallery.vue'
import Location from './components/Location.vue'
import CTA from './components/CTA.vue'
import Footer from './components/Footer.vue'
</script>