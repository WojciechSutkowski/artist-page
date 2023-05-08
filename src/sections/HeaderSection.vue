<script setup lang="ts">
import AboutMeSection from '../sections/AboutMeSection.vue'
import NavBarComponent from '../components/NavBarComponent.vue'
</script>

<template>
  <header
    id="home"
    class="h-screen bg-cover bg-top bg-no-repeat bg-[url('./assets/artist-img.jpg')] bg-amber-900 bg-blend-multiply flex flex-col justify-end"
  >
    <NavBarComponent />
    <AboutMeSection />
  </header>
</template>