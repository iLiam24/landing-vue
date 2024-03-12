<template>

<div class="card">
                <div class="card-title">
                    <span><strong>Studio Floax</strong> - CEO et Co-fondateur</span>
                    <span>Jan 2015 - présent</span>
                </div>
                <div class="card-tag">
                    <div>Stratégie</div>
                    <div>Management</div>
                    <div>DesignOps</div>
                    <div>Ingénieur FullStack</div>
                    <div>Product Deisgn</div>
                    <div>Formation</div>
                </div>
                <ul>
                    <li><div class="list-mark"></div>Gestion d'une entreprise d'ingénierie Logiciel et Product Design</li>
                    <li><div class="list-mark"></div>Management des équipes (9 salariés)</li>
                    <li><div class="list-mark"></div>Conception techniques et gestion des projets clients (Industrie, Formations, Startup, BTP)</li>
                    <li><div class="list-mark"></div>Relation client, Prospection et Communication externe</li>
                </ul>
            </div>

</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
        .card {
            color: black;
            margin: 10px;
            background-color: white;
            padding: 32px;
        }
        .card-title {
            display: flex;
            justify-content: space-between;
            font-family: "Raleway", sans-serif;
            font-weight: 400;
        }
        .card-tag {
            margin-top: 10px;
            display: flex;
            flex-wrap: wrap;
            font-family: "Raleway", sans-serif;
            font-weight: 400;
            font-size: 0.7em;
            div {
                padding: 5px 10px;
                margin: 5px 10px 5px -3px;
                background-color: #f0f5f9;
                color: #646f7d;
                border-radius: 7px;
            }
        }
        ul {
            list-style: none;
            padding: 0;
            margin: 0;
            li {
                display: flex;
                align-items: center;
                justify-content: flex-start;
                font-family: "Raleway", sans-serif;
                font-size: 0.8em;
                .list-mark {
                    width: 10px;
                    height: 10px;
                    background-color: #e7edf2;
                    border-radius: 2px;
                    margin: 5px 10px 5px 0px;
                }
            }
        }
</style>