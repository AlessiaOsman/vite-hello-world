<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  name: 'HelloVite',
  
  components: {
    AppTitle,
    AppHero
  }
};
</script>

<template>
  <div class="container">
    <AppTitle />
    <AppHero/>
  </div>
  </template>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  .container{
    margin: 24px auto;
    display: flex;
    flex-direction: column;
    gap: 24px;
  }
</style>

