<template>
    <div class="container d-flex justify-content-between align-items-center p-5">
        <img src="../assets/dc-logo.png" alt="DC LOGO">
        <nav class="p-3">
            <ul>
                <li v-for="(element, index) in elementList" :key="index" class="p-3 text-uppercase fw-bold">
                    {{ element.text }}
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    data() {
        return {
            elementList: [
                {
                text: "characters",
                href: "#"
                },
                {
                text: "comics",
                href: "#"
                },
                {
                text: "movies",
                href: "#"
                },
                {
                text: "tv",
                href: "#"
                },
                {
                text: "games",
                href: "#"
                },
                {
                text: "collectibles",
                href: "#"
                },
                {
                text: "videos",
                href: "#"
                },
                {
                text: "fans",
                href: "#"
                },
                {
                text: "news",
                href: "#"
                },
                {
                text: "shop",
                href: "#"
                },
                {
                }
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
    font-size: 0.9rem;

    &:hover {
            border-bottom: 5px solid $brandColor;
            color: $brandColor;
        }
}
</style>