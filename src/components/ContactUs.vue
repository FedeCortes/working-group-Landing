<template>
    <v-container class="contact-container" fluid  id="contact">
      <h2 class="contact-title">Contacto</h2>
      <p class="contact-subtitle">
        Estamos disponibles para ayudarte. Contáctanos a través de los siguientes medios:
      </p>
      <v-row justify="center" align="center">
        <v-col cols="12" sm="6" md="3" class="contact-item">
          <v-card class="contact-card">
            <v-card-title>
              <v-icon class="contact-icon" color="green">mdi-whatsapp</v-icon>
              WhatsApp
            </v-card-title>
            <v-card-text>
              <a
                href="https://wa.link/hq22r9"
                target="_blank"
                class="contact-link"
              >
                Lidia ( 11 2492-0595 )
              </a>
              /
              <a
                href="https://wa.link/mio7s9"
                target="_blank"
                class="contact-link"
              >
                Hugo ( 11 2473-9147 )
              </a>
            </v-card-text>
          </v-card>
        </v-col>
  
        <v-col cols="12" sm="6" md="3" class="contact-item">
          <v-card class="contact-card">
            <v-card-title>
              <v-icon class="contact-icon" color="purple">mdi-instagram</v-icon>
              Instagram
            </v-card-title>
            <v-card-text>
              <a
                href="https://www.instagram.com/workinggroup23/"
                target="_blank"
                class="contact-link"
              >
                Visita nuestro perfil
              </a>
            </v-card-text>
          </v-card>
        </v-col>
  
        <v-col cols="12" sm="6" md="3" class="contact-item">
          <v-card class="contact-card">
            <v-card-title>
              <v-icon class="contact-icon" color="blue">mdi-email</v-icon>
              Correo Electrónico
            </v-card-title>
            <v-card-text>
              <a
                href="mailto:workinggroup.construcciones@gmail.com"
                class="contact-link"
              >
              workinggroup.construcciones@gmail.com
              </a>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  .contact-container {
    padding: 40px 20px;
    background-color: #f5f5f5;
  }
  
  .contact-title {
    font-size: 2rem;
    font-weight: bold;
    text-align: center;
    margin-bottom: 10px;
    color: #1976d2;
  }
  
  .contact-subtitle {
    font-size: 1.2rem;
    text-align: center;
    margin-bottom: 40px;
    color: #555;
  }
  
  .contact-card {
    padding: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    text-align: center;
  }
  
  .contact-icon {
    font-size: 2rem;
    margin-right: 10px;
  }
  
  .contact-link {
    font-size: 1rem;
    font-weight: 500;
    color: #1976d2;
    text-decoration: none;
  }
  
  .contact-link:hover {
    text-decoration: underline;
  }
  </style>