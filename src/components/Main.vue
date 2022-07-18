<template>
    <main>
        
        <div class="bg_shopDC">
            <div class="container shopDC text-white">
                <div>
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                    <span class="px-3">DIGITAL COMICS</span> 
                </div>
                <div>
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                    <span class="px-3">DC MERCHANDISE</span>
                </div>
                <div>
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                    <span class="px-3">SUBSCRIPTIONS</span>
                </div>
                
                <div>
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                    <span class="px-3">COMIC SHOP LOCATOR</span>
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
        padding: 40px;

        img{
        width: 50px;
    }
    }

    
</style>