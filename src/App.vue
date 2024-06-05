<script setup>

import ProductCard from './components/ProductCard.vue'
// import SideBar from './components/SideBar.vue';
import CartCard from './components/CartCard.vue';

</script>

<template>
  <!-- <CartCard/> -->
  <!-- <SideBar/> -->
  <header  class=" h-20 w-screen text-black flex justify-between items-center md:px-24 ">
    <div class="flex space-x-4 md: space-x-10 ">
            <img class="ml-4 md:invisible" src="@/assets/icon-menu.svg " alt="burger" />
            <img class="" src="@/assets/logo.svg" alt="logo"/>
            <ul class=" text-gray-500 ml-16 flex space-x-4">
              <li >Collection</li>
              <li>Men</li>
              <li>Women</li>
              <li>About</li>
              <li>Contact</li>

            </ul>
    </div>
    <div class="flex space-x-4 mr-4 ">
            <img src="@/assets/icon-cart.svg" alt="cat">
            <img class="h-8 w-10 " src="@/assets/image-avatar.png" alt="avatar">
    </div> 
  </header>
  <hr class="invisible bg-gray-200 md:visible ml-40 mr-24" >
  <main class="mt-4">
    <ProductCard/>
  </main>
</template>


<style>
</style>
