<template>
<div class="sm:px-28 px-3 sm:pt-10 pt-6">
  <div class="grid sm:grid-cols-3 grid-cols-2 sm:gap-4 gap-2">
    <div v-for="(item, index) in collection" :key="index">
      <img :src="item.img" alt="" class="w-full" />
      <div class="fonts text-center font-semibold sm:text-xl text-sm sm:py-5 py-3 backdrop-blur relative sm:bottom-16 bottom-10 text-white">
        {{ item.label }}
      </div>
    </div>
  </div>
  </div>
</template>

<script setup>
import image17 from "./Images/image17.png";
import image18 from "./Images/image18.png";
import image19 from "./Images/image19.png";
import image20 from "./Images/image20.png";
import image21 from "./Images/image21.png";
import image22 from "./Images/image22.png";

const collection = [
  {
    img: image17,
    label: "Streetwear Collections",
  },
  {
    img: image18,
    label: "Striped T-Shirts",
  },
  {
    img: image19,
    label: "Round Neck T-Shirts",
  },
  {
    img: image20,
    label: "Printed T-Shirts",
  },
  {
    img: image21,
    label: "Oversized T-Shirts",
  },
  {
    img: image22,
    label: "Half Sleeves T-Shirts",
  },
];
</script>

<style scoped>
.fonts {
  font-family: "Playfair Display", serif;
}
</style>
