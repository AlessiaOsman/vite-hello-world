<script>
  export default {
    name: 'AppHero',
    data: () => ({
        image: 'landscape.jpg'
    }),
    methods: {
        createImagePath(image){
            const url = new URL (`../assets/img/${image}`, import.meta.url);
            return url.href

        }
    }
  };
</script>

<template>
 <img :src="createImagePath(image)" alt="">
</template>

<style>
    img{
        margin: 0 auto;
        width: 90%;
    }
</style>