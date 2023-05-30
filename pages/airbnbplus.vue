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
    <div class="grid lg:grid-cols-6 md:grid-cols-3 sm:grid-cols-2 xs:grid-cols-1 ml-[80px] mr-[80px] mt-[50px] gap-[8px] overflow-hidden">
        <div class="" v-for="barang in contoh.products" :key="barang.id">
                        <div>
                            <div>
                                <img :src="barang.thumbnail" class="w-[188px] h-[240px] rounded-md">
                            </div>
                            <div>
                                <p class="text-[16px] p-[1px] text-gray-600 font-bold mt-1">{{ barang.title }}</p>                                       
                                <p class="text-[10px] text-px-[3px] text-justify">${{ barang.description }}</p>
                                <p class="text-[14px] text-start text-gray-600 font-bold">${{ barang.price }}</p>
                            </div>
                        </div>  
        </div>
    </div>
</template>

<script setup>
const { data: contoh } = await useFetch('https://dummyjson.com/products')
</script>

<style lang="" scoped>

</style>