<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'

</script>

<template>
  <Navbar />
  <body>
    
    <RouterView />
  </body>



</template>

<style scoped>
:global(body){
  background-color:  #ffe6d9;
  color: #894d2c;
}
</style>
