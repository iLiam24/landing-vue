<template>
    <section class="section-4">
        <div class="classic-container">
            <div class="content">
                <h2><span>Simplify</span> all <br> complexity</h2>
                <div class="bloc">
                    <p class="title-bloc">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sint sapiente ex sed nam obcaecati ab labore quia neque eos corporis.</p>
                    <p class="subtitle-bloc">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam velit ipsum voluptatum aperiam dignissimos sit ducimus iure alias, corporis ea illum cum consequuntur et animi!</p>
                </div>
                <div class="bloc">
                    <p class="title-bloc">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sint sapiente ex sed nam obcaecati ab labore quia neque eos corporis.</p>
                    <p class="subtitle-bloc">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam velit ipsum voluptatum aperiam dignissimos sit ducimus iure alias, corporis ea illum cum consequuntur et animi!</p>
                </div>
                <div class="bloc">
                    <p class="title-bloc">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sint sapiente ex sed nam obcaecati ab labore quia neque eos corporis.</p>
                    <p class="subtitle-bloc">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam velit ipsum voluptatum aperiam dignissimos sit ducimus iure alias, corporis ea illum cum consequuntur et animi!</p>
                </div>
            </div>
            <img src="../assets/img/guy.jpg" alt="">
        </div>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
.section-4 {
    background-color:rgb(58, 124, 128) ;
    margin: 250px -10px 0 -10px;
    height: 700px;
    max-height: 700px;

    .classic-container {
        display: flex;
    }
    .content{
        h2 {
            font-family: "Source Serif 4", serif;
            margin-top: -80px;
            font-size: 3.5em;
            color: white;
            span {
                display: block;
                color: rgb(58, 124, 128);
                }
        }
    }
    img {
        margin-top: -80px;
        background-repeat: no-repeat;
        background-size:contain; 
        height: auto;
        width: 40%;
        max-width: 40%;
        height: 100%;
    }
    .bloc {
        width: 60%;
        .title-bloc {
            font-family: "Source Serif 4", serif;
            font-size: 1.4em;
            color: rgb(255, 255, 255);
            border-left: 4px solid rgb(89, 184, 206);
            padding-left: 20px;
        
            &:hover {
                cursor: pointer;
                border-left: 4px solid rgb(72, 156, 147);
            }

            &:hover + .subtitle-bloc {
                transition: ease-in-out 200ms;
              display: block;
            }
          }
        
          .subtitle-bloc {
            display: none;
            font-family: "Source Serif 4", serif;
            font-size: 1em;
            color: rgb(255, 255, 255);

          }
    }
}
</style>