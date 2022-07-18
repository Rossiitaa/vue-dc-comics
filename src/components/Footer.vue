<template>
    <footer>

        <div class="container">
            <div class="cont-footer">
                <section class="row pt-5 pb-5 footer-left">
                    <div class="col-4">
                        <h3 class="text-white fs-5 mb-3">DC COMICS</h3>
                        <ul class="mb-4">
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>Tv</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                        <h3 class="text-white fs-5 mb-3">SHOP</h3>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                        <div class="col-4">
                        <h3 class="text-white fs-5 mb-3">DC </h3>
                        <ul>
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
                            <li>Contact Us</li>
                        </ul>
                    </div>
                        <div class="col-4">
                        <h3 class="text-white fs-5 mb-3">SITES</h3>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </section>
                
                <section class="footer-right">
                </section>
            </div>
        </div>

        <div class="footer-bottom d-flex">
            <div class="container d-flex justify-content-between align-items-center">
                <div>
                    <a href="#" class="text-white button-sign">SIGN-UP NOW!</a>
                </div>
                <div>
                    <a href="#" class="me-4 text-follow">FOLLOW US</a>
                    <a href="#" class="me-3"><img src="../assets/footer-facebook.png" alt="facebook"></a>
                    <a href="#" class="me-3"><img src="../assets/footer-twitter.png" alt="twitter"></a>
                    <a href="#" class="me-3"><img src="../assets/footer-youtube.png" alt="youtube"></a>
                    <a href="#" class="me-3"><img src="../assets/footer-pinterest.png" alt="pinterest"></a>
                    <a href="#" class="me-3"><img src="../assets/footer-periscope.png" alt="periscope"></a>
                </div>
            </div>
        </div>

    </footer>
</template>

<script>
export default {

}
</script>

<style lang='scss' scoped>
@import '../styles/general.scss';
@import '../styles/variables.scss';

footer {
    background-image: url(../assets/footer-bg.jpg);
    background-size: cover;
}

.cont-footer{
    height: 100%;
    display: flex;
    justify-content: space-between;
}

ul {
    padding: 0;
}

li {
    list-style: none;
    color: rgba(255, 255, 255, 0.377);
    font-size: 0.8rem;
}

a {
    text-decoration: none;
}

.footer-left {
    width: 35%;
}

.footer-right {
    width: 43%;
    background-image: url(../assets/dc-logo-bg.png);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

.footer-bottom {
    height: 100px;
    background-color: #303030;
}

.button-sign {
    padding: 10px 10px;
    border: 2px solid #1081f4;
    font-weight: bold;
}

.text-follow {
    color: #1081f4;
    font-weight: bold;
    font-size: 1.2rem;
}

</style>