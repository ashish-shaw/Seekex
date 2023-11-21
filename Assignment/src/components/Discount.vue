<template>
  <div
    class="fonts flex sm:space-x-10 space-x-6 sm:px-28 px-3 py-10 items-center justify-center"
  >
    <div class="bg-[#CCCEA7] sm:w-[550px] w-[300px] sm:h-[650px] h-[300px]">
      <div class="text-center">
        <img :src="diamond" alt="" class="m-auto sm:pt-12 pt-5 sm:w-auto w-24" />
        <h1 class="font-semibold sm:text-4xl text-lg sm:py-10 py-1">
          Hurry Up!
        </h1>
        <h1 class="font-semibold sm:text-7xl text-xl sm:pb-10 py-1">75% OFF</h1>
        <h2 class="font-semibold sm:text-4xl text-lg sm:pb-10 py-1">Sale</h2>
        <button
          class="border border-white text-white sm:px-8 px-4 sm:py-3 py-1.5 font-medium sm:text-base text-sm"
        >
          Shop Now
        </button>
      </div>
    </div>
    <div class="bg-[#D6BEBE] sm:w-[550px] w-[300px] sm:h-[650px] h-[300px]">
      <div class="text-center">
        <img :src="discount" alt="" class="m-auto sm:pt-12 pt-5 sm:w-auto w-24" />
        <h1 class="font-semibold sm:text-4xl text-lg sm:py-10 py-1">
          Hurry Up!
        </h1>
        <h1 class="font-semibold sm:text-7xl text-xl sm:pb-10 py-1">85% OFF</h1>
        <h2 class="font-semibold sm:text-4xl text-lg sm:pb-10 py-1">Sale</h2>
        <button
          class="border border-white text-white sm:px-8 px-4 sm:py-3 py-1.5 font-medium sm:text-base text-sm"
        >
          Shop Now
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
import discount from "./Images/discount.png";
import diamond from "./Images/diamond.png";
</script>

<style scoped>
.fonts {
  font-family: "Playfair Display", serif;
}
</style>
