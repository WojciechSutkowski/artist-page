<script setup lang="ts">
import CarouselItem from '../components/CarouselItemComponent.vue'
import painting1 from '../assets/painting-1.jpg'
import painting2 from '../assets/painting-2.jpg'
import painting3 from '../assets/painting-3.jpg'
import painting4 from '../assets/painting-4.jpg'
</script>

<template>
  <section
    id="gallery"
    class="relative pt-16 w-full mt-8 md:h-screen"
    data-carousel="slide"
  >
    <h2
      class="mb-4 text-4xl tracking-tight font-extrabold text-center text-[var(--palette-dark)]"
    >
      Gallery
    </h2>
    <!-- Carousel wrapper -->
    <div class="relative h-56 overflow-hidden rounded-lg md:h-5/6">
      <!-- Item 1 -->
      <CarouselItem :path="painting1" data-carousel-item="active" />
      <CarouselItem :path="painting2" data-carousel-item />
      <CarouselItem :path="painting3" data-carousel-item />
      <CarouselItem :path="painting4" data-carousel-item />
    </div>
    <div class="flex justify-center items-center pt-4">
      <button
        type="button"
        class="flex justify-center items-center mr-4 h-full cursor-pointer group focus:outline-none"
        data-carousel-prev
      >
        <span
          class="text-[var(--palette-light)] hover:text-[var(--palette-dark)] group-focus:text-[var(--palette-dark)]"
        >
          <svg
            aria-hidden="true"
            class="w-6 h-6"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M7.707 14.707a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 1.414L5.414 9H17a1 1 0 110 2H5.414l2.293 2.293a1 1 0 010 1.414z"
              clip-rule="evenodd"
            ></path>
          </svg>
          <span class="sr-only">Previous</span>
        </span>
      </button>
      <button
        type="button"
        class="flex justify-center items-center h-full cursor-pointer group focus:outline-none"
        data-carousel-next
      >
        <span
          class="text-[var(--palette-light)] hover:text-[var(--palette-dark)] group-focus:text-[var(--palette-dark)]"
        >
          <svg
            aria-hidden="true"
            class="w-6 h-6"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
              clip-rule="evenodd"
            ></path>
          </svg>
          <span class="sr-only">Next</span>
        </span>
      </button>
    </div>
  </section>
</template>