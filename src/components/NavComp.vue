<template>
        <div class="nav">
        <div class="navbar">
            <div class="animate__animated animate__fadeIn left-nav">
                <a href="https://liamjegou.com/"><img class="logo" src="../assets/img/logo.png" alt="logo"></a>
            </div>
            <nav>
                <button id="burger" class="burger" type="button"><img id="icon" src="../assets/svg/burger.svg" alt="menu burger"></button>
                <ul id="nav-list" class="nav-list">
                    <li id="navitem" class="nav-item"><a id="nav-a" href="#ancre-travaux">Portfolio</a></li>
                    <li id="navitem" class="nav-item"><a id="nav-a" href="#ancre-apropos">A propos</a></li>
                    <li id="navitem" class="nav-item"><a id="nav-a" href="#ancre-contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>

    .left-nav {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    max-width: 600px;
        a {
            width: 90%;
        }
}


.name {
    margin-left: 2em;
    font-size: larger;
    color: black;
    font-family: 'Tears of Joy', sans-serif;
    font-weight: 500;
}
.logo {
    padding-left: 20px;
    max-width: 30%;
    width: 30%;
}

nav {
    display: flex;
    align-items: center;


}

.burger {
    display: none;
    border: none;
    background-color: #ebebec;
    margin-right: 5px;

    img {
    width: 20px;
}
}

.nav-list {
display: block;
padding-left: 0;
}

.nav-list.active {
    display: flex; flex-direction: column;
    align-items: center;
    position: absolute;
    background: rgba(235,235,236,0.85);

    top: 100%;
    right: 0;
    height: 150px;
    width: 100%;
    margin-top: 0;
    z-index: 10;
    padding-top: 9px;
    gap: 5px;
}

.nav {
    background-color: #fef9f1;
    width: 100%;
    position: fixed;
    margin-top: -10em;
    z-index: 100;
}
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav-item {
    padding: 5px;
    display: inline-block;
    text-align: center;
    align-items: center;
    margin-right: 20px;
    transform: translateY(1.5px);
    transition-duration: .6s;

    a {
    text-decoration: none;
    color: black;
    font-family: 'Alexandria', sans-serif;
    font-weight: 300;
}
}

.nav-item:hover {
    transform: translateY(-1.5px);
    transition-duration: .6s;
}




</style>