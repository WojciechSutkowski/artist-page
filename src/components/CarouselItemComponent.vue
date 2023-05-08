<script setup lang="ts">
const props = defineProps<{
  path: string
}>()
</script>

<template>
  <div class="hidden duration-700 ease-in-out">
    <img
      :src="props.path"
      class="absolute block max-h-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
      alt=""
    />
  </div>
</template>