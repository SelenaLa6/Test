<script setup lang="ts">
import { RouterLink } from 'vue-router';

</script>

<template>
<div class=" min-h-screen">
    <div class="hero avatar hero-content">
         <div class="ring-primary ring-offset-base-100 w-64 rounded-full ring ring-offset-2">
            <img src="https://img.daisyui.com/images/stock/photo-1534528741775-53994a69daeb.webp" />
        </div>
    </div>
    <div>
        <div class="font-bold text-3xl font-serif tracking-wider">
            Selena La
        </div>
        <div>
            I put relevant links and contact here!!!
            <RouterLink to="/about">About</RouterLink>
        </div>
        <div>
            I talk about myself here! Blah blah blah
        </div>
    </div> 
</div>
 

    
</template>

<style scoped>

</style>