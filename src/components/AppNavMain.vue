
<script>
export default {
    name: "AppNavMain",

}

</script>

<template>
    <div class="containerNav">
        <div class="navName">
            <div><img src="../assets/buy-comics-digital-comics.png" alt="">DIGITAL COMICS</div>
            <div><img src="../assets/buy-comics-merchandise.png" alt="">DC MERCHANDISE</div>
            <div><img src="../assets/buy-comics-subscriptions.png" alt="">SUSCRIPTION</div>
            <div><img src="../assets/buy-comics-shop-locator.png" alt="">COMIC SHOP LOCATOR</div>
            <div><img id="Imgheight" src="../assets/buy-dc-power-visa.png" alt="">DC POWER VISA</div>

        </div>

    </div>
</template>


<style  lang="scss" scoped>
@use '../styles/partials/_variables' as *;


.containerNav {
    width: 100%;
    height: 8.5rem;
    background-color: #0282f9;
    display: flex;
    justify-content: center;
}


.navName {
    width: 70rem;
    height: 8.5rem;
    color: white;
    display: flex;
    justify-content: space-evenly;
}

.navName div {
    display: flex;
    align-items: center;
    font-size: 0.8rem;

}

.navName div img {
    height: 40%;
    margin-right: 0.8rem;
}

#Imgheight {
    height: 25%;
}
</style>


