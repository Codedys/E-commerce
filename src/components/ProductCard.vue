<script setup>
</script>

<template>
    
    <div class="   flex justify-between items-center bg-[url('@/assets/image-product-1-thumbnail.jpg')] h-64 w-full bg-cover bg-center md:invisible ">
        <img class=" h-8 w-8 rounded-full ml-4 bg-white" src="@/assets/icon-previous.svg" alt="previous">
        <img class=" h-8 w-8 rounded-full mr-4 bg-white" src="@/assets/icon-next.svg" alt="next">
    </div>

<div class="flex  space-x-0  h-screen w-screen px-44 ">
 <div class="">
   <img class="h-96 w-96 rounded-lg " src="@/assets/image-product-3.jpg" alt="">
   <div class="flex">
       <img class="h-14 w-14 rounded-lg" src="@/assets/image-product-1-thumbnail.jpg" alt="">
       <img class="h-14 w-14 rounded-lg" src="@/assets/image-product-1-thumbnail.jpg" alt="">
       <img class="h-14 w-14 rounded-lg" src="@/assets/image-product-1-thumbnail.jpg" alt="">
       <img class="h-14 w-14 rounded-lg" src="@/assets/image-product-1-thumbnail.jpg" alt="">
    
   </div>
 </div>
<div class="">
    <div class="mx-8 space-y-4 my-6 ">
        <h2 class="text-orange-500 text-lg">SNEAKER COMPANY</h2>
        <h1 class="text-3xl text-black">Fall Limited Edition Sneakers</h1>
        <p class="text-gray-500">These low-profile sneakers are you perfect casual wear companion.Featuring a durable outer
            rubber sole,they'll with stand anything  the weather can offer.
        </p>
    </div>
    <div class="flex justify-between items-center mx-8">
        <div class=" flex space-x-4 justify-center ">
                <div class="text-3xl text-center">$125.45</div>
                <div class=" h-10 w-16 flex items-center justify-center  rounded-lg   bg-orange-100 text-orange-500"> 50%</div>   
        </div>
        <div class="text-2xl text-gray-400"> $250.00</div>
    </div>
    <div>
    <div class=" flex items-center h-12 rounded-lg bg-gray-100 mt-6  justify-between mx-8"> 
        <img class=" ml-4 h-1 w-4 " src="@/assets/icon-minus.svg" alt="">
        <span class="text-lg">0</span>
        <img  class=" mr-4 h-3 w-3"   src="@/assets/icon-plus.svg" alt="">
    </div>
      <div class=" text-white mt-3 mb-4 flex items-center justify-center space-x-3 h-12 bg-orange-500 rounded-lg mx-8">
        <img class="fill-current text-white" src="@/assets/icon-cart.svg" alt="cat">
        <p>Add to cart</p>
      </div>
</div>
</div>

</div>



</template>