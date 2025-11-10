<script setup>
import 'vue3-carousel/carousel.css'
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel'

// import your images
import nature1 from '@/images/nature1.jpg'
import nature2 from '@/images/nature2.jpg'
import nature3 from '@/images/nature3.jpg'
import nature4 from '@/images/nature4.jpg'
import nature5 from '@/images/nature5.jpg'
import nature6 from '@/images/nature6.jpg'
import nature7 from '@/images/nature7.jpg'
import nature8 from '@/images/nature8.jpg'
import pic9 from '@/images/pic9.jpg'
import pic10 from '@/images/pic10.jpg'

const images = [
  { id: 1, url: nature1 },
  { id: 2, url: nature2 },
  { id: 3, url: nature3 },
  { id: 4, url: nature4 },
  { id: 5, url: nature5 },
  { id: 6, url: nature6 },
  { id: 7, url: nature7 },
  { id: 8, url: nature8 },
  { id: 9, url: pic9 },
  { id: 10, url: pic10 },
]

const carouselConfig = {
  itemsToShow: 1,
  wrapAround: true,
  autoplay: 2000,
  pauseAutoplayOnHover: true,
  slideEffects: 'fade',
}
</script>

<template>
  <div class="flex justify-center py-10">
    <Carousel v-bind="carouselConfig" class="max-w-5xl w-full">
      <Slide v-for="image in images" :key="image.id">
        <div class="flex justify-center">
          <img
            :src="image.url"
            alt="carousel-image"
            class="rounded-xl object-cover w-[400px] h-[400px]"
          />
        </div>
      </Slide>

      <template #addons>
        <Navigation />
        <Pagination />
      </template>
    </Carousel>
  </div>
</template>

<style>
/* Optional: adjust navigation colors */
.carousel__prev, .carousel__next {
  color: black;
}
.carousel__next:hover {
  background: white;
  border-radius: 5px;
}
.carousel__prev:hover {
  background: white;
  border-radius: 5px;
}
</style>
