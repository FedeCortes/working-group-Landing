<template>
    <v-tooltip bottom>
      <template #activator="{ props }">
        <v-btn
          v-bind="props"
          fab
          class="whatsapp-button"
          color="green"
          href="https://wa.link/hq22r9"
          target="_blank"
        >
          <v-icon size="36">mdi-whatsapp</v-icon>
        </v-btn>
      </template>
      <span>Contactanos por WhatsApp</span>
    </v-tooltip>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  .whatsapp-button {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    position: fixed;
    bottom: 40px;
    right: 25px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    z-index: 1000;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .whatsapp-button:hover {
    transform: scale(1.1); 
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3); 
  }
  </style>