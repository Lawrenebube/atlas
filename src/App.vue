<script setup>
import { RouterView } from 'vue-router';
import NavBar from './components/NavBar.vue';

</script>


<template>
  
  <NavBar />
  <RouterView />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
