<script>
export default {
    name: "AppMain",
    props: {
        fumetti: Array
    },
    data() {

    },
    mounted() {
        console.log("AppMain", this.fumetti);
    }
}

</script>

<template>
    <main>
        <div class="cointainerMain">

            <div class="jumba"><img src="../assets/jumbotron.jpg" alt=""></div>


            <div class="containerCard">
                <div class="btnMainB">
                    <button>CURRENT SERIES</button>
                </div>
                <div class="cards" v-for="fumetto in fumetti ">
                    <div class="imgs">
                        <img :src="fumetto.thumb" alt="">
                    </div>

                    <p>{{ fumetto.series }}</p>
                </div>
                <div class="btnMain">
                    <button>LOAD MORE</button>
                </div>

            </div>

        </div>


    </main>
</template>


<style  lang="scss" scoped>
@use '../styles/partials/_variables' as *;

.cointainerMain {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #1c1c1c;
    position: relative;
    padding-top: 23rem;
    position: relative;

}

.jumba img {
    width: 100%;
    height: 23rem;
    object-fit: cover;
    object-position: 0 0;
    position: absolute;
    left: 0;
    top: 0;
}

//********* */ CARDS******
.containerCard {
    width: 70rem;
    height: 38rem;
    color: white;
    display: flex;
    flex-wrap: wrap;
    margin-top: 3rem;
    padding-bottom: 2rem;
    justify-content: space-between;
    gap: 1rem;
}

.cards {
    width: 10rem;
    height: 12.5rem;

}

.imgs {
    max-width: 10rem;
    max-height: 10.5rem;
    margin-bottom: 1rem;

    img {
        width: 10rem;
        height: 10.5rem;
        object-fit: cover;

    }
}

.btnMainB {

    button {
        padding: 0.5rem 2rem;
        background-color: #0282f9;
        color: white;
        margin-top: 2rem;
        position: absolute;
        font-size: 2rem;
        font-weight: bold;
        top: 19rem;
    }

}


.btnMain {
    width: 100%;
    display: flex;
    justify-content: center;

    button {
        padding: 0rem 4rem;
        background-color: #0282f9;
        color: white;
        margin-top: 2rem;
    }
}
</style>