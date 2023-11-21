<template>
<div>
  <div class="sm:px-28 px-3 pt-10 flex sm:space-x-4 space-x-2">
    <div class="w-[24%]"> 
      <p class="fonts sm:flex hidden font-medium sm:text-sm text-[10px]">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever
        since the 1500s, when an unknown printer took a galley of type and
        scrambled it to make a type specimen book. It has survived not only five
        centuries....
      </p>
      <p class="fonts sm:hidden font-medium sm:text-sm text-[10px]">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, not only five
        centuries....
      </p>
      <div class="flex sm:space-x-2 space-x-1 sm:py-4 py-1">
        <Facebook />
        <Twitter />
        <Instagram />
        <LinkedIn />
        <Interest />
      </div>
    </div>
    <div class="w-[24%] sm:pl-10 pl-3">
      <div class="text-[#770015] font-playfair font-semibold sm:text-lg text-xs pb-4">
        ONLINE SHOPPING
      </div>
      <div class="py-2 fonts grid grid-flow-row sm:gap-y-4 gap-y-2">
      <p class="font-medium sm:text-sm text-[10px]">Men’s T-Shirts</p>
      <p class="font-medium sm:text-sm text-[10px]">Women’s Wear</p>
      <p class="font-medium sm:text-sm text-[10px]">Winter Collections</p>
      <p class="font-medium sm:text-sm text-[10px]">Hooded T-Shirts</p>
      <p class="font-medium sm:text-sm text-[10px]">Streetwear Collections</p>
    </div>
    </div>
    <div class="w-[24%]">
      <div class="text-[#770015] font-playfair font-semibold sm:text-lg text-xs pb-4">
        CUSTOMER POLICIES
      </div>
      <div class="py-2 fonts grid grid-flow-row sm:gap-y-4 gap-y-2">
      <p class="font-medium sm:text-sm text-[10px]">About Us</p>
      <p class="font-medium sm:text-sm text-[10px]">Terms & Conditions</p>
      <p class="font-medium sm:text-sm text-[10px]">Shipping & Returns Policy</p>
      <p class="font-medium sm:text-sm text-[10px]">Cancellation & Refund Policy</p>
      <p class="font-medium sm:text-sm text-[10px]">Contact Us</p>
    </div>
    </div>
    <div class="w-[24%]">
      <div class="text-[#770015] font-playfair font-semibold sm:text-lg text-xs pb-4">
        STORE INFORMATION
      </div>
      <div class="py-2 fonts grid grid-flow-row sm:gap-y-4 gap-y-2">
      <p class="font-medium sm:text-sm text-[10px]">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry.
      </p>
      <p class="font-medium sm:text-sm text-[10px]">Call Us: 1234567890</p>
      <p class="font-medium sm:text-sm text-[10px]">Email Us: info@yourmail.com</p>
    </div>
    </div>
  </div>
  <div class="bg-[#20050A] fonts text-center font-medium sm:text-sm text-[10px] text-white sm:py-4 py-2">©2022-23 Powered By dummy team</div>
  </div>
</template>

<script setup>
import Facebook from "./Icons/Facebook.vue";
import Twitter from "./Icons/Twitter.vue";
import Instagram from "./Icons/Instagram.vue";
import LinkedIn from "./Icons/LinkedIn.vue";
import Interest from "./Icons/Interest.vue";
</script>

<style scoped>
.fonts{
    font-family: 'Montserrat', sans-serif;
    }
.font-playfair{
  font-family: "Playfair Display", sans-serif;
}    
</style>
