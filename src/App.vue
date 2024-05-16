<script setup>

import ProductCard from './components/ProductCard.vue'

</script>

<template>
  <header  class=" h-20 w-screen text-black flex justify-between items-center">
    <div class="flex space-x-4 ">
            <img class="ml-4" src="@/assets/icon-menu.svg" alt="burger" />
            <img src="@/assets/logo.svg" alt="logo"/>
    </div>
    <div class="flex space-x-4 mr-4 ">
            <img src="@/assets/icon-cart.svg" alt="cat">
            <img class="h-8 w-10 " src="@/assets/image-avatar.png" alt="avatar">
    </div> 
  </header>
  <main>
    <ProductCard/>
  </main>
</template>


<style>
</style>
