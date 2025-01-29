<template>
  <v-container class="about-us" fluid id="about">
    <v-row align="center" justify="center">
      <v-col cols="12" md="8" lg="6">
        <h2 class="about-us-title">Sobre Nosotros</h2>
        <p class="about-us-text">
          En Working Group nos dedicamos a hacer realidad tu sueño, ofreciendo diseño, trabajos de calidad y cuidando cada detalle.
        </p>
        <p class="about-us-text">
          Tenemos más de 32 años de experiencia, hacemos realidad tus ideas y te garantizamos un resultado que cumpla con lo que necesitás.
        </p>
        <p class="about-us-text">
          Estamos ubicados en Zona Norte. 
        </p>

        <p class="about-us-text">
        ¡Hagamos tu proyecto juntos!
        </p>
      </v-col>
      <v-col cols="12" md="4" lg="3">
        <v-img
          src="@/assets/fotoCasa.jpeg"
          alt="Sobre Nosotros"
          class="about-us-image"
          contain
        ></v-img>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
</script>

<style scoped>
.about-us {
  padding: 40px 20px;
  background-color: #f5f5f5;
  color: #333;
}

.about-us-title {
  font-size: 2rem;
  font-weight: bold;
  text-align: center;
  margin-bottom: 20px;
  color: #1976d2;
}

.about-us-text {
  font-size: 1.2rem;
  line-height: 1.6;
  margin-bottom: 20px;
  max-width: 600px; /* Limita el ancho del texto */
  margin-left: auto;
  margin-right: auto;
}

.about-us-image {
  border-radius: 10px;
  width: 100%;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}
</style>
