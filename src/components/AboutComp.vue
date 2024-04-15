<template>
       <div class="ancre1" id="ancre-apropos"></div>
    <section>
        <div class="about">
            <div class="photo">
                    <img class="img-tete" src="../assets/img/photodemoi.jpg" alt="Ma tête">
            </div>
            <div class="text">
                <h1>Liam JEGOU</h1>
                <h2>Etudiant en Web Design à Angers</h2>
                <span>Je suis un étudiant en web design, passionné par les nouvelles technologies, les tendances du design et du web. J'ai une approche créative et innovante de mon travail. Curieux, je suis constamment à la recherche de nouvelles façons de mettre en valeur mes projets. <br>
                    
                    En tant que web designer autodidacte, je suis toujours en train de me perfectionner et de me tenir au courant des dernières tendances et des meilleures pratiques du métier en tenant une veille technologique sur le design et le développement web. <br>

                    Ayant déjà 2 années d'études en BTS SIO (Services informatiques aux organisations) je me suis formé au développement et je me suis spécialisé en autonomie sur le développement web. <br>

                    Actuellement en bachelor 3 Web design, j'améliore constamment mes qualités graphiques ainsi que mon approche UI/UX du web.<br>
                    
                    En étant polyvalent, je suis capable de travailler sur des projets de toutes tailles et de tous types. Que je sois chargé de créer un site web pour une petite entreprise ou de mettre en place une stratégie de marketing en ligne pour une grande marque, je suis prêt à relever tous les défis. <br>
                    
                    En résumé, je suis un web designer passionné, créatif et polyvalent, qui s'engage à offrir des solutions sur mesure et de qualité. <br><br>
                </span>
            </div>
        </div>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
    .about {
        display: flex;
        align-items: center;
        padding: 5%;
        margin-left: 10%;
        margin-right: 10%;
    }

.text {
    font-family: 'Alexandria', sans-serif;
    font-weight: 300;
    margin-left: 5%;
    text-align: justify;

    h1 {
        margin-bottom: 10px;
        }
    h2 {
        color: rgb(84, 84, 84);
        font-weight: 300;
        font-size: 2em;
        margin-top: 0;
        }
}
.img-tete {
        border-radius: 12px;
        max-width: 100%;
    }

.left {
        margin-bottom: 30px;
    }
</style>