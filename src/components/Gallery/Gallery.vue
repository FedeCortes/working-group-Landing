<template>
  <v-container id="gallery">
    <h2 class="gallery-title">Galería</h2>
    <p class="gallery-subtitle">Explora algunos de nuestros proyectos destacados:</p>
    
    <ImageCarousel :images="galleryImages" />
  </v-container>
</template>

<script setup>
import ImageCarousel from "./ImageCarousel.vue";

const galleryImages = [
  { src: "/images/proyecto3.jpeg", alt: "Proyecto 3" },
  { src: "/images/proyecto2.jpeg", alt: "Proyecto 2" },
  { src: "/images/fotoCasa.jpeg", alt: "Proyecto casa" },
  { src: "/images/gruas.jpeg", alt: "Proyecto gruas" },
  { src: "/images/carpinteria.jpeg", alt: "Proyecto carpinteria" },
  { src: "/images/proyecto1.jpg", alt: "Proyecto 1" },
  { src: "/images/proyecto4.jpeg", alt: "Proyecto 4" },
  { src: "/images/proyecto5.jpeg", alt: "Proyecto 5" }
];
</script>

<style scoped>
.gallery-title {
  font-size: 2rem;
  font-weight: bold;
  text-align: center;
  margin-bottom: 10px;
  color: #1976d2;
}

.gallery-subtitle {
  font-size: 1.2rem;
  text-align: center;
  margin-bottom: 20px;
  color: white;
}
</style>
