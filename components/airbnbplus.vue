<template>
    <div class="flex border-b-2 h-[81px] items-center justify-between sticky top-0 bg-white">
        <img src="/img/airbnbpinklogo.png" class="h-[81px] w-auto items-center">

        <!-- fitur search -->
        <search />
        
        <div class="flex gap-2 items-center pr-[10px]">
            <p class="font-bold">Become a Host</p>
            <img src="/img/globe.png" class="h-[16px] w[16px]">
            <div class="w-[81px] h-[38px] rounded-3xl border-2">

            </div>
        </div>
    </div>
    <!-- list produk category -->
    <div class="flex justify-center">
        <Category />
    </div>

    

    
        <div class="grid lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 xs:grid-cols-1 ml-[80px] mr-[80px] mt-[50px] gap-[8px] overflow-hidden">
        <div class="" v-for="item in product.products" :key="item.id">
                    <NuxtLink :to="`` + item.id">
                        <div>
                            <div>
                                <img :src="item.thumbnail" class="w-auto h-[240px]  rounded-md">
                            </div>
                            <div>
                                <p class="text-[16px] p-[1px] text-gray-600 font-bold mt-1">{{ item.title }}</p>                                       
                                <p class="text-[10px] text-px-[3px] text-justify">${{ item.description }}</p>
                                <p class="text-[14px] text-start text-gray-600 font-bold">${{ item.price }}</p>
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