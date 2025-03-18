<template>
  <v-container class="services-container" fluid id="services">
    <h2 class="services-title">Nuestros Servicios</h2>
    <p class="services-subtitle">
      Tenemos todo lo que necesitás para tus proyectos, ya sea construir, refaccionar o diseñar.
    </p>
    <v-row dense>
      <v-col v-for="(service, index) in services" :key="index" cols="12" md="4" class="service-item">
        <ServiceCard :service="service" />
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
import ServiceCard from "./ServiceCard.vue";

const services = [
  {
    title: "Construcción de Puente Grúas",
    description: "Construcción de puentes grúa en todo tipo de material estructural y armado de planos y factores de potencia.",
    image: "/images/gruas.jpeg" 
  },
  {
    title: "Herrería y Aluminio",
    description: "Soldaduras, escaleras, techos traslúcidos, balcones, barandas y proyectos especiales.",
    image: "/images/proyecto1.jpg"
  },
  {
    title: "Carpintería y Mobiliarios",
    description: "Fabricación de muebles, pérgolas, decks y arquitectura interior.",
    image: "/images/carpinteria.jpeg"
  },
  {
    title: "Electricidad",
    description: "Instalación de sistemas eléctricos, cableado de redes, CCTV y más.",
    image: "/images/electricidad.jpeg"
  },
  {
    title: "Plomería y Gas",
    description: "Remoción e instalación de cañerías de agua y gas.",
    image: "/images/plomeria.png"
  },
  {
    title: "Techos",
    description: "Construcción y reparación de techos en madera, metálicos, losas, zinguería e impermeabilización.",
    image: "/images/techos.jpeg"
  },
  {
    title: "Piscinas",
    description: "Construcción, reparación e impermeabilización de piletas, además de instalación de sistemas de filtrado y mantenimiento.",
    image: "/images/proyecto2.jpeg"
  },
  {
    title: "Pisos industriales",
    description: "Diseñamos y construimos pisos industriales de alta resistencia, ideales para fábricas, depósitos y talleres.",
    image: "/images/pisosIndustriales.jpeg"
  },
  {
    title: "Pisos epóxicos",
    description: "Instalamos pisos epóxicos con terminaciones modernas, ideales para hogares, oficinas y comercios.",
    image: "/images/pisosEpoxicos.jpeg"
  }
];

</script>

<style scoped>
.services-container {
  padding: 40px 20px;
  background-color: #f5f5f5;
}

.services-title {
  font-size: 2rem;
  font-weight: bold;
  text-align: center;
  margin-bottom: 10px;
  color: #1976d2;
}

.services-subtitle {
  font-size: 1.2rem;
  text-align: center;
  margin-bottom: 40px;
  color: #555;
}
</style>