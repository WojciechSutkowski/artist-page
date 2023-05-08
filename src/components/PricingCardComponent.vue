<script setup lang="ts">
const props = defineProps<{
  type: string
  minPrice: string
}>()
</script>

<template>
  <div class="w-full max-w-sm p-4 bg-white border border-[var(--palette-lightest)] rounded-lg shadow sm:p-8">
        <h5 class="mb-4 text-xl font-medium text-[var(--palette-light)]">{{props.type}} painting</h5>
        <span class="text-3xl text-[var(--palette-dark)] font-semibold">from ${{ props.minPrice }}</span>
    </div>
</template>