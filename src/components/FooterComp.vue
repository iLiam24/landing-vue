<template>
    <footer>
        <div class="footer-cont">
            <div class="social-media">
                <a href="https://www.linkedin.com/in/liam-jegou-74b991210/">LinkedIn</a><br>
                <a href="index.html">Site web</a><br>
            </div>
            <div class="last">
                <span>© 2021–2024</span>
                <span>PORTFOLIO</span>
            </div>
        </div>
    </footer>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
.social-media {
    display: inline-block;
    a {
    color: white;
    font-family: 'Alexandria', sans-serif;
    font-weight: 200;
    font-size: 1.4em;
    text-decoration: none;
}
}


.footer-cont {
    background-color: rgb(29, 31, 31);
    padding-top: 12%;
    padding-right: 12%;
    padding-left: 12%;
    padding-bottom: 2%;
}

.last {
    margin-top: 10%;
    display: flex;
    align-items: center;
    justify-content:space-between;

    span {
    color: rgb(165, 165, 165);
    font-family: 'Alexandria', sans-serif;
    font-weight: 200;
    font-size: 1em;
}
}

</style>