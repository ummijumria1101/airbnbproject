<template>
    <div>
        <div class="rounded-3xl border-2 justify-between items-center px-3 py-2">
            <input class="outline-none gap-2" placeholder="search" type="text" v-model="search">
            <button class="bg-pink-600 p-2 text-white rounded-2xl" type="submit"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-3 h-3">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                </svg>
            </button>

        </div>

    </div>
</template>

<script setup>
const { data: product } = await useFetch('https://dummyjson.com/products/search?q=phone')

</script>

<style scoped>

</style>