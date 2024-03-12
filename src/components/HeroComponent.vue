<template>
    <section class="section-1">
        <div class="classic-container">
            <h2>Explore <br>
                every<br>
                <span>great ideas</span></h2>
            <div class="hero-section">
                <img src="../assets/img/pc.jpg" alt="">
            </div>
        </div>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
.hero-section {
    position: relative;
    background: rgba(58, 124, 128);
    height: 25rem;
    overflow: hidden;
    img {
        opacity: 10%;
        background-repeat: no-repeat;
        background-size:contain; 
        height: auto;
        width: 100%;
    }
}

.section-1 {
    h2 {
    z-index: 2;
    position: absolute;
    margin-left: 5em;
    top: 6em;
    font-family: "Source Serif 4", serif;
    font-size: 3.5em;
    color: white;
    span {
        display: block;
        color: black;
        }
    }
}
</style>