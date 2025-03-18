<template>
  <v-app>
    <Header></Header>

    <BannerHome></BannerHome>

    <AboutUs></AboutUs>
    
    <Services></Services>

    <Gallery></Gallery>

    <ContactUs></ContactUs>

    <WhatsappButton></WhatsappButton>
  </v-app>
</template>

<script setup>
import Header from './Header.vue';
import BannerHome from './BannerHome.vue';
import AboutUs from './AboutUs.vue';
import Services from './Services/Services.vue';
import Gallery from './Gallery/Gallery.vue';
import ContactUs from './ContactUs.vue';
import WhatsappButton from './WhatsappButton.vue';

</script>

<style scoped>

</style>