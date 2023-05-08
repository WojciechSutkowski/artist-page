<script setup lang="ts">
import PricingCard from '../components/PricingCardComponent.vue'
</script>

<template>
    <section id="pricing" class="relative pt-16 w-full mt-8">
    <h2
      class="mb-4 text-4xl tracking-tight font-extrabold text-center text-[var(--palette-dark)]"
    >
      Pricing
    </h2>
    <div
      class="flex flex-col items-center gap-4 md:flex-row md:items-center md:justify-between"
    >
      <PricingCard type="Acrylic" minPrice="49"/>
      <PricingCard type="Watercolor" minPrice="79"/>
      <PricingCard type="Oil" minPrice="99"/>
    </div>
  </section>
</template>