<template>
    <section class="section-2">
            <span class="title">Hello there, <br> i'm John DOE</span>
            <div class="bloc-1">
                <span class="Designer">Designer</span>
                <span>&</span>
                <span class="Developer">Developer front-end</span>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias dolorem unde quas laborum illo ratione alias quaerat aspernatur aliquid non iusto, quidem ipsa voluptatum placeat quisquam!
            </p>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>

.section-2 {
    margin-top: 10rem;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    span {
        font-family: "Source Serif 4", serif;
        padding: 0.4em 0.8em;
        font-size: 1.5em;
    }
    .Designer {
        color: rgb(41 100 103);
        background-color: rgb(237 246 247);
        border-left: 2px solid;
        border-color: rgb(95 182 186);
    }
    .Developer {
        color: rgb(129 60 17);
        background-color: rgb(251 240 234);
        border-left: 2px solid;
        border-color: rgb(232 164 123);
    }
    .title{
        font-family: "Raleway", sans-serif;
        font-optical-sizing: auto;
        font-weight: 200;
        font-style: normal;
        font-size: 2em;
        margin-bottom: 0.5em;
    }
    .bloc-1 {
        margin-bottom: 2em;
    }
    p {
        font-family: "Source Serif 4", serif;
        text-align: center;
        width: 40%;
    }
}

</style>