<template>
  <v-container class="services-container" fluid id="services">
    <h2 class="services-title">Nuestros Servicios</h2>
    <p class="services-subtitle">
      Tenemos todo lo que necesitás para tus proyectos, ya sea construir, refaccionar o diseñar.
    </p>
    <v-row dense>
      <!-- Construcción -->
      <v-col cols="12" md="4" class="service-item">
        <v-card class="service-card">
          <v-row>
            <v-col cols="4">
              <div class="image-wrapper">
                <v-img
                  src="@/assets/gruas.jpeg"
                  alt="Construcción de Puente Grúas"
                  class="service-image"
                ></v-img>
              </div>
            </v-col>
            <v-col cols="8">
              <v-card-title>Construcción de Puente Grúas</v-card-title>
              <v-card-text>
                Construcción de puentes grúa en todo tipo de material estructural y armado de planos y factores de potencia.
              </v-card-text>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Herrería y Aluminio -->
      <v-col cols="12" md="4" class="service-item">
        <v-card class="service-card">
          <v-row>
            <v-col cols="4">
              <div class="image-wrapper">
                <v-img
                  src="@/assets/proyecto1.jpg"
                  alt="Herrería y Aluminio"
                  class="service-image"
                ></v-img>
              </div>
            </v-col>
            <v-col cols="8">
              <v-card-title>Herrería y Aluminio</v-card-title>
              <v-card-text>
                Soldaduras, escaleras, techos traslúcidos, balcones, barandas y proyectos especiales.
              </v-card-text>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Carpintería y Mobiliarios -->
      <v-col cols="12" md="4" class="service-item">
        <v-card class="service-card">
          <v-row>
            <v-col cols="4">
              <div class="image-wrapper">
                <v-img
                  src="@/assets/carpinteria.jpeg"
                  alt="Carpintería y Mobiliarios"
                  class="service-image"
                ></v-img>
              </div>
            </v-col>
            <v-col cols="8">
              <v-card-title>Carpintería y Mobiliarios</v-card-title>
              <v-card-text>
                Fabricación de muebles, pérgolas, decks y arquitectura interior.
              </v-card-text>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Electricidad -->
      <v-col cols="12" md="4" class="service-item">
        <v-card class="service-card">
          <v-row>
            <v-col cols="4">
              <div class="image-wrapper">
                <v-img
                  src="@/assets/electricidad.jpeg"
                  alt="Electricidad"
                  class="service-image"
                ></v-img>
              </div>
            </v-col>
            <v-col cols="8">
              <v-card-title>Electricidad</v-card-title>
              <v-card-text>
                Instalación de sistemas eléctricos, cableado de redes, CCTV y más.
              </v-card-text>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Plomería y Gas -->
      <v-col cols="12" md="4" class="service-item">
        <v-card class="service-card">
          <v-row>
            <v-col cols="4">
              <div class="image-wrapper">
                <v-img
                  src="@/assets/plomeria.png"
                  alt="Plomería y Gas"
                  class="service-image"
                ></v-img>
              </div>
            </v-col>
            <v-col cols="8">
              <v-card-title>Plomería y Gas</v-card-title>
              <v-card-text>
                Remoción e instalación de cañerías de agua y gas.
              </v-card-text>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Techos -->
      <v-col cols="12" md="4" class="service-item">
        <v-card class="service-card">
          <v-row>
            <v-col cols="4">
              <div class="image-wrapper">
                <v-img
                  src="@/assets/techos.jpeg"
                  alt="Techos"
                  class="service-image"
                ></v-img>
              </div>
            </v-col>
            <v-col cols="8">
              <v-card-title>Techos</v-card-title>
              <v-card-text>
                Construcción y reparación de techos en madera, metálicos, losas, zinguería e impermeabilización.
              </v-card-text>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Piletas -->
      <v-col cols="12" md="4" class="service-item">
        <v-card class="service-card">
          <v-row>
            <v-col cols="4">
              <div class="image-wrapper">
                <v-img
                  src="@/assets/proyecto2.jpeg"
                  alt="Piscinas"
                  class="service-image"
                ></v-img>
              </div>
            </v-col>
            <v-col cols="8">
              <v-card-title>Piscinas</v-card-title>
              <v-card-text>
                Construcción, reparación e impermeabilización de piletas, además de instalación de sistemas de filtrado y mantenimiento.
              </v-card-text>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Pisos industriales -->
      <v-col cols="12" md="4" class="service-item">
        <v-card class="service-card">
          <v-row>
            <v-col cols="4">
              <div class="image-wrapper">
                <v-img
                  src="@/assets/pisosIndustriales.jpeg"
                  alt="Pisos industriales"
                  class="service-image"
                ></v-img>
              </div>
            </v-col>
            <v-col cols="8">
              <v-card-title>Pisos industriales</v-card-title>
              <v-card-text>
                Diseñamos y construimos pisos industriales de alta resistencia, ideales para fábricas, depósitos y talleres.
              </v-card-text>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Pisos epóxicos -->
      <v-col cols="12" md="4" class="service-item">
        <v-card class="service-card">
          <v-row>
            <v-col cols="4">
              <div class="image-wrapper">
                <v-img
                  src="@/assets/pisosEpoxicos.jpeg"
                  alt="Pisos epóxicos"
                  class="service-image"
                ></v-img>
              </div>
            </v-col>
            <v-col cols="8">
              <v-card-title>Pisos epóxicos</v-card-title>
              <v-card-text>
                Instalamos pisos epóxicos con terminaciones modernas, ideales para hogares, oficinas y comercios.
              </v-card-text>
            </v-col>
          </v-row>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
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

.service-card {
  padding: 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  display: flex;
  height: 180px; /* Tamaño uniforme */
}

.image-wrapper {
  background-color: #fff;
  width: 120px; /* Incrementar ancho */
  height: 120px; /* Incrementar altura */
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 8px;
  overflow: hidden;
  margin: auto;
}

.service-image {
  object-fit: cover;
  width: 100%;
  height: 100%;
}

.v-card-title {
  font-size: 1.1rem;
  font-weight: bold;
}

.v-card-text {
  font-size: 0.9rem;
  color: white;
}
</style>
