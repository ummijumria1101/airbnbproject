<template>
    <div >
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
        </svg>
        <NuxtLink to="" class="flex items-center gap-1 hover:text-slate-800">
                {{ category }}
        </NuxtLink>
        </div>
        <!-- <p class="text-gray-600 text-xs">{{ category }}</p> -->
        <div  v-for="cat in product.products" :key="cat.id">
            <div>
                <img :src="cat.thumbnail" class="w-auto h-[240px]  rounded-md">
            </div>
                <div>
                                <!-- <p class="text-[16px] p-[1px] text-gray-600 font-bold mt-1">{{ item.title }}</p>                                       
                                <p class="text-[10px] text-px-[3px] text-justify">${{ item.description }}</p>
                                <p class="text-[14px] text-start text-gray-600 font-bold">${{ item.price }}</p> -->
                </div>
            </div>
</template>

<script setup>
    const { category } = useRoute().params;
    const uri = 'https://dummyjson.com/products/category/' + category;

    // fetch
    const { data: product } = await useFetch(uri);

</script>

<style lang="scss" scoped>

</style>