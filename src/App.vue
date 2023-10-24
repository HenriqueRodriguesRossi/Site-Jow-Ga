<template>
  <Header />
  <RouterView />
</template>

<script>
import Header from './components/header.vue';
import { RouterView } from 'vue-router';

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

}
</style>