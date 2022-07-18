<template>
    <div>
        <div>
            <img :src="thumb" :alt="series">
        </div>
        <h6>
            {{ series }}
        </h6>
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

<style>

</style>