<template>
    <div class="bg-[#F5F4F2]">
        <div class="sm:px-52 px-6 sm:py-12 py-7 flex">
            <div class="mx-auto">
                <Return class="mx-auto"/>
                <p class="fonts sm:text-base text-xs font-medium sm:pt-4 pt-2">7 Days Return</p>
            </div>
            <div class="bg-pink-200 w-0.5 h-28 m-auto mx-auto"></div>
            <div class="mx-auto">
                <Batch class="mx-auto"/>
                <p class="fonts sm:text-base text-xs font-medium sm:pt-4 pt-2">Quality Products</p>
            </div>
            <div class="bg-pink-200 w-0.5 h-28 m-auto mx-auto"></div>
            <div class="mx-auto">
                <Payment class="mx-auto"/>
                <p class="fonts sm:text-base text-xs font-medium sm:pt-4 pt-2">Safe Payment</p>
            </div>
            <div class="bg-pink-200 w-0.5 h-28 m-auto mx-auto"></div>
            <div class="mx-auto">
                <Helpline class="mx-auto"/>
                <p class="fonts sm:text-base text-xs font-medium sm:pt-4 pt-2">24x7 Helpline</p>
            </div>
        </div>
    </div>
</template>

<script setup>
import Return from './Icons/Return.vue'
import Batch from './Icons/Batch.vue'
import Payment from './Icons/Payment.vue'
import Helpline from './Icons/Helpline.vue' 
</script>

<style scoped>
.fonts{
    font-family: 'Montserrat', sans-serif;}
</style>