<template>
    <section>
        <div class="fonts flex justify-between bg-gray-800 px-3 py-2 sm:px-28">
            <div class="text-white font-medium sm:text-sm text-xs">Welcome to Our Store Hiscraves</div>
            <div class="flex sm:space-x-2 space-x-1">
                <Call/>
                <div class="text-white font-medium sm:text-sm text-xs">Call Us: 1234567890</div>
            </div>
        </div>
    </section>
</template>

<script setup>
import Call from './Icons/Call.vue'
</script>
<style scoped>
.fonts{
    font-family: 'Montserrat', sans-serif;
    }   
</style>
