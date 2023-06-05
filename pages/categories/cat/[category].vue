<template>
    <div >
        <div class="flex m-5 gap-2 items-center">
            <NuxtLink to="/">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
        </svg>
            </NuxtLink>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
  <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
</svg>

        <NuxtLink to="" class="flex items-center gap-1 hover:text-slate-800">
                {{ category }}
        </NuxtLink>
        </div>
        </div> 
        <!-- <p class="text-gray-600 text-xs">{{ category }}</p> -->
        <div class="grid lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 xs:grid-cols-1 ml-[80px] mr-[80px] mt-[50px] gap-[8px] overflow-hidden">
            <NuxtLink :to="`/` + cat.id" v-for="cat in product.products" :key="cat.id">
                <div>
                    <img :src="cat.thumbnail" class="w-auto h-[240px]  rounded-md justify-center">
                    <p class="text-[16px] p-[1px] text-gray-600 font-bold mt-1">{{ cat.title }}</p>                                       
                    <p class="text-[10px] text-px-[3px] text-justify overflow-y-auto px-2">${{ cat.description }}</p>
                        <p class="text-[14px] text-start text-gray-600 font-bold">${{ cat.price }}</p>
            </div>

            </NuxtLink>
            <div  >
            
            
        </div>
        </div>
</template>

<script setup>
    const { category } = useRoute().params;
    const uri = 'https://dummyjson.com/products/category/' + category;

    // fetch
    const { data: product } = await useFetch(uri);

    const { data: productt } = await useFetch('https://dummyjson.com/products')


</script>

<style lang="scss" scoped>

</style>