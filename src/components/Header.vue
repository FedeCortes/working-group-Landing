<template>
    <v-app-bar app color="primary" dark>
      <v-app-bar-title class="logo">
        Working Group
      </v-app-bar-title>
  
      <v-container
        v-if="!isMobile"
        class="d-none d-md-flex justify-center menu-container"
      >
        <v-btn text href="/" class="menu-item">Inicio</v-btn>
        <v-btn text href="#about" class="menu-item">Nosotros</v-btn>
        <v-btn text href="#services" class="menu-item">Servicios</v-btn>
        <v-btn text href="#gallery" class="menu-item">Galeria</v-btn>
        <v-btn text href="#contact" class="menu-item">Contacto</v-btn>
      </v-container>
  
      <v-menu offset-y v-if="isMobile" class="d-flex d-md-none">
        <template #activator="{ props }">
          <v-btn icon v-bind="props">
            <v-icon>mdi-menu</v-icon>
          </v-btn>
        </template>
        <v-list>
          <v-list-item href="/">
            <v-list-item-title>Inicio</v-list-item-title>
          </v-list-item>
          <v-list-item href="#about">
            <v-list-item-title>Nosotros</v-list-item-title>
          </v-list-item>
          <v-list-item href="#services">
            <v-list-item-title>Servicios</v-list-item-title>
          </v-list-item>
          <v-list-item href="#gallery">
            <v-list-item-title>Galeria</v-list-item-title>
          </v-list-item>
          <v-list-item href="#contact">
            <v-list-item-title>Contacto</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>
  </template>
  
  <script>
  import { useDisplay } from "vuetify";
  
  export default {
    name: "Header",
    setup() {
      const { mdAndDown } = useDisplay(); 
      const isMobile = mdAndDown;
  
      return { isMobile };
    },
  };
  </script>
  
  <style scoped>
  .logo {
    font-size: 1.5rem;
    font-weight: bold;
  }
  
  .menu-container {
    flex-grow: 1;
    display: flex;
  }
  
  .menu-item {
    text-transform: none;
    font-size: 1rem;
    font-weight: 500;
    margin: 0 10px;
  }
  </style>