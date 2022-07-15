<template>
    <div class=" d-flex justify-content-between align-items-center p-3">
        <img src="../assets/dc-logo.png" alt="DC LOGO">
        <nav>
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

nav {

}

img {
    height: 5rem;
}

ul li {
    text-decoration: none;
    display: inline-block;
    font-size: 0.8rem;

    &:hover {
            border-bottom: 5px solid $brandColor;
            color: $brandColor;
        }
}
</style>