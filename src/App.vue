<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HeroComp from './components/HeroComp.vue';
import NavComp from './components/NavComp.vue';
import Portfolio from './components/PortfolioComp.vue';
import Portfolio2 from './components/PortfolioComp2.vue';
import About from './components/AboutComp.vue';
import Contact from './components/ContactComp.vue';
import Footer from './components/FooterComp.vue';

</script>

<template>
<NavComp/>
<HeroComp/>
<Portfolio/>
<About/>
<Contact/>
<Footer/>


</template>

<style scoped>


</style>
