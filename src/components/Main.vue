<template>
    <main>
        <div class="container">
            <h2 class="fs-3 pt-5 pb-5">
                --- Content goes here ---
            </h2>
        </div>
        
        <div class="bg_shopDC">
            <div class="container shopDC p-5 text-white">
                <div>
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                    <span class="px-3">DIGITAL COMICS</span> 
                </div>
                <div>
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                    <span class="px-3">DC MERCHANDISE</span>
                </div>
                <div>
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                    <span class="px-3">COMIC SHOP LOCATOR</span>
                </div>
                <div>
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                    <span class="px-3">SUBSCRIPTIONS</span>
                </div>
                <div>
                    <img src="../assets/buy-dc-power-visa.svg" alt="">
                    <span class="px-3">DC POWER VISA</span>
                </div>
            </div>
        </div>

    </main>
</template>

<script>
export default {

}
</script>

<style lang='scss' scoped>
@import '../styles/variables.scss';

    main {
        background-color: $backgroundColor;
        color: #fff;
    }

    .bg_shopDC {
        background-color: $colorShop;

    }

    .shopDC {
        display: flex;
        justify-content: space-around;
        align-items: center;

        img{
        width: 46px;
    }
    }

    
</style>