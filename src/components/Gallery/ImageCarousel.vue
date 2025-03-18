<template>
  <v-carousel show-arrows-on-hover color="white">
    <v-carousel-item v-for="(image, index) in resolvedImages" :key="index">
      <v-img :src="image.src" :alt="image.alt" class="carousel-image"></v-img>
    </v-carousel-item>
  </v-carousel>
</template>

<script setup>
import { computed } from "vue";

const props = defineProps({
  images: Array
});

const resolvedImages = computed(() => {
  return props.images.map(image => {
    return {
      src: image.src,
      alt: image.alt
    };
  });
});
</script>

<style scoped>
.carousel-image {
  width: 100%;
  height: 400px;
  object-fit: cover;
  border-radius: 10px;
  cursor: pointer;
  transition: transform 0.3s ease-in-out;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.carousel-image:hover {
  transform: scale(1.05);
}
</style>
