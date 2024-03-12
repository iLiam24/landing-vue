<template>
    <section class="section-3">
        <div class="classic-container">
            <div class="title">
                <p>Few projects. <br><span>Many Years</span></p>
                <form>
                    <input type="" placeholder="Rechercher un projet" id="">
                    <button>Rechercher</button>
                </form>
            </div>

            <div class="bloc-show">
                <div class="show">
                    <div class="w30"><img src="../assets/img/featured.png" alt=""></div>
                    <div class="w60"><img src="../assets/img/shumasher.jpeg" alt=""></div>
                </div>
                <div class="show">
                    <div class="w60"><img src="../assets/img/refire.jpeg" alt=""></div>
                    <div class="w30"><img src="../assets/img/oakley-project-2075.jpeg" alt=""></div>
                </div>
                <div class="show">
                    <div class="w30"><img src="../assets/img/havasfactory.png" alt=""></div>            
                    <div class="w60"><img src="../assets/img/vaaal.png" alt=""></div>
                </div>
            </div>
        </div>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
.section-3 {
    p {
        font-family: "Raleway", sans-serif;
        font-size: 2em;
    }
    span {
        font-family: "Source Serif 4", serif;
        font-size: 1.2em;
    }
    .title {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    input {
        border: none;
        border: 1px solid  rgb(200, 201, 213);
        padding: 15px 60px;
        margin-right: 10px;
        border-radius: 2px;
        font-family: "Raleway", sans-serif;
        text-align: left;
        
    }
    button {
        padding: 15px 30px;
        background-color: rgb(40 64 91);
        color: white;
        border: none;
        border-top-left-radius: 5px; 
        border-bottom-right-radius: 5px; 
    }
    .bloc-show {
        display: flex;
        flex-direction: column;
    }
    .show {
        display: flex;
        justify-content: space-between;
        margin-bottom: 2em;
        div {
            overflow: hidden;
            img {
                width: 100%;
                height: 100%;
                object-fit: cover;
            }
        }
    }
    .w30 {
        width: 33%;
        height: 50vh;
        background-color: red;
    }
    .w60 {
        width: 65%;
        height: 50vh;
        background-color: blue;
    }

}
</style>