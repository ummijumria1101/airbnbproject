<template>
    <div class="flex border-2 h-[81px] items-center justify-between">
        <img src="/img/airbnbpinklogo.png" class="h-[81px] w-auto items-center">
        <div class="w-[352px] h-[48px] rounded-3xl border-2">

        </div>
        <div class="flex gap-2 items-center pr-[10px]">
            <p class="font-bold">Become a Host</p>
            <img src="/img/globe.png" class="h-[16px] w[16px]">
            <div class="w-[81px] h-[38px] rounded-3xl border-2">

            </div>
        </div>
    </div>
    <!-- list produk category -->
    <div>
        <ul id="categories-list"></ul>
        <div id="products-container"></div>
        <div class="flex p-2 ml-[80px] gap-[20px]">
            <div class="items-center" >
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10 justify-center">
                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                </svg>

                <p class="text-gray-700 text-xs">smartphones</p>
            </div>
            <div class="items-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10 justify-center">
                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                </svg>

                <p class="text-gray-700 text-xs">laptops</p>
            </div>
            <div class="items-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10 justify-center">
                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                </svg>

                <p class="text-gray-700 text-xs">fragnances</p>
            </div>
            <div class="items-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10 justify-center">
                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                </svg>

                <p class="text-gray-700 text-xs">skincare</p>
            </div>

        </div>

    </div>
    
        <div class="grid lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 xs:grid-cols-1 ml-[80px] mr-[80px] mt-[50px] gap-[8px] overflow-hidden">
        <div class="" v-for="barang in product.products" :key="barang.id">
                    <NuxtLink :to="`${barang.id}`">
                        <div>
                            <div>
                                <img :src="barang.thumbnail" class="w-auto h-[240px]  rounded-md">
                            </div>
                            <div>
                                <p class="text-[16px] p-[1px] text-gray-600 font-bold mt-1">{{ barang.title }}</p>                                       
                                <p class="text-[10px] text-px-[3px] text-justify">${{ barang.description }}</p>
                                <p class="text-[14px] text-start text-gray-600 font-bold">${{ barang.price }}</p>
                            </div>
                        </div>
                    </NuxtLink>
                          
        </div>
    </div>
    
</template>

<script setup>
const { data: product } = await useFetch('https://dummyjson.com/products')



</script>

<style lang="" scoped>

</style>