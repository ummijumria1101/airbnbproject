<template>
    <div class="flex ml-[80px] mr-[80px] mt-[10px] items-center overflow-x-scroll gap-4">
            <NuxtLink v-for="category in product" :key="category.id"  :to="`/categories/cat/` + category" class="flex  gap-4" >
                <div class="justify-center place-content-center">      
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                    </svg>
                    <div class="text-gray-600 text-xs">{{ category }}</div>
                </div> 
            </NuxtLink>   
    </div>
</template>

<script setup>
const { data: product } = await useFetch('https://dummyjson.com/products/categories');

</script>

<style lang="scss" scoped>

</style>