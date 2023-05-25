<script>
export default {
    name: "AppHeader",

    data() {
        return {
            helo: "ciao",


        }
    },
    methods: {
        metodo() {

        },

    },
    mounted() {

    }
}

</script>

<template>
    <header>
        <div class="navBar">
            <div class="containerBar">
                <div class="logo">
                    <img src="../assets/dc-logo.png" alt="">
                </div>
                <div class="bar">
                    <div>CHARACTERS</div>
                    <div>COMICS</div>
                    <div>MOVIES</div>
                    <div>TV</div>
                    <div>GAME</div>
                    <div>COLLECTIBLE</div>
                    <div>VIDEOS</div>
                    <div>FANS</div>
                    <div>NEWS</div>
                    <div>SHOP</div>
                </div>

            </div>

        </div>

    </header>
</template>

<style  lang="scss" scoped>
@use '../styles/partials/_variables' as *;

.navBar {
    width: 100vw;
    height: 7rem;
    background-color: #ffffff;
    display: flex;
    justify-content: center;
}

.containerBar {
    width: 70rem;
    height: 100%;
    display: flex;
}

.logo {
    width: 40%;
    height: 100%;
    display: flex;
    align-items: center;
}

.logo img {
    height: 75%;
}

.bar {
    width: 60%;
    height: 100%;
    display: flex;
    justify-content: space-evenly;
}

.bar div {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    font-size: 0.8rem;
}
</style>