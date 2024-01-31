<script>
  export default {
    name: 'AppTitle',
    data: () => ({
        text: 'La mia prima app con Vite!'
    }),
  };
</script>

<template>
  <h1>{{ text }}</h1>
</template>

<style>
    h1{
        color: blueviolet;
        text-align: center;
    }
</style>
