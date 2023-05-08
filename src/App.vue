<script setup lang="ts">
import { initFlowbite } from 'flowbite'
import { onMounted } from 'vue'
import HeaderSection from './sections/HeaderSection.vue'
import TimelineSection from './sections/TimelineSection.vue'
import GallerySection from './sections/GallerySection.vue'
import PricingSection from './sections/PricingSection.vue'
import ContactSection from './sections/ContactSection.vue'
import FooterSection from './sections/FooterSection.vue'

onMounted(() => {
  initFlowbite()
})
</script>

<template>
  <HeaderSection />
  <TimelineSection />
  <GallerySection />
  <PricingSection />
  <ContactSection />
  <FooterSection />
</template>

<style lang="scss" scoped></style>
