<template>
    <header>
        <div class="container d-flex justify-content-between align-items-center p-3">
            <img  src="../assets/dc-logo.png" alt="DC LOGO">
            <nav>
                <ul>
                    <li v-for="(element, index) in elementList" :key="index" class="me-4 text-uppercase fw-bold">
                        <a href="#">{{ element.text }}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    data() {
        return {
            elementList: [
                {
                text: "characters",
                },
                {
                text: "comics",
                },
                {
                text: "movies",
                },
                {
                text: "tv",
                },
                {
                text: "games",
                },
                {
                text: "collectibles",
                },
                {
                text: "videos",
                },
                {
                text: "fans",
                },
                {
                text: "news",
                },
                {
                text: "shop",
                },
            ]
        }
    }
}
</script>

<style lang='scss' scoped>
@import '../styles/general.scss';
@import '../styles/variables.scss';


img {
    height: 5rem;
}

ul li {
    text-decoration: none;
    display: inline-block;
    font-size: 0.8rem;
    cursor: pointer;

    &:hover {
            border-bottom: 5px solid $brandColor;
            color: $brandColor;
        }
}

a {
    text-decoration: none;
    color: #000;
}
</style>