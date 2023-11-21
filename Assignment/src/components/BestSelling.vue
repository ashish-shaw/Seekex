<template>
  <div class="sm:px-28 px-3">
    <div class="flex sm:justify-between sm:py-10 py-5">
      <div class="sm:w-1/3 w-1/4 h-[1px] bg-pink-200 m-auto"></div>
      <h1 class="font-playfair font-semibold sm:text-4xl text-xl">Best Selling Products</h1>
      <div class="sm:w-1/3 w-1/4 h-[1px] bg-pink-200 m-auto"></div>
    </div>
    <div class="grid sm:grid-cols-4 grid-cols-2 sm:gap-4 gap-2 sm:py-4 py-2">
      <div v-for="(item, index) in collection" :key="index">
        <img :src="item.img" alt="" class="w-full cursor-pointer" />
        <div class="fonts text-center mx-auto w-[60%] font-normal text-sm pt-2">
          {{ item.label }}
        </div>
        <div class="fonts text-center text-xs font-normal py-2">
          {{ item.price
          }}<span class="text-red-500 line-through px-1 font-normal text-xs"
            >₹1299</span
          >
        </div>
        <div class="fonts flex sm:space-x-4 space-x-2 p-2 items-center justify-center">
            <p class="border border-gray-300 sm:w-8 w-6 sm:h-7 h-4 text-center font-medium sm:text-sm text-[10px]">S</p>
            <p class="border border-gray-300 sm:w-8 w-6 sm:h-7 h-4 text-center font-medium sm:text-sm text-[10px]">M</p>
            <p class="border border-gray-300 sm:w-8 w-6 sm:h-7 h-4 text-center font-medium sm:text-sm text-[10px]">L</p>
            <p class="border border-gray-300 sm:w-8 w-6 sm:h-7 h-4 text-center font-medium sm:text-sm text-[10px]">XL</p>
            <p class="border border-gray-300 sm:w-8 w-6 sm:h-7 h-4 text-center font-medium sm:text-sm text-[10px]">XXL</p>
        </div>
      </div>
    </div>
    <div class="flex justify-center my-4">
    <button class="bg-red-900 text-white px-8 py-2 font-medium text-base m-auto">View All</button>
    </div>
  </div>
</template>

<script setup>
import image13 from "./Images/image13.png";
import image14 from "./Images/image14.png";
import image15 from "./Images/image15.png";
import image16 from "./Images/image16.png";

const collection = [
  {
    img: image13,
    label: "Men Henley Neck Full Sleeve Red Wine",
    price: "₹399",
  },
  {
    img: image14,
    label: "Men Henley Neck Full Sleeve Red Wine",
    price: "₹399",
  },
  {
    img: image15,
    label: "Men Henley Neck Full Sleeve Red Wine",
    price: "₹399",
  },
  {
    img: image16,
    label: "Men Henley Neck Full Sleeve Red Wine",
    price: "₹399",
  },
];
</script>

<style scoped>
.fonts{
    font-family: 'Montserrat', sans-serif;
    }
.font-playfair{
  font-family: "Playfair Display", sans-serif;
}    
</style>
