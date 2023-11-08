<template>
  <Header />
  <RouterView />
</template>

<script>
import { RouterView } from 'vue-router';
import Header from './components/Header.vue';

export default {
  components: {
    Header
  }
}
</script>

<style>
@media(max-width: 600px){
  html{
    overflow-x: hidden;
  }

  img{
    width: 400px;
    height: 400px;
  }
}
</style>