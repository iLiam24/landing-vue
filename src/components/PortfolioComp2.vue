<template>
    <div class="ancre2" id="ancre-travaux"></div>
    <section class="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <div class="Works">
                <div class="left">
                    <h3>Wanded</h3>
                    <img src="../assets/img/wanded.png" alt="photo d'un de mes travaux">
                </div>
                <div class="right">
                    <h3>Typotory</h3>
                    <img src="../assets/img/1edit.png" alt="photo d'un de mes travaux">
                </div>
            </div>
        </div>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
.portfolio {
    background-color: rgb(49, 50, 52);
    padding: 50px 0 50px 0;
    margin: 50px 0 50px 0;
    h2 {
        display: flex;
        justify-content: center;
        color: #fef9f1;
        font-family: 'Alexandria', sans-serif;
        font-weight: 700;
    }
    h3 {
        color: #fef9f1;
        font-family: 'Alexandria', sans-serif;
        font-weight: 300;
    }
    .Works {
        display: flex;
        justify-content: center;
        align-items: center;
        .left {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        .right {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        img {
            width: 70%;
            border-radius: 15px;
        }
    }
}


</style>