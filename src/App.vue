<script setup>

import ProductCard from './components/ProductCard.vue'
// import SideBar from './components/SideBar.vue';
import CartCard from './components/CartCard.vue';

</script>

<template>
  <!-- <CartCard/> -->
  <!-- <SideBar/> -->
  <header  class=" h-20 w-screen text-black flex justify-between items-center md:px-10 ">
    <div class="flex space-x-4 md:space-x-6 ">
             <!-- section to be commmented -->
            <!-- <img class="ml-4 md:invisible" src="@/assets/icon-menu.svg " alt="burger" /> -->
            <img class="" src="@/assets/logo.svg" alt="logo"/>

               <!-- section to be commented -->
            <ul class=" invisible md:visible text-gray-500 ml-4 flex space-x-6">
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
  <!-- another section to be commented -->
  <hr class="invisible bg-gray-200 md:visible ml-11 mr-16 mt-4" >
  <main class="mt-4">
    <ProductCard/>
  </main>
</template>


<style>
</style>
