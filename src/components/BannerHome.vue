<template>
    <v-container class="banner-container" fluid>
      <v-row class="banner-content" align="center" justify="center">
        <div class="banner-text">
          <h1>Working Group</h1>
          <h2>Especialistas en Construcción y Diseño</h2>
          <h3>Estamos en Zona Norte</h3>
        </div>
      </v-row>
    </v-container>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  .banner-container {
    padding: 0;
    margin: 0;
    width: 100%; 
    height: 100vh; 
    background: url('/images/proyecto5.jpeg') no-repeat center center;
    background-size: cover; 
    
  }
  
  .banner-content {
    height: 100%;
    color: #fff;
    text-align: center;
    background: rgba(0, 0, 0, 0.5);
  }
  
  .banner-text h1 {
    font-size: 3rem;
    margin-bottom: 0.5rem;
  }
  
  .banner-text h2 {
    font-size: 1.5rem;
    font-weight: 300;
  }

  .banner-text h3 {
  font-size: 1.2rem;
  margin-top: 1rem;
  font-weight: 400;
  }
  </style>
  