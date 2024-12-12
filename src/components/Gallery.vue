<template>
  <v-container class="gallery-container" fluid id="gallery">
    <h2 class="gallery-title">Galería</h2>
    <p class="gallery-subtitle">Explora algunos de nuestros proyectos destacados:</p>
    
    <!-- Carousel -->
    <v-carousel show-arrows-on-hover>
      <!-- Imagen 1 -->
      <v-carousel-item>
        <v-img
          src="@/assets/proyecto3.jpeg"
          alt="Proyecto 3"
          class="carousel-image"
        ></v-img>
      </v-carousel-item>

      <!-- Imagen 2 -->
      <v-carousel-item>
        <v-img
          src="@/assets/proyecto2.jpeg"
          alt="Proyecto 2"
          class="carousel-image"
        ></v-img>
      </v-carousel-item>

      <v-carousel-item>
        <v-img
          src="@/assets/fotoCasa.jpeg"
          alt="Proyecto casa"
          class="carousel-image"
        ></v-img>
      </v-carousel-item>

      <v-carousel-item>
        <v-img
          src="@/assets/gruas.jpeg"
          alt="Proyecto gruas"
          class="carousel-image"
        ></v-img>
      </v-carousel-item>

      <v-carousel-item>
        <v-img
          src="@/assets/carpinteria.jpeg"
          alt="Proyecto carpinteria"
          class="carousel-image"
        ></v-img>
      </v-carousel-item>

      <!-- Imagen 3 -->
      <v-carousel-item>
        <v-img
          src="@/assets/proyecto1.jpg"
          alt="Proyecto 1"
          class="carousel-image"
        ></v-img>
      </v-carousel-item>

      <!-- Imagen 4 -->
      <v-carousel-item>
        <v-img
          src="@/assets/proyecto4.jpeg"
          alt="Proyecto 4"
          class="carousel-image"
        ></v-img>
      </v-carousel-item>

      <!-- Imagen 5 -->
      <v-carousel-item>
        <v-img
          src="@/assets/proyecto5.jpeg"
          alt="Proyecto 5"
          class="carousel-image"
        ></v-img>
      </v-carousel-item>
    </v-carousel>
  </v-container>
</template>

<script setup>
/* En este caso, no necesitas el array `images` ni lógica dinámica. */
</script>

<style scoped>
.gallery-container {
  padding: 40px 0;
  background-color: #fff;
}

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
  color: #555;
}

.carousel-image {
  width: 100%;
  height: 400px;
  object-fit: cover;
  border-radius: 10px;
  cursor: pointer;
  transition: transform 0.3s ease-in-out;
}

.carousel-image:hover {
  transform: scale(1.05); /* Efecto de zoom */
}

.dialog-image {
  width: 100%;
  height: auto;
  border-radius: 10px;
}
</style>
