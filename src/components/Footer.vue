<template>
    <footer>

        <div class="container">
            <div class="cont-footer">
                <section class="row pt-5 pb-5 footer-left">
                    <div class="col-4">
                        <h3 class="text-white fs-5 mb-3">DC COMICS</h3>
                        <ul class="mb-4">
                            <li v-for="(link , index) in Links1" :key="index">
                                <a href="#">{{ link.text }}</a>
                            </li>
                        </ul>
                        <h3 class="text-white fs-5 mb-3">SHOP</h3>
                        <ul>
                            <li v-for="(link, index) in Links2" :key="index">
                                <a href="#">{{ link.text }}</a>
                            </li>
                        </ul>
                    </div>
                        <div class="col-4">
                        <h3 class="text-white fs-5 mb-3">DC </h3>
                        <ul>
                            <li v-for="(link , index) in Links3" :key="index">
                                <a href="#">{{ link.text }}</a>
                            </li>
                        </ul>
                    </div>
                        <div class="col-4">
                        <h3 class="text-white fs-5 mb-3">SITES</h3>
                        <ul>
                            <li v-for="(link , index) in Links4" :key="index">
                                <a href="#">{{ link.text }}</a>
                            </li>
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
    data: function () {
    return {
        Links1: [
        {
        text: "Characters",
        },
        {
        text: "Comics",
        },
        {
        text: "Movies",
        },
        {
        text: "TV",
        },
        {
        text: "Games",
        },
        {
        text: "Videos",
        },
        {
        text: "News",
        },
    ],
    Links2: [
        {
        text: "Shop DC",
        },
        {
        text: "Shop DC Collectibles",
        },
    ],
        Links3: [
        {
        text: "Terms Of Use",
        },
        {
        text: "Privacy Policy (New)",
        },
        {
        text: "Ad Choices",
        },
        {
        text: "Advertising",
        },
        {
        text: "Jobs",
        },
        {
        text: "Subscriptions",
        },
        {
        text: "Talent Workshops",
        },
        {
        text: "Privacy Policy (New)",
        },
        {
        text: "CPSC Certificates",
        },
        {
        text: "Ratings",
        },
        {
        text: "Shop Help",
        },
        {
        text: "Contact Us",
        },
    ],
    Links4: [
        {
        text: "DC",
        },
        {
        text: "MAD Magazine",
        },
        {
        text: "DC Kids",
        },
        {
        text: "DC Universe",
        },
        {
        text: "DC Power Visa",
        },
    ],
    };
    },
};

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

li a {
    list-style: none;
    color: rgba(255, 255, 255, 0.377);
    font-size: 0.8rem;
    text-decoration: none;
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