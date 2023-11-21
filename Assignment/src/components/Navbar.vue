<template>
    <div class="flex justify-between sm:px-28 px-3 sm:py-4 py-2 shadow">
        <Hamburger/>
        <Logo/>
        <div class="flex sm:space-x-6 space-x-2">
            <Search/>
            <Favourite/>
            <Bag/>
            <User/>
        </div>
    </div>
</template>

<script setup>
import Hamburger from './Icons/hambergur.vue'
import Search from './Icons/Search.vue'
import Favourite from './Icons/Favourite.vue'
import Bag from './Icons/Bag.vue'
import User from './Icons/User.vue'
import Logo from './Icons/Logo.vue'
</script>
