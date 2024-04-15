<template>
    <div class="contact">
        <div class="ancre" id="ancre-contact"></div>
        <span id="contact" class="title-c">Contact me.</span>
        </div>
        <div class="bloc-contact">
        <div class="right3">
            <span>liamjegoupro@gmail.com</span><br>
                <span>+33 6 42 65 30 40</span><br>
                <span>49100, Angers</span><br>
                <span>France</span>

            </div>
        </div>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
    .contact {
        margin: 100px 0 100px 0;
        align-items: center;
        justify-content: end;
        text-align: end;
        .title-c {
        color: #1c1cf5;
        font-family: 'Tears Of Joy', sans-serif;
        font-size: 8em;
    }
    }

    .right3 {
        padding: 0;
        margin: 20px;
        span {
        font-size: 2em;
    }
    }
    .bloc-contact {
    margin-top: 10em;
    display: flex;
    justify-content: end;
    align-items: end;
    text-align: end;
    }

</style>