<template>
    <div class="cont-card">
        <div class="cont-img">
            <img :src="thumb" :alt="series">
        </div>
        <h4 class="text-white pt-4 pe-4">
            {{ series }}
        </h4>
    </div>
</template>

<script>
export default {
    props: {
        'thumb': String,
        'price': String,
        'series': String,
        'type': String,
    }
}
</script>

<style lang='scss' scoped>

    .cont-card {
        width: calc(100% / 6);
        margin: 24px 0px;


    h4 {
        text-transform: uppercase;
        font-size: .9rem;
        }

    .cont-img{
        width: 100%;
    }

    img {
        width: 12rem;
        height: 12rem;
        object-fit: cover;
        object-position: top;
        }
} 

</style>