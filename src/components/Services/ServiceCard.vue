<template>
  <v-card class="service-card">
    <v-row>
      <v-col cols="4">
        <div class="image-wrapper">
          <v-img :src="service.image" :alt="service.title" class="service-image"></v-img>
        </div>
      </v-col>
      <v-col cols="8">
        <v-card-title>{{ service.title }}</v-card-title>
        <v-card-text>{{ service.description }}</v-card-text>
      </v-col>
    </v-row>
  </v-card>
</template>

<script setup>
import { defineProps } from "vue";

const props = defineProps({
  service: {
    type: Object,
    required: true
  }
});
</script>

<style scoped>
.service-card {
  padding: 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  display: flex;
  height: 180px;
}

.image-wrapper {
  background-color: #fff;
  width: 120px;
  height: 120px;
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