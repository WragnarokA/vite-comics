<script>
export default {
    name: "AppFooter"
}

</script>

<template>
    <footer>
        <img class="BgFooter" src="../assets/footer-bg.jpg" alt="">
        <div class="footerTop">
            <div>
                <ul class="listContatti">
                    <h2 class="titleUl">DC COMICS</h2>
                    <li>Caracters</li>
                    <li>Comics</li>
                    <li>movies</li>
                    <li>tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    <h2 class="titleUl">SHOP</h2>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibiles</li>
                </ul>

                <ul class="listContatti">
                    <h2 class="titleUl">DC </h2>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact US</li>
                </ul>

                <ul class="listContatti">
                    <h2 class="titleUl">SITES </h2>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
            <div>
                <img class="ImgDC" src="../assets/dc-logo-bg.png" alt="">

            </div>
        </div>

        <div class="footerBotton">
            <div>

                <button class="btnButton">SING-UP NOW!</button>

                <div class="ListFooter">

                    <p class="follow">FOLLOW US</p>

                    <div><img src="../assets/footer-facebook.png" alt=""></div>
                    <div><img src="../assets/footer-pinterest.png" alt=""></div>
                    <div><img src="../assets/footer-periscope.png" alt=""></div>
                    <div><img src="../assets/footer-youtube.png" alt=""></div>
                    <div><img src="../assets/footer-pinterest.png" alt=""></div>
                    <div><img src="../assets/footer-periscope.png" alt=""></div>

                </div>
            </div>
        </div>
    </footer>
</template>



<style>
footer {
    width: 100vw;
    height: calc(100vh - 23rem);
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
    flex-direction: column;
}

.BgFooter {
    width: 100vw;
    height: calc(100vh - 23rem);
    object-fit: cover;
    position: absolute;
    z-index: -1;
}

.footerTop {
    min-width: 70rem;
    height: 80%;
    display: flex;
}

.footerTop>div {
    width: 35rem;
    height: 100%;
    display: flex;

}


ul {
    list-style-type: none;
    margin: 3rem 1.5rem;
}

.listContatti>li {
    color: #959595;
    font-size: 0.8rem;
    margin-bottom: 0.4rem;
}

.titleUl {
    color: white;
    margin: 1.3rem 0;
}

.ImgDC {

    height: 40rem;
    position: absolute;
    bottom: 0.8rem;
    z-index: -1;
}

.footerBotton {
    width: 100vw;
    height: 20%;
    background-color: #303030;
    display: flex;
    justify-content: center;
    align-items: center;
}

.footerBotton>div {
    width: 70rem;
    height: 20%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.btnButton {
    font-size: 1rem;
    color: white;
    background: transparent;
    padding: 1rem;
    border: 1px solid #0282f9;
}

.ListFooter {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.follow {
    color: #0282f9;
    font-weight: bolder;
}
</style>