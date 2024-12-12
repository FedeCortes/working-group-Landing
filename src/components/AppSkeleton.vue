<template>
  <v-app>
    <!-- Header -->
    <Header></Header>

    <!-- Banner -->
    <BannerHome></BannerHome>

    <!-- About us -->
    <AboutUs></AboutUs>
    
    <!-- Services -->
    <Services></Services>

    <!-- Gallery -->
    <Gallery></Gallery>

    <!-- Contact us -->
    <ContactUs></ContactUs>

    <!-- Whatsapp button -->
    <WhatsappButton></WhatsappButton>
  </v-app>
</template>

<script setup>
import Header from './Header.vue';
import BannerHome from './BannerHome.vue';
import AboutUs from './AboutUs.vue';
import Services from './Services.vue';
import ContactUs from './ContactUs.vue';
import Gallery from './Gallery.vue';
import WhatsappButton from './WhatsappButton.vue';

</script>

<style scoped>

</style>