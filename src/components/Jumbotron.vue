<template>
    <div class="cont-jumb">
        <img src="../assets/jumbotron.jpg" alt="">
    </div>
</template>

<script>
export default {

}
</script>

<style lang='scss' scoped>
@import '../styles/variables.scss';

    .cont-jumb {
        height: 25rem;
    }
    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: top;
    }
</style>