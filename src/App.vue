<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HeaderComponent from './components/HeaderComponent.vue';
import HeroComponent from './components/HeroComponent.vue';
import AboutComponent from './components/AboutComponent.vue';
import ProjetSectionComponent from './components/ProjetSectionComponent.vue';
import SimplifySectionComponent from './components/SimplifySectionComponent.vue';
import CardSectionComponent from './components/CardSectionComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import ButtonComponent from './components/ButtonComponent.vue';
</script>

<template>
<HeaderComponent/>
<HeroComponent/>
<AboutComponent/>
<ProjetSectionComponent/>
<SimplifySectionComponent/>
<CardSectionComponent/>
<FooterComponent/>
<!-- <ButtonComponent label="Bouton" color="red"/>
<ButtonComponent label="OUA" color="blue"/> -->


</template>

<style scoped>


</style>
