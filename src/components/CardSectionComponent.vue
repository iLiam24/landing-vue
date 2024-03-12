

<template>
    
    <section class="section-5">
        <div class="classic-container">
            <CardLandingComponent/>
            <CardLandingComponent/>
            <CardLandingComponent/>
            <CardLandingComponent/>
        </div>
    </section>
</template>

<script lang="ts" setup>
import CardLandingComponent from './CardLandingComponent.vue';
</script>

<style lang="scss" scoped>
.section-5 {
    margin: 200px 0px;
    .classic-container {
        display: flex;
        flex-wrap: wrap;
        }
    }
</style>