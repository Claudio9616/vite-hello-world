<script>
export default {
    data: () => ({
        name: 'DELLA PRIMA APPLICAZIONE',
        image: '02.jpeg'
    }),
    methods: {
        getImagePath(image) {
            const url = new URL(`../assets/${image}`, import.meta.url)
            return url.href
        }
    }
}
</script>
<template>
    <h2>SOTTOTITOLO {{ name }}</h2>
    <img :src="getImagePath(image)" alt="">
</template>
<style scoped>
h2 {
    color: cadetblue;
}
</style>