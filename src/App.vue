<script setup>
import Navbar from "./components/nav-bar.vue";
import heroSection from "./components/hero-section.vue";
import PartnerSection from "./components/partner-section.vue";
import Operations from "./components/operations-section.vue";
import About from "./components/about-section.vue";
import ServiceDeliverySection from "./components/service-delivery-section.vue";
import TrialSection from "./components/trial-section.vue";
import Footer from "./components/footer.vue";
</script>

<template>
  <div class="">
    <Navbar></Navbar>
    <heroSection></heroSection>
    <PartnerSection></PartnerSection>
    <Operations></Operations>
    <About></About>
    <ServiceDeliverySection></ServiceDeliverySection>
    <TrialSection></TrialSection>
    <Footer></Footer>
  </div>
</template>

<style scoped></style>
