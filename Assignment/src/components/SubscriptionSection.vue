<template>
  <div class="sm:w-[71rem] w-[26.5rem] sm:h-[18rem] h-[15rem] flex justify-between m-auto mt-12 background">
    <img :src="vector1" alt="" class="sm:w-auto w-8 h-auto"/>
    <div class="text-center sm:pt-16 pt-10 sm:px-12">
      <h1 class="font-family font-semibold sm:text-4xl text-xl text-white">
        Subscribe to get updates on exciting offers & deals
      </h1>
      <div class="sm:w-[35rem] w-64 sm:h-16 h-10 mt-6 mx-auto flex">
      <input type="text" placeholder="Enter your email" class="font-medium w-2/3 h-full sm:px-8 px-2 sm:text-base text-xs bg-[#ab001f] placeholder-white">
      <div class="h-full w-1/3 bg-white text-[#770015] sm:text-xl text-sm font-family font-semibold sm:pt-4 pt-2.5 cursor-pointer">Subscribe</div>
      </div>
    </div>
    <img :src="vector2" alt="" class="sm:w-auto w-8 h-auto"/>
  </div>
</template>

<script setup>
import vector1 from "./Images/vector1.png";
import vector2 from "./Images/vector2.png";
</script>

<style scoped>
.background {
  background: linear-gradient(97.3deg, #ab001e -6.23%, #770015 105.09%);
}
.font-family {
  font-family: "Playfair Display", serif;
}
</style>
